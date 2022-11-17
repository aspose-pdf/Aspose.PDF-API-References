---
title: FreeTextAnnotation
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示直接在页面上显示文本的自由文本注释。
type: docs
weight: 142
url: /zh/java/com.aspose.pdf/freetextannotation/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class FreeTextAnnotation extends MarkupAnnotation
```

表示直接在页面上显示文本的自由文本注释。与普通文本注释不同，自由文本注释没有打开或关闭状态；文本不会显示在弹出窗口中，而是始终可见。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FreeTextAnnotation(IDocument document, DefaultAppearance appearance)](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | 与生成器一起使用的构造函数。 |
| [FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance)](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | 在指定页面上创建新的 FreeText 注释。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理注释。 |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | 根据矩阵变换更新参数和外观。 |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | 仅供内部使用 |
| [deepClone()](#deepClone--) | 克隆此实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | 直接在页面上放置注释内容，注释对象将被移除。 |
| [getActiveState()](#getActiveState--) | 获取当前注释外观状态。 |
| [getAlignment()](#getAlignment--) | 注释对齐。 |
| [getAnnotationType()](#getAnnotationType--) | 获取注解类型。 |
| [getAppearance()](#getAppearance--) | 获取注解的外观字典。 |
| [getBorder()](#getBorder--) | 获取注释边框特征。 |
| [getCallout()](#getCallout--) | 指定标注线的点数组。 |
| [getCharacteristics()](#getCharacteristics--) | 获取注解特征。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取注释颜色。 |
| [getContents()](#getContents--) | 获取注释文本。 |
| [getCreationDate()](#getCreationDate--) | 获取创建注释的日期和时间。 |
| [getDefaultAppearance()](#getDefaultAppearance--) | 获取用于设置文本格式的默认外观字符串。 |
| [getDefaultAppearanceObject()](#getDefaultAppearanceObject--) | 表示 FreeText 注释的默认外观的对象。 |
| [getDefaultStyle()](#getDefaultStyle--) | 获取默认样式字符串。 |
| [getEndingStyle()](#getEndingStyle--) | 获取线结束点的线结束样式。 |
| [getEngineDict()](#getEngineDict--) | 仅限内部 |
| [getEngineObj()](#getEngineObj--) | 仅供内部使用 |
| [getFlags()](#getFlags--) | 获取注释的标志。 |
| [getFullName()](#getFullName--) | 获取注释的完整限定名称。 |
| [getHeight()](#getHeight--) | 获取注释的高度。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | 获取或设置注释的文本对齐方式。 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getInReplyTo()](#getInReplyTo--) | 对该注释“回复”的注释的引用。 |
| [getIntent()](#getIntent--) | 获取自由文本注释的意图。 |
| [getJustification()](#getJustification--) | 获取一个代码，该代码指定用于显示注释文本的四边形（对齐）形式。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getModified()](#getModified--) | 获取最近修改注释的日期和时间。 |
| [getModifiedInternal()](#getModifiedInternal--) | 获取最近修改注释的日期和时间。 |
| [getName()](#getName--) | 获取页面上的注释名称。 |
| [getNormalAppearance()](#getNormalAppearance--) | 获得正常外观。 |
| [getOpacity()](#getOpacity--) | 获取用于绘制注释的常量不透明度值。 |
| [getPage()](#getPage--) | 获取与此注释关联的页面对象。 |
| [getPageIndex()](#getPageIndex--) | 获取包含注释的页面索引。 |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) | 获取包含注释的页面索引。 |
| [getPdfActions()](#getPdfActions--) | 获取注释操作列表。 |
| [getPopup()](#getPopup--) | 用于输入或编辑与此注释关联的文本的弹出式注释。 |
| [getRect()](#getRect--) | 获取注释矩形。 |
| [getRectangle(boolean considerRotation)](#getRectangle-boolean-) | 返回考虑页面旋转的注释矩形。 |
| [getReplyType()](#getReplyType--) | 一个字符串，指定此批注与 InReplyTo 指定的批注之间的关系（“回复类型”）。 |
| [getRichText()](#getRichText--) | 获取打开注释时在弹出窗口中显示的富文本字符串。 |
| [getRotate()](#getRotate--) | 注释旋转的角度。 |
| [getStartingStyle()](#getStartingStyle--) | 获取或设置线结束点的线结束样式。 |
| [getStates()](#getStates--) | 获取标注的外观字典。 |
| [getSubject()](#getSubject--) | 获取表示对象说明的文本。 |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | 获取注释的文本对齐方式。 |
| [getTextRectangle()](#getTextRectangle--) | 描述两个矩形之间数值差异的矩形：注释的 Rect 条目和包含在该矩形内的矩形。 |
| [getTextStyle()](#getTextStyle--) | 获取或设置文本的外观样式。当文本样式更改时，文本外观也会更新。 |
| [getTitle()](#getTitle--) | 获取应显示在注释标题栏中的文本。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getWidth()](#getWidth--) | 获取注释的宽度。 |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [initialize(IDocument doc)](#initialize-com.aspose.pdf.IDocument-) | 实例初始化 |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [isUpdateAppearanceOnConvert()](#isUpdateAppearanceOnConvert--) | 如果为真，注释外观将在将 PF 文档转换为图像之前更新。 |
| [isUseFontSubset()](#isUseFontSubset--) | 如果此属性设置为 true，字体将作为子集添加到文档中。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | 设置当前注释外观状态。 |
| [setAlignment(int value)](#setAlignment-int-) | 注释对齐。 |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | 设置注释边框特征。 |
| [setCallout(Point[] value)](#setCallout-com.aspose.pdf.Point---) | 指定标注线的点数组。 |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | 设置注释颜色。 |
| [setContents(String value)](#setContents-java.lang.String-) | 设置注释文本。 |
| [setDefaultAppearance(String value)](#setDefaultAppearance-java.lang.String-) | 设置用于格式化文本的默认外观字符串。 |
| [setDefaultStyle(String value)](#setDefaultStyle-java.lang.String-) | 设置默认样式字符串。 |
| [setEndingStyle(int value)](#setEndingStyle-int-) | 设置线结束点的线结束样式。 |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setFlags(int value)](#setFlags-int-) | 设置注释的标志。 |
| [setHeight(double value)](#setHeight-double-) | 设置注释的高度。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落的水平对齐方式 |
| [setHorizontalAlignment_Annotation_New(int value)](#setHorizontalAlignment-Annotation-New-int-) | 获取或设置注释的文本对齐方式。 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setInReplyTo(Annotation value)](#setInReplyTo-com.aspose.pdf.Annotation-) | 对该注释“回复”的注释的引用。 |
| [setIntent(int value)](#setIntent-int-) | 设置自由文本注释的意图。 |
| [setJustification(int value)](#setJustification-int-) | 设置一个代码，指定要在显示注释文本时使用的四边形（对齐）形式。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setModified(Date value)](#setModified-java.util.Date-) | 设置最近修改注释的日期和时间。 |
| [setModifiedInternal(System.DateTime value)](#setModifiedInternal-com.aspose.ms.System.DateTime-) | 设置最近修改注释的日期和时间。 |
| [setName(String value)](#setName-java.lang.String-) | 在页面上设置注释名称。 |
| [setOpacity(double value)](#setOpacity-double-) | 设置用于绘制注释的常量不透明度值。 |
| [setPopup(PopupAnnotation value)](#setPopup-com.aspose.pdf.PopupAnnotation-) | 用于输入或编辑与此注释关联的文本的弹出式注释。 |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | 设置注释矩形。 |
| [setReplyType(int value)](#setReplyType-int-) | 一个字符串，指定此批注与 InReplyTo 指定的批注之间的关系（“回复类型”）。 |
| [setRichText(String value)](#setRichText-java.lang.String-) | 设置打开注释时在弹出窗口中显示的富文本字符串。 |
| [setRotate(int value)](#setRotate-int-) | 注释旋转的角度。 |
| [setStartingStyle(int value)](#setStartingStyle-int-) | 获取或设置线结束点的线结束样式。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 设置表示对象描述的文本。 |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | 设置注释的文本对齐方式。 |
| [setTextRectangle(Rectangle value)](#setTextRectangle-com.aspose.pdf.Rectangle-) | 描述两个矩形之间数值差异的矩形：注释的 Rect 条目和包含在该矩形内的矩形。 |
| [setTextStyle(TextStyle value)](#setTextStyle-com.aspose.pdf.TextStyle-) | 设置外观中文本的样式。当文本样式更改时，文本外观也会更新。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 设置应显示在注释标题栏中的文本。 |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | 如果为真，注释外观将在将 PF 文档转换为图像之前更新。 |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | 如果此属性设置为 true，字体将作为子集添加到文档中。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置段落的垂直对齐方式 |
| [setWidth(double value)](#setWidth-double-) | 设置注释的宽度。 |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [updateAppearance()](#updateAppearance--) | 在更改/移动文本后更新外观。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FreeTextAnnotation(IDocument document, DefaultAppearance appearance) {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
```
public FreeTextAnnotation(IDocument document, DefaultAppearance appearance)
```


与生成器一起使用的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 将在其中创建注释的文档。 |
| appearance | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | 默认外观 |

### FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance) {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
```
public FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance)
```


在指定页面上创建新的 FreeText 注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 应在其中创建注释的文档页面。 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 注释矩形，定义注释在页面上的位置。 |
| appearance | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | 用于格式化文本的默认外观字符串。 |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


接受访问者对象以处理注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | 访客对象。 |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


根据矩阵变换更新参数和外观。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | 用于转换（调整大小）的矩阵。 |

### createAnnotation(IPdfObject annotEngineObj, Page page) {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
```
public static Annotation createAnnotation(IPdfObject annotEngineObj, Page page)
```


仅供内部使用

从描述注释的 PDF 对象初始化注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotEngineObj | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | 描述注释的 PDF 对象 |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |

**退货：**
[Annotation](../../com.aspose.pdf/annotation) 创建适当类型的注释对象
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆此实例。虚拟方法。始终返回空值。

**退货：**
java.lang.Object - 空
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
### flatten() {#flatten--}
```
public void flatten()
```


直接在页面上放置注释内容，注释对象将被移除。

### getActiveState() {#getActiveState--}
```
public String getActiveState()
```


获取当前注释外观状态。

**退货：**
java.lang.String - 字符串值
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


注释对齐。此属性已过时。使用 getHorizontalAlignment\_注解\_New 代替。

**退货：**
int - TextAlignment 元素
### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


获取注解类型。

**退货：**
int - 整数值
### getAppearance() {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```


