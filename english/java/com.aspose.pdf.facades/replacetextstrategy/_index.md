---
title: ReplaceTextStrategy
second_title: Aspose.PDF for Java API Reference
description: This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed.
type: docs
weight: 57
url: /java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object
```
public final class ReplaceTextStrategy
```

This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed.
## Constructors

| Constructor | Description |
| --- | --- |
| [ReplaceTextStrategy()](#ReplaceTextStrategy--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isRegularExpressionUsed()](#isRegularExpressionUsed--) | If false, string to find is a simple text. |
| [setRegularExpressionUsed(boolean value)](#setRegularExpressionUsed-boolean-) | If false, string to find is a simple text. |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [getReplaceScope()](#getReplaceScope--) | Scope of the replacement operation (replace first occurence or replace all occurences). |
| [setReplaceScope(int value)](#setReplaceScope-int-) | Scope of the replacement operation (replace first occurence or replace all occurences). |
### ReplaceTextStrategy() {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```


### isRegularExpressionUsed() {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```


If false, string to find is a simple text. If true, string to find is regular expression.

**Returns:**
boolean - boolean value
### setRegularExpressionUsed(boolean value) {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```


If false, string to find is a simple text. If true, string to find is regular expression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getNoCharacterBehavior() {#getNoCharacterBehavior--}
```
public int getNoCharacterBehavior()
```


Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway).

**Returns:**
int - NoCharacterAction value.
### setNoCharacterBehavior(int value) {#setNoCharacterBehavior-int-}
```
public void setNoCharacterBehavior(int value)
```


Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | NoCharacterAction value. |

### getReplaceScope() {#getReplaceScope--}
```
public int getReplaceScope()
```


Scope of the replacement operation (replace first occurence or replace all occurences).

**Returns:**
int - Scope element
### setReplaceScope(int value) {#setReplaceScope-int-}
```
public void setReplaceScope(int value)
```


Scope of the replacement operation (replace first occurence or replace all occurences).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

