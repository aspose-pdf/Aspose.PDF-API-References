---
title: "XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "处理相关数据封装的类"
type: docs
weight: 5560
url: /zh/java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfaParserOptions

```
public class XfaParserOptions extends Object
```

处理相关数据封装的类

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XfaParserOptions](#XfaParserOptions-java.awt.geom.Dimension2D-) | 初始化 {@code XfaParserOptions} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBasePath](#getBasePath--) | 获取或设置基路径。值：基路径。 |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | 如果此属性为 true，则会为必需的 Xfa "excluded groups" 绘制额外的红色矩形。引入此属性是因为在将 Xfa 表单表示转换为标准时，缺少对排除组的类比。默认值为 false。 |
| [getPageSize](#getPageSize--) | 获取或设置页面的大小。值：页面的大小。 |
| [getSigned](#getSigned--) | 如果此属性为 true，则文档将在使用 xfa 表单流（如果存在）的情况下进行转换。如果为 false，则 xfa 表单流将被忽略。引入此属性是因为尚不清楚如何计算用于检查签名的校验和。 |
| [setBasePath](#setBasePath-java.net.URI-) | 获取或设置基路径。值：基路径。 |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | 如果此属性为 true，则会为必需的 Xfa "excluded groups" 绘制额外的红色矩形。引入此属性是因为在将 Xfa 表单表示转换为标准时，缺少对排除组的类比。默认值为 false。 |
| [setPageSize](#setPageSize-java.awt.geom.Dimension2D-) | 获取或设置页面的大小。值：页面的大小。 |
| [setSigned](#setSigned-boolean-) | 如果此属性为 true，则文档将在使用 xfa 表单流（如果存在）的情况下进行转换。如果为 false，则 xfa 表单流将被忽略。引入此属性是因为尚不清楚如何计算用于检查签名的校验和。 |

### XfaParserOptions {#XfaParserOptions-java.awt.geom.Dimension2D-}
初始化 {@code XfaParserOptions} 类的新实例。

### getBasePath {#getBasePath--}
```
public URI getBasePath()
```

获取或设置基路径。值：基路径。

**Returns:**
URI 对象

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

如果此属性为 true，则会为必需的 Xfa "excluded groups" 绘制额外的红色矩形。引入此属性是因为在将 Xfa 表单表示转换为标准时，缺少对排除组的类比。默认值为 false。

**Returns:**
布尔值

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

获取或设置页面的大小。值：页面的大小。

**Returns:**
Dimension2D 对象

### getSigned {#getSigned--}
```
public boolean getSigned()
```

如果此属性为 true，则文档将在使用 xfa 表单流（如果存在）的情况下进行转换。如果为 false，则 xfa 表单流将被忽略。引入此属性是因为尚不清楚如何计算用于检查签名的校验和。

**Returns:**
布尔值

### setBasePath {#setBasePath-java.net.URI-}
获取或设置基路径。值：基路径。

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

如果此属性为 true，则会为必需的 Xfa "excluded groups" 绘制额外的红色矩形。引入此属性是因为在将 Xfa 表单表示转换为标准时，缺少对排除组的类比。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPageSize {#setPageSize-java.awt.geom.Dimension2D-}
获取或设置页面的大小。值：页面的大小。

### setSigned {#setSigned-boolean-}
```
public void setSigned(boolean value)
```

如果此属性为 true，则文档将在使用 xfa 表单流（如果存在）的情况下进行转换。如果为 false，则 xfa 表单流将被忽略。引入此属性是因为尚不清楚如何计算用于检查签名的校验和。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
