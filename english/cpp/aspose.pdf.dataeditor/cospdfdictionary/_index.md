---
title: Aspose::Pdf::DataEditor::CosPdfDictionary class
linktitle: CosPdfDictionary
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DataEditor::CosPdfDictionary class. A class for accessing an object''s dictionary in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class


A class for accessing an object's dictionary.

```cpp
class CosPdfDictionary : public Aspose::Pdf::DataEditor::CosPdfPrimitive,
                         public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<ICosPdfPrimitive>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<ICosPdfPrimitive\>\&) override | Set [ICosPdfPrimitive](../icospdfprimitive/) to dictionary. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Set [ICosPdfPrimitive](../icospdfprimitive/) to dictionary. |
| [Clear](./clear/)() override | Removes all items from the [CosPdfDictionary](./). |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) const override | Determines whether the [CosPdfDictionary](./) contains a specific value. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determines whether the [CosPdfDictionary](./) contains an element with the specified key. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\>, int32_t) override | Copies the elements of the [CosPdfDictionary](./) to an [Array](../../aspose.pdf/xmpfieldtype/), starting at a particular [Array](../../aspose.pdf/xmpfieldtype/) index. |
| [CosPdfDictionary](./cospdfdictionary/)(System::SharedPtr\<Resources\>) | Creates a dictionary from resources. |
| static [CreateEmptyDictionary](./createemptydictionary/)(System::SharedPtr\<Page\>) | Creates an empty dictionary that will be attached to the page. |
| static [CreateEmptyDictionary](./createemptydictionary/)(System::SharedPtr\<Document\>) | Creates an empty dictionary that will be attached to the document. |
| [get_AllKeys](./get_allkeys/)() const | Full collection of keys. Contains editable and not editable keys. |
| [get_Count](./get_count/)() const override | Gets the number of elements contained in the [CosPdfDictionary](./). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether the [CosPdfDictionary](./) is read-only. |
| [get_Keys](./get_keys/)() const override | [Collection](../../aspose.pdf/collection/) of editable keys. |
| [get_Values](./get_values/)() const override | Gets an [ICollection](../../system.collections.generic/icollection/icollection/) containing the values in the [CosPdfDictionary](./). |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that iterates through the collection. |
| [idx_get](./idx_get/)(const System::String\&) const override | Gets the element with the specified key. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>) override | Sets the element with the specified key. |
| [Remove](./remove/)(const System::String\&) override | Removes the element with the specified key from the [CosPdfDictionary](./). |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Removes the first occurrence of a specific object from the [CosPdfDictionary](./). |
| [ToCosPdfDictionary](./tocospdfdictionary/)() override | Tries cast this instance to [CosPdfDictionary](./). |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>\&) const override | For access to simple data type like string, name, bool, number. Returns null for other types. |
## See Also

* Class [CosPdfPrimitive](../cospdfprimitive/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::DataEditor](../)
* Library [Aspose.PDF for C++](../../)
