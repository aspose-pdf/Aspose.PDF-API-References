---
title: PageNumberStamp
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示页码戳，用于对页码进行编号。
type: docs
weight: 267
url: /zh/java/com.aspose.pdf/pagenumberstamp/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Stamp](../../com.aspose.pdf/stamp), [com.aspose.pdf.TextStamp](../../com.aspose.pdf/textstamp)
```
public final class PageNumberStamp extends TextStamp
```

表示页码戳，用于对页码进行编号。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageNumberStamp(String format)](#PageNumberStamp-java.lang.String-) | 初始化 PageNumberStamp 类的新实例。 |
| [PageNumberStamp()](#PageNumberStamp--) | 初始化 PageNumberStamp 类的新实例。 |
| [PageNumberStamp(FormattedText formattedText)](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | 通过格式化文本创建 PageNumberStamp。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | 获取图章的底部边距。 |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | 返回默认字体 |
| [getDefaultFontSize()](#getDefaultFontSize--) | 默认字体大小 |
| [getDraw()](#getDraw--) | 此属性决定如何在页面上绘制图章。 |
| [getFormat()](#getFormat--) | 获取标记页码的字符串值。 |
| [getHeight()](#getHeight--) | 页面上图章的所需高度。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取页面上图章的水平对齐方式。 |
| [getLeftMargin()](#getLeftMargin--) | 获取邮票的左边距。 |
| [getMaxRowWidth()](#getMaxRowWidth--) | WordWrap 选项的最大行高。 |
| [getNumberingStyle()](#getNumberingStyle--) | 此邮票使用的编号样式。 |
| [getOpacity()](#getOpacity--) | 获取一个值以指示图章不透明度。 |
| [getOutlineOpacity()](#getOutlineOpacity--) | 获取一个值以指示图章轮廓不透明度。 |
| [getOutlineWidth()](#getOutlineWidth--) | 获取图章轮廓宽度的值。 |
| [getRightMargin()](#getRightMargin--) | 获取邮票的右边距。 |
| [getRotate()](#getRotate--) | 根据旋转值获取图章内容的旋转。 |
| [getRotateAngle()](#getRotateAngle--) | 获取图章的旋转角度（以度为单位）。 |
| [getStampId()](#getStampId--) | 获取邮票 ID。 |
| [getStartingNumber()](#getStartingNumber--) | 获取起始页数的值。 |
| [getTextAlignment()](#getTextAlignment--) | 图章内文本的对齐方式。 |
| [getTextState()](#getTextState--) | 获取图章的文本属性。 |
| [getTopMargin()](#getTopMargin--) | 获取邮票的上边距。 |
| [getTreatYIndentAsBaseLine()](#getTreatYIndentAsBaseLine--) | 定义放置文本的坐标原点。 |
| [getValue()](#getValue--) | 获取在页面上用作标记的字符串值。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取页面上图章的垂直对齐方式。 |
| [getWidth()](#getWidth--) | 页面上图章的所需宽度。 |
| [getXIndent()](#getXIndent--) | 获取水平标记坐标，从左侧开始。 |
| [getYIndent()](#getYIndent--) | 从底部开始获取垂直图章坐标。 |
| [getZoom()](#getZoom--) | 获取图章的缩放因子。 |
| [getZoomX()](#getZoomX--) | 获取图章的水平缩放因子。 |
| [getZoomY()](#getZoomY--) | 获取图章的垂直缩放因子。 |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | 获取一个 bool 值，指示内容被标记为背景。 |
| [isJustify()](#isJustify--) | 定义文本对齐方式。 |
| [isScale()](#isScale--) | 定义文本的缩放比例。 |
| [isWordWrap()](#isWordWrap--) | 定义自动换行。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [put(Page page)](#put-com.aspose.pdf.Page-) | 添加页码。 |
| [setBackground(boolean value)](#setBackground-boolean-) | 设置一个 bool 值，指示内容被标记为背景。 |
| [setBottomMargin(double value)](#setBottomMargin-double-) | 设置图章的下边距。 |
| [setDraw(boolean value)](#setDraw-boolean-) | 此属性决定如何在页面上绘制图章。 |
| [setFormat(String value)](#setFormat-java.lang.String-) | 设置标记页码的字符串值。 |
| [setHeight(double value)](#setHeight-double-) | 页面上图章的所需高度。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置页面上图章的水平对齐方式。 |
| [setJustify(boolean value)](#setJustify-boolean-) | 定义文本对齐方式。 |
| [setLeftMargin(double value)](#setLeftMargin-double-) | 设置图章的左边距。 |
| [setMaxRowWidth(double value)](#setMaxRowWidth-double-) | WordWrap 选项的最大行高。 |
| [setNumberingStyle(int value)](#setNumberingStyle-int-) | 此邮票使用的编号样式。 |
| [setOpacity(double value)](#setOpacity-double-) | 设置一个值以指示图章不透明度。 |
| [setOutlineOpacity(double value)](#setOutlineOpacity-double-) | 设置一个值以指示图章轮廓不透明度。 |
| [setOutlineWidth(double value)](#setOutlineWidth-double-) | 设置图章轮廓宽度的值。 |
| [setRightMargin(double value)](#setRightMargin-double-) | 设置图章的右边距。 |
| [setRotate(int value)](#setRotate-int-) | 根据旋转值设置图章内容的旋转。 |
| [setRotateAngle(double value)](#setRotateAngle-double-) | 设置图章的旋转角度（以度为单位）。 |
| [setScale(boolean value)](#setScale-boolean-) | 定义文本的缩放比例。 |
| [setStampId(int value)](#setStampId-int-) | 设置戳记 ID。 |
| [setStartingNumber(int value)](#setStartingNumber-int-) | 设置起始页数的值。 |
| [setTextAlignment(int value)](#setTextAlignment-int-) | 图章内文本的对齐方式。 |
| [setTopMargin(double value)](#setTopMargin-double-) | 设置图章的上边距。 |
| [setTreatYIndentAsBaseLine(boolean value)](#setTreatYIndentAsBaseLine-boolean-) | 定义放置文本的坐标原点。 |
| [setValue(String value)](#setValue-java.lang.String-) | 设置在页面上用作标记的字符串值。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置页面上图章的垂直对齐方式。 |
| [setWidth(double value)](#setWidth-double-) | 页面上图章的所需宽度。 |
| [setWordWrap(boolean value)](#setWordWrap-boolean-) | 定义自动换行。 |
| [setXIndent(double value)](#setXIndent-double-) | 设置水平标记坐标，从左侧开始。 |
| [setYIndent(double value)](#setYIndent-double-) | 设置垂直图章坐标，从底部开始。 |
| [setZoom(double value)](#setZoom-double-) | 获取图章的缩放因子。 |
| [setZoomX(double value)](#setZoomX-double-) | 设置图章的水平缩放系数。 |
| [setZoomY(double value)](#setZoomY-double-) | 设置图章的垂直缩放系数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PageNumberStamp(String format) {#PageNumberStamp-java.lang.String-}
```
public PageNumberStamp(String format)
```


初始化 PageNumberStamp 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| format | java.lang.String | 用于标记的字符串值。有关详细信息，请参阅格式属性。 |

### PageNumberStamp() {#PageNumberStamp--}
```
public PageNumberStamp()
```


初始化 PageNumberStamp 类的新实例。格式设置为“\#”。

### PageNumberStamp(FormattedText formattedText) {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
```
public PageNumberStamp(FormattedText formattedText)
```


通过格式化文本创建 PageNumberStamp。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 用于创建页码戳的格式化文本。 |

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
### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


获取图章的底部边距。

**退货：**
双倍价值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


返回默认字体

**退货：**
[Font](../../com.aspose.pdf/font) - com.aspose.pdf.Font 对象
### getDefaultFontSize() {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```


默认字体大小

**退货：**
float - 浮点值
### getDraw() {#getDraw--}
```
public boolean getDraw()
```


此属性决定如何在页面上绘制图章。如果 Draw = true stamp 被绘制为图形运算符，如果 draw = false 则 stamp 被绘制为文本。

**退货：**
boolean - 布尔值
### getFormat() {#getFormat--}
```
public String getFormat()
```


获取标记页码的字符串值。值必须包含字符 '\#'在冲压过程中被页码代替。

**退货：**
java.lang.String - 字符串值
### getHeight() {#getHeight--}
```
public double getHeight()
```


页面上图章的所需高度。

**退货：**
双倍价值
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取页面上图章的水平对齐方式。

**退货：**
int - HorizontalAlignment 值
### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


获取邮票的左边距。

**退货：**
双倍价值
### getMaxRowWidth() {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```


WordWrap 选项的最大行高。

**退货：**
双倍价值
### getNumberingStyle() {#getNumberingStyle--}
```
public int getNumberingStyle()
```


此邮票使用的编号样式。

**退货：**
int - NumberingStyle 值
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


获取一个值以指示图章不透明度。该值从 0.0 到 1.0。默认情况下，该值为 1.0。

**退货：**
双倍价值
### getOutlineOpacity() {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```


获取一个值以指示图章轮廓不透明度。该值从 0.0 到 1.0。默认情况下，该值为 1.0。

**退货：**
双倍价值
### getOutlineWidth() {#getOutlineWidth--}
```
public double getOutlineWidth()
```


获取图章轮廓宽度的值。默认情况下，该值为 1.0。

**退货：**
双倍价值
### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


获取邮票的右边距。

**退货：**
双倍价值
### getRotate() {#getRotate--}
```
public int getRotate()
```


根据旋转值获取图章内容的旋转。笔记。此属性适用于 90 度的倍数（0、90、180、270 度）的设置角度。要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。

**退货：**
int - 旋转值
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取图章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。

**退货：**
双倍价值
### getStampId() {#getStampId--}
```
public int getStampId()
```


获取邮票 ID。

**退货：**
int - 邮票的标识符。
### getStartingNumber() {#getStartingNumber--}
```
public int getStartingNumber()
```


获取起始页数的值。其他页面将从该值开始编号。

**退货：**
int - 整数值
### getTextAlignment() {#getTextAlignment--}
```
public int getTextAlignment()
```


图章内文本的对齐方式。

**退货：**
int - HorizontalAlignment 值
### getTextState() {#getTextState--}
```
public TextState getTextState()
```


获取图章的文本属性。有关详细信息，请参见文本状态。

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态元素
### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


获取邮票的上边距。

**退货：**
双倍价值
### getTreatYIndentAsBaseLine() {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```


定义放置文本的坐标原点。如果 TreatYIndentAsBaseLine = true（当 Draw = true 时默认）YIndent 值将被视为文本基线。如果 TreatYIndentAsBaseLine = false（当 Draw = false 时默认）YIndent 值将被视为文本的底部（下降线）。

**退货：**
boolean - 布尔值
### getValue() {#getValue--}
```
public String getValue()
```


获取在页面上用作标记的字符串值。

**退货：**
java.lang.String - 字符串值
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取页面上图章的垂直对齐方式。

**退货：**
int - VerticalAlignment 值
### getWidth() {#getWidth--}
```
public double getWidth()
```


页面上图章的所需宽度。

**退货：**
双倍价值
### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


获取水平标记坐标，从左侧开始。

**退货：**
双倍价值
### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


从底部开始获取垂直图章坐标。

**退货：**
双倍价值
### getZoom() {#getZoom--}
```
public double getZoom()
```


获取图章的缩放因子。允许缩放图章。请注意，一对属性 ZoomX 和 ZoomY 允许分别为每个轴设置缩放因子。此属性的设置会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 值。

**退货：**
双倍价值
### getZoomX() {#getZoomX--}
```
public double getZoomX()
```


获取图章的水平缩放因子。允许水平缩放图章。

**退货：**
双倍价值
### getZoomY() {#getZoomY--}
```
public double getZoomY()
```


获取图章的垂直缩放因子。允许垂直缩放图章。

**退货：**
双倍价值
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


获取一个 bool 值，指示内容被标记为背景。如果该值为 true，则戳记内容位于底部。默认情况下，该值为 false，戳记内容位于顶部。

**退货：**
boolean - 布尔值
### isJustify() {#isJustify--}
```
public boolean isJustify()
```


定义文本对齐方式。如果此属性设置为 true，则文本的左右边缘对齐。默认值：假。

**退货：**
boolean - 布尔值
### isScale() {#isScale--}
```
public boolean isScale()
```


定义文本的缩放比例。如果此属性设置为 true 并指定了 Width 值，文本将被缩放以适应指定的宽度。

**退货：**
boolean - 布尔值
### isWordWrap() {#isWordWrap--}
```
public boolean isWordWrap()
```


定义自动换行。如果此属性设置为 true 并指定了 Width 值，文本将分成几行以适应指定的宽度。默认值：假。

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




### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


添加页码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 冲压页面。 |

### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


设置一个 bool 值，指示内容被标记为背景。如果该值为 true，则戳记内容位于底部。默认情况下，该值为 false，戳记内容位于顶部。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


设置图章的下边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setDraw(boolean value) {#setDraw-boolean-}
```
public void setDraw(boolean value)
```


此属性决定如何在页面上绘制图章。如果 Draw = true stamp 被绘制为图形运算符，如果 draw = false 则 stamp 被绘制为文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFormat(String value) {#setFormat-java.lang.String-}
```
public void setFormat(String value)
```


设置标记页码的字符串值。值必须包含字符 '\#'在冲压过程中被页码代替。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


页面上图章的所需高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置页面上图章的水平对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setJustify(boolean value) {#setJustify-boolean-}
```
public void setJustify(boolean value)
```


定义文本对齐方式。如果此属性设置为 true，则文本的左右边缘对齐。默认值：假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


设置图章的左边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setMaxRowWidth(double value) {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```


WordWrap 选项的最大行高。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setNumberingStyle(int value) {#setNumberingStyle-int-}
```
public void setNumberingStyle(int value)
```


此邮票使用的编号样式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | NumberingStyle 值 |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


设置一个值以指示图章不透明度。该值从 0.0 到 1.0。默认情况下，该值为 1.0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setOutlineOpacity(double value) {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```


设置一个值以指示图章轮廓不透明度。该值从 0.0 到 1.0。默认情况下，该值为 1.0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setOutlineWidth(double value) {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```


设置图章轮廓宽度的值。默认情况下，该值为 1.0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


设置图章的右边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


根据旋转值设置图章内容的旋转。笔记。此属性适用于 90 度的倍数（0、90、180、270 度）的设置角度。要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```


设置图章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 旋转角度 |

### setScale(boolean value) {#setScale-boolean-}
```
public void setScale(boolean value)
```


定义文本的缩放比例。如果此属性设置为 true 并指定了 Width 值，文本将被缩放以适应指定的宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


设置戳记 ID。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | Stamp ID 的新值。 |

### setStartingNumber(int value) {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```


设置起始页数的值。其他页面将从该值开始编号。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public void setTextAlignment(int value)
```


图章内文本的对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


设置图章的上边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setTreatYIndentAsBaseLine(boolean value) {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```


定义放置文本的坐标原点。如果 TreatYIndentAsBaseLine = true（当 Draw = true 时默认）YIndent 值将被视为文本基线。如果 TreatYIndentAsBaseLine = false（当 Draw = false 时默认）YIndent 值将被视为文本的底部（下降线）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


设置在页面上用作标记的字符串值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


设置页面上图章的垂直对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 值 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


页面上图章的所需宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setWordWrap(boolean value) {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```


定义自动换行。如果此属性设置为 true 并指定了 Width 值，文本将分成几行以适应指定的宽度。默认值：假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


设置水平标记坐标，从左侧开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


设置垂直图章坐标，从底部开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setZoom(double value) {#setZoom-double-}
```
public void setZoom(double value)
```


获取图章的缩放因子。允许缩放图章。请注意，一对属性 ZoomX 和 ZoomY 允许分别为每个轴设置缩放因子。此属性的设置会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setZoomX(double value) {#setZoomX-double-}
```
public void setZoomX(double value)
```


设置图章的水平缩放系数。允许水平缩放图章。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setZoomY(double value) {#setZoomY-double-}
```
public void setZoomY(double value)
```


设置图章的垂直缩放系数。允许垂直缩放图章。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

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
