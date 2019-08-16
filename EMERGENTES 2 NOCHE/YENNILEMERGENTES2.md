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
** 1.- DISPONIBILIDAD **

La capacidad de un sistema de ser accesible, teniendo un tiempo de inactividad limitado.

** ejemplo:** 24/7/365 

** 2.- CAPACIDAD **

La capacidad de un sistema de ejecutar varias tareas dentro de un periodo de tiempo.

** ejemplo:**
El sistema puede mantener 3 millones de ususario concurrentes.

**  3.- EXTENSIBILIDAD ** 

La capacidad de extender la funcionalidad del sistema.

** ejemplo: ** El sistema puede facilmente agregar una libreria que genere PDFs.

**  4.-FLEXIBILIDAD ** 

La capacidad de realizar cambios d configuracion, manteniendo la integridad del sistema.

** ejemplo: ** el sistema puede cambiarse de servidor de base de datos, con cambios de configuracion minimos.

**  5.- MANEJABILIDAD** 

La capacidad de gestionar los recursos del sistema.

** ejemplo: ** El sistema puede cambiar los permisos de acceso de los usuarios mientras esta en operacion.

**  6.- RENDIMIENTO** 

La capacidad de realizar  funciones dentro de objetivos especificos.

** ejemplo: ** El sistema debe recuperar las consultas de la base de datos en 3 seg.

**  7.- CONFIABILIDAD ** 

La capacidad de garantizar la integridad y consistencia del sistema y sus transacciones.

** ejemplo: ** El sistema envia e-mails que no son corruptos.


**  8.- REUSABILIDAD ** 

la capacidad de reutilizar un componte.

** ejemplo: ** El sistema usa el mismo componente de seguridad para varias aplicaciones.

**  9.- ESCALABILIDAD** 

la capacidad de soportar la funciobnalidad cuando la carga aumenta.

** ejemplo: ** El servicio de consultas a la base de datos respondera en el tiempo establecido, sin importar el numero de usuarios.

**  10.- SEGURIDAD** 

La capacidad de garantizar la seguridad de la informacion.

** ejemplo: ** El sistema encripta y desencripta los datos que viajan en la red.

**  11.- VALIDEZ** 

la capacidad de validar los resultados del sistema o una entrada de ususario.

** ejemplo: ** El sistema no permite los ampos de entrada que no estan en el formato especifico.
#### 3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta

#### 4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical
** Escalabilidad Vertical**

![](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-vertical.png)

El escalar hacia arriba un sistema viene a significar una migración de todo el sistema a un nuevo hardware que es mas potente y eficaz que el actual. Una vez se ha configurado el sistema futuro, se realizan una serie de validaciones y copias de seguridad y se pone en funcionamiento. Las aplicaciones que estén funcionando bajo la arquitectura hardware antigua no sufren con la migración, el impacto en el código es mínimo.

Este modelo de escalabilidad tiene un aspecto negativo. Al aumentar la potencia en base a ampliaciones de hardware, llegara un momento que existirá algún tipo de limitación hardware. Además a medida que se invierte en hardware de muy altas prestaciones, los costos se disparan tanto de forma temporal (ya que si se ha llegado al umbral máximo , hay componentes hardware que tardan mucho tiempo en ampliar su potencia de forma significativa) como económicos. Sin embargo a nivel estructural no supone ninguna modificación reseñable, lo que la convierte en una buena opción si los costos anteriores son asumibles.

** Escalabilidad Horizontal ** 

![](/20190813204625401/20190815120440811.png)

La escalabilidad horizontal consiste en potenciar el rendimiento del sistema desde un aspecto de mejora global, a diferencia de aumentar la potencia de una única parte del mismo. Este tipo de escalabilidad se basa en la modularidad de su funcionalidad. Por ello suele estar conformado por una agrupación de equipos que dan soporte a la funcionalidad completa. Normalmente, en una escalabilidad horizontal se añaden equipos para dar mas potencia a la red de trabajo.

