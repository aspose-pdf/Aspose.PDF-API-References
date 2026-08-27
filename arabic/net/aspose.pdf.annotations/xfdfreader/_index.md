---
title: "الفئة XfdfReader"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Annotations.XfdfReader. الفئة التي تقوم بقراءة تنسيق XFDF"
type: docs
weight: 2840
url: /ar/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

الفئة التي تقوم بقراءة تنسيق XFDF.

```csharp
public sealed class XfdfReader
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XfdfReader](xfdfreader/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | يقوم بتحليل ملف XFDF ويعيد المعلومات كجدول تجزئة. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | استيراد التعليقات التوضيحية من ملف XFDF ووضعها في المستند. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | استيراد قيم الحقول من ملف XFDF. |

## أمثلة

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### انظر أيضًا

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


