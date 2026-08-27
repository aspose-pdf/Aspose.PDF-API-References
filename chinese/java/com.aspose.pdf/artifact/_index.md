---
title: "Artifact"
linktitle: "Artifact"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF Artifact 对象的类。"
type: docs
weight: 190
url: /zh/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

表示 PDF Artifact 对象的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | 具有指定类型和子类型的 Artifact 构造函数 |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | 当从页面读取 Artifact 时使用此构造函数。 |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | 具有指定类型和子类型的 Artifact 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [beginUpdates](#beginUpdates--) | 开始已删除的更新。若需要对同一 Artifact 进行多次更改以提升性能，请使用此功能。通常在每次更改 Artifact 属性时，Artifact 操作器都会被修改，这会导致每次更改 Artifact 时页面内容都被重新写入。为避免此效果，请将所有 Artifact 更新放在 StartUpdates/SaveUpdates 调用之间。这样只会更改页面内容一次。Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | 关闭此文档使用的所有资源。 |
| [dispose](#dispose--) | 释放该工件。此方法已过时，请改用 close()。 |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | 获取工件的水平对齐方式。如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | 获取工件的垂直对齐方式。如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| [getBottomMargin](#getBottomMargin--) | 获取工件的底部边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| [getContents](#getContents--) | 获取工件内部操作符的集合。 |
| [getCustomSubtype](#getCustomSubtype--) | 获取工件子类型的名称。如果工件子类型不是标准子类型，可使用此属性。 |
| [getCustomType](#getCustomType--) | 获取工件类型的名称。如果工件类型非标准，可使用此属性。 |
| [getForm](#getForm--) | 获取工件的 XForm（如果使用了 XForm）。 |
| [getImage](#getImage--) | 获取工件的图像（如果存在）。 |
| [getLeftMargin](#getLeftMargin--) | 获取工件的左侧边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| [getLines](#getLines--) | 多行文本工件的行。 |
| [getOpacity](#getOpacity--) | 获取工件的不透明度。可能的取值范围为 0..1。 |
| [getPosition](#getPosition--) | 获取工件的位置。如果指定了此属性，则边距和对齐方式将被忽略。 |
| [getRectangle](#getRectangle--) | 获取工件的矩形。 |
| [getRightMargin](#getRightMargin--) | 获取工件的右侧边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| [getRotation](#getRotation--) | 获取工件的旋转角度。 |
| [getSubtype](#getSubtype--) | 获取工件子类型。如果工件具有非标准子类型，可通过 CustomSubtype 读取子类型名称。 |
| [getText](#getText--) | 获取工件的文本。 |
| [getTextState](#getTextState--) | 工件文本的文本状态。 |
| [getTopMargin](#getTopMargin--) | 获取工件的顶部边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| [getType](#getType--) | 获取工件类型。 |
| [getValue](#getValue-java.lang.String-) | 获取工件的自定义值。 |
| [isBackground](#isBackground--) | 如果为 true，工件将放置在页面内容后面。 |
| [removeValue](#removeValue-java.lang.String-) | 从工件中移除自定义值。 |
| [saveUpdates](#saveUpdates--) | 在调用 BeginUpdates() 之后，对工件所做的所有更新都会被保存。 |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 获取工件的水平对齐方式。 |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 设置工件的垂直对齐方式。 |
| [setBackground](#setBackground-boolean-) | 如果为 true，工件将放置在页面内容后面。 |
| [setBottomMargin](#setBottomMargin-double-) | 设置工件的底部边距。 |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | 设置工件类型的名称。如果工件类型为非标准类型，可使用此属性。 |
| [setImage](#setImage-java.io.InputStream-) | 设置工件的图像。 |
| [setImage](#setImage-java.lang.String-) | 设置工件的图像。 |
| [setLeftMargin](#setLeftMargin-double-) | 设置工件的左侧边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | 设置工件的文本及其属性。允许指定多行。 |
| [setOpacity](#setOpacity-double-) | 设置工件的不透明度。可能的取值范围为 0..1。 |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | 设置将被页码替换的字符串。默认值为 #。 |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | 设置作为工件放置在文档页上的 PDF 页面。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | 设置工件的位置。 |
| [setRightMargin](#setRightMargin-double-) | 设置工件的右侧边距。 |
| [setRotation](#setRotation-double-) | 设置工件的旋转角度。 |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | 设置工件的子类型。 |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | 设置工件的文本。 |
| [setText](#setText-java.lang.String-) | 设置工件的文本。 |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | 设置工件的文本及其属性。 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | 工件文本的文本状态。 |
| [setTopMargin](#setTopMargin-double-) | 设置工件的顶部边距。 |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | 设置工件类型。 |
| [setValue](#setValue-java.lang.String-java.lang.String-) | 设置工件的自定义值。 |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
具有指定类型和子类型的 Artifact 构造函数

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
当从页面读取 Artifact 时使用此构造函数。

### Artifact {#Artifact-java.lang.String-java.lang.String-}
具有指定类型和子类型的 Artifact 构造函数

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

开始已删除的更新。若需要对同一 Artifact 进行多次更改以提升性能，请使用此功能。通常在每次更改 Artifact 属性时，Artifact 操作器都会被修改，这会导致每次更改 Artifact 时页面内容都被重新写入。为避免此效果，请将所有 Artifact 更新放在 StartUpdates/SaveUpdates 调用之间。这样只会更改页面内容一次。Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

关闭此文档使用的所有资源。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

释放该工件。此方法已过时，请改用 close()。

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

获取工件的水平对齐方式。如果在 Position 属性中显式指定了位置，则此值将被忽略。

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

获取工件的垂直对齐方式。如果在 Position 属性中显式指定了位置，则此值将被忽略。

**Returns:**
VerticalAlignment 值。@see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

获取工件的底部边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。

**Returns:**
底部边距。

### getContents {#getContents--}
```
public List < Operator > getContents()
```

获取工件内部操作符的集合。

**Returns:**
列出工件的内部操作符。

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

获取工件子类型的名称。如果工件子类型不是标准子类型，可使用此属性。

**Returns:**
字符串值

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

获取工件类型的名称。如果工件类型非标准，可使用此属性。

**Returns:**
字符串工件名称

### getForm {#getForm--}
```
public XForm getForm()
```

获取工件的 XForm（如果使用了 XForm）。

**Returns:**
XForm 对象

### getImage {#getImage--}
```
public XImage getImage()
```

获取工件的图像（如果存在）。

**Returns:**
XImage 对象

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

获取工件的左侧边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。

**Returns:**
工件的左边距。

### getLines {#getLines--}
```
public final List < String > getLines()
```

多行文本工件的行。

**Returns:**
字符串列表

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

获取工件的不透明度。可能的取值范围为 0..1。

**Returns:**
工件的不透明度。

### getPosition {#getPosition--}
```
public Point getPosition()
```

获取工件的位置。如果指定了此属性，则边距和对齐方式将被忽略。

**Returns:**
工件位置。

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取工件的矩形。

**Returns:**
Rectangle 对象

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

获取工件的右侧边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。

**Returns:**
工件的右边距。

### getRotation {#getRotation--}
```
public double getRotation()
```

获取工件的旋转角度。

**Returns:**
工件的旋转角度。

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

获取工件子类型。如果工件具有非标准子类型，可通过 CustomSubtype 读取子类型名称。

**Returns:**
工件子类型。 @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

获取工件的文本。

**Returns:**
字符串值

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

工件文本的文本状态。

**Returns:**
TextState 实例

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

获取工件的顶部边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。

**Returns:**
工件的上边距。

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

获取工件类型。

**Returns:**
工件类型值。 @see ArtifactType

### getValue {#getValue-java.lang.String-}
获取工件的自定义值。

### isBackground {#isBackground--}
```
public boolean isBackground()
```

如果为 true，工件将放置在页面内容后面。

**Returns:**
布尔值

### removeValue {#removeValue-java.lang.String-}
从工件中移除自定义值。

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

在调用 BeginUpdates() 之后，对工件所做的所有更新都会被保存。

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
获取工件的水平对齐方式。

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
设置工件的垂直对齐方式。

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

如果为 true，工件将放置在页面内容后面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

设置工件的底部边距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 底部边距。 |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
设置工件类型的名称。如果工件类型为非标准类型，可使用此属性。

### setImage {#setImage-java.io.InputStream-}
设置工件的图像。

### setImage {#setImage-java.lang.String-}
设置工件的图像。

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

设置工件的左侧边距。如果在 Position 属性中显式指定了位置，则此值将被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 工件的左边距。 |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
设置工件的文本及其属性。允许指定多行。

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

设置工件的不透明度。可能的取值范围为 0..1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 工件的不透明度。 |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
设置将被页码替换的字符串。默认值为 #。

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
设置作为工件放置在文档页上的 PDF 页面。

### setPosition {#setPosition-com.aspose.pdf.Point-}
设置工件的位置。

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

设置工件的右侧边距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 工件的右边距。 |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

设置工件的旋转角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 工件的旋转角度。 |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
设置工件的子类型。

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
设置工件的文本。

### setText {#setText-java.lang.String-}
设置工件的文本。

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
设置工件的文本及其属性。

### setTextState {#setTextState-com.aspose.pdf.TextState-}
工件文本的文本状态。

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

设置工件的顶部边距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 工件的上边距。 |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
设置工件类型。

### setValue {#setValue-java.lang.String-java.lang.String-}
设置工件的自定义值。
