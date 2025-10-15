---
title: System::Collections::Generic::IDictionary class
linktitle: IDictionary
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IDictionary class. Interface for dictionary-alike containers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2100
url: /cpp/system.collections.generic/idictionary/
---
## IDictionary class


Interface for dictionary-alike containers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```


| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |
## Methods

| Method | Description |
| --- | --- |
| virtual [Add](./add/)(const TKey\&, const TValue\&) | Adds key-value pair into container. |
| virtual [ContainsKey](./containskey/)(const TKey\&) const | Checks if container contains key. |
| [CopyTo](./copyto/)(ArrayPtr\<KeyValuePair\<TKey, TValue\>\>, int) override | Copies dictionary contents into existing array elements. |
| virtual [get_Count](./get_count/)() const | Unhides get_Count member function. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Checks if collection size is fixed. |
| [get_IsSynchronized](./get_issynchronized/)() const | Checks if container is thread-safe. |
| virtual [get_Keys](./get_keys/)() const | Accesses key collection. |
| virtual [get_Values](./get_values/)() const | Accesses value collection. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&) const | Returns value if found; or **Value()** otherwise. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&, const TValue\&) const | Returns value if found; or **defaultValue** otherwise. |
| virtual [GetValueOrNull](./getvalueornull/)(const TKey\&) const | Returns value if found; or **null** otherwise, make sense only for reference types. |
| virtual [idx_get](./idx_get/)(const TKey\&) const | Getter function. |
| virtual [idx_set](./idx_set/)(const TKey\&, TValue) | Setter function. |
| virtual [Remove](./remove/)(const TKey\&) | Removes key from container. |
| virtual [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | Looks for value and retreives it if found. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | RTTI information. |
| [KeyValuePairType](./keyvaluepairtype/) | Key value pair type. |

## See Also

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
