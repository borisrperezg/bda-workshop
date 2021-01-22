---
title : "Vistas"
date : 2020-10-10T18:28:43-05:00
weight : 18
chapter : true
pre : "<b>2.3 </b>"
---


### Vistas de Arquitectura
Las vistas son una representación de la arquitectura que tiene significado para uno o más usuarios en el sistema abordando sus principales preocupaciones. 
Las vistas funcional y de despliegue para el caso de estudio propuesto se presentan a continuación:



#### Vista Funcional
Describe el conjunto de tres componentes que separan la responsabilidades de recolectar los datos, estimar la probabilidad de abandono y almacenar las estimaciones realizadas. Los dos conectores se encargan de comunicar los componentes mencionados.

![Vista Funcional](/images/fv-view.png?width=660px)

#### Vista de Despliegue

Describe los nodos de computación y entornos de ejecución donde se desplegaran los diferentes artefactos (componentes y conectores) descritos en la vista funcional.

![Vista de Despliegue](/images/dv-view.png?width=500px)