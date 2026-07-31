---
title: "Classe ImageCompressionOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Optimization.ImageCompressionOptions classe. Classe che contiene le opzioni impostate per la compressione delle immagini"
type: docs
weight: 8090
url: /it/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

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
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Ottiene o imposta la codifica usata per memorizzare le immagini. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Specifica il livello di compressione dell'immagine quando viene usato il flag CompressImages. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Specifica la risoluzione massima delle immagini. Se un'immagine ha una risoluzione più alta verrà ridimensionata. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Se questo flag è impostato su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è superiore al parametro MaxResolution specificato. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. veloce (compressione migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini), 3. mista (la compressione standard viene applicata alle immagini che non possono essere compresse dall'algoritmo più veloce; questo può fornire la migliore compressione ma è più lenta rispetto all'algoritmo \"fast\". La versione \"Fast\" non è applicabile al ridimensionamento delle immagini (verrà utilizzato il metodo standard). Il valore predefinito è \"Standard\"). |

### Vedi anche

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


