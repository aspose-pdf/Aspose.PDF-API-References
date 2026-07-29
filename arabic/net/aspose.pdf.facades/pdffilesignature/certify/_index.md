---
title: "PdfFileSignature.Certify"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSignature. تصدق على المستند باستخدام توقيع MDP. يجب توفير بيانات مثل سبب التوقيع والاتصال والموقع عبر الخصائص المقابلة لكائن Signature sig"
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

صادق المستند باستخدام توقيع MDP. يجب توفير بيانات مثل سبب التوقيع، جهة الاتصال والموقع عبر الخصائص المقابلة لكائن Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | الصفحة التي تم فيها إنشاء التوقيع. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة الاتصال للتوقيع. |
| SigLocation | String | موقع التوقيع. |
| مرئي | Boolean | ظهور التوقيع. |
| annotRect | Rectangle | مستطيل التوقيع. |
| docMdpSignature | DocMDPSignature | نوع MDP للوثيقة للتوقيع. |

### انظر أيضًا

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

صادق المستند باستخدام توقيع MDP الموجود في حقل التوقيع الموجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي الحقل على قاموس توقيع. وبالتالي فإن مستند pdf يحتوي بالفعل على حقل توقيع، لا يلزم توفير مكان لتخطيط التوقيع؛ يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يُعثر عليه باسم التوقيع (انظر معلمة sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| sigName | String | اسم حقل التوقيع. |
| docMdpSignature | DocMDPSignature | نوع التوقيع، يمكن أن يكون [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) و [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### انظر أيضًا

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


