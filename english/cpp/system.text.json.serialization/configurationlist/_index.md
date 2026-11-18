---
title: System::Text::Json::Serialization::ConfigurationList class
linktitle: ConfigurationList
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::ConfigurationList class in C++.'
type: docs
weight: 100
url: /cpp/system.text.json.serialization/configurationlist/
---
## ConfigurationList class




```cpp
template<typename TItem>class ConfigurationList : public System::Collections::Generic::IList<TItem>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const TItem\&) override |  |
| [begin](./begin/)() | Gets iterator pointing to the first element (if any) of the collection. |
| [begin](./begin/)() const | Gets iterator pointing to the first element (if any) of the const-qualified instance of the collection. |
| [cbegin](./cbegin/)() const | Gets iterator pointing to the first const-qualified element (if any) of the collection. |
| [cend](./cend/)() const | Gets iterator pointing right after the last const-qualified element (if any) of the collection. |
| [Clear](./clear/)() override | Deletes all elements from collection. |
| [ConfigurationList](./configurationlist/)(System::SharedPtr\<Collections::Generic::IEnumerable\<TItem\>\>) |  |
| [Contains](./contains/)(const TItem\&) const override |  |
| [CopyTo](./copyto/)(System::SharedPtr\<Array\<TItem\>\>, int32_t) override |  |
| [end](./end/)() | Gets iterator pointing right after the last element (if any) of the collection. |
| [end](./end/)() const | Gets iterator pointing right after the last element (if any) of the const-qualified instance of the collection. |
| [get_Count](./get_count/)() const override | Gets number of elements in collection. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Checks if collection is read only. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator. |
| [idx_get](./idx_get/)(int32_t) const override |  |
| [idx_set](./idx_set/)(int32_t, TItem) override |  |
| [IndexOf](./indexof/)(const TItem\&) const override | Gets index of first appearance of item in container. |
| [Insert](./insert/)(int32_t, const TItem\&) override |  |
| [Remove](./remove/)(const TItem\&) override |  |
| [RemoveAt](./removeat/)(int32_t) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets iterator pointing to the first element (if any)of the const-qualified instance of the collection. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets iterator pointing to the first element (if any) of the collection. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets iterator pointing right after the last element (if any)of the const-qualified instance of the collection. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets iterator pointing right after the last element (if any) of the collection. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [iterator](./iterator/) | Iterator type. |
| [iterator_holder_type](./iterator_holder_type/) | A collection type whose iterator types is used as iterator types in the current collection. |
| [virtualized_iterator](./virtualized_iterator/) | Virtualized type. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Virtualized element type. |
## See Also

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Text::Json::Serialization](../)
* Library [Aspose.PDF for C++](../../)
