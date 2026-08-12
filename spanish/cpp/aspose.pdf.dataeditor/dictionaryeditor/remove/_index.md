---
title: "Aspose::Pdf::DataEditor::DictionaryEditor::Remove método"
linktitle: "Eliminar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DataEditor::DictionaryEditor::Remove método. Elimina la primera ocurrencia de un objeto específico del DictionaryEditor en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## DictionaryEditor::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) method


Elimina la primera ocurrencia de un objeto específico del [DictionaryEditor](../).

```cpp
bool Aspose::Pdf::DataEditor::DictionaryEditor::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<ICosPdfPrimitive>> &item) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\& | El objeto a eliminar del [DictionaryEditor](../). |

### ReturnValue

true si el elemento se eliminó correctamente del [DictionaryEditor](../); de lo contrario, false. Este método también devuelve false si el elemento no se encuentra en el [DictionaryEditor](../) original.

## Ver también

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
## DictionaryEditor::Remove(const System::String\&) method


Elimina el elemento con la clave especificada del [DictionaryEditor](../).

```cpp
bool Aspose::Pdf::DataEditor::DictionaryEditor::Remove(const System::String &key) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | const System::String\& | La clave del elemento a eliminar. |

### ReturnValue

True si el elemento se elimina correctamente; de lo contrario, false. Este método también devuelve false si la clave no se encontró en el diccionario original o la clave no es editable.

## Ver también

* Class [String](../../../system/string/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
