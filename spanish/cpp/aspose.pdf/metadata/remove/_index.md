---
title: "Método Aspose::Pdf::Metadata::Remove"
linktitle: "Eliminar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Metadata::Remove. Elimina el par clave/valor de la colección en C++."
type: docs
weight: 2100
url: /es/cpp/aspose.pdf/metadata/remove/
---
## Metadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Elimina el par clave/valor de la colección.

```cpp
bool Aspose::Pdf::Metadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
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
* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Remove(const System::String\&) method


Elimina la entrada de los metadatos.

```cpp
bool Aspose::Pdf::Metadata::Remove(const System::String &key) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | const System::String\& | La clave de la entrada a eliminar. |

### ReturnValue

True - si la clave se elimina; de lo contrario, false.

## Ver también

* Class [String](../../../system/string/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