获取注解的外观字典。

**退货：**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) AppearanceDictionary 对象
### getBorder() {#getBorder--}
```
public Border getBorder()
```


获取注释边框特征。边界 

**退货：**
[Border](../../com.aspose.pdf/border) 边框对象
### getCallout() {#getCallout--}
```
public final Point[] getCallout()
```


指定标注线的点数组。

**退货：**
com.aspose.pdf.点[- 点数组
### getCharacteristics() {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```


获取注解特征。

**退货：**
[Characteristics](../../com.aspose.pdf/characteristics) 特征对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


获取注释颜色。

**退货：**
[Color](../../com.aspose.pdf/color) 颜色对象
### getContents() {#getContents--}
```
public String getContents()
```


获取注释文本。

**退货：**
java.lang.String - 字符串值
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


获取创建注释的日期和时间。

**退货：**
[Date](../../java.util/date) - 日期对象
### getDefaultAppearance() {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```


获取用于设置文本格式的默认外观字符串。

**退货：**
java.lang.String - 字符串值
### getDefaultAppearanceObject() {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```


表示 FreeText 注释的默认外观的对象。

**退货：**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) 默认外观对象
### getDefaultStyle() {#getDefaultStyle--}
```
public String getDefaultStyle()
```


获取默认样式字符串。

