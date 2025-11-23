# Práctica 1: Captura de requisitos software y diseño
* **Asignatura:** Ingeniería del Software (IS, GIA) 
* **Curso:** 2025-2026
* **Grupo:** G04

---

## Integrantes y Roles 

* **Jefe de Proyecto:** [David Hernandez Esteban](https://github.com/Daby7777)
* **Analista Software:** [Victor Bravo Vivas](https://github.com/vibrav19)
* **Analista Software:** [Eneas Ramirez Ocaña](https://github.com/EneasRO)
* **Arquitecto Software:** [Francisco Jiménez Gómez](https://github.com/gomprogramming)
* **Arquitecto Software:** [Jesús Humanes Cuadrado](https://github.com/Chechu13)
* **Arquitecto Software:** [Jorge Higuera Herrero](https://github.com/reni8912)

---

## Descripción Del Caso De Estudio 

ANEXO: Caso de estudio
El transporte ferroviario dispone de elementos eléctricos de alta y baja tensión. En concreto, las
vías de tren disponen de unos dispositivos que envían señales eléctricas en voltios para saber si
un tren está ocupando o no la vía. En función de esos valores es posible que surjan incidencias
que hay que detectar y predecir. En este sentido, el software que se pretende diseñar es una
aplicación Web basada en protocolos HTTP/REST y debe contar con las siguientes
funcionalidades:
 Un elemento que lea los valores de voltajes de las vías desde un fichero CSV con la hora
en formato (HH:MM:SS:MS) y un valor binario (0/1) que indica el estado. Por cada vía
de tren pueden existir múltiples dispositivos cada cierto número de metros. Cada
dispositivo debe llevar un identificador.
 Una funcionalidad que detecte si hay un tren en la vía en función del valore binario (1:
vía libre, 0: hay un tren)
 Un módulo inteligente que detecte y sea capaz de predecir tipos de incidencias en
función de los valores. De los tipos posibles solo vamos a considerar los siguientes: (i)
ausencia de datos por bloqueo prolongado donde un dispositivo de vía no emite datos
por un periodo de más de 2 minutos, (ii) saltos de frecuencia de al menos 0.5 voltios.
 Un módulo de suscripción a incidencias por parte de los usuarios del sistema donde se
pueden publicar diferentes tipos de incidencias.
 Un módulo de visualización que muestre gráficamente las incidencias en función de los
valores de los voltajes.

---

## Estructura Del Repositorio

* Archivos de los diagramas en UML en la carpeta ([UMLs](UMLs))
* La memoria se encuentra en la carpeta ([Memoria](Memoria))
---

## Herramientas Utilizadas 

* Para almacenar información se ha utilizado este repositorio de GitHub.
* Para el desarrollo de los diagramas UML se ha utilizado la herramienta ([StarUML](https://staruml.io)).
* Para la organización de las tareas se ha utilizado la herramienta ([Trello](https://trello.com/b/YNkNkZTs/ispractica1))
