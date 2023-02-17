# Frontend

Interfaz entre un usuario y la computadora


Intérprete que ayuda al usuario a comunicarse con la máquina.


**User focus** 

 Cómo poder transmitir al usuario la información necesaria para que pueda usar el programa


**UX/UI** (User Interface / User Experience)


Cómo se van a ver las aplicaciones --> que el usuario tenga una aplicación estética y fácil de usar


Se necesita conocer al usuario, debe investigarse acerca de quiénes van a utilizar la aplicación y mejorar la experiencia, las formas de usabilidad deben cambiar de acuerdo al usuario.


En la interfaz debe poderse reflejar toda la marca y las cuestiones estéticas.


**Patrón de arquitectura de desarrollo web**


De las formas más comunes y seguras 

FrontEnd se enfoca en View, donde se hace la vista, que es la interfaz de usuario


El controlador recibe lo que viene de la vista y le envía cosas, tiene diferentes tipos de lógica.


El modelo es la parte de BackEnd, por ejemplo, si se tiene una base de datos el controlador consulta al modelo para no consultar directamente al back desde la vista.


**SDLC (Software Development Life Cycle) (Ciclo de vista del desarrollo de software)**


Es la forma más correcta de hacer las cosas.


Comienza con el **análisis de requerimientos (Requirement analysis)**
Un requerimiento es cuando alguien dice qué necesita (generalmente alguien no técnico). Se necesita toda la información posible con respecto a qué necesita el cliente.


Una vez que se tiene el contexto y análisis completo de los requerimientos se pasa al **Diseño**, donde se integra UX/UI, conocer las reglas de negocio que se deben seguir (como restricciones, por ejemplo, una persona solo puede reservar 1 taxi al mismo tiempo)


**Implementación** es el desarrollo como tal, ya se sabe qué, cómo y cómo se verá la aplicación. Aquí se aplican buenas prácticas, etc.


**Pruebas** Pruebas unitarias, punto a punto, integrales, etc. Es para verificar si lo que se está programando va acorde a lo que se pidió en los requerimientos.


Es un proceso iterativo entre pruebas y desarrollo hasta que todo pasa las pruebas y se llega a la **Evolución** (soporte, despliege, etc) ya que se terminó un ciclo, qué sigue? Se pasa al siguiente ciclo, qué sigue?


Los desarrollos deben mantenerse y revisarse para ver cómo van avanzando, deben actualizarse.


## Tecnologías que se utilizarán


   * HTML --> ayuda a maquetar las aplicaciones (pone un botón) (Esqueleto)
   * CSS --> para dar estilos y estilizar la aplicación (hace que el botón sea de tal color con tal forma) 
   * JS --> da funcionalidad (da cerebro / sistema nervioso a la aplicación) (manda las órdenes)

   * Frameworks y librerías

## Herramientas de diseño

Ayudan a estructurar la idea de forma rápida. Se puede comenzar a hacer bocetos, mock ups, prototipos completos. Puede ser en un cuaderno y luego se digitaliza, se llama **Design Thinking y Visual Thinking**. Es para poder pensar en qué solución se necesita para que lo que se está pidiendo se pueda poner rápido en un dibujo, puede llevar a tener diagramas de flujo para interpretar y entender la idea de alguien más. Ayudan para explicar lo que se está entendiendo de las ideas que se están recibiendo, ese flujo lleva a tener una funcionalidad y entendimiento completo de los requerimientos.

Se puede utilizar desde un cuaderno, paint, canva, ilustrator, publisher. Canva puede ser una opción para algo rápido y si no se tiene conocimiento de herramientas más avanzadas.


Una vez que se tiene el dibujo, se pasa al flujo y WireFrame, cómo se va a ver el dibujo en algo más estructurado, se tienen como reglas de negocio que permiten entender los flujos que se tienen dentro de los requerimientos.

   * Miro --> permite crear tableros, expresiones de las ideas.
   * Balsamic --> para empezar a crear los flujos

