---
title: ImageCompressionOptions.Version
second_title: Aspose.PDF for .NET API Reference
description: Propriedade ImageCompressionOptions. Versão do algoritmo de compressão. Os valores possíveis são 1. compressão padrão 2. compressão rápida melhorada que é mais rápida que a padrão, mas pode não ser aplicável a todas as imagens 3. compressão mista a compressão padrão é aplicada a imagens que não podem ser comprimidas pelo algoritmo mais rápido, isso pode oferecer a melhor compressão, mas é mais lenta que o algoritmo "rápido". A versão "Rápida" não é aplicável para redimensionar imagens. O padrão é "Padrão".
type: docs
weight: 70
url: /pt/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## Propriedade ImageCompressionOptions.Version

Versão do algoritmo de compressão. Os valores possíveis são: 1. compressão padrão, 2. rápida (compressão melhorada que é mais rápida que a padrão, mas pode não ser aplicável a todas as imagens), 3. mista (a compressão padrão é aplicada a imagens que não podem ser comprimidas pelo algoritmo mais rápido, isso pode oferecer a melhor compressão, mas é mais lenta que o algoritmo "rápido". A versão "Rápida" não é aplicável para redimensionar imagens (o método padrão será utilizado). O padrão é "Padrão".

```csharp
public ImageCompressionVersion Version { get; set; }
```

### Veja Também

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)