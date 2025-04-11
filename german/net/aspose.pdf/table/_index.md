---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Table-Klasse. Stellt eine Tabelle dar, die zur Seite hinzugefügt werden kann
type: docs
weight: 10280
url: /de/net/aspose.pdf/table/
---
## Klassentabelle

Stellt eine Tabelle dar, die zur Seite hinzugefügt werden kann.

```csharp
public sealed class Table : BaseParagraph
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Table](table/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Ruft die Tabellenausrichtung ab oder legt sie fest. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Ruft die Hintergrundfarbe der Tabelle ab oder legt sie fest. |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Ruft den Rand ab oder legt ihn fest. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Ruft den Umbruchtext für die Tabelle ab oder legt ihn fest. |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Ruft ab oder legt fest, ob die Tabelle vertikal gebrochen ist. |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Ruft die Spaltenanpassung der Tabelle ab oder legt sie fest. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Ruft die Spaltenbreiten der Tabelle ab. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Ruft die Stile der Rand-Ecken ab oder legt sie fest. |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Ruft den Standardzellenrand ab oder legt ihn fest. |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Ruft das Standardzellenpolster ab oder legt es fest. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Ruft den Standardtextzustand der Zelle ab oder legt ihn fest. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Ruft die Standardspaltenbreite ab oder legt sie fest. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung des Absatzes ab oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für PDF-Generator) ab oder legt ihn fest. |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Ruft ab oder legt fest, ob der Rand in den Spaltenbreiten enthalten ist. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Ruft ab oder legt fest, ob die Tabelle gebrochen ist - wird für die nächste Seite abgeschnitten. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch. (für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist falsch. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für PDF-Generierung) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Ruft die linke Koordinate der Tabelle ab oder legt sie fest. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für PDF-Generierung) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Ruft die maximale Spaltenanzahl für die Tabelle ab oder legt sie fest. |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Ruft die Anzahl der ersten Zeilen ab, die für mehrere Seiten wiederholt werden. |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Ruft den Stil für wiederholte Zeilen ab oder legt ihn fest. |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Ruft die Zeilen der Tabelle ab. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Ruft die obere Koordinate der Tabelle ab oder legt sie fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung des Absatzes ab oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Klont die Tabelle. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Ruft die Höhe ab. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Ruft die Breite ab. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Importiert ein eindimensionales Array von Daten in die Tabelle. Der Import erfolgt zelle für zelle und beginnt mit der in den Parametern definierten Zeile und Spalte. Während des Imports, wenn festgestellt wird, dass notwendige Zeilen noch fehlen (d.h. die Ziel-Tabelle ist zu klein, um alle Daten aufzunehmen), werden notwendige Zeilen erstellt. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Importiert Daten aus System.Data.DataTable in Aspose.Pdf.Table. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importiert ein DataTable-Objekt in die Tabelle. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importiert ein DataTable-Objekt, jedoch nicht als ganze Einheit. Nur die angegebenen Zeilen und Spalten werden importiert. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Importiert die Daten eines DataView-Objekts in die Tabelle. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Setzt die Höhe. |

### Siehe auch

* Klasse [BaseParagraph](../baseparagraph/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)