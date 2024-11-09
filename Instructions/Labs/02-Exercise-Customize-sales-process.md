---
lab:
  title: 'Ejercicio 1: Personalizar el proceso de ventas.'
---

# Ejercicio 1: Personalizar el proceso de ventas.

## Escenario: Contoso Home Security 
Contoso Home Security es una empresa de supervisión y equipos de seguridad residencial directos al consumidor. Sus productos incluyen timbres inteligentes, termostatos inteligentes, sistemas de seguridad, sensores de humedad, etc. Puesto que son directos al consumidor, sus productos se venden en línea o en sus tiendas minoristas en 11 de las principales ciudades de EE. UU. A los clientes en línea se les asigna un representante de cuenta. Su rol es realizar un seguimiento con el cliente e intentar proporcionarles productos y servicios adicionales. 

### Proceso de ventas de Contoso
Los representantes de cuentas se asignan a las cuentas corporativas que buscan soluciones de seguridad. Las ventas corporativas suelen tardar más tiempo e incluyen varias fases y tareas diferentes.

Un ejemplo del proceso de ventas puede incluir las siguientes fases:

-   **Calificar:** aquí es donde el ejecutivo cuentas intenta determinar si sería una buena opción para un cliente.
-   **Desarrollar:** aquí es donde el ejecutivo de cuentas trabaja con otros miembros del equipo de ventas para crear la solución que mejor se adapte al cliente. Durante esta fase, los ejecutivos de cuentas deben incluir productos relevantes del catálogo de productos de Contoso.
-   **Presupuesto:** aquí es donde el ejecutivo elaborará y entregará un presupuesto al cliente. El presupuesto puede pasar por varias iteraciones antes de que el cliente lo acepte.
-   **Comprobación técnica:** esta fase solo se aplica a las ofertas que se valoran en más de 20 000,00 dólares. Un consultor técnico debe comprobar la solución antes de cerrarla.
-   **Cierre:** aquí es donde el ejecutivo de cuentas repasa la oferta una vez más y se asegura de que el cliente está listo para aceptarla.

### Generación de clientes potenciales 
Contoso también tiene un programa de generación de clientes potenciales que usan para maximizar las posibilidades de cerrar un negocio. El programa de generación de clientes potenciales consta de lo siguiente:

1.  **Llamada telefónica de introducción:** el ejecutivo de cuentas llama al cliente para presentar Contoso y los productos que vendemos.
2.  **Correo electrónico informativo:** un día después de la llamada telefónica inicial, el ejecutivo de cuentas envía al cliente un correo electrónico. El correo electrónico incluye detalles sobre Contoso Home Security y los productos que venden.
3.  **Correo electrónico de control:** tres días después del correo electrónico introducción, se envía otro correo electrónico al cliente para ver si tiene alguna pregunta que podamos responder.
4.  **Llamada telefónica para programar una cita:** dos días después del correo electrónico de control, debe recibir otra llamada telefónica donde el ejecutivo de cuentas intenta obtener una reunión con el cliente para calificarlo o descalificarlo.

### Detalles importantes
-   El proceso de generación de clientes potenciales solo debe aplicarse a los clientes etiquetados como cuentas corporativas.
-   Contoso Home Security no hace referencia a sus oportunidades como oportunidades: las llaman **Ofertas.**
-   Las ofertas por un valor superior a los \$20,00.00 requieren comprobaciones técnicas. Este paso es necesario y la oferta no puede seguir adelante si no se ha realizado.
    -   La comprobación técnica y sus detalles deben anotarse y registrarse con la oferta. Deben identificar qué miembro del equipo la hizo, la fecha en que se realizó y cualquier otro detalle relevante. Si todo está en orden, eso también debe anotarse.
-   No todas las ventas de Contoso se registran en su sistema de CRM.
    -   Las transacciones de sus tiendas minoristas se almacenan en un sistema independiente de punto de venta.
    -   Las transacciones en línea se almacenan en un sitio de comercio electrónico independiente.
-   Contoso también tiene un programa de fidelidad en el que los clientes pueden inscribirse. Esta información también se almacena en un sitio independiente.

Dado que Contoso tiene la información de los clientes en varios lugares, a menudo tienen dificultades para mantener un conocimiento completo de quién es el cliente en todas sus organizaciones. Quieren una manera de consolidar todos estos datos en una única vista.

Los orígenes de datos se pueden encontrar en las siguientes rutas de acceso de archivo CSV:
- **Clientes:**https://aka.ms/CI-ILT/Contacts
- **Transacciones comerciales de PDV:**https://aka.ms/CI-ILT/POSPurchases
- **Transacciones en línea:**https://aka.ms/CI-ILT/OnlinePurchases
- **Clientes del programa de fidelidad:**https://aka.ms/CI-ILT/LoyaltySchemeCustomers

