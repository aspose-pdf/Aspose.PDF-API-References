---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: SignaturesCompromiseDetector 方法。检查文档的数字签名是否被篡改
type: docs
weight: 20
url: /zh/net/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector.Check 方法

检查文档的数字签名是否被篡改。

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | 文档验证的结果。 |

### 返回值

如果未检测到签名的篡改，则返回 True。

## 备注

对没有数字签名的文档使用此方法将返回 `True`。

### 另请参阅

* 类 [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* 类 [SignaturesCompromiseDetector](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)