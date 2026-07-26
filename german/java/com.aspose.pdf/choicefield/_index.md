---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Basisklasse für Auswahlfelder dar."
type: docs
weight: 590
url: /de/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Stellt die Basisklasse für Auswahlfelder dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Erstellt ein ChoiceField (für Generator) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Konstruktor für ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor für ChoiceField. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Fügt eine neue Option mit angegebenem Namen hinzu. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Fügt eine neue Option mit angegebenem Exportwert und Namen hinzu. |
| [deleteOption](#deleteOption-java.lang.String-) | Löscht die Option nach ihrem Namen. |
| [getCommitImmediately](#getCommitImmediately--) | Gibt das Commit‑bei‑Auswahländerung‑Flag zurück. |
| [getMultiSelect](#getMultiSelect--) | Gibt das Mehrfachauswahl‑Flag zurück. |
| [getOptions](#getOptions--) | Liefert die Sammlung von Auswahloptionen. |
| [getSelected](#getSelected--) | Liefert den Index der ausgewählten Option. Diese Eigenschaft ermöglicht es, die Auswahl zu ändern. |
| [getSelectedItems](#getSelectedItems--) | Setzt ein Array ausgewählter Elemente. Für eine Mehrfachauswahl-Liste enthält das Array mehr als ein Element. Für eine Einzelauswahl-Liste enthält es ein einzelnes Element. |
| [getValue](#getValue--) | Liest den Wert des Feldes. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Setzt das Commit‑bei‑Auswahländerung‑Flag. |
| [setMultiSelect](#setMultiSelect-boolean-) | Setzt das Mehrfachauswahl‑Flag. |
| [setOptions](#setOptions-java.util.List-) | Ersetzt die verfügbaren Optionen durch diejenigen, deren Namen im Parameter options angegeben sind. |
| [setSelected](#setSelected-int-) | Setzt den Index der ausgewählten Option. Diese Eigenschaft ermöglicht es, die Auswahl zu ändern. |
| [setSelectedItems](#setSelectedItems-int:A-) | Setzt ein Array ausgewählter Elemente. Für eine Mehrfachauswahl-Liste enthält das Array mehr als ein Element. Für eine Einzelauswahl-Liste enthält es ein einzelnes Element. |
| [setValue](#setValue-java.lang.String-) | Setzt den Wert des Feldes. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Erstellt ein ChoiceField (für Generator)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Konstruktor für ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor für ChoiceField.

### addOption {#addOption-java.lang.String-}
Fügt eine neue Option mit angegebenem Namen hinzu.

### addOption {#addOption-java.lang.String-java.lang.String-}
Fügt eine neue Option mit angegebenem Exportwert und Namen hinzu.

### deleteOption {#deleteOption-java.lang.String-}
Löscht die Option nach ihrem Namen.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Gibt das Commit‑bei‑Auswahländerung‑Flag zurück.

**Returns:**
boolescher Wert

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Gibt das Mehrfachauswahl‑Flag zurück.

**Returns:**
boolescher Wert

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Liefert die Sammlung von Auswahloptionen.

**Returns:**
OptionCollection‑Objekt

### getSelected {#getSelected--}
```
public int getSelected()
```

Liefert den Index der ausgewählten Option. Diese Eigenschaft ermöglicht es, die Auswahl zu ändern.

**Returns:**
int-Wert

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Setzt ein Array ausgewählter Elemente. Für eine Mehrfachauswahl-Liste enthält das Array mehr als ein Element. Für eine Einzelauswahl-Liste enthält es ein einzelnes Element.

**Returns:**
Array von int-Werten

### getValue {#getValue--}
```
public String getValue()
```

Liest den Wert des Feldes.

**Returns:**
String Wert

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Setzt das Commit‑bei‑Auswahländerung‑Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Setzt das Mehrfachauswahl‑Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOptions {#setOptions-java.util.List-}
Ersetzt die verfügbaren Optionen durch diejenigen, deren Namen im Parameter options angegeben sind.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Setzt den Index der ausgewählten Option. Diese Eigenschaft ermöglicht es, die Auswahl zu ändern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Setzt ein Array ausgewählter Elemente. Für eine Mehrfachauswahl-Liste enthält das Array mehr als ein Element. Für eine Einzelauswahl-Liste enthält es ein einzelnes Element.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Array von int-Werten |

### setValue {#setValue-java.lang.String-}
Setzt den Wert des Feldes.
