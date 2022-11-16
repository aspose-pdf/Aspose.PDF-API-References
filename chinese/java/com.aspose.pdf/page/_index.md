---
title: Page
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 PDF 文档页面的类。
type: docs
weight: 257
url: /zh/java/com.aspose.pdf/page/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.IDisposable、java.io.Closeable、com.aspose.pdf.ISupportsMemoryCleanup
```
public final class Page implements System.IDisposable, Closeable, ISupportsMemoryCleanup
```

表示 PDF 文档页面的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | 接受 AnnotationSelector 访问者对象，该对象提供使用注释的功能。 |
| [accept(ImagePlacementAbsorber visitor)](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | 接受 ImagePlacementAbsorber 访问者对象，该访问者对象提供处理图像放置对象的功能。 |
| [accept(TextAbsorber visitor)](#accept-com.aspose.pdf.TextAbsorber-) | 接受提供处理文本对象功能的 TextAbsorber 访问者对象。 |
| [accept(TextFragmentAbsorber visitor)](#accept-com.aspose.pdf.TextFragmentAbsorber-) | 接受提供处理文本对象功能的 TextFragmentAbsorber 访问者对象。 |
| [addImage(InputStream imageStream, Rectangle imageRect)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | 将图片添加到页面上，并将其定位在指定矩形保存图片比例的中间。 |
| [addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | 将图片添加到页面上，并将其定位在指定矩形保存图片比例的中间。 |
| [addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | 将可搜索图像添加到页面上，并将其定位在指定矩形保存图像比例的中间。 |
| [addImage(String imagePath, Rectangle rectangle)](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | 将图片添加到页面上，并将其定位在指定矩形保存图片比例的中间。 |
| [addImage(String hocr, InputStream imageStream, Rectangle imageRect)](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | 将可搜索图像添加到页面上，并将其定位在指定矩形保存图像比例的中间。 |
| [addStamp(Stamp stamp)](#addStamp-com.aspose.pdf.Stamp-) | 将邮票放入页面。 |
| [asByteArray(Resolution resolution)](#asByteArray-com.aspose.pdf.devices.Resolution-) | 将当前页面转换为 BMP 位图，然后返回字节数组。 |
| [asXml()](#asXml--) | 将当前页面转换为 utf8 编码的 xml。 |
| [calculateContentBBox()](#calculateContentBBox--) | 计算 bbox 值 - 包含没有可见边距的内容的矩形。 |
| [clearContents()](#clearContents--) | 仅供内部使用 |
| [close()](#close--) | 关闭此文档使用的所有资源。 |
| [convertToPNGMemoryStream()](#convertToPNGMemoryStream--) | 为 DSR、OMR、OCR 图像流将页面转换为 PNG。 |
| [deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable)](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--) |  |
| [dispose()](#dispose--) | 释放内存 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources)](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences(OperatorCollection contents, String name)](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | 返回使用具有指定名称的资源的运算符列表。 |
| [findReferences(String name)](#findReferences-java.lang.String-) | 查找参考资料 |
| [flatten()](#flatten--) | 删除位于页面上的所有静态字段并改为放置它们的值。 |
| [freeMemory()](#freeMemory--) | 清除缓存数据 |
| [getActions()](#getActions--) | 获取页面属性的集合。 |
| [getAnnotations()](#getAnnotations--) | 获取页面注释的集合。 |
| [getArtBox()](#getArtBox--) | 获取页面的艺术框。 |
| [getArtifacts()](#getArtifacts--) | 获取页面上的工件集合。 |
| [getBackground()](#getBackground--) | 获取页面的背景颜色。 |
| [getBackgroundImage()](#getBackgroundImage--) | 获取或设置页面的背景图像（仅适用于生成器）。 |
| [getBleedBox()](#getBleedBox--) | 获取页面的出血框。 |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 根据从运算符 SetColor、图像和表单中获取的信息获取页面的颜色类型。 |
| [getContents()](#getContents--) | 获取页面内容流中的运算符集合。 |
| [getContentsAppender()](#getContentsAppender--) | 获取当前内容附加器。 |
| [getCropBox()](#getCropBox--) | 获取页面的裁剪框。 |
| [getDocument()](#getDocument--) | 获取文档 |
| [getDuration()](#getDuration--) | 获取页面显示时长。 |
| [getEnginePage()](#getEnginePage--) | 仅供内部使用 |
| [getFieldsInTabOrder()](#getFieldsInTabOrder--) | 获取此页面上 Tab 顺序的 Field 对象列表。 |
| [getFooter()](#getFooter--) | 获取页脚。 |
| [getGroup()](#getGroup--) | 获取一个组属性类，该类指定用于透明成像模型的页页组的属性。 |
| [getHeader()](#getHeader--) | 获取页眉。 |
| [getLayers()](#getLayers--) | 获取图层集合。 |
| [getMediaBox()](#getMediaBox--) | 获取页面的媒体框。 |
| [getNoteLineStyle()](#getNoteLineStyle--) | 获取注释的线条样式。 |
| [getNotifications()](#getNotifications--) | 返回有关页面内容内部操作的通知。 |
| [getNumber()](#getNumber--) | 获取页码。 |
| [getOnBeforePageGenerate()](#getOnBeforePageGenerate--) | 自定义页眉和页脚的事件。 |
| [getPageInfo()](#getPageInfo--) | 获取页面信息。 |
| [getPageRect(boolean considerRotation)](#getPageRect-boolean-) | 根据其 CropBox 返回页面的矩形（如果 CropBox 为 null，则返回 MediaBox）。 |
| [getParagraphs()](#getParagraphs--) | 获取段落。 |
| [getRect()](#getRect--) | 根据其 CropBox 和 MediaBox 返回页面的矩形；对于获取：如果指定则返回页面裁剪框，否则返回页面媒体框。 |
| [getRect_Rename_Namesake()](#getRect-Rename-Namesake--) | 根据其 CropBox 和 MediaBox 返回页面的矩形； |
| [getResources()](#getResources--) | 获取页面资源。 |
| [getRotate()](#getRotate--) | 获取页面的旋转。 |
| [getRotationMatrix()](#getRotationMatrix--) | 获取页面的变换矩阵。 |
| [getTabOrder()](#getTabOrder--) | 获取页面的 Tab 键顺序。 |
| [getTocInfo()](#getTocInfo--) | 获取目录信息。 |
| [getTrimBox()](#getTrimBox--) | 获取页面的裁切框。 |
| [getUserUnit()](#getUserUnit--) | 获取或设置 UserUnit 值。 |
| [getWatermark()](#getWatermark--) | 获取页面的水印。 |
| [hashCode()](#hashCode--) |  |
| [intToRotation(int rotation)](#intToRotation-int-) | 将整数值转换为相应的旋转枚举成员。 |
| [isAddParagraphsAfterLast()](#isAddParagraphsAfterLast--) | 获取或设置页面最后一段后添加段落 |
| [isBlank(double fillThresholdFactor)](#isBlank-double-) | 获取页面是否为空白的标志。 |
| [makeGrayscale()](#makeGrayscale--) | 将页面转换为灰度。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeObjectReferences(OperatorCollection contents, String name)](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | 删除对象引用 |
| [removeObjectReferences(String name)](#removeObjectReferences-java.lang.String-) | 从页面内容中删除对 XObject 的引用（即所有使用对象名称的 Do 运算符）。 |
| [rotationToInt(int rotation)](#rotationToInt-int-) | 将旋转枚举成员转换为整数值。 |
| [sendTo(PageDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | 发送页面以使用给定的页面设备进行处理。 |
| [sendTo(PageDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | 发送页面以使用给定的页面设备进行处理。 |
| [setAddParagraphsAfterLast(boolean value)](#setAddParagraphsAfterLast-boolean-) | 获取或设置页面最后一段后添加段落 |
| [setArtBox(Rectangle value)](#setArtBox-com.aspose.pdf.Rectangle-) | 设置页面的艺术框。 |
| [setBackground(Color value)](#setBackground-com.aspose.pdf.Color-) | 设置页面的背景颜色。 |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | 设置页面的背景颜色。 |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | 获取或设置页面的背景图像（仅适用于生成器）。 |
| [setBleedBox(Rectangle value)](#setBleedBox-com.aspose.pdf.Rectangle-) | 设置页面的出血框。 |
| [setCropBox(Rectangle value)](#setCropBox-com.aspose.pdf.Rectangle-) | 设置页面裁剪框。 |
| [setDuration(double value)](#setDuration-double-) | 设置页面显示持续时间。 |
| [setEnginePage(IPage enginePage)](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | 仅供内部使用 |
| [setFooter(HeaderFooter value)](#setFooter-com.aspose.pdf.HeaderFooter-) | 设置页脚。 |
| [setGroup(Group value)](#setGroup-com.aspose.pdf.Group-) | 设置组属性类，指定用于透明成像模型的页面的页面组的属性。 |
| [setHeader(HeaderFooter value)](#setHeader-com.aspose.pdf.HeaderFooter-) | 设置页眉。 |
| [setLayers(ArrayList<Layer> value)](#setLayers-java.util.ArrayList-com.aspose.pdf.Layer--) | 设置图层集合。 |
| [setLayersInternal(System.Collections.Generic.List<Layer> value)](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Layer--) | 设置图层集合。 |
| [setMediaBox(Rectangle value)](#setMediaBox-com.aspose.pdf.Rectangle-) | 设置页面的媒体框。 |
| [setNoteLineStyle(GraphInfo value)](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | 设置注释的线条样式。 |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置页面信息。 |
| [setPageSize(double width, double height)](#setPageSize-double-double-) | 设置页面的页面大小。 |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | 设置段落。 |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | 获取或设置页面的矩形。 |
| [setRotate(int value)](#setRotate-int-) | 设置页面的旋转。 |
| [setTabOrder(int value)](#setTabOrder-int-) | 设置页面的 Tab 键顺序。 |
| [setTocInfo(TocInfo value)](#setTocInfo-com.aspose.pdf.TocInfo-) | 设置目录信息。 |
| [setTransition(IPdfDictionary transition)](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | 设置过渡 |
| [setTrimBox(Rectangle value)](#setTrimBox-com.aspose.pdf.Rectangle-) | 设置页面的裁切框。 |
| [setUserUnit(double value)](#setUserUnit-double-) | 获取或设置 UserUnit 值。 |
| [setWatermark(Watermark value)](#setWatermark-com.aspose.pdf.Watermark-) | 设置页面的水印。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


接受 AnnotationSelector 访问者对象，该对象提供使用注释的功能。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | 注释选择器对象。 |

### accept(ImagePlacementAbsorber visitor) {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
```
public void accept(ImagePlacementAbsorber visitor)
```


接受 ImagePlacementAbsorber 访问者对象，该访问者对象提供处理图像放置对象的功能。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [ImagePlacementAbsorber](../../com.aspose.pdf/imageplacementabsorber) | 图像放置吸收器对象。 |

### accept(TextAbsorber visitor) {#accept-com.aspose.pdf.TextAbsorber-}
```
public void accept(TextAbsorber visitor)
```


接受提供处理文本对象功能的 TextAbsorber 访问者对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [TextAbsorber](../../com.aspose.pdf/textabsorber) | 文本吸收器对象。 |

### accept(TextFragmentAbsorber visitor) {#accept-com.aspose.pdf.TextFragmentAbsorber-}
```
public void accept(TextFragmentAbsorber visitor)
```


接受提供处理文本对象功能的 TextFragmentAbsorber 访问者对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) | 文本吸收器对象。 |

### addImage(InputStream imageStream, Rectangle imageRect) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
```
public void addImage(InputStream imageStream, Rectangle imageRect)
```


将图片添加到页面上，并将其定位在指定矩形保存图片比例的中间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 图像流。 |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | 图片的位置。 |

### addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
```
public void addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters)
```


将图片添加到页面上，并将其定位在指定矩形保存图片比例的中间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 图像流。 |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | 图片的位置。 |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | 合成参数。 |

### addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
```
public void addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions)
```


将可搜索图像添加到页面上，并将其定位在指定矩形保存图像比例的中间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 输入流对象 |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |
| imageWidth | int | 整数值 |
| imageHeight | int | 整数值 |
| saveImageProportions | boolean | 布尔值 |

### addImage(String imagePath, Rectangle rectangle) {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
```
public void addImage(String imagePath, Rectangle rectangle)
```


将图片添加到页面上，并将其定位在指定矩形保存图片比例的中间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imagePath | java.lang.String | 图像的路径。 |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | 图片的位置。 |

### addImage(String hocr, InputStream imageStream, Rectangle imageRect) {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
```
public void addImage(String hocr, InputStream imageStream, Rectangle imageRect)
```


将可搜索图像添加到页面上，并将其定位在指定矩形保存图像比例的中间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| hocr | java.lang.String | 图像的原形。 |
| imageStream | java.io.InputStream | 图像流。 |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | 图片的位置。 |

### addStamp(Stamp stamp) {#addStamp-com.aspose.pdf.Stamp-}
```
public void addStamp(Stamp stamp)
```


将邮票放入页面。戳记可以是页码、图像或简单的文本，例如一些标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stamp | [Stamp](../../com.aspose.pdf/stamp) | 添加到页面上的戳记。每个图章都有其坐标和与图章类型相关的相应属性，即图像或文本值。 |

### asByteArray(Resolution resolution) {#asByteArray-com.aspose.pdf.devices.Resolution-}
```
public byte[] asByteArray(Resolution resolution)
```


将当前页面转换为 BMP 位图，然后返回字节数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 决议。 |

**退货：**
字节[] - 转换后的图像字节数组。
### asXml() {#asXml--}
```
public String asXml()
```


将当前页面转换为 utf8 编码的 xml。

**退货：**
java.lang.String - 转换后的 xml 字符串。
### calculateContentBBox() {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```


计算 bbox 值 - 包含没有可见边距的内容的矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - Bbox 值 - 包含没有可见边距的内容的矩形
### clearContents() {#clearContents--}
```
public void clearContents()
```


仅供内部使用

### close() {#close--}
```
public void close()
```


关闭此文档使用的所有资源。

### convertToPNGMemoryStream() {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```


为 DSR、OMR、OCR 图像流将页面转换为 PNG。

**退货：**
字节[- 以字节为单位的图像流[大批。
### deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable) {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--}
```
public void deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| usageTable | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.Integer> |  |

### dispose() {#dispose--}
```
public void dispose()
```


释放内存

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
### fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources) {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| usageTable | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.Integer> |  |
| CommonResources | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### findReferences(OperatorCollection contents, String name) {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
```
public static List<Object> findReferences(OperatorCollection contents, String name)
```


返回使用具有指定名称的资源的运算符列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contents | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | OperatorCollection 值 |
| name | java.lang.String | 字符串值 |

**退货：**
java.util.List<java.lang.Object> - 对象列表
### findReferences(String name) {#findReferences-java.lang.String-}
```
public List<Object> findReferences(String name)
```


查找参考资料

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字符串值 |

**退货：**
java.util.List<java.lang.Object> - 列表对象
### flatten() {#flatten--}
```
public void flatten()
```


删除位于页面上的所有静态字段并改为放置它们的值。

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


清除缓存数据

### getActions() {#getActions--}
```
public PageActionCollection getActions()
```


获取页面属性的集合。

**退货：**
[PageActionCollection](../../com.aspose.pdf/pageactioncollection) PageActionCollection 值
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


获取页面注释的集合。注释 

**退货：**
[AnnotationCollection](../../com.aspose.pdf/annotationcollection) AnnotationCollection 值
### getArtBox() {#getArtBox--}
```
public Rectangle getArtBox()
```


获取页面的艺术框。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形值

--------------------

```
Example demonstrates how to get art box of the page:


 Document document = new Document("sample.pdf");
 Rectangle artBox = document.getPages().get(1).getArtBox();
```
### getArtifacts() {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```


获取页面上的工件集合。

**退货：**
[ArtifactCollection](../../com.aspose.pdf/artifactcollection) ArtifactCollection 值
### getBackground() {#getBackground--}
```
public Color getBackground()
```


获取页面的背景颜色。

**退货：**
[Color](../../java.awt/color) - 颜色值
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


获取或设置页面的背景图像（仅适用于生成器）。

**退货：**
[Image](../../com.aspose.pdf/image) 图片实例
### getBleedBox() {#getBleedBox--}
```
public Rectangle getBleedBox()
```


获取页面的出血框。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形值

--------------------

```
Example demonstrates how to get bleed box of the page:


 Document document = new Document("sample.pdf");
 Rectangle bleedBox = document.getPages().get(1).getBleedBox();
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


根据从运算符 SetColor、图像和表单中获取的信息获取页面的颜色类型。

**退货：**
int - ColorType 元素
### getContents() {#getContents--}
```
public OperatorCollection getContents()
```


获取页面内容流中的运算符集合。运算符集合 

**退货：**
[OperatorCollection](../../com.aspose.pdf/operatorcollection) OperatorCollection 对象

--------------------

```
Example is demonstrates how to scan operators stream of page.


 Document document = new Document("sample.pdf");
 Operators contents = document.getPages().get_Item(1).getContents();
 for(Operator op : ```
(Iterable)
```contents)
 {
     System.out.println(op);
 }
```
### getContentsAppender() {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```


获取当前内容附加器。 ContentsAppender 

**退货：**
[ContentsAppender](../../com.aspose.pdf/contentsappender) - ContentsAppender 值
### getCropBox() {#getCropBox--}
```
public Rectangle getCropBox()
```


获取页面的裁剪框。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形值

--------------------

```
Example demonstrates how to get crop box of the page:


 Document document = new Document("sample.pdf");
 Rectangle cropBox = document.getPages().get_Item(1).getCropBox();
```
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取文档

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 对象
### getDuration() {#getDuration--}
```
public double getDuration()
```


获取页面显示时长。这是页面在演示过程中应显示的时间（以秒为单位）。如果未定义持续时间，则返回 -1。

--------------------

示例演示如何获取页面持续时间

文档 document = new Document("sample.pdf");页面 page = document.getPages().get(1); int pageRect = page.getDuration();

**退货：**
双倍价值
### getEnginePage() {#getEnginePage--}
```
public IPage getEnginePage()
```


仅供内部使用

**退货：**
[IPage](../../com.aspose.pdf.engine.commondata/ipage) - 内部实例
### getFieldsInTabOrder() {#getFieldsInTabOrder--}
```
public List<Field> getFieldsInTabOrder()
```


获取此页面上 Tab 顺序的 Field 对象列表。

**退货：**
java.util.List<com.aspose.pdf.Field> - 字段对象列表
### getFooter() {#getFooter--}
```
public HeaderFooter getFooter()
```


获取页脚。

**退货：**
[HeaderFooter](../../com.aspose.pdf/headerfooter) 页脚。
### getGroup() {#getGroup--}
```
public Group getGroup()
```


获取一个组属性类，该类指定用于透明成像模型的页页组的属性。

**退货：**
[Group](../../com.aspose.pdf/group) - 集团价值
### getHeader() {#getHeader--}
```
public HeaderFooter getHeader()
```


获取页眉。

**退货：**
[HeaderFooter](../../com.aspose.pdf/headerfooter) 页眉。
### getLayers() {#getLayers--}
```
public List<Layer> getLayers()
```


获取图层集合。

**退货：**
java.util.List<com.aspose.pdf.Layer> - 值：图层集合。
### getMediaBox() {#getMediaBox--}
```
public Rectangle getMediaBox()
```


获取页面的媒体框。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形值

--------------------

```
Example demonstrates how to get media box of the page:


 Document document = new Document("sample.pdf");
 Rectangle mediaBox = document.getPages().get(1).getMediaBox();
```
### getNoteLineStyle() {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```


获取笔记的线条样式。（仅适用于生成器）

**退货：**
[GraphInfo](../../com.aspose.pdf/graphinfo) - GraphInfo 值
### getNotifications() {#getNotifications--}
```
public String getNotifications()
```


返回有关页面内容内部操作的通知。 （目前仅支持文本添加场景下的段落事件通知。）

**退货：**
java.lang.String - 表示有关页面内容内部操作的通知的字符串。
### getNumber() {#getNumber--}
```
public final int getNumber()
```


获取页码。

**退货：**
int - 整数值
### getOnBeforePageGenerate() {#getOnBeforePageGenerate--}
```
public PdfEvent<Page.BeforePageGenerate> getOnBeforePageGenerate()
```


自定义页眉和页脚的事件。

**退货：**
[PdfEvent](../../com.aspose.pdf/pdfevent) - PdfEvent 实例 
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


获取页面信息。（仅供生成器使用，读取文件时不填写）。

**退货：**
[PageInfo](../../com.aspose.pdf/pageinfo) - 页面信息。
### getPageRect(boolean considerRotation) {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```


根据其 CropBox 返回页面的矩形（如果 CropBox 为 null，则返回 MediaBox）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| considerRotation | boolean | 如果为真，则页面的旋转将被考虑在矩形计算中。 |

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 页面的矩形。
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


获取段落。

**退货：**
[Paragraphs](../../com.aspose.pdf/paragraphs) - 段落。
### getRect() {#getRect--}
```
public Rectangle getRect()
```


根据其 CropBox 和 MediaBox 返回页面的矩形；对于获取：如果指定则返回页面裁剪框，否则返回页面媒体框。对于设置：页面媒体框始终设置。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形值

--------------------

```
Example demonstrates how to get page rectangle:

 Document document = new Document("sample.pdf");
 Page page = document.getPages().get(1);
 Rectangle pageRect = page.getRect();
```
### getRect_Rename_Namesake() {#getRect-Rename-Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```


根据其 CropBox 和 MediaBox 返回页面的矩形；

内部的

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形值

--------------------

```
Example demonstrates how to get page rectangle:

 Document document = new Document("sample.pdf");
 Page page = document.getPages().get(1);
 Rectangle pageRect = page.getRect();
```
### getResources() {#getResources--}
```
public Resources getResources()
```


获取页面资源。资源对象包含图像、表单和字体的集合。资源 

**退货：**
[Resources](../../com.aspose.pdf/resources) - 资源价值

--------------------

```
Example demonstrates scan through page images:


 Document document = new Document("sample.pdf");
 DocumentActions actions = document.getActions();
 Resources resources = document.getPages().get(1).getResources();
 for(XImage image : ```
(Ierable)resources
```.getImages())
 {
   System.out.println(image.getWidth() + ":" + image.getHeight());
 }
```
### getRotate() {#getRotate--}
```
public int getRotate()
```


获取页面的旋转。

**退货：**
int - 旋转元素

--------------------

```
Example demonstrates how to determine page rotation.


 Document document = new Document("sample.pdf");
 System.out.println(document.getPages().get(1).getRotate());
```
### getRotationMatrix() {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```


获取页面的变换矩阵。

**退货：**
[Matrix](../../com.aspose.pdf/matrix) 矩阵值
### getTabOrder() {#getTabOrder--}
```
public int getTabOrder()
```


获取页面的 Tab 键顺序。可能的值：行、列。默认、手动

**退货：**
int - TabOrder 值
### getTocInfo() {#getTocInfo--}
```
public TocInfo getTocInfo()
```


获取目录信息。

**退货：**
[TocInfo](../../com.aspose.pdf/tocinfo) 目录信息 - 默认为空。如果它设置此页面将包含目录。
### getTrimBox() {#getTrimBox--}
```
public Rectangle getTrimBox()
```


获取页面的裁切框。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形值

--------------------

```
Example demonstrates how to get trim box of the page:


 Document document = new Document("sample.pdf");
 Rectangle trimBox = document.getPages().get(1).getTrimBox();
```
### getUserUnit() {#getUserUnit--}
```
public final double getUserUnit()
```


获取或设置 UserUnit 值。一个正数，给出默认用户空间单元的大小，是 1 的倍数\\u0432\\u0403\\u201e 72 英寸。默认值为 1。请设置零或负值以清除页面中的此项。

**退货：**
双倍价值
### getWatermark() {#getWatermark--}
```
public Watermark getWatermark()
```


获取页面的水印。

**退货：**
[Watermark](../../com.aspose.pdf/watermark) - 水印值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### intToRotation(int rotation) {#intToRotation-int-}
```
public static int intToRotation(int rotation)
```


将整数值转换为相应的旋转枚举成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rotation | int | 要转换的整数值 |

**退货：**
int - 旋转枚举成员
### isAddParagraphsAfterLast() {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```


获取或设置页面最后一段后添加段落

Value：Value表示是否在页面最后一段之后添加段落。如果值为 true，将在页面的最后一段之后添加段落。

**退货：**
boolean - 布尔值
### isBlank(double fillThresholdFactor) {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```


获取页面是否为空白的标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fillThresholdFactor | double | 管理检测灵敏度的填充阈值。应等于或大于 0.01。 |

**退货：**
boolean - 布尔值 True - 如果页面为空白；否则，假的。
### makeGrayscale() {#makeGrayscale--}
```
public final void makeGrayscale()
```


将页面转换为灰度。

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeObjectReferences(OperatorCollection contents, String name) {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
```
public static void removeObjectReferences(OperatorCollection contents, String name)
```


删除对象引用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contents | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | OperatorCollection 对象 |
| name | java.lang.String | 价值 |

### removeObjectReferences(String name) {#removeObjectReferences-java.lang.String-}
```
public void removeObjectReferences(String name)
```


从页面内容中删除对 XObject 的引用（即所有使用对象名称的 Do 运算符）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字符串值 |

### rotationToInt(int rotation) {#rotationToInt-int-}
```
public static int rotationToInt(int rotation)
```


将旋转枚举成员转换为整数值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rotation | int | 旋转枚举成员。 |

**退货：**
int - 对应的整数值
### sendTo(PageDevice device, OutputStream output) {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
```
public void sendTo(PageDevice device, OutputStream output)
```


发送页面以使用给定的页面设备进行处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | [PageDevice](../../com.aspose.pdf.devices/pagedevice) | 处理页面的设备。 |
| output | java.io.OutputStream | 与设备一起使用以保存其输出的结果流。 |

### sendTo(PageDevice device, String outputFileName) {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
```
public void sendTo(PageDevice device, String outputFileName)
```


发送页面以使用给定的页面设备进行处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | [PageDevice](../../com.aspose.pdf.devices/pagedevice) | 处理页面的设备。 |
| outputFileName | java.lang.String | 与设备一起使用以保存其输出的文件。 |

### setAddParagraphsAfterLast(boolean value) {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```


获取或设置页面最后一段后添加段落

Value：Value表示是否在页面最后一段之后添加段落。如果值为 true，将在页面的最后一段之后添加段落。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setArtBox(Rectangle value) {#setArtBox-com.aspose.pdf.Rectangle-}
```
public void setArtBox(Rectangle value)
```


设置页面的艺术框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形值 |

### setBackground(Color value) {#setBackground-com.aspose.pdf.Color-}
```
public void setBackground(Color value)
```


设置页面的背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色对象 |

### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public void setBackground(Color value)
```


设置页面的背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color | 颜色对象 |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


获取或设置页面的背景图像（仅适用于生成器）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | 图片实例 |

### setBleedBox(Rectangle value) {#setBleedBox-com.aspose.pdf.Rectangle-}
```
public void setBleedBox(Rectangle value)
```


设置页面的出血框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形值 |

### setCropBox(Rectangle value) {#setCropBox-com.aspose.pdf.Rectangle-}
```
public void setCropBox(Rectangle value)
```


设置页面裁剪框。

--------------------

```
Example demonstrates how to get crop box of the page:


 Document document = new Document("sample.pdf");
 document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### setDuration(double value) {#setDuration-double-}
```
public void setDuration(double value)
```


设置页面显示持续时间。这是页面在演示过程中应显示的时间（以秒为单位）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 页面显示时长。 |

### setEnginePage(IPage enginePage) {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
```
public void setEnginePage(IPage enginePage)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| enginePage | [IPage](../../com.aspose.pdf.engine.commondata/ipage) | 内部实例 |

### setFooter(HeaderFooter value) {#setFooter-com.aspose.pdf.HeaderFooter-}
```
public void setFooter(HeaderFooter value)
```


设置页脚。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [HeaderFooter](../../com.aspose.pdf/headerfooter) | 页脚。 |

### setGroup(Group value) {#setGroup-com.aspose.pdf.Group-}
```
public void setGroup(Group value)
```


设置组属性类，指定用于透明成像模型的页面的页面组的属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Group](../../com.aspose.pdf/group) | 集团价值 |

### setHeader(HeaderFooter value) {#setHeader-com.aspose.pdf.HeaderFooter-}
```
public void setHeader(HeaderFooter value)
```


设置页眉。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [HeaderFooter](../../com.aspose.pdf/headerfooter) | 页眉。 |

### setLayers(ArrayList<Layer> value) {#setLayers-java.util.ArrayList-com.aspose.pdf.Layer--}
```
public void setLayers(ArrayList<Layer> value)
```


设置图层集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.ArrayList<com.aspose.pdf.Layer> | ：图层集合。 |

### setLayersInternal(System.Collections.Generic.List<Layer> value) {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Layer--}
```
public void setLayersInternal(System.Collections.Generic.List<Layer> value)
```


设置图层集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Layer> | ：图层集合。 |

### setMediaBox(Rectangle value) {#setMediaBox-com.aspose.pdf.Rectangle-}
```
public void setMediaBox(Rectangle value)
```


设置页面的媒体框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [长方形](../../com.aspose.pdf/rectangle) | Rectangle |

### setNoteLineStyle(GraphInfo value) {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
```
public void setNoteLineStyle(GraphInfo value)
```


设置注释的线条样式。（仅适用于生成器）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | : GraphInfo 值 |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


设置页面信息。（仅供生成器使用，读取文件时不填写）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | 页面信息。 |

### setPageSize(double width, double height) {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```


设置页面的页面大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | double | 页面宽度。 |
| height | double | 页面大小。 |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


设置段落。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | 款值 |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


获取或设置页面的矩形。对于获取：如果指定则返回页面裁剪框，否则返回页面媒体框。对于设置：页面媒体框始终设置。被退回。请注意，此属性不考虑页面旋转。要获得考虑旋转的页面矩形，请使用 ActualRect。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


设置页面的旋转。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 旋转元素 |

### setTabOrder(int value) {#setTabOrder-int-}
```
public void setTabOrder(int value)
```


设置页面的 Tab 键顺序。可能的值：行、列。默认、手动

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | TabOrder 对象 |

### setTocInfo(TocInfo value) {#setTocInfo-com.aspose.pdf.TocInfo-}
```
public void setTocInfo(TocInfo value)
```


设置目录信息。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TocInfo](../../com.aspose.pdf/tocinfo) | 目录信息 - 默认为空。如果它设置此页面将包含目录。 |

### setTransition(IPdfDictionary transition) {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setTransition(IPdfDictionary transition)
```


设置过渡

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| transition | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) | IPDFDictionary 对象 |

### setTrimBox(Rectangle value) {#setTrimBox-com.aspose.pdf.Rectangle-}
```
public void setTrimBox(Rectangle value)
```


设置页面的裁切框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形值 |

### setUserUnit(double value) {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```


获取或设置 UserUnit 值。一个正数，给出默认用户空间单元的大小，是 1 的倍数\\u0432\\u0403\\u201e 72 英寸。默认值为 1。请设置零或负值以清除页面中的此项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setWatermark(Watermark value) {#setWatermark-com.aspose.pdf.Watermark-}
```
public void setWatermark(Watermark value)
```


设置页面的水印。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Watermark](../../com.aspose.pdf/watermark) | 水印对象 |

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
