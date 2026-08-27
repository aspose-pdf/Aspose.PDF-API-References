---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Referência da API Aspose.PDF para Java"
description: "ATENÇÃO! O recurso foi implementado, mas ainda não foi colocado na API pública, pois um problema bloqueador na camada OSHARED foi revelado para o documento de exemplo. Representa o modo de uso do tamanho da página."
type: docs
weight: 2810
url: /pt/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

ATTENTION! A funcionalidade foi implementada, mas ainda não foi disponibilizada na API pública devido a um problema bloqueador na camada OSHARED revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos (como HTML, EPUB etc.) geralmente têm design fluido, portanto permitem ajustar o tamanho da página necessário. Mas às vezes o conteúdo especifica posições horizontais ou tamanho que não permitem colocar o conteúdo no tamanho de página requerido. Nesse caso podemos definir o que deve ser feito (por exemplo, quando o tamanho do conteúdo não cabe no tamanho de página inicial requerido do documento PDF resultante).

## Campos

| Campo | Descrição |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Este modo define esse comportamento: após obter o resultado da conversão e detectar o fato de que algum conteúdo foi truncado, a largura da visualização é ampliada para acomodar o conteúdo e a conversão é repetida. Este modo permite obter menos páginas no resultado nesse caso, mas requer renderização repetida (e, portanto, mais tempo de processamento). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | Neste modo, as páginas resultantes terão o tamanho de página requerido definido em LoadOptions, independentemente de o conteúdo após a conversão ultrapassar os limites da página ou não. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Este modo define esse comportamento: após obter o resultado da conversão e detectar o fato de que algum conteúdo foi truncado, a largura da visualização é ampliada para acomodar o conteúdo e a conversão é repetida. Este modo permite obter menos páginas no resultado nesse caso, mas requer renderização repetida (e, portanto, mais tempo de processamento).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

Neste modo, as páginas resultantes terão o tamanho de página requerido definido em LoadOptions, independentemente de o conteúdo após a conversão ultrapassar os limites da página ou não.
