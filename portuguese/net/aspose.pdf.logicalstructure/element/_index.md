---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.Element. Representa uma classe base para elemento na estrutura lógica
type: docs
weight: 6320
url: /pt/net/aspose.pdf.logicalstructure/element/
---
## Classe Elemento

Representa uma classe base para elemento na estrutura lógica.

```csharp
public abstract class Element
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtém a coleção de filhos de objetos Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtém o elemento pai. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Adiciona Element à coleção de filhos. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpa todos os filhos. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encontra Elementos de um tipo dado |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insere Element na coleção de filhos no índice especificado. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove filho em. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Vincula um elemento de estrutura à Anotação. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Vincula um elemento de estrutura ao Artefato. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Vincula um elemento de estrutura ao operador BDC do fluxo de conteúdo. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Vincula um elemento de estrutura ao XForm do fluxo de conteúdo. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Vincula um elemento de estrutura ao XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Retorna uma string que representa o objeto atual. |

### Veja Também

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)