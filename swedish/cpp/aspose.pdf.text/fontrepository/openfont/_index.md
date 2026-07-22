---
title: "Aspose::Pdf::Text::FontRepository::OpenFont‑metod"
linktitle: "OpenFont"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::FontRepository::OpenFont‑metod. Öppnar teckensnitt med angivet teckensnittström i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.text/fontrepository/openfont/
---
## FontRepository::OpenFont(const System::SharedPtr\<System::IO::Stream\>\&, const FontTypes\&) method


Öppnar teckensnitt med angiven teckensnittström.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::SharedPtr<System::IO::Stream> &fontStream, const FontTypes &fontType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontStream | const System::SharedPtr\<System::IO::Stream\>\& | [Font](../../font/) ström. |
| fontType | const FontTypes\& | [Font](../../font/) typvärde. |

### ReturnValue

[Font](../../font/) object.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Stream](../../../system.io/stream/)
* Enum [FontTypes](../../fonttypes/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(const System::String\&) method


Öppnar teckensnitt med angiven teckensnittsfilssökväg.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::String &fontFilePath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFilePath | const System::String\& | [Font](../../font/) filsökväg. |

### ReturnValue

[Font](../../font/) object.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [String](../../../system/string/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(const System::String\&, const System::String\&) method


Öppnar teckensnitt med angiven teckensnittsfilssökväg och metrisfilssökväg.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::String &fontFilePath, const System::String &metricsFilePath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFilePath | const System::String\& | [Font](../../font/) filsökväg. |
| metricsFilePath | const System::String\& | [Font](../../font/) metrikfilens sökväg. |

### ReturnValue

[Font](../../font/) object.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [String](../../../system/string/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
