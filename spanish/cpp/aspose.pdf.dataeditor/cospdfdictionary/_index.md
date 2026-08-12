---
title: "Aspose::Pdf::DataEditor::CosPdfDictionary clase"
linktitle: "CosPdfDictionary"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DataEditor::CosPdfDictionary clase. Una clase para acceder al diccionario de un objeto en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class


Una clase para acceder al diccionario de un objeto.

```cpp
class CosPdfDictionary : public Aspose::Pdf::DataEditor::CosPdfPrimitive,
                         public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<ICosPdfPrimitive>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<ICosPdfPrimitive\>\&) override | Establecer [ICosPdfPrimitive](../icospdfprimitive/) en el diccionario. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Establecer [ICosPdfPrimitive](../icospdfprimitive/) en el diccionario. |
| [Clear](./clear/)() override | Elimina todos los elementos del [CosPdfDictionary](./). |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) const override | Determina si el [CosPdfDictionary](./) contiene un valor específico. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determina si el [CosPdfDictionary](./) contiene un elemento con la clave especificada. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\>, int32_t) override | Copia los elementos del [CosPdfDictionary](./) a un [Array](../../aspose.pdf/xmpfieldtype/), comenzando en un índice particular del [Array](../../aspose.pdf/xmpfieldtype/). |
| [CosPdfDictionary](./cospdfdictionary/)(const System::SharedPtr\<Resources\>\&) | Crea un diccionario a partir de recursos. |
| static [CreateEmptyDictionary](./createemptydictionary/)(const System::SharedPtr\<Page\>\&) | Crea un diccionario vacío que se adjuntará a la página. |
| static [CreateEmptyDictionary](./createemptydictionary/)(const System::SharedPtr\<Document\>\&) | Crea un diccionario vacío que se adjuntará al documento. |
| [get_AllKeys](./get_allkeys/)() const | Colección completa de claves. Contiene claves editables y no editables. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos contenidos en el [CosPdfDictionary](./). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si el [CosPdfDictionary](./) es de solo lectura. |
| [get_Keys](./get_keys/)() const override | [Collection](../../aspose.pdf/collection/) de claves editables. |
| [get_Values](./get_values/)() const override | Obtiene una [ICollection](../../system.collections.generic/icollection/icollection/) que contiene los valores del [CosPdfDictionary](./). |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que recorre la colección. |
| [idx_get](./idx_get/)(const System::String\&) const override | Obtiene el elemento con la clave especificada. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>) override | Establece el elemento con la clave especificada. |
| [Remove](./remove/)(const System::String\&) override | Elimina el elemento con la clave especificada del [CosPdfDictionary](./). |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Elimina la primera aparición de un objeto específico del [CosPdfDictionary](./). |
| [ToCosPdfDictionary](./tocospdfdictionary/)() override | Intenta convertir esta instancia a [CosPdfDictionary](./). |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>\&) const override | Para acceder a tipos de datos simples como string, name, bool, number. Devuelve null para otros tipos. |
## Ver también

* Class [CosPdfPrimitive](../cospdfprimitive/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::DataEditor](../)
* Library [Aspose.PDF for C++](../../)
