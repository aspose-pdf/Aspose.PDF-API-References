---
title: DateField
second_title: 用于 Java API 参考的 Aspose.PDF
description: 带有日历视图的日期字段。
type: docs
weight: 81
url: /zh/java/com.aspose.pdf/datefield/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field), [com.aspose.pdf.TextBoxField](../../com.aspose.pdf/textboxfield)
```
public class DateField extends TextBoxField
```

带有日历视图的日期字段。

```
DateField dateField = new DateField(page, rect);
 doc.getForm().add(dateField);
 dateField.init(page);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DateField()](#DateField--) | 初始化一个新的实例[DateField](../../com.aspose.pdf/datefield) |
| [DateField(Document doc)](#DateField-com.aspose.pdf.Document-) | 应该与生成器一起使用的构造函数。 |
| [DateField(Page page, Rectangle rect)](#DateField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 初始化一个新的实例[DateField](../../com.aspose.pdf/datefield) |
| [DateField(Document doc, Rectangle rect)](#DateField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-) | 初始化一个新的实例[DateField](../../com.aspose.pdf/datefield) |
## 领域

| 场地 | 描述 |
| --- | --- |
| [_文件选择](#-FileSelect) | \_FileSelect |
| [_密码](#-Password) | \_Password |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | 接待来访者。 |
| [add(WidgetAnnotation item)](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [addBarcode(String code)](#addBarcode-java.lang.String-) | 将条码 128 添加到字段中。 |
| [addImage(BufferedImage image)](#addImage-java.awt.image.BufferedImage-) | 将图像添加到现场资源并绘制它。 |
| [addImage_DateField_New(BufferedImage image)](#addImage-DateField-New-java.awt.image.BufferedImage-) | 拒绝为此字段添加图像。 |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | 根据矩阵变换更新参数和外观。 |
| [clear()](#clear--) |  |
| [contains(WidgetAnnotation item)](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo(Field[] array, int index)](#copyTo-com.aspose.pdf.Field---int-) | 将此字段的子字段复制到从指定索引开始的数组中。 |
| [copyTo(WidgetAnnotation[] array, int arrayIndex)](#copyTo-com.aspose.pdf.WidgetAnnotation---int-) |  |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | 仅供内部使用 |
| [deepClone()](#deepClone--) | 克隆此实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | 删除此字段并将其值直接放在页面上。 |
| [getActiveState()](#getActiveState--) | 获取当前注释外观状态。 |
| [getAlignment()](#getAlignment--) | 注释对齐。 |
| [getAlternateName()](#getAlternateName--) | 获取字段的替代名称（在用户界面中标识字段的任何地方，应使用替代字段名称代替实际字段名称）。 |
| [getAnnotationActions()](#getAnnotationActions--) | 获取注解动作。 |
| [getAnnotationIndex()](#getAnnotationIndex--) | 获取此注释在页面上的索引。 |
| [getAnnotationType()](#getAnnotationType--) | 获取注解类型。 |
| [getAppearance()](#getAppearance--) | 获取注解的外观字典。 |
| [getBorder()](#getBorder--) | 获取注释边框特征。 |
| [getCharacteristics()](#getCharacteristics--) | 获取注解特征。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取注释颜色。 |
| [getContents()](#getContents--) | 获取注释文本。 |
| [getDateFormat()](#getDateFormat--) | 获取或设置日期格式。 |
| [getDefaultAppearance()](#getDefaultAppearance--) | 获取字段的默认外观。 |
| [getEngineDict()](#getEngineDict--) | 仅限内部 |
| [getEngineObj()](#getEngineObj--) | 仅供内部使用 |
| [getExportable()](#getExportable--) | 获取字段的可导出标志。 |
| [getFlags()](#getFlags--) | 获取注释的标志。 |
| [getForceCombs()](#getForceCombs--) | 获取指示字段被划分为间隔位置的标志。 |
| [getFullName()](#getFullName--) | 获取注释的完整限定名称。 |
| [getHeight()](#getHeight--) | 获取注释的高度。 |
| [getHighlighting()](#getHighlighting--) | 注释突出显示模式。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | 获取或设置注释的文本对齐方式。 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getMappingName()](#getMappingName--) | 获取从文档中导出交互式表单字段数据时应使用的字段的映射名称。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getMaxFontSize()](#getMaxFontSize--) | 可用于字段内容的最大字体大小。 -1 不检查大小。 |
| [getMaxLen()](#getMaxLen--) | 获取字段中文本的最大长度。 |
| [getMinFontSize()](#getMinFontSize--) | 可用于字段内容的最小字体大小。 -1 不检查大小。 |
| [getModified()](#getModified--) | 获取最近修改注释的日期和时间。 |
| [getModifiedInternal()](#getModifiedInternal--) | 获取最近修改注释的日期和时间。 |
| [getMultiline()](#getMultiline--) | 获取字段的多行标志。 |
| [getName()](#getName--) | 获取页面上的注释名称。 |
| [getNormalAppearance()](#getNormalAppearance--) | 获得正常外观。 |
| [getOnActivated()](#getOnActivated--) | 获取激活注释时应执行的操作。 |
| [getPage()](#getPage--) | 获取与此注释关联的页面对象。 |
| [getPageIndex()](#getPageIndex--) | 获取包含该字段的页面的索引。 |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) | 获取包含注释的页面索引。 |
| [getParent()](#getParent--) | 获取注解父级。 |
| [getPartialName()](#getPartialName--) | 获取字段的部分名称。 |
| [getPdfActions()](#getPdfActions--) | 获取注释操作列表。 |
| [getReadOnly()](#getReadOnly--) | 获取字段的只读状态。 |
| [getRect()](#getRect--) | 获取字段矩形。 |
| [getRectangle(boolean considerRotation)](#getRectangle-boolean-) | 返回考虑页面旋转的注释矩形。 |
| [getRequired()](#getRequired--) | 获取字段的必需状态。 |
| [getScrollable()](#getScrollable--) | 获取字段的可滚动标志。 |
| [getSpellCheck()](#getSpellCheck--) | 获取字段的拼写检查标志。 |
| [getStates()](#getStates--) | 获取标注的外观字典。 |
| [getSyncRoot()](#getSyncRoot--) | 同步对象。 |
| [getTabOrder()](#getTabOrder--) | 获取或设置字段的 Tab 键顺序。 |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | 获取注释的文本对齐方式。 |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | 获取或设置注释的文本垂直对齐方式。 |
| [getValue()](#getValue--) | 获取字段的值。 |
| [getValue_DateField_New()](#getValue-DateField-New--) | 获取或设置日期。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getWidth()](#getWidth--) | 获取注释的宽度。 |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [get_Item(int index)](#get-Item-int-) | 通过索引获取该字段中包含的子字段。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 通过子字段的名称获取此字段中包含的子字段。 |
| [hashCode()](#hashCode--) |  |
| [init(Page page)](#init-com.aspose.pdf.Page-) | 初始化 JS 动作。 |
| [initialize(IDocument doc)](#initialize-com.aspose.pdf.IDocument-) | 实例初始化 |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isFitIntoRectangle()](#isFitIntoRectangle--) | 如果为真，则字体大小将减小以适合指定矩形的文本。 |
| [isGroup()](#isGroup--) | 获取布尔值，指示该字段是非终端字段，即字段组。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [isReadOnly()](#isReadOnly--) |  |
| [isSharedField()](#isSharedField--) | 生成器支持的属性。 |
| [isSynchronized()](#isSynchronized--) | 如果字典已同步，则返回 true。 |
| [isUpdateAppearanceOnConvert()](#isUpdateAppearanceOnConvert--) | 如果为真，注释外观将在将 PF 文档转换为图像之前更新。 |
| [isUseFontSubset()](#isUseFontSubset--) | 如果此属性设置为 true，字体将作为子集添加到文档中。 |
| [iterator()](#iterator--) | 返回包含字段的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recalculate()](#recalculate--) | 重新计算表单上的所有计算字段。 |
| [remove(WidgetAnnotation item)](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | 设置当前注释外观状态。 |
| [setAlignment(int value)](#setAlignment-int-) | 注释对齐。 |
| [setAlternateName(String value)](#setAlternateName-java.lang.String-) | 设置字段的替代名称（在用户界面中标识字段的任何地方，应使用替代字段名称代替实际字段名称）。 |
| [setAnnotationIndex(int value)](#setAnnotationIndex-int-) | 在页面上设置此注释的索引。 |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | 设置注释边框特征。 |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | 设置注释颜色。 |
| [setContents(String value)](#setContents-java.lang.String-) | 设置注释文本。 |
| [setDateFormat(String value)](#setDateFormat-java.lang.String-) | 获取或设置日期格式。 |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | 设置字段的默认外观。 |
| [setExportable(boolean value)](#setExportable-boolean-) | 设置字段的只读状态。 |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setFitIntoRectangle(boolean value)](#setFitIntoRectangle-boolean-) | 如果为真，则字体大小将减小以适合指定矩形的文本。 |
| [setFlags(int value)](#setFlags-int-) | 设置注释的标志。 |
| [setForceCombs(boolean value)](#setForceCombs-boolean-) | 设置标志，指示字段被划分为间隔位置。 |
| [setHeight(double value)](#setHeight-double-) | 设置注释的高度。 |
| [setHighlighting(int value)](#setHighlighting-int-) | 注释突出显示模式。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落的水平对齐方式 |
| [setHorizontalAlignment_Annotation_New(int value)](#setHorizontalAlignment-Annotation-New-int-) | 获取或设置注释的文本对齐方式。 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setJustification(boolean value)](#setJustification-boolean-) | 设置理由 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setMappingName(String value)](#setMappingName-java.lang.String-) | 设置从文档中导出交互式表单字段数据时应使用的字段的映射名称。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setMaxFontSize(double value)](#setMaxFontSize-double-) | 可用于字段内容的最大字体大小。 -1 不检查大小。 |
| [setMaxLen(int value)](#setMaxLen-int-) | 设置字段中文本的最大长度。 |
| [setMinFontSize(double value)](#setMinFontSize-double-) | 可用于字段内容的最小字体大小。 -1 不检查大小。 |
| [setModified(Date value)](#setModified-java.util.Date-) | 设置最近修改注释的日期和时间。 |
| [setModifiedInternal(System.DateTime value)](#setModifiedInternal-com.aspose.ms.System.DateTime-) | 设置最近修改注释的日期和时间。 |
| [setMultiline(boolean value)](#setMultiline-boolean-) | 设置字段的多行标志。 |
| [setName(String value)](#setName-java.lang.String-) | 在页面上设置注释名称。 |
| [setOnActivated(PdfAction value)](#setOnActivated-com.aspose.pdf.PdfAction-) | 设置激活注释时应执行的操作。 |
| [setPartialName(String value)](#setPartialName-java.lang.String-) | 设置字段的部分名称。 |
| [setPosition(Point point)](#setPosition-com.aspose.pdf.Point-) | 设置字段的位置。 |
| [setReadOnly(boolean value)](#setReadOnly-boolean-) | 设置字段的只读状态。 |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | 设置字段矩形。 |
| [setRequired(boolean value)](#setRequired-boolean-) | 设置字段的只读状态。 |
| [setScrollable(boolean value)](#setScrollable-boolean-) | 设置字段的可滚动标志。 |
| [setSharedField(boolean value)](#setSharedField-boolean-) | 生成器支持的属性。 |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | 为字段设置拼写检查标志。 |
| [setTabOrder(int value)](#setTabOrder-int-) | 获取或设置字段的 Tab 键顺序。 |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | 设置注释的文本对齐方式。 |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | 获取或设置注释的文本垂直对齐方式。 |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | 如果为真，注释外观将在将 PF 文档转换为图像之前更新。 |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | 如果此属性设置为 true，字体将作为子集添加到文档中。 |
| [setValue(String value)](#setValue-java.lang.String-) | 设置字段的值。 |
| [setValue_DateField_New(Date value)](#setValue-DateField-New-java.util.Date-) | 获取或设置日期。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置段落的垂直对齐方式 |
| [setWidth(double value)](#setWidth-double-) | 设置注释的宽度。 |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [size()](#size--) | 获取此字段中的子字段数。 |
| [toString()](#toString--) |  |
| [updateAppearances()](#updateAppearances--) | 更新外观值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateField() {#DateField--}
```
public DateField()
```


初始化一个新的实例[DateField](../../com.aspose.pdf/datefield)

### DateField(Document doc) {#DateField-com.aspose.pdf.Document-}
```
public DateField(Document doc)
```


应该与生成器一起使用的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | 将在其中创建字段的文档。 |

### DateField(Page page, Rectangle rect) {#DateField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public DateField(Page page, Rectangle rect)
```


