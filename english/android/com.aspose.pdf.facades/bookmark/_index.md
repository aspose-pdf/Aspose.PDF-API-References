---
title: Bookmark
second_title: Aspose.PDF for Java API Reference
description: Represents a bookmark.
type: docs
weight: 14
url: /java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object
```
public final class Bookmark
```

Represents a bookmark.
## Constructors

| Constructor | Description |
| --- | --- |
| [Bookmark()](#Bookmark--) | Initializes a new instance of the  Bookmark  class. |
## Methods

| Method | Description |
| --- | --- |
| [toOutlineItemCollection(IDocument doc)](#toOutlineItemCollection-com.aspose.pdf.IDocument-) |  |
| [getAction()](#getAction--) | Gets the action bound with the bookmark. |
| [setAction(String value)](#setAction-java.lang.String-) | Sets the action bound with the bookmark. |
| [getBoldFlag()](#getBoldFlag--) | Gets the bold flag of bookmark's title. |
| [setBoldFlag(boolean value)](#setBoldFlag-boolean-) | Sets the bold flag of bookmark's title. |
| [getChildItem()](#getChildItem--) | Gets bookmark's children. |
| [setChildItem(Bookmarks value)](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Sets bookmark's children. |
| [getChildItems()](#getChildItems--) | Gets or sets bookmark's children. |
| [setChildItems(Bookmarks value)](#setChildItems-com.aspose.pdf.facades.Bookmarks-) |  |
| [getCustomAcorbatViewerMenuActionName()](#getCustomAcorbatViewerMenuActionName--) | Gets the action name corresponding to execute a menu item in Acrobat viewer. |
| [setCustomAcorbatViewerMenuActionName(System.Enum[] value)](#setCustomAcorbatViewerMenuActionName-com.aspose.ms.System.Enum---) | Sets the action name corresponding to execute a menu item in Acrobat viewer. |
| [getDestination()](#getDestination--) | Gets bookmark's destination page. |
| [setDestination(String value)](#setDestination-java.lang.String-) | Sets bookmark's destination page. |
| [getItalicFlag()](#getItalicFlag--) | Gets the italic flag of bookmark's title. |
| [setItalicFlag(boolean value)](#setItalicFlag-boolean-) | Sets the italic flag of bookmark's title. |
| [getLevel()](#getLevel--) | Gets bookmark's hierarchy level. |
| [setLevel(int value)](#setLevel-int-) | Sets bookmark's hierarchy level. |
| [getPageDisplay()](#getPageDisplay--) | Gets the type of display bookmark's destination page. |
| [setPageDisplay(String value)](#setPageDisplay-java.lang.String-) | Sets the type of display bookmark's destination page. |
| [getPageDisplay_Bottom()](#getPageDisplay-Bottom--) | Gets the bottom coordinate of page display. |
| [setPageDisplay_Bottom(int value)](#setPageDisplay-Bottom-int-) | Sets the bottom coordinate of page display. |
| [getPageDisplay_Left()](#getPageDisplay-Left--) | Gets the left coordinate of page display. |
| [setPageDisplay_Left(int value)](#setPageDisplay-Left-int-) | Sets the left coordinate of page display. |
| [getPageDisplay_Right()](#getPageDisplay-Right--) | Gets the right coordinate of page display. |
| [setPageDisplay_Right(int value)](#setPageDisplay-Right-int-) | Sets the right coordinate of page display. |
| [getPageDisplay_Top()](#getPageDisplay-Top--) | Gets the top coordinate of page display. |
| [setPageDisplay_Top(int value)](#setPageDisplay-Top-int-) | Sets the top coordinate of page display. |
| [getPageDisplay_Zoom()](#getPageDisplay-Zoom--) | Gets the zoom factor of page display. |
| [setPageDisplay_Zoom(int value)](#setPageDisplay-Zoom-int-) | Sets the zoom factor of page display. |
| [getPageNumber()](#getPageNumber--) | Gets the number of bookmark's destination page. |
| [setPageNumber(int value)](#setPageNumber-int-) | Sets the number of bookmark's destination page. |
| [getRemoteFile()](#getRemoteFile--) | Gets the file (path) which is required for "GoToR" action of bookmark. |
| [setRemoteFile(String value)](#setRemoteFile-java.lang.String-) | Sets the file (path) which is required for "GoToR" action of bookmark. |
| [getTitle()](#getTitle--) | Gets bookmark's title. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets bookmark's title. |
| [getTitleColor()](#getTitleColor--) | Gets the color of bookmark's title. |
| [setTitleColor(Color value)](#setTitleColor-com.aspose.pdf.java.awt.Color-) | Sets the color of bookmark's title. |
| [getOpen()](#getOpen--) |  |
| [setOpen(boolean value)](#setOpen-boolean-) |  |
### Bookmark() {#Bookmark--}
```
public Bookmark()
```


Initializes a new instance of the  Bookmark  class.

### toOutlineItemCollection(IDocument doc) {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
```
public OutlineItemCollection toOutlineItemCollection(IDocument doc)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) |  |

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection)
### getAction() {#getAction--}
```
public String getAction()
```


Gets the action bound with the bookmark. If PageNumber is presented the action can not be specified. The action type includes: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
java.lang.String
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Sets the action bound with the bookmark. If PageNumber is presented the action can not be specified. The action type includes: "GoTo", "GoToR", "Launch", "Named".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBoldFlag() {#getBoldFlag--}
```
public boolean getBoldFlag()
```


Gets the bold flag of bookmark's title.

**Returns:**
boolean
### setBoldFlag(boolean value) {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```


Sets the bold flag of bookmark's title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChildItem() {#getChildItem--}
```
public Bookmarks getChildItem()
```


Gets bookmark's children.

**Returns:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks)
### setChildItem(Bookmarks value) {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
```
public void setChildItem(Bookmarks value)
```


Sets bookmark's children.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Bookmarks](../../com.aspose.pdf.facades/bookmarks) |  |

### getChildItems() {#getChildItems--}
```
public Bookmarks getChildItems()
```


Gets or sets bookmark's children.

**Returns:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks)
### setChildItems(Bookmarks value) {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
```
public void setChildItems(Bookmarks value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Bookmarks](../../com.aspose.pdf.facades/bookmarks) |  |

### getCustomAcorbatViewerMenuActionName() {#getCustomAcorbatViewerMenuActionName--}
```
public System.Enum[] getCustomAcorbatViewerMenuActionName()
```


Gets the action name corresponding to execute a menu item in Acrobat viewer.

**Returns:**
com.aspose.ms.System.Enum[]
### setCustomAcorbatViewerMenuActionName(System.Enum[] value) {#setCustomAcorbatViewerMenuActionName-com.aspose.ms.System.Enum---}
```
public void setCustomAcorbatViewerMenuActionName(System.Enum[] value)
```


Sets the action name corresponding to execute a menu item in Acrobat viewer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Enum[] |  |

### getDestination() {#getDestination--}
```
public String getDestination()
```


Gets bookmark's destination page. Required if action is set as "".

**Returns:**
java.lang.String
### setDestination(String value) {#setDestination-java.lang.String-}
```
public void setDestination(String value)
```


Sets bookmark's destination page. Required if action is set as "".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getItalicFlag() {#getItalicFlag--}
```
public boolean getItalicFlag()
```


Gets the italic flag of bookmark's title.

**Returns:**
boolean
### setItalicFlag(boolean value) {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```


Sets the italic flag of bookmark's title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public int getLevel()
```


Gets bookmark's hierarchy level.

**Returns:**
int
### setLevel(int value) {#setLevel-int-}
```
public void setLevel(int value)
```


Sets bookmark's hierarchy level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageDisplay() {#getPageDisplay--}
```
public String getPageDisplay()
```


Gets the type of display bookmark's destination page.

**Returns:**
java.lang.String
### setPageDisplay(String value) {#setPageDisplay-java.lang.String-}
```
public void setPageDisplay(String value)
```


Sets the type of display bookmark's destination page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPageDisplay_Bottom() {#getPageDisplay-Bottom--}
```
public int getPageDisplay_Bottom()
```


Gets the bottom coordinate of page display.

**Returns:**
int
### setPageDisplay_Bottom(int value) {#setPageDisplay-Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```


Sets the bottom coordinate of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageDisplay_Left() {#getPageDisplay-Left--}
```
public int getPageDisplay_Left()
```


Gets the left coordinate of page display.

**Returns:**
int
### setPageDisplay_Left(int value) {#setPageDisplay-Left-int-}
```
public void setPageDisplay_Left(int value)
```


Sets the left coordinate of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageDisplay_Right() {#getPageDisplay-Right--}
```
public int getPageDisplay_Right()
```


Gets the right coordinate of page display.

**Returns:**
int
### setPageDisplay_Right(int value) {#setPageDisplay-Right-int-}
```
public void setPageDisplay_Right(int value)
```


Sets the right coordinate of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageDisplay_Top() {#getPageDisplay-Top--}
```
public int getPageDisplay_Top()
```


Gets the top coordinate of page display.

**Returns:**
int
### setPageDisplay_Top(int value) {#setPageDisplay-Top-int-}
```
public void setPageDisplay_Top(int value)
```


Sets the top coordinate of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageDisplay_Zoom() {#getPageDisplay-Zoom--}
```
public int getPageDisplay_Zoom()
```


Gets the zoom factor of page display.

**Returns:**
int
### setPageDisplay_Zoom(int value) {#setPageDisplay-Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```


Sets the zoom factor of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Gets the number of bookmark's destination page.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Sets the number of bookmark's destination page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRemoteFile() {#getRemoteFile--}
```
public String getRemoteFile()
```


Gets the file (path) which is required for "GoToR" action of bookmark.

**Returns:**
java.lang.String
### setRemoteFile(String value) {#setRemoteFile-java.lang.String-}
```
public void setRemoteFile(String value)
```


Sets the file (path) which is required for "GoToR" action of bookmark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets bookmark's title.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets bookmark's title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTitleColor() {#getTitleColor--}
```
public Color getTitleColor()
```


Gets the color of bookmark's title.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setTitleColor(Color value) {#setTitleColor-com.aspose.pdf.java.awt.Color-}
```
public void setTitleColor(Color value)
```


Sets the color of bookmark's title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### getOpen() {#getOpen--}
```
public boolean getOpen()
```




**Returns:**
boolean
### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

