---
title: "Feld"
linktitle: "Feld"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Basisklasse für Acro-Formularfelder."
type: docs
weight: 1380
url: /de/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Basisklasse für Acro-Formularfelder.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Erstellt ein Feld zur Verwendung im Generator. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Führt eine angegebene JavaScript-Aktion für das Feld aus. |
| [flatten](#flatten--) | Entfernt dieses Feld und legt seinen Wert direkt auf der Seite ab. |
| [get_Item](#get_Item-int-) | Liefert das im Feld enthaltene Unterfeld nach Index. |
| [get_Item](#get_Item-java.lang.String-) | Liefert das im Feld enthaltene Unterfeld nach Namen des Unterfelds. |
| [getAlternateName](#getAlternateName--) | Erhält alternativen Namen des Feldes (Ein alternativer Feldname, der anstelle des tatsächlichen Feldnamens überall dort verwendet werden soll, wo das Feld in der Benutzeroberfläche identifiziert wird. Der alternative Name wird als Feld-Tooltip in Adobe Acrobat verwendet.) |
| [getAnnotationIndex](#getAnnotationIndex--) | Ermittelt den Index dieser Anmerkung auf der Seite. |
| [getMappingName](#getMappingName--) | Ermittelt den Zuordnungsnamen des Feldes, der beim Exportieren interaktiver Formularfelddaten aus dem Dokument verwendet werden soll. |
| [getMaxFontSize](#getMaxFontSize--) | Maximale Schriftgröße, die für Feldinhalte verwendet werden kann. -1, um die Größe nicht zu prüfen. |
| [getMinFontSize](#getMinFontSize--) | Minimale Schriftgröße, die für Feldinhalte verwendet werden kann. -1, um die Größe nicht zu prüfen. |
| [getPageIndex](#getPageIndex--) | Ermittelt den Index der Seite, die dieses Feld enthält. |
| [getPartialName](#getPartialName--) | Ermittelt den Teilnamen des Feldes. |
| [getRect](#getRect--) | Ermittelt das Feldrechteck. |
| [getSyncRoot](#getSyncRoot--) | Synchronisationsobjekt. |
| [getTabOrder](#getTabOrder--) | Liest oder setzt die Tab-Reihenfolge des Feldes. |
| [getValue](#getValue--) | Liest den Wert des Feldes. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | Wenn true, wird die Schriftgröße reduziert, um den Text in das angegebene Rechteck einzupassen. |
| [isGroup](#isGroup--) | Ermittelt den booleschen Wert, der anzeigt, ob dieses Feld ein Nicht-Endfeld ist, d.h. eine Gruppe von Feldern. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Eigenschaft zur Unterstützung des Generators. Wird verwendet, wenn das Feld zu Kopf- oder Fußzeile hinzugefügt wird. Wenn true, wird dieses Feld einmal erstellt und sein Erscheinungsbild ist auf allen Seiten des Dokuments sichtbar. Wenn false, wird für jede Dokumentseite ein separates Feld erstellt. |
| [isSynchronized](#isSynchronized--) | Gibt true zurück, wenn das Wörterbuch synchronisiert ist. |
| [iterator](#iterator--) | Gibt den Enumerator der enthaltenen Felder zurück. |
| [recalculate](#recalculate--) | Berechnet alle berechneten Felder im Formular neu. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Legt den alternativen Namen des Feldes fest (Ein alternativer Feldname, der anstelle des tatsächlichen Feldnamens verwendet werden soll, wo immer das Feld in der Benutzeroberfläche identifiziert wird). Der alternative Name wird als Feld-Tooltip in Adobe Acrobat verwendet. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Legt den Index dieser Anmerkung auf der Seite fest. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | Wenn true, wird die Schriftgröße reduziert, um den Text in das angegebene Rechteck einzupassen. |
| [setMappingName](#setMappingName-java.lang.String-) | Legt den Zuordnungsnamen des Feldes fest, der beim Exportieren interaktiver Formularfelddaten aus dem Dokument verwendet werden soll. |
| [setMaxFontSize](#setMaxFontSize-double-) | Maximale Schriftgröße, die für Feldinhalte verwendet werden kann. -1, um die Größe nicht zu prüfen. |
| [setMinFontSize](#setMinFontSize-double-) | Minimale Schriftgröße, die für Feldinhalte verwendet werden kann. -1, um die Größe nicht zu prüfen. |
| [setPartialName](#setPartialName-java.lang.String-) | Legt den Teilnamen des Feldes fest. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Setzt die Position des Feldes. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Legt das Feldrechteck fest. |
| [setSharedField](#setSharedField-boolean-) | Eigenschaft zur Unterstützung des Generators. Wird verwendet, wenn das Feld zu Kopf- oder Fußzeile hinzugefügt wird. Wenn true, wird dieses Feld einmal erstellt und sein Erscheinungsbild ist auf allen Seiten des Dokuments sichtbar. Wenn false, wird für jede Dokumentseite ein separates Feld erstellt. |
| [setTabOrder](#setTabOrder-int-) | Liest oder setzt die Tab-Reihenfolge des Feldes. |
| [setValue](#setValue-java.lang.String-) | Wert setzen. |
| [size](#size--) | Ermittelt die Anzahl der Unterfelder in diesem Feld. (Zum Beispiel die Anzahl der Elemente in einem Optionsfeld.) |
| [updateAppearances](#updateAppearances--) | Aktualisiert den Darstellungswert. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Erstellt ein Feld zur Verwendung im Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Führt eine angegebene JavaScript-Aktion für das Feld aus.

### flatten {#flatten--}
```
public void flatten()
```

Entfernt dieses Feld und legt seinen Wert direkt auf der Seite ab.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Liefert das im Feld enthaltene Unterfeld nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des angeforderten Unterfeldes. |

**Returns:**
Feldinstanz.

### get_Item {#get_Item-java.lang.String-}
Liefert das im Feld enthaltene Unterfeld nach Namen des Unterfelds.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Erhält alternativen Namen des Feldes (Ein alternativer Feldname, der anstelle des tatsächlichen Feldnamens überall dort verwendet werden soll, wo das Feld in der Benutzeroberfläche identifiziert wird. Der alternative Name wird als Feld-Tooltip in Adobe Acrobat verwendet.)

**Returns:**
String Wert

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Ermittelt den Index dieser Anmerkung auf der Seite.

**Returns:**
int-Wert

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Ermittelt den Zuordnungsnamen des Feldes, der beim Exportieren interaktiver Formularfelddaten aus dem Dokument verwendet werden soll.

**Returns:**
String Wert

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Maximale Schriftgröße, die für Feldinhalte verwendet werden kann. -1, um die Größe nicht zu prüfen.

**Returns:**
double-Wert

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Minimale Schriftgröße, die für Feldinhalte verwendet werden kann. -1, um die Größe nicht zu prüfen.

**Returns:**
double-Wert

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Ermittelt den Index der Seite, die dieses Feld enthält.

**Returns:**
int-Wert

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Ermittelt den Teilnamen des Feldes.

**Returns:**
String Wert

### getRect {#getRect--}
```
public Rectangle getRect()
```

Ermittelt das Feldrechteck.

**Returns:**
das Feldrechteck.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Synchronisationsobjekt.

**Returns:**
Objektwert

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Liest oder setzt die Tab-Reihenfolge des Feldes.

**Returns:**
int-Wert

### getValue {#getValue--}
```
public String getValue()
```

Liest den Wert des Feldes.

**Returns:**
String Wert

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

Wenn true, wird die Schriftgröße reduziert, um den Text in das angegebene Rechteck einzupassen.

**Returns:**
boolescher Wert

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Ermittelt den booleschen Wert, der anzeigt, ob dieses Feld ein Nicht-Endfeld ist, d.h. eine Gruppe von Feldern.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Eigenschaft zur Unterstützung des Generators. Wird verwendet, wenn das Feld zu Kopf- oder Fußzeile hinzugefügt wird. Wenn true, wird dieses Feld einmal erstellt und sein Erscheinungsbild ist auf allen Seiten des Dokuments sichtbar. Wenn false, wird für jede Dokumentseite ein separates Feld erstellt.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gibt true zurück, wenn das Wörterbuch synchronisiert ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Gibt den Enumerator der enthaltenen Felder zurück.

**Returns:**
Enumerator-Objekt.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Berechnet alle berechneten Felder im Formular neu.

**Returns:**
Wahr, wenn der Feldwert während der Neuberechnung geändert wurde.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Legt den alternativen Namen des Feldes fest (Ein alternativer Feldname, der anstelle des tatsächlichen Feldnamens verwendet werden soll, wo immer das Feld in der Benutzeroberfläche identifiziert wird). Der alternative Name wird als Feld-Tooltip in Adobe Acrobat verwendet.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Legt den Index dieser Anmerkung auf der Seite fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

Wenn true, wird die Schriftgröße reduziert, um den Text in das angegebene Rechteck einzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMappingName {#setMappingName-java.lang.String-}
Legt den Zuordnungsnamen des Feldes fest, der beim Exportieren interaktiver Formularfelddaten aus dem Dokument verwendet werden soll.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Maximale Schriftgröße, die für Feldinhalte verwendet werden kann. -1, um die Größe nicht zu prüfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Minimale Schriftgröße, die für Feldinhalte verwendet werden kann. -1, um die Größe nicht zu prüfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setPartialName {#setPartialName-java.lang.String-}
Legt den Teilnamen des Feldes fest.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Setzt die Position des Feldes.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Legt das Feldrechteck fest.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Eigenschaft zur Unterstützung des Generators. Wird verwendet, wenn das Feld zu Kopf- oder Fußzeile hinzugefügt wird. Wenn true, wird dieses Feld einmal erstellt und sein Erscheinungsbild ist auf allen Seiten des Dokuments sichtbar. Wenn false, wird für jede Dokumentseite ein separates Feld erstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Liest oder setzt die Tab-Reihenfolge des Feldes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setValue {#setValue-java.lang.String-}
Wert setzen.

### size {#size--}
```
public int size()
```

Ermittelt die Anzahl der Unterfelder in diesem Feld. (Zum Beispiel die Anzahl der Elemente in einem Optionsfeld.)

**Returns:**
int-Wert

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Aktualisiert den Darstellungswert.