Ayuda a tener una idea más clara de la funcionalidad de lo que se tiene que programar.


Los clientes también son clientes internos, si se está trabajando en una organización puede ser el jefe o alguna otra área.

Herramientas para WireFrame e interfaz gráfica, ya tienen diferentes funcionalidades:

   * Sketch --> Solo para Mac
   * Figma (Gratis)
   * Adobe XD (Gratis)


Se debe tener la capacidad de tomar una idea e interpretarlas en cosas con más funcionalidad.


   * Problemática
   * Metodología de diseño
   * Público objetivo
   * Modelo de negocio
   * Definir a quién va dirigido --> definición del usuario, se puede poner una imagen, conocer la información, ubicación, a qué se dedica, intereses, aplicaciones que utiliza, etc. 
   * User-persona --> cómo se define a las personas y a los usuarios que utilizarán la aplicación
   * Definir funcionalidades necesarias dentro de la aplicación 1:03:24
   * Creación de flujo
   * Idear la parte de marca
   * Planificar trabajo
   * Prototipar --> se empieza en un dibujo, pantallas (inicio, inicio de sesión, registro, contraseña, etc)
   * WireFrames para poder prototipar (passar el dibujo a experiencia de usuario)


Flujo --> El dibujo tiene flechitas, de ahí se hacen los wireframes y de ahí se hace el diseño y luego el modal


Wireframes --> usan los mock ups, se crea el diseño de la aplicación que luego se estiliza con la interfaz de usuario, ayuda a resolver dudas


Site map --> funcionalidades en cuestiones de flujo con la experiencia, cómo está estructurada la aplicación sin necesidad de ver el diseño, se ven los íconos, textos, botones, a dónde llevan, etc.


En la experiencia de usuario ya se ven los colores, interacciones, íconos, parches, etc.


El site map complementa a las historias de usuario(definición descrita de lo que se está dibujando).


Modal --> Pantalla emergente


Pexels --> para buscar imágenes


Behance --> ejemplos 


# Práctica de diseño de aplicaciones


Ejemplo: Aplicación en donde se puedan poner las medidas de los pantalones y que los pantalones estén a la medida sin tener que ajustarlos después.


1.- ¿Quién la usaría? 


   * Usuarios en un rango de edad 22-50 años
   * Hombres y mujeres
   * Usuarios con un poder adquisitivo, estatus económico, personas que ganan entre 500 y 3,000 dólares mensuales
   * Suponiendo un precio promedio de 30 dólares por pantalón
   * Usuarios con iphone, carro pequeño, gym, les agrada verse bien, quizá consumen starbucks, utilizan redes sociales como instagram 

![Target]()


![MenúInicial]()


En la otra pantalla se muestran los pantalones, tipos de pantalones, shorts, pants, descripción y precio debajo de cada uno, cantidad disponible, etc.

![Pantalones]()


Hay que poner la parte legal, lo de copyright, aviso de privacidad, etc.

![ParteLegal]()


Cuando se da click a un pantalón sale otra página, que tiene diferentes fotos del pantalón seleccionado, ahí es donde se personaliza, se elige el color (los círculos de colores), se tiene un formulario que podría tener las medidas de las piernas (PI, PD), el largo, el ancho, el tipo de tela, reviews con estrellitas, el botón de compra.


![PantallaPersonalización]()


Se pasa al formulario de pago, se ingresan los datos de la tarjeta y se tiene el formulario de envío con los datos de entrega, si es un regalo, etc.

![PantallaFormularioPago]()


![DiseñoCompleto]()


![SecuenciaDePantallas]()


Se debe pensar en la aplicación para el administrador, en donde se tengan los pedidos, el stock, etc.


![PantallaAdmin]()


Se debe pensar en la pantalla de log in, donde se ingrese email y password, si no se tiene cuenta aún tener registro de cuenta, lo que lleva a formulario de registro, en donde se podría iniciar sesión con google, Facebook, etc.


