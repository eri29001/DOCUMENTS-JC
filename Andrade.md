Nombre del proyecto Scratch: App de Actividad Física con Filtros
Hecho por: Gemma

Descripción:El bloque de código implementa el motor de búsqueda y filtrado por tipo de deporte dentro de la aplicación móvil de actividad física. Su objetivo es clasificar las preferencias del usuario para dirigirlo de forma automatizada hacia el grupo o comunidad deportiva correspondiente a su elección.
Flujo principal:
El flujo de búsqueda se activa cuando el usuario interactúa directamente haciendo clic sobre el botón o personaje del asistente de la aplicación. El sistema solicita al usuario definir su preferencia mediante una casilla de texto con las opciones "correr" o "bicicleta".
Si sí: Si la respuesta ingresada coincide exactamente con el término "Correr", la aplicación simula un proceso de carga de datos y le asigna en pantalla el "Grupo para correr".Si no: Si la respuesta es distinta a "Correr" (asumiendo de forma predeterminada la opción de bicicleta), el sistema procesa la búsqueda de igual manera y despliega la opción de "Grupo para andar en bici".💻 Pseudocódigo:textAl hacer clic en este objeto:
    PREGUNTAR: "¿Qué deporte buscas (correr o bicicleta)?" y esperar respuesta

Pseudocódigo:
    if respuesta == "Correr":
        print("Grupo para correr")
    if not:
        print( "Grupo para andar en bici")
    FIN SI

    SCRATCH:
    <img width="4032" height="3024" alt="8A8F7C78-5A64-4712-8222-5E9EFD9A4C98" src="https://github.com/user-attachments/assets/e36d9a85-7d52-43c7-8510-de64e914ad14" />
