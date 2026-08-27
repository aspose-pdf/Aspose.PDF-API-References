---
title: "注释"
linktitle: "注释"
second_title: "Aspose.PDF for Java API 参考"
description: "表示注释对象的类。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

表示注释对象的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受用于注释处理的访问者。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 根据矩阵变换更新参数和外观。 |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | 仅供内部使用 |
| [flatten](#flatten--) | 将注释内容直接放置在页面上，注释对象将被移除。 |
| [getActiveState](#getActiveState--) | 获取当前注释外观状态。 |
| [getAlignment](#getAlignment--) | ff / * / * 根据现有状态名称返回 "checked" 状态的名称。 / * / * / * |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getAppearance](#getAppearance--) | 获取注释的外观字典。 |
| [getAssignedPageIndex](#getAssignedPageIndex--) | 获取注释应出现的页面索引（基于1的索引）。 |
| [getBorder](#getBorder--) | 获取注释边框特性。 {@code Border} |
| [getCharacteristics](#getCharacteristics--) | 获取注释特性。 |
| [getColor](#getColor--) | 获取注释颜色。 |
| [getContents](#getContents--) | 获取注释文本。 |
| [getEngineDict](#getEngineDict--) | 仅内部使用 |
| [getEngineObj](#getEngineObj--) | 仅供内部使用 |
| [getFlags](#getFlags--) | 获取注释的标志。 |
| [getFullName](#getFullName--) | 获取注释的完全限定名称。 |
| [getHeight](#getHeight--) | 获取注释的高度。 |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | 获取或设置注释的文本对齐方式。 |
| [getModified](#getModified--) | 获取注释最近修改的日期和时间。 |
| [getModifiedInternal](#getModifiedInternal--) | 获取注释最近修改的日期和时间。 |
| [getName](#getName--) | 获取页面上注释的名称。 |
| [getNormalAppearance](#getNormalAppearance--) | 获取正常外观。 |
| [getPage](#getPage--) | 获取与此注释关联的页面对象。 |
| [getPageIndex](#getPageIndex--) | 获取包含注释的页面索引。 |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | 获取包含注释的页面索引。 |
| [getPdfActions](#getPdfActions--) | 获取注释操作的列表。 |
| [getRect](#getRect--) | 获取注释矩形。 |
| [getRectangle](#getRectangle-boolean-) | 返回考虑页面旋转后的注释矩形。 |
| [getStates](#getStates--) | 获取注释的外观字典。 |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | 获取注释的文本对齐方式。 |
| [getWidth](#getWidth--) | 获取注释的宽度。 |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | 实例初始化 |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | 如果为 true，注释外观将在将 PDF 文档转换为图像之前更新。这可以正确转换字段，但可能需要更多时间。 |
| [isUseFontSubset](#isUseFontSubset--) | 如果此属性设置为 true，字体将以子集形式添加到文档中。默认值为 true。 |
| [setActiveState](#setActiveState-java.lang.String-) | 设置当前注释的外观状态。 |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | 注释对齐。此属性已过时。请改用 getHorizontalAlignment_Annotation_New。 |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | 设置注释应出现的页面索引（从 1 开始）。 |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | 设置注释边框特性。 {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | 设置注释颜色。 |
| [setContents](#setContents-java.lang.String-) | 设置注释文本。 |
| [setFlags](#setFlags-int-) | 设置注释的标志。 |
| [setHeight](#setHeight-double-) | 设置注释的高度。 |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | 获取或设置注释的文本对齐方式。 |
| [setModified](#setModified-java.util.Date-) | 设置注释最近修改的日期和时间。 |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | 设置注释最近修改的日期和时间。 |
| [setName](#setName-java.lang.String-) | 设置页面上注释的名称。 |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | 设置注释矩形。 |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置注释的文本对齐方式。 |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | 如果为 true，注释外观将在将 PDF 文档转换为图像之前更新。这可以正确转换字段，但可能需要更多时间。 |
| [setUseFontSubset](#setUseFontSubset-boolean-) | 如果此属性设置为 true，字体将以子集形式添加到文档中。默认值为 true。 |
| [setWidth](#setWidth-double-) | 设置注释的宽度。 |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受用于注释处理的访问者。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
根据矩阵变换更新参数和外观。

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
仅供内部使用

### flatten {#flatten--}
```
public void flatten()
```

将注释内容直接放置在页面上，注释对象将被移除。

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

获取当前注释外观状态。

**Returns:**
字符串值

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * 根据现有状态名称返回 "checked" 状态的名称。 / * / * / *

**Returns:**
字符串值 /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
整数值 @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

获取注释的外观字典。

**Returns:**
AppearanceDictionary 对象

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

获取注释应出现的页面索引（基于1的索引）。

**Returns:**
注释应出现的页面索引（从 1 开始）。

### getBorder {#getBorder--}
```
public Border getBorder()
```

获取注释边框特性。 {@code Border}

**Returns:**
Border 对象

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

获取注释特性。

**Returns:**
Characteristics 对象

### getColor {#getColor--}
```
public Color getColor()
```

获取注释颜色。

**Returns:**
Color 对象

### getContents {#getContents--}
```
public String getContents()
```

获取注释文本。

**Returns:**
字符串值

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

仅内部使用

**Returns:**
IPdfDictionary 对象

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

仅供内部使用

**Returns:**
内部对象

### getFlags {#getFlags--}
```
public int getFlags()
```

获取注释的标志。

**Returns:**
注释的标志 @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

获取注释的完全限定名称。

**Returns:**
字符串值

### getHeight {#getHeight--}
```
public double getHeight()
```

获取注释的高度。

**Returns:**
注释的高度

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

获取或设置注释的文本对齐方式。

**Returns:**
注释的文本对齐方式。@see HorizontalAlignment @deprecated 使用 TextHorizontalAlignment 属性

### getModified {#getModified--}
```
public Date getModified()
```

获取注释最近修改的日期和时间。

**Returns:**
注释最近修改的日期和时间。

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

获取注释最近修改的日期和时间。

**Returns:**
DateTime 对象

### getName {#getName--}
```
public String getName()
```

获取页面上注释的名称。

**Returns:**
字符串值

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

获取正常外观。

**Returns:**
XForm 对象

### getPage {#getPage--}
```
public Page getPage()
```

获取与此注释关联的页面对象。

**Returns:**
Page 对象

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

获取包含注释的页面索引。

**Returns:**
int 值

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
获取包含注释的页面索引。

**Returns:**
int 值

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

获取注释操作的列表。

**Returns:**
PdfActionCollection 实例

### getRect {#getRect--}
```
public Rectangle getRect()
```

获取注释矩形。

**Returns:**
Rectangle 对象

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

返回考虑页面旋转后的注释矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| considerRotation |  | 如果为 true，则会考虑页面旋转。 |

**Returns:**
Rectangle 对象

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

获取注释的外观字典。

**Returns:**
AppearanceDictionary 对象

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

获取注释的文本对齐方式。

**Returns:**
注释的文本对齐方式。@see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

获取注释的宽度。

**Returns:**
双精度值，注释的宽度。

### initialize {#initialize-com.aspose.pdf.IDocument-}
实例初始化

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

如果为 true，注释外观将在将 PDF 文档转换为图像之前更新。这可以正确转换字段，但可能需要更多时间。

**Returns:**
布尔值

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

如果此属性设置为 true，字体将以子集形式添加到文档中。默认值为 true。

**Returns:**
布尔值

### setActiveState {#setActiveState-java.lang.String-}
设置当前注释的外观状态。

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
注释对齐。此属性已过时。请改用 getHorizontalAlignment_Annotation_New。

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
设置注释应出现的页面索引（从 1 开始）。

### setBorder {#setBorder-com.aspose.pdf.Border-}
设置注释边框特性。 {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
设置注释颜色。

### setContents {#setContents-java.lang.String-}
设置注释文本。

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

设置注释的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 注释的标志 @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

设置注释的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 注释的高度 |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
获取或设置注释的文本对齐方式。

### setModified {#setModified-java.util.Date-}
设置注释最近修改的日期和时间。

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
设置注释最近修改的日期和时间。

### setName {#setName-java.lang.String-}
设置页面上注释的名称。

### setRect {#setRect-com.aspose.pdf.Rectangle-}
设置注释矩形。

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
设置注释的文本对齐方式。

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

如果为 true，注释外观将在将 PDF 文档转换为图像之前更新。这可以正确转换字段，但可能需要更多时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

如果此属性设置为 true，字体将以子集形式添加到文档中。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置注释的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 注释的宽度。 |
