---
title: Class CompromiseCheckResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.CompromiseCheckResult 类。表示用于检查文档数字签名是否被篡改的类
type: docs
weight: 10100
url: /zh/net/aspose.pdf.signatures/compromisecheckresult/
---
## CompromiseCheckResult class

表示用于检查文档数字签名是否被篡改的类。

```csharp
public sealed class CompromiseCheckResult
```

## Properties

| Name | Description |
| --- | --- |
| [HasCompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/hascompromisedsignatures/) { get; } | 指示文档中是否存在任何被篡改的数字签名。如果至少有一个签名被篡改，则返回 true；否则返回 false。 |
| [SignaturesCoverage](../../aspose.pdf.signatures/compromisecheckresult/signaturescoverage/) { get; } | 获取文档中数字签名的覆盖状态。如果等于 Undefined，则表示其中一个签名被篡改。 |

## Fields

| Name | Description |
| --- | --- |
| readonly [CompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/compromisedsignatures/) | 获取已被识别为被篡改的数字签名集合。此属性包含文档中检测到的所有被篡改签名的列表。 |

### See Also

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)