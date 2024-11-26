# Guia de Javascript for dummies, como tu y como yo


<img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHVyY3UwYTRnZGwzdHFpeHR6Yndkbnpob2g5ZjBsdHIyMjlvOWp4dSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/iIqmM5tTjmpOB9mpbn/giphy.gif" width='250'>

<h2>Que es Javascript?</h2>
<p>Javascript es un lenguaje de programacion usado mayormente para el desarrollo web, que permite crear paginas web interactivas y dinamicas. Fue creado por Netscape como un recurso dinamico para agregar funcionalidad a los sitios web, se ha convertido en uno de los lenguajes mas usados en la web hasta el dia de hoy, segun copilot el 98% de las paginas web estan desarrolladas con Javascript. </p>
<p>Primero lo primero, ya dijimos que js te permite hacer muchas cosas para hacer mas interactiva una pagina web, como conectar otros servidores, que las paginas sean mas interactivas, agregar movimiento a recursos,entre otras cosas. Siempre y cuando tu le hables al lenguaje de programacion con los conceptos correctos, podemos hacer que javascript elimine datos,los cambie de lugar, los sume, los guarde, entre muchas cosas.Lo que nos lleva a nuestro primer punto </p>
<h3>Indice</H3>

<h1>Datos</h1>
<p>Los datos son entradas de caracteres(letras,numeros o simbolos) que tienes que especificar por categoria que van a ser ingresados, para que js pueda entender que tipo de dato vas a querer que el manipule, y estan divididos en 2 tipos </p>
<img src="https://www.cursosgis.com/wp-content/uploads/javascript-data-types-primitive-and-non-primitive.png" width='800'>
<h1>Datos Primitivos</h1>
<dt><h3>Boolean:</h3> 
  <p>Con este valor tu vas a poder ingresar dos entradas de texto uno lo va a tomar como verdadero y el otro como falso.Puede tener uno de dos valores: true (verdadero) o false (falso). Los booleanos se utilizan para realizar decisiones lógicas en el código. En este meme de codecademy se muestra un ejemplo IF: para ingresar la primera opcion que seria si hay bugs(errores en el codigo) odio programar, ELSE, si no es la primer opcion, entonces amo programar </p></dt>
  <img src="https://global.discourse-cdn.com/codecademy/original/5X/2/b/8/1/2b81676be890f64cf54382f56794378b21409f1a.jpeg" width='250'>

<p>Pero que pasa si hay mas de un if o entrada de datos que tienes que evaluar? supongamos que las respuestas que te de algun cliente en tu web puede tener distintas opciones, hasta un punto en el que se tienen mas de una opcion para la respuesta</p>
 <img src="https://codefinity-content-media-v2.s3.eu-west-1.amazonaws.com/courses/a5c23211-8dc2-4c4a-9a83-07a51e843ab6/section_1/TS_meme_10%404x.png" width='300'>
 <p>Seria un codigo muy cansado de escribir por todas las lineas que tendriamos que escribir una por una por tanto, cuando son varias las opciones que tienes que utilizar, en esos casos tienes que utilizar switch</p>
<img src="https://miro.medium.com/v2/resize:fit:1400/1*SiM_5c6wtpq-p7O-DvkQ4A.png" width='400'> 
<p>o usando objetos pero eso es algo que viene mas adelante</p>
  
<dt><h3>Fecha:</h3> 
  <p>Vas a poder ingresar un valor en el que js va a interpretar que contiene el día, el mes y el año. </p></dt>
  <img src="https://miro.medium.com/v2/resize:fit:1400/1*9lvHULUztfFsTPItRU2Y1Q.png" width='500'>
  
<dt><h3>Fecha y hora:</h3> 
  <p>Combina el tipo fecha y un valor que representa el tiempo transcurrido desde la medianoche. </p> </dt>
  <img src="https://phoenixnap.com/kb/wp-content/uploads/2023/12/get-full-time-and-date.png" width='500'>
  
  
  
<dt><h3>Number:</h3> <p>Un tipo de dato primitivo en JavaScript.</p> </dt>
  
<dt><h3>Entero:</h3> 
  <p>En terminos generales podriamos decir que es un dato que representa un número que no tiene decimales,aunque aqui podemos jugar un poco con temas que escribire mas adelante.Este tema son los metodos,pero no te adelantes tanto todavia, esto es solo para darte una introduccion de lo que veremos despues,</p>
  
  <p>Por ejemplo:</p>
  <p></p>Hay un tipo de metodo que se llama Number.isInteger() </p>
  
<p>Este método devuelve un booleano( el tipo de dato que mencionamos antes) que indica si un valor es un entero o no. </p>
  <p>Por ejemplo, </p>
  
  <p>    le indicamos a js   Number.isInteger (0) devuelve true, pero Number.isInteger(0.1) devuelve false.</p>
 <img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*Dso9OAkDSXp-pTDOeM5-SQ.png" width='500'>
  
<h3>BigInt</h3>
Este tipo de dato te permite representar números enteros de longitud arbitraria o si lo quieres decir mas simple(js va a interpretar que el numero que vas a ingresar es muy largo, largo,laargoooo). Para crear un valor BigInt, se agrega n al final de un entero. Por ejemplo, const bigInt = 1234567890123456789012345678901234567890n.para que el sistema sepa que va a ser un numerote el que vas a ingresar  
</p></dt>
<p>Y si eres como yo y te preguntas antes de saber el resto del lenguaje, para que querria yo utilizar un numero tan gigante si todo puede ser simple con alguna herremienta que ya este en 2024, bueno pues segun copilot( y yo siempre le creo a copilot), en 2024 BigInt sigue siendo una herramienta valiosa en JavaScript para manejar números enteros extremadamente grandes con precisión. Aquí te dejo algunos usos destacados de BigInt en este año:</p>
<li>Cálculos Financieros: En aplicaciones financieras donde la precisión es crucial, BigInt se utiliza para realizar cálculos exactos sin riesgo de pérdida de precisión3.</li>

