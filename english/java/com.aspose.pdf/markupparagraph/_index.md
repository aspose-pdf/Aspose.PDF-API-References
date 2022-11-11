---
title: MarkupParagraph
second_title: Aspose.PDF for Java API Reference
description: Represents a paragraph.
type: docs
weight: 207
url: /java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object
```
public final class MarkupParagraph
```

Represents a paragraph.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContinuationPageNumbers()](#getContinuationPageNumbers--) | List of page numbers on which the paragraph is continued. |
| [getFragments()](#getFragments--) | Collection of not empty  TextFragment  objects of the paragraph. |
| [getLines()](#getLines--) | Lines of paragraph. |
| [getPoints()](#getPoints--) | Points of polygon that describes paragraph. |
| [getSecondaryPoints()](#getSecondaryPoints--) | Points of secondary polygon describes paragraph continuation. |
| [getText()](#getText--) | Gets  string  text object that the  MarkupParagraph  object represents. |
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
### getContinuationPageNumbers() {#getContinuationPageNumbers--}
```
public final List<Integer> getContinuationPageNumbers()
```


List of page numbers on which the paragraph is continued. It will match with page where the paragraph started if it is continuing in the next column on the same page.

**Returns:**
java.util.List<java.lang.Integer> - list of Integer
### getFragments() {#getFragments--}
```
public List<TextFragment> getFragments()
```


Collection of not empty  TextFragment  objects of the paragraph.

--------------------

The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
java.util.List<com.aspose.pdf.TextFragment> - list of TextFragment instances
### getLines() {#getLines--}
```
public List<System.Collections.Generic.List<TextFragment>> getLines()
```


Lines of paragraph. Each line represented by list of text fragments.

--------------------

The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
java.util.List<com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.TextFragment>> - list of TextFragment instances
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Points of polygon that describes paragraph. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence.

**Returns:**
com.aspose.pdf.Point[] - array of Point instances
### getSecondaryPoints() {#getSecondaryPoints--}
```
public final List<Point[]> getSecondaryPoints()
```


Points of secondary polygon describes paragraph continuation. It will not be null if the paragraph is continued in the next column or page. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence.

**Returns:**
java.util.List<com.aspose.pdf.Point[]> - list of Point[]
### getText() {#getText--}
```
public String getText()
```


Gets  string  text object that the  MarkupParagraph  object represents.

**Returns:**
java.lang.String - String value
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

