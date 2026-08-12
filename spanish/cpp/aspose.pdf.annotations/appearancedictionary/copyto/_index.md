---
title: "Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo método"
linktitle: "CopyTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo method. Copia los elementos del diccionario a un Array, comenzando en un índice de Array particular en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.annotations/appearancedictionary/copyto/
---
## AppearanceDictionary::CopyTo(const System::ArrayPtr\<System::SharedPtr\<XForm\>\>\&, int32_t) method


Copia los elementos del diccionario a una Matriz, comenzando en un índice de Matriz particular.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo(const System::ArrayPtr<System::SharedPtr<XForm>> &array, int32_t index)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | const System::ArrayPtr\<System::SharedPtr\<XForm\>\>\& | Array donde los elementos deben copiarse. |
| índice | int32_t | Índice donde los elementos deben copiarse. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## AppearanceDictionary::CopyTo(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\>, int32_t) method


Copia los elementos de la ICollection a una Matriz, comenzando en un índice de Matriz particular.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo(System::ArrayPtr<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XForm>>> array, int32_t arrayIndex) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\> | El Array unidimensional que es el destino de los elementos copiados de ICollection. El Array debe tener indexación basada en cero. |
| arrayIndex | int32_t | El índice basado en cero en el array en el que comienza la copia. |
## Observaciones



No se realiza verificación de límites.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