<li>Criptografía: BigInt es esencial en la implementación de algoritmos criptográficos que requieren operaciones con números enteros muy grandes3.</li>

<li>Simulaciones y Modelos Matemáticos: En simulaciones científicas y modelos matemáticos que involucran números grandes, BigInt permite realizar cálculos precisos y eficientes3.</li>

<li>Gestión de Identificadores Únicos: En sistemas que requieren identificadores únicos y grandes, como bases de datos distribuidas, BigInt se utiliza para generar y manejar estos identificadores.</li>

<li>Desarrollo de Juegos: En juegos que requieren cálculos precisos con números grandes, como juegos de estrategia o simulaciones, BigInt es una herramienta útil.</li>

<dt><h3>Real:</h3> <p>Puede contener valores decimales además de enteros.</p> </dt>
<p>BigInt ha mejorado la capacidad de JavaScript para manejar números grandes de manera eficiente y precisa, lo que lo hace indispensable para ciertos tipos de aplicaciones y proyectos en 2024.</p>

<p>Aun asi, existen librerias que ya hacen uso de bigint con una combinacion de metodos para poder utilizar el bigint BigInteger.js. Una libreria que nos ayudara mas tarde  </p>
<img src="https://uploads.dailydot.com/834/8b/468b7dd539258655.jpg?q=65&auto=format&w=1600&ar=2:1&fit=crop" width='500'>


<dt><h3>String:</h3> Un string (o cadena de caracteres)es la manera en que vas a poder representar texto en JavaScript, los strings se utilizan para almacenar y manipular texto y pueden incluir letras, números, símbolos y espacios.</dt>

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240119115020/JavaScript-strings.webp" width='500'>

<dt><h3>Symbol:</h3> <p>Los símbolos son utilizados principalmente para crear identificadores únicos que no pueden ser accidentalmente duplicados, lo que los hace especialmente útiles para definir propiedades de objetos(que veremos mas adelante y  que no colisionen con otras propiedades.)Al utilizar Symbols, puedes evitar que las propiedades de los objetos entren en conflicto, especialmente en grandes proyectos o cuando se utilizan librerías de terceros, tambien ayudan a ocultar Propiedades: Las propiedades de los objetos definidas usando Symbols no aparecen en iteraciones normales, lo que permite ocultar ciertas propiedades cuando no son necesarias.</p>
<img src="https://miro.medium.com/v2/resize:fit:1400/1*Z0WsWHIAGlWKG1guLz-32Q.png" width='500'>

  
  <p>
   
  </p>
<p> </p></dt>
<dt><h3>Undefined:</h3> <p> Tipo de dato que se usa para indicar la ausencia de un valor asignado a una variable. Es una señal de que una variable ha sido declarada pero no se le ha asignado ningún valor.Lo puedes utilizar cuando no sabes que tipo de informacion habra dentro de una variable(no te desesperes que veremos lo que es una variable) solo digamos que sabes que vas a guardar algun dato pero no sabes exactamente que tipo de dato es </p> 

<img src="https://debugmode.net/wp-content/uploads/2017/03/image18.png" width='500'></dt> 
<dt><h3>Null:</h3> <p>Es un tipo de dato primitivo que se usa para representar la ausencia intencional de cualquier objeto o valor. Es un valor especial que indica que una variable no tiene ningún valor asignado, a diferencia de undefined, que indica que una variable ha sido declarada pero no se le ha asignado un valor. </p></dt>
<p>Aqui una comparativa de ambos datos</p>
<img src="https://codingnomads.com/images/ef21dcae-9744-4bbe-fe90-8546f7f27700/public" width='500'></dt> 


<table>
  <tr>
    <th>Caracteristica</th>
    <th>Undefined</th>
    <th>Null</th>
  </tr>
  <tr>
    <td>Definicion</td>
    <td>Variable declarada pero no inicializada</td>
    <td>Ausencia intencional de valor</td>
  </tr>
  <tr>
    <td>Asignacion</td>
    <td>Automatica</td>
    <td>Intencional</td>
  </tr>
</table>
<H2>Ahora vamos con los compuestos o no primitivos </H2> 
<h1>Datos Compuestos</h1>
<h2>Objects</h2>
<p>Un objeto en JavaScript es una colección de propiedades, donde cada propiedad es una asociación entre una clave (llamada "nombre" o "clave") y un valor. Los objetos pueden contener muchos valores de diferentes tipos y son fundamentales para la programación en JavaScript.</p>
<p> Por ejemplo:</p>
<p> Si tomaramos como objeto a una persona, esa persona tendria mas caracteristicas o varias propiedades:</p>

<p>nombre: una cadena de texto que representa el nombre de la persona.</p>

<p>edad: un número que representa la edad de la persona.</p>

<p>profesion: una cadena de texto que representa la profesión de la persona.</p>

<p>saludar: un método (función) que imprime un saludo en la consola.</p>

<p>actualizar Edad: un método que actualiza la edad de la persona.</p>










