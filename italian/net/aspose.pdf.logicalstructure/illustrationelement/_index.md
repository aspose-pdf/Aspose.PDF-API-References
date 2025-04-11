---
title: Class IllustrationElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.IllustrationElement. Rappresenta una classe base per gli elementi della struttura di illustrazione nella struttura logica
type: docs
weight: 6420
url: /it/net/aspose.pdf.logicalstructure/illustrationelement/
---
## Classe IllustrationElement

Rappresenta una classe base per gli elementi della struttura di illustrazione nella struttura logica.

```csharp
public abstract class IllustrationElement : StructureElement, IAdjustPosition
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Ottiene o imposta il testo effettivo per l'elemento di struttura. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Ottiene o imposta il testo alternativo per l'elemento di struttura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Ottiene l'oggetto StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ottiene la collezione di elementi figli di oggetti Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Ottiene l'oggetto AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Ottiene o imposta il testo di espansione per l'elemento di struttura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Ottiene l'ID per l'elemento di struttura. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Ottiene o imposta la lingua per l'elemento di struttura. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Ottiene la pagina su cui alcuni o tutti gli elementi figli verranno renderizzati. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ottiene l'elemento padre. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Ottiene il tipo di elemento di struttura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Ottiene o imposta il titolo per l'elemento di struttura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/illustrationelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Aggiunge l'Element alla collezione di figli. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia l'elemento padre per l'elemento di struttura corrente |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Pulisce tutti i figli. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Pulisce l'ID per l'elemento di struttura. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trova elementi di un dato tipo |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genera ID per l'elemento di struttura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserisce l'Element nella collezione di figli all'indice specificato. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Rimuove: un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figli, l'oggetto corrispondente dal documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figli, e l'oggetto corrispondente dal documento. Inserisce gli oggetti figli dell'oggetto rimosso nella collezione di oggetti figli del suo precedente genitore a partire dall'indice dell'oggetto rimosso. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Rimuove il figlio all'indice. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Imposta l'ID per l'elemento di struttura. |
| virtual [SetImage](../../aspose.pdf.logicalstructure/illustrationelement/setimage/#setimage)(string, double) | Aggiunge un'immagine all'elemento di illustrazione corrente. |
| virtual [SetImage](../../aspose.pdf.logicalstructure/illustrationelement/setimage/#setimage_1)(string, double, double) | Aggiunge un'immagine all'elemento di illustrazione corrente. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Imposta un tag personalizzato per l'elemento di struttura. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Collega un elemento di struttura all'Annotazione. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Collega un elemento di struttura all'Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Collega un elemento di struttura all'operatore BDC del flusso di contenuto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Collega un elemento di struttura al XForm del flusso di contenuto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Collega un elemento di struttura all'XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Vedi anche

* classe [StructureElement](../structureelement/)
* interfaccia [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)