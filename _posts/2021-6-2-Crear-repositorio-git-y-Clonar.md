---
title: "Crear repositorio Git y Clonar"
date: 2021-05-01T15:34:30-04:00
categories:
  - Tutoriales desarrollo Web
tags:
  - Github
---

.Ubicarse en la carpeta raíz del proyecto, luego ejecutar los siguientes comandos:

```sh
git init
git add .
git commit -m "message"
git remote add origin "github.com/your_repo.git"
git push -u origin master 
```

.Para clonar, ubicarse carpeta raiz donde queremos clonar, luego ejecutar:

```sh
git clone https://github.com/jotafer11/'nombre-proyecto'.git
```

.Iniciar proyecto clonado: `npm install`: dependencias necesarias, `npm start` para iniciar.
