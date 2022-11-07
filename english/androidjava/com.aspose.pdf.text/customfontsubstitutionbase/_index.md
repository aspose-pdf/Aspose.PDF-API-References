---
title: CustomFontSubstitutionBase
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for custom font substitution strategy.
type: docs
weight: 10
url: /java/com.aspose.pdf.text/customfontsubstitutionbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public class CustomFontSubstitutionBase extends FontSubstitution
```

Represents a base class for custom font substitution strategy.
## Constructors

| Constructor | Description |
| --- | --- |
| [CustomFontSubstitutionBase()](#CustomFontSubstitutionBase--) |  |
## Methods

| Method | Description |
| --- | --- |
| [trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)](#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.text.Font---) | Substitutes original font with another font. |
### CustomFontSubstitutionBase() {#CustomFontSubstitutionBase--}
```
public CustomFontSubstitutionBase()
```


### trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont) {#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.text.Font---}
```
public boolean trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)
```


Substitutes original font with another font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalFontSpecification | [OriginalFontSpecification](../../com.aspose.pdf.text/originalfontspecification) |  |
| substitutionFont | [Font\[\]](../../com.aspose.pdf.text/font) | --------------------

The class CustomFontSubstitutionBase should be inherited to implement custom font substitution logic. TrySubstitute method should be overridden properly: Must return true in case substitution is required. substitutionFont must be set to valid Font object. Must return false in case no substitution is required. substitutionFont may be set to null. |

**Returns:**
boolean - 