**退货：**
java.lang.String - 字符串值
### getEndingStyle() {#getEndingStyle--}
```
public int getEndingStyle()
```


获取线结束点的线结束样式。

**退货：**
int - LineEnding 值
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


仅限内部

**退货：**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) IPdfDictionary 对象
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


仅供内部使用

**退货：**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) 内部项目
### getFlags() {#getFlags--}
```
public int getFlags()
```


获取注释的标志。

**退货：**
int - 注释的标志
### getFullName() {#getFullName--}
```
public String getFullName()
```


获取注释的完整限定名称。

**退货：**
java.lang.String - 字符串值
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取注释的高度。

**退货：**
注释的双倍高度
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取段落的水平对齐方式

**退货：**
int - HorizontalAlignment 值
### getHorizontalAlignment_Annotation_New() {#getHorizontalAlignment-Annotation-New--}
```
public final int getHorizontalAlignment_Annotation_New()
```


获取或设置注释的文本对齐方式。

**退货：**
int - 注释的文本对齐方式。
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


获取片段超链接（用于 pdf 生成器）。

**退货：**
[Hyperlink](../../com.aspose.pdf/hyperlink) - 片段超链接（用于 pdf 生成器）。
### getInReplyTo() {#getInReplyTo--}
```
public Annotation getInReplyTo()
```


