---
title: HtmlFragment
second_title: Aspose.PDF for Java API Reference
description: Represents html fragment.
type: docs
weight: 160
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
| [getRectangle()](#getRectangle--) | Gets rectangle of the HtmlFragment |
| [isParagraphHasMargin()](#isParagraphHasMargin--) | Gets or sets is paragraph has default margin otherwise margin is 0 |
| [setParagraphHasMargin(boolean value)](#setParagraphHasMargin-boolean-) | Gets or sets is paragraph has default margin otherwise margin is 0 |
| [isBreakWords()](#isBreakWords--) | Gets or sets words break |
| [setBreakWords(boolean value)](#setBreakWords-boolean-) | Gets or sets words break |
| [getTextState()](#getTextState--) | Gets or sets font |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | Gets or sets font |
| [getHtmlLoadOptions()](#getHtmlLoadOptions--) | Gets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. |
| [setHtmlLoadOptions(HtmlLoadOptions value)](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Sets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. |
| [deepClone()](#deepClone--) | Clones html fragment. |
### HtmlFragment(String text) {#HtmlFragment-java.lang.String-}
```
public HtmlFragment(String text)
```


Initializes a new instance of the HtmlFragment class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text |

### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```


Gets rectangle of the HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float - java.awt.geom.Rectangle2D.Float instance
### isParagraphHasMargin() {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```


Gets or sets is paragraph has default margin otherwise margin is 0

**Returns:**
boolean - boolean value
### setParagraphHasMargin(boolean value) {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```


Gets or sets is paragraph has default margin otherwise margin is 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isBreakWords() {#isBreakWords--}
```
public final boolean isBreakWords()
```


Gets or sets words break

**Returns:**
boolean - boolean value
### setBreakWords(boolean value) {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```


Gets or sets words break

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Gets or sets font

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState object
### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public void setTextState(TextState value)
```


Gets or sets font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState object |

### getHtmlLoadOptions() {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```


Gets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used.

**Returns:**
[HtmlLoadOptions](../../com.aspose.pdf/htmlloadoptions) - HtmlLoadOptions value
### setHtmlLoadOptions(HtmlLoadOptions value) {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
```
public void setHtmlLoadOptions(HtmlLoadOptions value)
```


Sets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HtmlLoadOptions](../../com.aspose.pdf/htmlloadoptions) | HtmlLoadOptions value |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones html fragment.

**Returns:**
java.lang.Object - Cloned html fragment object.
