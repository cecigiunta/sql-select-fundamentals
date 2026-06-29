# SQL Select Fundamentals

## Descripción
Este proyecto corresponde al trabajo práctico de la unidad 1 del Módulo 4 del Curso Data Analytics.

## Propósito del ejercicio
En esta práctica se construye desde cero la base de datos Ventas_Tech_DB y la tabla "sales".
Luego se realizan consultas con SELECT y se utilizan alias con la clausula AS.

## Tecnologías utilizadas
- SQL
- Git
- GitHub

## ¿Por qué es mala práctica usar SELECT * en producción? 
Usar SELECT * en producción degrada el rendimiento de la aplicación y la estabilidad del sistema. 
Provoca un consumo excesivo de memoria.
También genera problemas de ambigüedad: Al unir tablas, si ambas tienen columnas con nombres idénticos (como id o created_at), SELECT * puede devolver nombres duplicados.

## ¿Por qué son importantes los alias para un stakeholder no técnico? 
Son importantes porque ayudan a la comprensión de los datos/columnas. Pueden simplificar nombres y barreras de idioma. 
Con esto, se mejora la claridad y el contexto del proyecto

