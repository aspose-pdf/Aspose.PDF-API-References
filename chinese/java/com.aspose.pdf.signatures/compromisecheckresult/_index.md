---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于检查文档数字签名是否被篡改的类。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

表示用于检查文档数字签名是否被篡改的类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | 获取已被识别为受损的数字签名集合。此属性包含文档中检测到的所有受损签名的列表。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | 获取文档中数字签名的覆盖状态。如果它等于 {@code SignaturesCoverage#Undefined}，则其中一个签名已受损。 |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | 指示文档中是否存在受损的数字签名。如果至少有一个签名受损，则返回 true；否则返回 false。 |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

获取已被识别为受损的数字签名集合。此属性包含文档中检测到的所有受损签名的列表。

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

获取文档中数字签名的覆盖状态。如果它等于 {@code SignaturesCoverage#Undefined}，则其中一个签名已受损。

**Returns:**
SignaturesCoverage 元素

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

指示文档中是否存在受损的数字签名。如果至少有一个签名受损，则返回 true；否则返回 false。

**Returns:**
布尔值
