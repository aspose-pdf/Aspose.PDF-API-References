---
title: "SignaturesCompromiseDetector"
linktitle: "SignaturesCompromiseDetector"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于检查文档中受损签名的类。检测器仅检查已知的签名受损方式。验证无法提供 100% 的保证。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.signatures/signaturescompromisedetector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.SignaturesCompromiseDetector

```
public final class SignaturesCompromiseDetector extends Object
```

表示用于检查文档被破坏签名的类。检测器仅检查已知的签名破坏方式。验证无法提供 100% 的签名未被破坏的保证，并且对于未在测试中涉及的新的、未知的破坏方法可能会出现误报（假阴性）结果。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SignaturesCompromiseDetector](#SignaturesCompromiseDetector-com.aspose.pdf.IDocument-) | 创建 {@link SignaturesCompromiseDetector} 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [check](#check-com.aspose.pdf.signatures.CompromiseCheckResult:A-) | 检查文档的数字签名是否受损。 |

### SignaturesCompromiseDetector {#SignaturesCompromiseDetector-com.aspose.pdf.IDocument-}
创建 {@link SignaturesCompromiseDetector} 类的实例。

### check {#check-com.aspose.pdf.signatures.CompromiseCheckResult:A-}
检查文档的数字签名是否受损。
