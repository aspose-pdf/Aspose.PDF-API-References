---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LoadOptions. O tipo LoadOptions mantém o nível de abstração sobre opções de carregamento individuais
type: docs
weight: 6120
url: /pt/net/aspose.pdf/loadoptions/
---
## Classe LoadOptions

O tipo LoadOptions mantém o nível de abstração sobre opções de carregamento individuais

```csharp
public abstract class LoadOptions
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato de arquivo que `LoadOptions` descreve. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)