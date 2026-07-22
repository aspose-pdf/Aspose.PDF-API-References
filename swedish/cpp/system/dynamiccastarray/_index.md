---
title: "System::DynamicCastArray method"
linktitle: "DynamicCastArray"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DynamicCastArray method. Utför kast av element i den angivna arrayen till en annan typ i C++."
type: docs
weight: 18400
url: /sv/cpp/system/dynamiccastarray/
---
## System::DynamicCastArray method


Utför kast av element i den angivna arrayen till en annan typ.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


| Parameter | Beskrivning |
| --- | --- |
| Till | Typen att kasta elementen i den angivna arrayen till |
| From | Typen av element i array-elementen som ska kastas |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| från | const SharedPtr\<Array\<From\>\>\& | Delad pekare till arrayen som innehåller elementen som ska kastas |

### ReturnValue

En pekare till en ny array som innehåller element av typen **To** motsvarande elementen i **from**

## Deprecated
Tillagd för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
