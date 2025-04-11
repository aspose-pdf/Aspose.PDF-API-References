---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileSignature. تصديق الوثيقة بتوقيع MDP. يجب توفير بيانات مثل سبب التوقيع، جهة الاتصال والموقع من خلال الخصائص المقابلة لكائن التوقيع sig
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

تصديق الوثيقة بتوقيع MDP. يجب توفير بيانات مثل سبب التوقيع، جهة الاتصال والموقع من خلال الخصائص المقابلة لكائن التوقيع sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | الصفحة التي يتم فيها التوقيع. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة الاتصال للتوقيع. |
| SigLocation | String | موقع التوقيع. |
| visible | Boolean | رؤية التوقيع. |
| annotRect | Rectangle | مستطيل التوقيع. |
| docMdpSignature | DocMDPSignature | نوع توقيع MDP للوثيقة. |

### See Also

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

تصديق الوثيقة بتوقيع MDP الذي يتم وضعه في حقل التوقيع الموجود مسبقًا. قبل التوقيع، يجب أن يكون حقل التوقيع فارغًا، أي يجب ألا يحتوي الحقل على قاموس التوقيع. وبالتالي، إذا كانت وثيقة pdf تحتوي بالفعل على حقل توقيع، فلا يجب عليك توفير المكان لوضع التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه بواسطة اسم التوقيع (انظر معلمة sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sigName | String | اسم حقل التوقيع. |
| docMdpSignature | DocMDPSignature | نوع التوقيع، يمكن أن يكون [`PKCS1`](../../../aspose.pdf.forms/pkcs1/)، [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) و [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### See Also

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)