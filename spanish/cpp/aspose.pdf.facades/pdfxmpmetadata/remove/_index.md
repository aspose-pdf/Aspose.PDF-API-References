---
title: "Aspose::Pdf::Facades::PdfXmpMetadata::Remove método"
linktitle: "Eliminar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfXmpMetadata::Remove método. Elimina el par clave/valor de la colección en C++."
type: docs
weight: 2100
url: /es/cpp/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Elimina el par clave/valor de la colección.

```cpp
bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Par clave/valor a eliminar. |

### ReturnValue

true si el par fue encontrado y eliminado.

## Ver también

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(const System::String\&) method


Elimina la clave del diccionario.

```cpp
bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::String &key) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | const System::String\& | Clave que será eliminada. |

### ReturnValue

True - si la clave se elimina; de lo contrario, false.


## Ver también

* Class [String](../../../system/string/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(DefaultMetadataProperties) method


Elimina el elemento con la clave especificada.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Remove(DefaultMetadataProperties key)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | DefaultMetadataProperties | Clave del elemento que será eliminado. |

## Ver también

* Enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