Con un entorno de este tipo, es lógico pensar que la potencia de procesamiento es directamente proporcional al número de equipos de la red. El total de la potencia de procesamiento es la suma de la velocidad física de cada equipo transferida por la partición de aplicaciones y datos extendida a través de los nodos.

Si se aplica un modelo de escalabilidad basado en la horizontalidad, no existen limitaciones de crecimiento a priori. Como principal e importante defecto, este modelo de escalabilidad supone una gran modificación en el diseño, lo que conlleva a una gran trabajo de diseño y reimplantación. Si la lógica se ha concebido para un único servidor, es probable que se tenga que estructurar el modelo arquitectónico para soportar este modelo de escalabilidad.

#### 5) Que es un servidor Web y que es un servidor de aplicaciones
** Servidor Web:** 

Un servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor realizando conexiones bidireccionales y/o unidireccionales y síncronas o asíncronas con el cliente generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente.

** Servidor de aplicaciones:**

En informática, se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.

#### 6) Con un gráfico explique cómo funciona el protocolo HTTP

<center>
![Incrustar tipografía un un Powerpoint](https://img-17.ccm2.net/-P-kXsfhNd-6KT1HjIb3_8YKn3w=/377x/61c0586238c04582855627961b329882/ccm-encyclopedia/internet-images-comm.gif)
</center>

El protocolo HTTP funciona a traves de solicitudes y respuestas entre un cliente y un servidor.

a una secuencia de HTTP.

#### 7) Explique los elementos importantes de REQUEST en HTTP

La request line está formada por 3 partes: el método, la ruta y el protocolo.

** METODO **

>El método indica el tipo de petición que se realiza, y que típicamente puede ser GET, POST ó HEAD. La carga de una web normalmente se hace por GET. Sin embargo, cuando por ejemplo enviamos un formulario es habitual que la petición se haga por post, de modo que la línea de petición podría ser de la forma POST /resultados.php HTTP 1.1. También el envío de un formulario puede hacerse por GET, en este caso bajo un formato similar a GET /form.php?nombre=Juan&apellidos=Perez&action=Submit HTTP/1.1

** RUTA **

>La ruta, es normalmente la ruta relativa o parte de la dirección web que viene detrás del dominio. 

** PROTOCOLO **

> El protocolo consta de HTTP y el número de versión de protocolo que se emplea, típicamente 1.1.

- HEAD, igual que GET pero sin el cuerpo de la respuesta.

- GET, pide al servidor que le envíe un recurso.
- 
POST, envía datos al servidor para que sean procesados por el recurso especificado en la petición.

- PUT, envía un recurso al servidor.
- 
DELETE, elimina el recurso especificado.

- TRACE, pide al servidor mensaje de respuesta, empleado para diagnosticar posibles problemas de conexión.

- OPTIONS, pide al servidor que le indique los metodos HTTP que soporta para una URL.

- CONNECT, para transformar una conexión a una encriptada.

- PATCH, se usa para modificar parcialmente un recurso existente en el servidor.

#### 8) Explique los elementos importantes de RESPONSE en HTTP

-  ** CODIGO DE ESTADO **, Un código de estado 400 o un código de tres dígitos que comienza con 4xx indica un error de cliente. Cuando el cliente envía una petición al servidor que está dañada o defectuosa, el servidor emite un código de estado 400. Es importante corregir los errores de 4xx en una web para que los usuarios puedan acceder a todo el contenido del sitio.
-  
** VERSION DE PROTOCOLO **, El protocolo IP establece el sistema de identificación que emplea Internet para enviar información ente dispositivos.

- ** MENSAJE DE ESTADO **, El cuerpo del mensaje contiene el mensaje de solicitud recibido por el servidor.
- 
** ENCABEZADAS **, Las cabeceras (en inglés headers) HTTP permiten al cliente y al servidor enviar información adicional junto a una petición o respuesta. Una cabecera de petición esta compueta por su nombre (no sensible a las mayusculas) seguido de dos puntos ':', y a continuación su valor (sin saltos de línea). Los espacios en blanco a la izquierda del valor son ignorados.



El objeto Response tiene 8 propiedades, 1 colección y 8 métodos: 

** PROPIEDADES **

> Response.Buffer = False | True
Response.CacheControl = "Public" | "Private"
Response.Charset("String")
Response.ContentType("String")
Response.Expires
Response.ExpiresAbsolute
Response.IsClientConnected = True | False
Response.Status = "Status"

** COLECCIONES **

>Response.Cookies(Nombre)[(Clave)|.Atributo]=Valor

** METODOS **

> Response.AddHeader "Nombre", "Valor"
Response.AppendToLog("String")
Response.BinaryWrite(Data)
Response.Clear
Response.End
Response.Flush
Response.Redirect(URL)

#### 9) Describa con un gráfico la arquitectura Java EE

<center>

![Incrustar tipografía un un Powerpoint](data:image/png;base64,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)

</center>

#### 10) Explique cuáles son los contenedores, componentes y servicios de Java EE
** contenedores **
> ** Java EE Server:** La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

> ** Contenedor EJB:**  Maneja la ejecución de los enterprise beans.

>** Contenedor Web: ** Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

>** Contenedor de aplicación cliente:**  Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

>** Contenedor Applet: ** Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

** componentes **
<center>
![Incrustar tipografía un un Powerpoint](https://parasitovirtual.files.wordpress.com/2010/12/contenedores.gif)
</center>

** servicios de Java EE **

![Incrustar tipografía un un Powerpoint ](http://www.jtech.ua.es/j2ee/2003-2004/abierto-j2ee-2003-2004/ejb/imagenes/arquitecturaEJB.png)

#### 11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.

** clases HttpServlet **

> public abstract class HttpServlet extends GenericServlet: Es la clase de la cual se debe extender para crear un servlet HTTP. De la clase que extiende obtiene los métodos ya definidos además de los cuales define:

> - doGet(HttpServletRequest req, HttpServletResponse resp): Es el método llamado para procesar información que haya sido enviado con el método GET. Este método es llamado concurrentemente para cada cliente por lo que hay que estar atento por posibles variables compartidas que causen problemas.


> - doPost(HttpServletRequest req, HttpServletResponse resp): Ídem al anterior pero para el método POST, en general se implementa sólo un método y el otro lo referencia.

**  clases  HttpServletRequest  ** 

> public abstract interface HttpServletRequest extends ServletRequest: Permite obtener del cliente la información que es dependiente del protocolo, en este caso HTTP. Entre sus métodos están:

> - getHeader(String name): Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.

> - getCookies(): Retorna un arreglo que contiene todas las cookies que el cliente envía al servlet.
getSession(): Retorna la sesión en la cual se encuentra el cliente.

**  clases  HttpServletResponset  **

> - public abstract interface HttpServletResponse extends ServletResponse: Permite enviar al cliente respuestas específicas del protocolo HTTP.

> - addCookie(Cookie cookie): Para definir nuevas cookies en el cliente.

> - setHeader(String name, String value): Para definir un header HTTP a enviar al cliente.
sendRedirect(String location): Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.

** EJEMPLO **
![](https://mdn.mozillademos.org/files/13691/HTTP_Response.png)
> ** CODIGO **

> import java.io.IOException;
import javax.servlet.ServletException;
import javax.servlet.annotation.WebServlet;
import javax.servlet.http.HttpServlet;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

> /**
 * Servlet implementation class HolaMundo
 */
@WebServlet("/HolaMundo")
public class HolaMundo extends HttpServlet {
	private static final long serialVersionUID = 1L;
       
  >  /**
     * @see HttpServlet#HttpServlet()
     */
    public HolaMundo() {
        super();
        // TODO Auto-generated constructor stub
    }

>	/**
	 * @see HttpServlet#doGet(HttpServletRequest request, HttpServletResponse response) 
	 */
	protected void doGet(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
		// TODO Auto-generated method stub
	}

>	/**
	 * @see HttpServlet#doPost(HttpServletRequest request, HttpServletResponse response)
	 */
	protected void doPost(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
		// TODO Auto-generated method stub
	}

>}
> <center>
![Incrustar tipografía un un Powerpoint](D:\EMERGENTES 2 NOCHE/servelets.jpg)
</center>