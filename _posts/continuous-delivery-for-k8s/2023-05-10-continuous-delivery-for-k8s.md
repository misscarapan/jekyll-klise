---
title:  Continuous Delivery for Kubernetes. 
date: 2023-05-10 18:03:55 +07:00
modified: 2023-05-10 18:03:55 +07:00
tags: [Books]
description: Resumen
image: ""
---

<a 

¡Hola!

Este post es para guardar todas mis apuntes del libro de Mauricio Salatino "Continuous Delivery for Kubernetes". 

Parte 1. CLoud-Native continuous delivery.
"Clod-Native is structuring teams, culture and technology to utlize automation and architectures to manage complexity and unlock velocity."

"12-factorss apps"
I. Codebase. One codebase tracked in revision control, many deploys.
II. Dependencies. Explicitly declare and isolate dependencies.
III. Config. Store config in the enviroment.
IV. Backing services. Treat backing services ass attached resosurces.
V. Build, release, run. Strictly separate build and run stages.
VI. Processes. Execute the app as one or more stateless processes.
VII. Port binding. Export services via port binding.
VIII. Concurrency. Scale out via the process model.
IX. Disposability. Maximize robustness with fast startup and graceful shutdown.
X. Dev/prod parity. Keep development, staging and production as similar as possible.
XI. Logs. Treat logs as events streams.
XII. Admin processes. run admin/management tasks as one-off processes.

The term Cloud-Native is also strongly related to container tech (such as Docker) because containers by design folows best practices from the 12-factors apps principles as they were designes qith Cloud-Native applications and clloud infrastructures in mind.

You are only interested in having yours applications running, not where they run.



¡Gracias por leer!
C.








