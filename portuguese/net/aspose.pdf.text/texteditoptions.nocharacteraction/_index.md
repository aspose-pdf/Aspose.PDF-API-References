---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. Ação a ser executada se a fonte não contiver o caractere necessário
type: docs
weight: 10860
url: /pt/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## Enumeração TextEditOptions.NoCharacterAction

Ação a ser executada se a fonte não contiver o caractere necessário

```csharp
public enum NoCharacterAction
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| ThrowException | `0` | Lançar exceção |
| UseStandardFont | `1` | Substituir fonte pela fonte padrão que contém o caractere necessário |
| ReplaceAnyway | `2` | Substituir texto de qualquer maneira sem substituição de fonte |
| ReplaceFonts | `3` | Substitui fontes conforme necessário para garantir que todos os caracteres no texto possam ser exibidos. O algoritmo de substituição de fonte segue estas etapas: 1. Se o usuário definir explicitamente a propriedade Font, verifique se a fonte especificada pode exibir os caracteres desejados. 2. Se nenhuma fonte definida pelo usuário estiver configurada, procure entre as fontes adicionadas via o [`Sources`](../fontrepository/sources/). 3. Analise o texto para identificar seu alfabeto ou escrita e sugira nomes de fontes de acordo. Tente localizar e usar essas fontes do sistema. 4. Como uma alternativa, procure no sistema qualquer fonte capaz de exibir os caracteres necessários. |
| UseCustomReplacementFont | `4` | Substituir fonte pela fonte de substituição definida |

### Veja Também

* classe [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)