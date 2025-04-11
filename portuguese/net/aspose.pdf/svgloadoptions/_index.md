---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SvgLoadOptions. Representa opções para carregar/importar arquivo SVG em documento PDF
type: docs
weight: 10210
url: /pt/net/aspose.pdf/svgloadoptions/
---
## Classe SvgLoadOptions

Representa opções para carregar/importar arquivo SVG em documento PDF.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Ajusta o tamanho da página PDF ao tamanho SVG |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato do arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Obtém ou define as informações da página que devem ser aplicadas durante o carregamento do documento. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Permite selecionar o mecanismo de conversão que será utilizado durante a conversão. Atualmente, o novo mecanismo está na fase de testes B, então este valor por padrão é definido como ConversionEngines.LegacyEngine |

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)