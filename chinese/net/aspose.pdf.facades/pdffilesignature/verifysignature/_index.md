---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 方法。检查签名的有效性
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

检查签名的有效性。

```csharp
public bool VerifySignature(SignatureName signName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signName | SignatureName | 签名的名称。 |

### 返回值

返回一个布尔类型的结果。

### 另请参阅

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

检查签名的有效性。

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signName | SignatureName | 签名的名称。 |
| options | ValidationOptions | 验证选项。 |
| validationResult | ValidationResult& | 证书验证结果。 |

### 返回值

返回一个布尔类型的结果。

## 备注

此方法允许您使用 OCSP 和/或 CRL（证书撤销列表）检查签名证书的撤销。此方法不检查证书链及其有效性，但会检查最终证书是否已被撤销。

### 另请参阅

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)