初始化一个新的实例[DateField](../../com.aspose.pdf/datefield)

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 创建所需的页面。 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 文本字段将放置在页面上的矩形。 |

### DateField(Document doc, Rectangle rect) {#DateField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-}
```
public DateField(Document doc, Rectangle rect)
```


初始化一个新的实例[DateField](../../com.aspose.pdf/datefield)

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | 将在其中创建字段的文档。 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 场地的矩形。 |

### _FileSelect {#-FileSelect}
```
public static final int _FileSelect
```


\_文件选择

### _Password {#-Password}
```
public static final int _Password
```


\_密码

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


接待来访者。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | 接待来访者。 |

### add(WidgetAnnotation item) {#add-com.aspose.pdf.WidgetAnnotation-}
```
public void add(WidgetAnnotation item)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

### addBarcode(String code) {#addBarcode-java.lang.String-}
```
public void addBarcode(String code)
```


将条码 128 添加到字段中。字段值将更改为代码，字段变为只读。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| code | java.lang.String | 生成条形码 128 的文本。 |

### addImage(BufferedImage image) {#addImage-java.awt.image.BufferedImage-}
```
public void addImage(BufferedImage image)
```


将图像添加到现场资源并绘制它。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | 要添加到文本字段中的图像。 |

### addImage_DateField_New(BufferedImage image) {#addImage-DateField-New-java.awt.image.BufferedImage-}
```
public final void addImage_DateField_New(BufferedImage image)
```


拒绝为此字段添加图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | 图片。 |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


根据矩阵变换更新参数和外观。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | 用于转换（调整大小）的矩阵。 |

### clear() {#clear--}
```
public void clear()
```




### contains(WidgetAnnotation item) {#contains-com.aspose.pdf.WidgetAnnotation-}
```
public boolean contains(WidgetAnnotation item)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

