---
title: "SignaturesCompromiseDetector.Check"
second_title: "Aspose.PDF for .NET API 参考"
description: "SignaturesCompromiseDetector 方法。检查文档的数字签名是否受损"
type: docs
weight: 20
url: /zh/net/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector.Check method

检查 Document 的数字签名是否被破坏。

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | 文档验证的结果。 |

### 返回值

如果未检测到签名受损，则为 True。

## 备注

对没有数字签名的文档使用此方法将返回 `True`。

### 另请参见

* class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* class [SignaturesCompromiseDetector](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


