---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: مفوض لتوقيع تجزئة الوثيقة بشكل مخصص
type: docs
weight: 5260
url: /ar/net/aspose.pdf.forms/signhash/
---
## مفوض SignHash

مفوض لتوقيع تجزئة الوثيقة بشكل مخصص.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hash | Byte[] | تجزئة الوثيقة المدخلة. |
| digestHashAlgorithm | DigestHashAlgorithm | خوارزمية التجزئة المستخدمة لإنشاء التجزئة. القيمة لن تكون أبداً مساوية لـ Auto. |

### قيمة الإرجاع

التوقيع الناتج.

## ملاحظات

لاحظ أنه سواء كانت التوقيع الرقمي مفصولاً أم لا، فإن معامل التجزئة سيكون دائماً هو التجزئة النهائية التي سيتم توقيعها.

### انظر أيضًا

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)