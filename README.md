# Configuración de Bodegas

### Escenario

Configura dos bodegas (warehouse) diferentes para un producto en la plataforma VTEX. La bodega A debe tener un stock de 50 unidades y la bodega B debe tener un stock de 100 unidades. Configura las prioridades de las bodegas para que las órdenes se despachen primero desde la bodega A.

#### Instrucciones
* Define las políticas de envío y las reglas de inventario
* Asegúrate de que las órdenes se despachen de acuerdo con la prioridad establecida

#### Entrega
* Proporciona capturas de pantalla de la configuración de las bodegas y las reglas de inventario
* Simula un pedido y muestra cómo se asigna el stock de acuerdo con la configuración.



# Servicios y modulos de VTEX

### Escenario 1

En la organización desean salir con una estrategia de regalo dependiendo del tipo de metodo de pago que el cliente utilice, el regalo solo sera asignado despues de realizar la compra.

¿Qué modulo o api de vtex me perfime obtener la información del metodo de pago y poder asignar el regalo correspondiente a la orden de forma automatica?

#### Argumento
* Explica cuál es la mejor estrategia para implementar esta funcionalidad dentro del ecosistema VTEX.

### Implementación
* Describir el flujo de trabajo que seguirías, incluyendo qué endpoints o servicios de VTEX utilizarías y cómo se integraría el sistema de regalos en el proceso de checkout.


### Escenario 2
* Tu equipo necesita consultar un endpoint externo cada 5 horas para enviar datos actualizados sobre una campaña en curso. Además, se requiere desarrollar un dashboard que muestre la información enviada a este servicio, permitiendo monitorear el rendimiento de la campaña en tiempo real.

#### Argumento
* Argumentar tu respuesta, ¿Cúal estrategia seria la más adecuada de las que tenga conocimiento?

#### Implementación
* Detalla cómo configurarías el entorno en VTEX IO, qué módulos o servicios utilizarías para realizar las consultas periódicas y cómo diseñarías el dashboard para visualizar los datos de la campaña.

### Escenario 3

La empresa cuenta con múltiples bodegas distribuidas en diferentes ciudades. Necesitan asegurarse de que el stock de productos se actualice en tiempo real en la tienda en línea, reflejando la disponibilidad en cada bodega. Además, si una bodega se queda sin stock, los pedidos deben redirigirse automáticamente a la siguiente bodega con stock disponible más cercana.

#### Argumento
* Justifica la elección de los módulos o APIs que creas que se pueden utilizar

#### Implementación
* Explica cómo configurarías las prioridades de las bodegas, cómo manejarías la sincronización de stock en tiempo real, y cómo garantizarías la correcta asignación de pedidos en caso de falta de stock

### Escenario 4

El equipo de atención al cliente quiere automatizar ciertos procesos post-venta, como la generación de facturas y el envío de notificaciones de seguimiento de pedidos. También desean implementar un sistema que ofrezca la opción de agregar una encuesta de satisfacción después de que un pedido haya sido entregado.

¿Qué servicios o módulos de VTEX utilizarías para automatizar estos procesos y agregar la encuesta de satisfacción?

#### Argumento
* Describe que modulos podrías utilizar

#### Implementación
* Proporciona un plan detallado de cómo configurarías las automatizaciones, qué servicios utilizarías para cada tarea, y cómo asegurarías que la encuesta de satisfacción se envíe de manera oportuna después de la entrega

### Escenario 5
La empresa quiere lanzar un programa de lealtad en el que los clientes puedan acumular puntos por cada compra realizada. Estos puntos se pueden canjear por descuentos en futuras compras. Necesitan que este sistema se integre con la plataforma VTEX de manera que los puntos se calculen y apliquen automáticamente

#### Argumento
* Explica qué herramientas de VTEX se pueden utilizar para llevar acabo este escenario y que utilizarías para configurar y gestionar el programa de lealtad, y cómo asegurarías la correcta acumulación y redención de puntos.

#### Implementación
* Detalla el proceso de integración del sistema de puntos con el checkout, cómo manejarías las reglas de acumulación y redención, y cómo mostrarías el saldo de puntos a los clientes durante el proceso de compra


### Escenario 6

La empresa quiere expandir su alcance vendiendo en varios marketplaces externos como Amazon y eBay. Necesitan que su catálogo de productos, precios, y stock estén sincronizados en tiempo real con estos marketplaces, y que los pedidos realizados en los marketplaces se gestionen desde la plataforma VTEX.

¿Qué estrategia y módulos de VTEX utilizarías para integrar el catálogo y la gestión de pedidos con marketplaces externos, asegurando una sincronización en tiempo real?

#### Argumento
* Explica cómo podrías sincronizar productos, precios, y stock con los marketplaces, y cómo gestionarías los pedidos recibidos

#### Implementación
* Proporciona un plan de integración, incluyendo cómo manejarías las actualizaciones de inventario y precios, y cómo asegurarías que los pedidos de los marketplaces se integren sin problemas en el flujo de trabajo de VTEX.
