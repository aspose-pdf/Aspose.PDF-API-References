---
title: TextSearchOptions
linktitle: TextSearchOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text search options
type: docs
weight: 5290
url: /java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Represents text search options

## Constructors

| Constructor | Description |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Initializes new instance of the {@code TextSearchOptions} object. Specifies regular expression usage mode. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Initializes new instance of the TextSearchOptions object. Specifies rectangle that delimits the searched text. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Initializes new instance of the TextSearchOptions object. Specifies rectangle that delimits the searched text and regular expression usage mode. |

## Methods

| Method | Description |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Gets or sets rectangles whose borders exclude text from the search. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false (default) - absence of font error will terminate processing by throwing exception. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Gets indication that text is searched within the page bounds. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging. |
| [getRectangle](#getRectangle--) | Gets rectangle that bounds the searched text. The property may be used in case it is required to delimit text extraction or text replace region. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. true - searching for text related graphics will be performed (default value). false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Gets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Gets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value) |
| [isDotallMode](#isDotallMode--) | <p> In dotall mode, the expression <tt>.</tt> matches any character, including a line terminator. By default this expression does not match line terminators. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value) |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Indicated that regular expression is used or not |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Gets or sets value that permits searching for text in Annotations. true - text will be searched in Annotations. false - text in Annotations won't be parsed by TextFragmentAbsorber. |
| [setDotallMode](#setDotallMode-boolean-) | Enables dotall mode. <p> In dotall mode, the expression <tt>.</tt> matches any character, including a line terminator. By default this expression does not match line terminators. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Gets or sets rectangles whose borders exclude text from the search. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false (default) - absence of font error will terminate processing by throwing exception. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value) |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Sets indication that text is searched within the page bounds. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Sets rectangle that bounds the searched text. The property may be used in case it is required to delimit text extraction or text replace region. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Indicated that regular expression is used or not |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. true - searching for text related graphics will be performed (default value). false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Gets or sets value that permits searching for text in Annotations. true - text will be searched in Annotations. false - text in Annotations won't be parsed by TextFragmentAbsorber. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Sets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Sets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value) |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Initializes new instance of the {@code TextSearchOptions} object. Specifies regular expression usage mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isRegularExpressionUsed |  | Value that indicates that regularexpression is used. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Initializes new instance of the TextSearchOptions object. Specifies rectangle that delimits the searched text.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Initializes new instance of the TextSearchOptions object. Specifies rectangle that delimits the searched text and regular expression usage mode.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Gets or sets rectangles whose borders exclude text from the search.

**Returns:**
array of Rectangle instances

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false (default) - absence of font error will terminate processing by throwing exception.

**Returns:**
boolean value

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Gets indication that text is searched within the page bounds.

**Returns:**
boolean value

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging.

**Returns:**
boolean value

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle that bounds the searched text. The property may be used in case it is required to delimit text extraction or text replace region.

**Returns:**
Rectangle value

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. true - searching for text related graphics will be performed (default value). false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping.

**Returns:**
boolean value

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Gets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found.

**Returns:**
int value

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Gets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value)

**Returns:**
boolean value

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> In dotall mode, the expression <tt>.</tt> matches any character, including a line terminator. By default this expression does not match line terminators.

**Returns:**
boolean value

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value)

**Returns:**
boolean value

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Indicated that regular expression is used or not

**Returns:**
boolean value

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Gets or sets value that permits searching for text in Annotations. true - text will be searched in Annotations. false - text in Annotations won't be parsed by TextFragmentAbsorber.

**Returns:**
boolean value

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Enables dotall mode. <p> In dotall mode, the expression <tt>.</tt> matches any character, including a line terminator. By default this expression does not match line terminators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dotallMode |  | boolean value |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Gets or sets rectangles whose borders exclude text from the search.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false (default) - absence of font error will terminate processing by throwing exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Sets indication that text is searched within the page bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Sets rectangle that bounds the searched text. The property may be used in case it is required to delimit text extraction or text replace region.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Indicated that regular expression is used or not

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. true - searching for text related graphics will be performed (default value). false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Gets or sets value that permits searching for text in Annotations. true - text will be searched in Annotations. false - text in Annotations won't be parsed by TextFragmentAbsorber.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Sets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Sets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
