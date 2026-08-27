---
title: "Signature.Verify"
second_title: "Aspose.PDF for .NET API 参考"
description: "Signature 方法。验证关于此签名的文档，如果文档有效则返回 true，否则返回 false"
type: docs
weight: 170
url: /zh/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

验证文档相对于此签名的有效性，如果文档有效则返回 true，否则返回 false。

```csharp
public bool Verify()
```

### 返回值

如果文档有效则为 true。

### 另请参见

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

验证文档相对于此签名的有效性，如果文档有效则返回 true，否则返回 false。

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | ValidationOptions | 验证选项。 |
| validationResult | ValidationResult& | 证书验证结果。 |

### 返回值

如果文档有效则为 true。

### 另请参见

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

验证文档相对于此签名的有效性，如果文档有效则返回 true，否则返回 false。验证使用外部公钥证书进行。

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | 用于验证的公钥证书。 |
| options | ValidationOptions | 验证选项。 |
| validationResult | ValidationResult& | 证书验证结果。 |

### 返回值

如果文档有效则为 true。

### 另请参见

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


