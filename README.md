# Plan de gestión de configuración.

## Introducción
El presente documento tiene como objetivo establecer los lineamientos a seguir para la gestión de la configuración del proyecto, a lo largo del desarrollo de la materia Ingeniería y calidad de software.

## Estructura de directorios
Hemos propuesto como estructura de directorios la siguiente, pensando en el desarrollo de la materia y en la facilidad de acceso a los archivos.

```
├──Bibliografia
├──Clases
│   ├── ClaseX-(Tema)
│   │   ├── Presentaciones
│   │   ├── Toma de notas
├──Lineamientos
├──TrabajosPrácticos
    ├──TPX
├──Resúmenes
    ├── UnidadX
├──Multimedia
    ├──UnidadX
```

## Control de versiones
Para el control de versiones se utilizará el sistema de control de versiones distribuido [Git](https://git-scm.com/). El repositorio se encuentra alojado en [GitHub](https://github.com/ginomassei/TP4-SCM.git). 

## Linea base
Se establecerá una linea base para cada parcial rendido y aprobado de la  materia, la cual se encontrará en la rama main del repositorio.

La idea es utilizar un parcial porque lo consideramos un "checkpoint" en el conocimiento adquirido en la materia, y por lo tanto, un buen momento para establecer una linea base.

## Numeración de versiones

Se utilizará el siguiente formato para la numeración de versiones:

```
<TipoItemDeConfiguración>_<Numeración>_<Nombre>.<Extensión>
```

Donde: 

### TipoItemDeConfiguración: 
Es el tipo de ítem de configuración, por ejemplo: BIBLIO, TP, etc.

Remitirse a la sección "Listado de ítems de configuración" para ver los tipos de ítems de configuración.

### Numeración:
Es un número que se le asigna al ítem de configuración, y debe seguir el formato XXXX, por ejemplo: 0001, 0002, etc. Teniendo en cuenta que la primer X es dependiendo de la serie de ítem de configuración a la que pertenece el ítem.

Ver sección "Series" para ver la numeración de cada serie.

### Nombre:
Es el nombre que se le asigna al ítem de configuración, por ejemplo: "Plan de gestión de configuración", "TP1", etc.

### Extensión:
Es la extensión del ítem de configuración, por ejemplo: pdf, docx, etc.

### Ejemplo:
```
BIBLIO_1001_ManifiestoAgil.pdf
```

## Series

| Serie | Prefijo |
| :--------: | :--------: |
| Bibliografía | 1XXXX |
| Trabajos Prácticos | 2XXXX |
| Resúmenes | 3XXXX |
| Lineamientos | 4XXXX |
| Presentaciones | 5XXXX |
| Multimedia | 6XXXX |
| Tomas de notas | 7XXXX |

## Listado de ítems de configuración
Se consideran ítems de configuración a los siguientes elementos:

| Tipo | Formato | Abreviatura | Ubicación Física |
| :--------: | :--------: | :--------: | :--------: |
| Bibliografía | PDF | BIBLIO | Bibliografia/ |
| Trabajos Prácticos | PDF, DOCX, XLSX | TP | TrabajosPrácticos/ |
| Resúmenes | PDF, DOCX, GDOC | RES | Resúmenes/ |
| Lineamientos | PDF | LINEA | Lineamientos/ |
| Multimedia | JPG, PNG, PDF, MP4 | MULT | Multimedia/ |
| Tomas de notas | PDF, DOCX, GDOC | NOTAS | Clases/ClaseX-(Tema)/Toma de notas/ |
| Presentaciones | PDF, PPTX, GDOC | PRESENT | Clases/ClaseX-(Tema)/Presentaciones/ |

## Documento de gestión de configuración
El documento de gestión de configuración se encuentra en el directorio raíz del repositorio y por una disposición del repositorio remoto que estamos utilizando debe de llamarse "README.md". De esta manera se puede tener siempre visible el documento de gestión de configuración de una forma rápida y sencilla.
