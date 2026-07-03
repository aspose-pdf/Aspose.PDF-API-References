---
title: TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for Java API Reference
description: Action to perform if font does not contain required character
type: docs
weight: 5010
url: /java/com.aspose.pdf/texteditoptions.nocharacteraction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextEditOptions.NoCharacterAction > com.aspose.pdf.TextEditOptions.NoCharacterAction, java.lang.Enum < TextEditOptions.NoCharacterAction >, com.aspose.pdf.TextEditOptions.NoCharacterAction

**All Implemented Interfaces:**
Serializable, Comparable < TextEditOptions.NoCharacterAction >

```
public static enum TextEditOptions.NoCharacterAction extends Enum < TextEditOptions.NoCharacterAction >
```

Action to perform if font does not contain required character

## Fields

| Field | Description |
| --- | --- |
| [ReplaceAnyway](#ReplaceAnyway) | Replace text anyway without font substitution |
| [ReplaceFonts](#ReplaceFonts) | Replaces fonts as necessary to ensure all characters in the text can be displayed. |
| [ThrowException](#ThrowException) | Throw exception |
| [UseCustomReplacementFont](#UseCustomReplacementFont) | Replace font to defined replacement font |
| [UseStandardFont](#UseStandardFont) | Repalce font to standard font which contains required character |

## Methods

| Method | Description |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### ReplaceAnyway {#ReplaceAnyway}
```
public static final TextEditOptions.NoCharacterAction ReplaceAnyway
```

Replace text anyway without font substitution

### ReplaceFonts {#ReplaceFonts}
```
public static final TextEditOptions.NoCharacterAction ReplaceFonts
```

Replaces fonts as necessary to ensure all characters in the text can be displayed.

### ThrowException {#ThrowException}
```
public static final TextEditOptions.NoCharacterAction ThrowException
```

Throw exception

### UseCustomReplacementFont {#UseCustomReplacementFont}
```
public static final TextEditOptions.NoCharacterAction UseCustomReplacementFont
```

Replace font to defined replacement font

### UseStandardFont {#UseStandardFont}
```
public static final TextEditOptions.NoCharacterAction UseStandardFont
```

Repalce font to standard font which contains required character

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static TextEditOptions.NoCharacterAction [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
