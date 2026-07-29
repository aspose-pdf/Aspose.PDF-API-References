---
title: "المندوب SignHash"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "المندوب لتوقيع مخصص لتجزئة المستند"
type: docs
weight: 5380
url: /ar/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

مفوض لتوقيع تجزئة المستند بشكل مخصص.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| التجزئة | Byte[] | تجزئة الإدخال للمستند. |
| digestHashAlgorithm | DigestHashAlgorithm | خوارزمية التجزئة المستخدمة لإنشاء التجزئة. لن تكون القيمة مطابقة أبداً لـ Auto. |

### قيمة الإرجاع

التوقيع الناتج.

## ملاحظات

لاحظ أنه سواء كان التوقيع الرقمي منفصلاً أم لا، فإن معامل التجزئة سيكون دائماً هو التجزئة النهائية التي سيتم توقيعها.

### انظر أيضًا

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