对该注释“回复”的注释的引用。两个注释必须在文档的同一页上。

**退货：**
[Annotation](../../com.aspose.pdf/annotation) - 注释值
### getIntent() {#getIntent--}
```
public int getIntent()
```


获取自由文本注释的意图。

**退货：**
int - 整数值
### getJustification() {#getJustification--}
```
public int getJustification()
```


获取一个代码，该代码指定用于显示注释文本的四边形（对齐）形式。

**退货：**
int - 整数值
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取段落的外边距（用于生成 pdf）

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getModified() {#getModified--}
```
public Date getModified()
```


获取最近修改注释的日期和时间。

**退货：**
[Date](../../java.util/date) 最近修改注释的日期和时间。
### getModifiedInternal() {#getModifiedInternal--}
```
public System.DateTime getModifiedInternal()
```


获取最近修改注释的日期和时间。

**退货：**
com.aspose.ms.System.DateTime - 日期时间对象
### getName() {#getName--}
```
public String getName()
```


获取页面上的注释名称。

**退货：**
java.lang.String - 字符串值
### getNormalAppearance() {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```


获得正常外观。

**退货：**
[XForm](../../com.aspose.pdf/xform) 变形对象
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


获取用于绘制注释的常量不透明度值。

**退货：**
双倍价值
### getPage() {#getPage--}
```
public Page getPage()
```


获取与此注释关联的页面对象。

**退货：**
[Page](../../com.aspose.pdf/page) 页面对象
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


获取包含注释的页面索引。

**退货：**
int - 整数值
### getPageIndex(Annotation annotation) {#getPageIndex-com.aspose.pdf.Annotation-}
```
public int getPageIndex(Annotation annotation)
```


获取包含注释的页面索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 注释对象 |

**退货：**
int - 整数值
### getPdfActions() {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```


获取注释操作列表。

**退货：**
[PdfActionCollection](../../com.aspose.pdf/pdfactioncollection) PdfActionCollection 实例
### getPopup() {#getPopup--}
```
public PopupAnnotation getPopup()
```


用于输入或编辑与此注释关联的文本的弹出式注释。

**退货：**
[PopupAnnotation](../../com.aspose.pdf/popupannotation) PopupAnnotation 值
### getRect() {#getRect--}
```
public Rectangle getRect()
```


获取注释矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getRectangle(boolean considerRotation) {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```


返回考虑页面旋转的注释矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| considerRotation | boolean | 如果为真，则考虑页面旋转。 |

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getReplyType() {#getReplyType--}
```
public int getReplyType()
```


一个字符串，指定此批注与 InReplyTo 指定的批注之间的关系（“回复类型”）。

**退货：**
int - 回复类型值
### getRichText() {#getRichText--}
```
public String getRichText()
```


获取打开注释时在弹出窗口中显示的富文本字符串。

**退货：**
java.lang.String - 字符串值
### getRotate() {#getRotate--}
```
public int getRotate()
```


注释旋转的角度。

**退货：**
int - 旋转元素
### getStartingStyle() {#getStartingStyle--}
```
public final int getStartingStyle()
```


获取或设置线结束点的线结束样式。 O此属性已过时，请使用 EndingStyle。

**退货：**
int - LineEnding 元素
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


获取标注的外观字典。

**退货：**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) AppearanceDictionary 对象
### getSubject() {#getSubject--}
```
public String getSubject()
```


获取表示对象说明的文本。

**退货：**
java.lang.String - 字符串值
### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public int getTextHorizontalAlignment()
```


获取注释的文本对齐方式。

**退货：**
int - 注释的文本对齐方式。
### getTextRectangle() {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```


描述两个矩形之间数值差异的矩形：注释的 Rect 条目和包含在该矩形内的矩形。内部矩形是注释的位置\\ufffds 文本应该被显示。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形实例
### getTextStyle() {#getTextStyle--}
```
public TextStyle getTextStyle()
```


获取或设置文本的外观样式。当文本样式更改时，文本外观也会更新。

**退货：**
[TextStyle](../../com.aspose.pdf/textstyle) - 文本样式值
### getTitle() {#getTitle--}
```
public String getTitle()
```


获取应显示在注释标题栏中的文本。

**退货：**
java.lang.String - 字符串值
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取段落的垂直对齐方式

**退货：**
int - VerticalAlignment 元素
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取注释的宽度。

**退货：**
double - double 值，注释的宽度。
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


获取一个 int 值，该值指示图形的 Z 顺序。具有较大 ZIndex 的图形将被放置在具有较小 ZIndex 的图形之上。 ZIndex 可以是负数。具有负 ZIndex 的图形将放置在页面中文本的后面。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### initialize(IDocument doc) {#initialize-com.aspose.pdf.IDocument-}
```
public void initialize(IDocument doc)
```


实例初始化

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象 |

### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


获取一个段落是内联的。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


获取强制此段落在新页面生成的 bool 值。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isUpdateAppearanceOnConvert() {#isUpdateAppearanceOnConvert--}
```
public static synchronized boolean isUpdateAppearanceOnConvert()
```


如果为真，注释外观将在将 PF 文档转换为图像之前更新。这允许正确转换字段，但可能需要更多时间。

**退货：**
boolean - 布尔值
### isUseFontSubset() {#isUseFontSubset--}
```
public static synchronized boolean isUseFontSubset()
```


如果此属性设置为 true，字体将作为子集添加到文档中。默认值为真。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setActiveState(String value) {#setActiveState-java.lang.String-}
```
public void setActiveState(String value)
```


设置当前注释外观状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


注释对齐。此属性已过时。使用 getHorizontalAlignment\_注解\_New 代替。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | TextAlignment 元素 |

### setBorder(Border value) {#setBorder-com.aspose.pdf.Border-}
```
public void setBorder(Border value)
```


设置注释边框特征。边界 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Border](../../com.aspose.pdf/border) | 边界值 |

### setCallout(Point[] value) {#setCallout-com.aspose.pdf.Point---}
```
public final void setCallout(Point[] value)
```


指定标注线的点数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) | 点数组 |

### setColor(Color value) {#setColor-com.aspose.pdf.Color-}
```
public void setColor(Color value)
```


设置注释颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 色值 |

### setContents(String value) {#setContents-java.lang.String-}
```
public void setContents(String value)
```


设置注释文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setDefaultAppearance(String value) {#setDefaultAppearance-java.lang.String-}
```
public void setDefaultAppearance(String value)
```


设置用于格式化文本的默认外观字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setDefaultStyle(String value) {#setDefaultStyle-java.lang.String-}
```
public void setDefaultStyle(String value)
```


设置默认样式字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setEndingStyle(int value) {#setEndingStyle-int-}
```
public void setEndingStyle(int value)
```


设置线结束点的线结束样式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 行结束值 |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


设置注释的标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 注释的标志 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


设置注释的高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 注释的高度 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置段落的水平对齐方式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setHorizontalAlignment_Annotation_New(int value) {#setHorizontalAlignment-Annotation-New-int-}
```
public final void setHorizontalAlignment_Annotation_New(int value)
```


获取或设置注释的文本对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 注释的文本对齐方式。 |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


设置超链接（用于 pdf 生成器）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | 超链接（用于 pdf 生成器）。 |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


设置一个段落是内联的。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


设置一个布尔值，强制此段落在新页面生成。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setInReplyTo(Annotation value) {#setInReplyTo-com.aspose.pdf.Annotation-}
```
public void setInReplyTo(Annotation value)
```


对该注释“回复”的注释的引用。两个注释必须在文档的同一页上。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Annotation](../../com.aspose.pdf/annotation) | 注释值 |

### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


设置自由文本注释的意图。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setJustification(int value) {#setJustification-int-}
```
public void setJustification(int value)
```


设置一个代码，指定要在显示注释文本时使用的四边形（对齐）形式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置段落的外边距（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setModified(Date value) {#setModified-java.util.Date-}
```
public void setModified(Date value)
```


设置最近修改注释的日期和时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期对象 |

### setModifiedInternal(System.DateTime value) {#setModifiedInternal-com.aspose.ms.System.DateTime-}
```
public void setModifiedInternal(System.DateTime value)
```


设置最近修改注释的日期和时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime | 日期时间对象 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


在页面上设置注释名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


设置用于绘制注释的常量不透明度值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setPopup(PopupAnnotation value) {#setPopup-com.aspose.pdf.PopupAnnotation-}
```
public void setPopup(PopupAnnotation value)
```


用于输入或编辑与此注释关联的文本的弹出式注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | PopupAnnotation值 |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


设置注释矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形值 |

### setReplyType(int value) {#setReplyType-int-}
```
public void setReplyType(int value)
```


一个字符串，指定此批注与 InReplyTo 指定的批注之间的关系（“回复类型”）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 回复类型值 |

### setRichText(String value) {#setRichText-java.lang.String-}
```
public void setRichText(String value)
```


设置打开注释时在弹出窗口中显示的富文本字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


注释旋转的角度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 旋转元素 |

### setStartingStyle(int value) {#setStartingStyle-int-}
```
public final void setStartingStyle(int value)
```


获取或设置线结束点的线结束样式。 O此属性已过时，请使用 EndingStyle。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 行尾元素 |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


设置表示对象描述的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public void setTextHorizontalAlignment(int value)
```


设置注释的文本对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 注释的文本对齐方式。 |

### setTextRectangle(Rectangle value) {#setTextRectangle-com.aspose.pdf.Rectangle-}
```
public final void setTextRectangle(Rectangle value)
```


描述两个矩形之间数值差异的矩形：注释的 Rect 条目和包含在该矩形内的矩形。内部矩形是注释的位置\\ufffds 文本应该被显示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形实例 |

### setTextStyle(TextStyle value) {#setTextStyle-com.aspose.pdf.TextStyle-}
```
public void setTextStyle(TextStyle value)
```


设置外观中文本的样式。当文本样式更改时，文本外观也会更新。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextStyle](../../com.aspose.pdf/textstyle) | TextStyle 对象 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


设置应显示在注释标题栏中的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setUpdateAppearanceOnConvert(boolean value) {#setUpdateAppearanceOnConvert-boolean-}
```
public static synchronized void setUpdateAppearanceOnConvert(boolean value)
```


如果为真，注释外观将在将 PF 文档转换为图像之前更新。这允许正确转换字段，但可能需要更多时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setUseFontSubset(boolean value) {#setUseFontSubset-boolean-}
```
public static synchronized void setUseFontSubset(boolean value)
```


如果此属性设置为 true，字体将作为子集添加到文档中。默认值为真。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


设置段落的垂直对齐方式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


设置注释的宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 注释的宽度。 |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


设置一个指示图形 Z 顺序的 int 值。具有较大 ZIndex 的图形将被放置在具有较小 ZIndex 的图形之上。 ZIndex 可以是负数。具有负 ZIndex 的图形将放置在页面中文本的后面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### updateAppearance() {#updateAppearance--}
```
public void updateAppearance()
```


在更改/移动文本后更新外观。

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
