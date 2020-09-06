# Lambda@Edge

Lambda@Edge es una característica de Amazon CloudFront que permite ejecutar el código más cerca de los usuarios de la aplicación, lo cual mejora el rendimiento y reduce la latencia. Con Lambda@Edge, no es necesario aprovisionar ni administrar la infraestructura en diversas partes del mundo. Solo pagará por el tiempo de computación que consuma. No se cobra nada cuando el código no se está ejecutando.
[Más información](https://aws.amazon.com/es/lambda/edge/)

En este repositorio entontraras un template de Cloudformation para que puedas experimentar, junto con el video de [Youtube de Leo Codigo](https://www.youtube.com/channel/UCfOCW9QaQRzO3rGvHSYJsiQ)


La arquitectura es como se muestra en la siguiente imagen:

[<img src="https://s3.amazonaws.com/templates-cf.cancunlabs.com/images/lambda-at-edge-leo-codigo.png">](https://s3.amazonaws.com/templates-cf.cancunlabs.com/images/lambda-at-edge-leo-codigo.png)


[<img src="https://s3.amazonaws.com/templates-cf.cancunlabs.com/cloudformation-launch-stack.png">](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=LambdaAtEdgeTest&templateURL=https://s3.amazonaws.com/templates-cf.cancunlabs.com/lambda-at-edge.template)


> Cuando se termine de crear los recursos del template, agrega un archivo index.html en el buckets que creaste.