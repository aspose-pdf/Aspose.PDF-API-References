---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType. Este enum descreve possíveis medidas de antialiasing durante a conversão
type: docs
weight: 5570
url: /pt/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## Enumeração HtmlSaveOptions.AntialiasingProcessingType

Este enum descreve possíveis medidas de antialiasing durante a conversão

```csharp
public enum AntialiasingProcessingType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | sem processamento especial de antialiasing em uso. Esta é uma opção ideal para a esmagadora maioria dos documentos e não requer tempo adicional durante a conversão |
| TryCorrectResultHtml | `1` | Nesse caso, o conversor tenta detectar locais com elementos gráficos de fundo adjacentes e corrigir o HTML resultante de maneira relevante. Esta opção permite melhorar o resultado da exportação para documentos que contêm fundos construídos a partir de vários elementos gráficos adjacentes (para esse tipo de documentos, renderizadores de PDF, por exemplo, Acrobat Reader, geralmente tentam suavizar as bordas dos elementos durante a renderização. Com esta opção, o conversor imita esse comportamento dos renderizadores de PDF. Esta opção permite melhorar o layout do resultado da exportação para alguns documentos específicos (que usam esses fundos compostos), mas requer tempo adicional para processamento (geralmente cerca de 10-15% de tempo adicional). Portanto, o uso deste modo, em geral, não é recomendado. |

### Veja Também

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)