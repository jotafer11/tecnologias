---
title: "Crear proyecto firebase, config db"
date: 2021-05-01T15:34:30-04:00
categories:
  - Tutoriales desarrollo Web
tags:
  - Firebase
---

Crear proyecto en firebase e instalar modulo firebase con

```sh
npm install firebase @angular/fire --save
```


Crear firestore db en firebase, configurar, importar en app.module

```sh
import { AngularFireModule } from '@angular/fire';
import { environment } from '../environments/environment'


imports: [

    AngularFireModule.initializeApp(environment.firebaseConfig)
    
],
```


Importar servicios de firestore en app.module y en el servicio.
```sh
import { AngularFirestoreModule } from '@angular/fire/firestore'; 
```
