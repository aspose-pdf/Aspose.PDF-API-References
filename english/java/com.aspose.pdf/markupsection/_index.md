---
title: MarkupSection
second_title: Aspose.PDF for Java API Reference
description: Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks.
type: docs
weight: 208
url: /java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object
```
public final class MarkupSection
```

Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFragments()](#getFragments--) | Collection of not empty  TextFragment  objects that are inside the section. |
| [getParagraphs()](#getParagraphs--) | Collection of  MarkupParagraph  objects that are inside the section. |
| [getRectangle()](#getRectangle--) | Section rectangle |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFragments() {#getFragments--}
```
public List<TextFragment> getFragments()
```


Collection of not empty  TextFragment  objects that are inside the section.

--------------------

The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
java.util.List<com.aspose.pdf.TextFragment> - list of TextFragment instances
### getParagraphs() {#getParagraphs--}
```
public List<MarkupParagraph> getParagraphs()
```


Collection of  MarkupParagraph  objects that are inside the section.

**Returns:**
java.util.List<com.aspose.pdf.MarkupParagraph> - list of MarkupParagraph instances
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Section rectangle

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle instance
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

