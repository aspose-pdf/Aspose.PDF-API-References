---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar radioknappsfält."
type: docs
weight: 4080
url: /sv/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Klass som representerar radioknappsfält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | Konstruktor för RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | Konstruktor för RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Ställer in radioknappfältet |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | Lägger till ett nytt alternativfält till RadioButton-fältet |
| [addOption](#addOption-java.lang.String-) | Lägg till alternativ till radion-knappen |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Lägg till radioknappalternativ med angiven rektangel |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Hämtar eller anger flaggan som tillåter radioknappen att ha inget valt värde. Om {@code } ska exakt en radioknapp vara vald hela tiden; att välja den redan valda knappen har ingen effekt. Om {@code } klickas på den valda knappen avmarkeras den, så att ingen knapp är vald. </p> <hr> Vissa PDF-läsare (inklusive Adobe Acrobat) kan ignorera flaggans tillstånd. |
| [getOptions](#getOptions--) | Hämtar samling av alternativ för radioknappen. |
| [getPageIndex](#getPageIndex--) | Hämtar sidindex för sidan som innehåller detta RadioButton-fält. |
| [getSelected](#getSelected--) | Hämtar index för valt objekt. Numrering av objekt startar från 1. |
| [getStyle](#getStyle--) | Stil för fältboxen. |
| [getValue](#getValue--) | Hämtar värdet för fältet. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Hämtar eller anger flaggan som tillåter radioknappen att ha inget valt värde. Om {@code } ska exakt en radioknapp vara vald hela tiden; att välja den redan valda knappen har ingen effekt. Om {@code } klickas på den valda knappen avmarkeras den, så att ingen knapp är vald. </p> <hr> Vissa PDF-läsare (inklusive Adobe Acrobat) kan ignorera flaggans tillstånd. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Flytta alla underobjekt för radioknappen till angivna positioner på sidan. |
| [setSelected](#setSelected-int-) | Anger index för valt objekt. Numrering av objekt startar från 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Stil för fältboxen. |
| [setValue](#setValue-java.lang.String-) | Anger värdet för fältet. |
| [updateAppearances](#updateAppearances--) | Uppdatera utseendets värde. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
Konstruktor för RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
Konstruktor för RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Ställer in radioknappfältet

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
Lägger till ett nytt alternativfält till RadioButton-fältet

### addOption {#addOption-java.lang.String-}
Lägg till alternativ till radion-knappen

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Lägg till radioknappalternativ med angiven rektangel

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Hämtar eller anger flaggan som tillåter radioknappen att ha inget valt värde. Om {@code } ska exakt en radioknapp vara vald hela tiden; att välja den redan valda knappen har ingen effekt. Om {@code } klickas på den valda knappen avmarkeras den, så att ingen knapp är vald. </p> <hr> Vissa PDF-läsare (inklusive Adobe Acrobat) kan ignorera flaggans tillstånd.

**Returns:**
booleskt värde

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Hämtar samling av alternativ för radioknappen.

**Returns:**
OptionCollection-objekt

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Hämtar sidindex för sidan som innehåller detta RadioButton-fält.

**Returns:**
int‑värde

### getSelected {#getSelected--}
```
public int getSelected()
```

Hämtar index för valt objekt. Numrering av objekt startar från 1.

**Returns:**
int‑värde

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Stil för fältboxen.

**Returns:**
BoxStyle-värde @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Hämtar värdet för fältet.

**Returns:**
String värde

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Hämtar eller anger flaggan som tillåter radioknappen att ha inget valt värde. Om {@code } ska exakt en radioknapp vara vald hela tiden; att välja den redan valda knappen har ingen effekt. Om {@code } klickas på den valda knappen avmarkeras den, så att ingen knapp är vald. </p> <hr> Vissa PDF-läsare (inklusive Adobe Acrobat) kan ignorera flaggans tillstånd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Flytta alla underobjekt för radioknappen till angivna positioner på sidan.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Anger index för valt objekt. Numrering av objekt startar från 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Stil för fältboxen.

### setValue {#setValue-java.lang.String-}
Anger värdet för fältet.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Uppdatera utseendets värde.
