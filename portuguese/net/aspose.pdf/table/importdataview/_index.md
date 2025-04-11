---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Método da tabela. Importa os dados de um objeto DataView para a tabela
type: docs
weight: 270
url: /pt/net/aspose.pdf/table/importdataview/
---
## Método Table.ImportDataView

Importa os dados de um objeto DataView para a tabela.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceDataView | DataView | O objeto DataView a ser importado. |
| isColumnNamesImported | Boolean | Indica se os nomes das colunas serão importados como a primeira linha. |
| firstFilledRow | Int32 | O número da linha baseado em zero da primeira célula na tabela de destino a partir da qual a importação começará. Se a tabela de destino não contiver essa linha, ela (e todas as anteriores, se necessário) será criada. |
| firstFilledColumn | Int32 | O número da coluna baseado em zero da primeira célula na tabela de destino a partir da qual a importação começará. A tabela de destino deve conter essa coluna antes que a importação comece, caso contrário, uma exceção será lançada. |
| maxRows | Int32 | Quantidade máxima de linhas a serem importadas do DataView de origem. |
| maxColumns | Int32 | Máximas colunas a serem importadas do DataView de origem. |

### Veja Também

* classe [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)