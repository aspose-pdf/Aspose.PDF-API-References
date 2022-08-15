---
title: PdfExtractor
second_title: Aspose.PDF для справочника API .NET
description: Класс для извлечения изображений и текста из документа PDF.
type: docs
weight: 2460
url: /ru/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Класс для извлечения изображений и текста из документа PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfExtractor](pdfextractor#constructor)() | Инициализирует новый[`PdfExtractor`](../pdfextractor) объект. |
| [PdfExtractor](pdfextractor#constructor_1)(Document) | Инициализирует новый[`PdfExtractor`](../pdfextractor) объект на базе*document* . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage) { get; set; } | Получает или задает конечную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode) { get; set; } | Устанавливает режим для процесса извлечения изображений. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode) { get; set; } | Устанавливает режим извлечения результата текста. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi) { get; } | Верно, если в тексте есть еврейские или арабские символы. Этот случай должен быть рассмотрен специально, т.к. строковые функции меняют свое поведение и начинают обрабатывать текст справа налево (кроме чисел и других нетекстовых символов). |
| [Password](../../aspose.pdf.facades/pdfextractor/password) { get; set; } | Получает или устанавливает пароль входного файла. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution) { get; set; } | Установка или получение разрешения для извлеченных изображений. Значение по умолчанию: 150. Изображения с большим значением разрешения более четкие. Однако увеличение значения разрешения приводит к увеличению времени и памяти, необходимых для извлечения изображений. Обычно для получения четкого изображения достаточно установить разрешение 150 или 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage) { get; set; } | Получает или задает начальную страницу в диапазоне страниц, где будет выполняться операция извлечения. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions) { get; set; } | Получает или задает параметры текстового поиска. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_1)(Stream) | Связывает PDF-документ из потока. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_2)(string) | Привязать входной файл PDF. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Удаляет Aspose.Pdf.Document, связанный с фасадом. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment)() | Извлекает вложения из документа PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment_1)(string) | Извлекает вложение в файл PDF по имени вложения. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage)() | Извлечение изображений из файла PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext)() | Извлекает текст из документа Pdf, используя кодировку Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext_1)(Encoding) | Извлекает текст из документа Pdf, используя указанную кодировку. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment)() | Сохраняет все вложенные файлы в потоки. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment_1)(string) | Сохраняет вложение в файл. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo)() | Получает список вложений. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames)() | Возвращает список вложений в файле PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractAttachments. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage)(Stream) | Получить следующее изображение из файла PDF и сохранить его в потоке. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_2)(string) | Получает следующее изображение из документа PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_1)(Stream, ImageFormat) | Получить следующее изображение из файла PDF и сохранить его в поток с заданным форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_3)(string, ImageFormat) | Получает следующее изображение из документа PDF с заданным форматом изображения. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext)(Stream) | Сохраняет текст одной страницы в поток. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext_1)(string) | Сохраняет текст одной страницы в файл. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext)(Stream) | Сохраняет текст в поток. смотрите также:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_2)(string) | Сохраняет текст в файл. смотрите также:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_1)(Stream, bool) | Сохраняет текст в поток. смотрите также:[`ExtractText`](./extracttext) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage)() | Проверяет, доступны ли дополнительные изображения в документе PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext)() | Указывает, можно ли получить больше текстов или нет. |

### Смотрите также

* class [Facade](../facade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
