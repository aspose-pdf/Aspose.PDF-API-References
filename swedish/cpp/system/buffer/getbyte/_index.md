---
title: "System::Buffer::GetByte metod"
linktitle: "GetByte"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Buffer::GetByte metod. Tolkar den angivna typade arrayen som en rå byte-array och hämtar bytevärdet vid den angivna byteoffseten i C++."
type: docs
weight: 300
url: /sv/cpp/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) method


Tolkar den angivna typade arrayen som en rå byte-array och hämtar bytevärdet vid den angivna byteoffseten.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i arrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const SharedPtr\<Array\<T\>\>\& | Målarrayen |
| index | int | Nollbaserad offset för den byte som ska hämtas |

### ReturnValue

Bytevärdet vid det angivna indexet

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) method


Tolkar den angivna typade arrayen som en rå byte-array och hämtar bytevärdet vid den angivna byteoffseten.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i arrayvyn |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Målarrayvyn |
| index | int | Nollbaserad offset för den byte som ska hämtas |

### ReturnValue

Bytevärdet vid det angivna indexet

## Se även

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) method


Tolkar den angivna typade arrayen som en rå byte-array och hämtar bytevärdet vid den angivna byteoffseten.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i stackarrayen |
| N | Storleken på stackarrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Den målstackarrayen |
| index | int | Nollbaserad offset för den byte som ska hämtas |

### ReturnValue

Bytevärdet vid det angivna indexet

## Se även

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
