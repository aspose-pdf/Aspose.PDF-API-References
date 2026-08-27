---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSignature 方法。提取签名的单个 X.509 证书"
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

提取签名的单个 X.509 证书。

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signName | SignatureName | 签名的名称。 |
| 证书 | X509Certificate2& | 如果找到证书，则返回 X.509 单个证书对象；否则为 null。 |

### 返回值

已找到有效证书。

### 另请参见

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

提取签名的单个 X.509 证书为流。

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signName | SignatureName | 签名的名称。 |
| stream | Stream& | 如果找到证书，则返回 X.509 单个证书流；否则为 null。 |

### 返回值

已找到有效证书。

### 另请参见

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


