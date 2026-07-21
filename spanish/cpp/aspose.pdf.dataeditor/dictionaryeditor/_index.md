---
title: "Clase Aspose::Pdf::DataEditor::DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::DataEditor::DictionaryEditor. Una clase para acceder al árbol de diccionarios de un documento (diccionario del documento, diccionario de página, diccionario de recursos) en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class


Una clase para acceder al diccionario de árbol de un documento (diccionario del documento, diccionario de página, diccionario de recursos).

```cpp
class DictionaryEditor : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<ICosPdfPrimitive>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<ICosPdfPrimitive\>\&) override | Establecer [ICosPdfPrimitive](../icospdfprimitive/) en el diccionario. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Establecer [ICosPdfPrimitive](../icospdfprimitive/) en el diccionario. |
| [Clear](./clear/)() override | Elimina todos los elementos del [DictionaryEditor](./). |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) const override | Determina si el [DictionaryEditor](./) contiene un valor específico. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determina si el [DictionaryEditor](./) contiene un elemento con la clave especificada. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\>, int32_t) override | Copia los elementos del [DictionaryEditor](./) a un [Array](../../aspose.pdf/xmpfieldtype/), comenzando en un índice particular del [Array](../../aspose.pdf/xmpfieldtype/). |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Page\>\&) | ArgumentNullException |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Document\>\&) | ArgumentNullException |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Resources\>\&) | ArgumentNullException |
| [get_AllKeys](./get_allkeys/)() const | Colección completa de claves. Contiene claves editables y no editables. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos contenidos en el [DictionaryEditor](./). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si el [DictionaryEditor](./) es de solo lectura. |
| [get_Keys](./get_keys/)() const override | [Collection](../../aspose.pdf/collection/) de claves editables. |
| [get_Values](./get_values/)() const override | Obtiene una [ICollection](../../system.collections.generic/icollection/icollection/) que contiene los valores del [DictionaryEditor](./). |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que recorre la colección. |
| [idx_get](./idx_get/)(const System::String\&) const override | Obtiene el elemento con la clave especificada. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>) override | Establece el elemento con la clave especificada. |
| [Remove](./remove/)(const System::String\&) override | Elimina el elemento con la clave especificada del [DictionaryEditor](./). |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Elimina la primera aparición de un objeto específico del [DictionaryEditor](./). |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>\&) const override | Para acceder a tipos de datos simples como string, name, bool, number. Devuelve null para otros tipos. |
## Ver también

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::DataEditor](../)
* Library [Aspose.PDF for C++](../../)
