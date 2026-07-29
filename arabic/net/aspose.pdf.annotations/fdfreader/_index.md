---
title: "الفئة FdfReader"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Annotations.FdfReader. الفئة التي تقوم بقراءة تنسيق FDF"
type: docs
weight: 1790
url: /ar/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

فئة تقوم بقراءة تنسيق FDF.

```csharp
public sealed class FdfReader
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | استيراد التعليقات التوضيحية من ملف FDF ووضعها في المستند. |

## أمثلة

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### انظر أيضًا

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


