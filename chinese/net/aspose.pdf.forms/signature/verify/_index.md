---
title: Signature.Verify
second_title: Aspose.PDF for .NET API Reference
description: 签名方法。验证与此签名相关的文档，如果文档有效则返回 true，否则返回 false
type: docs
weight: 170
url: /zh/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

验证与此签名相关的文档，如果文档有效则返回 true，否则返回 false。

```csharp
public bool Verify()
```

### 返回值

如果文档有效则返回 true。

### 另请参阅

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

验证与此签名相关的文档，如果文档有效则返回 true，否则返回 false。

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | ValidationOptions | 验证选项。 |
| validationResult | ValidationResult& | 证书验证结果。 |

### 返回值

如果文档有效则返回 true。

### 另请参阅

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)