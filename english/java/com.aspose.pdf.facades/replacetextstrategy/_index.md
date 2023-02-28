---
title: ReplaceTextStrategy
second_title: Aspose.PDF for Java API Reference
description: This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed.
type: docs
weight: 52
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
| [setNoCharacterBehavior(ReplaceTextStrategy.NoCharacterAction value)](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [getReplaceScope()](#getReplaceScope--) | Scope of the replacement operation (replace first occurence or replace all occurences). |
| [setReplaceScope(ReplaceTextStrategy.Scope value)](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Scope of the replacement operation (replace first occurence or replace all occurences). |
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
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```


Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway).

**Returns:**
[NoCharacterAction](../../com.aspose.pdf.facades/nocharacteraction) - NoCharacterAction value.
### setNoCharacterBehavior(ReplaceTextStrategy.NoCharacterAction value) {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
```
public void setNoCharacterBehavior(ReplaceTextStrategy.NoCharacterAction value)
```


Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NoCharacterAction](../../com.aspose.pdf.facades/nocharacteraction) | NoCharacterAction value. |

### getReplaceScope() {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```


Scope of the replacement operation (replace first occurence or replace all occurences).

**Returns:**
[Scope](../../com.aspose.pdf.facades/scope) - Scope element
### setReplaceScope(ReplaceTextStrategy.Scope value) {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
```
public void setReplaceScope(ReplaceTextStrategy.Scope value)
```


Scope of the replacement operation (replace first occurence or replace all occurences).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Scope](../../com.aspose.pdf.facades/scope) | int value |

