---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableTRElement klass. Representerar TR-struktur element i den logiska strukturen av tabellen
type: docs
weight: 6850
url: /sv/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement klass

Representerar TR-struktur element i den logiska strukturen av tabellen.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Hämtar eller sätter den faktiska texten för struktur element. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Hämtar eller sätter den alternativa texten för struktur element. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Hämtar StructureAttributeCollection objekt. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | Hämtar eller sätter radens bakgrundsfärg. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | Hämtar eller sätter radens kantlinje. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Hämtar barnkollektion av Element objekt. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Hämtar AttributeOwnerStandard objekt. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | Hämtar standard cellkant. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | Hämtar eller sätter standard marginal för radens celler. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | Hämtar eller sätter standard texttillstånd för radens celler |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Hämtar eller sätter expansions texten för struktur element. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | Hämtar fast rad höjd - raden kan ha fast höjd. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Hämtar ID för struktur element. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | Hämtar om fast rad är på ny sida - sidan med denna egenskap bör skrivas ut på nästa sida. Standard falsk. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | Hämtar om raden kan brytas mellan två sidor. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Hämtar eller sätter språket för struktur element. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | Hämtar höjd för rad. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Hämtar sidan på vilken några eller alla barn element kommer att renderas. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Hämtar föräldraelementet. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Hämtar typ av struktur element. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Hämtar eller sätter titeln för struktur element. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | Hämtar eller sätter den vertikala justeringen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Lägg till Element till samlingen av barn. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Ändra föräldraelementet för det aktuella struktur elementet |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Rensa alla barn. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Rensa ID för struktur element. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | Skapar [`TableTHElement`](../tablethelement/) och lägger till det i den aktuella tabellen. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | Skapar [`TableTHElement`](../tablethelement/) och lägger till det i den aktuella tabellen. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Hitta Element av en given typ |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generera ID för struktur element. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Infoga Element till samlingen av barn vid angiven index. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Tar bort: ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, det motsvarande objektet från dokumentet. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, och det motsvarande objektet från dokumentet. Infogar barnobjekt av det borttagna objektet i dess tidigare förälders barnobjekts samling som börjar vid indexet för det borttagna objektet. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Ta bort barn vid. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Sätter ID för struktur element. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Sätter anpassad tagg för struktur element. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Binder ett struktur element till Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Binder ett struktur element till Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Binder ett struktur element till innehållsström BDC-operator. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Binder ett struktur element till innehållsström XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Binder ett struktur element till XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se Även

* klass [TableChildElement](../tablechildelement/)
* namnrymd [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* sammansättning [Aspose.PDF](../../)