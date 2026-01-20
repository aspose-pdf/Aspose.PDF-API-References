---
title: Aspose::Pdf::DataEditor::DictionaryEditor class
linktitle: DictionaryEditor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DataEditor::DictionaryEditor class. A class for accessing an document''s tree dictionary (document dictionary, page dictionary, resources dictionary) in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class


A class for accessing an document's tree dictionary (document dictionary, page dictionary, resources dictionary).

```cpp
class DictionaryEditor : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<ICosPdfPrimitive>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<ICosPdfPrimitive\>\&) override | Set [ICosPdfPrimitive](../icospdfprimitive/) to dictionary. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Set [ICosPdfPrimitive](../icospdfprimitive/) to dictionary. |
| [Clear](./clear/)() override | Removes all items from the [DictionaryEditor](./). |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) const override | Determines whether the [DictionaryEditor](./) contains a specific value. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determines whether the [DictionaryEditor](./) contains an element with the specified key. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\>, int32_t) override | Copies the elements of the [DictionaryEditor](./) to an [Array](../../aspose.pdf/xmpfieldtype/), starting at a particular [Array](../../aspose.pdf/xmpfieldtype/) index. |
| [DictionaryEditor](./dictionaryeditor/)(System::SharedPtr\<Page\>) | ArgumentNullException |
| [DictionaryEditor](./dictionaryeditor/)(System::SharedPtr\<Document\>) | ArgumentNullException |
| [DictionaryEditor](./dictionaryeditor/)(System::SharedPtr\<Resources\>) | ArgumentNullException |
| [get_AllKeys](./get_allkeys/)() const | Full collection of keys. Contains editable and not editable keys. |
| [get_Count](./get_count/)() const override | Gets the number of elements contained in the [DictionaryEditor](./). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether the [DictionaryEditor](./) is read-only. |
| [get_Keys](./get_keys/)() const override | [Collection](../../aspose.pdf/collection/) of editable keys. |
| [get_Values](./get_values/)() const override | Gets an [ICollection](../../system.collections.generic/icollection/icollection/) containing the values in the [DictionaryEditor](./). |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that iterates through the collection. |
| [idx_get](./idx_get/)(const System::String\&) const override | Gets the element with the specified key. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>) override | Sets the element with the specified key. |
| [Remove](./remove/)(const System::String\&) override | Removes the element with the specified key from the [DictionaryEditor](./). |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Removes the first occurrence of a specific object from the [DictionaryEditor](./). |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>\&) const override | For access to simple data type like string, name, bool, number. Returns null for other types. |
## See Also

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::DataEditor](../)
* Library [Aspose.PDF for C++](../../)
