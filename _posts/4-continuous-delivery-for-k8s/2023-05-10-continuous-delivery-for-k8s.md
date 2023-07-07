---
title:  Continuous Delivery for Kubernetes. (WIP) 
date: 2023-05-10 18:03:55 +07:00
modified: 2023-05-10 18:03:55 +07:00
tags: [Books]
description: Resumen
image: ""
---


¡Hola!

Estoy leyendo y aprendiendo cantidad de cosas con este libro de Mauricio Salatino "Continuous Delivery for Kubernetes". <a href="https://www.manning.com/books/platform-engineering-on-kubernetes?utm_source=linkedin&utm_medium=organic&utm_campaign=book_salatino2_continuous_9_18_21" target="_blank" rel="nofollow">Os dejó el enlace para echarle un vistazo.</a>

En este blog dejaré mis apuntes de las prácticas y técnicas clave que voy descubriendo en el libro y empezar en el contexto de Kubernetes.

Parte 1. Cloud-Native continuous delivery.
"Cloud-Native is structuring teams, culture and technology to utlize automation and architectures to manage complexity and unlock velocity."

<h2> "12-factorss apps" </h2>
<ol>
<li>Codebase. One codebase tracked in revision control, many deploys.</li>
<li>Dependencies. Explicitly declare and isolate dependencies.</li>
<li>Config. Store config in the enviroment.</li>
<li>Backing services. Treat backing services ass attached resosurces.</li>
<li>Build, release, run. Strictly separate build and run stages.</li>
<li>Processes. Execute the app as one or more stateless processes.</li>
<li>Port binding. Export services via port binding.</li>
<li>Concurrency. Scale out via the process model.</li>
<li>Disposability. Maximize robustness with fast startup and graceful shutdown.</li>
<li>Dev/prod parity. Keep development, staging and production as similar as possible.</li>
<li>Logs. Treat logs as events streams.</li>
<li>Admin processes. run admin/management tasks as one-off processes.</li>
</ol>
<hr>
The term Cloud-Native is also strongly related to container tech (such as Docker) because containers by design folows best practices from the 12-factors apps principles as they were designes qith Cloud-Native applications and clloud infrastructures in mind.
<hr>
You are only interested in having yours applications running, not where they run.



¡Gracias por leer!
C.








