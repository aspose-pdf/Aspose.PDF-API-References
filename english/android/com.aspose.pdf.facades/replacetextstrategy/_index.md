---
title: ReplaceTextStrategy
second_title: Aspose.PDF for Java API Reference
description: This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed.
type: docs
weight: 49
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
| [isRegularExpressionUsed(boolean value)](#isRegularExpressionUsed-boolean-) |  |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) |  |
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
boolean
### isRegularExpressionUsed(boolean value) {#isRegularExpressionUsed-boolean-}
```
public void isRegularExpressionUsed(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNoCharacterBehavior() {#getNoCharacterBehavior--}
```
public int getNoCharacterBehavior()
```


Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway).

**Returns:**
int
### setNoCharacterBehavior(int value) {#setNoCharacterBehavior-int-}
```
public void setNoCharacterBehavior(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReplaceScope() {#getReplaceScope--}
```
public int getReplaceScope()
```


Scope of the replacement operation (replace first occurence or replace all occurences).

**Returns:**
int
### setReplaceScope(int value) {#setReplaceScope-int-}
```
public void setReplaceScope(int value)
```


Scope of the replacement operation (replace first occurence or replace all occurences).

```
Example:
 ReplaceTextStrategy replaceTxt = new ReplaceTextStrategy();
 replaceTxt.setReplaceScope(ReplaceTextStrategy.Scope.REPLACE_ALL);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

