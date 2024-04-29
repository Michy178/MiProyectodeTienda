# MiProyectodeTienda
views/: Contiene las plantillas HTML para renderizar la interfaz de usuario. Están organizadas por controlador para mantener la estructura limpia.
La carpeta public/ es la carpeta raíz del servidor web.
assets/: Contiene archivos estáticos como CSS, JavaScript e imágenes.
index.php: Punto de entrada de la aplicación que dirige las solicitudes a los controladores.
La carpeta config/ contiene archivos de configuración.
routes.php: Define las rutas de la aplicación, asociando URLs con controladores y acciones.
 Un ejemplo de la programación con php utilizando este modelo de negocio cada parte de cada carpeta queda así:
Controlador:
 
Modelo:
 

Vista:
 
Index:
  
Ventajas del MVC:
Separación de preocupaciones:
MVC divide la aplicación en componentes ya que ocupan de aspectos específicos, lo que facilita la comprensión y el mantenimiento del código. Cada componente tiene una responsabilidad clara y definida, lo que facilita la colaboración en equipos de desarrollo.
Reutilización de código:
Al separar la lógica de negocio de la presentación, es más fácil reutilizar componentes en diferentes partes de la aplicación o en diferentes aplicaciones. Por ejemplo, el mismo Modelo puede ser utilizado por diferentes Vistas con distintas interfaces de usuario.

Facilita las pruebas:
La separación de la lógica de negocio del código de presentación hace que sea más fácil probar cada componente por separado. Los modelos pueden ser probados independientemente de las vistas y los controladores, lo que facilita la escritura de pruebas unitarias y la detección de errores.
Flexibilidad y escalabilidad:
MVC facilita la evolución y la expansión de una aplicación a medida que los requisitos cambian o crecen. Los cambios en la interfaz de usuario no afectan al modelo subyacente, lo que permite realizar modificaciones con menor impacto en el resto del sistema.
En este diagrama contiene tres clases, controlador, modelo y vista con las relaciones de uso que existen entre ellas. El controlador usa los modelos y las vistas y las vistas usan los modelos. Generalmente el controlador trabajará con los modelos de la aplicación, seleccionando aquellos datos que requiere la vista. Entonces el controlador usa la vista para generar la salida, enviando los modelos adecuados a la vista para que pinte los datos que necesite en la salida al usuario.

Conclusión

En conclusión, el patrón Modelo-Vista-Controlador (MVC) es una herramienta importante en el desarrollo de software, brindando un enfoque sólido y adaptable para la creación de aplicaciones que perduren en el tiempo. Al estructurar las áreas de preocupación relacionadas con la lógica de negocio, la presentación de datos y la interacción del usuario, MVC establece un estándar de calidad que sigue siendo relevante en el cambiante paisaje tecnológico actual.
MVC ofrece una estructura organizada y modular para la construcción de aplicaciones, fomentando la separación de responsabilidades y simplificando tanto el mantenimiento como la evolución del software. Al descomponer la aplicación en tres componentes discretos, este patrón optimiza la claridad del código, promueve la reutilización de componentes y potencia la escalabilidad del sistema. Su adopción es ampliamente recomendada en el ámbito del desarrollo de aplicaciones web y de escritorio, contribuyendo así a la creación de una arquitectura resistente y fácil de gestionar.
Otro aspecto importante del MVC es su capacidad para adaptarse a diferentes tecnologías y plataformas. Aunque el patrón se originó en el contexto del desarrollo web, su filosofía de separación de preocupaciones y su enfoque en el modularidad lo hacen igualmente aplicable al desarrollo de aplicaciones de escritorio, móviles o incluso embebidas. Esto lo convierte en una opción versátil y duradera para una amplia gama de proyectos de software.
Referencias  
Qué es MVC. (s. f.). DesarrolloWeb.com.https://desarrolloweb.com/articulos/quees-
García, M. (2017, 5 octubre). MVC (Modelo-Vista-Controlador): ¿qué es y para qué sirve? https://codingornot.com/mvc-modelo-vista-controlador-que-es-y-para-que-sirve
Guía MVC (Model, View, Controller). (2023, 19 noviembre). DevCode Tutoriales. https://devcode.la/blog/guia-mvc-model-view-controller/
Rick-Anderson. (2023, 13 julio). ASP.NET introducción MVC. Microsoft Learn. https://learn.microsoft.com/es-es/aspnet/mvc/overview/getting-started/
Hernandez, R. D. (2021, 28 junio). El patrón modelo-vista-controlador:  Arquitectura y frameworks explicados. freeCodeCamp.org. https://www.freecodecamp.org/espanol/news/el-modelo-de-arquitectura-view-controller-pattern/
colaboradores de Wikipedia. (2023, 14 noviembre). Modelo–Vista–Controlador. Wikipedia, la Enciclopedia Libre. https://es.wikipedia.org/wiki/Modelo%E2%80%93vista%E2%80%93controlador
