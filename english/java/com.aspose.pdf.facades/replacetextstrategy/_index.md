---
title: ReplaceTextStrategy
linktitle: ReplaceTextStrategy
second_title: Aspose.PDF for Java API Reference
description: This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed.
type: docs
weight: 650
url: /java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed.

## Constructors

| Constructor | Description |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [getReplaceScope](#getReplaceScope--) | Scope of the replacement operation (replace first occurence or replace all occurences). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | If false, string to find is a simple text. If true, string to find is regular expression. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | If false, string to find is a simple text. If true, string to find is regular expression. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Scope of the replacement operation (replace first occurence or replace all occurences). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway).

**Returns:**
NoCharacterAction value. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Scope of the replacement operation (replace first occurence or replace all occurences).

**Returns:**
Scope element @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

If false, string to find is a simple text. If true, string to find is regular expression.

**Returns:**
boolean value

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

If false, string to find is a simple text. If true, string to find is regular expression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Scope of the replacement operation (replace first occurence or replace all occurences).
