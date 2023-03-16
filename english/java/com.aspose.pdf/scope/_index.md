---
title: TextReplaceOptions.Scope
second_title: Aspose.PDF for Java API Reference
description: Scope where replace text operation is applied REPLACE_FIRST by default This obsolete option was kept for compatibility.
type: docs
weight: 11
url: /java/com.aspose.pdf/textreplaceoptions.scope/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextReplaceOptions.Scope extends Enum<TextReplaceOptions.Scope>
```

Scope where replace text operation is applied REPLACE\_FIRST by default This obsolete option was kept for compatibility. It affects to PdfContentEditor and has no effect to TextFragmentAbsorber.
## Fields

| Field | Description |
| --- | --- |
| [REPLACE_FIRST](#REPLACE-FIRST) | Replace only first occurrence of the text on each of affected pages |
| [REPLACE_ALL](#REPLACE-ALL) | Replace all text occurrences on all affected pages |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getValue()](#getValue--) |  |
### REPLACE_FIRST {#REPLACE-FIRST}
```
public static final TextReplaceOptions.Scope REPLACE_FIRST
```


Replace only first occurrence of the text on each of affected pages

### REPLACE_ALL {#REPLACE-ALL}
```
public static final TextReplaceOptions.Scope REPLACE_ALL
```


Replace all text occurrences on all affected pages

### values() {#values--}
```
public static TextReplaceOptions.Scope[] values()
```




**Returns:**
com.aspose.pdf.TextReplaceOptions.Scope[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextReplaceOptions.Scope valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Scope](../../com.aspose.pdf/scope)
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
