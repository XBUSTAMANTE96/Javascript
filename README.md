# Guia de Javascript for dummies, como tu y como yo


<img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHVyY3UwYTRnZGwzdHFpeHR6Yndkbnpob2g5ZjBsdHIyMjlvOWp4dSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/iIqmM5tTjmpOB9mpbn/giphy.gif" width='250'>

<h2>Que es Javascript?</h2>
<p>Javascript es un lenguaje de programacion usado mayormente para el desarrollo web, que permite crear paginas web interactivas y dinamicas. Fue creado por Netscape como un recurso dinamico para agregar funcionalidad a los sitios web, se ha convertido en uno de los lenguajes mas usados en la web hasta el dia de hoy, segun copilot el 98% de las paginas web estan desarrolladas con Javascript. </p>
<p>Primero lo primero, ya dijimos que js te permite hacer muchas cosas para hacer mas interactiva una pagina web, como conectar otros servidores, que las paginas sean mas interactivas, agregar movimiento a recursos,entre otras cosas. Siempre y cuando tu le hables al lenguaje de programacion con los conceptos correctos, podemos hacer que javascript elimine datos,los cambie de lugar, los sume, los guarde, entre muchas cosas lo que nos lleva a nuestro primer punto </p>
<h3>Indice</H3>

<h1>Datos</h1>
<p>Los datos son entradas de caracteres(letras,numeros o simbolos) que tienes que especificar por categoria que van a ser ingresados, para que js pueda entender que tipo de dato vas a querer que el manipule, por ejemplo: </p>
<dt><h3>Boolean:</h3> 
  <p>Con este valor tu vas a poder ingresar dos entradas de texto uno lo va a tomar como verdadero y el otro como falso.Puede tener uno de dos valores: true (verdadero) o false (falso). Los booleanos se utilizan para realizar decisiones lógicas en el código. En este meme de codecademy se muestra un ejemplo IF: para ingresar la primera opcion que seria si hay bugs(errores en el codigo) odio programar, ELSE, si no es la primer opcion, entonces amo programar </p></dt>
  <img src="https://global.discourse-cdn.com/codecademy/original/5X/2/b/8/1/2b81676be890f64cf54382f56794378b21409f1a.jpeg" width='250'>

<p>Pero que pasa si hay mas de un if o entrada de datos que tienes que evaluar? supongamos que las respuestas que te de algun cliente en tu web puede tener distintas opciones, hasta un punto en el que se tienen mas de una opcion para la respuesta</p>
 <img src="https://codefinity-content-media-v2.s3.eu-west-1.amazonaws.com/courses/a5c23211-8dc2-4c4a-9a83-07a51e843ab6/section_1/TS_meme_10%404x.png" width='300'>
 <p>Seria un codigo muy cansado de escribir por todas las lineas que tendriamos que escribir una por una por tanto, cuando son varias las opciones que tienes que utilizar, en esos casos tienes que utilizar switch</p>
<img src="https://miro.medium.com/v2/resize:fit:1400/1*SiM_5c6wtpq-p7O-DvkQ4A.png" width='400'> 
  
<dt><h3>Fecha:</h3> 
  <p>Vas a poder ingresar un valor en el que js va a interpretar que contiene el día, el mes y el año. </p></dt>
  <img src="https://miro.medium.com/v2/resize:fit:1400/1*9lvHULUztfFsTPItRU2Y1Q.png" width='500'>
  
<dt><h3>Fecha y hora:</h3> 
  <p>Combina el tipo fecha y un valor que representa el tiempo transcurrido desde la medianoche. </p> </dt>
  <img src="https://phoenixnap.com/kb/wp-content/uploads/2023/12/get-full-time-and-date.png" width='500'>
  
  
  
  
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
<dt><h3>Real:</h3> <p>Puede contener valores decimales además de enteros.</p> </dt>
<dt><h3>String:</h3><p> Un tipo de dato primitivo en JavaScript.</p> </dt>
<dt><h3>Number:</h3> <p>Un tipo de dato primitivo en JavaScript.</p> </dt>
<dt><h3>Symbol:</h3> <p>Un tipo de dato primitivo en JavaScript.</p> </dt>
<dt><h3>Undefined:</h3> <p>Un tipo de dato primitivo en JavaScript.</p></dt> 
<dt><h3>Null:</h3> <p>Un tipo de dato primitivo en JavaScript. </p></dt>
<dt><h3>Bigint:</h3> <p>Un tipo de dato primitivo en JavaScript</p></dt>
    
<p>En 2024, BigInt sigue siendo una herramienta valiosa en JavaScript para manejar números enteros extremadamente grandes con precisión. Aquí te dejo algunos usos destacados de BigInt en este año:</p>

<li>Cálculos Financieros: En aplicaciones financieras donde la precisión es crucial, BigInt se utiliza para realizar cálculos exactos sin riesgo de pérdida de precisión3.</li>

<li>Criptografía: BigInt es esencial en la implementación de algoritmos criptográficos que requieren operaciones con números enteros muy grandes3.</li>

<li>Simulaciones y Modelos Matemáticos: En simulaciones científicas y modelos matemáticos que involucran números grandes, BigInt permite realizar cálculos precisos y eficientes3.</li>

<li>Gestión de Identificadores Únicos: En sistemas que requieren identificadores únicos y grandes, como bases de datos distribuidas, BigInt se utiliza para generar y manejar estos identificadores.</li>

<li>Desarrollo de Juegos: En juegos que requieren cálculos precisos con números grandes, como juegos de estrategia o simulaciones, BigInt es una herramienta útil.</li>

<p>BigInt ha mejorado la capacidad de JavaScript para manejar números grandes de manera eficiente y precisa, lo que lo hace indispensable para ciertos tipos de aplicaciones y proyectos en 2024.</p>

















