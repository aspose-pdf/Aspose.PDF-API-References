---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse beschreibt Regeln, die verwendet werden können, um den Vorgang des Kopierens von Kodierungsdaten für Fälle zu optimieren, in denen TrueType‑symbolische Schriftarten mehr als eine Kodierung besitzen. Einige PDF‑Dokumente danach."
type: docs
weight: 3690
url: /de/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

Diese Klasse beschreibt Regeln, die verwendet werden können, um den Vorgang des Kopierens von Kodierungsdaten für Fälle zu optimieren, in denen eine TrueType‑Symbolschrift mehr als eine Kodierung hat. Einige PDF‑Dokumente können nach der Konvertierung in das PDF/A‑Format einen Fehler \"More than one encoding in symbolic TrueType font's cmap\" ausgeben. Was ist die Ursache dieses Fehlers? Alle TrueType‑Symbolschriften besitzen eine spezielle Tabelle \"cmap\" in ihren internen Daten. Diese Tabelle ordnet Zeichencodes Glyphen‑Indizes zu. Und diese Tabelle kann verschiedene Kodierungs‑Untertabelle(n) enthalten, die die verwendeten Kodierungen beschreiben. Siehe erweiterte Informationen zu cmap‑Tabellen unter https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Normalerweise enthält die cmap‑Tabelle mehrere Kodierungs‑Untertabelle(n), aber der PDF/A‑Standard verlangt, dass entweder nur eine Kodierungs‑Untertabelle für diese Schrift im PDF/A‑Dokument verbleibt oder dass unter den Unterschrift‑Tabellen dieser Schrift eine (3,0)‑Kodierungs‑Untertabelle vorhanden ist. Und die zentrale Frage hier – welche Daten aus anderen Unterschrift‑Tabellen müssen in die Ziel‑Kodierungstabelle (3,0) kopiert werden? Die Mehrheit der Schriften hat \"wohlgeformte\" cmap‑Tabellen, bei denen jede Kodierungs‑Untertabelle vollständig mit einer anderen Unterschrift‑Tabelle konsistent ist. Einige Schriften besitzen jedoch cmap‑Tabellen mit Kollisionen – zum Beispiel hat eine Unterschrift‑Tabelle den Glyphen‑Index 100 für Unicode 100, während eine andere Unterschrift‑Tabelle den Glyphen‑Index 200 für denselben Unicode 100 hat. Zur Lösung dieses Problems ist eine spezielle Strategie erforderlich. Standardmäßig wird folgende Strategie verwendet: Es wird nach der mac‑Unterschrift‑Tabelle (1,0) gesucht. Wird diese Tabelle gefunden, werden nur deren Daten zum Befüllen der Ziel‑Tabelle (3,0) verwendet. Wird die mac‑Unterschrift‑Tabelle nicht gefunden, werden alle Unterschrift‑Tabellen außer (3,0) durchlaufen und deren Daten in die Ziel‑Unterschrift‑Tabelle (3,0) kopiert. Außerdem wird die Zuordnung für jedes Unicode (Unicode, Glyphen‑Index) nur dann in die Ziel‑Tabelle kopiert, wenn die Ziel‑Tabelle dieses Unicode zum aktuellen Zeitpunkt noch nicht enthält. So wird zum Beispiel, wenn die erste Unterschrift‑Tabelle den Glyphen‑Index 100 für Unicode 100 hat und die nächste Unterschrift‑Tabelle den Glyphen‑Index 200 für dasselbe Unicode 100, nur das Datum der ersten Unterschrift‑Tabelle (Unicode=100, Glyphen‑Index = 100) kopiert. Jede vorherige Unterschrift‑Tabelle hat also Vorrang vor der nächsten. Eigenschaften dieser Klasse { PdfASymbolicFontEncodingStrategy} helfen, das Standardverhalten zu optimieren. Wenn die Eigenschaft {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) vom Typ { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} gesetzt ist, wird die entsprechende Unterschrift‑Tabelle mit Vorrang vor der mac‑Unterschrift‑Tabelle (1,0) verwendet. Der Wert \"MacTable\" aus der Aufzählung {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} hat in diesem Fall keinen Sinn, da er auf dieselbe mac‑Unterschrift‑Tabelle (1,0) verweist, die standardmäßig verwendet wird. Die Eigenschaft {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) verwirft alle Prioritäten für irgendeine Unterschrift‑Tabelle. Ist diese Eigenschaft gesetzt, werden nur Unterschrift‑Tabellen aus der deklarierten Warteschlange in der angegebenen Reihenfolge verwendet. Werden die angegebenen Unterschrift‑Tabellen nicht gefunden, wird die Standarditeration aller Unterschrift‑Tabellen und die oben beschriebene Kopierstrategie verwendet. Das Objekt { PdfASymbolicFontEncodingStrategy.QueueItem} gibt die zu verwendende Kodierungs‑Unterschrift‑Tabelle an. Diese Unterschrift‑Tabelle kann über eine Kombination von Mitgliedern (PlatformID, PlatformSpecificId) oder über die Aufzählung { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} festgelegt werden. Falls die Schrift keine (3,0)‑Unterschrift‑Tabelle besitzt, wird eine andere Unterschrift‑Tabelle verwendet, um die PDF/A‑Kompatibilität aufrechtzuerhalten. Die Auswahl der zu verwendenden Unterschrift‑Tabelle erfolgt nach denselben Regeln wie zuvor beschrieben, sodass {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) und {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) Eigenschaften verwendet werden, um die resultierende Unterschrift‑Tabelle zu bestimmen, und falls die Schrift die angeforderte(n) Unterschrift‑Tabelle(n) nicht hat, wird irgendeine vorhandene Unterschrift‑Tabelle verwendet.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | Konstruktor. Setzt die Standardsubtabelle (mac 1,0). |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | Konstruktor. Setzt die Standardsubtabelle (mac 1,0). |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | Gibt die Warteschlange der zu verarbeitenden Kodierungs-Subtabellen an. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | Gibt die Subtabelle an, die der mac-Subtabelle (1,0) vorrangig verwendet wird. Der Wert 'MacTable' aus der Aufzählung {@code QueueItem.CMapEncodingTableType} hat in diesem Fall keinen Sinn. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | Gibt die Warteschlange der zu verarbeitenden Kodierungs-Subtabellen an. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | Gibt die Subtabelle an, die der mac-Subtabelle (1,0) vorrangig verwendet wird. Der Wert 'MacTable' aus der Aufzählung {@code QueueItem.CMapEncodingTableType} hat in diesem Fall keinen Sinn. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

Konstruktor. Setzt die Standardsubtabelle (mac 1,0).

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
Konstruktor. Setzt die Standardsubtabelle (mac 1,0).

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

Konstruktor

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| preferredEncodingTable |  | Kodierungs-Subtabelle, die der mac-Subtabelle (1,0) vorrangig verwendet wird @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

Gibt die Warteschlange der zu verarbeitenden Kodierungs-Subtabellen an.

**Returns:**
Warteschlange von QueueItem

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

Gibt die Subtabelle an, die der mac-Subtabelle (1,0) vorrangig verwendet wird. Der Wert 'MacTable' aus der Aufzählung {@code QueueItem.CMapEncodingTableType} hat in diesem Fall keinen Sinn.

**Returns:**
CMapEncodingTableType-Element @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
Gibt die Warteschlange der zu verarbeitenden Kodierungs-Subtabellen an.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

Gibt die Subtabelle an, die der mac-Subtabelle (1,0) vorrangig verwendet wird. Der Wert 'MacTable' aus der Aufzählung {@code QueueItem.CMapEncodingTableType} hat in diesem Fall keinen Sinn.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | preferredEncodingTable Kodierungs-Subtabelle, die der mac-Subtabelle (1,0) vorrangig verwendet wird @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
