---
title: Class TableElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableElement-Klasse. Stellt ein Tabellenelement in der logischen Struktur dar
type: docs
weight: 6780
url: /de/net/aspose.pdf.logicalstructure/tableelement/
---
## Klasse TableElement

Stellt ein Tabellenelement in der logischen Struktur dar.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Ruft den tatsächlichen Text für das Strukturelement ab oder legt ihn fest. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Ruft die Tabellenausrichtung ab oder legt sie fest. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Ruft den alternativen Text für das Strukturelement ab oder legt ihn fest. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Ruft das StructureAttributeCollection-Objekt ab. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Ruft die Hintergrundfarbe der Tabelle ab oder legt sie fest. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Ruft den Tabellenrand ab oder legt ihn fest. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Ruft ab oder legt fest, ob die Tabelle vertikal gebrochen ist; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ruft die Sammlung von Kind-Elementobjekten ab. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Ruft die Spaltenanpassung der Tabelle ab oder legt sie fest. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Ruft die Spaltenbreiten der Tabelle ab. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Ruft die Stile der Rand-Ecken ab oder legt sie fest. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Ruft das AttributeOwnerStandard-Objekt ab. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Ruft den Standardzellenrand ab oder legt ihn fest. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Ruft das Standardzellenpadding ab oder legt es fest. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Ruft den Standardtextzustand der Zelle ab oder legt ihn fest. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Ruft die Standardspaltenbreite ab oder legt sie fest. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Ruft den Erweiterungstext für das Strukturelement ab oder legt ihn fest. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Ruft die ID für das Strukturelement ab. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Ruft ab oder legt fest, ob der Rand in den Spaltenbreiten enthalten ist. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Ruft ab oder legt fest, ob die Tabelle gebrochen ist - wird für die nächste Seite abgeschnitten. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Ruft die Sprache für das Strukturelement ab oder legt sie fest. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Ruft die linke Koordinate der Tabelle ab oder legt sie fest. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Ruft die Seite ab, auf der einige oder alle Kind-Elemente gerendert werden. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ruft das Elternelement ab. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Ruft die maximale Anzahl der Spalten für die Tabelle ab oder legt sie fest. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Ruft die Anzahl der ersten Zeilen ab, die für mehrere Seiten wiederholt werden. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Ruft den Stil für wiederholte Zeilen ab oder legt ihn fest. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Ruft den Typ des Strukturelements ab. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Ruft den Titel für das Strukturelement ab oder legt ihn fest. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Ruft die obere Koordinate der Tabelle ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Fügt ein Element zur Sammlung der Kinder hinzu. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Ändert das Elternelement für das aktuelle Strukturelement. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Löscht alle Kinder. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Löscht die ID für das Strukturelement. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Erstellt [`TableTHeadElement`](../tabletheadelement/) und fügt es zur aktuellen Tabelle hinzu. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Erstellt [`TableTFootElement`](../tabletfootelement/) und fügt es zur aktuellen Tabelle hinzu. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Erstellt [`TableTHeadElement`](../tabletheadelement/) und fügt es zur aktuellen Tabelle hinzu. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Findet Elemente eines bestimmten Typs. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generiert eine ID für das Strukturelement. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Fügt ein Element zur Sammlung der Kinder an einem bestimmten Index ein. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Entfernt: ein Element aus der Struktur, eine Referenz darauf aus dem Elternelement, Referenzen darauf aus Kindobjekten, das entsprechende Objekt aus dem Dokument. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Entfernt ein Element aus der Struktur, eine Referenz darauf aus dem Elternelement, Referenzen darauf aus Kindobjekten und das entsprechende Objekt aus dem Dokument. Fügt die Kindobjekte des entfernten Objekts in die Sammlung der Kindobjekte des ehemaligen Elternteils ein, beginnend am Index des entfernten Objekts. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Entfernt das Kind an. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Setzt die ID für das Strukturelement. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Setzt ein benutzerdefiniertes Tag für das Strukturelement. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Bindet ein Strukturelement an die Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Bindet ein Strukturelement an das Artefakt. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bindet ein Strukturelement an den Inhaltstream BDC-Operator. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Bindet ein Strukturelement an den Inhaltstream XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Bindet ein Strukturelement an das XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* Klasse [BLSElement](../blselement/)
* Schnittstelle [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* Assembly [Aspose.PDF](../../)