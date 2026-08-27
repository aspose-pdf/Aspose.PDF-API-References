---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Optionsklasse für den Vergleich von PDF‑Dokumenten dar."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Stellt eine Optionsklasse für den Vergleich von PDF‑Dokumenten dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Erstellt eine {@link ComparisonOptions}-Klasseninstanz. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Liest und setzt die Reihenfolge der Bearbeitungsoperationen. |
| [getExcludeAreas1](#getExcludeAreas1--) | Lese und setze die Ausschlussbereiche. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) festgelegt werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden. |
| [getExcludeAreas2](#getExcludeAreas2--) | Lese und setze die Ausschlussbereiche. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) festgelegt werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden. |
| [getExtractionArea](#getExtractionArea--) | Lese und setze den rechteckigen Bereich, in dem der Text der Seiten verglichen wird. Diese Option kann nicht zusammen mit {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) und { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) Optionen festgelegt werden. |
| [isExcludeTables](#isExcludeTables--) | Lese und setze die Option, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden. Der Standardwert ist {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Liest und setzt die Reihenfolge der Bearbeitungsoperationen. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Lese und setze die Ausschlussbereiche. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) festgelegt werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Lese und setze die Ausschlussbereiche. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) festgelegt werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden. |
| [setExcludeTables](#setExcludeTables-boolean-) | Lese und setze die Option, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden. Der Standardwert ist {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Lese und setze den rechteckigen Bereich, in dem der Text der Seiten verglichen wird. Diese Option kann nicht zusammen mit {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) und { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) Optionen festgelegt werden. |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Erstellt eine {@link ComparisonOptions}-Klasseninstanz.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Liest und setzt die Reihenfolge der Bearbeitungsoperationen.

**Returns:**
EditOperationsOrder-Element

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Lese und setze die Ausschlussbereiche. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) festgelegt werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden.

**Returns:**
Array von Rectangle‑Instanzen

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Lese und setze die Ausschlussbereiche. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) festgelegt werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden.

**Returns:**
Array von Rectangle‑Instanzen

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Lese und setze den rechteckigen Bereich, in dem der Text der Seiten verglichen wird. Diese Option kann nicht zusammen mit {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) und { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) Optionen festgelegt werden.

**Returns:**
Rechteck-Instanz

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Lese und setze die Option, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden. Der Standardwert ist {@code false}.

**Returns:**
boolescher Wert

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Liest und setzt die Reihenfolge der Bearbeitungsoperationen.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Lese und setze die Ausschlussbereiche. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) festgelegt werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Lese und setze die Ausschlussbereiche. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) festgelegt werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Lese und setze die Option, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) festgelegt werden. Der Standardwert ist {@code false}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Lese und setze den rechteckigen Bereich, in dem der Text der Seiten verglichen wird. Diese Option kann nicht zusammen mit {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) und { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) Optionen festgelegt werden.
