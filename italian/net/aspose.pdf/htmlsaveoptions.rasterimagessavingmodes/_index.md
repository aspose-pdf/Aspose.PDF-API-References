---
title: "Enum HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. Il PDF convertito può contenere immagini raster .png, .jpeg, ecc. Questo enum definisce i metodi di gestione delle immagini raster durante la conversione da PDF a HTML."
type: docs
weight: 5850
url: /it/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Il PDF convertito può contenere immagini raster (.png, *.jpeg, ecc.) Questo enum definisce i metodi di gestione delle immagini raster durante la conversione da PDF a HTML.

```csharp
public enum RasterImagesSavingModes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | Per ogni file raster distinto verrà generata un'immagine SVG di avvolgimento, e l'immagine raster sarà incorporata come stringhe codificate Base64 in tale immagine SVG. |
| AsExternalPngFilesReferencedViaSvg | `1` | Le immagini raster distinte saranno separate come file PNG ma saranno referenziate tramite immagini SVG di avvolgimento, cioè verrà generato un file PNG e un SVG per ogni immagine raster, e ciascuno di questi SVG conterrà collegamenti al file PNG corrispondente. |
| AsEmbeddedPartsOfPngPageBackground | `2` | Verrà generato un unico grande file PNG di sfondo per ogni pagina di risultato. Le immagini raster saranno incorporate in quel file e renderizzate come regioni dell'immagine. Non verranno generati file PNG esterni per ciascuna immagine, ma sarà presente un solo file PNG per pagina nel set di file risultante dalla conversione. |
| DontSave | `3` | Non salvare le immagini per il layout fisso. |

### Vedi anche

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


