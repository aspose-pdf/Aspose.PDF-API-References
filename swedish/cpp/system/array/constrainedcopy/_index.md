---
title: "System::Array::ConstrainedCopy metod"
linktitle: "ConstrainedCopy"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::ConstrainedCopy metod. Kopierar ett intervall av element från en System.Array som startar vid den angivna källan i C++."
type: docs
weight: 4900
url: /sv/cpp/system/array/constrainedcopy/
---
## Array::ConstrainedCopy method


Kopierar ett intervall av element från en [System.Array](../) som startar vid den angivna källan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beskrivning |
| --- | --- |
| SrcType | Typ av element i källarrayen |
| DstType | Typ av element i destinationsarrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Källarray |
| srcIndex | int64_t | [Index](../../index/) i källarrayen som anger början på intervallet av objekt att kopiera |
| dstArray | const ArrayPtr\<DstType\>\& | Destinationsarray |
| dstIndex | int64_t | [Index](../../index/) i destinationsarrayen för att börja infoga kopierade objekt vid |
| count | int64_t | Antalet element att kopiera |
## Anmärkningar


TILLFÄLLIG RÅ IMPLEMENTERING UTAN NÅGRA OFÄRDIGA DELAR!
## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