**退货：**
布尔值
### copyTo(Field[] array, int index) {#copyTo-com.aspose.pdf.Field---int-}
```
public void copyTo(Field[] array, int index)
```


将此字段的子字段复制到从指定索引开始的数组中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [Field\[\]](../../com.aspose.pdf/field) | 必须复制字段的数组。 |
| index | int | 将复制字段的起始索引。 |

### copyTo(WidgetAnnotation[] array, int arrayIndex) {#copyTo-com.aspose.pdf.WidgetAnnotation---int-}
```
public void copyTo(WidgetAnnotation[] array, int arrayIndex)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [WidgetAnnotation\[\]](../../com.aspose.pdf/widgetannotation) |  |
| arrayIndex | int |  |

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


删除此字段并将其值直接放在页面上。

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
### getAlternateName() {#getAlternateName--}
```
public String getAlternateName()
```


获取字段的替代名称（在用户界面中标识字段的任何地方，应使用替代字段名称代替实际字段名称）。别名在 Adobe Acrobat 中用作字段工具提示。

**退货：**
java.lang.String - 字符串值
### getAnnotationActions() {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```


获取注解动作。

**退货：**
[AnnotationActionCollection](../../com.aspose.pdf/annotationactioncollection) - AnnotationActionCollection 对象
### getAnnotationIndex() {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```


