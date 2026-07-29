---
title: "UnsignedContentAbsorber"
linktitle: "UnsignedContentAbsorber"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于从受数字签名管理的 PDF 文件中提取未签名内容的类。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

表示用于从受数字签名管理的 PDF 文件中提取未签名内容的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | 表示用于处理未签名内容的类。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [tryGetContent](#tryGetContent--) | 尝试从关联的文档中检索未签名内容。 |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
表示用于处理未签名内容的类。

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

尝试从关联的文档中检索未签名内容。

**Returns:**
一个 {@link UnsignedContentAbsorber.Result} 对象，包含未签名内容的详细信息、数字签名的覆盖范围、操作的成功状态以及信息性消息。
