---
title: "PdfConverter.MergeImages"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfConverter metodo. Unisce un elenco di flussi di immagini in un unico flusso di immagine. I formati di output Png/Jpg/Tiff sono supportati; nel caso di utilizzo di un formato non supportato, il flusso di output viene codificato come Jpeg per impostazione predefinita."
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

Unisce un elenco di stream di immagini in un unico stream di immagini. Sono supportati i formati di output Png/jpg/tiff; nel caso di utilizzo di un formato non supportato, lo stream di output viene codificato come Jpeg per impostazione predefinita.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputImagesStreams | List`1 | L'elenco dei flussi di immagini da unire. |
| outputImageFormat | ImageFormat | Formato di output dell'immagine per il flusso unito. |
| mergeMode | ImageMergeMode | Modalità di unione. Utilizzata per i formati Png/Jpg. |
| horizontal | Nullable`1 | Rapporto orizzontale per impostare la larghezza della tela per il flusso di immagine di output. Utilizzato per i formati Png/Jpg solo con ImageMergeMode.Center. |
| vertical | Nullable`1 | Rapporto verticale per impostare l'altezza della tela per il flusso di immagine di output. Utilizzato per i formati Png/Jpg solo con ImageMergeMode.Center. |

### Valore di ritorno

Flusso di immagine codificato nel formato di immagine di output.

### Vedi anche

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


