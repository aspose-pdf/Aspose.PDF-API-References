---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfConverter. Unisce un elenco di flussi di immagini in un unico flusso di immagini. I formati di output Png/jpg/tiff sono supportati nel caso di utilizzo di un flusso di output in formato non supportato codificato come Jpeg per impostazione predefinita
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## Metodo PdfConverter.MergeImages

Unisce un elenco di flussi di immagini in un unico flusso di immagini. I formati di output Png/jpg/tiff sono supportati, nel caso di utilizzo di un flusso di output in formato non supportato codificato come Jpeg per impostazione predefinita.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputImagesStreams | List`1 | L'elenco dei flussi di immagini da unire. |
| outputImageFormat | ImageFormat | Formato di output dell'immagine per il flusso unito. |
| mergeMode | ImageMergeMode | Modalità di unione. Utilizzata per i formati Png/Jpg. |
| horizontal | Nullable`1 | Rapporto orizzontale per impostare la larghezza della tela per il flusso di output dell'immagine. Utilizzata solo per i formati Png/Jpg con ImageMergeMode.Center. |
| vertical | Nullable`1 | Rapporto verticale per impostare l'altezza della tela per il flusso di output dell'immagine. Utilizzata solo per i formati Png/Jpg con ImageMergeMode.Center. |

### Valore di Ritorno

Flusso di immagini codificato come formato di output dell'immagine.

### Vedi Anche

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)