---
title: "Aspose::Pdf::Text::FontRepository::OpenFont метод"
linktitle: "OpenFont"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::FontRepository::OpenFont метод. Открывает шрифт с указанным потоком шрифта в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.text/fontrepository/openfont/
---
## FontRepository::OpenFont(const System::SharedPtr\<System::IO::Stream\>\&, const FontTypes\&) method


Открывает шрифт с указанным потоком шрифта.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::SharedPtr<System::IO::Stream> &fontStream, const FontTypes &fontType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fontStream | const System::SharedPtr\<System::IO::Stream\>\& | [Font](../../font/) поток. |
| fontType | const FontTypes\& | [Font](../../font/) значение типа. |

### ReturnValue

[Font](../../font/) object.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Stream](../../../system.io/stream/)
* Enum [FontTypes](../../fonttypes/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(const System::String\&) method


Открывает шрифт с указанным путем к файлу шрифта.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::String &fontFilePath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFilePath | const System::String\& | [Font](../../font/) путь к файлу. |

### ReturnValue

[Font](../../font/) object.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [String](../../../system/string/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(const System::String\&, const System::String\&) method


Открывает шрифт с указанным путем к файлу шрифта и путем к файлу метрик.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::String &fontFilePath, const System::String &metricsFilePath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFilePath | const System::String\& | [Font](../../font/) путь к файлу. |
| metricsFilePath | const System::String\& | [Font](../../font/) путь к файлу метрик. |

### ReturnValue

[Font](../../font/) object.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [String](../../../system/string/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
