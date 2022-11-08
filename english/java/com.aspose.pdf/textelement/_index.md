---
title: TextElement
second_title: Aspose.PDF for Java API Reference
description: General text element of document logical structure.
type: docs
weight: 367
url: /java/com.aspose.pdf/textelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Element](../../com.aspose.pdf/element)
```
public class TextElement extends Element
```

General text element of document logical structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextElement(IPdfObject obj)](#TextElement-com.aspose.pdf.engine.data.IPdfObject-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActualText()](#getActualText--) | (Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. |
| [getAlt()](#getAlt--) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes. |
| [getChildren()](#getChildren--) | Gets child elements collection. |
| [getClass()](#getClass--) |  |
| [getE()](#getE--) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| [getLang()](#getLang--) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
| [getText()](#getText--) | Gets the value of text structure element. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | (Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. |
| [setAlt(String value)](#setAlt-java.lang.String-) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes. |
| [setE(String value)](#setE-java.lang.String-) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| [setLang(String value)](#setLang-java.lang.String-) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextElement(IPdfObject obj) {#TextElement-com.aspose.pdf.engine.data.IPdfObject-}
```
public TextElement(IPdfObject obj)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |

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
### getActualText() {#getActualText--}
```
public String getActualText()
```


(Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Returns:**
java.lang.String - String object
### getAlt() {#getAlt--}
```
public String getAlt()
```


(Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Returns:**
java.lang.String - String object
### getChildren() {#getChildren--}
```
public List<Element> getChildren()
```


Gets child elements collection.

**Returns:**
java.util.List<com.aspose.pdf.Element> -  java.util.List  object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getE() {#getE--}
```
public String getE()
```


(Optional; PDF 1.5) The expanded form of an abbreviation.

**Returns:**
java.lang.String - String object
### getLang() {#getLang--}
```
public String getLang()
```


(Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content.

**Returns:**
java.lang.String - String object
### getText() {#getText--}
```
public String getText()
```


Gets the value of text structure element.

**Returns:**
java.lang.String - String object
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




### setActualText(String value) {#setActualText-java.lang.String-}
```
public void setActualText(String value)
```


(Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setAlt(String value) {#setAlt-java.lang.String-}
```
public void setAlt(String value)
```


(Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setE(String value) {#setE-java.lang.String-}
```
public void setE(String value)
```


(Optional; PDF 1.5) The expanded form of an abbreviation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setLang(String value) {#setLang-java.lang.String-}
```
public void setLang(String value)
```


(Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

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

