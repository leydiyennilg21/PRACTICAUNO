# <center> PRÁCTICA Nº # 1 </center>
# <center>SISTEMAS EMPRESARIALES </center>

<table  border="" >
<tr>
  <td bgcolor= "YELLOW">Carrera:</td>
  <td bgcolor= "YELLOW">Ingenieria de Sistemas</td>
  
</tr>
<tr>
  <td bgcolor= "YELLOW">Materia:</td>
  <td bgcolor= "YELLOW">Emergentes II</td>
 
</tr>
<tr>
  <td bgcolor= "YELLOW">Apellidos y Nombres:</td>
  <td bgcolor= "YELLOW">	Gutierrrez Isidro Yennil</td>
 
</tr>
<tr>
  <td bgcolor= "YELLOW">C.I:</td>
  <td bgcolor= "YELLOW">	8297962 LP</td>
 
</tr>

<tr>
  <td bgcolor= "YELLOW">Lugar y Fecha:</td>
  <td bgcolor= "YELLOW">	El Alto, 12 de Agosto de 2019</td>
 
</tr>

</table>



#### 1) Explique que son los sistemas empresariales
 El sistema de información empresarial constituye el conjunto de recursos de la empresa que sirven como soporte para el proceso básico de captación, transformación y comunicación de la información.

 Un sistema de información debe ser eficaz y eficiente. Es eficaz si facilita la información necesaria, y es eficiente si lo realiza con los menores recursos posibles.
#### 2) Describa cuales son las características más importantes de una aplicación empresarial
**1.- DISPONIBILIDAD**

La capacidad de un sistema de ser accesible, teniendo un tiempo de inactividad limitado.

**ejemplo:** 24/7/365 

**2.- CAPACIDAD**

La capacidad de un sistema de ejecutar varias tareas dentro de un periodo de tiempo.

**ejemplo:**
El sistema puede mantener 3 millones de ususario concurrentes.

**3.- EXTENSIBILIDAD** 

La capacidad de extender la funcionalidad del sistema.

**ejemplo:** El sistema puede facilmente agregar una libreria que genere PDFs.

**4.- FLEXIBILIDAD:** 

La capacidad de realizar cambios d configuracion, manteniendo la integridad del sistema.

**ejemplo:** el sistema puede cambiarse de servidor de base de datos, con cambios de configuracion minimos.

**5.- MANEJABILIDAD:** 

La capacidad de gestionar los recursos del sistema.

**ejemplo:** El sistema puede cambiar los permisos de acceso de los usuarios mientras esta en operacion.

**6.- RENDIMIENTO** 

La capacidad de realizar  funciones dentro de objetivos especificos.

**ejemplo:** El sistema debe recuperar las consultas de la base de datos en 3 seg.

**7.- CONFIABILIDAD** 

La capacidad de garantizar la integridad y consistencia del sistema y sus transacciones.

**ejemplo:** El sistema envia e-mails que no son corruptos.


**8.- REUSABILIDAD:** 

la capacidad de reutilizar un componte.

**ejemplo:** El sistema usa el mismo componente de seguridad para varias aplicaciones.

**9.- ESCALABILIDAD:** 

la capacidad de soportar la funciobnalidad cuando la carga aumenta.

**ejemplo:** El servicio de consultas a la base de datos respondera en el tiempo establecido, sin importar el numero de usuarios.

**10.- SEGURIDAD:** 

La capacidad de garantizar la seguridad de la informacion.

**ejemplo:** El sistema encripta y desencripta los datos que viajan en la red.

**11.- VALIDEZ:** 

la capacidad de validar los resultados del sistema o una entrada de ususario.

**ejemplo:** El sistema no permite los ampos de entrada que no estan en el formato especifico.

#### 3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta

#### 4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical
**Escalabilidad Vertical**

![](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-vertical.png)

El escalar hacia arriba un sistema viene a significar una migración de todo el sistema a un nuevo hardware que es mas potente y eficaz que el actual. Una vez se ha configurado el sistema futuro, se realizan una serie de validaciones y copias de seguridad y se pone en funcionamiento. Las aplicaciones que estén funcionando bajo la arquitectura hardware antigua no sufren con la migración, el impacto en el código es mínimo.

Este modelo de escalabilidad tiene un aspecto negativo. Al aumentar la potencia en base a ampliaciones de hardware, llegara un momento que existirá algún tipo de limitación hardware. Además a medida que se invierte en hardware de muy altas prestaciones, los costos se disparan tanto de forma temporal (ya que si se ha llegado al umbral máximo , hay componentes hardware que tardan mucho tiempo en ampliar su potencia de forma significativa) como económicos. Sin embargo a nivel estructural no supone ninguna modificación reseñable, lo que la convierte en una buena opción si los costos anteriores son asumibles.

