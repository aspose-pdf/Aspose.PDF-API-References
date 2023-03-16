---
title: TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for Java API Reference
description: Action to perform if font does not contain required character
type: docs
weight: 13
url: /java/com.aspose.pdf/texteditoptions.nocharacteraction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextEditOptions.NoCharacterAction extends Enum<TextEditOptions.NoCharacterAction>
```

Action to perform if font does not contain required character
## Fields

| Field | Description |
| --- | --- |
| [ThrowException](#ThrowException) | Throw exception |
| [UseStandardFont](#UseStandardFont) | Repalce font to standard font which contains required character |
| [ReplaceAnyway](#ReplaceAnyway) | Replace text anyway without font substitution |
| [UseCustomReplacementFont](#UseCustomReplacementFont) | Repalce font to defined replacement font |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getValue()](#getValue--) |  |
### ThrowException {#ThrowException}
```
public static final TextEditOptions.NoCharacterAction ThrowException
```


Throw exception

### UseStandardFont {#UseStandardFont}
```
public static final TextEditOptions.NoCharacterAction UseStandardFont
```


Repalce font to standard font which contains required character

### ReplaceAnyway {#ReplaceAnyway}
```
public static final TextEditOptions.NoCharacterAction ReplaceAnyway
```


Replace text anyway without font substitution

### UseCustomReplacementFont {#UseCustomReplacementFont}
```
public static final TextEditOptions.NoCharacterAction UseCustomReplacementFont
```


Repalce font to defined replacement font

### values() {#values--}
```
public static TextEditOptions.NoCharacterAction[] values()
```




**Returns:**
com.aspose.pdf.TextEditOptions.NoCharacterAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextEditOptions.NoCharacterAction valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[NoCharacterAction](../../com.aspose.pdf/nocharacteraction)
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
