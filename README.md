<h1 align="center"> Doctor Vet </h1>

![Esta es una imagen](https://user-images.githubusercontent.com/63665948/194942261-74a0897a-fd8d-4d80-9769-537eb5f5e519.png)


* Descripcion del Proyecto
  
  El desarrollo de la web que hicimos esta basada en mantener un historial de las mascotas que son atendidas en las diferentes veterinarias, poder consultar todos los  datos y el historial medico, asi el veterinario puede conocer y administrar la correcta medicina

 * Requerimientos
 
  Definimos 2 App para desarrollar el proyecto:
  - AppVet
  - Mensajeria
  
  Se definieron los siguientes modelos en cada App:
  - AppVet
    - DatosVeterinarios
    - DatosPropietario
    - DatosMascota
    - HistoriaClinica
    - Avatar
  
  - Mensajeria
    - Mensajeria
  
  Funcionalida de la App
  
  - Pagina principal: http://127.0.0.1:8000
    Dentro la pagina principar encontramos 3 secciones, que contienen informacion general sobre la veterinaria ( informacion que puede ser modificaca por el cliente a su criterio ). Estas secciones son : Inicio, sobre nosotros y servicios.
    
    ![image](https://user-images.githubusercontent.com/63665948/194943652-4416d2d0-fbd3-4f05-b24a-1efbefef546b.png)
    
   La pagina principal cuenta con un link de "iniciar session" que nos lleva a la pagina de inicio de la App.
   
   ![image](https://user-images.githubusercontent.com/63665948/194944009-88ced33c-662f-40c0-9c26-b164ae5839c1.png)

   
En esta pagina es posible iniciar session con un usuario registrado, registrar uno nuevo o volver a la pagina inicial.

Una vez iniciada la session (admin/admin), tenemos la posibilidad de navegar por las distintas paginas de la App:

 - Veterinarios
 - Historia Cinica
 - Cliente
 - Mascotas
 - Perfil
 - Inbox
 - Creadores
 - Admin
 

![image](https://user-images.githubusercontent.com/63665948/194945346-7944d917-e7d5-492d-9a54-cfe49de52140.png)

Descripcion de las sessiones:

- Veterinarios:
  - Agregar Veterinarios: En esta session podemos agregar un nuevo veterinario.
  - Buscar Veterinarios: en esta session se puede buscar un veterinario por nombre o listar todos los veterinarios cargados. Para cada veterinario es posible editar o eliminar el perfil.
  
- Cliente:
   - Agregar cliente: En esta session podemos agregar un nuevo Cliente.
   - Buscar Cliente: en esta session se puede buscar un cliente por nombre o listar todos los clientes cargados. Para cada cliente es posible editar o eliminar el perfil.

- Mascotas:
    - Agregar mascota: En esta session podemos agregar una nueva mascota. En el campo dueño de mascota se debe seleccionar el cliente agregado previamente.
    - Buscar mascota: en esta session se puede buscar una mascota por nombre o listar todos las mascotas cargadas. Para cada mascota es posible editar o eliminar el perfil.
    
- Historia Cinica:
    - Agregar Historia clinica: En esta session podemos asociar atravez del campo nombre de mascota una historia clinica a la respectiva mascota. En el campo veterinario  se debe seleccionar el veterinario agregado previamente.
    - Buscar Historia clinica: en esta session se pueden ver un resumen de las hostoria clinicas de las mascotas. Para cada ver la historia clinica completa se debe hacer click en el boton de la historia clinica. Tambien es posible eliminar la historia clinica.
    
- Perfil: En esta session es posible editar el perfil del usuario logueado.

- Inbox:
  - Ver mensajes: en esta session podemos ver todos los mensajes que recibio el usuario logueado y responderlos.
  - Enviar mensaje: en esta session se puede enviar un mensaje a los usuarios registrados. 




    
  
    
  
