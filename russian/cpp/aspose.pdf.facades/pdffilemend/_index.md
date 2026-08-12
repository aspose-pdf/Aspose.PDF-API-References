---
title: "Aspose::Pdf::Facades::PdfFileMend класс"
linktitle: "PdfFileMend"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileMend класс. Представляет класс для добавления текста и изображений на страницы существующего PDF‑документа в C++."
type: docs
weight: 2200
url: /ru/cpp/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class


Представляет класс для добавления текста и изображений на страницы существующего PDF‑документа.

```cpp
class PdfFileMend : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float) | Добавляет изображение на указанную страницу PDF‑документа в заданных координатах. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Добавляет изображение на указанную страницу PDF‑документа в заданных координатах. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Добавляет изображение на указанные страницы PDF‑документа в заданных координатах. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Добавляет изображение на указанные страницы PDF‑документа в заданных координатах. |
| [AddImage](./addimage/)(const System::String\&, int32_t, float, float, float, float) | Добавляет изображение на указанную страницу PDF‑документа в заданных координатах. |
| [AddImage](./addimage/)(const System::String\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Добавляет изображение на указанную страницу PDF‑документа в заданных координатах. |
| [AddImage](./addimage/)(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Добавляет изображение на указанные страницы PDF‑документа в заданных координатах. |
| [AddImage](./addimage/)(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Добавляет изображение на указанные страницы PDF‑документа в заданных координатах. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float) | Не реализовано. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) | Не реализовано. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Не реализовано. |
| [Close](./close/)() override | Закрывает объект [PdfFileMend](./). |
| [get_InputFile](./get_inputfile/)() const | Устанавливает входной файл. |
| [get_InputStream](./get_inputstream/)() const | Устанавливает входной поток. |
| [get_OutputFile](./get_outputfile/)() const | Устанавливает выходной файл. |
| [get_OutputStream](./get_outputstream/)() const | Устанавливает выходной поток. |
| [get_TextPositioningMode](./get_textpositioningmode/)() const | Устанавливает или получает стратегию позиционирования текста. [PositioningMode](../positioningmode/) Режим по умолчанию — Legacy. |
| [get_WrapMode](./get_wrapmode/)() const | Устанавливает или получает алгоритм переноса слов. См. [WordWrapMode](../wordwrapmode/) и IsWordWrap. |
| [PdfFileMend](./pdffilemend/)() | Конструктор. |
| [PdfFileMend](./pdffilemend/)(const System::String\&, const System::String\&) | Конструктор. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Конструктор. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfFileMend](./) на основе *document*. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Инициализирует новый объект [PdfFileMend](./) на основе *document*. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Инициализирует новый объект [PdfFileMend](./) на основе *document*. |
| [Save](./save/)(System::String) override | Сохраняет PDF‑документ в указанный файл. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Сохраняет PDF‑документ в указанный поток. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Устанавливает входной файл. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает входной поток. |
| [set_IsWordWrap](./set_iswordwrap/)(bool) | Устанавливает булево значение, указывающее на перенос слов в методах AddText. Если значение истинно, текст в [FormattedText](../formattedtext/) будет переноситься. По умолчанию значение ложно. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Устанавливает выходной файл. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает выходной поток. |
| [set_TextPositioningMode](./set_textpositioningmode/)(PositioningMode) | Устанавливает или получает стратегию позиционирования текста. [PositioningMode](../positioningmode/) Режим по умолчанию — Legacy. |
| [set_WrapMode](./set_wrapmode/)(WordWrapMode) | Устанавливает или получает алгоритм переноса слов. См. [WordWrapMode](../wordwrapmode/) и IsWordWrap. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
