# Empleo minero por rubro

Aplicación web interactiva para explorar el empleo minero formal en la República Argentina. El tablero permite analizar la distribución territorial y ocupacional de los puestos de trabajo mediante indicadores, gráficos, filtros combinables, un mapa y una tabla de detalle.

## Funcionalidades

- Indicadores de trabajadores, registros y localidades, con su porcentaje respecto del total nacional.
- Mapa interactivo con OpenStreetMap y marcadores activados al aplicar una selección.
- Filtros por rubro, provincia, departamento, localidad y género.
- Filtros por país de nacimiento, calificación, grupo de puesto y puesto desempeñado.
- Búsqueda por localidad, departamento, provincia, CUIL y características laborales.
- Gráficos de trabajadores por rubro, género y grupo ocupacional.
- Tabla con el detalle de los registros filtrados.
- Exportación de la selección actual a CSV.
- Diseño adaptable para computadoras, tabletas y dispositivos móviles.

## Datos

La base contiene **32.768 registros** correspondientes a puestos de trabajo asalariados formales del sector minero durante octubre de 2021.

Entre las variables utilizadas se encuentran:

| Dimensión | Variables |
| --- | --- |
| Territorio | Provincia, departamento, localidad, latitud y longitud |
| Actividad | Rubro minero y clasificación de actividad |
| Perfil | Género y país de nacimiento |
| Ocupación | Calificación, grupo de puesto y puesto desempeñado |
| Identificación estadística | CUIL, CUIT, CLAE y códigos territoriales |

Los datos están incluidos dentro del HTML para permitir la apertura directa de la aplicación. El mapa base necesita conexión a internet para descargar las imágenes de OpenStreetMap.

## Uso

### Apertura directa

Abrir el archivo:

```text
outputs/Index.html
```

## Estructura

La aplicación está desarrollada con HTML, CSS y JavaScript, sin necesidad de un proceso de compilación. Para la visualización geográfica utiliza [Leaflet](https://leafletjs.com/) y [OpenStreetMap](https://www.openstreetmap.org/).

## Fuentes

- [Secretaría de Minería de la Nación - Empleo minero por rubro](https://public.tableau.com/app/profile/sec.mineria/viz/EmpleoMinero/EmpleoRubro).
- CEP-XXI, sobre la base de información de AFIP.
- Dirección Nacional de Información y Transparencia Minera.
- Los datos corresponden a puestos de trabajo de asalariados formales de octubre de 2021.
- Cartografía: colaboradores de [OpenStreetMap](https://www.openstreetmap.org/copyright).

## Autoría

Proyecto desarrollado por **Silvana Sánchez Di Domenico**.
https://www.linkedin.com/in/silvana-s%C3%A1nchez-di-domenico/ 

Economista, especialista en el análisis de datos, la visualización de información pública y el desarrollo de herramientas digitales que faciliten la comprensión de temas productivos y territoriales. Este proyecto busca transformar una base estadística compleja en una experiencia clara, accesible e interactiva.

## Consideraciones

La información se presenta con fines analíticos y de visualización. Para interpretaciones oficiales, metodologías, actualizaciones o validaciones de los datos se recomienda consultar las fuentes institucionales indicadas.
