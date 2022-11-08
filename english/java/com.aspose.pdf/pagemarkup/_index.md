---
title: PageMarkup
second_title: Aspose.PDF for Java API Reference
description: Page markup represented by collections of MarkupSection and MarkupParagraph.
type: docs
weight: 265
url: /java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object
```
public final class PageMarkup
```

Page markup represented by collections of  MarkupSection  and  MarkupParagraph .
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNumber()](#getNumber--) | Gets processed page number. |
| [getParagraphs()](#getParagraphs--) | Gets collection of  MarkupParagraph  that was found on the page. |
| [getRectangle()](#getRectangle--) | Gets processed page rectangle. |
| [getSections()](#getSections--) | Gets collection of  MarkupSection  that was found on the page. |
| [getTextFragments()](#getTextFragments--) | Gets collection of  TextFragment  that was found on the page. |
| [hashCode()](#hashCode--) |  |
| [isMulticolumnParagraphsAllowed()](#isMulticolumnParagraphsAllowed--) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMulticolumnParagraphsAllowed(boolean value)](#setMulticolumnParagraphsAllowed-boolean-) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
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
### getNumber() {#getNumber--}
```
public int getNumber()
```


Gets processed page number.

**Returns:**
int - int value
### getParagraphs() {#getParagraphs--}
```
public List<MarkupParagraph> getParagraphs()
```


Gets collection of  MarkupParagraph  that was found on the page.

**Returns:**
java.util.List<com.aspose.pdf.MarkupParagraph> - List of MarkupParagraph instances
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets processed page rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getSections() {#getSections--}
```
public List<MarkupSection> getSections()
```


Gets collection of  MarkupSection  that was found on the page.

**Returns:**
java.util.List<com.aspose.pdf.MarkupSection> - List of MarkupSection instances
### getTextFragments() {#getTextFragments--}
```
public List<TextFragment> getTextFragments()
```


Gets collection of  TextFragment  that was found on the page.

--------------------

The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
java.util.List<com.aspose.pdf.TextFragment> - List of TextFragment instances
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isMulticolumnParagraphsAllowed() {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```


Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMulticolumnParagraphsAllowed(boolean value) {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```


Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

