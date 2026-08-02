---
title: "Класс SubmitFormAction"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Annotations.SubmitFormAction класс. Класс, описывающий действие submitform."
type: docs
weight: 2740
url: /ru/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

Класс, описывающий действие submit-form.

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
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Получает или задает флаги действия отправки. |
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
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Если установлено, запись F в отправленном FDF должна быть спецификацией файла, содержащей встроенный поток файла, представляющий PDF‑файл, из которого отправляется FDF. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Если установлено, отправленный FDF будет исключать запись F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Если установлено, будут включены только те разметочные аннотации, у которых запись T совпадает с именем текущего пользователя. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Если сброшено, массив Fields указывает, какие поля включать в отправку. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Если установлено, имена полей и их значения будут отправлены в формате HTML‑формы. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Если установлено, имена полей и их значения будут отправлены с помощью HTTP‑GET запроса. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Если установлено, отправленный файл FDF должен включать все разметочные аннотации в базовом PDF‑документе. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Если установлено, отправленный файл FDF должен включать содержимое всех инкрементных обновлений. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Если установлено, должны быть отправлены все поля, указанные в массиве Fields, и флаг Include/Exclude. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Если установлено, координаты щелчка мыши, вызвавшего действие submit-form, должны передаваться как часть данных формы. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Если установлено, документ должен быть отправлен в формате PDF, используя MIME‑тип содержимого application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Если установлено, имена полей и их значения должны быть отправлены в формате XFDF. |

### См. также

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


