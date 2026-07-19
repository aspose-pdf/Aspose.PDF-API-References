---
title: "Класс Aspose::Pdf::HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::HtmlLoadOptions. Представляет параметры загрузки/импорта HTML‑файла в PDF‑документ в C++."
type: docs
weight: 7200
url: /ru/cpp/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class


Представляет параметры загрузки/импорта html‑файла в PDF‑документ.

```cpp
class HtmlLoadOptions : public Aspose::Pdf::LoadOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | Базовый путь/URL для HTML‑файла. |
| [get_CreateLogicalStructure](./get_createlogicalstructure/)() const | Получает значение, указывающее, следует ли создавать логическую структуру в результирующем PDF‑документе. |
| [get_HtmlMediaType](./get_htmlmediatype/)() const | Получает возможные типы медиа, используемые при рендеринге. |
| [get_InputEncoding](./get_inputencoding/)() const | Получает атрибут, указывающий кодировку, используемую для этого документа во время разбора. Если этот атрибут равен null, кодировка будет определена из атрибута набора символов документа. |
| [get_IsEmbedFonts](./get_isembedfonts/)() const | Получает встраивание шрифтов в результирующий документ. |
| [get_IsPriorityCssPageRule](./get_isprioritycsspagerule/)() const |  |
| [get_IsRenderToSinglePage](./get_isrendertosinglepage/)() const | Получает рендеринг всего документа в одну страницу. |
| [get_PageInfo](./get_pageinfo/)() const | Получает информацию о страницах документа. |
| [get_PageLayoutOption](./get_pagelayoutoption/)() const | Получает параметр макета. |
| [HtmlLoadOptions](./htmlloadoptions/)() | Создаёт параметры загрузки для преобразования html в pdf‑документ с пустым базовым путём. |
| [HtmlLoadOptions](./htmlloadoptions/)(const System::String\&) | Создаёт параметры загрузки для преобразования html в pdf‑документ с заданным базовым путём. |
| [set_CreateLogicalStructure](./set_createlogicalstructure/)(bool) | Устанавливает значение, указывающее, следует ли создавать логическую структуру в результирующем PDF‑документе. |
| [set_HtmlMediaType](./set_htmlmediatype/)(Aspose::Pdf::HtmlMediaType) | Устанавливает возможные типы медиа, используемые при рендеринге. |
| [set_InputEncoding](./set_inputencoding/)(const System::String\&) | Устанавливает атрибут, указывающий кодировку, используемую для этого документа во время разбора. Если этот атрибут равен null, кодировка будет определена из атрибута набора символов документа. |
| [set_IsEmbedFonts](./set_isembedfonts/)(bool) | Устанавливает встраивание шрифтов в результирующий документ. |
| [set_IsPriorityCssPageRule](./set_isprioritycsspagerule/)(bool) |  |
| [set_IsRenderToSinglePage](./set_isrendertosinglepage/)(bool) | Устанавливает рендеринг всего документа в одну страницу. |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Устанавливает информацию о страницах документа. |
| [set_PageLayoutOption](./set_pagelayoutoption/)(HtmlPageLayoutOption) | Устанавливает параметр макета. |
## См. также

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
