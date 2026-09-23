<img width="483" height="172" alt="image" src="https://github.com/user-attachments/assets/930be3bd-3947-4361-9eb8-a12c35d6bbd1" />David Córdoba Carreto
# JS desde cero en el navegador... antes que REACT.

El objetivo de esta práctica es crear un formulario básico en HTML y JavaScript que permita saludar a un usuario. Publicarlo en un repositorio de GitHub con GitHub Pages. Todo debes documentarlo con un pantallazo en este mismo archivo y personalizarlo con tu tus datos personales.

## Por qué REACT

- REACT es una biblioteca de JavaScript para construir interfaces de usuario.
- Es mantenida por Meta y una comunidad de desarrolladores.
- Permite construir componentes reutilizables.
- Es ampliamente utilizada en la industria, lo que la hace relevante para desarrolladores web.
- Aprender REACT abre oportunidades laborales y mejora las habilidades en desarrollo frontend.
- Cuenta con un ecosistema robusto, incluyendo herramientas como Redux para la gestión del estado y React Router para la navegación.
- Tiene un rendimiento optimizado gracias a su uso del Virtual DOM.
- Se sitúa como uno de los frameworks más populares en la actualidad. [State of JS 2023](https://2023.stateofjs.com/en-US/libraries/front-end-frameworks/)

## Por qué JavaScript antes de REACT
- REACT está construido sobre JavaScript, por lo que es esencial tener una buena comprensión de este lenguaje antes de aprender REACT.
- JavaScript es el lenguaje de programación principal para el desarrollo web frontend.

# ¿Qué es JavaScript?

JavaScript (JS) es un lenguaje de programación interpretado, ligero y multiplataforma, creado inicialmente para dotar de interactividad a las páginas web. Hoy en día, se utiliza tanto en el desarrollo frontend (navegadores) como en el backend (servidores, gracias a Node.js), aplicaciones móviles, de escritorio y más.

## Versiones
- **ECMAScript** es el estándar que define el lenguaje. Las versiones más importantes son:
  - **ES5 (2009):** Amplió la compatibilidad y funcionalidades.
  - **ES6/ES2015:** Introdujo let/const, arrow functions, clases, módulos, promesas, etc.
  - Desde 2015, cada año se publica una nueva versión con mejoras y nuevas características.

## Potencia
- Permite crear desde páginas web dinámicas hasta aplicaciones complejas, videojuegos, servidores, inteligencia artificial y más.
- Es asíncrono, flexible y tiene una enorme cantidad de librerías y frameworks (React, Angular, Vue, etc.).
- Es esencial para el desarrollo web y uno de los lenguajes más demandados en el mercado laboral.

---
## Parte 1: Instalación y configuración

1. **Instala Visual Studio Code**  
   Descarga e instala VS Code desde [code.visualstudio.com](https://code.visualstudio.com/).

## Parte 2: Primeros pasos con la consola del navegador

1. Abre tu navegador web (Chrome, Firefox, Edge, etc.).
2. Accede a cualquier página web y pulsa `F12` o `Ctrl+Shift+I` para abrir las herramientas de desarrollo.
3. Haz clic en la pestaña "Consola".
4. Prueba los siguientes comandos uno por uno y observa el resultado:
   ```js
   2 + 2
   console.log("¡Hola, mundo!")
   let nombre = "Anita"
   nombre
   ```

<img width="691" height="353" alt="image" src="https://github.com/user-attachments/assets/50bc871d-a819-4dea-b903-abc0e4d8c319" />


## Parte 3: Tu primer archivo HTML + JavaScript

1. Crea una carpeta llamada `00JSyEntorno` dentro de tu espacio de trabajo.
 <img width="1401" height="242" alt="image" src="https://github.com/user-attachments/assets/527d6775-0bcd-4ab2-92db-64e0ddb0debb" />
  
2. Dentro de esa carpeta, crea un archivo llamado `hola.html`.
3. Escribe el siguiente código en `hola.html`:
   ```html
   <!DOCTYPE html>
   <html lang="es">
   <head>
     <meta charset="UTF-8">
     <title>Hola JS</title>
   </head>
   <body>
     <script>
       console.log("¡Hola, mundo!");
       let nombre = "Ana";
       console.log("Bienvenida, " + nombre);
     </script>
   </body>
   </html>
   ```
   
   <img width="1367" height="397" alt="image" src="https://github.com/user-attachments/assets/b83ea712-7e89-4d59-ba8a-cb627254dfa3" />

5. Desde VSCode abre el archivo `hola.html` en tu navegador.
6. Observa el resultado en la consola del navegador.
<img width="850" height="57" alt="image" src="https://github.com/user-attachments/assets/a227146f-a02c-4052-be3a-3f18a9a08fdf" />


## Parte 4: Experimenta

- Cambia el valor de la variable `nombre` por el tuyo y recarga la página.
<img width="845" height="52" alt="image" src="https://github.com/user-attachments/assets/af45094c-b1f3-4696-afc6-fb392b42d567" />

- Añade una línea que sume dos números y muestre el resultado con `console.log`.
<img width="847" height="86" alt="image" src="https://github.com/user-attachments/assets/2c2622d1-b28d-4441-859f-2fade7f98d73" />

- Añade otra variable con tu apellido y muestra un saludo completo.
  <img width="852" height="86" alt="image" src="https://github.com/user-attachments/assets/66ce1d7e-0154-44a3-a4fc-cc2f575b1de6" />

- Modifica el saludo para que incluya el apellido en mayúsculas. Busca en la consola cómo convertir una cadena a mayúsculas. Para ello usa un literal de cadena (con tu nombre) seguido del operador punto (`.`)
  <img width="851" height="77" alt="image" src="https://github.com/user-attachments/assets/413347b0-c5b5-48a4-87bd-7e8c07e99be2" />

- Modifica el archivo para que el saludo se muestre en la página web en lugar de la consola. Usa `document.body.innerHTML` para esto:
   ```js
   document.body.innerHTML = "<h1>¡Hola, " + nombre + "!</h1>";
   ```
  <img width="1906" height="162" alt="image" src="https://github.com/user-attachments/assets/b8740330-3ed8-4717-9801-0fea40f903dc" />

- Publica tu proyecto en el repositorio de GitHub y usa GitHub Pages para alojarlo. Sigue [esta guía](https://docs.github.com/es/pages/getting-started-with-github-pages/creating-a-github-pages-site) para hacerlo.


## parte 5: formulario HTML + JavaScript
1. Crea un archivo llamado `formulario.html` en la misma carpeta `00JSyEntorno`.
2. Crea un archivo llamado `formulario.js` en la misma carpeta `00JSyEntorno`.
3. Escribe el siguiente código en `formulario.html`:
4. ```html
   <!DOCTYPE html>
   <html lang="es">
   <head>
     <meta charset="UTF-8">
     <title>Formulario de Saludo</title>
   </head>
   <body>
     <h1>Formulario de Saludo</h1>
     <form id="formulario">
       <label for="nombreInput">Nombre:</label>
       <input type="text" id="nombreInput" required>
       <button type="submit">Saludar</button>
     </form>
     <p id="salida"></p>
     
     <script src="formulario.js"></script>
   </body>
   </html>
   ```
5. Escribe el siguiente código en `formulario.js`:
   ```js
   document.addEventListener('DOMContentLoaded', function() {
     document.getElementById('formulario').addEventListener('submit', function(event) {
       event.preventDefault();
       const nombre = document.getElementById('nombreInput').value;
       document.getElementById('salida').textContent = '¡Hola, ' + nombre + '!';
     });
   });
   ```
6. Desde VSCode abre `formulario.html` en tu navegador y prueba el formulario.
   <img width="510" height="245" alt="image" src="https://github.com/user-attachments/assets/91b90a43-5aff-44d0-bdc2-884d38a2b0e5" />


   
## Parte 6: Preguntas de reflexión

1. ¿Qué hace `console.log`?

   Devuelve un valor en la consola del navegador.
   
2. ¿Qué ocurre si cambias el valor de la variable desde la consola? ¿Se puede?
   Se puede modificar, pero al no ser el valor original al recargar la página vuelve al original.
   
3. ¿Para qué sirve la consola del navegador en este contexto?
   Se suele utilizar como entorno de pruebas o debug.
   
4. Para qué sirve el archivo HTML en este contexto?
   Es la estructura de la página dónde se definen los elementos visuales, y se aloja el archivo JS en él.
   
5. ¿Por qué es una buena práctica separar el código JavaScript del HTML?
    Por fines de reutilización de código, limpieza y organización del mismo.
   
6. Por qué se llama Vanilla JavaScript?
    Porque es entendido por los navegadores de manera nativa, por eso se refiere como puro.
  
7. Cuándo se usa JavaScript puro y cuándo se usan frameworks o librerías como REACT?
    JS puro se utiliza en proyectos pequeños, de poca complejidad y de carga ligera.
    Como un Framework es una ayuda al programador, se utiliza en webs complejas o escalables, y facilita el dinamismo de la web.
    
8. Cómo se define una función en JS
    function nombre_funcion(atributo){
      return "Lo que quieras que devuelva";
    }
9. Sobre el código demuestra la diferencia entre let y const
    
    let declara una variable que se puede modificar.
    <img width="136" height="282" alt="image" src="https://github.com/user-attachments/assets/1abc4098-dbfc-42e3-ab8a-19f58dcecc0c" />

    Mientras que const, declara una constante la cual no se puede modificar
    <img width="483" height="172" alt="image" src="https://github.com/user-attachments/assets/1b1b632a-1437-483a-bfd6-69c197691a0b" />

10. Indica en el código:
   1. Si puede evitarse el uso de let. Qué hace
   2. Cuántos eventos hay en el código, cuáles son y para qué sirven



