# Practica-KevinOrdonez

# Ejercicio 1
### Git Bash
![Get](https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/Git_Bash.jpg)
### Visual Code
![Get](https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/VisualStudioCode.jpg)
# Ejercicio 2
Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son agnósticas al lenguaje de programación, la idea es comprender los conceptos del estándar:
	1. ¿Qué es un servidor HTTP?
  Principalmente son utilizados para la distribución de contenido web ya sea en redes internas o en web mediante la transferencia de documentos.

	2.¿Qué son los verbos HTTP?
 Son conjuntos  de métodos para indicar la acción de un recurso determinado. Alguno los que se utilizan para la creación de Restful son: -Get
-Post
-Put
-Delete.

	3.¿Qué es un request y un response en una comunicación HTTP?
Request: es una petición que se hace desde el cliente 
Response: es la respuesta del servidor al cliente.
 Es un acceso que se ejecuta en un navegador al que se le hace una petición de un objeto web con el propósito de que se brinda una respuesta. 
 
	
	4.¿Qué son los headers?
		Es la parte superior de las páginas web y es muy importante pues en ese mismo espacio suelen encontrarse las secciones de interración . 
 
	5.¿Qué es un queryString? (En el contexto de una url)
Se utiliza para hacer referencias a una interacción con una base de datos. Es la parte de la URL que contiene los datos que deben pasar a las aplicaciones web. 

	6.¿Qué es el responseCode?
Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica.

 	¿Qué significado tiene los posibles valores devueltos?
Respuestas informativas 100–199.
Respuestas satisfactorias 200–299.
Redirecciones 300–399.
Errores de los clientes 400–499.
Errores de los servidores 500–599.
						

	7.¿Cómo se envía la data en un Get y cómo en un POST? 
  Se puede hacer mediante el lenguaje de PHP o HTML

	8.¿Qué verbo http utiliza el navegador cuando accedemos a una página?
   Puede ser POST o Get de acuerdo a lo que se quiera mostrar al abrir la página.

Explicar brevemente qué son las estructuras de datos JSON y XML dando
JSON:  Representan formas a base de objetos, un objeto es un conjunto desordenado de pares nombre/valor.ejemplo de estructuras posibles.
XML: Es siempre descriptivo y se compara con un árbol porque cuenta con elementos, elementos secundarios
*JSON:*

{
“tipo” “class”
“Nombre:” “persona”
“Operaciones” (“Consultar”,” Insertar”,” Actualizar”)
“Vistas” (“PDF”, “XML”, “cargo”)
}

*XML:*

<Receptor>
	<DireccionReceptor>
		<Direccion>1 Av Patria </Direccion >
		<CodigoPostal>   45070      </CodigoPostal>
		<Municipio> Zapopan </Municipio>
		<País> México </País>
	<DireccionReceptor>
<Receptor>


 	9. Explicar brevemente el estándar SOAP
Es un protocolo ligero para el intercambio de información en entornos descentralizados y distribuidos, además de que sus mensajes son transmisiones de remitente a destinatario.

	10.	Explicar brevemente el estándar REST Full
	Es un servicio que funciona para compartir información en un sistema de doble vía, consulta y respuesta (Request=> Response).

11.	*¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?*
Los headers transmiten la información acerca del navegador del cliente, de la página solicitada, del servidor, etc., y el key content se usa para informar que tipo de dato se retorna.

# Ejercicio 3

## Get1
![Get](https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/Get1.jpg)

## Post
![Get](https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/Post.jpg)

## Get final
![Get](https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/Get2.jpg)

*¿Qué diferencias se observan?*
Se le agregaron 5 líneas de código al url final, las mismas 5 de código que se le agregaron al body anteriormente.


# Ejercicio 4
Perfil personal trailhead
![GET](https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/Perfil%20peronal%20Trailhead.jpg)

# Ejercicio 5
|Objeto		| Definición 					| 
|---------------|-----------------------------------------------|
|Lead           |Registro de posible cliente que esta en proceso de evaluación.|			 
|Account	|Registro de un cliente, este puede ser de una empresa o persona individual|
|Contact	|Registro de la(s) persona(s) relacionada(s).|
|Opportunity	|Es la negociación de una venta.|
|Product	|Catalogo de productos o servicios que ofrece la empresa.|
|PriceBook	|Lista de precios de los productos y servicios.|
|Quote		|Es la cotización que se envia a los clientes.|
|Asset		|Producto comprado o instalado por el cliente.|
|Case		|Registro de una situación o problema de un cliente. un caso se puede asociar a un lead, a una cuentam a un contacto y a una oportunidad.|
|Article	|Documentos de información o procesos.   |

