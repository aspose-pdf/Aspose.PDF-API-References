---
title: "Page"
linktitle: "Page"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档页面的类。"
type: docs
weight: 3310
url: /zh/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

表示 PDF 文档页面的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受 {@code AnnotationSelector} 访问者对象，该对象提供处理注释的功能。 |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | 接受 {@code ImagePlacementAbsorber} 访问者对象，该对象提供处理图像放置对象的功能。 |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | 接受 {@code TextAbsorber} 访问者对象，该对象提供处理文本对象的功能。 |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | 接受 {@code TextFragmentAbsorber} 访问者对象，该对象提供处理文本对象的功能。 |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | 向页面添加图形。比逐个使用 GraphicElement#addOnPage(Page) 方法添加元素更快。 |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | 向页面添加图形。比逐个使用 GraphicElement#addOnPage(Page) 方法添加元素更快。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | 将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | 在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | 在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | 将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | 将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。 |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | 将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。 |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | 在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | 在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | 将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。 |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | 将印章放入页面。印章可以是页码、图像或简单文本，例如某个徽标。 |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | 将当前页面转换为 BMP 位图，然后返回字节数组。 |
| [asXml](#asXml--) | 将当前页面转换为 UTF-8 编码的 XML。 |
| [calculateContentBBox](#calculateContentBBox--) | 计算 bbox 值——包含内容且没有可见边距的矩形。 |
| [clearContents](#clearContents--) | 仅供内部使用 |
| [close](#close--) | 关闭此文档使用的所有资源。 |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | 将页面转换为 PNG，以用于 DSR、OMR、OCR 图像流。 |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | 从页面删除图形。比使用 {@link GraphicElement#remove} 方法逐个删除元素更快。 |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | 释放内存。此方法已过时，请改用 close()。 |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | 返回使用具有指定名称资源的操作符列表。 |
| [findReferences](#findReferences-java.lang.String-) | <p> 查找引用 </p> |
| [flatten](#flatten--) | 删除页面上所有静态字段，并将其值放置在原处。 |
| [freeMemory](#freeMemory--) | 清除缓存数据 |
| [getActions](#getActions--) | 获取页面属性的集合。 |
| [getAnnotations](#getAnnotations--) | 获取页面注释的集合。 {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> 获取页面的艺术框。 </p> |
| [getArtifacts](#getArtifacts--) | 获取页面上伪影的集合。 |
| [getBackground](#getBackground--) | 获取页面的背景颜色。 |
| [getBackgroundImage](#getBackgroundImage--) | 获取或设置页面的背景图像（仅用于生成器，读取文档时不填充）。 |
| [getBleedBox](#getBleedBox--) | <p> 获取页面的出血框。 </p> |
| [getColorType](#getColorType--) | 根据从 SetColor 操作符、图像和表单获取的信息，获取页面的颜色类型。 |
| [getContents](#getContents--) | <p> 获取页面内容流中操作符的集合。 {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | 获取当前内容追加器。 {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> 获取页面的裁剪框。 </p> |
| [getDocument](#getDocument--) | 获取文档 |
| [getDuration](#getDuration--) | <p> 获取页面显示持续时间。该时间以秒为单位，表示页面在演示期间应显示的时长。如果未定义持续时间，则返回 -1。 </p> <hr> 示例演示如何获取页面持续时间 <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | 仅供内部使用 |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | 获取此页面上按 Tab 顺序排列的 Field 对象列表。 |
| [getFooter](#getFooter--) | 获取页面页脚。 |
| [getGroup](#getGroup--) | 获取一个组属性类，指定页面的页面组属性，以在透明成像模型中使用。 |
| [getHeader](#getHeader--) | 获取页面页眉。 |
| [getLayers](#getLayers--) | 获取图层集合。 |
| [getMediaBox](#getMediaBox--) | <p> 获取页面的媒体框。 </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | 获取注释的线条样式。（仅用于生成器，读取文档时不填充） |
| [getNotifications](#getNotifications--) | 返回有关页面内容内部操作的通知。（目前仅支持文本添加场景中的段落事件通知） |
| [getNumber](#getNumber--) | 获取页面编号。 |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | 用于自定义页眉和页脚的事件。 |
| [getPageInfo](#getPageInfo--) | 获取页面信息。（仅用于生成器，读取文档时不填充） |
| [getPageRect](#getPageRect-boolean-) | 根据页面的 CropBox（如果 CropBox 为 null，则使用 MediaBox）返回页面矩形。 |
| [getParagraphs](#getParagraphs--) | 获取段落。 |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> 根据页面的 CropBox 和 MediaBox 返回页面矩形； </p> Internal |
| [getRect](#getRect--) | <p> 根据页面的 CropBox 和 MediaBox 返回页面矩形；获取时：如果指定则返回页面 CropBox，否则返回页面 MediaBox。设置时：始终设置页面 MediaBox。 </p> |
| [getResources](#getResources--) | 检索与页面关联的资源。 |
| [getResourcesField](#getResourcesField--) | <p> 获取页面资源。Resources 对象包含图像、表单和字体的集合。{@code Resources} </p> |
| [getRotate](#getRotate--) | <p> 获取页面的旋转角度。 </p> |
| [getRotationMatrix](#getRotationMatrix--) | 获取页面的变换矩阵。 |
| [getTabOrder](#getTabOrder--) | 获取页面的制表顺序。可能的值：Row、Column。默认，手动 |
| [getTocInfo](#getTocInfo--) | 获取目录信息。 |
| [getTrimBox](#getTrimBox--) | <p> 获取页面的裁剪框。 </p> |
| [getUserUnit](#getUserUnit--) | 获取或设置 UserUnit 值。正数表示默认用户空间单位的大小，以 1/72 英寸的倍数计。默认值为 1。请设置为零或负数以清除页面中的此条目。 |
| [getWatermark](#getWatermark--) | 获取页面的水印。 |
| [hasVectorGraphics](#hasVectorGraphics--) | 检测页面上是否存在矢量图形。 |
| [intToRotation](#intToRotation-int-) | 将整数值转换为相应的旋转枚举成员。 |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | 获取或设置在页面最后一个段落之后添加段落的选项。值：指示是否在页面最后一个段落之后添加段落。如果值为 true，则会在页面最后一个段落之后添加段落。 |
| [isBlank](#isBlank-double-) | 获取页面是否为空的标志。 |
| [isBlank](#isBlank-double-boolean-) | 获取页面是否为空的标志。 |
| [makeGrayscale](#makeGrayscale--) | 将页面转换为灰度。 |
| [mergeLayers](#mergeLayers-java.lang.String-) | 将页面上的所有图层合并为一个图层，使用指定的新图层名称。 |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | 将页面上的所有图层合并为一个图层，使用指定的新图层名称和可选的内容组 Id。 |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | 移除对象引用 |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | 从页面内容中移除对 XObject 的引用（即所有使用对象名称的 Do 操作符）。 |
| [resize](#resize-com.aspose.pdf.PageSize-) | 调整页面大小。 |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | 将旋转枚举成员转换为整数值。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | 使用给定的页面设备发送页面进行处理。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | 使用给定的页面设备发送页面进行处理。 |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | 获取或设置在页面最后一个段落之后添加段落的选项。值：指示是否在页面最后一个段落之后添加段落。如果值为 true，则会在页面最后一个段落之后添加段落。 |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | 设置页面的艺术框。 |
| [setBackground](#setBackground-java.awt.Color-) | 设置页面的背景颜色。 |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | 设置页面的背景颜色。 |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | 获取或设置页面的背景图像（仅用于生成器，读取文档时不填充）。 |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | 设置页面的出血框。 |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> 设置页面的裁剪框。 </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | 设置页面显示持续时间。这是页面在演示期间显示的秒数。如果未定义持续时间，则返回 -1。 |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | 仅供内部使用 |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | 设置页面页脚。 |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | 设置一个组属性类，指定页面组的属性，以用于透明成像模型。 |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | 设置页面页眉。 |
| [setLayers](#setLayers-java.util.ArrayList-) | 设置图层集合。 |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | 设置图层集合。 |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | 设置页面的媒体框。 |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | 设置注释的线条样式。（仅用于生成器，读取文档时不填充） |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置页面信息。（仅用于生成器，读取文档时不填充）。 |
| [setPageSize](#setPageSize-double-double-) | 为页面设置大小。 |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | 设置段落。 |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | 获取或设置页面的矩形。获取时：如果指定，则返回页面裁剪框，否则返回页面媒体框。设置时：始终设置页面媒体框并返回。请注意，此属性不考虑页面旋转。若要获取考虑旋转的页面矩形，请使用 ActualRect。 |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | 设置页面的旋转。 |
| [setTabOrder](#setTabOrder-int-) | 设置页面的标签顺序。可能的值：Row，Column。默认，Manual。 |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | 设置目录信息。 |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | 设置过渡 |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | 设置页面的裁剪框。 |
| [setUserUnit](#setUserUnit-double-) | 获取或设置 UserUnit 值。正数表示默认用户空间单位的大小，以 1/72 英寸的倍数计。默认值为 1。请设置为零或负数以清除页面中的此条目。 |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | 设置页面的水印。 |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | 尝试保存页面上存在的矢量图形。保存格式为 SVG。 |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受 {@code AnnotationSelector} 访问者对象，该对象提供处理注释的功能。

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
接受 {@code ImagePlacementAbsorber} 访问者对象，该对象提供处理图像放置对象的功能。

### accept {#accept-com.aspose.pdf.TextAbsorber-}
接受 {@code TextAbsorber} 访问者对象，该对象提供处理文本对象的功能。

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
接受 {@code TextFragmentAbsorber} 访问者对象，该对象提供处理文本对象的功能。

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
向页面添加图形。比逐个使用 GraphicElement#addOnPage(Page) 方法添加元素更快。

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
向页面添加图形。比逐个使用 GraphicElement#addOnPage(Page) 方法添加元素更快。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
将图像添加到页面，并将其定位在指定矩形的中间，保持图像的比例。

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
将印章放入页面。印章可以是页码、图像或简单文本，例如某个徽标。

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
将当前页面转换为 BMP 位图，然后返回字节数组。

### asXml {#asXml--}
```
public String asXml()
```

将当前页面转换为 UTF-8 编码的 XML。

**Returns:**
已转换的 XML 字符串。

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

计算 bbox 值——包含内容且没有可见边距的矩形。

**Returns:**
Bbbox 值 - 包含内容且没有可见边距的矩形

### clearContents {#clearContents--}
```
public void clearContents()
```

仅供内部使用

### close {#close--}
```
public void close()
```

关闭此文档使用的所有资源。

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

将页面转换为 PNG，以用于 DSR、OMR、OCR 图像流。

**Returns:**
以 byte[] 数组形式的图像流。

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
从页面删除图形。比使用 {@link GraphicElement#remove} 方法逐个删除元素更快。

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

释放内存。此方法已过时，请改用 close()。

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
返回使用具有指定名称资源的操作符列表。

### findReferences {#findReferences-java.lang.String-}
<p> 查找引用 </p>

### flatten {#flatten--}
```
public void flatten()
```

删除页面上所有静态字段，并将其值放置在原处。

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

清除缓存数据

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

获取页面属性的集合。

**Returns:**
PageActionCollection 值

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

获取页面注释的集合。 {@code Annotations}

**Returns:**
AnnotationCollection 值

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> 获取页面的艺术框。 </p>

**Returns:**
矩形值 <hr> <pre> 示例演示如何获取页面的 art box: Document document = new Document("sample.pdf"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

获取页面上伪影的集合。

**Returns:**
ArtifactCollection 值

### getBackground {#getBackground--}
```
public Color getBackground()
```

获取页面的背景颜色。

**Returns:**
颜色值

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

获取或设置页面的背景图像（仅用于生成器，读取文档时不填充）。

**Returns:**
图像实例

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> 获取页面的出血框。 </p>

**Returns:**
矩形值 <hr> <pre> 示例演示如何获取页面的 bleed box: Document document = new Document("sample.pdf"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

根据从 SetColor 操作符、图像和表单获取的信息，获取页面的颜色类型。

**Returns:**
ColorType 元素 @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> 获取页面内容流中操作符的集合。 {@code OperatorCollection} </p>

**Returns:**
OperatorCollection 对象 <hr> <pre> 示例演示如何扫描页面的 operators 流: Document document = new Document("sample.pdf"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

获取当前内容追加器。 {@code ContentsAppender}

**Returns:**
ContentsAppender 值

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> 获取页面的裁剪框。 </p>

**Returns:**
矩形值 <hr> <pre> 示例演示如何获取页面的 crop box: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

获取文档

**Returns:**
IDocument 对象

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> 获取页面显示持续时间。该时间以秒为单位，表示页面在演示期间应显示的时长。如果未定义持续时间，则返回 -1。 </p> <hr> 示例演示如何获取页面持续时间 <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
double 值

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

仅供内部使用

**Returns:**
内部实例

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

获取此页面上按 Tab 顺序排列的 Field 对象列表。

**Returns:**
字段对象列表

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

获取页面页脚。

**Returns:**
页面页脚。

### getGroup {#getGroup--}
```
public Group getGroup()
```

获取一个组属性类，指定页面的页面组属性，以在透明成像模型中使用。

**Returns:**
组值

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

获取页面页眉。

**Returns:**
页面页眉。

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

获取图层集合。

**Returns:**
值：图层集合。

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> 获取页面的媒体框。 </p>

**Returns:**
矩形值 <hr> <pre> 示例演示如何获取页面的 media box: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

获取注释的线条样式。（仅用于生成器，读取文档时不填充）

**Returns:**
GraphInfo 值

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

返回有关页面内容内部操作的通知。（目前仅支持文本添加场景中的段落事件通知）

**Returns:**
表示页面内容内部操作通知的字符串。

### getNumber {#getNumber--}
```
public final int getNumber()
```

获取页面编号。

**Returns:**
int 值

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

用于自定义页眉和页脚的事件。

**Returns:**
{@code PdfEvent<BeforePageGenerate> instance}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

获取页面信息。（仅用于生成器，读取文档时不填充）

**Returns:**
页面信息。

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

根据页面的 CropBox（如果 CropBox 为 null，则使用 MediaBox）返回页面矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| considerRotation |  | 如果为 true，则在矩形计算时会考虑页面的旋转。 |

**Returns:**
页面的矩形。

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

获取段落。

**Returns:**
段落。

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> 根据页面的 CropBox 和 MediaBox 返回页面矩形； </p> Internal

**Returns:**
矩形值 <hr> <pre> Example demonstrates how to get page rectangle: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> 根据页面的 CropBox 和 MediaBox 返回页面矩形；获取时：如果指定则返回页面 CropBox，否则返回页面 MediaBox。设置时：始终设置页面 MediaBox。 </p>

**Returns:**
矩形值 <hr> <pre> Example demonstrates how to get page rectangle: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

检索与页面关联的资源。

**Returns:**
一个 {@code Resources}({@link #getResources()}) 对象，表示页面的资源。

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> 获取页面资源。Resources 对象包含图像、表单和字体的集合。{@code Resources} </p>

**Returns:**
资源值 <hr> <pre> Example demonstrates scan through page images: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> 获取页面的旋转角度。 </p>

**Returns:**
旋转元素 <hr> <pre> Example demonstrates how to determine page rotation. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

获取页面的变换矩阵。

**Returns:**
矩阵值

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

获取页面的制表顺序。可能的值：Row、Column。默认，手动

**Returns:**
TabOrder 值 @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

获取目录信息。

**Returns:**
目录信息 - 默认为 null。如果设置，则此页面将包含目录。

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> 获取页面的裁剪框。 </p>

**Returns:**
矩形值 <hr> <pre> Example demonstrates how to get trim box of the page: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

获取或设置 UserUnit 值。正数表示默认用户空间单位的大小，以 1/72 英寸的倍数计。默认值为 1。请设置为零或负数以清除页面中的此条目。

**Returns:**
double 值

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

获取页面的水印。

**Returns:**
水印值

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

检测页面上是否存在矢量图形。

**Returns:**
如果页面包含路径构造操作符，则为 True；否则为 False。

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

将整数值转换为相应的旋转枚举成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 旋转 |  | 要转换的整数值 |

**Returns:**
Rotation 枚举成员 @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

获取或设置在页面最后一个段落之后添加段落的选项。值：指示是否在页面最后一个段落之后添加段落。如果值为 true，则会在页面最后一个段落之后添加段落。

**Returns:**
布尔值

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

获取页面是否为空的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillThresholdFactor |  | 管理检测灵敏度的填充阈值。应在范围 [0..1) 内。为了确定页面是否为空，会计算已填充空间与页面总空间的比例。将该比例与 fillThresholdFactor 参数进行比较，如果小于该值，则页面被视为空。 |

**Returns:**
布尔值 True - 如果页面为空；否则为 false。

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

获取页面是否为空的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillThresholdFactor |  | 管理检测灵敏度的填充阈值。应大于或等于 0.01。 |
| parseWhiteContent |  | True 表示进行完整的页面扫描并分析白色内容，False（默认）表示使用快速算法，其中白色图形被视为非空白页面。 |

**Returns:**
布尔值 True - 如果页面为空；否则为 false。

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

将页面转换为灰度。

### mergeLayers {#mergeLayers-java.lang.String-}
将页面上的所有图层合并为一个图层，使用指定的新图层名称。

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
将页面上的所有图层合并为一个图层，使用指定的新图层名称和可选的内容组 Id。

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
移除对象引用

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
从页面内容中移除对 XObject 的引用（即所有使用对象名称的 Do 操作符）。

### resize {#resize-com.aspose.pdf.PageSize-}
调整页面大小。

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
将旋转枚举成员转换为整数值。

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
使用给定的页面设备发送页面进行处理。

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
使用给定的页面设备发送页面进行处理。

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

获取或设置在页面最后一个段落之后添加段落的选项。值：指示是否在页面最后一个段落之后添加段落。如果值为 true，则会在页面最后一个段落之后添加段落。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
设置页面的艺术框。

### setBackground {#setBackground-java.awt.Color-}
设置页面的背景颜色。

### setBackground {#setBackground-com.aspose.pdf.Color-}
设置页面的背景颜色。

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
获取或设置页面的背景图像（仅用于生成器，读取文档时不填充）。

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
设置页面的出血框。

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> 设置页面的裁剪框。 </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

设置页面显示持续时间。这是页面在演示期间显示的秒数。如果未定义持续时间，则返回 -1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 页面显示持续时间。 |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
仅供内部使用

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
设置页面页脚。

### setGroup {#setGroup-com.aspose.pdf.Group-}
设置一个组属性类，指定页面组的属性，以用于透明成像模型。

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
设置页面页眉。

### setLayers {#setLayers-java.util.ArrayList-}
设置图层集合。

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
设置图层集合。

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
设置页面的媒体框。

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
设置注释的线条样式。（仅用于生成器，读取文档时不填充）

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
设置页面信息。（仅用于生成器，读取文档时不填充）。

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

为页面设置大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 页面宽度。 |
| 高度 |  | 页面大小。 |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
设置段落。

### setRect {#setRect-com.aspose.pdf.Rectangle-}
获取或设置页面的矩形。获取时：如果指定，则返回页面裁剪框，否则返回页面媒体框。设置时：始终设置页面媒体框并返回。请注意，此属性不考虑页面旋转。若要获取考虑旋转的页面矩形，请使用 ActualRect。

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
设置页面的旋转。

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

设置页面的标签顺序。可能的值：Row，Column。默认，Manual。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | TabOrder 对象 @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
设置目录信息。

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
设置过渡

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
设置页面的裁剪框。

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

获取或设置 UserUnit 值。正数表示默认用户空间单位的大小，以 1/72 英寸的倍数计。默认值为 1。请设置为零或负数以清除页面中的此条目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
设置页面的水印。

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
尝试保存页面上存在的矢量图形。保存格式为 SVG。
