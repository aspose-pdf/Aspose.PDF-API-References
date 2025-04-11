---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Table. Representa uma tabela que pode ser adicionada à página
type: docs
weight: 10280
url: /pt/net/aspose.pdf/table/
---
## Classe Tabela

Representa uma tabela que pode ser adicionada à página.

```csharp
public sealed class Table : BaseParagraph
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Table](table/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Obtém ou define o alinhamento da tabela. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Obtém ou define a cor de fundo da tabela |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Obtém ou define a borda. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Obtém ou define o texto de quebra para a tabela |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Obtém ou define se a tabela está quebrada verticalmente; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Obtém ou define o ajuste da coluna da tabela. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Obtém as larguras das colunas da tabela. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Obtém ou define os estilos dos cantos da borda |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Obtém a borda padrão da célula; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Obtém ou define o preenchimento padrão da célula. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Obtém ou define o estado do texto padrão da célula. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Obtém a borda padrão da célula; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do parágrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Obtém ou define se a borda está incluída nas larguras das colunas. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Obtém ou define se a tabela está quebrada - será truncada para a próxima página. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo está em linha. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Obtém ou define a coordenada esquerda da tabela. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Obtém ou define a contagem máxima de colunas para a tabela |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Obtém a contagem das primeiras linhas repetidas por várias páginas |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Obtém o estilo para linhas repetidas |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Obtém as linhas da tabela. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Obtém ou define a coordenada superior da tabela. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Clona a tabela. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Obtém a altura. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Obtém a largura. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Importa um array unidimensional de dados para a tabela. A importação ocorre uma célula por cada item do array e começa pela linha e coluna definidas nos parâmetros. Durante a importação, se detectar que as linhas necessárias ainda estão ausentes (ou seja, a tabela de destino é muito pequena para absorver todos os dados), as linhas necessárias serão criadas |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Importa dados do System.Data.DataTable para Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importa um objeto DataTable para a tabela. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importa um objeto DataTable, mas não como uma entidade inteira. Apenas as linhas e colunas especificadas são importadas. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Importa os dados de um objeto DataView para a tabela. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Define a altura. |

### Veja Também

* classe [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)