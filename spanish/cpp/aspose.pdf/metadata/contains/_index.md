---
title: "Método Aspose::Pdf::Metadata::Contains"
linktitle: "Contiene"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Metadata::Contains. Verifica si el par clave-valor especificado está contenido en el diccionario en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf/metadata/contains/
---
## Metadata::Contains(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const method


Comprueba si el par clave-valor especificado está contenido en el diccionario.

```cpp
bool Aspose::Pdf::Metadata::Contains(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) const override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Par clave-valor. |

### ReturnValue

verdadero si se encontró este pauir.

## Ver también

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Contains(const System::String\&) const method


Comprueba si la clave está contenida en los metadatos.

```cpp
bool Aspose::Pdf::Metadata::Contains(const System::String &key) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | const System::String\& | La clave de la entrada a buscar. |

### ReturnValue

Verdadero si la clave está contenida en los metadatos.

## Ver también

* Class [String](../../../system/string/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
