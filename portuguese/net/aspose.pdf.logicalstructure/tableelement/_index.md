---
title: Class TableElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.TableElement. Representa o elemento de estrutura de tabela na estrutura lógica
type: docs
weight: 6780
url: /pt/net/aspose.pdf.logicalstructure/tableelement/
---
## Classe TableElement

Representa o elemento de estrutura de tabela na estrutura lógica.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtém ou define o texto real para o elemento de estrutura. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Obtém ou define o alinhamento da tabela. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtém ou define o texto alternativo para o elemento de estrutura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtém o objeto StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Obtém ou define a cor de fundo da tabela. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Obtém ou define a borda da tabela. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Obtém ou define se a tabela está verticalmente quebrada; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtém a coleção de filhos de objetos Element. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Obtém ou define o ajuste da coluna da tabela. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Obtém as larguras das colunas da tabela. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Obtém ou define os estilos dos cantos da borda |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtém o objeto AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Obtém a borda padrão da célula. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Obtém ou define o preenchimento padrão da célula. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Obtém ou define o estado de texto padrão da célula. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Obtém ou define a largura padrão da coluna. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtém ou define o texto de expansão para o elemento de estrutura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtém o ID para o elemento de estrutura. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Obtém ou define se a borda está incluída nas larguras das colunas. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Obtém ou define se a tabela está quebrada - será truncada para a próxima página. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtém ou define o idioma para o elemento de estrutura. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Obtém ou define a coordenada esquerda da tabela. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtém a página na qual alguns ou todos os elementos filhos serão renderizados. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtém o elemento pai. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Obtém ou define a contagem máxima de colunas para a tabela. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Obtém a contagem das primeiras linhas repetidas por várias páginas. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Obtém o estilo para linhas repetidas. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtém o tipo do elemento de estrutura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtém ou define o título para o elemento de estrutura. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Obtém ou define a coordenada superior da tabela. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Anexa o Elemento à coleção de filhos. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Altera o elemento pai para o elemento de estrutura atual |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpa todos os filhos. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Limpa o ID para o elemento de estrutura. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Cria [`TableTHeadElement`](../tabletheadelement/) e o adiciona à tabela atual. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Cria [`TableTFootElement`](../tabletfootelement/) e o adiciona à tabela atual. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Cria [`TableTHeadElement`](../tabletheadelement/) e o adiciona à tabela atual. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encontra elementos de um tipo dado |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Gera um ID para o elemento de estrutura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insere o Elemento na coleção de filhos no índice especificado. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Remove: um elemento da estrutura, uma referência a ele do objeto pai, referências a ele de objetos filhos, o objeto correspondente do documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Remove um elemento da estrutura, uma referência a ele do objeto pai, referências a ele de objetos filhos, e o objeto correspondente do documento. Insere os objetos filhos do objeto removido na coleção de objetos filhos do seu antigo pai, começando no índice do objeto removido. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove o filho na posição. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Define o ID para o elemento de estrutura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Define uma tag personalizada para o elemento de estrutura. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Vincula um elemento de estrutura à Anotação. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Vincula um elemento de estrutura ao Artefato. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Vincula um elemento de estrutura ao operador BDC do fluxo de conteúdo. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Vincula um elemento de estrutura ao XForm do fluxo de conteúdo. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Vincula um elemento de estrutura à XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Retorna uma string que representa o objeto atual. |

### Veja Também

* classe [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)