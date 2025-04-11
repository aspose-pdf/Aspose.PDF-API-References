---
title: Class CdrLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.CdrLoadOptions. A classe descreve opções de carregamento de CDR
type: docs
weight: 2960
url: /pt/net/aspose.pdf/cdrloadoptions/
---
## Classe CdrLoadOptions

A classe descreve opções de carregamento de CDR.

```csharp
public class CdrLoadOptions : LoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [CdrLoadOptions](cdrloadoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desativar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desativem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato do arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)