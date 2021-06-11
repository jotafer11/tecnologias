---
title: "Subir Página a Github Pages"
date: 2021-05-01T15:34:30-04:00
categories:
  - Tutoriales desarrollo Web
tags:
  - Github
---

1. Ubicarse en la carpeta raíz del proyecto, luego ejecutar los siguientes comandos:

```sh

git init
git add .
git commit -m "message"
git remote add origin "github.com/your_repo.git"
git push -u origin master 

```

2. Asegurarse de haber agregado primero, y luego hacer el push.

3. Ir a Settings, apartado GitHub Pages, Seleccionar Main branch y carpeta proyecto (/docs).


