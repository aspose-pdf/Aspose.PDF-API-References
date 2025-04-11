---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.ImageCompressionOptions class. Class contains set options for image compression
type: docs
weight: 7950
url: /it/net/aspose.pdf.optimization/imagecompressionoptions/
---
## Classe ImageCompressionOptions

La classe contiene un insieme di opzioni per la compressione delle immagini.

```csharp
public class ImageCompressionOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Se questo flag è impostato su true, le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Ottiene o imposta la codifica utilizzata per memorizzare le immagini. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Specifica il livello di compressione delle immagini quando viene utilizzato il flag CompressImages. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione superiore, verrà ridimensionata. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Se questo flag è impostato su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è maggiore del parametro MaxResolution specificato. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. veloce (compressione migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini), 3. mista (la compressione standard è applicata alle immagini che non possono essere compresse dall'algoritmo più veloce, questo può dare la migliore compressione ma è più lento dell'algoritmo "veloce". La versione "Veloce" non è applicabile per il ridimensionamento delle immagini (verrà utilizzato il metodo standard). Il predefinito è "Standard". |

### Vedi Anche

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)