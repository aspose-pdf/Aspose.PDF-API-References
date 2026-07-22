---
title: "System::Array::CopyTo metod"
linktitle: "CopyTo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::CopyTo metod. Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid det index som anges av argumentet arrayIndex i C++."
type: docs
weight: 900
url: /sv/cpp/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) method


Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid det index som anges av argumentet arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | ArrayPtr\<T\> | Destinationsarray |
| arrayIndex | int | [Index](../../index/) i destinationsarrayen för att börja infoga kopierade objekt vid |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const method


Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid det index som anges av argumentet dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


| Parameter | Beskrivning |
| --- | --- |
| DstType | Typ av element i destinationsarrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstArray | const ArrayPtr\<DstType\>\& | Destinationsarray |
| dstIndex | int64_t | [Index](../../index/) i destinationsarrayen för att börja infoga kopierade objekt vid |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const method


Kopierar ett angivet antal element från den aktuella arrayen som startar vid den angivna positionen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid det index som anges av argumentet dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


| Parameter | Beskrivning |
| --- | --- |
| DstType | Typ av element i destinationsarrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstArray | const ArrayPtr\<DstType\>\& | Destinationsarray |
| srcIndex | int64_t | [Index](../../index/) i källarrayen för att börja kopiera objekt vid |
| dstIndex | int64_t | [Index](../../index/) i destinationsarrayen för att börja infoga kopierade objekt vid |
| count | int64_t | Antal element att kopiera |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const method


Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayens vy. Elementen infogas i destinationsarrayens vy med start vid det index som anges av argumentet dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


| Parameter | Beskrivning |
| --- | --- |
| DstType | Typ av element i visning av destinationsarrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destinationens arrayvy |
| dstIndex | int64_t | [Index](../../index/) i destinationens arrayvy för att börja infoga kopierade objekt vid |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const method


Kopierar ett angivet antal element från den aktuella arrayen som startar vid den angivna positionen till den angivna destinationsarrayens vy. Elementen infogas i destinationsarrayens vy med start vid det index som anges av argumentet dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


| Parameter | Beskrivning |
| --- | --- |
| DstType | Typ av element i visning av destinationsarrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destinationens arrayvy |
| srcIndex | int64_t | [Index](../../index/) i källarrayen för att börja kopiera objekt vid |
| dstIndex | int64_t | [Index](../../index/) i destinationens arrayvy för att börja infoga kopierade objekt vid |
| count | int64_t | Antal element att kopiera |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