Puede haber un video explicando cómo tomar las medidas.


![Login]()


![FormularioDeRegistro]()


![BocetoCompleto]()


Branding --> la marca, que se compone del logo, lo que se quiere comunicar, colores, el a quién va dirigido, los mensajes que se dan como difusión, en dónde se anuncia, etc.


Definir paleta de color, los colores de la marca, la tipografía seleccionada (no tienen patitas --> Sans), Grids (web, tablet y mobile, cambia el acomodo, tamaño de letra, etc.), todo debe estar homologado, debe haber armonía. se debe tener la consideración sobre diferentes tamaños de pantallas.


Los dibujos se pasan con los grids y la tipografía ya en el orden que debe llegar, se van pasando a cuadros grises (figma, ilustrator)


![PantallaCuadrosGrises0]()

![PantallaCuadrosGrises1]()

![PantallaCuadrosGrises2]()

![PantallaCuadrosGrises3]()

![PantallaCuadrosGrises4]()

![PantallaCuadrosGrises5]()

![DireccionesEnvío]()

![MétodoPago]()

![CompraFinalizada]()


Guías de estilo --> generalmente son iOS y android 


Mobile first --> paradigma de diseño --> primero se piensa en pantallas pequeñas porque cuando se programan elementos de maquetación y estilos en los diseños es más fácil hacer que las cosas se ensanchen a que se hagan pequeñas.


Diseño de flujo y diseño lógico de la aplicación --> reglas de negocio (si la contraseña tiene cierta cantidad de caracteres, si se verifica el correo, etc.)


Elementos y componentes --> botones, inputs, imágenes, títulos, ventanas pop-up, etc.


Si ya se tienen los componentes armados, si se cambia algo en el componente, por ejemplo, un ícono, se cambia en todas las pantallas donde se tenga porque es una matriz y eso ahorra tiempo.


Ejemplo: tiene un fondo de color (como es wire frame va en gris) https://www.figma.com/file/uVMdESbgFgsDSbbBflXxUg/Untitled?node-id=0%3A1


Las pantallas deben llevar a un lugar en específico y se debe poder regresar.


![UI]()


![UI1]()


![UICompra]()

![UI2]()


Figma tiene una función para compartir al desarrollador.


Branding


Manual de identidad


Logo --> podría representar lo que hace la empresa


Colores --> la identidad mostrada en distintos colores


Tipografía --> light, regular, bold, colores de la identidad --> en da font se pueden encontrar tipografías


Aplicaciones --> qué se puede hacer con la marca, página web, impresos (sobres, tarjetas, discos, hojas membretadas, cajas)


Cosas fundamentales
 

Crear guía de estilo (ya sea que la de el cliente o nosotros lo ofrezcamos adicionalmente, qué se ofrece y porqué eres la mejor opción)


# Estructura de programación


Código spaghetti --> todo está revuelto y no se entiende



* Código legible, escalable, mantenible, seguro, etc.


* Adaptarse de manera más sencilla en organizaciones que ya tienen esas estructuras.


El **SDLC (Software Development Life Cycle)** ayuda a tener mejor órden y organización, el software y código es un ente vivo, se está moviendo de manera continua por las características de la tecnología.


Análisis de requerimientos --> cuáles son las cosas que está pidiendo el cliente. Brief --> se debe entender todo, se deben identificar las necesidades de la aplicación, de automatización, de los clientes, etc. Toma de requerimientos.


Se hace el software para poder ahorrar tiempo, dinero o recursos, lo que lleva a ganar más. 


Siempre se debe pensar en cómo nos beneficia, tiempo, recursos, parte monetaria o en cualquier área o necesidad, el software debe ser rentable por sí mismo.


### Diseño


Experiencia de usuario e interfaz de usuario. Se plasman las necesidades que se tienen. También es el diseño lógico de cómo se mueve la aplicación, de cómo va a estar desarrollada la aplicación.


