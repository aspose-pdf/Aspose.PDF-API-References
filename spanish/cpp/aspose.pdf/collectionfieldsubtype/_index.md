---
title: "Aspose::Pdf::CollectionFieldSubtype enum"
linktitle: "CollectionFieldSubtype"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::CollectionFieldSubtype enum. Representa el parámetro de subtipo de un campo en una colección de esquema en C++."
type: docs
weight: 21800
url: /es/cpp/aspose.pdf/collectionfieldsubtype/
---
## CollectionFieldSubtype enum


Representa el parámetro de subtipo de un campo en una colección de esquema.

```cpp
enum class CollectionFieldSubtype
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | El subtipo no está definido. |
| S | 1 | Un tipo de texto. Los datos del campo se almacenarán como una cadena de texto PDF. |
| D | 2 | Un tipo de fecha. Los datos del campo se almacenarán como una cadena de fecha PDF. |
| N | 3 | Un tipo numérico. Los datos del campo se almacenarán como un número PDF. |
| F | 4 | Los datos del campo deben ser el nombre de archivo del flujo de archivo incrustado, según lo identifique la entrada UF de la especificación del archivo, si está presente; de lo contrario, por la entrada F de la especificación del archivo. |
| Desc | 5 | Los datos del campo deben ser el nombre de archivo del flujo de archivo incrustado, según lo identifique la entrada UF de la especificación del archivo, si está presente; de lo contrario, por la entrada F de la especificación del archivo. |
| ModDate | 6 | Los datos del campo deben ser la fecha de modificación del flujo de archivo incrustado, según lo identifique la entrada ModDate en el diccionario de parámetros del archivo incrustado. |
| CreationDate | 7 | Los datos del campo deben ser la fecha de creación del flujo de archivo incrustado, según lo identifique la entrada CreationDate en el archivo incrustado. |
| Size | 8 | Los datos del campo deben ser el tamaño del archivo incrustado, según lo identifique la entrada Size en el diccionario de parámetros del archivo incrustado. |
| CompressedSize | 9 | (PDF 2.0) Los datos del campo son la longitud del flujo de archivo incrustado, según lo identificado por la entrada Length en el diccionario del flujo de archivo incrustado, y los dos valores deberán ser idénticos. |

## Ver también

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
