---
title: PdfPageEditor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示一个类来编辑PDF文件页面，包括旋转页面缩放页面移动位置和改变页面大小。
type: docs
weight: 49
url: /zh/java/com.aspose.pdf.facades/pdfpageeditor/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfPageEditor extends SaveableFacade
```

表示一个类来编辑PDF文件的页面，包括旋转页面、缩放页面、移动位置和改变页面大小。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfPageEditor()](#PdfPageEditor--) | PdfPageEditor 类的构造函数。 |
| [PdfPageEditor(Document document)](#PdfPageEditor-com.aspose.pdf.Document-) | PdfPageEditor 类的构造函数。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [BLINDH](#BLINDH) | 垂直百叶窗 |
| [BLINDV](#BLINDV) | 垂直百叶窗 |
| [BTWIPE](#BTWIPE) | 自下而上擦除 |
| [DGLITTER](#DGLITTER) | 对角闪光 |
| [DISSOLVE](#DISSOLVE) | 旧页面溶解 |
| [INBOX](#INBOX) | 内盒 |
| [LRGLITTER](#LRGLITTER) | 左右闪光 |
| [LRWIPE](#LRWIPE) | 左右擦除 |
| [OUTBOX](#OUTBOX) | 外箱 |
| [RLWIPE](#RLWIPE) | 左右擦除 |
| [SPLITHIN](#SPLITHIN) | IN水平分割 |
| [SPLITHOUT](#SPLITHOUT) | 出水平分割 |
| [SPLITVIN](#SPLITVIN) | 在垂直分割 |
| [SPLITVOUT](#SPLITVOUT) | 出垂直分割 |
| [TBGLITTER](#TBGLITTER) | 上下闪光 |
| [TBWIPE](#TBWIPE) | 上下擦拭 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [applyChanges()](#applyChanges--) | 应用对文档页面所做的更改。 |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 处理与外观绑定的文档。 |
| [dispose()](#dispose--) | 处理门面。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 获取原始PDF内容在结果页面的水平对齐方式，默认为AlignmentType.Left。 |
| [getClass()](#getClass--) |  |
| [getDisplayDuration()](#getDisplayDuration--) | 获取页面的显示持续时间。 |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取原始PDF内容在结果页面的水平对齐方式，默认为AlignmentType.Left。 |
| [getPageBoxSize(int page, String pageBoxName)](#getPageBoxSize-int-java.lang.String-) | 返回文档中指定框的大小。 |
| [getPageRotation(int page)](#getPageRotation-int-) | 返回指定页面的旋转。 |
| [getPageRotations()](#getPageRotations--) | 获取页面的旋转，一个哈希表包含页码和旋转度数，key代表页码，key的值代表旋转度数。 |
| [getPageSize()](#getPageSize--) | 获取输出文件的页面大小。 |
| [getPageSize(int page)](#getPageSize-int-) | 返回指定页面的页面大小。 |
| [getPages()](#getPages--) | 返回总页数。 |
| [getProcessPages()](#getProcessPages--) | 获取要编辑的页码。 |
| [getRotation()](#getRotation--) | 获取页面的旋转角度，旋转角度必须为 0、90、180 或 270。 |
| [getTransitionDuration()](#getTransitionDuration--) | 获取过渡效果的持续时间。 |
| [getTransitionType()](#getTransitionType--) | 获取在演示过程中从另一个页面移至此页面时要使用的过渡样式。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取原始PDF内容在结果页面的垂直对齐方式，默认为VerticalAlignmentType.Bottom。 |
| [getVerticalAlignmentType()](#getVerticalAlignmentType--) | 获取原始PDF内容在结果页面的垂直对齐方式，默认为VerticalAlignmentType.Bottom。 |
| [getZoom()](#getZoom--) | 获取缩放系数。 |
| [hashCode()](#hashCode--) |  |
| [movePosition(float moveX, float moveY)](#movePosition-float-float-) | 将原点从 (0, 0) 移动到指定的点。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | 将更改的文档保存到流中。 |
| [save(String outputFile)](#save-java.lang.String-) | 将更改的文档保存到文件中。 |
| [setAlignment(AlignmentType value)](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | 设置原始 PDF 内容在结果页面上的水平对齐方式，默认为 AlignmentType.Left。 |
| [setDisplayDuration(int value)](#setDisplayDuration-int-) | 设置页面的显示持续时间。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置原始 PDF 内容在结果页面上的水平对齐方式，默认为 AlignmentType.Left。 |
| [setPageRotations(Map<Integer,Integer> value)](#setPageRotations-java.util.Map-java.lang.Integer-java.lang.Integer--) | 设置页面的旋转，一个哈希表包含页码和旋转度数，key代表页码，key的值代表旋转度数。 |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.pdf.PageSize-) | 设置输出文件的页面大小。 |
| [setProcessPages(int[] value)](#setProcessPages-int---) | 设置要编辑的页码。 |
| [setRotation(int value)](#setRotation-int-) | 设置页面的旋转角度，旋转角度必须为 0、90、180 或 270。 |
| [setTransitionDuration(int value)](#setTransitionDuration-int-) | 设置过渡效果的持续时间。 |
| [setTransitionType(int value)](#setTransitionType-int-) | 设置在演示期间从另一个页面移动到此页面时要使用的过渡样式。 |
| [setVerticalAlignment(VerticalAlignmentType value)](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | 设置原始 PDF 内容在结果页面上的垂直对齐方式，默认为 VerticalAlignmentType.Bottom。 |
| [setVerticalAlignmentType(int value)](#setVerticalAlignmentType-int-) | 设置原始 PDF 内容在结果页面上的垂直对齐方式，默认为 VerticalAlignmentType.Bottom。 |
| [setZoom(float value)](#setZoom-float-) | 设置缩放系数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfPageEditor() {#PdfPageEditor--}
```
public PdfPageEditor()
```


PdfPageEditor 类的构造函数。

### PdfPageEditor(Document document) {#PdfPageEditor-com.aspose.pdf.Document-}
```
public PdfPageEditor(Document document)
```


PdfPageEditor 类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | 应处理的文档对象。 |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```


