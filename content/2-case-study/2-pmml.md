---
title : "PMML"
date : 2020-10-10T18:28:43-05:00
weight : 11
chapter : true
pre : "<b>2.1 </b>"
---

### Predictive Model Markup Language (PMML)

[PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) es un lenguaje XML para describir modelos predictivos y de minería de datos desarrollado por el Data Mining Group ([DMG](http://dmg.org/)) con el propósito de facilitar la portabilidad e interoperabilidad al ser de tecnología neutral.
Actualmente varias [tecnologías y herramientas](http://dmg.org/pmml/products.html) soportan PMML permitiendo exportar e importar modelos especificados en ese formato convirtiendo a PMML en un estándar de facto en la industria.

Las dos herramientas evaluadas en este estudio soportan PMML con el propósito de desacoplar el modelo analítico de las soluciones que lo implementan. El [archivo PMML utilizado](https://s3.amazonaws.com/ccastellanos87.bda.workshop.io/data/ChurnDTree.pmml) en este caso de estudio codifica un modelo de árbol de decisión que predice si  es probable (1) o no (0) el abandono de un cliente acorde a sus datos de llamadas y contrato. Tanto el modelo PMML como los datos de clientes son tomados de una [aplicación de ejemplo de churn](https://hub.knime.com/knime/spaces/Examples/latest/50_Applications/18_Churn_Prediction/) provista por el software Knime. 
![PMML](/images/pmml.png?width=700px)