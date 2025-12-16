# SweetByte Cupcakes
En la actualidad, las pequeñas pastelerías y negocios de repostería necesitan herramientas digitales que les permitan presentar sus productos y gestionar su contenido de manera eficiente. Sin embargo, muchos de estos negocios carecen de una solución tecnológica que organice su catálogo de cupcakes, sabores, decoraciones, precios y pedidos básicos.
La creación de un sitio web desarrollado en Python con Flask surge como una respuesta a esta necesidad, ya que permite mostrar de forma clara los cupcakes disponibles, registrar pedidos simples y ofrecer una experiencia visual agradable para los clientes.
Esta plataforma facilitará la administración del catálogo de productos y mejorará la presencia digital de la pastelería, permitiendo una mejor toma de decisiones y una experiencia más profesional.

![image](https://github.com/Liftny/SweetByte-Cupcakes/blob/main/Cupcakes1.jpg?raw=true)


## Características clave del sitio
### Página principal (Home)
- Bienvenida y presentación de la marca SweetBiteCupcakes.
- Imágenes destacadas de cupcakes artesanales.
- Botón de acceso directo al catálogo de productos.

### Catálogo de productos
- Lista organizada de cupcakes disponibles.
- Información detallada de cada producto: nombre, sabor, descripción y precio.
- Botón “Agregar al pedido”, gestionado mediante sesiones del servidor.

### Personalizador de cupcakes
- Formulario interactivo para seleccionar sabor, topping y decoración.
- Envío del pedido mostrando un resumen básico de la personalización seleccionada.

### Contacto
- Formulario para el envío de mensajes por parte del cliente.
- Validación de correo electrónico (solo dominios Gmail y Hotmail).
- Visualización de datos ficticios de la empresa.

### Arquitectura backend en Python
- Servidor backend desarrollado en Python utilizando el framework Django.
- Sistema de rutas separadas mediante archivos urls.py.
- Uso de plantillas HTML dinámicas mediante el sistema de templates de Django.
- Manejo de sesiones para pedidos básicos.

### Diseño responsive
- Estilos CSS sencillos y personalizados.
- Uso de Bootstrap para un diseño responsive adaptable a distintos dispositivos.

## Propósito
El propósito principal de SweetByte Cupcakes es proporcionar un sitio web intuitivo y visualmente atractivo, donde se pueda presentar un catálogo organizado de cupcakes artesanales.
El proyecto busca facilitar la interacción entre el cliente y la empresa ficticia, permitiendo consultar sabores, precios, decoraciones disponibles y realizar pedidos básicos a través del sitio.
Además, al estar desarrollado en Python/Flask, sirve como una solución simple, escalable y funcional para pequeños negocios que buscan digitalizar sus servicios.

![image](https://github.com/Liftny/SweetByte-Cupcakes/blob/main/Cupcakes.webp?raw=true)

## Objetivos
### Presentar un catálogo organizado de cupcakes:
- Mostrar sabores, descripciones y precios de manera clara y atractiva para el usuario.
### Mejorar la presencia digital del negocio:
- Ofrecer una plataforma accesible y visualmente profesional desarrollada en Python utilizando el framework Django.
### Facilitar la interacción con el cliente:
- Permitir un sistema básico de pedidos mediante botones y formularios, sin necesidad de registro previo.
### Optimizar la organización interna:
- Contar con una estructura de datos básica que pueda ampliarse a futuro para la gestión de pedidos, personalización y clientes.

## Contexto del Problema
### Definición del problema
Las pastelerías tradicionales suelen tener dificultades para mostrar sus productos de forma organizada y profesional en Internet. Esto puede afectar su visibilidad, sus ventas y la comunicación con sus clientes.
Sin una plataforma digital adecuada, la presentación del catálogo, los precios, las personalizaciones y los pedidos puede volverse desordenada e ineficiente.
Además, la falta de un sistema centralizado impide que el negocio ofrezca una experiencia moderna que facilite la selección de productos y mejore su competitividad en el mercado.

### Justificación del proyecto
El desarrollo de SweetByte Cupcakes permitirá contar con una solución digital clara y funcional que muestre el catálogo del negocio ficticio y permita la interacción directa con los clientes.
Este sitio web optimizará la presentación de los productos, facilitará la gestión de la información y brindará una base tecnológica que puede expandirse con nuevas funciones (carrito, registro de usuarios, personalización avanzada, etc.).
Esto contribuye a una mayor eficiencia, una mejor imagen y una experiencia más atractiva para los usuarios.

## Estructura

![image](https://github.com/Liftny/SweetByte-Cupcakes/blob/main/Diagrama%20de%20flujo.png?raw=true)

