---
title: TextSearchOptions
second_title: Aspose.PDF for Java API Reference
description: Represents text search options
type: docs
weight: 385
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIgnoreResourceFontErrors()](#getIgnoreResourceFontErrors--) | Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. |
| [getLimitToPageBounds()](#getLimitToPageBounds--) | Gets indication that text is searched within the page bounds. |
| [getLogTextExtractionErrors()](#getLogTextExtractionErrors--) | Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. |
| [getRectangle()](#getRectangle--) | Gets rectangle that bounds the searched text. |
| [getSearchForTextRelatedGraphics()](#getSearchForTextRelatedGraphics--) | Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. |
| [getStoredGraphicElementsMaxCount()](#getStoredGraphicElementsMaxCount--) | Gets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. |
| [getUseFontEngineEncoding()](#getUseFontEngineEncoding--) | Gets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value) |
| [hashCode()](#hashCode--) |  |
| [isDotallMode()](#isDotallMode--) | In dotall mode, the expression . matches any character, including a line terminator. |
| [isIgnoreShadowText()](#isIgnoreShadowText--) | Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value) |
| [isRegularExpressionUsed()](#isRegularExpressionUsed--) | Indicated that regular expression is used or not |
| [isSearchInAnnotations()](#isSearchInAnnotations--) | Gets or sets value that permits searching for text in Annotations. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDotallMode(boolean dotallMode)](#setDotallMode-boolean-) | Enables dotall mode. |
| [setIgnoreResourceFontErrors(boolean value)](#setIgnoreResourceFontErrors-boolean-) | Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. |
| [setIgnoreShadowText(boolean value)](#setIgnoreShadowText-boolean-) | Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value) |
| [setLimitToPageBounds(boolean value)](#setLimitToPageBounds-boolean-) | Sets indication that text is searched within the page bounds. |
| [setLogTextExtractionErrors(boolean value)](#setLogTextExtractionErrors-boolean-) | Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Sets rectangle that bounds the searched text. |
| [setRegularExpressionUsed(boolean value)](#setRegularExpressionUsed-boolean-) | Indicated that regular expression is used or not |
| [setSearchForTextRelatedGraphics(boolean value)](#setSearchForTextRelatedGraphics-boolean-) | Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. |
| [setSearchInAnnotations(boolean value)](#setSearchInAnnotations-boolean-) | Gets or sets value that permits searching for text in Annotations. |
| [setStoredGraphicElementsMaxCount(int value)](#setStoredGraphicElementsMaxCount-int-) | Sets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. |
| [setUseFontEngineEncoding(boolean value)](#setUseFontEngineEncoding-boolean-) | Sets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getIgnoreResourceFontErrors() {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```


Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false (default) - absence of font error will terminate processing by throwing exception.

**Returns:**
boolean - boolean value
### getLimitToPageBounds() {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```


Gets indication that text is searched within the page bounds.

**Returns:**
boolean - boolean value
### getLogTextExtractionErrors() {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```


Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging.

**Returns:**
boolean - boolean value
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle that bounds the searched text. The property may be used in case it is required to delimit text extraction or text replace region.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value
### getSearchForTextRelatedGraphics() {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```


Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. true - searching for text related graphics will be performed (default value). false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping.

**Returns:**
boolean - boolean value
### getStoredGraphicElementsMaxCount() {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```


Gets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found.

**Returns:**
int - int value
### getUseFontEngineEncoding() {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```


Gets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value)

**Returns:**
boolean - boolean value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDotallMode() {#isDotallMode--}
```
public static boolean isDotallMode()
```


In dotall mode, the expression . matches any character, including a line terminator. By default this expression does not match line terminators.

**Returns:**
boolean - boolean value
### isIgnoreShadowText() {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```


Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value)

**Returns:**
boolean - boolean value
### isRegularExpressionUsed() {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```


Indicated that regular expression is used or not

**Returns:**
boolean - boolean value
### isSearchInAnnotations() {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```


Gets or sets value that permits searching for text in Annotations. true - text will be searched in Annotations. false - text in Annotations won't be parsed by TextFragmentAbsorber.

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

### setIgnoreResourceFontErrors(boolean value) {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```


Gets or sets indication that errors related to absence of font will be ignored by text (fragment) absorber. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false (default) - absence of font error will terminate processing by throwing exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setIgnoreShadowText(boolean value) {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```


Gets or sets indication that text fragments representing shadow of normal text will be ignored during search. true - means that shadow text will not be found (try this if text search returns duplicated fragments on the close positions) false - means that shadow text will be found as well as normal text (default value)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLimitToPageBounds(boolean value) {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```


Sets indication that text is searched within the page bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLogTextExtractionErrors(boolean value) {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```


Gets or sets indication that text extraction (decoding) errors will be logged in the text (fragment) absorber. true - means that text extraction (decoding) errors will be loged. It may decrease performance. false (default) - no error loging.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Sets rectangle that bounds the searched text. The property may be used in case it is required to delimit text extraction or text replace region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### setRegularExpressionUsed(boolean value) {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```


Indicated that regular expression is used or not

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSearchForTextRelatedGraphics(boolean value) {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```


Gets or sets value that permits searching for text related graphics (underlining, background etc.) during text search. true - searching for text related graphics will be performed (default value). false - graphic elements that may present in source document will be ignored. Set this in case of performance issues or no need to handle underlining, background, or clipping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSearchInAnnotations(boolean value) {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```


Gets or sets value that permits searching for text in Annotations. true - text will be searched in Annotations. false - text in Annotations won't be parsed by TextFragmentAbsorber.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setStoredGraphicElementsMaxCount(int value) {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```


Sets value that limits searching for text related graphics (underlining, background etc.) on a page for the speciefied number of elements. The default is 250. Set lesser value in the case of performance problems, try larger value in the case some graphic elements wasn't found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setUseFontEngineEncoding(boolean value) {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```


Sets indication that text will be searched using font engine encoding. true - means that font engine encoding will be used (try this if text search fails because of imperfect encoding in the document) false - means that document font encoding will be used (default value)

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

