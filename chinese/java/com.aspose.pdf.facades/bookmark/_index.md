---
title: "Bookmark"
linktitle: "Bookmark"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一个书签。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

表示一个书签。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Bookmark](#Bookmark--) | 初始化 {@code Bookmark} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAction](#getAction--) | 获取与书签绑定的操作。如果提供了 PageNumber，则无法指定操作。操作类型包括：“GoTo”、“GoToR”、“Launch”、“Named”。 |
| [getBoldFlag](#getBoldFlag--) | 获取书签标题的粗体标志。 |
| [getChildItem](#getChildItem--) | 获取书签的子项。Obsolete("Use getChildItems() property instead of this one.") |
| [getChildItems](#getChildItems--) | 获取书签的子项。 |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | 尚未支持。对应在 Acrobat 查看器中执行菜单项的操作名称。 |
| [getDestination](#getDestination--) | 获取书签的目标页面。若操作设置为 "" 时为必需。 |
| [getItalicFlag](#getItalicFlag--) | 获取书签标题的斜体标志。 |
| [getLevel](#getLevel--) | 获取书签的层级。 |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | 获取页面显示的底部坐标。 |
| [getPageDisplay_Left](#getPageDisplay_Left--) | 获取页面显示的左侧坐标。 |
| [getPageDisplay_Right](#getPageDisplay_Right--) | 获取页面显示的右侧坐标。 |
| [getPageDisplay_Top](#getPageDisplay_Top--) | 获取页面显示的顶部坐标。 |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | 获取页面显示的缩放因子。 |
| [getPageDisplay](#getPageDisplay--) | 获取显示书签目标页面的类型。 |
| [getPageNumber](#getPageNumber--) | 获取书签目标页面的编号。 |
| [getRemoteFile](#getRemoteFile--) | 获取书签的 "GoToR" 操作所需的文件（路径）。 |
| [getTitle](#getTitle--) | 获取书签的标题。 |
| [getTitleColor](#getTitleColor--) | 获取书签标题的颜色。 |
| [isOpen](#isOpen--) | 获取书签状态（打开，关闭）。 |
| [setAction](#setAction-java.lang.String-) | 设置与书签绑定的操作。如果提供了 PageNumber，则无法指定操作。操作类型包括："GoTo"、"GoToR"、"Launch"、"Named"。 |
| [setBoldFlag](#setBoldFlag-boolean-) | 设置书签标题的粗体标志。 |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | 设置书签的子项。Obsolete("Use setChildItems() property instead of this one.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | 设置书签的子项。 |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | 尚未支持。设置对应在 Acrobat 查看器中执行菜单项的操作名称。 |
| [setDestination](#setDestination-java.lang.String-) | 设置书签的目标页面。若操作设置为 "" 时为必需。 |
| [setItalicFlag](#setItalicFlag-boolean-) | 设置书签标题的斜体标志。 |
| [setLevel](#setLevel-int-) | 设置书签的层级。 |
| [setOpen](#setOpen-boolean-) | 设置书签状态（打开，关闭）。 |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | 设置页面显示的底部坐标。 |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | 设置页面显示的左侧坐标。 |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | 设置页面显示的右侧坐标。 |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | 设置页面显示的顶部坐标。 |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | 设置页面显示的缩放因子。 |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | 设置显示书签目标页的类型。 |
| [setPageNumber](#setPageNumber-int-) | 设置书签目标页的页码。 |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | 设置书签的 \"GoToR\" 操作所需的文件（路径）。 |
| [setTitle](#setTitle-java.lang.String-) | 设置书签的标题。 |
| [setTitleColor](#setTitleColor-java.awt.Color-) | 设置书签标题的颜色。 |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | 转换为 OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

初始化 {@code Bookmark} 类的新实例。

### getAction {#getAction--}
```
public String getAction()
```

获取与书签绑定的操作。如果提供了 PageNumber，则无法指定操作。操作类型包括：“GoTo”、“GoToR”、“Launch”、“Named”。

**Returns:**
字符串值

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

获取书签标题的粗体标志。

**Returns:**
布尔值

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

获取书签的子项。Obsolete("Use getChildItems() property instead of this one.")

**Returns:**
书签元素

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

获取书签的子项。

**Returns:**
书签的子项。

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

尚未支持。对应在 Acrobat 查看器中执行菜单项的操作名称。

**Returns:**
int 数组值

### getDestination {#getDestination--}
```
public String getDestination()
```

获取书签的目标页面。若操作设置为 "" 时为必需。

**Returns:**
字符串值

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

获取书签标题的斜体标志。

**Returns:**
布尔值

### getLevel {#getLevel--}
```
public int getLevel()
```

获取书签的层级。

**Returns:**
int 值

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

获取页面显示的底部坐标。

**Returns:**
int 值

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

获取页面显示的左侧坐标。

**Returns:**
int 值

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

获取页面显示的右侧坐标。

**Returns:**
int 值

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

获取页面显示的顶部坐标。

**Returns:**
int 值

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

获取页面显示的缩放因子。

**Returns:**
int 值

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

获取显示书签目标页面的类型。

**Returns:**
字符串值

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

获取书签目标页面的编号。

**Returns:**
int 值

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

获取书签的 "GoToR" 操作所需的文件（路径）。

**Returns:**
字符串值

### getTitle {#getTitle--}
```
public String getTitle()
```

获取书签的标题。

**Returns:**
字符串值

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

获取书签标题的颜色。

**Returns:**
颜色元素

### isOpen {#isOpen--}
```
public boolean isOpen()
```

获取书签状态（打开，关闭）。

**Returns:**
布尔值

### setAction {#setAction-java.lang.String-}
设置与书签绑定的操作。如果提供了 PageNumber，则无法指定操作。操作类型包括："GoTo"、"GoToR"、"Launch"、"Named"。

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

设置书签标题的粗体标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
设置书签的子项。Obsolete("Use setChildItems() property instead of this one.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
设置书签的子项。

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

尚未支持。设置对应在 Acrobat 查看器中执行菜单项的操作名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 数组值 |

### setDestination {#setDestination-java.lang.String-}
设置书签的目标页面。若操作设置为 "" 时为必需。

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

设置书签标题的斜体标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

设置书签的层级。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

设置书签状态（打开，关闭）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

设置页面显示的底部坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

设置页面显示的左侧坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

设置页面显示的右侧坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

设置页面显示的顶部坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

设置页面显示的缩放因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPageDisplay {#setPageDisplay-java.lang.String-}
设置显示书签目标页的类型。

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

设置书签目标页的页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setRemoteFile {#setRemoteFile-java.lang.String-}
设置书签的 \"GoToR\" 操作所需的文件（路径）。

### setTitle {#setTitle-java.lang.String-}
设置书签的标题。

### setTitleColor {#setTitleColor-java.awt.Color-}
设置书签标题的颜色。

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
转换为 OutlineItemCollection
