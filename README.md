# 📊 BANAVIM - Datos Abiertos

Análisis de datasets relacionados con violencia de género en México provenientes de BANAVIM.

📅 **Periodo de análisis:** 01 de enero de 2018 al 30 de diciembre de 2023

---

# Dataset 1: Casos

## Estructura

| Columna | Descripción |
|--------|------------|
| id | Identificador único del registro |
| fecha_registro | Fecha de registro del caso |
| estado | Estado donde ocurrió |
| fecha_hechos | Fecha del incidente |
| lugar_hechos | Lugar donde ocurrió el evento |
| modalidad_violencia | Tipo o modalidad de violencia |
| conoce_agresor | Indica si la víctima conoce al agresor |
| hubo_drogas | Indica consumo de drogas |
| hubo_armas | Indica uso de armas |
| violencia_fisica | Presencia de violencia física |
| violencia_psicologica | Presencia de violencia psicológica |
| violencia_sexual | Presencia de violencia sexual |
| violencia_patrimonial | Presencia de violencia patrimonial |
| violencia_economica | Presencia de violencia económica |
| violencia_otra | Otros tipos de violencia |

---

## Resumen

- **Nivel:** Evento (caso)  
- **Granularidad:** 1 fila = 1 caso  
- **Tipo de datos:** Fechas, categóricos y binarios  

---

## Observaciones

- Inconsistencias en variables de texto (municipios, lugares)
- Variables de violencia en formatos mixtos (0/1 y texto)
- Presencia de valores nulos en ubicación y modalidad
- Fechas no estandarizadas

---

## Uso principal

- Análisis de tendencias  
- Distribución geográfica  
- Identificación de tipos de violencia  

---

# Dataset 2: Víctimas

## Estructura

| Columna | Descripción |
|--------|------------|
| id | Identificador único del registro |
| fecha_registro | Fecha de registro |
| estado | Estado |
| municipio | Municipio |
| escolaridad | Nivel educativo |
| edad | Edad de la víctima |
| estado_civil | Estado civil |
| hijas_e_hijos | Número de hijas e hijos |
| fuente_ingresos | Fuente de ingresos |

---

## Resumen

- **Nivel:** Individuo (víctima)  
- **Granularidad:** 1 fila = 1 víctima  
- **Tipo de datos:** Numéricos y categóricos  

---

## Observaciones

- Edades fuera de rango o valores nulos  
- Inconsistencias en categorías (especialmente escolaridad)  
- No existe relación directa con el dataset de casos  

---

## Uso principal

- Perfil demográfico de víctimas  
- Análisis socioeconómico  

---

# Dataset 3: Agresores

## Estructura

| Columna | Descripción |
|--------|------------|
| id | Identificador único del registro |
| fecha_registro | Fecha de registro |
| estado | Estado |
| municipio | Municipio |
| escolaridad | Nivel educativo |
| edad | Edad del agresor |
| estado_civil | Estado civil |
| sexo | Sexo |
| vinculo_con_la_victima | Relación con la víctima |

---

## Resumen

- **Nivel:** Individuo (agresor)  
- **Granularidad:** 1 fila = 1 agresor  
- **Tipo de datos:** Categóricos y numéricos  

---

## Observaciones

- Relación con la víctima no estandarizada  
- Variables categóricas inconsistentes  
- Presencia de datos faltantes  

---

## Uso principal

- Perfil del agresor  
- Identificación de patrones de conducta  

---

# 🔗 Descarga de datos

Puedes descargar los datasets desde el siguiente enlace oficial: [Banavim Abierto](https://banavimabierto.mx/descarga.php). 

---

# Nota general

Los datasets son independientes y **no cuentan con una llave común**, por lo que el análisis se basa en:

- Comparaciones por tiempo  
- Distribución geográfica  
- Análisis de perfiles  
