---
title: Class TableTDElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableTDElement-Klasse. Stellt das TD-Strukturelement in der logischen Struktur der Tabelle dar
type: docs
weight: 6810
url: /de/net/aspose.pdf.logicalstructure/tabletdelement/
---
## Klasse TableTDElement

Stellt das TD-Strukturelement in der logischen Struktur der Tabelle dar.

```csharp
public sealed class TableTDElement : TableCellElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Ruft den tatsächlichen Text für das Strukturelement ab oder legt ihn fest. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Ruft die Zellenausrichtung ab oder legt sie fest. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Ruft den alternativen Text für das Strukturelement ab oder legt ihn fest. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Ruft das StructureAttributeCollection-Objekt ab. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Ruft die Hintergrundfarbe der Zelle ab oder legt sie fest. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Ruft den Zellrand ab oder legt ihn fest. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ruft die Sammlung der Kind-Elementobjekte ab. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Ruft den Spaltenumfang ab oder legt ihn fest. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Ruft das AttributeOwnerStandard-Objekt ab. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Ruft den Standardtextzustand der Zelle ab oder legt ihn fest. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Ruft den Erweiterungstext für das Strukturelement ab oder legt ihn fest. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Ruft die ID für das Strukturelement ab. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Ruft ab oder legt fest, ob die Zelle keinen Rand hat. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Ruft ab oder legt fest, ob der Text der Zelle umgebrochen ist. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Ruft die Sprache für das Strukturelement ab oder legt sie fest. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | Ruft das Padding ab oder legt es fest. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Ruft die Seite ab, auf der einige oder alle Kind-Elemente gerendert werden. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ruft das übergeordnete Element ab. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Ruft den Zeilenumfang ab oder legt ihn fest. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Ruft das StructureTextState-Objekt für das aktuelle Element ab. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Ruft den Typ des Strukturelements ab. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Ruft den Titel für das Strukturelement ab oder legt ihn fest. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Fügt ein Element zur Sammlung der Kinder hinzu. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Ändert das übergeordnete Element für das aktuelle Strukturelement |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Löscht alle Kinder. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Löscht die ID für das Strukturelement. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Findet Elemente eines bestimmten Typs |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generiert eine ID für das Strukturelement. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Fügt ein Element an der angegebenen Stelle in die Sammlung der Kinder ein. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Entfernt: ein Element aus der Struktur, eine Referenz darauf aus dem übergeordneten Objekt, Referenzen darauf aus Kindobjekten, das entsprechende Objekt aus dem Dokument. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Entfernt ein Element aus der Struktur, eine Referenz darauf aus dem übergeordneten Objekt, Referenzen darauf aus Kindobjekten und das entsprechende Objekt aus dem Dokument. Fügt die Kindobjekte des entfernten Objekts in die Sammlung der Kindobjekte des ehemaligen übergeordneten Objekts ein, beginnend an der Stelle des entfernten Objekts. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Entfernt das Kind an. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Legt die ID für das Strukturelement fest. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Legt ein benutzerdefiniertes Tag für das Strukturelement fest. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Bindet ein Strukturelement an die Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Bindet ein Strukturelement an das Artefakt. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bindet ein Strukturelement an den Inhaltstream BDC-Operator. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Bindet ein Strukturelement an den Inhaltstream XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Bindet ein Strukturelement an das XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* Klasse [TableCellElement](../tablecellelement/)
* Namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* Assembly [Aspose.PDF](../../)