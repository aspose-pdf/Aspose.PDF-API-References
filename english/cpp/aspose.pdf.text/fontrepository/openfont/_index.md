---
title: Aspose::Pdf::Text::FontRepository::OpenFont method
linktitle: OpenFont
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontRepository::OpenFont method. Opens font with specified font stream in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.text/fontrepository/openfont/
---
## FontRepository::OpenFont(System::SharedPtr\<System::IO::Stream\>, FontTypes) method


Opens font with specified font stream.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(System::SharedPtr<System::IO::Stream> fontStream, FontTypes fontType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fontStream | System::SharedPtr\<System::IO::Stream\> | [Font](../../font/) stream. |
| fontType | FontTypes | [Font](../../font/) type value. |

### ReturnValue

[Font](../../font/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Stream](../../../system.io/stream/)
* Enum [FontTypes](../../fonttypes/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(System::String) method


Opens font with specified font file path.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(System::String fontFilePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | System::String | [Font](../../font/) file path. |

### ReturnValue

[Font](../../font/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [String](../../../system/string/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(System::String, System::String) method


Opens font with specified font file path and metrics file path.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(System::String fontFilePath, System::String metricsFilePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | System::String | [Font](../../font/) file path. |
| metricsFilePath | System::String | [Font](../../font/) metrics file patrh. |

### ReturnValue

[Font](../../font/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [String](../../../system/string/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
