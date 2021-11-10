# ChoucairEvaluationTest
Ecommerce WebSite Automation Test

En este repositorio encontrara todos los codigos en arquitectura POM, contando con una Base Page, las clases Page y las clases Test.
Se Implemento Maven como gestor de dependecias.

El codigo BasePage se implemento para todas las pruebas de automatizacion, en este se declaraon las acciones de Selenium necesarias para las pruebas.

- En la primera prueba se realiza el registro de un usurio en la plataforma WEB:

El codigo RegisterHomePage contiene todos los localizadores y acciones necesarias para registrar el usuario exitosamente.

El codigo RegisterTest contiene la prueba en Junit que verifica la correcta creacion del usuario.

- En la segunda prueba se verifica que el usuario haya sido correctamente registrado en la plataforma WEB iniciado sesion con las credenciales registradas previamente.

El codigo SignInUser contiene todos los localizadores y acciones necesarias para ingresar a la plataforma WEB.

El codigo SignInVerification contiene la prueba en Junit que verifica el correcto inicio de sesion del usuario registrado.

- En la tercera prueba se verifica la correcta busqueda de un producto y que este sea agregado al carro de compras exitosamente.

El codigo ItemSearchPage contiene todos los localizadores y acciones necesarias para realizar la busqueda del producto.

El codigo ItemSearchTest contiene la prueba en Junit que verifica la correcta busqueda y adicion al carro de compras del producto elegido.

- En la cuarta prueba se verifica el correcto funcionamiento de la seccion Contac Us verificando que el mensaje de contacto se envie exitosamente.

El codigo SendContactMessage contiene todos los localizadores y acciones necesarias para realizar el envio del mensaje de contacto.

El codigo ContactMessageTest contiene la prueba en Junit que verifica el correcto envio del mensaje de contacto.

---------------------------------------------------------------------------------------------------------------------------------------

Adicional se realizo una quinta prueba la cual consistio en ir al sitio WEB, ingresar con un usuario previamente registrado, buscar un producto, agregarlo al carro de compras y realizar el pago, al final se captura, compara e imprime el mensaje esperado de confirmacion de la orden de compra

Este es el codigo BuyConfirmation y fue hecho sin estructura POM.

