---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfAOptionsBase. Obtém ou define a estratégia para remover fontes para minimizar o tamanho do arquivo de saída durante o processo de conversão para PDF/A
type: docs
weight: 30
url: /pt/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## Propriedade PdfAOptionsBase.ExcludeFontsStrategy

Obtém ou define a estratégia para remover fontes para minimizar o tamanho do arquivo de saída durante o processo de conversão para PDF/A.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Valor da Propriedade

A estratégia para remover fontes. Isso pode ser um dos valores da enumeração [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/). O padrão é a combinação de SubsetFonts e RemoveDuplicatedFonts.

## Observações

Esta propriedade permite que você controle como as fontes são tratadas durante o processo de conversão. Você pode optar por remover fontes duplicadas, remover fontes semelhantes com larguras diferentes ou subdefinir fontes.

### Veja Também

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)