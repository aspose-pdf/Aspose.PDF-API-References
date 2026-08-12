---
title: "Aspose::Pdf::Facades::PdfExtractor class"
linktitle: "PdfExtractor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfExtractor class. Класс для извлечения изображений и текста из PDF‑документа на C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class


Класс для извлечения изображений и текста из PDF‑документа.

```cpp
class PdfExtractor : public Aspose::Pdf::Facades::Facade
```

## Методы

| Метод | Описание |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Привязать входной PDF‑файл. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Привязывает PDF‑документ из потока. |
| [ExtractAttachment](./extractattachment/)() | Извлекает вложения из документа [Pdf](../../aspose.pdf/). |
| [ExtractAttachment](./extractattachment/)(const System::String\&) | Извлекает вложение в PDF‑файл по имени вложения. |
| [ExtractImage](./extractimage/)() | Извлекает изображения из PDF‑файла. |
| [ExtractText](./extracttext/)() | Извлекает текст из документа [Pdf](../../aspose.pdf/) с использованием Unicode‑кодировки. |
| [ExtractText](./extracttext/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Извлекает текст из документа [Pdf](../../aspose.pdf/) с использованием указанной кодировки. |
| [get_EndPage](./get_endpage/)() const | Получает конечную страницу в диапазоне страниц, где будет выполнена операция извлечения. |
| [get_ExtractImageMode](./get_extractimagemode/)() const | Устанавливает режим процесса извлечения изображений. |
| [get_ExtractTextMode](./get_extracttextmode/)() const | Устанавливает режим результата извлечения текста. |
| [get_IsBidi](./get_isbidi/)() | Истина, когда текст содержит еврейские или арабские символы. Этот случай необходимо учитывать специально, поскольку функции работы со строками меняют своё поведение и начинают обрабатывать текст справа налево (за исключением цифр и других не текстовых символов). |
| [get_Password](./get_password/)() const | Получает пароль входного файла. |
| [get_Resolution](./get_resolution/)() const | Устанавливает или получает разрешение извлекаемых изображений. Значение по умолчанию — 150. Изображения с более высоким разрешением более чёткие. Однако увеличение разрешения приводит к росту времени и памяти, необходимых для извлечения изображений. Обычно, чтобы получить чёткое изображение, достаточно установить разрешение 150 или 300. |
| [get_StartPage](./get_startpage/)() const | Получает начальную страницу в диапазоне страниц, где будет выполнена операция извлечения. |
| [get_TextSearchOptions](./get_textsearchoptions/)() const | Получает параметры поиска текста. |
| [GetAttachment](./getattachment/)(const System::String\&) | Сохраняет вложение в файл. |
| [GetAttachment](./getattachment/)() | Сохраняет все файлы вложений в потоки. |
| [GetAttachmentInfo](./getattachmentinfo/)() | Получает список вложений. |
| [GetAttachNames](./getattachnames/)() | Возвращает список вложений в PDF‑файле. [Note](../../aspose.pdf/note/): метод ExtractAttachments должен быть вызван перед использованием этого метода. |
| [GetNextImage](./getnextimage/)(const System::String\&) | Получает следующее изображение из PDF‑документа. [Note](../../aspose.pdf/note/): метод ExtractImage должен быть вызван перед использованием этого метода. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Получает следующее изображение из PDF‑документа в заданном формате изображения. [Note](../../aspose.pdf/note/): метод ExtractImage должен быть вызван перед использованием этого метода. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Получает следующее изображение из PDF‑файла и сохраняет его в поток в заданном формате изображения. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Получить следующее изображение из PDF‑файла и сохранить его в поток. |
| [GetNextPageText](./getnextpagetext/)(const System::String\&) | Сохраняет текст одной страницы в файл. |
| [GetNextPageText](./getnextpagetext/)(const System::SharedPtr\<System::IO::Stream\>\&) | Сохраняет текст одной страницы в поток. |
| [GetText](./gettext/)(const System::String\&) | Сохраняет текст в файл. см. также:[ExtractText](./extracttext/) |
| [GetText](./gettext/)(const System::SharedPtr\<System::IO::Stream\>\&) | Сохраняет текст в поток. см. также:[ExtractText](./extracttext/) |
| [GetText](./gettext/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Сохраняет текст в поток. см. также:[ExtractText](./extracttext/) |
| [HasNextImage](./hasnextimage/)() | Проверяет, доступны ли дополнительные изображения в PDF‑документе. [Note](../../aspose.pdf/note/): ExtractImage должен быть вызван до использования этого метода. |
| [HasNextPageText](./hasnextpagetext/)() | Указывает, можно ли получить дополнительный текст или нет. |
| [PdfExtractor](./pdfextractor/)() | Инициализирует новый объект [PdfExtractor](./). |
| [PdfExtractor](./pdfextractor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfExtractor](./) на основе *document*. |
| [set_EndPage](./set_endpage/)(int32_t) | Устанавливает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [set_ExtractImageMode](./set_extractimagemode/)(Aspose::Pdf::ExtractImageMode) | Устанавливает режим процесса извлечения изображений. |
| [set_ExtractTextMode](./set_extracttextmode/)(int32_t) | Устанавливает режим результата извлечения текста. |
| [set_Password](./set_password/)(const System::String\&) | Устанавливает пароль входного файла. |
| [set_Resolution](./set_resolution/)(int32_t) | Устанавливает или получает разрешение извлекаемых изображений. Значение по умолчанию — 150. Изображения с более высоким разрешением более чёткие. Однако увеличение разрешения приводит к росту времени и памяти, необходимых для извлечения изображений. Обычно, чтобы получить чёткое изображение, достаточно установить разрешение 150 или 300. |
| [set_StartPage](./set_startpage/)(int32_t) | Устанавливает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [set_TextSearchOptions](./set_textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Устанавливает параметры поиска текста. |
## См. также

* Class [Facade](../facade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
