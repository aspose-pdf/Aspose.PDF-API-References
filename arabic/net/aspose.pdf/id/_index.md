---
title: Id
second_title: Aspose.PDF لمرجع .NET API
description: يمثل بنية معرف الملف.
type: docs
weight: 3710
url: /ar/net/aspose.pdf/id/
---
## Id class

يمثل بنية معرف الملف.

```csharp
public class Id
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified) { get; } | تغيير المعرف بناءً على محتويات المستند في وقت آخر تحديث له. |
| [Original](../../aspose.pdf/id/original) { get; } | معرّف دائم يعتمد على محتويات المستند وقت إنشائه في الأصل. |

### أمثلة

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->