## Diagrama UML
![Diagrama UML](https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/DiagramaUML.jpg)
	
	
# Ejercicio 6
	Codigo en apex de la clase IdProContacto(https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/IdProcontacto.txt).
	Codigo en apex TriggerIdProcontacto (https://github.com/Kevinordonez09/Practica-KevinOrdonez/blob/main/TriggerIdProcontacto.txt).
	
	

# Ejercicio 7

### Soluciones de Salesforce
- *¿Qué es Salesforce?* Es una empresa americana de que hace software a gran escala tipo Google.
- *¿Qué es Sales Cloud?* Es una aplicación que gestiona las relaciones de Salesforce mediante la nube.
- *¿Qué es Service Cloud?* Son los servicios que se realizan en la nube.
- *¿Qué es Health Cloud?* En un software que permite ofrecer información medica del paciente a las entidades médicas.
- *¿Qué es Marketing Cloud?* Software y servicios de análisis y automatización de marketing digital. 

### Funcionalidades de Salesforce
- *¿Qué es un RecordType?*
	Es la herramienta que determina que proceso comercial, los diseños de página y los valores de lista de selección a los que los usuarios tienen acceso.
- *¿Qué es un ReportType?* 
	Es una plantilla que define los objetos y campos que estarán disponibles en el reporte que se creara.
- *¿Qué es un Page Layout?*
	Se encarga de controlar el diseño y organización de los botones, campos,  control, visualforce y listas relacionadas en las paginas de registro de objetos.
- *¿Qué es un Compact Layout?*
	Muestra los campos clave de un registro en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.
- *¿Qué es un Perfil?*
	Los perfiles se encargan de controlar al acceso a los datos y que pueden hacer en la aplicación de los usuarios.
- *¿Qué es un Rol?*
	Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización.
- *¿Qué es un Validation Rule?*
	Se encargan de verificar que los datos que el usuario ingresa en el registro cumple con los estándares solicitados antes de que el usuario pueda guardar el registro.
- *¿Qué diferencia hay entre una relación Master Detail y Lookup?*
	Master detail se basa en una clase principal(padre) y una secundaria(hijo), mientras que lookup se crea una relación entre dos objetos iguales.
- *¿Qué es un Sandbox?*
	Es una herramienta para copiar los metadatos desde la organización de producción a una de prueba.
- *¿Que es un ChangeSet?*
	Es una función que contiene solo las modificaciones y modifica la metadata.
- *¿Para qué sirve el import Wizard de Salesforce?*
	Funciona para importar cualquier dato estándar de Salesforce como objetos, cuentas, contactos, etc, fácilmente.
- *¿Para qué sirve la funcionalidad Web to Lead?* 
	Para recopilar información de los sitios web de la empresa.
- *¿Para qué sirve la funcionalidad Web to Case?*
	Para Recopilar solicitudes de atención al cliente directamente desde el sitio web de su empresa.
- *¿Para qué sirve la funcionalidad Omnichannel?*
	Para conectar a diferentes redes simultáneamente y en tiempo integral.
- *¿Para qué sirve la funcionalidad Chatter?*
	Para mantenerse conectado con sus constituyentes y en toda la organización internamente.

### Conceptos generales
- *¿Qué significa SaaS? Software As A Service       ¿Salesforce es Saas? Si.
- *¿Que significa que una solución sea Cloud?* 
	Que se puede conseguir el servidor de la nube de una página web.
- *¿Que significa que una solución sea On-Premise?* 
	Que se puede ejecutar desde el operador local del dispositivo y la empresa de hace cargo de la seguridad e disponibilidad.
- *¿Que es un pipeline de ventas?*
	Es el mapa de las actividades diarias que del proceso de ventas en el trabajo de un representante comercial.
- *¿Que es un funnel de ventas?* 
	Es una representación del ciclo o procesos de venta.
- *¿Qué significa Customer Experience?* 
	Es como percibe racional, física, emocional y/o psicológicamente cualquier parte de una empresa un cliente.
- *¿Qué significa omnicanalidad?*
	Es el uso de múltiples canales de comunicación para tener una mejor comunicación.
- *¿Qué significa que un negocio sea B2B?*
	Que es de empresa a empresa no al consumidor directamente.
- *¿Qué significa que un negocio sea B2C?* 
	Que es de empresa a consumidor directo.
- *¿Qué es un KPI?*
	Es un indicador de desempeño o rendimiento en un proceso.
- *¿Qué es una API y en qué se diferencia de una Rest API?*
	Es una interfaz de programación de aplicaciones, Rest api funciona con la arquitectura rest y permite la interacción con servicios web de restful.
- *¿Qué es un Proceso Batch?* 
	Es la ejecución de un programa sin el control o supervisión directa del usuario.
- *¿Qué es Kanban?*
	Es un sistema que controla armónicamente la fabricación de los productos necesarios en la cantidad y tiempo necesarios en cada uno de los procesos que tienen lugar tanto en el interior de la fábrica o una compañía.
- *¿Qué es un ERP? Son los sistemas gerenciales que integran y manejan negocios asociados a las operaciones de producción y de los aspectos de distribución de una compañía en la producción de bienes o servicios 
	¿Salesforce es un ERP?* Si, porque es un sofware que permite hacer de forma automatica prácticas de negocio.
