---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Aspose.PDF for Java API 参考"
description: "封装了尝试从 PDF 文档中提取未签名内容的操作结果。此类提供有关操作成功与否的信息以及详细信息。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

封装尝试从 PDF 文档中提取未签名内容的操作结果。此类提供有关操作成功与否的信息、未签名内容的详细信息、描述结果的消息以及文档签名的覆盖状态。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCoverage](#getCoverage--) | 获取一个值，指示文档被有效数字签名覆盖的程度。 |
| [getMessage](#getMessage--) | 获取描述操作结果的消息。 |
| [getSuccess](#getSuccess--) | 获取一个值，指示从文档检索未签名内容的操作是否成功。 |
| [getUnsignedContent](#getUnsignedContent--) | 获取未签名内容。 |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

获取一个值，指示文档被有效数字签名覆盖的程度。

**Returns:**
指示文档被有效数字签名覆盖程度的值。

### getMessage {#getMessage--}
```
public final String getMessage()
```

获取描述操作结果的消息。

**Returns:**
描述操作结果的消息。

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

获取一个值，指示从文档检索未签名内容的操作是否成功。

**Returns:**
指示从文档检索未签名内容的操作是否成功的值。

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

获取未签名内容。

**Returns:**
未签名内容。
