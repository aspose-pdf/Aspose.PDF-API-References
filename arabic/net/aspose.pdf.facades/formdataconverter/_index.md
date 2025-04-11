---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.FormDataConverter. تمثل فئة لتحويل البيانات من تنسيق إلى آخر. يمكنها تحويل البيانات من fdf/xml/pdf/xfdf إلى OLEDB/OdbcDB. يمكنها أيضًا تحويل البيانات من OLEDB/OdbcDB إلى البيانات في fdf/xml/xfdf. يمكنها تحويل fdf إلى xml مع علامة "مسمّاة بشكل ثابت".
type: docs
weight: 4320
url: /ar/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

تمثل فئة لتحويل البيانات من تنسيق إلى آخر. يمكنها تحويل البيانات من fdf/xml/pdf/xfdf إلى OLEDB/OdbcDB. يمكنها أيضًا تحويل البيانات من OLEDB/OdbcDB إلى البيانات في fdf/xml/xfdf. يمكنها تحويل fdf إلى xml مع علامة "مسمّاة بشكل ثابت".

```csharp
public sealed class FormDataConverter
```

## Constructors

| Name | Description |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | سيقوم ExportFromData بتفريغ الجدول قبل تصدير البيانات. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | سيقوم ConvertToDataTable بإنشاء الحقل المطلوب إذا لم يكن موجودًا في الجدول. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | سيقوم ImportIntoDatabase بإنشاء الجدول إذا لم يكن موجودًا. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | سيقوم ImportIntoDatabase بحذف الجدول الموجود وإنشاء جدول جديد إذا تم تعيين هذه الخاصية إلى true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | يحصل على أو يحدد حاوية البيانات الوسطى، وهي DataTable واحدة. يجب تعريفها قبل تحويل البيانات من تنسيق إلى آخر. يجب تعريف الأعمدة واسم الجدول في DataTable. اسم الجدول هو اسم الجدول في قاعدة البيانات. اسم كل عمود هو الاسم المؤهل للحقل في pdf. عنوان كل عمود هو اسم العمود في الجدول في قاعدة البيانات. إذا كان اسم الحقل هو نفسه اسم عمود الجدول، فلا حاجة لتحديد العنوان. |

## Methods

| Name | Description |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | هذه الطريقة قديمة. يرجى استخدام ConvertToStreams() بدلاً من ذلك. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | تحويل ملفات التدفقات إلى جدول. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | تحويل البيانات في الجدول إلى تدفقات. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | تصدير البيانات من قاعدة البيانات إلى الجدول. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | استيراد البيانات من الجدول إلى قاعدة البيانات. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | تحويل ملف FDF إلى XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | تحويل ملف بيانات استيراد/تصدير XML إلى تنسيق FDF. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)