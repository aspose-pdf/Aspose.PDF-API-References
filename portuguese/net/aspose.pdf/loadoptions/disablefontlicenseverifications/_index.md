---
title: LoadOptions.DisableFontLicenseVerifications
second_title: Aspose.PDF for .NET API Reference
description: Propriedade LoadOptions. Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando verdadeiro, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF, mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão, falso.
type: docs
weight: 10
url: /pt/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## Propriedade LoadOptions.DisableFontLicenseVerifications

Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF, mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão, `false`.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## Observações

Tenha cuidado ao usar esta flag. Quando ela é definida, significa que a pessoa que define esta flag assume toda a responsabilidade por possíveis violações de licença/lei. Portanto, ela assume isso por seu próprio risco. É altamente recomendável usar esta flag apenas quando você estiver totalmente confiante de que não está infringindo a lei de direitos autorais.

### Veja Também

* classe [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)