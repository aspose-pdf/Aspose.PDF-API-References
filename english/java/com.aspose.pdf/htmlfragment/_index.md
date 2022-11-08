---
title: HtmlFragment
second_title: Aspose.PDF for Java API Reference
description: Represents html fragment.
type: docs
weight: 157
url: /java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.FormattedFragment](../../com.aspose.pdf/formattedfragment)
```
public final class HtmlFragment extends FormattedFragment
```

Represents html fragment.
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlFragment(String text)](#HtmlFragment-java.lang.String-) | Initializes a new instance of the HtmlFragment class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clones html fragment. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHtmlLoadOptions()](#getHtmlLoadOptions--) | Gets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getRectangle()](#getRectangle--) | Gets rectangle of the HtmlFragment |
| [getTextState()](#getTextState--) | Gets or sets font |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [hashCode()](#hashCode--) |  |
| [isBreakWords()](#isBreakWords--) | Gets or sets words break |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [isParagraphHasMargin()](#isParagraphHasMargin--) | Gets or sets is paragraph has default margin otherwise margin is 0 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBreakWords(boolean value)](#setBreakWords-boolean-) | Gets or sets words break |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [setHtmlLoadOptions(HtmlLoadOptions value)](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Sets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setParagraphHasMargin(boolean value)](#setParagraphHasMargin-boolean-) | Gets or sets is paragraph has default margin otherwise margin is 0 |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | Gets or sets font |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlFragment(String text) {#HtmlFragment-java.lang.String-}
```
public HtmlFragment(String text)
```


Initializes a new instance of the HtmlFragment class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones html fragment.

**Returns:**
java.lang.Object - Cloned html fragment object.
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
### getHtmlLoadOptions() {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```


Gets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used.

**Returns:**
[HtmlLoadOptions](../../com.aspose.pdf/htmlloadoptions) - HtmlLoadOptions value
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Gets the fragment hyperlink(for pdf generator).

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - the fragment hyperlink(for pdf generator).
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```


Gets rectangle of the HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float - java.awt.geom.Rectangle2D.Float instance
### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Gets or sets font

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState object
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
### isBreakWords() {#isBreakWords--}
```
public final boolean isBreakWords()
```


Gets or sets words break

**Returns:**
boolean - boolean value
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
### isParagraphHasMargin() {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```


Gets or sets is paragraph has default margin otherwise margin is 0

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




### setBreakWords(boolean value) {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```


Gets or sets words break

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

### setHtmlLoadOptions(HtmlLoadOptions value) {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
```
public void setHtmlLoadOptions(HtmlLoadOptions value)
```


Sets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HtmlLoadOptions](../../com.aspose.pdf/htmlloadoptions) | HtmlLoadOptions value |

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

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setParagraphHasMargin(boolean value) {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```


Gets or sets is paragraph has default margin otherwise margin is 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public void setTextState(TextState value)
```


Gets or sets font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState object |

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

