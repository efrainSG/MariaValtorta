# MariaValtorta
El poema de El Hombre-Dios.
--------------------------

## Objetivo

El objetivo principal es ajustar el formato para que pueda ser leido por personas con dificultad visual. Todo está en tamaño carta vertical y para ser impreso por ambos lados, por lo que el ancho de cada volumen es aproximadamente la mitad del número de páginas indicadas (estos números irán cambiando conforme vaya avanzando.

## Organización de los escritos

Está organizado en la misma forma que se encuentra en http://www.reinadelcielo.org/el-evangelio-como-me-fue-revelado-poema-de-el-hombre-dios-mar%EE%A1%ADvaltorta/

1. Introducción y vida oculta de Jesús _+300 páginas en formato Word 18 pt, 172 páginas en formato TeX (agrego páginas según avanzo en Word)_
2. Primer año de la vida pública de Jesús
3. Segundo año de la vida pública de Jesús
4. Tercer año de la vida pública de Jesús
5. Preparación a la Pasión de Jesús
6. Pasión y Muerte de Jesús
7. Glorificación de Jesús y María

## Organización del proyecto

El proyecto está organizado en:
* **Formato de Word 12pt**
* **Formato de Word 18pt**
* **TeX** editado en LaTeX para un formato más sobrio, formal y en archivos PDF

## Comentarios

* Con esta secuencia emulo el título de capítulo y su subtítulo agregando solo el primero a la tabla de contenidos, además de que quita el texto "Capítulo X" del contenido.
\chapter\*{_<Título>_ \\ \normalfont\normalsize\textit{ _<Subtítulos>_ }}
\addcontentsline{toc}{chapter}{\normalfont\scshape{ _<Título>_ }}
* Ya incluyo portada.
\begin{titlepage}
\centering
\vspace{3.5cm}
{\scshape\LARGE El Evangelio\\como me fue revelado \par}
\vfill
{\scshape\Large María Valtorta \par}
\vfill
{\itshape \url{http://www.reinadelcielo.org/el-evangelio-como-me-fue-revelado-poema-de-el-hombre-dios-mar%EE%A1%ADvaltorta/} \par}
\vfill
Reina del Cielo
\end{titlepage}
