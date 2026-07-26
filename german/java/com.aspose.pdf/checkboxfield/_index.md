---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Kontrollkästchenfeld darstellt"
type: docs
weight: 580
url: /de/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Klasse, die ein Kontrollkästchenfeld darstellt

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CheckboxField](#CheckboxField--) | Erstelle Instanz von CheckboxField. @deprecated Für volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich – verwende CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | Erstelle Instanz von CheckboxField. @deprecated Für volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich – verwende CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Erstelle Instanz von CheckboxField. @deprecated Für volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich – verwende CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Erstelle Instanz von CheckboxField. @deprecated Für volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich – verwende CheckboxField(Document doc) |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Fügt ein neues Kontrollkästchen zu einer Kontrollkästchengruppe hinzu, in der höchstens ein Kontrollkästchen gleichzeitig ausgewählt sein darf. Das neue Kontrollkästchen wird am unteren Ende der Gruppe hinzugefügt. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Fügt ein neues Kontrollkästchen zu einer Kontrollkästchengruppe hinzu, in der höchstens ein Kontrollkästchen gleichzeitig ausgewählt sein darf. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Fügt ein neues Kontrollkästchen zu einer Kontrollkästchengruppe hinzu, in der höchstens ein Kontrollkästchen gleichzeitig ausgewählt sein darf. |
| [deepClone](#deepClone--) | Kopiere das Kontrollkästchen. |
| [getActiveState](#getActiveState--) | Liefert den aktuellen Anzeigestatus der Annotation. |
| [getAllowedStates](#getAllowedStates--) | Gibt die Liste der zulässigen Zustände zurück. |
| [getChecked](#getChecked--) | Liest den Zustand des Kontrollkästchens. |
| [getExportValue](#getExportValue--) | Liest oder setzt den Exportwert des CheckBox-Feldes. |
| [getNormalCaption](#getNormalCaption--) | Liest die normale Beschriftung des Feldes. |
| [getOnState](#getOnState--) | Gibt den Namen des Zustands zurück, der dem "Checked"-Zustand des Kontrollkästchens entspricht. Dies ist "Yes", wenn vorhanden, oder ein anderer Wert außer "Off" und "No"; |
| [getStyle](#getStyle--) | Liefert den Stil des Kontrollkästchens. |
| [getValue](#getValue--) | Liest den Wert des Kontrollkästchenfeldes. |
| [setActiveState](#setActiveState-java.lang.String-) | Legt den aktuellen Anmerkungs‑Erscheinungszustand fest. |
| [setChecked](#setChecked-boolean-) | Setzt den Zustand des Kontrollkästchens. |
| [setExportValue](#setExportValue-java.lang.String-) | Liest oder setzt den Exportwert des CheckBox-Feldes. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Setzt den Stil des Kontrollkästchens. |
| [setValue](#setValue-java.lang.String-) | Setzt den Wert des Kontrollkästchenfeldes. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

Erstelle Instanz von CheckboxField. @deprecated Für volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich – verwende CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
Erstelle Instanz von CheckboxField. @deprecated Für volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich – verwende CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Erstelle Instanz von CheckboxField. @deprecated Für volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich – verwende CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Erstelle Instanz von CheckboxField. @deprecated Für volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich – verwende CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
Fügt ein neues Kontrollkästchen zu einer Kontrollkästchengruppe hinzu, in der höchstens ein Kontrollkästchen gleichzeitig ausgewählt sein darf. Das neue Kontrollkästchen wird am unteren Ende der Gruppe hinzugefügt.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Fügt ein neues Kontrollkästchen zu einer Kontrollkästchengruppe hinzu, in der höchstens ein Kontrollkästchen gleichzeitig ausgewählt sein darf.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Fügt ein neues Kontrollkästchen zu einer Kontrollkästchengruppe hinzu, in der höchstens ein Kontrollkästchen gleichzeitig ausgewählt sein darf.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Kopiere das Kontrollkästchen.

**Returns:**
Das geklonte Objekt

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Liefert den aktuellen Anzeigestatus der Annotation.

**Returns:**
String Wert

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

Gibt die Liste der zulässigen Zustände zurück.

**Returns:**
Liste von String-Werten

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Liest den Zustand des Kontrollkästchens.

**Returns:**
boolescher Wert

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

Liest oder setzt den Exportwert des CheckBox-Feldes.

**Returns:**
String Wert

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Liest die normale Beschriftung des Feldes.

**Returns:**
String Wert

### getOnState {#getOnState--}
```
public String getOnState()
```

Gibt den Namen des Zustands zurück, der dem "Checked"-Zustand des Kontrollkästchens entspricht. Dies ist "Yes", wenn vorhanden, oder ein anderer Wert außer "Off" und "No";

**Returns:**
String Wert

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Liefert den Stil des Kontrollkästchens.

**Returns:**
Stil des Kontrollkästchens. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Liest den Wert des Kontrollkästchenfeldes.

**Returns:**
String Wert

### setActiveState {#setActiveState-java.lang.String-}
Legt den aktuellen Anmerkungs‑Erscheinungszustand fest.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Setzt den Zustand des Kontrollkästchens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setExportValue {#setExportValue-java.lang.String-}
Liest oder setzt den Exportwert des CheckBox-Feldes.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Setzt den Stil des Kontrollkästchens.

### setValue {#setValue-java.lang.String-}
Setzt den Wert des Kontrollkästchenfeldes.
