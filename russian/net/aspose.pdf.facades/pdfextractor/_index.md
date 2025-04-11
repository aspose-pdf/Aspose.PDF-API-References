---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfExtractor. Класс для извлечения изображений и текста из PDF документа
type: docs
weight: 4450
url: /ru/net/aspose.pdf.facades/pdfextractor/
---
## Класс PdfExtractor

Класс для извлечения изображений и текста из PDF документа.

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Получает или устанавливает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Устанавливает режим для процесса извлечения изображений. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Устанавливает режим для результата извлечения текста. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Истинно, когда текст содержит еврейские или арабские символы. Этот случай должен рассматриваться особенно, потому что функции строк изменяют свое поведение и начинают обрабатывать текст справа налево (за исключением чисел и других не текстовых символов). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Получает или устанавливает пароль входного файла. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Устанавливает или получает разрешение для извлеченных изображений. Значение по умолчанию — 150. Изображения с большим значением разрешения более четкие. Однако увеличение значения разрешения приводит к увеличению времени и памяти, необходимых для извлечения изображений. Обычно для получения четкого изображения достаточно установить разрешение на 150 или 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Получает или устанавливает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Получает или устанавливает параметры поиска текста. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Привязывает PDF документ из потока. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Привязывает входной PDF файл. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Освобождает Aspose.Pdf.Document, связанный с фасадом. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Извлекает вложения из PDF документа. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Извлекает вложение в PDF файл по имени вложения. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Извлекает изображения из PDF файла. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Извлекает текст из PDF документа с использованием кодировки Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Извлекает текст из PDF документа с использованием указанной кодировки. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Сохраняет все файлы вложений в потоки. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Сохраняет вложение в файл. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Получает список вложений. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Возвращает список вложений в PDF файле. Примечание: Метод ExtractAttachments должен быть вызван перед использованием этого метода. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Извлекает следующее изображение из PDF файла и сохраняет его в поток. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Извлекает следующее изображение из PDF документа. Примечание: Метод ExtractImage должен быть вызван перед использованием этого метода. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Извлекает следующее изображение из PDF файла и сохраняет его в поток с заданным форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Извлекает следующее изображение из PDF документа с заданным форматом изображения. Примечание: Метод ExtractImage должен быть вызван перед использованием этого метода. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Сохраняет текст одной страницы в поток. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Сохраняет текст одной страницы в файл. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Сохраняет текст в поток. см. также:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Сохраняет текст в файл. см. также:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Сохраняет текст в поток. см. также:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Проверяет, доступны ли еще изображения в PDF документе. Примечание: Метод ExtractImage должен быть вызван перед использованием этого метода. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Указывает, можно ли получить больше текстов или нет. |

### См. также

* класс [Facade](../facade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)