获取此注释在页面上的索引。

**退货：**
int - 整数值
### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


获取注解类型。

**退货：**
int - AnnotationType 元素
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
### getDateFormat() {#getDateFormat--}
```
public final String getDateFormat()
```


获取或设置日期格式。

值：日期格式。默认 dd/MM/yyyy

**退货：**
java.lang.String - 字符串值
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


获取字段的默认外观。

**退货：**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) 默认外观对象
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
### getExportable() {#getExportable--}
```
public boolean getExportable()
```


获取字段的可导出标志。

**退货：**
boolean - 布尔值
### getFlags() {#getFlags--}
```
public int getFlags()
```


获取注释的标志。

**退货：**
int - 注释的标志
### getForceCombs() {#getForceCombs--}
```
public boolean getForceCombs()
```


获取指示字段被划分为间隔位置的标志。

**退货：**
boolean - 布尔值
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
### getHighlighting() {#getHighlighting--}
```
public int getHighlighting()
```


注释突出显示模式。

**退货：**
int - HighlightingMode 值
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
### getMappingName() {#getMappingName--}
```
public String getMappingName()
```


获取从文档中导出交互式表单字段数据时应使用的字段的映射名称。

**退货：**
java.lang.String - 字符串值
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取段落的外边距（用于生成 pdf）

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getMaxFontSize() {#getMaxFontSize--}
```
public static synchronized double getMaxFontSize()
```


可用于字段内容的最大字体大小。 -1 不检查大小。

**退货：**
双倍价值
### getMaxLen() {#getMaxLen--}
```
public int getMaxLen()
```


获取字段中文本的最大长度。

**退货：**
int - 整数值
### getMinFontSize() {#getMinFontSize--}
```
public static double getMinFontSize()
```


可用于字段内容的最小字体大小。 -1 不检查大小。

**退货：**
双倍价值
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
### getMultiline() {#getMultiline--}
```
public boolean getMultiline()
```


获取字段的多行标志。如果 Multiline 为真，字段可以包含多行文本。

**退货：**
boolean - 布尔值
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
### getOnActivated() {#getOnActivated--}
```
public PdfAction getOnActivated()
```


获取激活注释时应执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
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


获取包含该字段的页面的索引。

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
### getParent() {#getParent--}
```
public Field getParent()
```


获取注解父级。

**退货：**
[Field](../../com.aspose.pdf/field) - 字段对象
### getPartialName() {#getPartialName--}
```
public String getPartialName()
```


获取字段的部分名称。

**退货：**
java.lang.String - 字符串值
### getPdfActions() {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```


获取注释操作列表。

**退货：**
[PdfActionCollection](../../com.aspose.pdf/pdfactioncollection) PdfActionCollection 实例
### getReadOnly() {#getReadOnly--}
```
public boolean getReadOnly()
```


获取字段的只读状态。

**退货：**
boolean - 布尔值
### getRect() {#getRect--}
```
public Rectangle getRect()
```


获取字段矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 场地矩形。
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
### getRequired() {#getRequired--}
```
public boolean getRequired()
```


获取字段的必需状态。

**退货：**
boolean - 布尔值
### getScrollable() {#getScrollable--}
```
public boolean getScrollable()
```


获取字段的可滚动标志。如果 true 字段可以滚动。

**退货：**
boolean - 布尔值
### getSpellCheck() {#getSpellCheck--}
```
public boolean getSpellCheck()
```


获取字段的拼写检查标志。如果 true 字段应进行拼写检查。

**退货：**
boolean - 布尔值
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


获取标注的外观字典。

**退货：**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) AppearanceDictionary 对象
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


