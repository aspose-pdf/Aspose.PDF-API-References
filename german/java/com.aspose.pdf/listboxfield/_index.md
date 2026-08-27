---
title: "ListBoxField"
linktitle: "ListBoxField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt ein ListBox-Feld dar."
type: docs
weight: 2770
url: /de/java/com.aspose.pdf/listboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.ChoiceField, com.aspose.pdf.ListBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class ListBoxField extends ChoiceField
```

Klasse stellt ein ListBox-Feld dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ListBoxField](#ListBoxField--) | Konstruktor für ListBoxField, der im Generator verwendet wird. |
| [ListBoxField](#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Konstruktor für ListBoxField, der im Generator verwendet wird. |
| [ListBoxField](#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor für ListBoxField, der im Generator verwendet wird. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTopIndex](#getTopIndex--) | Liefert den Index des obersten sichtbaren Elements der Liste. |
| [setSelected](#setSelected-int-) | Liefert den Index des ausgewählten Elements. Elemente werden ab 1 nummeriert. |
| [setSelectedItems](#setSelectedItems-int:A-) | Setzt das Array der ausgewählten Elemente in der Mehrfachauswahlliste. Für eine Einzelauswahlliste wird ein Array mit einem einzelnen Element zurückgegeben. |
| [setTopIndex](#setTopIndex-int-) | Setzt den Index des obersten sichtbaren Elements der Liste. |

### ListBoxField {#ListBoxField--}
```
public ListBoxField()
```

Konstruktor für ListBoxField, der im Generator verwendet wird.

### ListBoxField {#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Konstruktor für ListBoxField, der im Generator verwendet wird.

### ListBoxField {#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor für ListBoxField, der im Generator verwendet wird.

### getTopIndex {#getTopIndex--}
```
public int getTopIndex()
```

Liefert den Index des obersten sichtbaren Elements der Liste.

**Returns:**
int-Wert

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Liefert den Index des ausgewählten Elements. Elemente werden ab 1 nummeriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Setzt das Array der ausgewählten Elemente in der Mehrfachauswahlliste. Für eine Einzelauswahlliste wird ein Array mit einem einzelnen Element zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Array von int-Werten |

### setTopIndex {#setTopIndex-int-}
```
public void setTopIndex(int value)
```

Setzt den Index des obersten sichtbaren Elements der Liste.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
