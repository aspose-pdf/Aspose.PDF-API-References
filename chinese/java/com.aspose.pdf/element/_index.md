---
title: "Element"
linktitle: "Element"
second_title: "Aspose.PDF for Java API 参考"
description: "表示逻辑结构基础元素的类。"
type: docs
weight: 1180
url: /zh/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

表示逻辑结构基础元素的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getActualText](#getActualText--) | (Optional; PDF 1.4) 文本是结构元素及其子元素的精确替代。此替代文本（应尽可能适用于最小的内容块）在提取文档内容以支持残障用户的可访问性或用于其他目的时非常有用。 |
| [getAlt](#getAlt--) | (Optional) 结构元素及其子元素的人类可读形式的替代描述，在提取文档内容以支持残障用户的可访问性或用于其他目的时非常有用。 |
| [getChildren](#getChildren--) | 获取子元素集合。 |
| [getE](#getE--) | (Optional; PDF 1.5) 缩写的展开形式。 |
| [getLang](#getLang--) | (Optional; PDF 1.4) 一种语言，指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。 |
| [remove](#remove--) | 移除元素。 |
| [setActualText](#setActualText-java.lang.String-) | (Optional; PDF 1.4) 文本是结构元素及其子元素的精确替代。此替代文本（应尽可能适用于最小的内容块）在提取文档内容以支持残障用户的可访问性或用于其他目的时非常有用。 |
| [setAlt](#setAlt-java.lang.String-) | (Optional) 结构元素及其子元素的人类可读形式的替代描述，在提取文档内容以支持残障用户的可访问性或用于其他目的时非常有用。 |
| [setE](#setE-java.lang.String-) | (Optional; PDF 1.5) 缩写的展开形式。 |
| [setLang](#setLang-java.lang.String-) | (Optional; PDF 1.4) 一种语言，指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。 |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Optional; PDF 1.4) 文本是结构元素及其子元素的精确替代。此替代文本（应尽可能适用于最小的内容块）在提取文档内容以支持残障用户的可访问性或用于其他目的时非常有用。

**Returns:**
字符串对象

### getAlt {#getAlt--}
```
public String getAlt()
```

(Optional) 结构元素及其子元素的人类可读形式的替代描述，在提取文档内容以支持残障用户的可访问性或用于其他目的时非常有用。

**Returns:**
字符串对象

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

获取子元素集合。

**Returns:**
ElementCollection 实例

### getE {#getE--}
```
public String getE()
```

(Optional; PDF 1.5) 缩写的展开形式。

**Returns:**
字符串对象

### getLang {#getLang--}
```
public String getLang()
```

(Optional; PDF 1.4) 一种语言，指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。

**Returns:**
字符串对象

### remove {#remove--}
```
public final void remove()
```

移除元素。

### setActualText {#setActualText-java.lang.String-}
(Optional; PDF 1.4) 文本是结构元素及其子元素的精确替代。此替代文本（应尽可能适用于最小的内容块）在提取文档内容以支持残障用户的可访问性或用于其他目的时非常有用。

### setAlt {#setAlt-java.lang.String-}
(Optional) 结构元素及其子元素的人类可读形式的替代描述，在提取文档内容以支持残障用户的可访问性或用于其他目的时非常有用。

### setE {#setE-java.lang.String-}
(Optional; PDF 1.5) 缩写的展开形式。

### setLang {#setLang-java.lang.String-}
(Optional; PDF 1.4) 一种语言，指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。
