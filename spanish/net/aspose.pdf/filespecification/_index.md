---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.FileSpecification. Clase que representa un archivo incrustado
type: docs
weight: 4850
url: /es/net/aspose.pdf/filespecification/
---
## Clase FileSpecification

Clase que representa un archivo incrustado.

```csharp
public sealed class FileSpecification : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](filespecification/#constructor_3)(string) | Constructor para FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Constructor para la especificación de archivo. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Constructor para FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Constructor para FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Constructor para FileSpecification. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Relación de archivo asociada. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Obtiene un elemento de colección de la especificación de archivo. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Obtiene o establece el archivo de contenido. Esta propiedad devuelve datos cargados en memoria, lo que puede causar una excepción de falta de memoria para datos grandes. Para disminuir el uso de memoria, utilice StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Obtiene o establece el texto asociado con la especificación de archivo. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Obtiene o establece el formato de codificación. Valores posibles: Zip - el archivo está comprimido con ZIP, None - el archivo no está comprimido. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Obtiene la carga útil encriptada. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Obtiene o establece el nombre del sistema de archivos. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Si es verdadero, el contenido del archivo se incluirá en la especificación del archivo. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Obtiene el subtipo del archivo incrustado |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Obtiene o establece el nombre de la especificación del archivo. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Obtiene los parámetros del archivo. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Obtiene el contenido del archivo como un flujo. El contenido no se carga en memoria, lo que permite disminuir el uso de memoria. Pero este flujo no soporta posicionamiento y la propiedad Length. Si necesita estas características, utilice la propiedad Contents en su lugar. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Obtiene o establece el nombre unicode de la especificación del archivo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Desecha el contenido. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Obtiene un parámetro específico de la aplicación. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Establece un parámetro específico de la aplicación. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)