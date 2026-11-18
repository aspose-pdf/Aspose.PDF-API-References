---
title: System::Collections::Generic::IReadOnlyDictionary class
linktitle: IReadOnlyDictionary
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IReadOnlyDictionary class. Interface for read-only dictionary-alike containers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2900
url: /cpp/system.collections.generic/ireadonlydictionary/
---
## IReadOnlyDictionary class


Interface for read-only dictionary-alike containers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename TKey,typename TValue>class IReadOnlyDictionary : public System::Collections::Generic::IReadOnlyCollection<KeyValuePair<TKey, TValue>>
```


| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |
## Methods

| Method | Description |
| --- | --- |
| virtual [ContainsKey](./containskey/)(const TKey\&) const | RTTI information. |
| virtual [idx_get](./idx_get/)(const TKey\&) const | Getter function. |
| virtual [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | Looks for value and retreives it if found. |

## See Also

* Class [IReadOnlyCollection](../ireadonlycollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
