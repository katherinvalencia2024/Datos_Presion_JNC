# Datos_Presion_JNC

La base de datos incluye 56 registros de señales PPG tomadas en un laboratorio, cada una con una duración de 2 minutos y muestreadas a 100 Hz. Los participantes no estaban en el hospital durante la recopilación de datos.

El objetivo principal es ayudar a desarrollar formas de estimar la presión arterial utilizando estas señales PPG.

El archivo de Excel proporciona más detalles sobre cada persona, como si tienen alguna condición médica, están recibiendo tratamiento y cómo se clasifican según la presión arterial (N = normal, E = algo alta, H = alta).

Esta información es útil para investigadores y profesionales de la salud que trabajan en este campo.

Informacion sobre los archivos cargados:

## Datos_Presion.csv

Este archivo consta de la medicion directa de cada paciente, es decir, la informacion para visualizar las raficas PPG. Estos datos como lo indica antes, se realizaron bajo la frecuencia de muestreo de 100Hz

## Datos_Registros_PPG_V2.csv

Este archivo tenemos la informacion general de cada uno de los pacientes, como lo son:

### Edad: Numero entero que nos indica los años del paciente
### Genero: Masculino o Femenino
### Diagnostico: Si es Hipertenso o no lo es
### Tratamiento: SI el paciente esta en tratamiento de la Hipertension
### Presion Sistolica: Valor en mmHg para la presion
### Presion Diastolica: Valor en mmHg para la presion
### Frecuencia Cardiaca: Pulsaciones por minuto del corazon
### Clasificacion de la Presion: En que clasificacion se encuentra el paciente

    Clasificaciones 
      N -> Nomotenso.
      E -> Prehipertenso.
      H -> Hipertenso.
