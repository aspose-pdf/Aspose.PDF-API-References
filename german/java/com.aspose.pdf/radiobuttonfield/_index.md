---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Radio-Button-Feld darstellt."
type: docs
weight: 4080
url: /de/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Klasse, die ein Radio-Button-Feld darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | Konstruktor für RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | Konstruktor für RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Setzt das RadioButton-Feld |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | Fügt ein neues Optionsfeld zum RadioButton-Feld hinzu |
| [addOption](#addOption-java.lang.String-) | Option zum radion-Button hinzufügen. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Füge zur RadioButton-Option mit angegebenem Rechteck hinzu. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Liest oder setzt das Flag, das dem Radiobutton erlaubt, keinen ausgewählten Wert zu haben. Wenn {@code }, ist jederzeit genau ein Radio-Button ausgewählt; das Auswählen des bereits ausgewählten Buttons hat keine Wirkung. Wenn {@code }, wird durch Klicken auf den ausgewählten Button die Auswahl aufgehoben, sodass kein Button ausgewählt ist. </p> <hr> Einige PDF-Reader (einschließlich Adobe Acrobat) können den Zustand des Flags ignorieren. |
| [getOptions](#getOptions--) | Liest die Sammlung der Optionen des Radio-Buttons. |
| [getPageIndex](#getPageIndex--) | Liest den Index der Seite, die dieses RadioButton-Feld enthält. |
| [getSelected](#getSelected--) | Liest den Index des ausgewählten Elements. Die Nummerierung der Elemente beginnt bei 1. |
| [getStyle](#getStyle--) | Stil des Feldkastens. |
| [getValue](#getValue--) | Liest den Wert des Feldes. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Liest oder setzt das Flag, das dem Radiobutton erlaubt, keinen ausgewählten Wert zu haben. Wenn {@code }, ist jederzeit genau ein Radio-Button ausgewählt; das Auswählen des bereits ausgewählten Buttons hat keine Wirkung. Wenn {@code }, wird durch Klicken auf den ausgewählten Button die Auswahl aufgehoben, sodass kein Button ausgewählt ist. </p> <hr> Einige PDF-Reader (einschließlich Adobe Acrobat) können den Zustand des Flags ignorieren. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Verschiebt alle Unterelemente des Radio-Buttons zu den angegebenen Positionen auf der Seite. |
| [setSelected](#setSelected-int-) | Setzt den Index des ausgewählten Elements. Die Nummerierung der Elemente beginnt bei 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Stil des Feldkastens. |
| [setValue](#setValue-java.lang.String-) | Setzt den Wert des Feldes. |
| [updateAppearances](#updateAppearances--) | Aktualisiert den Darstellungswert. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
Konstruktor für RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
Konstruktor für RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Setzt das RadioButton-Feld

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
Fügt ein neues Optionsfeld zum RadioButton-Feld hinzu

### addOption {#addOption-java.lang.String-}
Option zum radion-Button hinzufügen.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Füge zur RadioButton-Option mit angegebenem Rechteck hinzu.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Liest oder setzt das Flag, das dem Radiobutton erlaubt, keinen ausgewählten Wert zu haben. Wenn {@code }, ist jederzeit genau ein Radio-Button ausgewählt; das Auswählen des bereits ausgewählten Buttons hat keine Wirkung. Wenn {@code }, wird durch Klicken auf den ausgewählten Button die Auswahl aufgehoben, sodass kein Button ausgewählt ist. </p> <hr> Einige PDF-Reader (einschließlich Adobe Acrobat) können den Zustand des Flags ignorieren.

**Returns:**
boolescher Wert

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Liest die Sammlung der Optionen des Radio-Buttons.

**Returns:**
OptionCollection‑Objekt

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Liest den Index der Seite, die dieses RadioButton-Feld enthält.

**Returns:**
int-Wert

### getSelected {#getSelected--}
```
public int getSelected()
```

Liest den Index des ausgewählten Elements. Die Nummerierung der Elemente beginnt bei 1.

**Returns:**
int-Wert

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Stil des Feldkastens.

**Returns:**
BoxStyle-Wert @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Liest den Wert des Feldes.

**Returns:**
String Wert

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Liest oder setzt das Flag, das dem Radiobutton erlaubt, keinen ausgewählten Wert zu haben. Wenn {@code }, ist jederzeit genau ein Radio-Button ausgewählt; das Auswählen des bereits ausgewählten Buttons hat keine Wirkung. Wenn {@code }, wird durch Klicken auf den ausgewählten Button die Auswahl aufgehoben, sodass kein Button ausgewählt ist. </p> <hr> Einige PDF-Reader (einschließlich Adobe Acrobat) können den Zustand des Flags ignorieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Verschiebt alle Unterelemente des Radio-Buttons zu den angegebenen Positionen auf der Seite.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Setzt den Index des ausgewählten Elements. Die Nummerierung der Elemente beginnt bei 1.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Stil des Feldkastens.

### setValue {#setValue-java.lang.String-}
Setzt den Wert des Feldes.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Aktualisiert den Darstellungswert.
