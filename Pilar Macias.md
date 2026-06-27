LOGICA DEL NEGOCIO: 
Nombre del proyecto Scratch: IA Chatbot generadora de ciencia ficción
Hecho por: Pilar Macías
Descripción:
El bloque de código controla la fase inicial de autenticación del usuario dentro de la interfaz del Chatbot de ciencia ficción. Su objetivo es validar mediante una pregunta interactiva si el usuario ya posee una sesión activa para personalizar el saludo de bienvenida o, en su defecto, invitarlo a registrarse antes de generar historias.
Flujo principal:
Si sí: Si el usuario responde exactamente "si", el Chatbot valida el ingreso exitoso, da una bienvenida personalizada incluyendo el nombre de usuario y le ofrece continuar con la experiencia.Si no: Si el usuario responde cualquier otra cosa (como "no"), el sistema identifica que no hay credenciales activas, muestra un saludo general e indica las instrucciones para crear una cuenta nueva en la plataforma de IA.
Si sí:

Pseudocódigo:
usuario_answer= input('¿Estas logeado  (si/no'?) #Solo se responde si  y no
If usuario_answer == 'Si':
  Se imprime la opción que muestra los datos guardados en el usuario y se da atención personalizada.

Si no:
If usuario_answer== 'No':
 El chatbot sugiere iniciar sesión y avisa que no se guardan los datos.

Simulación de scratch:
![Uploading Captura.ScratchAme.PNG…]()

