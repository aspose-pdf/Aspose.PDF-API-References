---
title: ImageCompressionOptions
second_title: Aspose.PDF per .NET API Reference
description: La classe contiene le opzioni impostate per la compressione dellimmagine.
type: docs
weight: 5710
url: /it/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

La classe contiene le opzioni impostate per la compressione dell'immagine.

```csharp
public class ImageCompressionOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages) { get; set; } | Se questo flag è impostato su true, le immagini verranno compresse nel documento. il livello di compressione è specificato con la proprietà ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding) { get; set; } | Ottiene o imposta la codifica utilizzata per archiviare le immagini. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality) { get; set; } | Specifica il livello di compressione dell'immagine quando viene utilizzato il flag CompressIamges. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution) { get; set; } | Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione maggiore, verrà ridimensionata |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages) { get; set; } | Se questo flag è impostato su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è maggiore del parametro MaxResolution specificato. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version) { get; set; } | Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. veloce (compressione migliorata che è più veloce dello standard ma potrebbe non essere applicabile a tutte le immagini), 3. mista (la compressione standard viene applicata alle immagini che non possono essere compresse da un algoritmo più veloce, questo può fornire la migliore compressione ma è più lento dell'algoritmo "fast". La versione "Fast" non è applicabile per il ridimensionamento delle immagini (verrà utilizzato il metodo standard). L'impostazione predefinita è "Standard". |

### Guarda anche

* spazio dei nomi [Aspose.Pdf.Optimization](../../aspose.pdf.optimization)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
