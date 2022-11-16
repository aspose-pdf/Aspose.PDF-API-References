---
title: BackgroundArtifact
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类描述背景工件。
type: docs
weight: 30
url: /zh/java/com.aspose.pdf/backgroundartifact/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Artifact](../../com.aspose.pdf/artifact)
```
public class BackgroundArtifact extends Artifact
```

类描述背景工件。这个工件允许设置页面的背景。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BackgroundArtifact()](#BackgroundArtifact--) | 初始化 BackgroundArtifact 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [beginUpdates()](#beginUpdates--) | 开始删除更新。 |
| [close()](#close--) | 关闭此文档使用的所有资源。 |
| [dispose()](#dispose--) | 处理工件。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtifactHorizontalAlignment()](#getArtifactHorizontalAlignment--) | 获取工件的水平对齐方式。 |
| [getArtifactVerticalAlignment()](#getArtifactVerticalAlignment--) | 获取工件的垂直对齐方式。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景工件的背景颜色 |
| [getBackgroundImage()](#getBackgroundImage--) | 获取背景工件的免费图像 |
| [getBackgroundImageInternal()](#getBackgroundImageInternal--) | 仅供内部使用 |
| [getBottomMargin()](#getBottomMargin--) | 获取工件的底部边距。 |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | 获取工件内部运算符的集合。 |
| [getCustomSubtype()](#getCustomSubtype--) | 获取工件子类型的名称。 |
| [getCustomType()](#getCustomType--) | 获取工件类型的名称。 |
| [getForm()](#getForm--) | 获取工件的 XForm（如果使用 XForm）。 |
| [getImage()](#getImage--) | 获取工件的图像（如果存在）。 |
| [getLeftMargin()](#getLeftMargin--) | 获取工件的左边距。 |
| [getLines()](#getLines--) | 多行文本工件的行。 |
| [getOpacity()](#getOpacity--) | 获取工件的不透明度。 |
| [getPosition()](#getPosition--) | 获取神器位置。 |
| [getRectangle()](#getRectangle--) | 获取工件的矩形。 |
| [getRightMargin()](#getRightMargin--) | 获取工件的右边距。 |
| [getRotation()](#getRotation--) | 获取神器旋转角度。 |
| [getSubtype()](#getSubtype--) | 获取工件子类型。 |
| [getText()](#getText--) | 获取工件的文本。 |
| [getTextState()](#getTextState--) | 工件文本的文本状态。 |
| [getTopMargin()](#getTopMargin--) | 获取工件的顶部边距。 |
| [getType()](#getType--) | 获取工件类型。 |
| [getValue(String name)](#getValue-java.lang.String-) | 获取工件的自定义值。 |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | 如果为真，则工件放置在页面内容后面。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeValue(String name)](#removeValue-java.lang.String-) | 从工件中删除自定义值。 |
| [saveUpdates()](#saveUpdates--) | 保存在调用 BeginUpdates() 之后进行的工件中的所有更新。 |
| [setArtifactHorizontalAlignment(int value)](#setArtifactHorizontalAlignment-int-) | 获取工件的水平对齐方式。 |
| [setArtifactVerticalAlignment(int value)](#setArtifactVerticalAlignment-int-) | 设置工件的垂直对齐方式。 |
| [setBackground(boolean value)](#setBackground-boolean-) | 如果为真，则工件放置在页面内容后面。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | 设置背景工件的背景颜色 |
| [setBackgroundImage(InputStream value)](#setBackgroundImage-java.io.InputStream-) | 设置背景工件的免费图像 |
| [setBottomMargin(double value)](#setBottomMargin-double-) | 设置工件的底部边距。 |
| [setCustomSubtype(String value)](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType(String value)](#setCustomType-java.lang.String-) | 设置工件类型的名称。 |
| [setImage(InputStream imageStream)](#setImage-java.io.InputStream-) | 设置工件的图像。 |
| [setImage(String imageName)](#setImage-java.lang.String-) | 设置工件的图像。 |
| [setLeftMargin(double value)](#setLeftMargin-double-) | 设置工件的左边距。 |
| [setLinesAndState(String[] text, TextState textState)](#setLinesAndState-java.lang.String---com.aspose.pdf.TextState-) | 设置工件的文本和文本属性。 |
| [setOpacity(double value)](#setOpacity-double-) | 设置工件的不透明度。 |
| [setPdfPage(Page page)](#setPdfPage-com.aspose.pdf.Page-) | 将放置在文档页面上的 PDF 页面设置为工件。 |
| [setPosition(Point value)](#setPosition-com.aspose.pdf.Point-) | 设置工件位置。 |
| [setRightMargin(double value)](#setRightMargin-double-) | 设置工件的右边距。 |
| [setRotation(double value)](#setRotation-double-) | 设置工件旋转角度。 |
| [setSubtype(int value)](#setSubtype-int-) | 设置工件子类型。 |
| [setText(FormattedText formattedText)](#setText-com.aspose.pdf.facades.FormattedText-) | 设置工件的文本。 |
| [setText(String value)](#setText-java.lang.String-) | 设置工件的文本。 |
| [setTextAndState(String text, TextState textState)](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | 设置工件的文本和文本属性。 |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | 工件文本的文本状态。 |
| [setTopMargin(double value)](#setTopMargin-double-) | 设置工件的上边距。 |
| [setType(int value)](#setType-int-) | 设置工件类型。 |
| [setValue(String name, String value)](#setValue-java.lang.String-java.lang.String-) | 设置工件的自定义值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BackgroundArtifact() {#BackgroundArtifact--}
```
public BackgroundArtifact()
```


初始化 BackgroundArtifact 对象。

### beginUpdates() {#beginUpdates--}
```
public void beginUpdates()
```


开始删除更新。如果您需要对同一工件进行多项更改以提高性能，请使用此功能。通常在更改工件属性时随时更改工件运算符。每次更改工件时，这都会导致页面内容发生变化。为了避免这种影响，将所有工件更新放在 StartUpdates/SaveUpdates 调用之间。这只允许更改页面内容一次。

```
Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1);
  art.beginUpdates();
  art.setOpacity ( 0.3f);
  art.setPosition ( new Point(10,10));
  art.setRotation (30);
  art.saveUpdates();
```

### close() {#close--}
```
public void close()
```


关闭此文档使用的所有资源。

### dispose() {#dispose--}
```
public void dispose()
```


处理工件。

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
### getArtifactHorizontalAlignment() {#getArtifactHorizontalAlignment--}
```
public int getArtifactHorizontalAlignment()
```


获取工件的水平对齐方式。如果明确指定位置（在 Position 属性中），则忽略此值。

**退货：**
int - HorizontalAlignment 值
### getArtifactVerticalAlignment() {#getArtifactVerticalAlignment--}
```
public int getArtifactVerticalAlignment()
```


获取工件的垂直对齐方式。如果明确指定位置（在 Position 属性中），则忽略此值。

**退货：**
int - VerticalAlignment 值。
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景工件的背景颜色

**退货：**
[Color](../../java.awt/color) 颜色对象
### getBackgroundImage() {#getBackgroundImage--}
```
public InputStream getBackgroundImage()
```


获取背景工件的免费图像

**退货：**
java.io.InputStream - InputStream 对象
### getBackgroundImageInternal() {#getBackgroundImageInternal--}
```
public System.IO.Stream getBackgroundImageInternal()
```


仅供内部使用

**退货：**
com.aspose.ms.System.IO.Stream - 内部对象
### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


获取工件的底部边距。如果明确指定位置（在 Position 属性中），则忽略此值。

**退货：**
双底边距。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getContents() {#getContents--}
```
public List<Operator> getContents()
```


获取工件内部运算符的集合。

**退货：**
java.util.List<com.aspose.pdf.Operator> - 列出工件内部运算符。
### getCustomSubtype() {#getCustomSubtype--}
```
public String getCustomSubtype()
```


获取工件子类型的名称。如果工件子类型不是标准子类型，则可以使用。

**退货：**
java.lang.String - 字符串值
### getCustomType() {#getCustomType--}
```
public String getCustomType()
```


获取工件类型的名称。如果工件类型是非标准的，则可以使用。

**退货：**
java.lang.String - 字符串工件名称
### getForm() {#getForm--}
```
public XForm getForm()
```


获取工件的 XForm（如果使用 XForm）。

**退货：**
[XForm](../../com.aspose.pdf/xform) 变形对象
### getImage() {#getImage--}
```
public XImage getImage()
```


获取工件的图像（如果存在）。

**退货：**
[XImage](../../com.aspose.pdf/ximage)-XImage 对象
### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


获取工件的左边距。如果明确指定位置（在 Position 属性中），则忽略此值。

**退货：**
双 - 人工制品的左边距。
### getLines() {#getLines--}
```
public final List<String> getLines()
```


多行文本工件的行。

**退货：**
java.util.List<java.lang.String> - 字符串列表
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


获取工件的不透明度。可能的值在 0..1 范围内。

**退货：**
双 - 神器的不透明度。
### getPosition() {#getPosition--}
```
public Point getPosition()
```


获取神器位置。如果指定了此属性，则边距和对齐方式将被忽略。

**退货：**
[Point](../../com.aspose.pdf/point) - 工件位置。
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取工件的矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


获取工件的右边距。如果明确指定位置（在 Position 属性中），则忽略此值。

**退货：**
双 - 神器的右边距。
### getRotation() {#getRotation--}
```
public double getRotation()
```


获取神器旋转角度。

**退货：**
双神器旋转角度。
### getSubtype() {#getSubtype--}
```
public int getSubtype()
```


获取工件子类型。如果工件具有非标准子类型，则可以通过 CustomSubtype 读取子类型的名称。

**退货：**
int - 工件子类型。
### getText() {#getText--}
```
public String getText()
```


获取工件的文本。

**退货：**
java.lang.String - 字符串值
### getTextState() {#getTextState--}
```
public final TextState getTextState()
```


工件文本的文本状态。

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态实例
### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


获取工件的顶部边距。如果明确指定位置（在 Position 属性中），则忽略此值。

**退货：**
工件的双顶边距。
### getType() {#getType--}
```
public int getType()
```


获取工件类型。

**退货：**
int - 工件类型值。
### getValue(String name) {#getValue-java.lang.String-}
```
public String getValue(String name)
```


获取工件的自定义值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 值的名称。 |

**退货：**
java.lang.String - 值，如果值不存在则为 null。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isBackground() {#isBackground--}
```
public boolean isBackground()
```


如果为真，则工件放置在页面内容后面。

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




### removeValue(String name) {#removeValue-java.lang.String-}
```
public void removeValue(String name)
```


从工件中删除自定义值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的自定义值的名称。 |

### saveUpdates() {#saveUpdates--}
```
public void saveUpdates()
```


保存在调用 BeginUpdates() 之后进行的工件中的所有更新。

### setArtifactHorizontalAlignment(int value) {#setArtifactHorizontalAlignment-int-}
```
public void setArtifactHorizontalAlignment(int value)
```


获取工件的水平对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 工件的水平对齐。 |

### setArtifactVerticalAlignment(int value) {#setArtifactVerticalAlignment-int-}
```
public void setArtifactVerticalAlignment(int value)
```


设置工件的垂直对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 工件的垂直对齐。 |

### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


如果为真，则工件放置在页面内容后面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color value)
```


设置背景工件的背景颜色

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color | 色值 |

### setBackgroundImage(InputStream value) {#setBackgroundImage-java.io.InputStream-}
```
public void setBackgroundImage(InputStream value)
```


设置背景工件的免费图像

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流对象 |

### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


设置工件的底部边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 底边距。 |

### setCustomSubtype(String value) {#setCustomSubtype-java.lang.String-}
```
public void setCustomSubtype(String value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public void setCustomType(String value)
```


设置工件类型的名称。如果工件类型是非标准的，则可以使用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串工件名称 |

### setImage(InputStream imageStream) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream imageStream)
```


设置工件的图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 包含图像数据的流。 |

### setImage(String imageName) {#setImage-java.lang.String-}
```
public void setImage(String imageName)
```


设置工件的图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | java.lang.String | 图像文件的名称。 |

### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


设置工件的左边距。如果明确指定位置（在 Position 属性中），则忽略此值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 工件的左边距。 |

### setLinesAndState(String[] text, TextState textState) {#setLinesAndState-java.lang.String---com.aspose.pdf.TextState-}
```
public void setLinesAndState(String[] text, TextState textState)
```


设置工件的文本和文本属性。允许指定多行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String[] | 文本字符串数组。 |
| textState | [TextState](../../com.aspose.pdf/textstate) | 文本属性。 |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


设置工件的不透明度。可能的值在 0..1 范围内。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 工件的不透明度。 |

### setPdfPage(Page page) {#setPdfPage-com.aspose.pdf.Page-}
```
public void setPdfPage(Page page)
```


将放置在文档页面上的 PDF 页面设置为工件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 作为 Artifcact 放置的页面。 |

### setPosition(Point value) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point value)
```


设置工件位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | 工件位置。 |

### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


设置工件的右边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 工件的右边距。 |

### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


设置工件旋转角度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 神器旋转角度。 |

### setSubtype(int value) {#setSubtype-int-}
```
public void setSubtype(int value)
```


设置工件子类型。如果工件具有非标准子类型，则可以通过 CustomSubtype 读取子类型的名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 工件子类型。 |

### setText(FormattedText formattedText) {#setText-com.aspose.pdf.facades.FormattedText-}
```
public void setText(FormattedText formattedText)
```


设置工件的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 包含工件文本的 FormattedText 对象。 |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置工件的文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTextAndState(String text, TextState textState) {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
```
public void setTextAndState(String text, TextState textState)
```


设置工件的文本和文本属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文本字符串。 |
| textState | [TextState](../../com.aspose.pdf/textstate) | 文本状态。 |

### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public final void setTextState(TextState value)
```


工件文本的文本状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态实例 |

### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


设置工件的上边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 神器的上边距。 |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


设置工件类型。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 工件类型。 |

### setValue(String name, String value) {#setValue-java.lang.String-java.lang.String-}
```
public void setValue(String name, String value)
```


设置工件的自定义值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 自定义值的名称。 |
| value | java.lang.String | 工件中的自定义值。 |

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
