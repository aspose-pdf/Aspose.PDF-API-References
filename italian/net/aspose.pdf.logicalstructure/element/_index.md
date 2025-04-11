---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Rappresenta una classe base per element nella struttura logica.
type: docs
weight: 6320
url: /it/net/aspose.pdf.logicalstructure/element/
---
## Classe Elemento

Rappresenta una classe base per elemento nella struttura logica.

```csharp
public abstract class Element
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ottiene la collezione di oggetti Element figli. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ottiene l'elemento genitore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Aggiunge un Elemento alla collezione di figli. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Pulisce tutti i figli. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trova Elementi di un tipo specifico |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserisce un Elemento nella collezione di figli all'indice specificato. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Rimuove il figlio a. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Collega un elemento di struttura all'Annotazione. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Collega un elemento di struttura all'Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Collega un elemento di struttura all'operatore BDC del flusso di contenuto. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Collega un elemento di struttura al flusso di contenuto XForm. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Collega un elemento di struttura all'XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Vedi Anche

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)