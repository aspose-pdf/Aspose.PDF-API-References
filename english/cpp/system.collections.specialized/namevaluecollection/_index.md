---
title: System::Collections::Specialized::NameValueCollection class
linktitle: NameValueCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Specialized::NameValueCollection class. Collection of associated String keys and String values that can be accessed either with the key or with the index in C++.'
type: docs
weight: 200
url: /cpp/system.collections.specialized/namevaluecollection/
---
## NameValueCollection class


Collection of associated [String](../../system/string/) keys and [String](../../system/string/) values that can be accessed either with the key or with the index.

```cpp
class NameValueCollection : public System::Collections::Generic::ICollection<System::String>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const String\&) override | Override [ICollection](../../system.collections/icollection/) method - not implemented. |
| [Add](./add/)(const System::SharedPtr\<NameValueCollection\>\&) | Copies the entries in the specified [NameValueCollection](./) to the current. |
| virtual [Add](./add/)(const String\&, const String\&) | Adds an entry with the specified name and value. |
| [Clear](./clear/)() override | Deletes all elements. |
| [Contains](./contains/)(const String\&) const override | Checks if item is present in collection. |
| [CopyTo](./copyto/)(System::ArrayPtr\<String\>, int32_t) override | Copies collection elements into existing array elements. |
| virtual [Get](./get/)(const String\&) | Gets the values associated with the specified key. |
| virtual [get_AllKeys](./get_allkeys/)() | Gets all the keys. |
| [get_Count](./get_count/)() const override | Gets the number of key/value pairs. |
| virtual [get_Keys](./get_keys/)() | Gets all the keys. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator to iterate through collection. |
| virtual [GetValues](./getvalues/)(const String\&) | Gets the values associated with the specified key. |
| [HasKeys](./haskeys/)() | Gets a value indicating whether the [NameValueCollection](./) contains keys that are not null. |
| [idx_get](./idx_get/)(const String\&) | Gets value at specified index. |
| [idx_set](./idx_set/)(const String\&, const String\&) | Sets value of an entry. |
| [NameValueCollection](./namevaluecollection/)() | Initializes a new instance of the [NameValueCollection](./) class that is empty. |
| [NameValueCollection](./namevaluecollection/)(const System::SharedPtr\<NameValueCollection\>\&) | Copies the entries from the specified [NameValueCollection](./) to a new [NameValueCollection](./). |
| [Remove](./remove/)(const String\&) override | Removes specific item. |
| virtual [Set](./set/)(const String\&, const String\&) | Sets the value of an entry. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
