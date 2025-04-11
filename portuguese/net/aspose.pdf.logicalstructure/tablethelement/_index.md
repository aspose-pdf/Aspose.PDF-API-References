---
title: Class TableTHElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.TableTHElement. Representa o elemento de estrutura TH na estrutura lógica da tabela
type: docs
weight: 6830
url: /pt/net/aspose.pdf.logicalstructure/tablethelement/
---
## Classe TableTHElement

Representa o elemento de estrutura TH na estrutura lógica da tabela.

```csharp
public sealed class TableTHElement : TableCellElement
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtém ou define o texto real para o elemento de estrutura. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Obtém ou define o alinhamento da célula. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtém ou define o texto alternativo para o elemento de estrutura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtém o objeto StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Obtém ou define a cor de fundo da célula. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Obtém ou define a borda da célula. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtém a coleção de filhos de objetos Element. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Obtém ou define a extensão da coluna. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtém o objeto AttributeOwnerStandard. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Obtém ou define o estado de texto padrão da célula. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtém ou define o texto de expansão para o elemento de estrutura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtém o ID para o elemento de estrutura. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Obtém ou define se a célula tem borda. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Obtém ou define se o texto da célula está quebrado em palavras. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtém ou define o idioma para o elemento de estrutura. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | Obtém ou define o preenchimento. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtém a página na qual alguns ou todos os elementos filhos serão renderizados. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtém o elemento pai. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Obtém ou define a extensão da linha. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Obtém o objeto StructureTextState para o elemento atual. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtém o tipo de elemento de estrutura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtém ou define o título para o elemento de estrutura. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Obtém ou define o alinhamento vertical. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Anexa o Elemento à coleção de filhos. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Altera o elemento pai para o elemento de estrutura atual |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpa todos os filhos. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Limpa o ID para o elemento de estrutura. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encontra Elementos de um tipo dado |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Gera um ID para o elemento de estrutura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insere o Elemento na coleção de filhos no índice especificado. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Remove: um elemento da estrutura, uma referência a ele do objeto pai, referências a ele de objetos filhos, o objeto correspondente do documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Remove um elemento da estrutura, uma referência a ele do objeto pai, referências a ele de objetos filhos, e o objeto correspondente do documento. Insere os objetos filhos do objeto removido na coleção de objetos filhos do seu antigo pai, começando no índice do objeto removido. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove o filho em. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Define o ID para o elemento de estrutura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Define uma tag personalizada para o elemento de estrutura. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Vincula um elemento de estrutura à Anotação. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Vincula um elemento de estrutura ao Artefato. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Vincula um elemento de estrutura ao operador BDC do fluxo de conteúdo. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Vincula um elemento de estrutura ao XForm do fluxo de conteúdo. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Vincula um elemento de estrutura ao XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Retorna uma string que representa o objeto atual. |

### Veja Também

* classe [TableCellElement](../tablecellelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)