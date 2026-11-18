---
title: System::CastEnumeratorTo method
linktitle: CastEnumeratorTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::CastEnumeratorTo method. Performs a type cast of the enumerator by explicitly casting the type of each element over which the source enumerator iterates in C++.'
type: docs
weight: 17100
url: /cpp/system/castenumeratorto/
---
## System::CastEnumeratorTo method


Performs a type cast of the enumerator by explicitly casting the type of each element over which the source enumerator iterates.

```cpp
template<class From,class To> System::SharedPtr<System::Collections::Generic::IEnumerator<To>> System::CastEnumeratorTo(const System::SharedPtr<System::Collections::Generic::IEnumerator<From>> &enumerator)
```


| Parameter | Description |
| --- | --- |
| From | Type argument of enumerator to cast |
| To | Type argument of resulting enumerator |

| Parameter | Type | Description |
| --- | --- | --- |
| enumerator | const System::SharedPtr\<System::Collections::Generic::IEnumerator\<From\>\>\& | Enumerator to cast |

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
