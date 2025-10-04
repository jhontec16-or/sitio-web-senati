# sitio-web-senati
Sitio Web Educativo SENATI — Guía para el PDF
Autores:Jesus Kaled HuamanVasquez , Jhon Piero Ordinola Peña
Curso : FULLSTACK DEVELOPER SOFTWARE- 
Fecha: [04/10/2025]
 Repositorio/github : https://github.com/praditonet/web_senati.git 
			https://praditonet.github.io/web_senati/
________________________________________

Pasos a seguir
Teníamos que tener instalado Node.js  para poder crear nuestro proyecto con Vite:
Comandos :
 npm create vite@latest senati-web -- --template react
cd senati-web

luego teníamos que estructurar el proyecto:
						Creación de componentes principales
•	Navbar.jsx: barra de navegación con menú responsive.
•	Footer.jsx: pie de página con información institucional.
•	Home.jsx: página inicial con contador de visitas.
•	Cursos.jsx: muestra los cursos y permite buscar y filtrar.
•	DetalleCurso.jsx: vista individual de cada curso.
•	Contacto.jsx: formulario de contacto con validaciones.



Luego tenemos Validación del formulario.
Se controla manualmente cada campo con useState.
•	Nombre y Apellido: requeridos, 3 a 50 caracteres.
•	Email: formato válido.
•	Teléfono: 9 dígitos.
•	Carrera: obligatorio seleccionar.
•	Mensaje: mínimo 10 y máximo 500 caracteres.
•	Términos: debe estar marcado

Realizamos Contador de visitas
En la página principal se usa useEffect con sessionStorage para contar las visitas del usuario durante su sesión.


 






• Búsqueda y filtros de cursos
Se puede buscar por nombre o filtrar por categoría. El código recorre el arreglo cursosData y muestra solo los resultados que coinciden.
Diseño responsive
Los estilos se aplican con CSS-in-JS. El sitio se adapta a:
•	celulares: menos de 768px.
•	Tablet: entre 768px y 1024px.
•	computadora: más de 1024px.

Ejecución y pruebas del proyecto
Instala dependencias y ejecuta el servidor de desarrollo:
 
•  Resumen del Proyecto
En este proyecto desarrollé una página web educativa para SENATI usando React y Vite. El objetivo fue crear un sitio moderno, fácil de usar y sin recargas al navegar, ya que está hecho como una Single Page Application (SPA).
La web tiene varias secciones:
•	En Inicio, se muestra una bienvenida con un contador de visitas que aumenta cada vez que el usuario entra.
•	En Cursos, se pueden ver todos los cursos disponibles, buscar por nombre y filtrar por categoría.
•	En Detalle del Curso, aparece la información completa de cada curso.
•	En Contacto, hay un formulario validado donde el usuario puede enviar sus datos y un mensaje.
También hice que el sitio sea responsive, para que se vea bien tanto en celulares como en computadoras.
.

