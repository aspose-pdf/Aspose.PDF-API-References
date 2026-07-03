---
title: HtmlFragment
second_title: Aspose.PDF for Java API Reference
description: Represents html fragment.
type: docs
weight: 1950
url: /java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

Represents html fragment.

## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | Initializes a new instance of the HtmlFragment class. |

## Methods

| Method | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clones html fragment. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Gets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used. |
| [getRectangle](#getRectangle--) | Gets rectangle of the HtmlFragment |
| [getTextState](#getTextState--) | Gets or sets font |
| [isBreakWords](#isBreakWords--) | Gets or sets words break |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Gets or sets is paragraph has default margin otherwise margin is 0 |
| [setBreakWords](#setBreakWords-boolean-) | Gets or sets words break |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Sets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Gets or sets is paragraph has default margin otherwise margin is 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Gets or sets font |

### HtmlFragment {#HtmlFragment-java.lang.String-}
Initializes a new instance of the HtmlFragment class.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clones html fragment.

**Returns:**
Cloned html fragment object.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Gets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used.

**Returns:**
HtmlLoadOptions value

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Gets rectangle of the HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float instance

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Gets or sets font

**Returns:**
TextState object

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Gets or sets words break

**Returns:**
boolean value

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Gets or sets is paragraph has default margin otherwise margin is 0

**Returns:**
boolean value

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Gets or sets words break

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Sets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Gets or sets is paragraph has default margin otherwise margin is 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Gets or sets font
