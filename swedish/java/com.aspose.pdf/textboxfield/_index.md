---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar ett textrutefält."
type: docs
weight: 4930
url: /sv/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

Klass som representerar ett textrutefält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextBoxField](#TextBoxField--) | Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc) |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | Lägger till streckkod 128 i fältet. Fältvärdet kommer att ändras till koden och fältet blir skrivskyddat. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Lägger till en bild i fältresurserna och ritar den. |
| [getForceCombs](#getForceCombs--) | Hämtar flagga som indikerar om fältet är uppdelat i separata positioner. |
| [getMaxLen](#getMaxLen--) | Hämtar maximal längd för text i fältet. |
| [getMultiline](#getMultiline--) | Hämtar flerradig flagga för fältet. Om Multiline är true kan fältet innehålla flera rader text. |
| [getScrollable](#getScrollable--) | Hämtar rullningsbar flagga för fältet. Om true kan fältet rullas. |
| [getSpellCheck](#getSpellCheck--) | Hämtar stavningskontroll-flagga för fältet. Om true ska fältet stavningskontrolleras. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | Hämtar eller anger vertikal justering av text för annotation. |
| [getValue](#getValue--) | Hämtar värdet för fältet. |
| [setForceCombs](#setForceCombs-boolean-) | Anger flagga som indikerar om fältet är uppdelat i avståndspositioner. |
| [setJustification](#setJustification-boolean-) | Anger justering |
| [setMaxLen](#setMaxLen-int-) | Anger maximal längd för text i fältet. |
| [setMultiline](#setMultiline-boolean-) | Anger flerradig flagga för fältet. Om Multiline är sant kan fältet innehålla flera rader text. |
| [setScrollable](#setScrollable-boolean-) | Anger rullningsbar flagga för fältet. Om sant kan fältet rullas. |
| [setSpellCheck](#setSpellCheck-boolean-) | Anger stavningskontrollflagga för fältet. Om sant ska fältet stavningskontrolleras. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Hämtar eller anger vertikal justering av text för annotation. |
| [setValue](#setValue-java.lang.String-) | Anger värdet för fältet. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
Skapa en instans av TextBoxField. @deprecated För fullständig fältfunktionalitet krävs en bindning till dokumentet - använd TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
Lägger till streckkod 128 i fältet. Fältvärdet kommer att ändras till koden och fältet blir skrivskyddat.

### addImage {#addImage-java.awt.image.BufferedImage-}
Lägger till en bild i fältresurserna och ritar den.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

Hämtar flagga som indikerar om fältet är uppdelat i separata positioner.

**Returns:**
booleskt värde

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

Hämtar maximal längd för text i fältet.

**Returns:**
int‑värde

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

Hämtar flerradig flagga för fältet. Om Multiline är true kan fältet innehålla flera rader text.

**Returns:**
booleskt värde

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

Hämtar rullningsbar flagga för fältet. Om true kan fältet rullas.

**Returns:**
booleskt värde

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

Hämtar stavningskontroll-flagga för fältet. Om true ska fältet stavningskontrolleras.

**Returns:**
booleskt värde

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

Hämtar eller anger vertikal justering av text för annotation.

**Returns:**
VerticalAlignment-element

### getValue {#getValue--}
```
public String getValue()
```

Hämtar värdet för fältet.

**Returns:**
String värde

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

Anger flagga som indikerar om fältet är uppdelat i avståndspositioner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

Anger justering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

Anger maximal längd för text i fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

Anger flerradig flagga för fältet. Om Multiline är sant kan fältet innehålla flera rader text.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

Anger rullningsbar flagga för fältet. Om sant kan fältet rullas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

Anger stavningskontrollflagga för fältet. Om sant ska fältet stavningskontrolleras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Hämtar eller anger vertikal justering av text för annotation.

### setValue {#setValue-java.lang.String-}
Anger värdet för fältet.
