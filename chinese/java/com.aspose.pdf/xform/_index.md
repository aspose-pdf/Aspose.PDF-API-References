---
title: "XForm"
linktitle: "XForm"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 XForm 的类"
type: docs
weight: 5590
url: /zh/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

表示 XForm 的类

## 方法

| 方法 | 描述 |
| --- | --- |
| [close](#close--) | 释放内存 |
| [containsOwnResources](#containsOwnResources--) | 如果包含自有资源则返回 True |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | 在文档中创建新的 XForm。 |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | 创建复制页面内容的 XForm。 |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | 释放内存 |
| [freeMemory](#freeMemory--) | 清除缓存数据 |
| [getBBox](#getBBox--) | 获取表单的边界框。 |
| [getContents](#getContents--) | 获取表单的操作符。 |
| [getEngineObj](#getEngineObj--) | 仅内部使用 |
| [getIT](#getIT--) | 获取表单 IT。Form IT 是描述 XObject 意图的名称。 |
| [getMatrix](#getMatrix--) | 获取表单的矩阵。 |
| [getName](#getName--) | 获取表单名称。表单名称是在页面资源的 XObejct 字典中用于引用表单的名称。 |
| [getOpi](#getOpi--) | 获取开放预印刷接口 (OPI)。 |
| [getRectangle](#getRectangle--) | 获取表单的矩形。 |
| [getResources](#getResources--) | 返回 Form X-Object 的资源。如果 Form 没有资源且 allowCreate 为 true，资源将自动为该表单创建。 |
| [getResources](#getResources-boolean-) | 返回 Form X-Object 的资源 |
| [getResourcesField](#getResourcesField--) | 获取 Form XObject 资源。 |
| [getSubtype](#getSubtype--) | 获取表单的子类型。 |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | 设置表单的边界框。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | 设置表单的矩阵。 |
| [setName](#setName-java.lang.String-) | 设置表单名称。表单名称是在页面资源的 XObejct 字典中用于引用表单的名称。 |

### close {#close--}
```
public final void close()
```

释放内存

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

如果包含自有资源则返回 True

**Returns:**
布尔值

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
在文档中创建新的 XForm。

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
创建复制页面内容的 XForm。

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

释放内存

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

清除缓存数据

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

获取表单的边界框。

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

获取表单的操作符。

**Returns:**
OperatorCollection 对象

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

仅内部使用

**Returns:**
IPdfObject 对象

### getIT {#getIT--}
```
public final String getIT()
```

获取表单 IT。Form IT 是描述 XObject 意图的名称。

**Returns:**
字符串值

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

获取表单的矩阵。

**Returns:**
Matrix

### getName {#getName--}
```
public String getName()
```

获取表单名称。表单名称是在页面资源的 XObejct 字典中用于引用表单的名称。

**Returns:**
字符串

### getOpi {#getOpi--}
```
public Opi getOpi()
```

获取开放预印刷接口 (OPI)。

**Returns:**
Opi 实例

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取表单的矩形。

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

返回 Form X-Object 的资源。如果 Form 没有资源且 allowCreate 为 true，资源将自动为该表单创建。

**Returns:**
Resources 实例

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

返回 Form X-Object 的资源

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| allowCreate |  | 如果 For 没有资源且 allowCreate 为 true，则会自动为表单创建 Resources。 |

**Returns:**
Resources 实例

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

获取 Form XObject 资源。

**Returns:**
Resources 实例。如果 For 没有资源，则会自动为表单创建 Resources。

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

获取表单的子类型。

**Returns:**
字符串值

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
设置表单的边界框。

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
设置表单的矩阵。

### setName {#setName-java.lang.String-}
设置表单名称。表单名称是在页面资源的 XObejct 字典中用于引用表单的名称。