Se pueden tener diagramas de flujo, diagramas de entidad relación, UML (cómo va a estar la BD), ayudan con el diseño técnico que nos da las bases de lo que necesitamos hacer. (draw.io o lucid chart)


Casos de uso --> para entender las necesidades de negocio o la lógica de negocio que se debe  cumplir con el software, qué hace qué y responde qué (p.ej. si el cliente cambia el número de productos, el precio debe modificarse) (el usuario puede picarle a y entonces pasa esto)


Los diagramas combinados con UX/UI dan la parte de diseño.


### Implementación


Cuando se hace el código, infraestructura de redes, infraestructura de nube, research, diferentes formas de implementar el diseño.


### Testing


Para verificar que la implementación cumple con el análisis de requerimientos y está alineada al diseño que se hizo. Tiene diferentes formas de pruebas

   * Unitarias --> específicas sobre cada módulo que se va diseñando y desarrollando
   * Integrales --> se mete el módulo dentro de la aplicación y ver cómo se comporta
   * Punto a punto --> se hace un flujo completo de inicio a fin para ver cómo se comporta todo y levantar tickets o recomendaciones
   * Seguridad --> pen testing, intentos de hackeo, caja negra, blanca, gris, para romper la aplicación o intentar sacar información sensible.
   * Estrés --> si en un caso específico o momento no definido se tiene un ataque de negación de servicios o un número inesperado de usuarios.

Es un proceso iterativo que regresa con implementación, ya que el testing verifica que la implementación cumpla con los requerimientos y si no es así se debe arreglar. 


### Evolución


Se cumple y se regresa el ciclo, es cuando se ve si en el primer ciclo o iteración que falta algo o se puede arreglar algo y regresa al análisis de requerimientos.


Se puede considerar en sprints o en línea start up (sale al mercado, se prueba y regresa).


Las iteraciones se pueden documentar con sprint planning (marcos de trabajo ágiles, metodologías).


Can I use --> página para buscar las funcionalidades de programación web frontend y te dice en qué navegadores funciona


### Developer tools


F2 al navegador o click derecho --> inspeccionar 


Wappalayzer --> extensión para saber con qué están hechas las páginas


Lighthouse --> parte de testing para saber cómo funciona la aplicación --> herramientas de desarrollo --> Lighthouse


Programación pensando en inclusividad --> poder llevar la tecnología a personas con capacidades físicas distintas --> axe DevTools hace un escaneo para saber si la aplicación es inclusiva.


Democratización de tecnología --> cómo hacer que tenga impacto en diferentes usuarios y llegue más lejos.


