---
title: "Layer"
linktitle: "Layer"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 页面中的图层。"
type: docs
weight: 2640
url: /zh/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

表示 PDF 页面中的图层。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | 初始化 {@code Layer} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [delete](#delete--) | 从 PDF 文档中删除当前图层。 |
| [flatten](#flatten-boolean-) | 将指定的图层展平。 |
| [getContents](#getContents--) | <p> 获取图层内容。 </p> |
| [getDefaultState](#getDefaultState--) | 获取 PDF 图层的默认状态。 |
| [getId](#getId--) | 获取图层 ID。 |
| [getLocked](#getLocked--) | 获取指示图层是否被锁定的值。 |
| [getName](#getName--) | 获取图层名称。 |
| [lock](#lock--) | 锁定图层。 |
| [save](#save-java.io.OutputStream-) | 将当前图层保存到 PDF 文档。 |
| [save](#save-java.lang.String-) | 将当前图层保存到 PDF 文档。 |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | 设置 PDF 图层的默认状态。 |
| [unlock](#unlock--) | 解锁图层。 |

### Layer {#Layer-java.lang.String-java.lang.String-}
初始化 {@code Layer} 类的新实例。

### delete {#delete--}
```
public final void delete()
```

从 PDF 文档中删除当前图层。

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

将指定的图层展平。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cleanupContentStream |  | 指定是否从内容流中移除可选内容组标记。将 {@code cleanupContentStream} 参数设置为 false 可加快展平过程。 |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> 获取图层内容。 </p>

**Returns:**
{@code List<Operator>} 对象

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

获取 PDF 图层的默认状态。

**Returns:**
PDF 图层的默认状态。

### getId {#getId--}
```
public String getId()
```

获取图层 ID。

**Returns:**
字符串值

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

获取指示图层是否被锁定的值。

**Returns:**
布尔值

### getName {#getName--}
```
public String getName()
```

获取图层名称。

**Returns:**
字符串值

### lock {#lock--}
```
public final void lock()
```

锁定图层。

### save {#save-java.io.OutputStream-}
将当前图层保存到 PDF 文档。

### save {#save-java.lang.String-}
将当前图层保存到 PDF 文档。

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
设置 PDF 图层的默认状态。

### unlock {#unlock--}
```
public final void unlock()
```

解锁图层。
