---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.XfdfReader. فئة تقوم بقراءة تنسيق XFDF
type: docs
weight: 2740
url: /ar/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

فئة تقوم بقراءة تنسيق XFDF.

```csharp
public sealed class XfdfReader
```

## Constructors

| Name | Description |
| --- | --- |
| [XfdfReader](xfdfreader/)() | المُنشئ الافتراضي. |

## Methods

| Name | Description |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | يقوم بتحليل ملف XFDF ويعيد المعلومات كجدول تجزئة. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | يستورد التعليقات التوضيحية من ملف XFDF ويضعها في المستند. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | يستورد قيم الحقول من ملف XFDF. |

## Examples

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)