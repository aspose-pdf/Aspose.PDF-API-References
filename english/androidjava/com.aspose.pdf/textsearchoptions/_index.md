---
title: TextSearchOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text search options
type: docs
weight: 306
url: /java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextSearchOptions extends TextOptions
```

Represents text search options
## Constructors

| Constructor | Description |
| --- | --- |
| [TextSearchOptions(boolean isRegularExpressionUsed)](#TextSearchOptions-boolean-) | Initializes new instance of the  TextSearchOptions  object. |
| [TextSearchOptions(Rectangle rectangle)](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Initializes new instance of the TextSearchOptions object. |
| [TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed)](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Initializes new instance of the TextSearchOptions object. |
## Methods

| Method | Description |
| --- | --- |
| [setDotallMode(boolean dotallMode)](#setDotallMode-boolean-) | Enables dotall mode. |
| [isDotallMode()](#isDotallMode--) | In dotall mode, the expression . matches any character, including a line terminator. |
| [isRegularExpressionUsed()](#isRegularExpressionUsed--) | Indicated that regular expression is used or not |
| [setRegularExpressionUsed(boolean value)](#setRegularExpressionUsed-boolean-) | Indicated that regular expression is used or not |
| [getLimitToPageBounds()](#getLimitToPageBounds--) | Gets indication that text is searched within the page bounds. |
| [setLimitToPageBounds(boolean value)](#setLimitToPageBounds-boolean-) | Sets indication that text is searched within the page bounds. |
| [getRectangle()](#getRectangle--) | Gets rectangle that bounds the searched text. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Sets rectangle that bounds the searched text. |
| [getUseFontEngineEncoding()](#getUseFontEngineEncoding--) | Gets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value) |
| [setUseFontEngineEncoding(boolean value)](#setUseFontEngineEncoding-boolean-) | Sets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value) |
| [isIgnoreShadowText()](#isIgnoreShadowText--) | Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value) |
| [setIgnoreShadowText(boolean value)](#setIgnoreShadowText-boolean-) | Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value) |
| [getLogTextExtractionErrors()](#getLogTextExtractionErrors--) | Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. |
| [setLogTextExtractionErrors(boolean value)](#setLogTextExtractionErrors-boolean-) | Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. |
| [getSearchForTextRelatedGraphics()](#getSearchForTextRelatedGraphics--) | Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. |
| [setSearchForTextRelatedGraphics(boolean value)](#setSearchForTextRelatedGraphics-boolean-) | Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. |
### TextSearchOptions(boolean isRegularExpressionUsed) {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```


Initializes new instance of the  TextSearchOptions  object. Specifies regular expression usage mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isRegularExpressionUsed | boolean | Value that indicates that regularexpression is used. |

### TextSearchOptions(Rectangle rectangle) {#TextSearchOptions-com.aspose.pdf.Rectangle-}
```
public TextSearchOptions(Rectangle rectangle)
```


Initializes new instance of the TextSearchOptions object. Specifies rectangle that delimits the searched text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle that includes the extracted text. |

### TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed) {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
```
public TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed)
```


Initializes new instance of the TextSearchOptions object. Specifies rectangle that delimits the searched text and regular expression usage mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle that includes the extracted text. |
| isRegularExpressionUsed | boolean | Value that indicates that regular expression is used. |

### setDotallMode(boolean dotallMode) {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```


Enables dotall mode.

In dotall mode, the expression . matches any character, including a line terminator. By default this expression does not match line terminators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dotallMode | boolean | boolean value |

### isDotallMode() {#isDotallMode--}
```
public static boolean isDotallMode()
```


In dotall mode, the expression . matches any character, including a line terminator. By default this expression does not match line terminators.

**Returns:**
boolean - boolean value
### isRegularExpressionUsed() {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```


Indicated that regular expression is used or not

**Returns:**
boolean - boolean value
### setRegularExpressionUsed(boolean value) {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```


Indicated that regular expression is used or not

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getLimitToPageBounds() {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```


Gets indication that text is searched within the page bounds.

**Returns:**
boolean - boolean value
### setLimitToPageBounds(boolean value) {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```


Sets indication that text is searched within the page bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle that bounds the searched text. The property may be used in case it is required to delimit text extraction or text replace region.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value
### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Sets rectangle that bounds the searched text. The property may be used in case it is required to delimit text extraction or text replace region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### getUseFontEngineEncoding() {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```


Gets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value)

**Returns:**
boolean - boolean value
### setUseFontEngineEncoding(boolean value) {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```


Sets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isIgnoreShadowText() {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```


Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value)

**Returns:**
boolean - boolean value
### setIgnoreShadowText(boolean value) {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```


Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getLogTextExtractionErrors() {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```


Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging.

**Returns:**
boolean - boolean value
### setLogTextExtractionErrors(boolean value) {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```


Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getSearchForTextRelatedGraphics() {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```


Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. false - graphic elements that may present in source document will be ignored (default value). true - searching for text related graphics will be performed. It may decrease performance of text search and edit. It also may change graphical elements that look like text related.

**Returns:**
boolean - boolean value
### setSearchForTextRelatedGraphics(boolean value) {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```


Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. false - graphic elements that may present in source document will be ignored (default value). true - searching for text related graphics will be performed. It may decrease performance of text search and edit. It also may change graphical elements that look like text related.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

