---
title: HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF per .NET API Reference
description: Il PDF convertito può contenere immagini raster .png .jpeg ecc. Questo enum definisce i metodi di gestione delle immagini raster durante la conversione di PDF in HTML
type: docs
weight: 3590
url: /it/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Il PDF convertito può contenere immagini raster (.png, *.jpeg ecc.) Questo enum definisce i metodi di gestione delle immagini raster durante la conversione di PDF in HTML

```csharp
public enum RasterImagesSavingModes
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | per ogni file raster distinto verrà generata un'immagine SVG wrapper, e l'immagine raster verrà incorporata come stringhe codificate Base64 in quell'immagine SVG |
| AsExternalPngFilesReferencedViaSvg | `1` | immagini raster distinte verranno messe a parte come file PNG ma verrà fatto riferimento tramite il wrapping di immagini SVG, ovvero verranno generati un file PNG e un SVG per ciascuna immagine raster, e ciascuno di tali SVG conterrà collegamenti al file PNG pertinente |
| AsEmbeddedPartsOfPngPageBackground | `2` | Verrà generato un grande file di sfondo PNG per ogni pagina dei risultati. Le immagini raster verranno incorporate in quel file e renderizzate come regioni di quell'immagine. Non verranno generati file PNG esterni per ciascuna immagine, solo un file PNG per pagina sarà presente nel set di risultati di conversione dei file. |

### Guarda anche

* class [HtmlSaveOptions](../htmlsaveoptions)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
