---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Id. تمثل هيكل معرف الملف
type: docs
weight: 5850
url: /ar/net/aspose.pdf/id/
---
## فئة Id

تمثل هيكل معرف الملف.

```csharp
public class Id
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | تغيير المعرف بناءً على محتويات الوثيقة في الوقت الذي تم تحديثه فيه آخر مرة. |
| [Original](../../aspose.pdf/id/original/) { get; } | معرف دائم بناءً على محتويات الوثيقة في الوقت الذي تم إنشاؤه فيه أصلاً. |

## أمثلة

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)