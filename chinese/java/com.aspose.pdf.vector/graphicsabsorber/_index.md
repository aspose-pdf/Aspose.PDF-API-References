---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Aspose.PDF for Java API 参考"
description: "表示图形元素的吸收器对象。执行图形搜索并通过 {@code GraphicsAbsorber.Elements}({@link 提供对搜索结果的访问。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

表示图形元素的吸收器对象。执行图形搜索并通过 {@code GraphicsAbsorber.Elements}（{@link GraphicsAbsorber#getElements}）集合提供对搜索结果的访问。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose](#dispose--) | 释放 {@link GraphicsAbsorber} 类使用的所有资源。 |
| [getElements](#getElements--) | 获取以 {@link GraphicElement} 对象呈现的搜索出现集合。 |
| [resumeUpdate](#resumeUpdate--) | 恢复对 Page#getContents 和所有 @link XForm#getContents 的更新。此操作是为提升性能而进行的，另请参见。 |
| [suppressUpdate](#suppressUpdate--) | 抑制对 Page#getContents 和所有 @link XForm#getContents 的更新。此操作是为提升性能而进行的，另请参见。 |
| [visit](#visit-com.aspose.pdf.Page-) | 在指定页面上执行搜索。 |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

释放 {@link GraphicsAbsorber} 类使用的所有资源。

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

获取以 {@link GraphicElement} 对象呈现的搜索出现集合。

**Returns:**
GraphicElementCollection 实例

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

恢复对 Page#getContents 和所有 @link XForm#getContents 的更新。此操作是为提升性能而进行的，另请参见。

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

抑制对 Page#getContents 和所有 @link XForm#getContents 的更新。此操作是为提升性能而进行的，另请参见。

### visit {#visit-com.aspose.pdf.Page-}
在指定页面上执行搜索。
