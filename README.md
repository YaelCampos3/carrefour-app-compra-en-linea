### **Proyecto: Mejora del módulo de compra en línea — Carrefour Argentina**



Estudiante: Campos Vanina Yael

Asignatura: Organización empresarial - UTN - TUP

Repositorio GitHub: https://github.com/YaelCampos3/carrefour-app-compra-en-linea

Proyecto GitHub: https://github.com/users/YaelCampos3/projects/1/views/1



##### **Descripción del proyecto**



El presente proyecto tiene como objetivo desarrollar y optimizar el módulo de compra en línea y finalización de pedidos de la aplicación móvil de Carrefour Argentina.



La propuesta busca mejorar la estabilidad, velocidad y confiabilidad del proceso de compra, desde la búsqueda de productos hasta la confirmación del pedido y el pago. También contempla la correcta integración con los sistemas de inventario, precios y promociones, medios de pago y logística.



El proyecto surge a partir de problemas identificados en el proceso de compra digital, como la lentitud en la carga y actualización del carrito, la disponibilidad de productos y los errores durante la finalización del pago.



##### **Objetivo general**



Desarrollar y optimizar el módulo de compra en línea y finalización de pedidos de la aplicación móvil de Carrefour Argentina, en un plazo de seis meses, para mejorar la estabilidad, velocidad y confiabilidad del proceso de compra y su integración con los sistemas relacionados.



##### **Funcionalidades contempladas**



* Consulta del catálogo, búsqueda y filtros de productos.
* Administración del carrito de compras y actualización de cantidades.
* Validación de disponibilidad de productos en inventario.
* Consulta y aplicación de precios, promociones y cupones.
* Integración con medios de pago.
* Registro y seguimiento del estado de los pedidos.

Coordinación con los procesos de preparación, facturación y logística.

* Gestión de productos faltantes, errores de pago y posibles reintegros.



##### **Documentación del proyecto**



El repositorio reúne la documentación técnica y organizativa elaborada durante las distintas etapas del trabajo práctico.



###### **Entre los documentos previstos se incluyen:**



* Análisis FODA del proyecto.
* Objetivo general y metas cuantitativas.
* Diagrama de Gantt y planificación de tareas.
* Organigrama del área de Sistemas.
* Diccionario de datos inicial.
* Diagrama BPMN del proceso de compra en línea.
* Historias de usuario y seguimiento del backlog.



##### **Estado del proyecto**



En desarrollo — Proyecto académico.



##### **Declaración de uso de IA**



Herramientas utilizadas: Claude (Anthropic) y ChatGPT (OpenAI).



Uso general: apoyo para sugerir ejemplos, organizar entidades y estructura de los documentos, revisar la redacción



Prompt:

*Te adjunto las entregas anteriores del trabajo integrador y la descripción de mi proyecto de la app carrefour y en base a él crea un diagrama BPMN que comience con el pool externo (cliente) quien selecciona los productos, los agrega al carrito y realiza la compra, la compra ingresa a los pools internos, primero al sistema de ventas, el pedido se recibe, se verifica y con una compuerta se ve si los datos están correctos o no para ingresar el pedido, si están correctos el pedido ingresa a la sucursal o depósito, sino se deben solicitar los datos nuevamente( lo que no se es si en esta parte vuelve al cliente a que vuelva a poner los datos correctos), luego de ingresado a sucursal o depósito se verifique si hay stock de todos los productos para armar el pedido, si no hay stock notificar la falta de producto y generar el reintegro de ese faltante, actualizar el pedido y continuar la preparación del mismo, una vez preparado pase área de facturación para que emitan la factura y posteriomente pase al área de logística para realizar la entrega, luego que vuelva al cliente con un mensaje confirmación de pedido y finalmente termine el diagrama con el círculo de "Fin".*

*Por otro lado organiza de manera formal la redacción que acompañe el diagrama bpmn usando las instrucciones que te di para generar el mismo.*

El diagrama generado presentaba errores críticos, con líneas irracionales que salían del diagrama sin llegar a ningún evento o decisión, finalmente el diagrama se realizó manualmente en Canva, se utilizó parte de la estructuración de la redacción de modo que la explicación del diagrama sea más clara y profesional.



Prompt:



*Necesito crear un diccionario de datos basados en el proyecto del módulo de compra online de la app Carrefour, te pido que me des ejemplos pero la idea principal es tener las siguientes entidades: cliente(con sus datos personales, de contacto y ubicación), producto(nombre, categoría, precio y stock), pedido(productos seleccionados, cantidades y precios de los mismos, sucursal, método y costo de entrega, estado y precio final) y por último el pago(medio de pago, monto, estado).*



Ayudó a organizar las entidades permitiendo evidenciar que los datos del pedido y los detalles del pedido debían realizarse en entidades separadas ya que sinó generarían inconsistencias.



El contenido fue revisado, corregido y aprobado.

