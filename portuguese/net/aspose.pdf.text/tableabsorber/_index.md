---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TableAbsorber. Representa um objeto absorvedor de elementos de tabela. Realiza busca e fornece acesso aos resultados da busca através da coleção TableList
type: docs
weight: 10790
url: /pt/net/aspose.pdf.text/tableabsorber/
---
## Classe TableAbsorber

Representa um objeto absorvedor de elementos de tabela. Realiza busca e fornece acesso aos resultados da busca através da coleção [`TableList`](./tablelist/).

```csharp
public class TableAbsorber
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Inicializa uma nova instância do `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Inicializa uma nova instância do `TableAbsorber` com opções de busca de texto. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Retorna uma IList somente leitura contendo tabelas que foram encontradas |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Obtém ou define opções de busca de texto. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Habilita um mecanismo alternativo de reconhecimento de tabela que é superior em numerosos cenários e é capaz de reconhecer tabelas sem bordas. Não suporta edição de tabelas e obtenção de estilos de texto ainda. O valor padrão é falso; |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Remove um [`AbsorbedTable`](../absorbedtable/) da página. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Substitui um [`AbsorbedTable`](../absorbedtable/) por um [`Table`](../../aspose.pdf/table/) na página. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Extrai tabelas no documento especificado. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Extrai tabelas na página especificada |

## Exemplos

O exemplo demonstra como encontrar uma tabela na primeira página do documento PDF e substituir o texto em uma célula da tabela.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Veja Também

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)