Documentación --> necesaria completamente, el código debe ser entendible para uno mismo en un tiempo, lo que se debe documentar es:


   * Definir a la audiencia si va a ser para alguien administrativo, para otros desarrolladores, para uno mismo o simplemente es para explicar qué es lo que se está haciendo la aplicación, eso nos dirá qué tan específico (qué tanto detalle hay que poner) debe ser.
   * Qué problemática soluciona el código? Se programan funciones, módulos, cosas especificas para generar los desarrollos y aplicaciones. Todos los códigos solucionan problemas, por cada módulo, ¿Qué se está solucionando? Qué hay de entrada y de salida? ¿Qué pregunta va a responder?
   * Estructura de la aplicación. Cuando se está documentando hay diferentes carpetas, secciones, páginas, librerías, etc., toda esa estructura se debe documentar. Firebase --> plataforma de desarrollo, ahí hay estructuras como autenticación, etc. (https://firebase.google.com/docs/build) 
   Se puede hacer en Notion (https://www.notion.so/), Confluence(https://www.atlassian.com/es/software/confluence), o incluso un readme en github


### Estructura de Código


Puede ser la estructura de un proyecto y puede ser:

   * Por tipo de archivo 
   * Por funcionalidad
   * Por ruta

Cómo se van a organizar los archivos


Estructura web


Cómo van a estar organizadas las páginas para tener una mejor experiencia de usuario. 


Vamos de lo general a lo particular. Entramos a la página de inicio y ahí se abren categorías.


Los usuarios tienen que tener una guía, las páginas o aplicaciones deben ser como un mapa que nos lleve a lo que buscamos.


Hay **modelos secuenciales**, que se utiliza para que el usuario llene formularios o pase un flujo sin salirse de un carril (1 --> 2 --> 3 --> 4)


Un **modelo de matriz** es donde podemos movernos por todo el sitio sin necesidad de una estructura específica y el usuario es responsable de todo lo que debe hacer.


De las prácticas --> el formato es una opción para guiarse, se pueden tomar las opciones para generar una plantilla propia. Si falta información se hacen los dibujos.

Buyer persona --> para definir quién será el usuario. En Miro se puede usar la plantilla de público objetivo (target audience) y se puede elegir lo que nos sirva.
Es el cliente ideal, una persona específica que te va a comprar.


Público objetivo --> Si se tuviera que dar a una multitud de personas, ¿Qué característica en común tendrían?


# HTML


HyperText Markup Language es la estructura de lo que se tendrá en una página web. 


Los navegadores interpretan el código para desplegar la estructura. Se pueden agregar funcionalidades como optimización, accesibilidad, etc.


### Estructura de HTML


Está definida por **etiquetas** (meta, title, style, etc.). Da cómo va la página o aplicación y cómo se tendrá el archivo.



#### Elementos compuestos

Son cosas que se usan para generar la aplicación e interactuar, además de tener texto tienen cosas que permiten seleccionar o interactuar


Box model --> cómo se puede hacer la estructura con la información necesaria. Todo va en cajas (ejemplo [layout y rutas]())

Práctica html --> Hacer página de una taquería

## Cascade Style Sheet (CSS)


Son para poner estilo en las páginas web


Selectores --> ids, clases, name, son las 3 clases de selectores, tienen una jerarquía, le indica al archivo qué ponerle.


En el archivo CSS se tiene cómo identificar a los selectores, cuando solo es en la etiqueta style, el CSS va dentro de esa etiqueta


Cuando se pone *{ } significa que ese estilo se aplicará a todo.


Cuando se pone solo la palabra, como body, significa que eso se aplica a lo que esté dentro de la etiqueta body


Otro tipo de selector es con id, (el id que se pone en html) --> #id


.nombre_de_la_clase es más fácil y da más versatilidad, permite juntar clases, tener diferentes elementos, etc.


Es más fácil usar clases


Se puede definir el color solo con el nombre, o específico de un programa de diseño, con RGB, RGBA, HEX o HSL


Texto decorado --> como en los links


Los links (\<a\>\</a>) ya tienen una decoración por default


Flexbox --> forma en la que se pueden tener los contenedores y cómo se pueden mover, para lo cual existen diferentes formas de tener el display, define cómo se va a mostrar el contenedor (div, section o article)


Display --> Se puede desplegar de diferentes formas


justify --> parte horizontal


align-items --> parte vertical


align-content --> para elementos compuestos que usan tanto filas como columnas


Elementos --> Child --> items


order --> en qué orden se acomodarán los elementos


flex-grow --> uno de los elementos ocupa más espacio que el resto, utilizar de una fila una columna, dos columnas, una columna


flex-shrink --> para encoger 


align-self --> para un solo elemento 


space-around --> los elementos tienen el mismo espacio al rededor


Se puede agregar una dirección vertical (la inicial es horizontal) (en forma de columna)


flex-wrap --> Para hacerlo repsonsive (los elementos se acomodan de acuerdo al tamaño de la ventana)


margin (distancia interna), border (borde de los elementos(de la caja)), paddidng (distancia interna entre elementos (entre la caja y el contenido)) --> cómo interactúan entre elementos 


09:14 css movil