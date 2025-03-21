# API SDK Checkout Transparente de Clip
Integración de la API de clip Checkout Transparente en en lenguaje PHP. Dicha API permite procesar pagos con tarjetas de crédito o debito, la palabra "transparente" significa que no se mostraran elementos multimedia de la empresa CLIP, si no que el usuario lo percibirá como una pasarela propia del sitio web, la cual se puede personalizar a medida.

Para utilizar el SDK no necesitas tener certificación PCI, lo cual si es indispensable en la API de Checkout Transparente, esto permite que cualquier persona o empresa pueda integrar una pasarela personalizada visualmente y que se adapte a funciones específicas. 

Al usar el SDK de este api, la información de las tarjetas de crédito/debito, no es manipulable ni se puede almacenar, todo queda en manos de clip, en lugar de eso se generara un token con una duración de 15 minutos el cual puede ser usado para las distintas operaciones que nos ofrece clip.

Para ejecutar el proyecto es necesario tener un servidor web y un SGDB, en mi caso uso lo que proporciona XAMPP.

Puedes descargar y pegar esta carpeta en “htdocs” la cual se encuentra dentro de la carpeta principal donde instalaste XAMPP.

*Opcional: Importar la base de datos en el SGBD de MySQL y haz los cambios necesarios adaptados a tu proyecto. 

Documentación oficial: https://developer.clip.mx/docs/sdk-de-checkout-transparente

