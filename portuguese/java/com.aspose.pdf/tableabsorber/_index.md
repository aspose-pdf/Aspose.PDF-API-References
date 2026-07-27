---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um objeto absorvedor de elementos de tabela. Executa a pesquisa e fornece acesso aos resultados da pesquisa via coleção {@code TableAbsorber.TableList}. </p> <hr> <pre> O."
type: docs
weight: 4800
url: /pt/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Representa um objeto absorvedor de elementos de tabela. Executa a pesquisa e fornece acesso aos resultados da pesquisa via coleção {@code TableAbsorber.TableList}. </p> <hr> <pre> O exemplo demonstra como encontrar a tabela na primeira página do documento PDF e substituir o texto em uma célula da tabela. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Inicializa uma nova instância do {@code TableAbsorber}. </p> <hr> Executa a pesquisa de tabelas e fornece acesso às tabelas via objeto {@code TableList}. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa uma nova instância do {@code TableAbsorber}. </p> <hr> Executa a pesquisa de tabelas e fornece acesso às tabelas via objeto {@code TableList}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getTableList](#getTableList--) | <p> Retorna IList somente leitura contendo as tabelas que foram encontradas </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Obtém opções de pesquisa de texto. </p> <hr> Permite definir várias opções que serão usadas durante a pesquisa de texto contido em tabelas. |
| [isUseFlowEngine](#isUseFlowEngine--) | Habilite um mecanismo alternativo de reconhecimento de tabelas que é superior em diversos cenários e capaz de reconhecer tabelas sem bordas. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Remove um {@code AbsorbedTable} da página. </p> <hr> <p> Por favor, considere que isso altera a coleção TableList. Caso remova/substitua tabelas em um loop, use uma cópia da coleção TableList. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Substitui um {@code AbsorbedTable} por {@code Table} na página. </p> <hr> <p> Por favor, considere que isso altera a coleção TableList. Caso remova/substitua tabelas em um loop, use uma cópia da coleção TableList. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Obtém ou define opções de pesquisa de texto. </p> <hr> Permite definir várias opções que serão usadas durante a pesquisa de texto contido em tabelas. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Habilite um mecanismo alternativo de reconhecimento de tabelas que é superior em diversos cenários e capaz de reconhecer tabelas sem bordas. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extrai tabelas no documento especificado. </p> <hr> <pre> O exemplo demonstra como extrair a tabela na primeira página do documento PDF. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extrai tabelas na página especificada </p> <hr> <pre> O exemplo demonstra como extrair a tabela na primeira página do documento PDF. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Inicializa uma nova instância do {@code TableAbsorber}. </p> <hr> Executa a pesquisa de tabelas e fornece acesso às tabelas via objeto {@code TableList}.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa uma nova instância do {@code TableAbsorber}. </p> <hr> Executa a pesquisa de tabelas e fornece acesso às tabelas via objeto {@code TableList}.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Retorna IList somente leitura contendo as tabelas que foram encontradas </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Obtém opções de pesquisa de texto. </p> <hr> Permite definir várias opções que serão usadas durante a pesquisa de texto contido em tabelas.

**Returns:**
TextSearchOptions objeto

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Habilite um mecanismo alternativo de reconhecimento de tabelas que é superior em diversos cenários e capaz de reconhecer tabelas sem bordas.

**Returns:**
valor booleano

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Remove um {@code AbsorbedTable} da página. </p> <hr> <p> Por favor, considere que isso altera a coleção TableList. Caso remova/substitua tabelas em um loop, use uma cópia da coleção TableList. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Substitui um {@code AbsorbedTable} por {@code Table} na página. </p> <hr> <p> Por favor, considere que isso altera a coleção TableList. Caso remova/substitua tabelas em um loop, use uma cópia da coleção TableList. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Obtém ou define opções de pesquisa de texto. </p> <hr> Permite definir várias opções que serão usadas durante a pesquisa de texto contido em tabelas.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Habilite um mecanismo alternativo de reconhecimento de tabelas que é superior em diversos cenários e capaz de reconhecer tabelas sem bordas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| useFlowEngine |  | valor booleano |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extrai tabelas no documento especificado. </p> <hr> <pre> O exemplo demonstra como extrair uma tabela na primeira página do documento PDF. // Abrir documento Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Criar objeto TableAbsorber para encontrar tabelas TableAbsorber absorber = new TableAbsorber(); // Visitar a primeira página com o absorvedor absorber.visit(pdfDocument); // Obter acesso à primeira tabela na página, sua primeira célula e fragmentos de texto nela TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Alterar o texto do primeiro fragmento de texto na célula fragment.setText (\"hi world\"); // Salvar documento doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extrai tabelas na página especificada </p> <hr> <pre> O exemplo demonstra como extrair uma tabela na primeira página do documento PDF. // Abrir documento Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Criar objeto TableAbsorber para encontrar tabelas TableAbsorber absorber = new TableAbsorber(); // Visitar a primeira página com o absorvedor absorber.visit(doc.getPages.get_item(1)); // Obter acesso à primeira tabela na página, sua primeira célula e fragmentos de texto nela TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Alterar o texto do primeiro fragmento de texto na célula fragment.setText (\"hi world\"); // Salvar documento doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
