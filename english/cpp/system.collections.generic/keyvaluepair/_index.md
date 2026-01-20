---
title: System::Collections::Generic::KeyValuePair class
linktitle: KeyValuePair
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::KeyValuePair class. Pair of key and value. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 2900
url: /cpp/system.collections.generic/keyvaluepair/
---
## KeyValuePair class


Pair of key and value. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Methods

| Method | Description |
| --- | --- |
| [get_Key](./get_key/)() const | Gets key. |
| [get_Value](./get_value/)() const | Gets value. |
| [GetHashCode](./gethashcode/)() const | Calculates key-value pair hash by xoring key's and value's hashes. |
| [IsNull](./isnull/)() const | Always returns false. |
| [KeyValuePair](./keyvaluepair/)() | Null key-value pair initializer. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Constructor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Type conversion constructor. |
| [operator<](./operator_/)(const KeyValuePair\&) const | Patch for classes inherited from [IComparer<KeyValuePair<TKey, TValue>>](../icomparer/), doesn't compare anything. |
| [ToString](./tostring/)() const | Converts key-value pair to string. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
