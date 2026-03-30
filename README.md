# banavim-datos-abiertos

## Dataset 1: Casos

### Estructura

Columnas principales:

* id → identificador de la fila
* fecha_registro
* estado
* fecha_hechos
* lugar_hechos
* modalidad_violencia
* conoce_agresor
* hubo_drogas
* hubo_armas
* violencia_fisica
* violencia_psicologica
* violencia_sexual
* 

### Resumen

* Nivel: evento (caso)
* Granularidad: 1 fila = 1 caso
* Tipo de datos: fechas, categóricos, binarios

### Observaciones

* Variación en texto (municipios, lugares)
* Variables de violencia en formato 0/1 o texto
* Posibles nulos en ubicación o modalidad
* Fechas no normalizadas

### Uso principal

Tendencias, distribución geográfica, tipos de violencia

## Dataset 2: Víctimas

### Estructura

* id → identificador de la fila
* fecha_registro
* estado
* municipio
* escolaridad
* edad
* estado_civil
* hijas_e_hijos
* fuente_ingresos

### Resumen

* Nivel: individuo (víctima)
* Granularidad: 1 fila = 1 víctima
* Tipo de datos: numéricos, categóricos

### Observaciones

* Edades fuera de rango o nulas
* Categorías inconsistentes (escolaridad)
* Falta de relación directa con casos

### Usos principales

Perfil de víctimas (edad, características sociales)

## Dataset 3: Agresores

### Estructura

# Enlace de descarga

Enlace directo para la descarga de los datasets [Banavim Abierto](https://pages.github.com/](https://banavimabierto.mx/descarga.php). 