垂直百叶窗

### BLINDV {#BLINDV}
```
public static final int BLINDV
```


垂直百叶窗

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```


自下而上擦除

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```


对角闪光

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```


旧页面溶解

### INBOX {#INBOX}
```
public static final int INBOX
```


内盒

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```


左右闪光

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```


左右擦除

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```


外箱

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```


左右擦除

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```


IN水平分割

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```


出水平分割

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```


在垂直分割

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```


出垂直分割

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```


上下闪光

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```


上下擦拭

### applyChanges() {#applyChanges--}
```
public void applyChanges()
```


应用对文档页面所做的更改。

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### close() {#close--}
```
public void close()
```


处理与外观绑定的文档。

### dispose() {#dispose--}
```
public void dispose()
```


处理门面。

此方法已过时，请改用 close() 。

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
### getAlignment() {#getAlignment--}
```
public AlignmentType getAlignment()
```


获取原始PDF内容在结果页面的水平对齐方式，默认为AlignmentType.Left。
改为使用 getHorizontalAlignment

**退货：**
[AlignmentType](../../com.aspose.pdf.facades/alignmenttype) - AlignmentType 对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDisplayDuration() {#getDisplayDuration--}
```
public int getDisplayDuration()
```


获取页面的显示持续时间。

**退货：**
int - 整数值
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取原始PDF内容在结果页面的水平对齐方式，默认为AlignmentType.Left。

**退货：**
int - HorizontalAlignment 元素
### getPageBoxSize(int page, String pageBoxName) {#getPageBoxSize-int-java.lang.String-}
```
public Rectangle getPageBoxSize(int page, String pageBoxName)
```


返回文档中指定框的大小。

--------------------

```
The following example demonstrates how to get media box of the 1st page:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 Rectangle rect = editor.getBoxSize(1, "media");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 页面索引。文档页面从 1 开始编号。 |
| pageBoxName | java.lang.String | 框类型名称。有效值为：“art”、“bleed”、“crop”、“media”、“trim”。 |

**退货：**
[Rectangle](../../java.awt/rectangle) - 包含请求框的矩形。
### getPageRotation(int page) {#getPageRotation-int-}
```
public int getPageRotation(int page)
```


返回指定页面的旋转。

--------------------

```
The following example demonstrates how to get page rotation:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 int rotation = editor.getPageSize(1);
 System.out.println("Rotation of 1st page : " + rotation + " degrees");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 页面索引。文档页面从 1 开始编号。 |

**退货：**
int - 页面旋转度数。
### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Integer> getPageRotations()
```


获取页面的旋转，一个哈希表包含页码和旋转度数，key代表页码，key的值代表旋转度数。

**退货：**
java.util.Map<java.lang.Integer,java.lang.Integer> - 地图对象
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


获取输出文件的页面大小。

**退货：**
[PageSize](../../com.aspose.pdf/pagesize) - PageSize 对象
### getPageSize(int page) {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```


返回指定页面的页面大小。

--------------------

