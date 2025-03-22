
<h1>Clip SDK Checkout Transparente</h1>
Integración de la API de Clip SDK Checkout Transparente en en lenguaje PHP. Dicha API permite procesar pagos con tarjetas de crédito o debito, la palabra "transparente" significa que no se mostraran elementos multimedia de la empresa CLIP, si no que el usuario lo percibirá como una pasarela propia del sitio web, la cual se puede personalizar a medida.
<br>
Para utilizar el SDK Checkout Transparente no necesitas tener certificación PCI (lo cual si es indispensable en la API de Checkout Transparente), esto permite que cualquier persona o empresa pueda integrar una pasarela personalizada visualmente y que se adapte a funciones específicas.

Al usar el SDK de este api, la información de las tarjetas de crédito/debito, no es manipulable ni se puede almacenar, todo queda en manos de clip, en lugar de eso se generara un token con una duración de 15 minutos el cual puede ser usado para las distintas operaciones que nos ofrece clip.

Para ejecutar el proyecto es necesario tener un servidor web y un SGDB, en mi caso uso lo que proporciona XAMPP.

Puedes descargar y pegar esta carpeta en “htdocs” la cual se encuentra dentro de la carpeta principal donde XAMPP se encuentre instalado.

Despues sistituye tu API KEY en el archivo api.php. Dicha API KEY la deberas generar desde tu panel de Clip como lo indica la documentación.

Documentación oficial: https://developer.clip.mx/docs/sdk-de-checkout-transparente