**Escalabilidad Horizontal** 

![](/20190813204625401/20190815120440811.png)

La escalabilidad horizontal consiste en potenciar el rendimiento del sistema desde un aspecto de mejora global, a diferencia de aumentar la potencia de una única parte del mismo. Este tipo de escalabilidad se basa en la modularidad de su funcionalidad. Por ello suele estar conformado por una agrupación de equipos que dan soporte a la funcionalidad completa. Normalmente, en una escalabilidad horizontal se añaden equipos para dar mas potencia a la red de trabajo.

Con un entorno de este tipo, es lógico pensar que la potencia de procesamiento es directamente proporcional al número de equipos de la red. El total de la potencia de procesamiento es la suma de la velocidad física de cada equipo transferida por la partición de aplicaciones y datos extendida a través de los nodos.

Si se aplica un modelo de escalabilidad basado en la horizontalidad, no existen limitaciones de crecimiento a priori. Como principal e importante defecto, este modelo de escalabilidad supone una gran modificación en el diseño, lo que conlleva a una gran trabajo de diseño y reimplantación. Si la lógica se ha concebido para un único servidor, es probable que se tenga que estructurar el modelo arquitectónico para soportar este modelo de escalabilidad.

#### 5) Que es un servidor Web y que es un servidor de aplicaciones
**Servidor Web:** 

Un servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor realizando conexiones bidireccionales y/o unidireccionales y síncronas o asíncronas con el cliente generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente.

**Servidor de aplicaciones:**

En informática, se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.

#### 6) Con un gráfico explique cómo funciona el protocolo HTTP

<center>

