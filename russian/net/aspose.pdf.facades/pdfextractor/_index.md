---
title: "Класс PdfExtractor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Facades.PdfExtractor class. Класс для извлечения изображений и текста из PDF‑документа"
type: docs
weight: 4570
url: /ru/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Класс для извлечения изображений и текста из PDF Document.

```csharp
public sealed class PdfExtractor : Facade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Инициализирует новый объект `PdfExtractor`. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Инициализирует новый объект `PdfExtractor` на основе *документа*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Получает или задаёт конечную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Устанавливает режим процесса извлечения изображений. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Устанавливает режим результата извлечения текста. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Истинно, когда текст содержит ивритские или арабские символы. Этот случай необходимо учитывать специально, поскольку функции строк меняют своё поведение и начинают обработку текста справа налево (за исключением цифр и других не текстовых символов). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Получает или задаёт пароль входного файла. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Устанавливает или получает разрешение для извлечённых изображений. Значение по умолчанию — 150. Изображения с более высоким разрешением более чёткие. Однако увеличение разрешения приводит к росту времени и памяти, необходимых для извлечения изображений. Обычно, чтобы получить чёткое изображение, достаточно установить разрешение 150 или 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Получает или задаёт начальную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Получает или задает параметры поиска текста. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Привязывает PDF‑документ из потока. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Привязать входной PDF‑файл. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Освобождает Aspose.Pdf.Document, связанный с фасадом. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Извлекает вложения из PDF‑документа. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Извлекает вложение в PDF-файл по имени вложения. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Извлекает изображения из PDF-файла. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Извлекает текст из документа Pdf, используя кодировку Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Извлекает текст из документа Pdf, используя указанную кодировку. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Сохраняет все файлы вложений в потоки. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Сохраняет вложение в файл. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Получает список вложений. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Возвращает список вложений в PDF-файле. Примечание: перед использованием этого метода необходимо вызвать ExtractAttachments. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Получает следующее изображение из PDF-файла и сохраняет его в поток. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Получает следующее изображение из PDF-документа. Примечание: перед использованием этого метода необходимо вызвать ExtractImage. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Получает следующее изображение из PDF-файла и сохраняет его в поток в указанном формате изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Получает следующее изображение из PDF-документа в указанном формате изображения. Примечание: перед использованием этого метода необходимо вызвать ExtractImage. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Сохраняет текст одной страницы в поток. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Сохраняет текст одной страницы в файл. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Сохраняет текст в поток. см. также:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Сохраняет текст в файл. см. также:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Сохраняет текст в поток. см. также:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Проверяет, доступны ли дополнительные изображения в PDF-документе. Примечание: перед использованием этого метода необходимо вызвать ExtractImage. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Указывает, можно ли получить дополнительный текст или нет. |

### См. также

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


