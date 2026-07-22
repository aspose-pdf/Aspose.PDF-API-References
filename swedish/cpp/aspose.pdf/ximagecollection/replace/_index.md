---
title: "Aspose::Pdf::XImageCollection::Replace method"
linktitle: "Ersätt"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XImageCollection::Replace method. Ersätter bild i samlingen med en annan bild i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.pdf/ximagecollection/replace/
---
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Ersätt bild i samlingen med en annan bild.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int32_t | Index för samlingsobjektet som kommer att ersättas i intervallet [1..images count]. |
| ström | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller bilddata (i JPEG-format). |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t) method


Ersätt bild i samlingen med en annan bild.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int32_t | Index för samlingsobjektet som kommer att ersättas i intervallet [1..images count]. |
| ström | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller bilddata (i JPEG-format). |
| kvalitet | int32_t | JPEG-kvalitet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, bool) method


Ersätt bild i samlingen med en annan bild.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream, int32_t quality, bool isBlackAndWhite)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int32_t | Index för samlingsobjektet som kommer att ersättas i intervallet [1..images count]. |
| ström | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller bilddata (i JPEG-format). |
| kvalitet | int32_t | Kvalitet för JPEG-komprimering, i procent (giltiga värden är 0..100). |
| isBlackAndWhite | bool | Om true, bilden komprimeras med CCITT-komprimeringsmetod som ger bättre komprimering för svart‑och‑vitt bild. Kan endast användas för svart‑och‑vitt bilder. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
