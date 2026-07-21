---
title: "Aspose::Pdf::DataEditor::CosPdfDictionary::Remove método"
linktitle: "Eliminar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DataEditor::CosPdfDictionary::Remove método. Elimina la primera aparición de un objeto específico del CosPdfDictionary en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## CosPdfDictionary::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) method


Elimina la primera aparición de un objeto específico del [CosPdfDictionary](../).

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<ICosPdfPrimitive>> &item) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\& | El objeto a eliminar del [CosPdfDictionary](../). |

### ReturnValue

true si el elemento se eliminó correctamente del [CosPdfDictionary](../); de lo contrario, false. Este método también devuelve false si el elemento no se encuentra en el [CosPdfDictionary](../) original.

## Ver también

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
## CosPdfDictionary::Remove(const System::String\&) method


Elimina el elemento con la clave especificada del [CosPdfDictionary](../).

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::Remove(const System::String &key) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | const System::String\& | La clave del elemento a eliminar. |

### ReturnValue

True si el elemento se elimina correctamente; de lo contrario, false. Este método también devuelve false si la clave no se encontró en el diccionario original o la clave no es editable.

## Ver también

* Class [String](../../../system/string/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
