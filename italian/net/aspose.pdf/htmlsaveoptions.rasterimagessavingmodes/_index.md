---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. Il PDF convertito può contenere immagini raster .png .jpeg ecc. Questo enum definisce i metodi di come le immagini raster possono essere gestite durante la conversione da PDF a HTML
type: docs
weight: 5720
url: /it/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## Enumerazione HtmlSaveOptions.RasterImagesSavingModes

Il PDF convertito può contenere immagini raster (.png, *.jpeg ecc.) Questo enum definisce i metodi di come le immagini raster possono essere gestite durante la conversione da PDF a HTML

```csharp
public enum RasterImagesSavingModes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | per ogni file raster distinto verrà generata un'immagine SVG wrapper, e l'immagine raster sarà incorporata come stringhe codificate in Base64 in quell'immagine SVG |
| AsExternalPngFilesReferencedViaSvg | `1` | le immagini raster distinte saranno messe a parte come file PNG ma saranno referenziate tramite immagini SVG di wrapping, cioè verrà generato un file PNG e un SVG per ogni immagine raster, e ciascuno di questi SVG conterrà collegamenti al file PNG pertinente |
| AsEmbeddedPartsOfPngPageBackground | `2` | Verrà generato un grande file di sfondo PNG per ogni pagina di risultato. Le immagini raster saranno incorporate in quel file e renderizzate come regioni di quell'immagine. Non verranno generati file PNG esterni per ogni immagine, solo un file PNG per pagina sarà presente nel set di file risultanti dalla conversione. |
| DontSave | `3` | Non salvare immagini per Layout Fisso |

### Vedi Anche

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)