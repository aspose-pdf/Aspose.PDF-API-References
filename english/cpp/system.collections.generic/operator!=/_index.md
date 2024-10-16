---
title: System::Collections::Generic::operator!= method
linktitle: operator!=
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::operator!= method. Compares two key-value pairs using inverse ''equals'' semantics in C++.'
type: docs
weight: 5200
url: /cpp/system.collections.generic/operator!=/
---
## System::Collections::Generic::operator!= method


Compares two key-value pairs using inverse 'equals' semantics.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator!=(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

| Parameter | Type | Description |
| --- | --- | --- |
| left | const KeyValuePair\<TKey, TValue\>\& | LHS operand. |
| right | const KeyValuePair\<TKey, TValue\>\& | RHS operand. |

### ReturnValue

True if both keys and values don't match, false otherwise.

## See Also

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
