---
title: "FileSpecification"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa un archivo incrustado."
type: docs
weight: 360
url: /es/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Clase que representa un archivo incrustado.

El tipo FileSpecification expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| FileSpecification(file) | Inicializa una nueva instancia de la clase FileSpecification |
| FileSpecification(stream, name) | Inicializa una nueva instancia de la clase FileSpecification |
| FileSpecification(file, description) | Inicializa una nueva instancia de la clase FileSpecification |
| FileSpecification(stream, name, description) | Inicializa una nueva instancia de la clase FileSpecification |
| FileSpecification(file_name, annot) | Inicializa una nueva instancia de la clase FileSpecification |
| FileSpecification() | Crea una nueva especificación de archivo vacía. |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| codificación | Obtiene o establece el formato de codificación.<br/>            Valores posibles: Zip - el archivo está comprimido con ZIP, <br/>            None - el archivo no está comprimido. |
| include_contents | Si es verdadero, el contenido del archivo se incluirá en la especificación de archivo. |
| encrypted_payload | Obtiene la carga útil cifrada. |
| descripción | Obtiene o establece el texto asociado con la especificación del archivo. |
| af_relationship | Relación de archivo asociada. |
| stream_contents | Obtiene el contenido del archivo como flujo. <br/>            El contenido no se carga en memoria, lo que permite reducir el uso de memoria.<br/>            Pero este flujo no admite posicionamiento ni la propiedad Length. Si necesita estas funciones, utilice la propiedad Contents en su lugar. |
| contenidos | Obtiene o establece el contenido del archivo. <br/>            Esta propiedad devuelve datos cargados en memoria, lo que puede causar una excepción de falta de memoria para datos grandes.<br/>            Para reducir el uso de memoria, utilice StreamContents. |
| params | Obtiene los parámetros del archivo. |
| mime_type | Obtiene el subtipo del archivo incrustado |
| name | Obtiene o establece el nombre de la especificación del archivo. |
| unicode_name | Obtiene o establece el nombre unicode de la especificación del archivo. |
| file_system | Obtiene o establece el nombre del sistema de archivos. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| get_value(key) | Obtiene el parámetro específico de la aplicación. |
| set_value(key, value) | Establece el parámetro específico de la aplicación. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