同步对象。

**退货：**
java.lang.Object - 对象值
### getTabOrder() {#getTabOrder--}
```
public int getTabOrder()
```


获取或设置字段的 Tab 键顺序。

**退货：**
int - 整数值
### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public int getTextHorizontalAlignment()
```


获取注释的文本对齐方式。

**退货：**
int - 注释的文本对齐方式。
### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


获取或设置注释的文本垂直对齐方式。

**退货：**
int - VerticalAlignment 元素
### getValue() {#getValue--}
```
public String getValue()
```


获取字段的值。

**退货：**
java.lang.String - 字符串值
### getValue_DateField_New() {#getValue-DateField-New--}
```
public final Date getValue_DateField_New()
```


获取或设置日期。

**退货：**
[Date](../../java.util/date) - java.util.Date 实例
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
### get_Item(int index) {#get-Item-int-}
```
public WidgetAnnotation get_Item(int index)
```


通过索引获取该字段中包含的子字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 请求子字段的索引。 |

**退货：**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - 字段实例。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public WidgetAnnotation get_Item(String name)
```


通过子字段的名称获取此字段中包含的子字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 包含的子字段名称。 |

**退货：**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - 字段实例。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### init(Page page) {#init-com.aspose.pdf.Page-}
```
public final void init(Page page)
```


初始化 JS 动作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 这页纸。 |

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
### isFitIntoRectangle() {#isFitIntoRectangle--}
```
public static synchronized boolean isFitIntoRectangle()
```


如果为真，则字体大小将减小以适合指定矩形的文本。

**退货：**
boolean - 布尔值
### isGroup() {#isGroup--}
```
public boolean isGroup()
```


获取布尔值，指示该字段是非终端字段，即字段组。

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
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**退货：**
布尔值
### isSharedField() {#isSharedField--}
```
public boolean isSharedField()
```


生成器支持的属性。在将字段添加到页眉或页脚时使用。如果为 true，该字段将创建一次，并且它的外观将在文档的所有页面上可见。如果为 false，将为每个文档页面创建单独的字段。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


如果字典已同步，则返回 true。

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
### iterator() {#iterator--}
```
public Iterator<WidgetAnnotation> iterator()
```


返回包含字段的枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.WidgetAnnotation> - 枚举器对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### recalculate() {#recalculate--}
```
public boolean recalculate()
```


重新计算表单上的所有计算字段。

