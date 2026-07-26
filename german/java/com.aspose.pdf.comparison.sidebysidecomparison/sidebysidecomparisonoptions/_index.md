---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Optionsklasse zum Vergleich von Dokumenten mit nebeneinander ausgegebenem Ergebnis dar."
type: docs
weight: 60
url: /de/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Stellt eine Optionsklasse zum Vergleich von Dokumenten mit nebeneinander ausgegebenem Ergebnis dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Erstellt eine Instanz der {@link SideBySideComparisonOptions} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Lese und setze die Eigenschaft, die bestimmt, ob zusätzliche Änderungsmarkierungen angezeigt werden. Wenn gesetzt, werden Änderungsmarkierungen angezeigt, die nicht auf der aktuellen Seite, aber auf einer anderen Seite vorhanden sind. Wenn die Änderung zwischen Wörtern liegt, kann die Markierung möglicherweise nicht exakt relativ zum Leerzeichen positioniert werden. Der Standardwert ist {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Lese und setze den Vergleichsbereich. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) und {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) Optionen gesetzt werden. |
| [getComparisonArea2](#getComparisonArea2--) | Lese und setze den Vergleichsbereich. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) und {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) Optionen gesetzt werden. |
| [getComparisonMode](#getComparisonMode--) | Lese und setze einen Vergleichsmodus. Der Standardwert ist {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Lese die Farbe, die verwendet wird, um gelöschten Inhalt bei einem Side-by-Side-Vergleich zu markieren. Diese Eigenschaft definiert die visuelle Darstellung von Löschungen im Vergleichsergebnis. |
| [getExcludeAreas1](#getExcludeAreas1--) | Lese und setze die auszuschließenden Bereiche. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) gesetzt werden. Diese Option kann nicht zusammen mit {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) Option gesetzt werden. |
| [getExcludeAreas2](#getExcludeAreas2--) | Lese und setze die auszuschließenden Bereiche. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) gesetzt werden. Diese Option kann nicht zusammen mit {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) Option gesetzt werden. |
| [getExcludeTables](#getExcludeTables--) | Lese und setze die Option, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) und {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) gesetzt werden. Der Standardwert ist {@code false}. |
| [getInsertColor](#getInsertColor--) | Lese die Farbe, die verwendet wird, um eingefügten Inhalt bei einem Side-by-Side-Vergleich zu markieren. Diese Eigenschaft definiert die visuelle Darstellung von Einfügungen im Vergleichsergebnis. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Lese und setze die Eigenschaft, die bestimmt, ob zusätzliche Änderungsmarkierungen angezeigt werden. Wenn gesetzt, werden Änderungsmarkierungen angezeigt, die nicht auf der aktuellen Seite, aber auf einer anderen Seite vorhanden sind. Wenn die Änderung zwischen Wörtern liegt, kann die Markierung möglicherweise nicht exakt relativ zum Leerzeichen positioniert werden. Der Standardwert ist {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Lese und setze den Vergleichsbereich. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) und {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) Optionen gesetzt werden. |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Lese und setze den Vergleichsbereich. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) und {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) Optionen gesetzt werden. |
| [setComparisonMode](#setComparisonMode-int-) | Lese und setze einen Vergleichsmodus. Der Standardwert ist {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Legt die Farbe fest, die verwendet wird, um gelöschten Inhalt während eines Nebeneinander-Vergleichs zu markieren. Diese Eigenschaft definiert die visuelle Darstellung von Löschungen im Vergleichsergebnis. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Lese und setze die auszuschließenden Bereiche. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) gesetzt werden. Diese Option kann nicht zusammen mit {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) Option gesetzt werden. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Lese und setze die auszuschließenden Bereiche. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) gesetzt werden. Diese Option kann nicht zusammen mit {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) Option gesetzt werden. |
| [setExcludeTables](#setExcludeTables-boolean-) | Lese und setze die Option, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) und {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) gesetzt werden. Der Standardwert ist {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Legt die Farbe fest, die verwendet wird, um eingefügten Inhalt während eines Nebeneinander-Vergleichs zu markieren. Diese Eigenschaft definiert die visuelle Darstellung von Einfügungen im Vergleichsergebnis. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Erstellt eine Instanz der {@link SideBySideComparisonOptions} Klasse.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Lese und setze die Eigenschaft, die bestimmt, ob zusätzliche Änderungsmarkierungen angezeigt werden. Wenn gesetzt, werden Änderungsmarkierungen angezeigt, die nicht auf der aktuellen Seite, aber auf einer anderen Seite vorhanden sind. Wenn die Änderung zwischen Wörtern liegt, kann die Markierung möglicherweise nicht exakt relativ zum Leerzeichen positioniert werden. Der Standardwert ist {@code false}.

**Returns:**
boolescher Wert

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Lese und setze den Vergleichsbereich. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) und {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) Optionen gesetzt werden.

**Returns:**
Rechteck-Instanz

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Lese und setze den Vergleichsbereich. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) und {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) Optionen gesetzt werden.

**Returns:**
Rechteck-Instanz

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Lese und setze einen Vergleichsmodus. Der Standardwert ist {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
ComparisonMode-Element

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Lese die Farbe, die verwendet wird, um gelöschten Inhalt bei einem Side-by-Side-Vergleich zu markieren. Diese Eigenschaft definiert die visuelle Darstellung von Löschungen im Vergleichsergebnis.

**Returns:**
die Farbe, die verwendet wird, um gelöschten Inhalt während eines Nebeneinander-Vergleichs zu markieren.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Lese und setze die auszuschließenden Bereiche. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) gesetzt werden. Diese Option kann nicht zusammen mit {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) Option gesetzt werden.

**Returns:**
Array von Rectangle‑Instanzen

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Lese und setze die auszuschließenden Bereiche. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) gesetzt werden. Diese Option kann nicht zusammen mit {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) Option gesetzt werden.

**Returns:**
Array von Rectangle‑Instanzen

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Lese und setze die Option, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) und {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) gesetzt werden. Der Standardwert ist {@code false}.

**Returns:**
boolescher Wert

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Lese die Farbe, die verwendet wird, um eingefügten Inhalt bei einem Side-by-Side-Vergleich zu markieren. Diese Eigenschaft definiert die visuelle Darstellung von Einfügungen im Vergleichsergebnis.

**Returns:**
die Farbe, die verwendet wird, um eingefügten Inhalt während eines Nebeneinander-Vergleichs zu markieren.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Lese und setze die Eigenschaft, die bestimmt, ob zusätzliche Änderungsmarkierungen angezeigt werden. Wenn gesetzt, werden Änderungsmarkierungen angezeigt, die nicht auf der aktuellen Seite, aber auf einer anderen Seite vorhanden sind. Wenn die Änderung zwischen Wörtern liegt, kann die Markierung möglicherweise nicht exakt relativ zum Leerzeichen positioniert werden. Der Standardwert ist {@code false}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Lese und setze den Vergleichsbereich. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) und {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) Optionen gesetzt werden.

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Lese und setze den Vergleichsbereich. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) und {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) Optionen gesetzt werden.

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Lese und setze einen Vergleichsmodus. Der Standardwert ist {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ComparisonMode-Element |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Legt die Farbe fest, die verwendet wird, um gelöschten Inhalt während eines Nebeneinander-Vergleichs zu markieren. Diese Eigenschaft definiert die visuelle Darstellung von Löschungen im Vergleichsergebnis.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Lese und setze die auszuschließenden Bereiche. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) gesetzt werden. Diese Option kann nicht zusammen mit {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) Option gesetzt werden.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Lese und setze die auszuschließenden Bereiche. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) gesetzt werden. Diese Option kann nicht zusammen mit {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) Option gesetzt werden.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Lese und setze die Option, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) und {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) gesetzt werden. Der Standardwert ist {@code false}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Legt die Farbe fest, die verwendet wird, um eingefügten Inhalt während eines Nebeneinander-Vergleichs zu markieren. Diese Eigenschaft definiert die visuelle Darstellung von Einfügungen im Vergleichsergebnis.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
