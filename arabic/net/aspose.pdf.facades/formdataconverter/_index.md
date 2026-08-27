---
title: "الفئة FormDataConverter"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.FormDataConverter. تمثل فئة لتحويل البيانات من تنسيق إلى آخر. يمكنها تحويل البيانات في fdf/xml/pdf/xfdf إلى OLEDB/OdbcDB. كما يمكنها تحويل البيانات في OLEDB/OdbcDB إلى البيانات في fdf/xml/xfdf. يمكنها تحويل fdf إلى xml مع علامة ذات اسم ثابت."
type: docs
weight: 4440
url: /ar/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

يمثل فئة لتحويل البيانات من تنسيق إلى آخر. يمكنه تحويل البيانات في fdf/xml/pdf/xfdf إلى OLEDB/OdbcDB. كما يمكنه تحويل البيانات في OLEDB/OdbcDB إلى البيانات في fdf/xml/xfdf. يمكنه تحويل fdf إلى xml باستخدام علامة "hard-named".

```csharp
public sealed class FormDataConverter
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ستقوم ExportFromData بمسح الجدول قبل تصدير البيانات. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ستقوم ConvertToDataTable بإنشاء الحقل المطلوب إذا لم يكن موجودًا في الجدول. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ستقوم ImportIntoDatabase بإنشاء الجدول إذا لم يكن موجودًا. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ستقوم ImportIntoDatabase بحذف الجدول الحالي وإنشاء جدول جديد إذا تم تعيين هذه الخاصية إلى true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | يحصل أو يعيّن حاوية البيانات الوسطى، وهي DataTable واحدة. يجب تعريفها قبل تحويل البيانات من تنسيق إلى آخر. يجب تعريف الأعمدة (Columns) واسم الجدول (TableName) في DataTable. اسم الجدول (TableName) هو اسم الجدول في قاعدة البيانات. اسم كل عمود (ColumnName) هو اسم الحقل المؤهل في pdf. تسمية كل عمود (Caption) هي اسم العمود في الجدول بقاعدة البيانات. إذا كان اسم الحقل هو نفسه اسم عمود الجدول، فلا يلزم تحديد Caption. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | هذه الطريقة مهجورة. يرجى استخدام ConvertToStreams() بدلاً من ذلك. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | تحويل ملفات التدفقات إلى جدول. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | تحويل البيانات في الجدول إلى تدفقات. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | تصدير البيانات من قاعدة البيانات إلى جدول. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | استيراد البيانات من الجدول إلى قاعدة البيانات. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | تحويل ملف FDF إلى XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | تحويل ملف بيانات نموذج استيراد/تصدير XML إلى تنسيق FDF. |

### انظر أيضًا

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


