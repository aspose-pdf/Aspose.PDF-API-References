---
title: ImageCompressionOptions.Version
second_title: Aspose.PDF for .NET API Reference
description: Proprietà ImageCompressionOptions. Versione dell'algoritmo di compressione. I valori possibili sono 1. compressione standard 2. compressione veloce migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini 3. compressione standard mista applicata a immagini che non possono essere compresse dall'algoritmo più veloce, questo può dare la migliore compressione ma è più lento dell'algoritmo "veloce". La versione "Veloce" non è applicabile per il ridimensionamento delle immagini. Predefinito è "Standard".
type: docs
weight: 70
url: /it/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## Proprietà ImageCompressionOptions.Version

Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. veloce (compressione migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini), 3. mista (la compressione standard è applicata a immagini che non possono essere compresse dall'algoritmo più veloce, questo può dare la migliore compressione ma è più lento dell'algoritmo "veloce". La versione "Veloce" non è applicabile per il ridimensionamento delle immagini (verrà utilizzato il metodo standard). Predefinito è "Standard".

```csharp
public ImageCompressionVersion Version { get; set; }
```

### Vedi Anche

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)