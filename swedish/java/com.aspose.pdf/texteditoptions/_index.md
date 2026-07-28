---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Beskriver alternativ för textredigeringsoperationer."
type: docs
weight: 4970
url: /sv/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Beskriver alternativ för textredigeringsoperationer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Initierar en ny instans av {@code TextEditOptions}-objektet för det angivna textomarrangeringsläget. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Hämtar värde som tillåter användning av språktransformation vid tillägg eller redigering av text. true - språktransformation kommer att tillämpas om nödvändigt (standardvärde). false - språktransformation kommer INTE att tillämpas. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Hämtar läge för bearbetning av beskärningsväg för den redigerade texten. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Hämtar läge som definierar beteende för scenarier med teckensnittsersättning. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Hämtar läge som definierar beteende för scenarier med språktransformation. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Hämtar läge som definierar beteende om teckensnitt inte innehåller begärda tecken. |
| [getReplacementFont](#getReplacementFont--) | Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Hämtar eller anger värde som tillåter sökning efter textunderstrykning på sidan i källdokumentet. <p> (Obsolet) Använd TextSearchOptions.SearchForTextRelatedGraphics istället för detta. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Anger värde som tillåter användning av språktransformation vid tillägg eller redigering av text. true - språktransformation kommer att tillämpas om nödvändigt (standardvärde). false - språktransformation kommer INTE att tillämpas. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Hämtar läge för bearbetning av beskärningsväg för den redigerade texten. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Anger läge som definierar beteende för scenarier med teckensnittsersättning. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Anger läge som definierar beteende för scenarier med språktransformation. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Anger läge som definierar beteende om teckensnitt inte innehåller begärda tecken. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Hämtar eller anger värde som tillåter sökning efter textunderstrykning på sidan i källdokumentet. <p> (Obsolet) Använd TextSearchOptions.SearchForTextRelatedGraphics istället för detta. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Initierar en ny instans av {@code TextEditOptions}-objektet för det angivna textomarrangeringsläget. / * / *

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Initierar en ny instans av {@code TextEditOptions}-objektet med standardalternativ. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Hämtar värde som tillåter användning av språktransformation vid tillägg eller redigering av text. true - språktransformation kommer att tillämpas om nödvändigt (standardvärde). false - språktransformation kommer INTE att tillämpas.

**Returns:**
booleskt värde

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Hämtar läge för bearbetning av beskärningsväg för den redigerade texten.

**Returns:**
ClippingPathsProcessingMode element

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Hämtar läge som definierar beteende för scenarier med teckensnittsersättning.

**Returns:**
FontReplace värde @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Hämtar läge som definierar beteende för scenarier med språktransformation.

**Returns:**
LanguageTransformation värde @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Hämtar läge som definierar beteende om teckensnitt inte innehåller begärda tecken.

**Returns:**
NoCharacterAction värde @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet

**Returns:**
Font instans

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Hämtar eller anger värde som tillåter sökning efter textunderstrykning på sidan i källdokumentet. <p> (Obsolet) Använd TextSearchOptions.SearchForTextRelatedGraphics istället för detta. </p>

**Returns:**
booleskt värde

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Anger värde som tillåter användning av språktransformation vid tillägg eller redigering av text. true - språktransformation kommer att tillämpas om nödvändigt (standardvärde). false - språktransformation kommer INTE att tillämpas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Hämtar läge för bearbetning av beskärningsväg för den redigerade texten.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Anger läge som definierar beteende för scenarier med teckensnittsersättning.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Anger läge som definierar beteende för scenarier med språktransformation.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Anger läge som definierar beteende om teckensnitt inte innehåller begärda tecken.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Hämtar eller anger värde som tillåter sökning efter textunderstrykning på sidan i källdokumentet. <p> (Obsolet) Använd TextSearchOptions.SearchForTextRelatedGraphics istället för detta. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
