---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Aspose.PDF for .NET API 参考"
description: "ValidationOptions 属性。获取或设置一个值，指示在验证过程中是否应检查证书链。"
type: docs
weight: 20
url: /zh/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

获取或设置一个值，指示在验证过程中是否应检查证书链。

```csharp
public bool CheckCertificateChain { get; set; }
```

## 备注

当设置该属性时，将检查证书链的存在；如果不存在，则验证结果为 Undefined，这对应于 Adobe Acrobat 的行为。如果只想在线检查吊销状态，请将该字段设为 `false`。默认值为 `false`。

### 另请参见

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