**退货：**
boolean - 如果在重新计算期间更改了字段值，则为 true。
### remove(WidgetAnnotation item) {#remove-com.aspose.pdf.WidgetAnnotation-}
```
public boolean remove(WidgetAnnotation item)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

**退货：**
布尔值
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

### setAlternateName(String value) {#setAlternateName-java.lang.String-}
```
public void setAlternateName(String value)
```


设置字段的替代名称（在用户界面中标识字段的任何地方，应使用替代字段名称代替实际字段名称）。别名在 Adobe Acrobat 中用作字段工具提示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setAnnotationIndex(int value) {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```


在页面上设置此注释的索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setBorder(Border value) {#setBorder-com.aspose.pdf.Border-}
```
public void setBorder(Border value)
```


设置注释边框特征。边界 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Border](../../com.aspose.pdf/border) | 边界值 |

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

### setDateFormat(String value) {#setDateFormat-java.lang.String-}
```
public final void setDateFormat(String value)
```


获取或设置日期格式。

值：日期格式。默认 dd/MM/yyyy

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


设置字段的默认外观。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | DefaultAppearance 对象 |

### setExportable(boolean value) {#setExportable-boolean-}
```
public void setExportable(boolean value)
```


设置字段的只读状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFitIntoRectangle(boolean value) {#setFitIntoRectangle-boolean-}
```
public static synchronized void setFitIntoRectangle(boolean value)
```


如果为真，则字体大小将减小以适合指定矩形的文本。

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

### setForceCombs(boolean value) {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```


设置标志，指示字段被划分为间隔位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


设置注释的高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 注释的高度 |

### setHighlighting(int value) {#setHighlighting-int-}
```
public void setHighlighting(int value)
```


注释突出显示模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HighlightingMode 值 |

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

### setJustification(boolean value) {#setJustification-boolean-}
```
public void setJustification(boolean value)
```


设置理由

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMappingName(String value) {#setMappingName-java.lang.String-}
```
public void setMappingName(String value)
```


设置从文档中导出交互式表单字段数据时应使用的字段的映射名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置段落的外边距（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setMaxFontSize(double value) {#setMaxFontSize-double-}
```
public static synchronized void setMaxFontSize(double value)
```


可用于字段内容的最大字体大小。 -1 不检查大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setMaxLen(int value) {#setMaxLen-int-}
```
public void setMaxLen(int value)
```


设置字段中文本的最大长度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setMinFontSize(double value) {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```


可用于字段内容的最小字体大小。 -1 不检查大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

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

### setMultiline(boolean value) {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```


设置字段的多行标志。如果 Multiline 为真，字段可以包含多行文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


在页面上设置注释名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setOnActivated(PdfAction value) {#setOnActivated-com.aspose.pdf.PdfAction-}
```
public void setOnActivated(PdfAction value)
```


设置激活注释时应执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setPartialName(String value) {#setPartialName-java.lang.String-}
```
public void setPartialName(String value)
```


设置字段的部分名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setPosition(Point point) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point point)
```


设置字段的位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) | 应放置字段的点。 |

### setReadOnly(boolean value) {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```


设置字段的只读状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


设置字段矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 字段矩形。 |

### setRequired(boolean value) {#setRequired-boolean-}
```
public void setRequired(boolean value)
```


设置字段的只读状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setScrollable(boolean value) {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```


设置字段的可滚动标志。如果 true 字段可以滚动。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSharedField(boolean value) {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```


生成器支持的属性。在将字段添加到页眉或页脚时使用。如果为 true，该字段将创建一次，并且它的外观将在文档的所有页面上可见。如果为 false，将为每个文档页面创建单独的字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```


为字段设置拼写检查标志。如果 true 字段应进行拼写检查。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setTabOrder(int value) {#setTabOrder-int-}
```
public void setTabOrder(int value)
```


获取或设置字段的 Tab 键顺序。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public void setTextHorizontalAlignment(int value)
```


设置注释的文本对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 注释的文本对齐方式。 |

### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


获取或设置注释的文本垂直对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

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

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


设置字段的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setValue_DateField_New(Date value) {#setValue-DateField-New-java.util.Date-}
```
public final void setValue_DateField_New(Date value)
```


获取或设置日期。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | java.util.Date 实例 |

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

### size() {#size--}
```
public int size()
```


获取此字段中的子字段数。 （例如单选按钮字段中的项目数）。

**退货：**
int - 整数值
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### updateAppearances() {#updateAppearances--}
```
public void updateAppearances()
```


更新外观值。

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
