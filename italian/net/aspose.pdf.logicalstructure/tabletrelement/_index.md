---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.TableTRElement. Rappresenta l'elemento di struttura TR nella struttura logica della tabella
type: docs
weight: 6850
url: /it/net/aspose.pdf.logicalstructure/tabletrelement/
---
## Classe TableTRElement

Rappresenta l'elemento di struttura TR nella struttura logica della tabella.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Ottiene o imposta il testo effettivo per l'elemento di struttura. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Ottiene o imposta il testo alternativo per l'elemento di struttura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Ottiene l'oggetto StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | Ottiene o imposta il colore di sfondo della riga. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | Ottiene o imposta il bordo della riga. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ottiene la collezione di figli degli oggetti Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Ottiene l'oggetto AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | Ottiene il bordo predefinito della cella. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | Ottiene o imposta il margine predefinito per le celle della riga. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | Ottiene o imposta lo stato del testo predefinito per le celle della riga |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Ottiene o imposta il testo di espansione per l'elemento di struttura. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | Ottiene l'altezza fissa della riga - la riga può avere un'altezza fissa. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Ottiene l'ID per l'elemento di struttura. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | Ottiene se la riga fissa è in una nuova pagina - la pagina con questa proprietà dovrebbe essere stampata sulla pagina successiva. Predefinito falso. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | Ottiene se la riga può essere spezzata tra due pagine. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Ottiene o imposta la lingua per l'elemento di struttura. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | Ottiene l'altezza per la riga. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Ottiene la pagina su cui alcuni o tutti gli elementi figli verranno renderizzati. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ottiene l'elemento genitore. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Ottiene il tipo di elemento di struttura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Ottiene o imposta il titolo per l'elemento di struttura. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Aggiunge l'Element alla collezione di figli. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia l'elemento genitore per l'elemento di struttura corrente |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Pulisce tutti i figli. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Pulisce l'ID per l'elemento di struttura. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | Crea [`TableTHElement`](../tablethelement/) e lo aggiunge alla tabella corrente. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | Crea [`TableTHElement`](../tablethelement/) e lo aggiunge alla tabella corrente. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trova gli Element di un dato tipo |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genera un ID per l'elemento di struttura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserisce l'Element nella collezione di figli all'indice specificato. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Rimuove: un elemento dalla struttura, un riferimento ad esso dall'oggetto genitore, riferimenti ad esso dagli oggetti figli, l'oggetto corrispondente dal documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto genitore, riferimenti ad esso dagli oggetti figli, e l'oggetto corrispondente dal documento. Inserisce gli oggetti figli dell'oggetto rimosso nella collezione di oggetti figli del suo ex genitore a partire dall'indice dell'oggetto rimosso. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Rimuove il figlio a. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Imposta l'ID per l'elemento di struttura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Imposta un tag personalizzato per l'elemento di struttura. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Collega un elemento di struttura all'Annotazione. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Collega un elemento di struttura all'Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Collega un elemento di struttura all'operatore BDC del flusso di contenuto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Collega un elemento di struttura al flusso di contenuto XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Collega un elemento di struttura all'XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Vedi anche

* classe [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)