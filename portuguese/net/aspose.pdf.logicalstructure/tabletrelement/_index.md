---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.TableTRElement. Representa o elemento de estrutura TR na estrutura lógica da tabela
type: docs
weight: 6850
url: /pt/net/aspose.pdf.logicalstructure/tabletrelement/
---
## Classe TableTRElement

Representa o elemento de estrutura TR na estrutura lógica da tabela.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtém ou define o texto real para o elemento de estrutura. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtém ou define o texto alternativo para o elemento de estrutura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtém o objeto StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | Obtém ou define a cor de fundo da linha. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | Obtém ou define a borda da linha. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtém a coleção de filhos de objetos Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtém o objeto AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | Obtém a borda padrão da célula. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | Obtém ou define a margem padrão para as células da linha. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | Obtém ou define o estado de texto padrão para as células da linha |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtém ou define o texto de expansão para o elemento de estrutura. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | Obtém a altura fixa da linha - a linha pode ter altura fixa. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtém o ID para o elemento de estrutura. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | Obtém se a linha fixa está em nova página - a página com esta propriedade deve ser impressa na próxima página. Padrão falso. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | Obtém se a linha pode ser quebrada entre duas páginas. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtém ou define o idioma para o elemento de estrutura. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | Obtém a altura da linha. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtém a página na qual alguns ou todos os elementos filhos serão renderizados. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtém o elemento pai. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtém o tipo do elemento de estrutura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtém ou define o título para o elemento de estrutura. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | Obtém ou define o alinhamento vertical. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Anexa o Elemento à coleção de filhos. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Altera o elemento pai para o elemento de estrutura atual |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpa todos os filhos. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Limpa o ID para o elemento de estrutura. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | Cria [`TableTHElement`](../tablethelement/) e o adiciona à tabela atual. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | Cria [`TableTHElement`](../tablethelement/) e o adiciona à tabela atual. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encontra Elementos de um tipo dado |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Gera um ID para o elemento de estrutura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insere o Elemento na coleção de filhos no índice especificado. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Remove: um elemento da estrutura, uma referência a ele do objeto pai, referências a ele de objetos filhos, o objeto correspondente do documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Remove um elemento da estrutura, uma referência a ele do objeto pai, referências a ele de objetos filhos, e o objeto correspondente do documento. Insere os objetos filhos do objeto removido na coleção de objetos filhos do seu antigo pai, começando no índice do objeto removido. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Remove o filho em. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Define o ID para o elemento de estrutura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Define uma tag personalizada para o elemento de estrutura. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Vincula um elemento de estrutura à Anotação. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Vincula um elemento de estrutura ao Artefato. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Vincula um elemento de estrutura ao operador BDC do fluxo de conteúdo. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Vincula um elemento de estrutura ao XForm do fluxo de conteúdo. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Vincula um elemento de estrutura à XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Retorna uma string que representa o objeto atual. |

### Veja Também

* classe [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)