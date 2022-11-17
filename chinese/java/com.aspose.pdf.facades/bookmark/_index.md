---
title: Bookmark
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表一个书签。
type: docs
weight: 14
url: /zh/java/com.aspose.pdf.facades/bookmark/
---
**遗产：**
java.lang.Object
```
public final class Bookmark
```

代表一个书签。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Bookmark()](#Bookmark--) | 初始化 Bookmark 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 获取书签绑定的动作。 |
| [getBoldFlag()](#getBoldFlag--) | 获取书签标题的粗体标志。 |
| [getChildItem()](#getChildItem--) | 获取书签的孩子。 |
| [getChildItems()](#getChildItems--) | 获取书签的孩子。 |
| [getClass()](#getClass--) |  |
| [getCustomAcorbatViewerMenuActionName()](#getCustomAcorbatViewerMenuActionName--) | 尚不支持。 |
| [getDestination()](#getDestination--) | 获取书签的目标页面。 |
| [getItalicFlag()](#getItalicFlag--) | 获取书签标题的斜体标志。 |
| [getLevel()](#getLevel--) | 获取书签的层次结构级别。 |
| [getPageDisplay()](#getPageDisplay--) | 获取显示书签的目标页面的类型。 |
| [getPageDisplay_Bottom()](#getPageDisplay-Bottom--) | 获取页面显示的底部坐标。 |
| [getPageDisplay_Left()](#getPageDisplay-Left--) | 获取页面显示的左坐标。 |
| [getPageDisplay_Right()](#getPageDisplay-Right--) | 获取页面显示的右坐标。 |
| [getPageDisplay_Top()](#getPageDisplay-Top--) | 获取页面显示的顶部坐标。 |
| [getPageDisplay_Zoom()](#getPageDisplay-Zoom--) | 获取页面显示的缩放比例。 |
| [getPageNumber()](#getPageNumber--) | 获取书签的目标页数。 |
| [getRemoteFile()](#getRemoteFile--) | 获取书签的“GoToR”操作所需的文件（路径）。 |
| [getTitle()](#getTitle--) | 获取书签的标题。 |
| [getTitleColor()](#getTitleColor--) | 获取书签标题的颜色。 |
| [hashCode()](#hashCode--) |  |
| [isOpen()](#isOpen--) | 获取书签状态（打开、关闭）。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | 设置与书签绑定的动作。 |
| [setBoldFlag(boolean value)](#setBoldFlag-boolean-) | 设置书签标题的粗体标志。 |
| [setChildItem(Bookmarks value)](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | 设置书签的孩子。 |
| [setChildItems(Bookmarks value)](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | 设置书签的孩子。 |
| [setCustomAcorbatViewerMenuActionName(int[] value)](#setCustomAcorbatViewerMenuActionName-int---) | 尚不支持。 |
| [setDestination(String value)](#setDestination-java.lang.String-) | 设置书签的目标页面。 |
| [setItalicFlag(boolean value)](#setItalicFlag-boolean-) | 设置书签标题的斜体标志。 |
| [setLevel(int value)](#setLevel-int-) | 设置书签的层次结构级别。 |
| [setOpen(boolean value)](#setOpen-boolean-) | 设置书签状态（打开、关闭）。 |
| [setPageDisplay(String value)](#setPageDisplay-java.lang.String-) | 设置显示书签目标页面的类型。 |
| [setPageDisplay_Bottom(int value)](#setPageDisplay-Bottom-int-) | 设置页面显示的底部坐标。 |
| [setPageDisplay_Left(int value)](#setPageDisplay-Left-int-) | 设置页面显示的左坐标。 |
| [setPageDisplay_Right(int value)](#setPageDisplay-Right-int-) | 设置页面显示的右坐标。 |
| [setPageDisplay_Top(int value)](#setPageDisplay-Top-int-) | 设置页面显示的顶部坐标。 |
| [setPageDisplay_Zoom(int value)](#setPageDisplay-Zoom-int-) | 设置页面显示的缩放比例。 |
| [setPageNumber(int value)](#setPageNumber-int-) | 设置书签的目标页数。 |
| [setRemoteFile(String value)](#setRemoteFile-java.lang.String-) | 设置书签的“GoToR”操作所需的文件（路径）。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 设置书签的标题。 |
| [setTitleColor(Color value)](#setTitleColor-java.awt.Color-) | 设置书签标题的颜色。 |
| [toOutlineItemCollection(IDocument doc)](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | 转换为 OutlineItemCollection |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bookmark() {#Bookmark--}
```
public Bookmark()
```


初始化 Bookmark 类的新实例。

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
### getAction() {#getAction--}
```
public String getAction()
```


获取书签绑定的动作。如果出现 PageNumber，则无法指定操作。动作类型包括：“GoTo”、“GoToR”、“Launch”、“Named”。

**退货：**
java.lang.String - 字符串值
### getBoldFlag() {#getBoldFlag--}
```
public boolean getBoldFlag()
```


获取书签标题的粗体标志。

**退货：**
boolean - 布尔值
### getChildItem() {#getChildItem--}
```
public Bookmarks getChildItem()
```


获取书签的孩子。

Obsolete("使用 getChildItems() 属性代替这个属性。")

**退货：**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - 书签元素
### getChildItems() {#getChildItems--}
```
public Bookmarks getChildItems()
```


获取书签的孩子。

**退货：**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) 书签的子项目。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCustomAcorbatViewerMenuActionName() {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```


尚不支持。

对应于在 Acrobat 查看器中执行菜单项的动作名称。

**退货：**
整数[- 整数值数组
### getDestination() {#getDestination--}
```
public String getDestination()
```


获取书签的目标页面。如果操作设置为，则需要“”.

**退货：**
java.lang.String - 字符串值
### getItalicFlag() {#getItalicFlag--}
```
public boolean getItalicFlag()
```


获取书签标题的斜体标志。

**退货：**
boolean - 布尔值
### getLevel() {#getLevel--}
```
public int getLevel()
```


获取书签的层次结构级别。

**退货：**
int - 整数值
### getPageDisplay() {#getPageDisplay--}
```
public String getPageDisplay()
```


获取显示书签的目标页面的类型。

**退货：**
java.lang.String - 字符串值
### getPageDisplay_Bottom() {#getPageDisplay-Bottom--}
```
public int getPageDisplay_Bottom()
```


获取页面显示的底部坐标。

**退货：**
int - 整数值
### getPageDisplay_Left() {#getPageDisplay-Left--}
```
public int getPageDisplay_Left()
```


获取页面显示的左坐标。

**退货：**
int - 整数值
### getPageDisplay_Right() {#getPageDisplay-Right--}
```
public int getPageDisplay_Right()
```


获取页面显示的右坐标。

**退货：**
int - 整数值
### getPageDisplay_Top() {#getPageDisplay-Top--}
```
public int getPageDisplay_Top()
```


获取页面显示的顶部坐标。

**退货：**
int - 整数值
### getPageDisplay_Zoom() {#getPageDisplay-Zoom--}
```
public int getPageDisplay_Zoom()
```


获取页面显示的缩放比例。

**退货：**
int - 整数值
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


获取书签的目标页数。

**退货：**
int - 整数值
### getRemoteFile() {#getRemoteFile--}
```
public String getRemoteFile()
```


获取书签的“GoToR”操作所需的文件（路径）。

**退货：**
java.lang.String - 字符串值
### getTitle() {#getTitle--}
```
public String getTitle()
```


获取书签的标题。

**退货：**
java.lang.String - 字符串值
### getTitleColor() {#getTitleColor--}
```
public Color getTitleColor()
```


获取书签标题的颜色。

**退货：**
[Color](../../java.awt/color) - 颜色元素
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isOpen() {#isOpen--}
```
public boolean isOpen()
```


获取书签状态（打开、关闭）。

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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


设置与书签绑定的动作。如果出现 PageNumber，则无法指定操作。动作类型包括：“GoTo”、“GoToR”、“Launch”、“Named”。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setBoldFlag(boolean value) {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```


设置书签标题的粗体标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setChildItem(Bookmarks value) {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
```
public void setChildItem(Bookmarks value)
```


设置书签的孩子。

Obsolete("使用 setChildItems() 属性代替这个属性。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Bookmarks](../../com.aspose.pdf.facades/bookmarks) | 书签元素 |

### setChildItems(Bookmarks value) {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
```
public void setChildItems(Bookmarks value)
```


设置书签的孩子。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Bookmarks](../../com.aspose.pdf.facades/bookmarks) | 书签的子项目。 |

### setCustomAcorbatViewerMenuActionName(int[] value) {#setCustomAcorbatViewerMenuActionName-int---}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```


尚不支持。

设置对应于在 Acrobat 查看器中执行菜单项的动作名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] | int值数组 |

### setDestination(String value) {#setDestination-java.lang.String-}
```
public void setDestination(String value)
```


设置书签的目标页面。如果操作设置为，则需要“”.

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setItalicFlag(boolean value) {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```


设置书签标题的斜体标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLevel(int value) {#setLevel-int-}
```
public void setLevel(int value)
```


设置书签的层次结构级别。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


设置书签状态（打开、关闭）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPageDisplay(String value) {#setPageDisplay-java.lang.String-}
```
public void setPageDisplay(String value)
```


设置显示书签目标页面的类型。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setPageDisplay_Bottom(int value) {#setPageDisplay-Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```


设置页面显示的底部坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPageDisplay_Left(int value) {#setPageDisplay-Left-int-}
```
public void setPageDisplay_Left(int value)
```


设置页面显示的左坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPageDisplay_Right(int value) {#setPageDisplay-Right-int-}
```
public void setPageDisplay_Right(int value)
```


设置页面显示的右坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPageDisplay_Top(int value) {#setPageDisplay-Top-int-}
```
public void setPageDisplay_Top(int value)
```


设置页面显示的顶部坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPageDisplay_Zoom(int value) {#setPageDisplay-Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```


设置页面显示的缩放比例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


设置书签的目标页数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRemoteFile(String value) {#setRemoteFile-java.lang.String-}
```
public void setRemoteFile(String value)
```


设置书签的“GoToR”操作所需的文件（路径）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


设置书签的标题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTitleColor(Color value) {#setTitleColor-java.awt.Color-}
```
public void setTitleColor(Color value)
```


设置书签标题的颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color | 颜色元素 |

### toOutlineItemCollection(IDocument doc) {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
```
public OutlineItemCollection toOutlineItemCollection(IDocument doc)
```


转换为 OutlineItemCollection

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象 |

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 对象
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
