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

**3.- EXTENSIBILIDAD ** 

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
![](data:image/png;base64,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)

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

**clases  HttpServletResponset  **

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