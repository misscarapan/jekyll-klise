---
layout: post
title:  "The beginning of Carapan"
date:   2023-04-29 09:29:20 +0700
categories: Training
tags: [Training]
---
¡Hola!

Este blog quería compartir algunos enlaces que me fueron de gran ayuda durante el proceso de despliegue de este sitio web. 

Para entrar un poco en contexto, esta web es mi primer proyecto con algo de conocimiento. En diciembre de 2022, saqué mi primera certificación como Solutions Architect de AWS y tenía muchas ganas de hacer cositas. Así que aquí estoy, dando forma a una web estática para ver como os cuento mi proceso.

Sin dar mucha chapa, desplegar todo no fue muy difícil, con la documentación, paciencia y lo que había estudiado, al final esto no es lo más complejo que puedes hacer en la nube, pero tuve probleminas, así que aquí os dejo un poco los enlaces que me ayudaron.

 Jekyll - esta web personal está configurada en este entorno de desarrollo. Aquí dejo el enlace con el paso a paso.
<a href="https://jekyllrb.com/docs/step-by-step/01-setup/" target="_blank" rel="nofollow">Docs Jekyll</a>


S3 + CloudFront: 
Para configurar y desplegar la web de forma escalable y segura usé AWS me ayudaron estos enlaces.
<a href="https://aws.amazon.com/es/blogs/aws-spanish/como-alojar-tu-sitio-web-estatico-en-amazon-s3-y-amazon-cloudfront/" target="_blank" rel="nofollow">Documentación S3 y CloudFront</a>


<a href="https://dev.to/aws-builders/deploy-static-website-on-s3-bucket-and-configure-cloudfront-distribution-12em" target="_blank" rel="nofollow">Blog ayuda web estática con S3 y CloudFront.</a>


S3 + Hosting: Para el proceso de configuración de DNS, crear el alias y asociar el dominio personalizado con el bucket utilicé esta documentación.

<a href="https://docs.aws.amazon.com/es_es/AmazonS3/latest/userguide/website-hosting-custom-domain-walkthrough.html" target="_blank" rel="nofollow">Documentación S3 custom domain</a>

Me dió error jajaja (estaba claro) pero en esta guía tienes información sobre el enrutamiento y redireccionamiento de URLs, que fue lo que me ayudó a arreglar el problema.
<a href="https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html" target="_blank" rel="nofollow">Solución Error 404</a>

Google Analytics: para utilizar GA en Jekyll, no es obligatorio, pero ya puestos,en comparación es bastante sencillo.
<a href="https://michaelsoolee.com/google-analytics-jekyll/" target="_blank" rel="nofollow">Blog Google Analytics</a>

Y esta es un poco mi experiencia, al final, seguir un poco la documentación, calma y cariño. 


Gracias por leer,
<hr>
C.
