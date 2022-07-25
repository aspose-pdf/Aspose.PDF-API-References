---
title: Table
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt eine Tabelle dar die der Seite hinzugefügt werden kann.
type: docs
weight: 6500
url: /de/net/aspose.pdf/table/
---
## Table class

Stellt eine Tabelle dar, die der Seite hinzugefügt werden kann.

```csharp
public sealed class Table : BaseParagraph
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Table](table)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment) { get; set; } | Ruft die Tabellenausrichtung ab oder legt sie fest. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor) { get; set; } | Holt oder setzt Tabellenhintergrundfarbe |
| [Border](../../aspose.pdf/table/border) { get; set; } | Ruft den Rahmen ab oder legt ihn fest. |
| [BreakText](../../aspose.pdf/table/breaktext) { get; set; } | Ruft Umbruchtext für table ab oder legt ihn fest |
| [Broken](../../aspose.pdf/table/broken) { get; set; } | Holt oder setzt Tabellenvertial defekt; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment) { get; set; } | Ruft die Anpassung der Tabellenspalte ab oder legt sie fest. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths) { get; set; } | Ruft die Spaltenbreiten der Tabelle ab. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle) { get; set; } | Holt oder setzt die Stile der Rahmenecken |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder) { get; set; } | Ruft den Standardzellenrand ab; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding) { get; set; } | Ruft die standardmäßige Zellenauffüllung ab oder legt sie fest. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate) { get; set; } | Ruft den standardmäßigen Zelltextstatus ab oder legt ihn fest. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth) { get; set; } | Ruft den Standardzellenrand ab; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | Holt oder setzt eine horizontale Ausrichtung des Absatzes |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Holt oder setzt den Fragment-Hyperlink (für PDF-Generator). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded) { get; set; } | Ruft den in Spaltenbreiten enthaltenen Rand ab oder legt ihn fest. |
| [IsBroken](../../aspose.pdf/table/isbroken) { get; set; } | Ruft ab oder legt fest, dass die Tabelle defekt ist – wird für die nächste Seite abgeschnitten. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte steht. Standard ist „false“.(für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ruft ab oder legt fest, dass ein Absatz inline ist. Standard ist „false“.(für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Der Standardwert ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite verbleibt. Der Standardwert ist „false“. (für die PDF-Generierung) |
| [Left](../../aspose.pdf/table/left) { get; set; } | Liest oder setzt die linke Koordinate des Tisches. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Liest oder setzt einen Außenrand für Absatz (für PDF-Generierung) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount) { get; set; } | Ruft die maximale Spaltenanzahl für table ab oder legt sie fest |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount) { get; set; } | Ruft die Anzahl der ersten Zeilen ab, die für mehrere Seiten wiederholt wird |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle) { get; set; } | Ruft den Stil für sich wiederholende Zeilen ab |
| [Rows](../../aspose.pdf/table/rows) { get; } | Ruft die Zeilen der Tabelle ab. |
| [Top](../../aspose.pdf/table/top) { get; set; } | Holt oder setzt die Koordinate der Tischplatte. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Holt oder setzt eine vertikale Ausrichtung des Absatzes |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Diagramms angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Grafik mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone)() | Klonen Sie die Tabelle. |
| [GetHeight](../../aspose.pdf/table/getheight)(Page) | Höhe abrufen. |
| [GetWidth](../../aspose.pdf/table/getwidth)() | Breite abrufen. |
| [ImportArray](../../aspose.pdf/table/importarray)(object[], int, int, bool) | Importiert eindimensionales Array von Daten in die Tabelle. Der Import geht eine Zelle pro Element jedes Arrays und beginnt mit Zeile und Spalte, die in Parametern definiert sind. Wenn während des Imports festgestellt wird, dass erforderliche Zeilen noch fehlen (dh die Zieltabelle ist zu klein, um alle Daten aufzunehmen), werden erforderliche Zeilen erstellt |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_1)(DataTable, bool, int, int) | Importiert Daten aus System.Data.DataTable in Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importiert aDataTable Objekt in die Tabelle. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importiert aDataTable Objekt, aber nicht als Ganzes. Nur bestimmte Zeilen und Spalten werden importiert. |
| [ImportDataView](../../aspose.pdf/table/importdataview)(DataView, bool, int, int, int, int) | Importiert aDataView Objektdaten in die Tabelle. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate)(int, TextState) | Höhe einstellen. |

### Siehe auch

* class [BaseParagraph](../baseparagraph)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
