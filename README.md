El componente muestra una tabla interactiva con los detalles de los usuarios (ID, nombre, correo y rol). Utiliza Angular para gestionar datos dinámicos, Bootstrap para el diseño responsivo y ngx-pagination para la funcionalidad de paginación.

1.1 Archivos que se modificaron para la actividad
user-list.component.html: Contiene la estructura HTML de la tabla y la paginación.
user-list.component.ts: Gestiona la lógica del componente y la interacción con el servicio de usuarios.
user-list.component.css: Incluye los estilos personalizados.
app.module.ts: Importa y configura los módulos necesarios, como HttpClientModule y NgxPaginationModule.

user-list.component.html

![imagen_2024-11-15_023413255](https://github.com/user-attachments/assets/9f06b249-7529-45be-a009-a2cc2796ffc7)

Este archivo define nuestra estructura visual, es decir lo que va a contener nuestra pagina


user-list.component.ts

![image](https://github.com/user-attachments/assets/a6691868-11ee-4920-a81e-e6894a06c49d)

Este archivo gestiona los datos de los usuarios


user-list.component.css

![image](https://github.com/user-attachments/assets/9ad66e1c-9a08-4f32-b1e1-30f6a82f8055)

esta parte se encarga de darle diseño a la pagina como cambiar una fuente, color o estilo de esta misma


app.module.ts

![image](https://github.com/user-attachments/assets/02b292c3-5177-4f0d-bd1c-76d888085084)

En este archivo el modulo principal incluye las dependencias necesarias


Concluison

Este proyecto se me hizo muy bueno para el aprendiazaje de angular , dentro de este proyecto se presenta un diseño moderno, una tabla interactiva y una funcionalidad de paginación. Esta tabla es ideal para poder controlar la visualizacion de los datos ya que facilita al usuario ver mejor el contenido, ademas de que le agrega una mejor estetica al proyecto.

Al final la practica queda de esta manera

![image](https://github.com/user-attachments/assets/423e25c9-a3f3-4afe-8e3b-db28ac43b204)
