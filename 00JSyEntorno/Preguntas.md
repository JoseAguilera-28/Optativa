### 1. ¿Qué hace `console.log`?

 Es una función de JavaScript que sirve para imprimir (mostrar) mensajes, variables o resultados de operaciones en la consola de las herramientas de desarrollo del navegador.

### 2. ¿Qué ocurre si cambias el valor de la variable desde la consola? ¿Se puede?

 Sí , si escribes el nombre de una variable declarada previamente y pulsas Enter en la consola, su valor cambiará temporalmente en la memoria del navegador. Pero este cambio no modifica tu archivo fuente original.

### 3. ¿Para qué sirve la consola del navegador en este contexto?

 La consola sirve como un entorno de pruebas. Permite ejecutar código JavaScript en tiempo real.

### 4. ¿Para qué sirve el archivo HTML en este contexto?

 El archivo HTML actúa como la estructura base de la aplicación.

### 5. ¿Por qué es una buena práctica separar el código JavaScript del HTML?

 - El código es más fácil de leer, organizar y corregir.
 - Puedes usar el mismo archivo JavaScript en múltiples archivos HTML.
 - El navegador puede guardar en caché el archivo `.js`, lo que acelera los tiempos de carga en visitas posteriores.

### 6. ¿Por qué se llama Vanilla JavaScript?

 Se utiliza en programación para referirse a JavaScript puro, es decir, el lenguaje base sin el uso de librerías, frameworks o complementos externos. 

### 7. ¿Cuándo se usa JavaScript puro y cuándo se usan frameworks o librerías como REACT?

 - JavaScript puro: Se recomienda para proyectos pequeños, scripts sencillos, manipulaciones básicas del DOM, prototipos rápidos o cuando el rendimiento y el peso mínimo de la página son prioridad absoluta.

 - Frameworks/Librerías: Se utilizan en aplicaciones web más complejas cuando hay muchos datos interactuando en tiempo real, cuando se trabaja en equipos grandes o cuando se necesita crear componentes reutilizables y un estado global de la aplicación.

### 8. ¿Cómo se define una función en JS? 

 En JavaScript hay varias formas de definir una función. Las dos más comunes son la declaración tradicional y la función de flecha.

### 9. Sobre el código demuestra la diferencia entre let y const
 
 La principal diferencia es que let permite reasignar el valor de la variable más adelante, mientras que const crea una constante cuyo valor no puede ser reasignado.

### 10. Indica en el código:
#### 10.1 Si puede evitarse el uso de let. Qué hace

 No se a que parte del codigo se refiere por que no hay ningun let, el let no se puede cambiar si la asignación se hace a una variable. Por el contrario si esa variable no va a cambiar, sí,  se evita su uso y se hace constante con CONST

#### 10.2 Cuántos eventos hay en el código, cuáles son y para qué sirven

 Hay dos eventos:

 - DOMContentLoaded: Se aplica al documento y sirve para que el código JavaScript espere a que toda la estructura del HTML esté completamente cargada en el navegador antes de intentar buscar el formulario.

 - submit: Se aplica al formulario (document.getElementById('formulario')). Sirve para detectar el momento exacto en que el usuario envía el formulario.