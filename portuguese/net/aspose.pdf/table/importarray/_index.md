---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: Método da tabela. Importa um array unidimensional de dados para a tabela. A importação ocorre uma célula por item do array e começa a partir da linha e coluna definidas nos parâmetros. Durante a importação, se for detectado que as linhas necessárias ainda estão ausentes, ou seja, a tabela de destino é muito pequena para absorver todos os dados, as linhas necessárias serão criadas.
type: docs
weight: 250
url: /pt/net/aspose.pdf/table/importarray/
---
## Método Table.ImportArray

Importa um array unidimensional de dados para a tabela. A importação ocorre uma célula por item do array e começa a partir da linha e coluna definidas nos parâmetros. Durante a importação, se for detectado que as linhas necessárias ainda estão ausentes (ou seja, a tabela de destino é muito pequena para absorver todos os dados), as linhas necessárias serão criadas.

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| importedArray | Object[] | dados importados, nulos serão importados como strings vazias |
| firstFilledRow | Int32 | define o número da primeira linha de destino na tabela de destino a partir da qual a importação começará. Se a quantidade de linhas na tabela de destino for menor do que o necessário, as linhas ausentes serão criadas primeiro. |
| firstFilledColumn | Int32 | especifica o número da primeira coluna de destino na tabela de destino, a coluna deve estar presente na tabela de destino antes do início da importação |
| isLeftColumnsFilled | Boolean | Se 'isLeftColumnsFilled'=false, então nas segundas e em todas as linhas preenchidas subsequentes, as células que estão à esquerda da firstFilledColumn serão ignoradas |

### Veja Também

* classe [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)