```
The following example demonstrates using of GetPageSize method:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 PageSize size = editor.getPageSize(1);
 System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight());
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 页面索引。文档页面从 1 开始编号。 |

**退货：**
[PageSize](../../com.aspose.pdf/pagesize) 结果是 PageSize 的实例。使用返回对象的宽度和高度属性获取页面宽度和高度。
### getPages() {#getPages--}
```
public int getPages()
```


返回总页数。

--------------------

```
The following example demonstrates using of GetPages() method:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 System.out.println("Document has: " + editor.GetPages());
```

**退货：**
int - 页数。
### getProcessPages() {#getProcessPages--}
```
public int[] getProcessPages()
```


获取要编辑的页码。默认情况下，每个页面都会被编辑。

**退货：**
整数[] - 整数值数组
### getRotation() {#getRotation--}
```
public int getRotation()
```


获取页面的旋转角度，旋转角度必须为 0、90、180 或 270。默认值为 0。

**退货：**
int - 整数值
### getTransitionDuration() {#getTransitionDuration--}
```
public int getTransitionDuration()
```


获取过渡效果的持续时间。

**退货：**
int - 整数值
### getTransitionType() {#getTransitionType--}
```
public int getTransitionType()
```


获取在演示过程中从另一个页面移至此页面时要使用的过渡样式。

**退货：**
int - 整数值
### getVerticalAlignment() {#getVerticalAlignment--}
```
public VerticalAlignmentType getVerticalAlignment()
```


获取原始PDF内容在结果页面的垂直对齐方式，默认为VerticalAlignmentType.Bottom。
改为使用 getVerticalAlignmentType

**退货：**
[VerticalAlignmentType](../../com.aspose.pdf.facades/verticalalignmenttype) - VerticalAlignmentType 对象
### getVerticalAlignmentType() {#getVerticalAlignmentType--}
```
public int getVerticalAlignmentType()
```


获取原始PDF内容在结果页面的垂直对齐方式，默认为VerticalAlignmentType.Bottom。

**退货：**
int - VerticalAlignmentType 元素
### getZoom() {#getZoom--}
```
public float getZoom()
```


获取缩放系数。值 1.0 对应于 100%。默认值为 1.0。

**退货：**
float - 浮点值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### movePosition(float moveX, float moveY) {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```


将原点从 (0, 0) 移动到指定的点。原点在左下角，单位为点（1 英寸 = 72 点）。

--------------------

```
PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("input.pdf");
 editor.movePosition(-100, 60);
 editor.save("moved.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| moveX | float | X 坐标。 |
| moveY | float | Y 坐标。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


将更改的文档保存到流中。

--------------------

```
The following sample demonstrates how to save changed PDF document into stream.


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 editor.setZoom ( 0.5f);
 editor.save("newdocument.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 将保存更改的 PDF 文档的流。 |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


将更改的文档保存到文件中。

--------------------

```
The following sample demonstrates how to save changed PDF document


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 editor.setZoom ( 0.5f);
 editor.save("newdocument.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存文档的文件路径。 |

### setAlignment(AlignmentType value) {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
```
public void setAlignment(AlignmentType value)
```


设置原始 PDF 内容在结果页面上的水平对齐方式，默认为 AlignmentType.Left。
改为使用 setHorizontalAlignment

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [AlignmentType](../../com.aspose.pdf.facades/alignmenttype) | AlignmentType 值 |

### setDisplayDuration(int value) {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```


设置页面的显示持续时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置原始 PDF 内容在结果页面上的水平对齐方式，默认为 AlignmentType.Left。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPageRotations(Map<Integer,Integer> value) {#setPageRotations-java.util.Map-java.lang.Integer-java.lang.Integer--}
```
public void setPageRotations(Map<Integer,Integer> value)
```


设置页面的旋转，一个哈希表包含页码和旋转度数，key代表页码，key的值代表旋转度数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Map<java.lang.Integer,java.lang.Integer> |  地图对象 |

### setPageSize(PageSize value) {#setPageSize-com.aspose.pdf.PageSize-}
```
public void setPageSize(PageSize value)
```


设置输出文件的页面大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.pdf/pagesize) | PageSize 对象 |

### setProcessPages(int[] value) {#setProcessPages-int---}
```
public void setProcessPages(int[] value)
```


设置要编辑的页码。默认情况下，每个页面都会被编辑。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] | 整数值数组 |

### setRotation(int value) {#setRotation-int-}
```
public void setRotation(int value)
```


设置页面的旋转角度，旋转角度必须为 0、90、180 或 270。默认值为 0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setTransitionDuration(int value) {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```


设置过渡效果的持续时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setTransitionType(int value) {#setTransitionType-int-}
```
public void setTransitionType(int value)
```


设置在演示期间从另一个页面移动到此页面时要使用的过渡样式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setVerticalAlignment(VerticalAlignmentType value) {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
```
public void setVerticalAlignment(VerticalAlignmentType value)
```


设置原始 PDF 内容在结果页面上的垂直对齐方式，默认为 VerticalAlignmentType.Bottom。
改为使用 setVerticalAlignmentType

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [VerticalAlignmentType](../../com.aspose.pdf.facades/verticalalignmenttype) | VerticalAlignmentType 值 |

### setVerticalAlignmentType(int value) {#setVerticalAlignmentType-int-}
```
public void setVerticalAlignmentType(int value)
```


设置原始 PDF 内容在结果页面上的垂直对齐方式，默认为 VerticalAlignmentType.Bottom。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

### setZoom(float value) {#setZoom-float-}
```
public void setZoom(float value)
```


设置缩放系数。值 1.0 对应于 100%。默认值为 1.0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值

--------------------

```
The following example demonstrates how to change zoom of the document pages.


                 PdfPageEditor editor = new PdfPageEditor();
                 editor.bindPdf("sample.pdf");
                 editor.setZoom ( 0.5f);
``` |

### toString() {#toString--}
```
公共字符串 toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
公共最终无效等待（）
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
公共最终无效等待（长 arg0，int arg1）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
