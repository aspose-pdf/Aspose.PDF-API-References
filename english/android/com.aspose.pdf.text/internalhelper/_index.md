---
title: InternalHelper
second_title: Aspose.PDF for Java API Reference
description: Internal class
type: docs
weight: 17
url: /java/com.aspose.pdf.text/internalhelper/
---
**Inheritance:**
java.lang.Object
```
public class InternalHelper
```

Internal class
## Constructors

| Constructor | Description |
| --- | --- |
| [InternalHelper()](#InternalHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [registerFont(TextProcessingContext value, IPdfFont font)](#registerFont-com.aspose.pdf.text.TextProcessingContext-com.aspose.pdf.engine.commondata.text.fonts.IPdfFont-) |  |
| [getInstance(IContext context)](#getInstance-com.aspose.pdf.engine.data.IContext-) |  |
| [getSubstitutionFontDefinition(FontSubstitution fs)](#getSubstitutionFontDefinition-com.aspose.pdf.text.FontSubstitution-) |  |
| [setSubstitutionFontDefinition(FontSubstitution fs, FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.pdf.text.FontSubstitution-com.aspose.fonts.FontDefinition-) |  |
| [isForcedBySaveOption(SimpleFontSubstitution value)](#isForcedBySaveOption-com.aspose.pdf.text.SimpleFontSubstitution-) |  |
### InternalHelper() {#InternalHelper--}
```
public InternalHelper()
```


### registerFont(TextProcessingContext value, IPdfFont font) {#registerFont-com.aspose.pdf.text.TextProcessingContext-com.aspose.pdf.engine.commondata.text.fonts.IPdfFont-}
```
public static void registerFont(TextProcessingContext value, IPdfFont font)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextProcessingContext](../../com.aspose.pdf.text/textprocessingcontext) |  |
| font | [IPdfFont](../../com.aspose.pdf.engine.commondata.text.fonts/ipdffont) |  |

### getInstance(IContext context) {#getInstance-com.aspose.pdf.engine.data.IContext-}
```
public static TextProcessingContext getInstance(IContext context)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| context | [IContext](../../com.aspose.pdf.engine.data/icontext) |  |

**Returns:**
[TextProcessingContext](../../com.aspose.pdf.text/textprocessingcontext)
### getSubstitutionFontDefinition(FontSubstitution fs) {#getSubstitutionFontDefinition-com.aspose.pdf.text.FontSubstitution-}
```
public static FontDefinition getSubstitutionFontDefinition(FontSubstitution fs)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fs | [FontSubstitution](../../com.aspose.pdf.text/fontsubstitution) |  |

**Returns:**
com.aspose.fonts.FontDefinition
### setSubstitutionFontDefinition(FontSubstitution fs, FontDefinition value) {#setSubstitutionFontDefinition-com.aspose.pdf.text.FontSubstitution-com.aspose.fonts.FontDefinition-}
```
public static void setSubstitutionFontDefinition(FontSubstitution fs, FontDefinition value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fs | [FontSubstitution](../../com.aspose.pdf.text/fontsubstitution) |  |
| value | com.aspose.fonts.FontDefinition |  |

### isForcedBySaveOption(SimpleFontSubstitution value) {#isForcedBySaveOption-com.aspose.pdf.text.SimpleFontSubstitution-}
```
public static boolean isForcedBySaveOption(SimpleFontSubstitution value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SimpleFontSubstitution](../../com.aspose.pdf.text/simplefontsubstitution) |  |

**Returns:**
boolean
