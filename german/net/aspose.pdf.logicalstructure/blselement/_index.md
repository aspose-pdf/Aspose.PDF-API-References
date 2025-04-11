---
title: Class BLSElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.BLSElement-Klasse. Stellt eine Basisklasse für Blockstruktur-Elemente in der logischen Struktur dar
type: docs
weight: 6240
url: /de/net/aspose.pdf.logicalstructure/blselement/
---
## BLSElement-Klasse

Stellt eine Basisklasse für Blockstruktur-Elemente in der logischen Struktur dar.

```csharp
public abstract class BLSElement : StructureElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Ruft den tatsächlichen Text für das Struktur-Element ab oder legt ihn fest. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Ruft den alternativen Text für das Struktur-Element ab oder legt ihn fest. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Ruft das StructureAttributeCollection-Objekt ab. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ruft die Sammlung der Kind-Elemente ab. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Ruft das AttributeOwnerStandard-Objekt ab. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Ruft den Expansionstext für das Struktur-Element ab oder legt ihn fest. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Ruft die ID für das Struktur-Element ab. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Ruft die Sprache für das Struktur-Element ab oder legt sie fest. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Ruft die Seite ab, auf der einige oder alle Kind-Elemente gerendert werden. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ruft das übergeordnete Element ab. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Ruft den Typ des Struktur-Elements ab. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Ruft den Titel für das Struktur-Element ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Fügt ein Element zur Sammlung der Kinder hinzu. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Ändert das übergeordnete Element für das aktuelle Struktur-Element. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Löscht alle Kinder. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Löscht die ID für das Struktur-Element. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Findet Elemente eines bestimmten Typs. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generiert eine ID für das Struktur-Element. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Fügt ein Element an einem bestimmten Index in die Sammlung der Kinder ein. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Entfernt: ein Element aus der Struktur, eine Referenz darauf aus dem übergeordneten Objekt, Referenzen darauf aus Kindobjekten, das entsprechende Objekt aus dem Dokument. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Entfernt ein Element aus der Struktur, eine Referenz darauf aus dem übergeordneten Objekt, Referenzen darauf aus Kindobjekten und das entsprechende Objekt aus dem Dokument. Fügt die Kindobjekte des entfernten Objekts in die Sammlung der Kindobjekte des ehemaligen übergeordneten Objekts ein, beginnend am Index des entfernten Objekts. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Entfernt das Kind an. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Legt die ID für das Struktur-Element fest. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Legt ein benutzerdefiniertes Tag für das Struktur-Element fest. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Bindet ein Struktur-Element an die Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Bindet ein Struktur-Element an das Artefakt. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bindet ein Struktur-Element an den Inhaltstream BDC-Operator. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Bindet ein Struktur-Element an den Inhaltstream XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Bindet ein Struktur-Element an das XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* Klasse [StructureElement](../structureelement/)
* Namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* Assembly [Aspose.PDF](../../)