---
title: Class WarichuWPElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.WarichuWPElement class. Represents WP structure element in logical structure of the Warichu
type: docs
weight: 6880
url: /it/net/aspose.pdf.logicalstructure/warichuwpelement/
---
## WarichuWPElement class

Rappresenta l'elemento di struttura WP nella struttura logica del Warichu.

```csharp
public sealed class WarichuWPElement : WarichuChildElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Ottiene o imposta il testo effettivo per l'elemento di struttura. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Ottiene o imposta il testo alternativo per l'elemento di struttura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Ottiene l'oggetto StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ottiene la collezione di oggetti Element figli. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Ottiene l'oggetto AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Ottiene o imposta il testo di espansione per l'elemento di struttura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Ottiene l'ID per l'elemento di struttura. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Ottiene o imposta la lingua per l'elemento di struttura. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Ottiene la pagina su cui alcuni o tutti gli elementi figli verranno renderizzati. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ottiene l'elemento genitore. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Ottiene il tipo di elemento di struttura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Ottiene o imposta il titolo per l'elemento di struttura. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Aggiunge un Element alla collezione di figli. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia l'elemento genitore per l'elemento di struttura corrente |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Pulisce tutti i figli. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Pulisce l'ID per l'elemento di struttura. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trova gli Element di un dato tipo |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genera un ID per l'elemento di struttura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserisce un Element nella collezione di figli all'indice specificato. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Rimuove: un elemento dalla struttura, un riferimento ad esso dall'oggetto genitore, riferimenti ad esso dagli oggetti figli, l'oggetto corrispondente dal documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto genitore, riferimenti ad esso dagli oggetti figli, e l'oggetto corrispondente dal documento. Inserisce gli oggetti figli dell'oggetto rimosso nella collezione di oggetti figli del suo precedente genitore a partire dall'indice dell'oggetto rimosso. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Rimuove il figlio all'indice. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Imposta l'ID per l'elemento di struttura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Imposta un tag personalizzato per l'elemento di struttura. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Collega un elemento di struttura all'Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Collega un elemento di struttura all'Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Collega un elemento di struttura all'operatore BDC del flusso di contenuto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Collega un elemento di struttura al flusso di contenuto XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Collega un elemento di struttura all'XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### See Also

* class [WarichuChildElement](../warichuchildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)