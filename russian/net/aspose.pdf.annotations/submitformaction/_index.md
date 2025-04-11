---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.SubmitFormAction. Класс, который описывает действие submitform
type: docs
weight: 2640
url: /ru/net/aspose.pdf.annotations/submitformaction/
---
## Класс SubmitFormAction

Класс, который описывает действие отправки формы.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Инициализирует объект SubmitFormAction. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Получает или задает флаги действия отправки |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Следующие действия в последовательности. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | URL назначения. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Получает строку для действия ECMAScript. |

## Поля

| Имя | Описание |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Если установлено, любые отправленные значения полей, представляющие даты, будут преобразованы в стандартный формат. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Если установлено, запись F отправленного FDF будет являться спецификацией файла, содержащей встроенный файловый поток, представляющий PDF-файл, из которого отправляется FDF. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Если установлено, отправленный FDF исключит запись F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Если установлено, будут включены только те аннотации разметки, чья запись T соответствует имени текущего пользователя. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Если очищено, массив Fields указывает, какие поля включить в отправку. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Если установлено, имена и значения полей будут отправлены в формате HTML Form. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Если установлено, имена и значения полей будут отправлены с использованием HTTP GET запроса. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Если установлено, отправленный файл FDF будет включать все аннотации разметки в исходном PDF-документе. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Если установлено, отправленный файл FDF будет включать содержимое всех инкрементальных обновлений. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Если установлено, все поля, обозначенные массивом Fields и флагом Include/Exclude, будут отправлены. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Если установлено, координаты щелчка мыши, вызвавшего действие отправки формы, будут переданы как часть данных формы. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Если установлено, документ будет отправлен как PDF, с использованием MIME типа содержимого application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Если установлено, имена и значения полей будут отправлены как XFDF. |

### См. также

* класс [PdfAction](../pdfaction/)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../)