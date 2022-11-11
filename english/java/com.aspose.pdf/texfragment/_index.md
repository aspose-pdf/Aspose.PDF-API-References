---
title: TeXFragment
second_title: Aspose.PDF for Java API Reference
description: Represents LaTeX fragment.
type: docs
weight: 356
url: /java/com.aspose.pdf/texfragment/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.FormattedFragment](../../com.aspose.pdf/formattedfragment)
```
public class TeXFragment extends FormattedFragment
```

Represents LaTeX fragment.
## Constructors

| Constructor | Description |
| --- | --- |
| [TeXFragment(String text)](#TeXFragment-java.lang.String-) | Initializes a new instance of the HtmlFragment class. |
| [TeXFragment(String text, boolean removeIndents)](#TeXFragment-java.lang.String-boolean-) | Initializes a new instance of the HtmlFragment class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clones fragment. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getLatexLoadOptionsOfInstance()](#getLatexLoadOptionsOfInstance--) | Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getTeXLoadOptionsOfInstance()](#getTeXLoadOptionsOfInstance--) | Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [hashCode()](#hashCode--) |  |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setLatexLoadOptionsOfInstance(TeXLoadOptions value)](#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setTeXLoadOptionsOfInstance(TeXLoadOptions value)](#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | Gets or sets LatexLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TeXFragment(String text) {#TeXFragment-java.lang.String-}
```
public TeXFragment(String text)
```


Initializes a new instance of the HtmlFragment class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text |

### TeXFragment(String text, boolean removeIndents) {#TeXFragment-java.lang.String-boolean-}
```
public TeXFragment(String text, boolean removeIndents)
```


Initializes a new instance of the HtmlFragment class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text |
| removeIndents | boolean | Determines whether not to make indents while typesetting LaTeX fragment |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones fragment.

**Returns:**
java.lang.Object - Cloned fragment.
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
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a horizontal alignment of paragraph

**Returns:**
int - HorizontalAlignment value
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Gets the fragment hyperlink(for pdf generator).

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - the fragment hyperlink(for pdf generator).
### getLatexLoadOptionsOfInstance() {#getLatexLoadOptionsOfInstance--}
```
public final TeXLoadOptions getLatexLoadOptionsOfInstance()
```


Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used.

**Returns:**
[TeXLoadOptions](../../com.aspose.pdf/texloadoptions) - TeXLoadOptions instance
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### getTeXLoadOptionsOfInstance() {#getTeXLoadOptionsOfInstance--}
```
public TeXLoadOptions getTeXLoadOptionsOfInstance()
```


Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used.

**Returns:**
[TeXLoadOptions](../../com.aspose.pdf/texloadoptions) - TeXLoadOptions instance
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a vertical alignment of paragraph

**Returns:**
int - VerticalAlignment element
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Gets a paragraph is inline. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

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




### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a horizontal alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Sets hyperlink(for pdf generator).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | hyperlink(for pdf generator). |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Sets a paragraph is inline. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLatexLoadOptionsOfInstance(TeXLoadOptions value) {#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
```
public final void setLatexLoadOptionsOfInstance(TeXLoadOptions value)
```


Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TeXLoadOptions](../../com.aspose.pdf/texloadoptions) | TeXLoadOptions instance |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setTeXLoadOptionsOfInstance(TeXLoadOptions value) {#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
```
public void setTeXLoadOptionsOfInstance(TeXLoadOptions value)
```


Gets or sets LatexLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TeXLoadOptions](../../com.aspose.pdf/texloadoptions) | TeXLoadOptions instance |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

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

