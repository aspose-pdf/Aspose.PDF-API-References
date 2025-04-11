---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Método da tabela. Importa dados de System.Data.DataTable para Aspose.Pdf.Table
type: docs
weight: 260
url: /pt/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Importa dados de System.Data.DataTable para Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| importedDataTable | DataTable | instância de origem de System.Data.DataTable |
| isColumnNamesImported | Boolean | especifica se os nomes das colunas serão importados como a primeira linha |
| firstFilledRow | Int32 | especifica o número baseado em zero da primeira linha na tabela de destino a partir da qual a importação começará; se a linha com esse número (e algumas linhas anteriores) estiver ausente na tabela de destino, elas serão criadas primeiro |
| firstFilledColumn | Int32 | especifica o número da primeira coluna de destino na tabela de destino; a coluna deve estar presente na tabela de destino antes do início da importação |

### Veja Também

* classe [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Importa um objeto DataTable para a tabela.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| importedDataTable | DataTable | O objeto DataTable a ser importado. |
| isColumnNamesShown | Boolean | Especifica se os nomes das colunas da tabela de dados de origem serão importados como a primeira linha. |
| firstFilledRow | Int32 | especifica o número baseado em zero da primeira linha na tabela de destino a partir da qual a importação começará; se a linha com esse número (e algumas linhas anteriores) estiver ausente na tabela de destino, elas serão criadas primeiro |
| firstFilledColumn | Byte | especifica o número da primeira coluna de destino na tabela de destino; a coluna deve estar presente na tabela de destino antes do início da importação |
| maxRows | Int32 | Quantidade máxima de linhas a serem importadas da tabela de origem. |
| maxColumns | Int32 | Quantidade máxima de colunas a serem importadas da tabela de origem. |
| isHtmlSupported | Boolean | Especifica se o texto é uma string html. |

### Veja Também

* classe [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Importa um objeto DataTable, mas não como uma entidade inteira. Apenas linhas e colunas especificadas são importadas.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| importedDataTable | DataTable | O objeto DataTable a ser importado. |
| sourceRowList | Int32[] | O array de números das linhas no objeto DataTable de origem que devem ser importadas. A lista não deve ser nula e deve conter apenas números de linhas existentes, caso contrário, uma exceção será lançada. |
| sourceColumnList | Int32[] | O array de números das colunas no objeto DataTable de origem que devem ser importadas. A lista não deve ser nula e deve conter apenas números de colunas existentes, caso contrário, uma exceção será lançada. |
| firstFilledRow | Int32 | O número da linha baseado em zero da primeira célula na tabela de destino a partir da qual a importação começará. Se a tabela de destino não contiver essa linha, ela (e todas as anteriores, se necessário) será criada |
| firstFilledColumn | Int32 | O número da coluna baseado em zero da primeira célula na tabela de destino a partir da qual a importação começará. A tabela de destino deve conter essa coluna antes que a importação comece, caso contrário, uma exceção será lançada. |
| showColumnNamesAsFirstRow | Boolean | Especifica se os nomes das colunas da tabela de dados de origem serão importados como a primeira linha. |
| isHtmlSupported | Boolean | Especifica se o texto é uma string html. |

### Veja Também

* classe [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)