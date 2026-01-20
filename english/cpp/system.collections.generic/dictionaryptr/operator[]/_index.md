---
title: System::Collections::Generic::DictionaryPtr::operator[] method
linktitle: operator[]
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::DictionaryPtr::operator[] method. Access operator in C++.'
type: docs
weight: 200
url: /cpp/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const T\&) const method


Access operator.

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) key. |

### ReturnValue

Reference to value corresponding to the key passed, existing or newly created.

## See Also

* Class [DictionaryPtr](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## DictionaryPtr::operator[](const X\&) const method


Access operator to work with key type conversion.

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```


| Parameter | Description |
| --- | --- |
| X | Source key type. |

| Parameter | Type | Description |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) key. |

### ReturnValue

Reference to value corresponding to the key passed, existing or newly created.

## See Also

* Class [DictionaryPtr](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
