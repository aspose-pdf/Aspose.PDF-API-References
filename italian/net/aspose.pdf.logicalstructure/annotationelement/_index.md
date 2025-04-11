---
title: Class AnnotationElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.AnnotationElement. Rappresenta una classe base per gli elementi della struttura di annotazione nella struttura logica
type: docs
weight: 6190
url: /it/net/aspose.pdf.logicalstructure/annotationelement/
---
## Classe AnnotationElement

Rappresenta una classe base per gli elementi della struttura di annotazione nella struttura logica.

```csharp
public abstract class AnnotationElement : ILSElement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Ottiene o imposta il testo effettivo per l'elemento della struttura. |
| [AlternateDescriptions](../../aspose.pdf.logicalstructure/annotationelement/alternatedescriptions/) { get; set; } | Ottiene o imposta le descrizioni alternative per l'annotazione. Testo che deve essere visualizzato per l'annotazione o, se questo tipo di annotazione non visualizza testo, una descrizione alternativa del contenuto dell'annotazione in forma leggibile dall'uomo. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Ottiene o imposta il testo alternativo per l'elemento della struttura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Ottiene l'oggetto StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ottiene la collezione di oggetti Element figli. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Ottiene l'oggetto AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Ottiene o imposta il testo di espansione per l'elemento della struttura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Ottiene l'ID per l'elemento della struttura. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Ottiene o imposta la lingua per l'elemento della struttura. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Ottiene la pagina su cui alcuni o tutti gli elementi figli verranno visualizzati. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ottiene l'elemento genitore. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Ottiene il tipo di elemento della struttura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Ottiene o imposta il titolo per l'elemento della struttura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Aggiunge un elemento alla collezione di figli. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia l'elemento genitore per l'elemento della struttura corrente |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Pulisce tutti i figli. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Pulisce l'ID per l'elemento della struttura. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trova elementi di un dato tipo |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genera un ID per l'elemento della struttura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserisce un elemento nella collezione di figli all'indice specificato. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Rimuove: un elemento dalla struttura, un riferimento ad esso dall'oggetto genitore, riferimenti ad esso dagli oggetti figli, l'oggetto corrispondente dal documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto genitore, riferimenti ad esso dagli oggetti figli e l'oggetto corrispondente dal documento. Inserisce gli oggetti figli dell'oggetto rimosso nella collezione di oggetti figli del suo precedente genitore a partire dall'indice dell'oggetto rimosso. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Rimuove il figlio all'indice specificato. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Imposta l'ID per l'elemento della struttura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Imposta un tag personalizzato per l'elemento della struttura. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Collega un elemento della struttura all'annotazione. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Collega un elemento della struttura all'artefatto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Collega un elemento della struttura all'operatore BDC del flusso di contenuto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Collega un elemento della struttura al flusso di contenuto XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Collega un elemento della struttura all'XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Vedi Anche

* classe [ILSElement](../ilselement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)