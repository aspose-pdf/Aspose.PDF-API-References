---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于编辑 PDF 文件页面的类，包括旋转页面、缩放页面、移动位置和更改页面尺寸。"
type: docs
weight: 570
url: /zh/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

表示用于编辑 PDF 文件页面的类，包括旋转页面、缩放页面、移动位置和更改页面尺寸。

## 字段

| 字段 | 描述 |
| --- | --- |
| [BLINDH](#BLINDH) | 垂直百叶窗 |
| [BLINDV](#BLINDV) | 垂直百叶窗 |
| [BTWIPE](#BTWIPE) | 自下至上擦除 |
| [DGLITTER](#DGLITTER) | 对角闪光 |
| [DISSOLVE](#DISSOLVE) | 旧页面溶解 |
| [INBOX](#INBOX) | 向内盒子 |
| [LRGLITTER](#LRGLITTER) | 左右闪光 |
| [LRWIPE](#LRWIPE) | 左右擦除 |
| [OUTBOX](#OUTBOX) | 向外盒子 |
| [RLWIPE](#RLWIPE) | 右至左擦除 |
| [SPLITHIN](#SPLITHIN) | 水平内部分割 |
| [SPLITHOUT](#SPLITHOUT) | 水平外部分割 |
| [SPLITVIN](#SPLITVIN) | 垂直内部分割 |
| [SPLITVOUT](#SPLITVOUT) | 垂直外部分割 |
| [TBGLITTER](#TBGLITTER) | 上下闪光 |
| [TBWIPE](#TBWIPE) | 上下擦除 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | PdfPageEditor 类的构造函数。 |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | PdfPageEditor 类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [applyChanges](#applyChanges--) | 应用对文档页面所做的更改。 |
| [getAlignment](#getAlignment--) | 获取原始 PDF 内容在结果页上的水平对齐方式，默认是 AlignmentType.Left。请改用 getHorizontalAlignment。 |
| [getDisplayDuration](#getDisplayDuration--) | 获取页面的显示时长。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 获取原始 PDF 内容在结果页上的水平对齐方式，默认是 AlignmentType.Left。 |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> 返回文档中指定框的大小。 </p> <hr> <pre> 以下示例演示如何获取第1页的 media 框：PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); Rectangle rect = editor.getBoxSize(1, \"media\"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | 返回页面的大小。 |
| [getPageRotation](#getPageRotation-int-) | <p> 返回指定页面的旋转角度。 </p> <hr> <pre> 以下示例演示如何获取页面旋转角度：PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); int rotation = editor.getPageSize(1); System.out.println(\"Rotation of 1st page : \" + rotation + \" degrees\"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> 获取页面的旋转角度，哈希表包含页面编号和旋转度数，键表示页面编号，键对应的值表示旋转的度数。 </p> |
| [getPages](#getPages--) | <p> 返回页面总数。 </p> <hr> <pre> 以下示例演示如何使用 GetPages() 方法：PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); System.out.println(\"Document has: \" + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | 获取输出文件的页面大小。 |
| [getPageSize](#getPageSize-int-) | <p> 返回指定页面的页面大小。 </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | 获取要编辑的页码。默认情况下，每页都会被编辑。 |
| [getRotation](#getRotation--) | 获取页面的旋转角度，旋转必须为 0、90、180 或 270。默认值为 0。 |
| [getTransitionDuration](#getTransitionDuration--) | 获取过渡效果的持续时间。 |
| [getTransitionType](#getTransitionType--) | 获取在演示过程中从另一页切换到此页时使用的过渡样式。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取原始 PDF 内容在结果页上的垂直对齐方式，默认是 VerticalAlignmentType.Bottom。请改用 getVerticalAlignmentType。 |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | 获取原始 PDF 内容在结果页上的垂直对齐方式，默认是 VerticalAlignmentType.Bottom。 |
| [getZoom](#getZoom--) | 获取缩放系数。值 1.0 对应 100%。默认值为 1.0。 |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | 检查页面上是否定义了该框。 |
| [movePosition](#movePosition-float-float-) | <p> 将原点从 (0, 0) 移动到指定的点。原点位于左下角，单位为点（1 英寸 = 72 点）。 </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> 将更改后的文档保存到流中。 </p> <hr> <pre> The following sample demonstrates how to save changed PDF document into stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> 将更改后的文档保存到文件中。 </p> <hr> <pre> The following sample demonstrates how to save changed PDF document PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | 设置原始 PDF 内容在结果页上的水平对齐方式，默认是 AlignmentType.Left。请改用 setHorizontalAlignment。 |
| [setDisplayDuration](#setDisplayDuration-int-) | 设置页面的显示持续时间。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置原始 PDF 内容在结果页上的水平对齐方式，默认是 AlignmentType.Left。 |
| [setPageRotations](#setPageRotations-java.util.Map-) | 设置页面的旋转角度，哈希表包含页码和旋转度数，键表示页码，键的值表示旋转的度数。 |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | 设置输出文件的页面大小。 |
| [setProcessPages](#setProcessPages-int:A-) | 设置要编辑的页码。默认情况下，每页都会被编辑。 |
| [setRotation](#setRotation-int-) | 设置页面的旋转角度，旋转必须为 0、90、180 或 270。默认值为 0。 |
| [setTransitionDuration](#setTransitionDuration-int-) | 设置过渡效果的持续时间。 |
| [setTransitionType](#setTransitionType-int-) | 设置在演示过程中从另一页切换到此页时使用的过渡样式。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | 设置原始 PDF 内容在结果页上的垂直对齐方式，默认是 VerticalAlignmentType.Bottom。请改用 setVerticalAlignmentType。 |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | 设置原始 PDF 内容在结果页上的垂直对齐方式，默认是 VerticalAlignmentType.Bottom。 |
| [setZoom](#setZoom-float-) | <p> 设置缩放系数。值 1.0 对应 100%。默认值为 1.0。 </p> |

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

自下至上擦除

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

向内盒子

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

向外盒子

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

右至左擦除

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

水平内部分割

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

水平外部分割

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

垂直内部分割

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

垂直外部分割

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

上下闪光

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

上下擦除

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

PdfPageEditor 类的构造函数。

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
PdfPageEditor 类的构造函数。

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

应用对文档页面所做的更改。

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

获取原始 PDF 内容在结果页上的水平对齐方式，默认是 AlignmentType.Left。请改用 getHorizontalAlignment。

**Returns:**
AlignmentType 对象 @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

获取页面的显示时长。

**Returns:**
int 值

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

获取原始 PDF 内容在结果页上的水平对齐方式，默认是 AlignmentType.Left。

**Returns:**
HorizontalAlignment 元素 @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> 返回文档中指定框的大小。 </p> <hr> <pre> 以下示例演示如何获取第1页的 media 框：PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); Rectangle rect = editor.getBoxSize(1, \"media\"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
返回页面的大小。

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> 返回指定页面的旋转角度。 </p> <hr> <pre> 以下示例演示如何获取页面旋转角度：PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); int rotation = editor.getPageSize(1); System.out.println(\"Rotation of 1st page : \" + rotation + \" degrees\"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 |  | 页面索引。文档页面从 1 开始编号。 |

**Returns:**
页面旋转（度）。

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> 获取页面的旋转角度，哈希表包含页面编号和旋转度数，键表示页面编号，键对应的值表示旋转的度数。 </p>

**Returns:**
{@code Map<Integer, Integer>} 对象

### getPages {#getPages--}
```
public int getPages()
```

<p> 返回页面总数。 </p> <hr> <pre> 以下示例演示如何使用 GetPages() 方法：PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); System.out.println(\"Document has: \" + editor.GetPages()); </pre>

**Returns:**
页面数量。

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

获取输出文件的页面大小。

**Returns:**
PageSize 对象

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> 返回指定页面的页面大小。 </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 |  | 页面索引。文档页面从 1 开始编号。 |

**Returns:**
Result 是 PageSize 的实例。使用返回对象的 Width 和 Height 属性来获取页面宽度和高度。

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

获取要编辑的页码。默认情况下，每页都会被编辑。

**Returns:**
int 值数组

### getRotation {#getRotation--}
```
public int getRotation()
```

获取页面的旋转角度，旋转必须为 0、90、180 或 270。默认值为 0。

**Returns:**
int 值

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

获取过渡效果的持续时间。

**Returns:**
int 值

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

获取在演示过程中从另一页切换到此页时使用的过渡样式。

**Returns:**
int 值

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

获取原始 PDF 内容在结果页上的垂直对齐方式，默认是 VerticalAlignmentType.Bottom。请改用 getVerticalAlignmentType。

**Returns:**
VerticalAlignmentType 对象

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

获取原始 PDF 内容在结果页上的垂直对齐方式，默认是 VerticalAlignmentType.Bottom。

**Returns:**
VerticalAlignmentType 元素 @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

获取缩放系数。值 1.0 对应 100%。默认值为 1.0。

**Returns:**
float 值

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
检查页面上是否定义了该框。

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> 将原点从 (0, 0) 移动到指定的点。原点位于左下角，单位为点（1 英寸 = 72 点）。 </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| moveX |  | X 坐标。 |
| moveY |  | Y 坐标。 |

### save {#save-java.io.OutputStream-}
<p> 将更改后的文档保存到流中。 </p> <hr> <pre> The following sample demonstrates how to save changed PDF document into stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> 将更改后的文档保存到文件中。 </p> <hr> <pre> The following sample demonstrates how to save changed PDF document PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
设置原始 PDF 内容在结果页上的水平对齐方式，默认是 AlignmentType.Left。请改用 setHorizontalAlignment。

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

设置页面的显示持续时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
设置原始 PDF 内容在结果页上的水平对齐方式，默认是 AlignmentType.Left。

### setPageRotations {#setPageRotations-java.util.Map-}
设置页面的旋转角度，哈希表包含页码和旋转度数，键表示页码，键的值表示旋转的度数。

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
设置输出文件的页面大小。

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

设置要编辑的页码。默认情况下，每页都会被编辑。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值数组 |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

设置页面的旋转角度，旋转必须为 0、90、180 或 270。默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

设置过渡效果的持续时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

设置在演示过程中从另一页切换到此页时使用的过渡样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
设置原始 PDF 内容在结果页上的垂直对齐方式，默认是 VerticalAlignmentType.Bottom。请改用 setVerticalAlignmentType。

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
设置原始 PDF 内容在结果页上的垂直对齐方式，默认是 VerticalAlignmentType.Bottom。

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> 设置缩放系数。值 1.0 对应 100%。默认值为 1.0。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 <hr> <pre> The following example demonstrates how to change zoom of the document pages. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); </pre> |
