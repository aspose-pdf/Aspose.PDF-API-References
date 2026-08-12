---
title: "System::Guid::Guid konstruktor"
linktitle: "Guid"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Guid::Guid konstruktor. Skapar ett objekt som representerar en GUID bestående av enbart nollor i C++."
type: docs
weight: 100
url: /sv/cpp/system/guid/guid/
---
## Guid::Guid() constructor


Skapar ett objekt som representerar ett GUID bestående av enbart nollor.

```cpp
System::Guid::Guid()
```

## Se även

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const ArrayPtr\<uint8_t\>\&) constructor


Skapar ett objekt som representerar ett GUID specificerat som en array av osignerade 8-bitars heltalsvärden.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| b | const ArrayPtr\<uint8_t\>\& | En byte-array som innehåller separata byte i GUID:en |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const Guid\&) constructor


Skapar ett objekt som representerar samma GUID som det specificerade objektet.

```cpp
System::Guid::Guid(const Guid &guid)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| guid | const Guid\& | Det [Guid](../)-objektet att kopiera GUID-värdet från |

## Se även

* Class [Guid](../)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const String\&) constructor


Skapar ett objekt som representerar ett GUID specificerat som en sträng.

```cpp
System::Guid::Guid(const String &g)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | const String\& | Strängrepresentationen av en GUID som ska representeras av det objekt som konstrueras |

## Se även

* Class [String](../../string/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) constructor


Skapar ett objekt som representerar ett GUID specificerat som en array‑vy av osignerade 8-bitars heltalsvärden.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| b | const System::Details::ArrayView\<uint8_t\>\& | En byte-array som innehåller separata byte i GUID:en |

## Se även

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) constructor


Skapar en instans av [Guid](../)-klassen från de angivna GUID-komponenterna.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | int32_t | Bitars 0-31 i GUID:en |
| b | int16_t | Bitars 32-47 i GUID:en |
| c | int16_t | Bitars 48-63 i GUID:en |
| d | const ArrayPtr\<uint8_t\>\& | En byte-array som innehåller bitar 64-127 i GUID:en |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) constructor


Skapar en instans av [Guid](../)-klassen från de angivna GUID-komponenterna.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | int32_t | Bitars 0-31 i GUID:en |
| b | int16_t | Bitars 32-47 i GUID:en |
| c | int16_t | Bitars 48-63 i GUID:en |
| d | const System::Details::ArrayView\<uint8_t\>\& | En byte-arrayvy som innehåller bitar 64-127 i GUID:en |

## Se även

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor


Skapar en instans av [Guid](../)-klassen från de angivna osignerade heltalen och byte.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | int32_t | Bitars 0-31 i GUID:en |
| b | int16_t | Bitars 32-47 i GUID:en |
| c | int16_t | Bitars 48-63 i GUID:en |
| d | uint8_t | Bitars 64-71 i GUID:en |
| e | uint8_t | Bitars 72-79 i GUID:en |
| f | uint8_t | Bitars 80-87 i GUID:en |
| g | uint8_t | Bitars 88-95 i GUID:en |
| h | uint8_t | Bitars 96-103 i GUID:en |
| i | uint8_t | Bitars 104-111 i GUID:en |
| j | uint8_t | Bitars 112-119 i GUID:en |
| k | uint8_t | Bitar 120-127 i GUID |

## Se även

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor


Skapar en instans av [Guid](../)-klassen från de angivna osignerade heltalen och byte.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | uint32_t | Bitars 0-31 i GUID:en |
| b | uint16_t | Bitars 32-47 i GUID:en |
| c | uint16_t | Bitars 48-63 i GUID:en |
| d | uint8_t | Bitars 64-71 i GUID:en |
| e | uint8_t | Bitars 72-79 i GUID:en |
| f | uint8_t | Bitars 80-87 i GUID:en |
| g | uint8_t | Bitars 88-95 i GUID:en |
| h | uint8_t | Bitars 96-103 i GUID:en |
| i | uint8_t | Bitars 104-111 i GUID:en |
| j | uint8_t | Bitars 112-119 i GUID:en |
| k | uint8_t | Bitar 120-127 i GUID |

## Se även

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
