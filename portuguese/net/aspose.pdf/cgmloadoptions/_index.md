---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.CgmLoadOptions. Contém opções para carregar/importar arquivo CGM em documento pdf
type: docs
weight: 3010
url: /pt/net/aspose.pdf/cgmloadoptions/
---
## Classe CgmLoadOptions

Contém opções para carregar/importar arquivo CGM em documento pdf.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Cria opções de carregamento padrão para converter arquivo CGM em documento pdf. Tamanho padrão da página pdf - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Cria opções de carregamento com !:pageSize definido. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato de arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Obtém ou define o tamanho da página de saída para importação. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)