---
title: Bookmark
linktitle: Bookmark
second_title: Aspose.PDF for Java API Reference
description: Represents a bookmark.
type: docs
weight: 60
url: /java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Represents a bookmark.

## Constructors

| Constructor | Description |
| --- | --- |
| [Bookmark](#Bookmark--) | Initializes a new instance of the {@code Bookmark} class. |

## Methods

| Method | Description |
| --- | --- |
| [getAction](#getAction--) | Gets the action bound with the bookmark. If PageNumber is presented the action can not be specified. The action type includes: "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | Gets the bold flag of bookmark's title. |
| [getChildItem](#getChildItem--) | Gets bookmark's children. Obsolete("Use getChildItems() property instead of this one.") |
| [getChildItems](#getChildItems--) | Gets bookmark's children. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Not supported yet. The action name corresponding to execute a menu item in Acrobat viewer. |
| [getDestination](#getDestination--) | Gets bookmark's destination page. Required if action is set as "". |
| [getItalicFlag](#getItalicFlag--) | Gets the italic flag of bookmark's title. |
| [getLevel](#getLevel--) | Gets bookmark's hierarchy level. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Gets the bottom coordinate of page display. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Gets the left coordinate of page display. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Gets the right coordinate of page display. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Gets the top coordinate of page display. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Gets the zoom factor of page display. |
| [getPageDisplay](#getPageDisplay--) | Gets the type of display bookmark's destination page. |
| [getPageNumber](#getPageNumber--) | Gets the number of bookmark's destination page. |
| [getRemoteFile](#getRemoteFile--) | Gets the file (path) which is required for "GoToR" action of bookmark. |
| [getTitle](#getTitle--) | Gets bookmark's title. |
| [getTitleColor](#getTitleColor--) | Gets the color of bookmark's title. |
| [isOpen](#isOpen--) | Gets bookmark state (open, close). |
| [setAction](#setAction-java.lang.String-) | Sets the action bound with the bookmark. If PageNumber is presented the action can not be specified. The action type includes: "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | Sets the bold flag of bookmark's title. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Sets bookmark's children. Obsolete("Use setChildItems() property instead of this one.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Sets bookmark's children. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Not supported yet. Sets the action name corresponding to execute a menu item in Acrobat viewer. |
| [setDestination](#setDestination-java.lang.String-) | Sets bookmark's destination page. Required if action is set as "". |
| [setItalicFlag](#setItalicFlag-boolean-) | Sets the italic flag of bookmark's title. |
| [setLevel](#setLevel-int-) | Sets bookmark's hierarchy level. |
| [setOpen](#setOpen-boolean-) | Sets bookmark state (open, close). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Sets the bottom coordinate of page display. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Sets the left coordinate of page display. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Sets the right coordinate of page display. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Sets the top coordinate of page display. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Sets the zoom factor of page display. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Sets the type of display bookmark's destination page. |
| [setPageNumber](#setPageNumber-int-) | Sets the number of bookmark's destination page. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Sets the file (path) which is required for "GoToR" action of bookmark. |
| [setTitle](#setTitle-java.lang.String-) | Sets bookmark's title. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Sets the color of bookmark's title. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | convert to OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Initializes a new instance of the {@code Bookmark} class.

### getAction {#getAction--}
```
public String getAction()
```

Gets the action bound with the bookmark. If PageNumber is presented the action can not be specified. The action type includes: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
String value

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Gets the bold flag of bookmark's title.

**Returns:**
boolean value

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Gets bookmark's children. Obsolete("Use getChildItems() property instead of this one.")

**Returns:**
Bookmarks element

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Gets bookmark's children.

**Returns:**
bookmark's children items.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Not supported yet. The action name corresponding to execute a menu item in Acrobat viewer.

**Returns:**
array of int value

### getDestination {#getDestination--}
```
public String getDestination()
```

Gets bookmark's destination page. Required if action is set as "".

**Returns:**
String value

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Gets the italic flag of bookmark's title.

**Returns:**
boolean value

### getLevel {#getLevel--}
```
public int getLevel()
```

Gets bookmark's hierarchy level.

**Returns:**
int value

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Gets the bottom coordinate of page display.

**Returns:**
int value

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Gets the left coordinate of page display.

**Returns:**
int value

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Gets the right coordinate of page display.

**Returns:**
int value

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Gets the top coordinate of page display.

**Returns:**
int value

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Gets the zoom factor of page display.

**Returns:**
int value

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Gets the type of display bookmark's destination page.

**Returns:**
String value

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Gets the number of bookmark's destination page.

**Returns:**
int value

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Gets the file (path) which is required for "GoToR" action of bookmark.

**Returns:**
String value

### getTitle {#getTitle--}
```
public String getTitle()
```

Gets bookmark's title.

**Returns:**
String value

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Gets the color of bookmark's title.

**Returns:**
Color element

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Gets bookmark state (open, close).

**Returns:**
boolean value

### setAction {#setAction-java.lang.String-}
Sets the action bound with the bookmark. If PageNumber is presented the action can not be specified. The action type includes: "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Sets the bold flag of bookmark's title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Sets bookmark's children. Obsolete("Use setChildItems() property instead of this one.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Sets bookmark's children.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Not supported yet. Sets the action name corresponding to execute a menu item in Acrobat viewer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | array of int value |

### setDestination {#setDestination-java.lang.String-}
Sets bookmark's destination page. Required if action is set as "".

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Sets the italic flag of bookmark's title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Sets bookmark's hierarchy level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Sets bookmark state (open, close).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Sets the bottom coordinate of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Sets the left coordinate of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Sets the right coordinate of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Sets the top coordinate of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Sets the zoom factor of page display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Sets the type of display bookmark's destination page.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Sets the number of bookmark's destination page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Sets the file (path) which is required for "GoToR" action of bookmark.

### setTitle {#setTitle-java.lang.String-}
Sets bookmark's title.

### setTitleColor {#setTitleColor-java.awt.Color-}
Sets the color of bookmark's title.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
convert to OutlineItemCollection
