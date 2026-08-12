---
title: "Aspose::Pdf::Facades::PdfContentEditor::ReplaceText метод"
linktitle: "ReplaceText"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::ReplaceText метод. Заменяет текст в PDF‑файле на C++."
type: docs
weight: 4500
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&) method


Заменяет текст в PDF‑файле.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | const System::String\& | Строка, которую нужно заменить. |
| destString | const System::String\& | Строка замены. |

### ReturnValue

Возвращает true, если замена была выполнена.

## См. также

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) method


Заменяет текст в PDF‑файле, используя указанный объект [TextState](../).

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString, const System::SharedPtr<Text::TextState> &textState)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | const System::String\& | Строка для замены |
| destString | const System::String\& | Строка замены |
| textState | const System::SharedPtr\<Text::TextState\>\& | [Text](../../../aspose.pdf.text/) состояние ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Шрифт и т.д.) |

### ReturnValue

Возвращает true, если замена была выполнена.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&, int32_t) method


Заменяет текст в PDF‑файле и задаёт размер шрифта.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString, int32_t fontSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | const System::String\& | Строка для замены. |
| destString | const System::String\& | Строка замены. |
| fontSize | int32_t | Размер шрифта. |

### ReturnValue

Возвращает true, если замена была выполнена.

## См. также

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, int32_t, const System::String\&) method


Заменяет текст в PDF‑файле на указанной странице.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, int32_t thePage, const System::String &destString)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | const System::String\& | Строка для замены. |
| thePage | int32_t | [Page](../../../aspose.pdf/page/) номер (0 для всех страниц) |
| destString | const System::String\& | Строка замены. |

### ReturnValue

Возвращает true, если замена была выполнена.

## См. также

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, int32_t, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) method


Заменяет текст в PDF‑файле на указанной странице. Объект [TextState](../) (семейство шрифтов, цвет) может быть указан для заменяемого текста.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, int32_t thePage, const System::String &destString, const System::SharedPtr<Text::TextState> &textState)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | const System::String\& | Строка, которую нужно заменить. |
| thePage | int32_t | [Page](../../../aspose.pdf/page/) номер (0 означает "все страницы"). |
| destString | const System::String\& | Заменённая строка. |
| textState | const System::SharedPtr\<Text::TextState\>\& | [Text](../../../aspose.pdf.text/) состояние ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Шрифт и т.д.). |

### ReturnValue

Возвращает true, если замена была выполнена.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
