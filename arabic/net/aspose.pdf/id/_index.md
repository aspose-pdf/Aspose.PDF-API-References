---
title: "الفئة Id"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Id. تمثل بنية معرف الملف."
type: docs
weight: 5980
url: /ar/net/aspose.pdf/id/
---
## Id class

يمثل بنية معرف الملف.

```csharp
public class Id
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | تغيير المعرف بناءً على محتويات المستند في وقت آخر تحديث له. |
| [Original](../../aspose.pdf/id/original/) { get; } | معرف دائم يعتمد على محتويات المستند في الوقت الذي تم إنشاؤه فيه أصلاً. |

## أمثلة

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


