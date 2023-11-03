---
title: Element
second_title: Aspose.PDF for Java API Reference
description: Class representing base element of logical structure.
type: docs
weight: 94
url: /java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object
```
public abstract class Element
```

Class representing base element of logical structure.
## Methods

| Method | Description |
| --- | --- |
| [getChildren()](#getChildren--) | Gets child elements collection. |
| [getLang()](#getLang--) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
| [setLang(String value)](#setLang-java.lang.String-) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
| [getActualText()](#getActualText--) | (Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. |
| [setActualText(String value)](#setActualText-java.lang.String-) | (Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. |
| [getAlt()](#getAlt--) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes. |
| [setAlt(String value)](#setAlt-java.lang.String-) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes. |
| [getE()](#getE--) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| [setE(String value)](#setE-java.lang.String-) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| [remove()](#remove--) | Remove element. |
### getChildren() {#getChildren--}
```
public final ElementCollection getChildren()
```


Gets child elements collection.

**Returns:**
[ElementCollection](../../com.aspose.pdf/elementcollection) - ElementCollection instance
### getLang() {#getLang--}
```
public String getLang()
```


(Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content.

**Returns:**
java.lang.String - String object
### setLang(String value) {#setLang-java.lang.String-}
```
public void setLang(String value)
```


(Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getActualText() {#getActualText--}
```
public String getActualText()
```


(Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Returns:**
java.lang.String - String object
### setActualText(String value) {#setActualText-java.lang.String-}
```
public void setActualText(String value)
```


(Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getAlt() {#getAlt--}
```
public String getAlt()
```


(Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Returns:**
java.lang.String - String object
### setAlt(String value) {#setAlt-java.lang.String-}
```
public void setAlt(String value)
```


(Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getE() {#getE--}
```
public String getE()
```


(Optional; PDF 1.5) The expanded form of an abbreviation.

**Returns:**
java.lang.String - String object
### setE(String value) {#setE-java.lang.String-}
```
public void setE(String value)
```


(Optional; PDF 1.5) The expanded form of an abbreviation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### remove() {#remove--}
```
public final void remove()
```


Remove element.

