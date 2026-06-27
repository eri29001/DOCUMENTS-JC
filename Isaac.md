Nombre del proyecto Scratch: Pastelería
Hecho por: Isaac

Descripción:
El bloque de código gestiona el proceso de compra de un producto dentro de la pastelería virtual. Su objetivo es validar si el cliente cuenta con el dinero suficiente para adquirir el pastel seleccionado y actualizar el inventario o saldo del juego de forma automática.

Flujo principal:
Si sí: El sistema descuenta el valor del pastel del dinero total del jugador, reproduce un sonido de éxito de compra y muestra un mensaje confirmando que el pedido está listo.
Si no: El sistema bloquea la transacción, emite un sonido de alerta y muestra un mensaje en pantalla indicando que los fondos son insuficientes para realizar la compra.

Pseucódigo

    respuesta: input("¿Deseas comprar este pastel?")

    if respuesta == "si":
        Dinero_Jugador >= Costo_Pastel:
            Dinero_Jugador = Dinero_Jugador - Costo_Pastel
            REPRODUCIR SONIDO: "Chime" o "Coin"
            print("¡Gracias por tu compra! Tu pastel está listo.")
        if respuesta== 'No':
            REPRODUCIR SONIDO: "Oops" o "Buzzer"
            print("No tienes suficiente dinero para este pastel.")
        
<img width="1362" height="645" alt="Captura de pantalla Ipin" src="https://github.com/user-attachments/assets/c224186d-5ecc-4f5e-9420-a482dd6c4699" /><img width="1366" height="640" alt="Captura de pantalla Ipin 2da parte" src="https://github.com/user-attachments/assets/1f0e1ddf-3274-4c46-9724-f7c1c2a1f438" />
