---
title: Aspose::Pdf::Annotations::AppearanceDictionary class
linktitle: AppearanceDictionary
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AppearanceDictionary class. Annotation appearance dictionary specifying how the annotation shall be presented visually on the page in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class


[Annotation](../annotation/) appearance dictionary specifying how the annotation shall be presented visually on the page.

```cpp
class AppearanceDictionary : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XForm>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XForm\>\&) override | Add X form for specifed key. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) override | Adds pair with key and value into the dictionary. |
| [Clear](./clear/)() override | Removes all elements from the dictionary. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) const override | Checks does specified key-value pair is contained in the dictionary. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determines does this dictionary contasins specified key. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<XForm\>\>, int32_t) | Copies the elements of the dictionary to an Array, starting at a particular Array index. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\>, int32_t) override | Copies the elements of the ICollection to an Array, starting at a particular Array index. |
| [get_Count](./get_count/)() const override | Gets the number of elements contained in the dictionary. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Gets a value indicating whether dictionary has a fixed size. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether dictionary is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets a value indicating whether access to the dictionary is synchronized (thread safe). |
| [get_Keys](./get_keys/)() const override | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [Keys](../) contains (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes). |
| [get_SyncRoot](./get_syncroot/)() const | Gets an object that can be used to synchronize access to the dictionary. |
| [get_Values](./get_values/)() const override | Gets the list of the dictionary values. Result collection contains the list of [XForm](../../aspose.pdf/xform/) objects. |
| [GetEnumerator](./getenumerator/)() override | Returns an IDictionaryEnumerator object for the dictionary. |
| [idx_get](./idx_get/)(const System::String\&) const override | Represents convenient form for getting appearance streams. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XForm\>) override | Represents convenient form for getting appearance streams. |
| [Remove](./remove/)(const System::String\&) override | Removes key from the dictionary. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) override | Removes key/value pair from the collection. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XForm\>\&) const override | Tries to find key in the dictionary and retreives value if found. |
## See Also

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
