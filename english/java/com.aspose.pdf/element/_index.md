---
title: Element
second_title: Aspose.PDF for Java API Reference
description: Class representing base element of logical structure.
type: docs
weight: 1180
url: /java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

Class representing base element of logical structure.

## Methods

| Method | Description |
| --- | --- |
| [getActualText](#getActualText--) | (Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document’s contents in support of accessibility to users with disabilities or for other purposes. |
| [getAlt](#getAlt--) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document’s contents in support of accessibility to users with disabilities or for other purposes. |
| [getChildren](#getChildren--) | Gets child elements collection. |
| [getE](#getE--) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| [getLang](#getLang--) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
| [remove](#remove--) | Remove element. |
| [setActualText](#setActualText-java.lang.String-) | (Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document’s contents in support of accessibility to users with disabilities or for other purposes. |
| [setAlt](#setAlt-java.lang.String-) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document’s contents in support of accessibility to users with disabilities or for other purposes. |
| [setE](#setE-java.lang.String-) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| [setLang](#setLang-java.lang.String-) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document’s contents in support of accessibility to users with disabilities or for other purposes.

**Returns:**
String object

### getAlt {#getAlt--}
```
public String getAlt()
```

(Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document’s contents in support of accessibility to users with disabilities or for other purposes.

**Returns:**
String object

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

Gets child elements collection.

**Returns:**
ElementCollection instance

### getE {#getE--}
```
public String getE()
```

(Optional; PDF 1.5) The expanded form of an abbreviation.

**Returns:**
String object

### getLang {#getLang--}
```
public String getLang()
```

(Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content.

**Returns:**
String object

### remove {#remove--}
```
public final void remove()
```

Remove element.

### setActualText {#setActualText-java.lang.String-}
(Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document’s contents in support of accessibility to users with disabilities or for other purposes.

### setAlt {#setAlt-java.lang.String-}
(Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document’s contents in support of accessibility to users with disabilities or for other purposes.

### setE {#setE-java.lang.String-}
(Optional; PDF 1.5) The expanded form of an abbreviation.

### setLang {#setLang-java.lang.String-}
(Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content.
