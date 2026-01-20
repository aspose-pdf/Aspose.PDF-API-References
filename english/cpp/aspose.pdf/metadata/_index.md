---
title: Aspose::Pdf::Metadata class
linktitle: Metadata
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Metadata class. Provides access to XMP metadata stream in C++.'
type: docs
weight: 11200
url: /cpp/aspose.pdf/metadata/
---
## Metadata class


Provides access to XMP metadata stream.

```cpp
class Metadata : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XmpValue>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpValue\>\&) override | Adds value to metadata. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Adds value to metadata. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Adds pdf extension to metadata. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Adds pair with key and value into the dictionary. |
| [Clear](./clear/)() override | Clears metadata. |
| [Contains](./contains/)(const System::String\&) const | Checks does key is contained in metadata. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const override | Checks does specified key-value pair is contained in the dictionary. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determines does this dictionary contasins specified key. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\>, int32_t) override | Copies elements of the collection into array. |
| [get_Count](./get_count/)() const override | Gets count of elements in the collection. |
| [get_ExtensionFields](./get_extensionfields/)() | Gets the dictionary of extension fields. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Checks if colleciton has fixed size. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Checks if collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Checks if collection is synchronized. |
| [get_Keys](./get_keys/)() const override | Gets collection of metadata keys. |
| [get_NamespaceManager](./get_namespacemanager/)() | Gets namespace manager. |
| [get_SyncRoot](./get_syncroot/)() const | Gets collection synchronization object. |
| [get_Values](./get_values/)() const override | Gets values in the metadata. |
| [GetEnumerator](./getenumerator/)() override | Returns dictionary enumerator. |
| [GetNamespaceUriByPrefix](./getnamespaceuribyprefix/)(System::String) | Returns namespace URI by prefix. |
| [GetPrefixByNamespaceUri](./getprefixbynamespaceuri/)(System::String) | Returns prefix by namespace URI. |
| [idx_get](./idx_get/)(const System::String\&) const override | Gets data from metadata. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XmpValue\>) override | Sets data from metadata. |
| [RegisterNamespaceUri](./registernamespaceuri/)(System::String, System::String) | Registers namespace URI. |
| [RegisterNamespaceUri](./registernamespaceuri/)(System::String, System::String, System::String) | Registers namespace URI. |
| [Remove](./remove/)(const System::String\&) override | Removes entry from metadata. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Removes key/value pair from the colleciton. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XmpValue\>\&) const override | Tries to find key in the dictionary and retreives value if found. |
## See Also

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
