---
title: "Classe Element"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.LogicalStructure.Element. Rappresenta una classe base per l'elemento nella struttura logica"
type: docs
weight: 6460
url: /it/net/aspose.pdf.logicalstructure/element/
---
## Element class

Rappresenta una classe base per l'elemento nella struttura logica.

```csharp
public abstract class Element
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ottiene la collezione di figli di oggetti Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ottieni l'elemento genitore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Aggiungi Element alla collezione di figli. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Cancella tutti i figli. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trova Elementi di un determinato tipo |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserisci Element nella collezione di figli all'indice specificato. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Rimuovi figlio a. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Associa un elemento di struttura all'Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Associa un elemento di struttura all'Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Associa un elemento di struttura all'operatore BDC del flusso di contenuto. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Associa un elemento di struttura al XForm del flusso di contenuto. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Associa un elemento di struttura al XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Vedi anche

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


