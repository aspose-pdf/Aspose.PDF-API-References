---
title: Class MCRElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.MCRElement. Rappresenta un oggetto di riferimento di contenuto contrassegnato nella struttura logica
type: docs
weight: 6500
url: /it/net/aspose.pdf.logicalstructure/mcrelement/
---
## Classe MCRElement

Rappresenta un oggetto di riferimento di contenuto contrassegnato nella struttura logica.

```csharp
public sealed class MCRElement : Element
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ottiene la collezione di oggetti Element figli. |
| [MCID](../../aspose.pdf.logicalstructure/mcrelement/mcid/) { get; } | Ottiene l'MCID dell'oggetto di riferimento di contenuto contrassegnato. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ottiene l'elemento padre. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Aggiunge un Element alla collezione di figli. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Pulisce tutti i figli. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trova gli Element di un tipo specificato |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserisce un Element nella collezione di figli all'indice specificato. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Rimuove il figlio all'indice. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_2)(Annotation) | Collega un elemento di struttura all'Annotazione. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag)(Artifact) | Collega un elemento di struttura all'Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_1)(BDC) | Collega un elemento di struttura all'operatore BDC del flusso di contenuto. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_3)(XForm) | Collega un elemento di struttura al flusso di contenuto XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_4)(XImage) | Collega un elemento di struttura all'XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/mcrelement/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Vedi Anche

* classe [Element](../element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)