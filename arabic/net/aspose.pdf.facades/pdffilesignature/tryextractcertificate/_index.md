---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSignature. تستخرج شهادة X.509 الفردية للتوقيعات"
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

يستخرج شهادة X.509 الفردية للتوقيع.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |
| شهادة | X509Certificate2& | إذا تم العثور على شهادة فإنها تُعيد كائن شهادة X.509 الفردية؛ وإلا، null. |

### قيمة الإرجاع

تم العثور على شهادة صحيحة.

### انظر أيضًا

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

يستخرج شهادة X.509 الفردية للتوقيع كتيار.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |
| stream | Stream& | إذا تم العثور على شهادة فإنها تُعيد تدفق شهادة X.509 الفردية؛ وإلا، null. |

### قيمة الإرجاع

تم العثور على شهادة صحيحة.

### انظر أيضًا

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


