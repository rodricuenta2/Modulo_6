
1. ¿Qué es Django?
• ¿Qué tipo de framework es Django?

Es un framework de desarrollo web backend de código abierto, creado para el lenguaje de programación Python.

• ¿Qué tipo de aplicaciones permite construir?

Permite crear aplicaciones : plataformas de comercio electrónico, Sistemas de Gestión de Contenido, redes sociales y de streaming, APIS entre otros.

• Menciona al menos tres ventajas de usar Django sobre trabajar con Python puro para desarrollo web.

- Velocidad
- Seguridad
- Paneles de administracion

2. Entornos virtuales en Python
• ¿Qué es un entorno virtual en Python y para qué sirve?

Un entorno virtual es un espacio aislado e independiente dentro de tu computadora donde puedes instalar versiones específicas de Python y de sus librerías para un proyecto en particular

• ¿Qué ventajas tiene crear un entorno virtual para un proyecto Django?

- Aislamiento de dependencias ya que Evita conflictos de versiones entre librerías de diferentes proyectos.
- Orden ya que se puede generar un archivo requirements.txt limpio que contiene únicamente las librerías que ese proyecto Django necesita, facilitando que otra persona lo ejecute en su computadora.

• Explica en tus palabras qué hace el siguiente comando (no es necesario ejecutarlo):
 Python -m venv env
 Ejecutara un módulo interno de entornos virtuales y una carpeta con el nombre venv

 3. Estructura y diseño de Django
• ¿Qué es el patrón MVC y cómo se aplica en Django (MTV)?
El patrón MVC (Modelo-Vista-Controlador) es una arquitectura de software que separa los datos de una aplicación, la interfaz de usuario y la lógica de control.

Completa esta tabla comparativa:

Concepto tradicional (MVC)    Nombre en Django (MTV)       Función
Model                           Model                       Gestiona los datos y la lógica.
View                            Template                    Capa de presentacion, archivos HTML.
Controller                      View                        Logica que recibe peticion de usuario.


• ¿Qué es el enrutador de Django y qué papel cumple en una aplicación web?
Toma la direccion de pagina ingresada por usuario y si esta dentro de las creadas la dirije a las vistas(view)

4. Principios del desarrollo con Django
• ¿Qué significa el principio DRY ("Don't Repeat Yourself") y cómo lo aplica Django?

Es una filosofía de programación que dicta que cada pieza de conocimiento o lógica en un sistema debe tener una representación única y no duplicada.

• ¿Qué significa que Django tenga una “estructura flexible y minimalista”?

Indica que Django está compuesto por aplicaciones independientes (apps)

• ¿Qué son los Templates en Django y qué rol cumplen en la renderización de contenido?

Los Templates son archivos de texto (comúnmente HTML) que contienen la estructura visual de la página web, pero con superpoderes: incluyen el Lenguaje de Plantillas de Django (DTL).