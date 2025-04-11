---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes. ATENÇÃO A funcionalidade foi implementada, mas ainda não foi disponibilizada na API pública devido a um problema bloqueador na camada OSHARED revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos como HTML, EPUB etc. geralmente têm design flutuante, portanto, permitem ajustar o tamanho da página necessário. Mas às vezes o conteúdo especifica posições ou tamanhos horizontais que não permitem colocar o conteúdo no tamanho de página necessário. Nesse caso, podemos definir o que deve ser feito nesse caso, ou seja, quando o tamanho do conteúdo não se ajusta ao tamanho inicial da página do documento PDF resultante.
type: docs
weight: 6140
url: /pt/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## Enumeração LoadOptions.PageSizeAdjustmentModes

ATENÇÃO! A funcionalidade foi implementada, mas ainda não foi disponibilizada na API pública devido a um problema bloqueador na camada OSHARED revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos (como HTML, EPUB etc.), geralmente têm design flutuante, portanto, permitem ajustar o tamanho da página necessário. Mas às vezes o conteúdo especifica posições ou tamanhos horizontais que não permitem colocar o conteúdo no tamanho de página necessário. Nesse caso, podemos definir o que deve ser feito nesse caso (ou seja, quando o tamanho do conteúdo não se ajusta ao tamanho inicial da página do documento PDF resultante).

```csharp
public enum PageSizeAdjustmentModes
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | Neste modo, as páginas resultantes terão o tamanho de página necessário definido em LoadOptions, não importa se o conteúdo após a conversão ultrapassa os limites da página ou não. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Este modo define o seguinte comportamento: após obter o resultado da conversão e detectar que algum conteúdo foi truncado, a largura da visualização é aumentada para caber o conteúdo e a conversão é repetida. Este modo permite obter menos páginas no resultado nesse caso, mas requer renderização repetida (e, portanto, mais tempo de processamento). |

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)