![](https://img-17.ccm2.net/-P-kXsfhNd-6KT1HjIb3_8YKn3w=/377x/61c0586238c04582855627961b329882/ccm-encyclopedia/internet-images-comm.gif)

</center>

El protocolo HTTP funciona a traves de solicitudes y respuestas entre un cliente y un servidor.

a una secuencia de HTTP.

#### 7) Explique los elementos importantes de REQUEST en HTTP

La request line está formada por 3 partes: el método, la ruta y el protocolo.

**METODO:**

>El método indica el tipo de petición que se realiza, y que típicamente puede ser GET, POST ó HEAD. La carga de una web normalmente se hace por GET. Sin embargo, cuando por ejemplo enviamos un formulario es habitual que la petición se haga por post, de modo que la línea de petición podría ser de la forma POST /resultados.php HTTP 1.1. También el envío de un formulario puede hacerse por GET, en este caso bajo un formato similar a GET /form.php?nombre=Juan&apellidos=Perez&action=Submit HTTP/1.1

**RUTA:**

>La ruta, es normalmente la ruta relativa o parte de la dirección web que viene detrás del dominio. 

**PROTOCOLO:**

> El protocolo consta de HTTP y el número de versión de protocolo que se emplea, típicamente 1.1.

- HEAD, igual que GET pero sin el cuerpo de la respuesta.

- GET, pide al servidor que le envíe un recurso.

- POST, envía datos al servidor para que sean procesados por el recurso especificado en la petición.

- PUT, envía un recurso al servidor.

- DELETE, elimina el recurso especificado.

- TRACE, pide al servidor mensaje de respuesta, empleado para diagnosticar posibles problemas de conexión.

- OPTIONS, pide al servidor que le indique los metodos HTTP que soporta para una URL.

- CONNECT, para transformar una conexión a una encriptada.

- PATCH, se usa para modificar parcialmente un recurso existente en el servidor.

#### 8) Explique los elementos importantes de RESPONSE en HTTP

-  **CODIGO DE ESTADO** , Un código de estado 400 o un código de tres dígitos que comienza con 4xx indica un error de cliente. Cuando el cliente envía una petición al servidor que está dañada o defectuosa, el servidor emite un código de estado 400. Es importante corregir los errores de 4xx en una web para que los usuarios puedan acceder a todo el contenido del sitio.

- **VERSION DE PROTOCOLO** , El protocolo IP establece el sistema de identificación que emplea Internet para enviar información ente dispositivos.

- **MENSAJE DE ESTADO** , El cuerpo del mensaje contiene el mensaje de solicitud recibido por el servidor.

- **ENCABEZADAS** , Las cabeceras (en inglés headers) HTTP permiten al cliente y al servidor enviar información adicional junto a una petición o respuesta. Una cabecera de petición esta compueta por su nombre (no sensible a las mayusculas) seguido de dos puntos ':', y a continuación su valor (sin saltos de línea). Los espacios en blanco a la izquierda del valor son ignorados.



El objeto Response tiene 8 propiedades, 1 colección y 8 métodos: 

**PROPIEDADES**

> Response.Buffer = False | True
Response.CacheControl = "Public" | "Private"
Response.Charset("String")
Response.ContentType("String")
Response.Expires
Response.ExpiresAbsolute
Response.IsClientConnected = True | False
Response.Status = "Status"

**COLECCIONES:**

>Response.Cookies(Nombre)[(Clave)|.Atributo]=Valor

**METODOS:**

> Response.AddHeader "Nombre", "Valor"
Response.AppendToLog("String")
Response.BinaryWrite(Data)
Response.Clear
Response.End
Response.Flush
Response.Redirect(URL)

#### 9) Describa con un gráfico la arquitectura Java EE

<center>

![](https://image.slidesharecdn.com/sesion3-140122074931-phpapp02/95/sesion-3-desarrollo-de-aplicaciones-jee-57-638.jpg?cb=1390376997)

</center>

#### 10) Explique cuáles son los contenedores, componentes y servicios de Java EE
**contenedores**
> **Java EE Server:** La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

> **Contenedor EJB:**  Maneja la ejecución de los enterprise beans.

>**Contenedor Web:**  Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

>**Contenedor de aplicación cliente:**  Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

>**Contenedor Applet:** Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

**componentes**


- Componente cliente: Cliente AWT, Swing, Applet y navegador Web.

- Componente web: Servlet, JSP y JSF.

- Componente de negocio: EJB



**servicios de Java EE**

![Incrustar tipografía un un Powerpoint ](http://www.jtech.ua.es/j2ee/2003-2004/abierto-j2ee-2003-2004/ejb/imagenes/arquitecturaEJB.png)

- De directorio: para la indexación y búsqueda de componentes y recursos.

- De despliegue: para poder personalizar los componentes y recursos.

- De transaccionalidad: para poder ejecutar distintas acciones en una misma unidad transaccional.

- De seguridad: para poder autenticar y autorizar a los usuarios de la aplicación.

- De acceso a datos: para facilitar el acceso a Bases de Datos.

- De conectividad: para poder acceder fácilmente a distintos EIS.

- De mensajería: para poder comunicarse con otros componentes, aplicaciones o EIS


#### 11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.

**clases HttpServlet **

> public abstract class HttpServlet extends GenericServlet: Es la clase de la cual se debe extender para crear un servlet HTTP. De la clase que extiende obtiene los métodos ya definidos además de los cuales define:

> -doGet(HttpServletRequest req, HttpServletResponse resp): Es el método llamado para procesar información que haya sido enviado con el método GET. Este método es llamado concurrentemente para cada cliente por lo que hay que estar atento por posibles variables compartidas que causen problemas.


> -doPost(HttpServletRequest req, HttpServletResponse resp): Ídem al anterior pero para el método POST, en general se implementa sólo un método y el otro lo referencia.

**clases  HttpServletRequest  ** 

> public abstract interface HttpServletRequest extends ServletRequest: Permite obtener del cliente la información que es dependiente del protocolo, en este caso HTTP. Entre sus métodos están:

> - getHeader(String name): Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.

> - getCookies(): Retorna un arreglo que contiene todas las cookies que el cliente envía al servlet.
getSession(): Retorna la sesión en la cual se encuentra el cliente.

**clases  HttpServletResponset**

> - public abstract interface HttpServletResponse extends ServletResponse: Permite enviar al cliente respuestas específicas del protocolo HTTP.

> - addCookie(Cookie cookie): Para definir nuevas cookies en el cliente.

> - setHeader(String name, String value): Para definir un header HTTP a enviar al cliente.
sendRedirect(String location): Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.

**EJEMPLO**
![](https://mdn.mozillademos.org/files/13691/HTTP_Response.png)
> **CODIGO** 

> import java.io.IOException;

>import javax.servlet.ServletException;

>import javax.servlet.annotation.WebServlet;

>import javax.servlet.http.HttpServlet;

>import javax.servlet.http.HttpServletRequest;

>import javax.servlet.http.HttpServletResponse;


> Servlet implementation class HolaMundo
 > 
 @WebServlet("/HolaMundo")
 > public class HolaMundo extends HttpServlet {
	private static final long serialVersionUID = 1L;
       
  >  
      @see HttpServlet#HttpServlet()
     
  >  public HolaMundo() { super(); TODO Auto-generated constructor stub }

>	
> @see HttpServlet#doGet(HttpServletRequest request, HttpServletResponse response) 
	 >
	protected void doGet(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
> @see HttpServlet#doPost(HttpServletRequest request, HttpServletResponse response)
>	 
	protected void doPost(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
		// TODO Auto-generated method stub
	} }


 <center>


![](http://www.tutorialesprogramacionya.com/javaya/imagentema/foto213.jpg)

</center>