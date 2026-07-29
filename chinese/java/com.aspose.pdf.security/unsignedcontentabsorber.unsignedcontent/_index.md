---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Aspose.PDF for Java API 参考"
description: "封装从 PDF 文档中提取的未签名内容元素。此类提供对页面、表单字段、XForms 和属于未签名部分的注释的访问。"
type: docs
weight: 50
url: /zh/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

封装从 PDF 文档中提取的未签名内容元素。此类提供对页面、表单字段、XForm 和文档中未签名内容所包含的注释的访问。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAnnotations](#getAnnotations--) | 获取可能已更改或新增的已修改注释的字典。 |
| [getForms](#getForms--) | 获取已增量更改或新增的表单字段。 |
| [getPages](#getPages--) | 获取内容未签名或已增量更改的页面列表。该页面被视为已修改，且 XForms 不会被检查，也不会出现在 XForms 列表中。 |
| [getXForms](#getXForms--) | 获取可能已更改的已修改 XForm 对象的字典，尽管页面本身未更改（不在页面列表中）。 |
| [setXForms](#setXForms-java.util.HashMap-) | 一个已修改 XForm 对象的字典，可能已更改，尽管页面本身未更改（不在页面列表中）。 |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

获取可能已更改或新增的已修改注释的字典。

**Returns:**
一个可能已更改或新增的已修改注释的字典。

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

获取已增量更改或新增的表单字段。

**Returns:**
已增量更改或新增的表单字段。

### getPages {#getPages--}
```
public final List < Page > getPages()
```

获取内容未签名或已增量更改的页面列表。该页面被视为已修改，且 XForms 不会被检查，也不会出现在 XForms 列表中。

**Returns:**
一个内容未签名或已增量更改的页面列表。

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

获取可能已更改的已修改 XForm 对象的字典，尽管页面本身未更改（不在页面列表中）。

**Returns:**
一个可能已更改的已修改 XForm 对象的字典，尽管页面本身没有更改（不在 Pages 列表中）。

### setXForms {#setXForms-java.util.HashMap-}
一个已修改 XForm 对象的字典，可能已更改，尽管页面本身未更改（不在页面列表中）。
