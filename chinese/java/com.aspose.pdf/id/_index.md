---
title: "Id"
linktitle: "Id"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示文件标识符结构。 </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /zh/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> 表示文件标识符结构。 </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## 方法

| 方法 | 描述 |
| --- | --- |
| [getModified](#getModified--) | 根据文档在上次更新时的内容更改标识符。 |
| [getOriginal](#getOriginal--) | 基于文档在最初创建时内容的永久标识符。 |

### getModified {#getModified--}
```
public String getModified()
```

根据文档在上次更新时的内容更改标识符。

**Returns:**
字符串值

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

基于文档在最初创建时内容的永久标识符。

**Returns:**
字符串值
