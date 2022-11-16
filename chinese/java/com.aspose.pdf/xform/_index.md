---
title: XForm
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类表示 XForm
type: docs
weight: 407
url: /zh/java/com.aspose.pdf/xform/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.pdf.ISupportsMemoryCleanup
```
public final class XForm implements ISupportsMemoryCleanup
```

类表示 XForm
## 方法

| 方法 | 描述 |
| --- | --- |
| [containsOwnResources()](#containsOwnResources--) | 如果包含自己的资源，则返回 True |
| [createNewForm(Page source, IDocument document)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | 创建复制页面内容的 XForm。 |
| [createNewForm(Page source, ITrailerable trailerable, Copier copier)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [createNewForm(ITrailerable trailerable)](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | 在文档中创建新的 XForm。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [freeMemory()](#freeMemory--) | 清除缓存数据 |
| [getBBox()](#getBBox--) | 获取表单边界框。 |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | 获取窗体的运算符。 |
| [getEngineObj()](#getEngineObj--) | 仅限内部 |
| [getMatrix()](#getMatrix--) | 获取表单的矩阵。 |
| [getName()](#getName--) | 获取表单名称。 |
| [getOpi()](#getOpi--) | 获取开放式印前接口 (OPI)。 |
| [getRectangle()](#getRectangle--) | 获取窗体的矩形。 |
| [getResources()](#getResources--) | 返回 Form X-Object 的资源。 |
| [getResources(boolean allowCreate)](#getResources-boolean-) | 返回 Form X-Object 的资源 |
| [getResources2()](#getResources2--) | 获取 Form XObject 资源。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBBox(Rectangle value)](#setBBox-com.aspose.pdf.Rectangle-) | 设置表单边界框。 |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | 设置表格的矩阵。 |
| [setName(String value)](#setName-java.lang.String-) | 设置表单名称。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsOwnResources() {#containsOwnResources--}
```
public boolean containsOwnResources()
```


如果包含自己的资源，则返回 True

**退货：**
boolean - 布尔值
### createNewForm(Page source, IDocument document) {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
```
public static XForm createNewForm(Page source, IDocument document)
```


创建复制页面内容的 XForm。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | [Page](../../com.aspose.pdf/page) | 源页面 |
| document | [IDocument](../../com.aspose.pdf/idocument) | 将添加新 XForm 的文档。 |

**退货：**
[XForm](../../com.aspose.pdf/xform) - 新创建的 XForm。
### createNewForm(Page source, ITrailerable trailerable, Copier copier) {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}
```
public static XForm createNewForm(Page source, ITrailerable trailerable, Copier copier)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | [Page](../../com.aspose.pdf/page) |  |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |
| copier | [Copier](../../com.aspose.pdf/copier) |  |

**退货：**
[XForm](../../com.aspose.pdf/xform)
### createNewForm(ITrailerable trailerable) {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
```
public static XForm createNewForm(ITrailerable trailerable)
```


在文档中创建新的 XForm。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | 描述 ITrailerable 对象 |

**退货：**
[XForm](../../com.aspose.pdf/xform) 新创建的 XForm
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


清除缓存数据

### getBBox() {#getBBox--}
```
public Rectangle getBBox()
```


获取表单边界框。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 长方形
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getContents() {#getContents--}
```
public OperatorCollection getContents()
```


获取窗体的运算符。

**退货：**
[OperatorCollection](../../com.aspose.pdf/operatorcollection) OperatorCollection 对象
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


仅限内部

**退货：**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) IPdfObject 对象
### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


获取表单的矩阵。

**退货：**
[Matrix](../../com.aspose.pdf/matrix) 矩阵
### getName() {#getName--}
```
public String getName()
```


获取表单名称。表单名称是在页面资源中XObejct ductionary中用来引用表单的名称。

**退货：**
java.lang.String - 字符串
### getOpi() {#getOpi--}
```
public Opi getOpi()
```


获取开放式印前接口 (OPI)。

**退货：**
[Opi](../../com.aspose.pdf/opi) Opi 实例
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取窗体的矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 长方形
### getResources() {#getResources--}
```
public Resources getResources()
```


返回 Form X-Object 的资源。如果 For 没有资源并且 allowCreate 为 true，则会自动为表单创建 Resources。

**退货：**
[Resources](../../com.aspose.pdf/resources) - 资源实例
### getResources(boolean allowCreate) {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```


返回 Form X-Object 的资源

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| allowCreate | boolean | 如果 For 没有资源并且 allowCreate 为 true，则会自动为表单创建 Resources。 |

**退货：**
[Resources](../../com.aspose.pdf/resources) - 资源实例
### getResources2() {#getResources2--}
```
public final Resources getResources2()
```


获取 Form XObject 资源。

**退货：**
[Resources](../../com.aspose.pdf/resources) - 资源实例。如果 For 没有资源，则会自动为表单创建 Resources。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBBox(Rectangle value) {#setBBox-com.aspose.pdf.Rectangle-}
```
public void setBBox(Rectangle value)
```


设置表单边界框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [长方形](../../com.aspose.pdf/rectangle) | Rectangle |

### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


设置表格的矩阵。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | 矩阵对象 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置表单名称。表单名称是页面资源中XObejct字典中用来引用表单的名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
