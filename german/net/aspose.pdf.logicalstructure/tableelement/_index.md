---
title: TableElement
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert ein Tabellenstrukturelement in einer logischen Struktur.
type: docs
weight: 4610
url: /de/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Repräsentiert ein Tabellenstrukturelement in einer logischen Struktur.

```csharp
public sealed class TableElement : BLSElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Holt oder setzt den aktuellen Text für Strukturelement. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment) { get; set; } | Ruft die Tabellenausrichtung ab oder legt sie fest. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Holt oder setzt den alternativen Text für Strukturelement. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | erhältStructureAttributeCollection Objekt. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor) { get; set; } | Ruft die Hintergrundfarbe der Tabelle ab oder legt sie fest. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border) { get; set; } | Holt oder setzt den Tabellenrand. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken) { get; set; } | Holt oder setzt Tabellenvertial defekt; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Ruft eine untergeordnete Sammlung von abElement Objekte. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment) { get; set; } | Ruft die Anpassung der Tabellenspalte ab oder legt sie fest. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths) { get; set; } | Ruft die Spaltenbreiten der Tabelle ab. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle) { get; set; } | Holt oder setzt die Stile der Rahmenecken |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | erhältAttributeOwnerStandard Objekt. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder) { get; set; } | Ruft den Standardzellenrand ab. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding) { get; set; } | Ruft die standardmäßige Zellenauffüllung ab oder legt sie fest. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate) { get; set; } | Ruft den standardmäßigen Zelltextstatus ab oder legt ihn fest. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth) { get; set; } | Ruft die Standardspaltenbreite ab oder legt sie fest. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Liest oder setzt den Erweiterungstext für Strukturelement. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Ruft die ID für Strukturelement ab. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded) { get; set; } | Ruft den in Spaltenbreiten enthaltenen Rand ab oder legt ihn fest. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken) { get; set; } | Ruft ab oder legt fest, dass die Tabelle defekt ist – wird für die nächste Seite abgeschnitten. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Holt oder setzt die Sprache für Strukturelement. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left) { get; set; } | Liest oder setzt die linke Koordinate des Tisches. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Übergeordnetes Element abrufen. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount) { get; set; } | Ruft die maximale Spaltenanzahl für die Tabelle ab oder legt sie fest. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount) { get; set; } | Ruft die Anzahl der ersten Zeilen ab, die für mehrere Seiten wiederholt wird. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle) { get; set; } | Ruft den Stil für sich wiederholende Zeilen ab. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Ruft den Typ des Strukturelements ab. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Holt oder setzt den Titel für Strukturelement. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top) { get; set; } | Holt oder setzt die Koordinate der Tischplatte. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | AnhängenElement zur Sammlung von Kindern. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Elternelement für aktuelles Strukturelement ändern |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | ID für Strukturelement löschen. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody)() | erstellt[`TableTHeadElement`](../tabletheadelement) und zur aktuellen Tabelle hinzugefügt. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot)() | erstellt[`TableTFootElement`](../tabletfootelement) und zur aktuellen Tabelle hinzugefügt. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead)() | erstellt[`TableTHeadElement`](../tabletheadelement) und zur aktuellen Tabelle hinzugefügt. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Elemente eines bestimmten Typs finden |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | ID für Strukturelement generieren. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Legt ID für Strukturelement fest. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Legt benutzerdefiniertes Tag für Strukturelement fest. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* class [BLSElement](../blselement)
* namensraum [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
