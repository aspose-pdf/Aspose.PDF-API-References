---
title: System::Collections::Generic::BaseDictionary class
linktitle: BaseDictionary
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::BaseDictionary class. Implements common code for various dictionary-alike data structures (e. g. Dictionary, SortedDictionary). Shouldn''t be used directly, except for inheritance when defining containers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.collections.generic/basedictionary/
---
## BaseDictionary class


Implements common code for various dictionary-alike data structures (e. g. [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/)). Shouldn't be used directly, except for inheritance when defining containers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```


| Parameter | Description |
| --- | --- |
| Map | Underlying map type. |
## Methods

| Method | Description |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | C++ specific. |
| [Add](./add/)(const key_t\&, const mapped_t\&) override | Adds key-value pair into dictionary. |
| [BaseDictionary](./basedictionary/)() | Creates empty data structure. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | Forwarding constructor to push arguments into underlying map constructor. |
| [BaseDictionary](./basedictionary/)(BaseType *, const Args\&...) | Copying constructor. |
| [BaseDictionary](./basedictionary/)(BaseType *) | Copying constructor. |
| [begin](./begin/)() const | Returns an iterator to the KVPair-wrapper for key-value-element of the container. Implemented in C# style - iterator should be return the KVPair-object with get_Key() and get_Value() interface. If the container is empty, the returned iterator will be equal to [end()](../ienumerable/end/). |
| [cbegin](./cbegin/)() const | Returns an iterator to the first element of the container. Implemented in STL-style. If the container is empty, the returned iterator will be equal to [end()](../ienumerable/end/). |
| [cend](./cend/)() const | Returns an iterator to the element following the last element of the container. Implemented in STL-style. This element acts as a placeholder; attempting to access it results in undefined behavior. |
| [Clear](./clear/)() override | Deletes all elements. |
| [ContainsKey](./containskey/)(const key_t\&) const override | Checks if key is present in dictionary. |
| [ContainsValue](./containsvalue/)(const mapped_t\&) | Checks if value is present in dictionary. Uses operator == to compare values. |
| [data](./data/)() | Underlying data storage accessor. |
| [data](./data/)() const | Underlying data storage accessor. |
| [end](./end/)() const | Returns an iterator to the KVPair-wrapper for key-value-element following the last element of the container. Implemented in C# style - iterator should be return the KVPair-object with get_Key() and get_Value() interface. This element acts as a placeholder; attempting to access it results in undefined behavior. |
| [get_Count](./get_count/)() const override | Gets elements count. |
| virtual [GetEnumerator](./getenumerator/)() | Creates enumerator instance, should be implemented by subclass. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | Returns value if found; or **Value()** otherwise. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | Returns value if found; or **defaultValue** otherwise. |
| [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | Returns value if found; or **null** otherwise. Make sense only for reference types. |
| [idx_get](./idx_get/)(const key_t\&) const override | Keyed getter function. |
| [idx_set](./idx_set/)(const key_t\&, mapped_t) override | Keyed setter function. Alters or creates element. |
| virtual [operator[]](./operator[]/)(const key_t\&) | Accessor function. |
| [Remove](./remove/)(const key_t\&) override | Removes specific key from dictionary. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | Looks for keyed value and retreives it if found. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | Implemented interface. |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [iterator](./iterator/) | Iterator type. |
| [KeyCollection](./keycollection/) | Make sure we use correct allocator with underlying storage type. |
| [KVPair](./kvpair/) | Key-value pair type. |
| [map_t](./map_t/) | Internal map type. |
| [ValueCollection](./valuecollection/) | Collection of values. |

## See Also

* Class [IDictionary](../idictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
