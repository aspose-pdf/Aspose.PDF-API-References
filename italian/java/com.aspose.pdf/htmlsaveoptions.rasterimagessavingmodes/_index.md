---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il PDF convertito può contenere immagini raster (.png, *.jpeg ecc.). Questo enum definisce i metodi di gestione delle immagini raster durante la conversione da PDF a HTML"
type: docs
weight: 2140
url: /it/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

Il PDF convertito può contenere immagini raster (.png, *.jpeg ecc.). Questo enum definisce i metodi di gestione delle immagini raster durante la conversione da PDF a HTML

## Campi

| Campo | Descrizione |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Verrà generato un unico grande file PNG di sfondo per ogni pagina di risultato. Le immagini raster saranno incorporate in quel file e renderizzate come regioni di quell'immagine. Non verranno generate file PNG esterni per ciascuna immagine, ma sarà presente un solo file PNG per pagina nel set di risultati della conversione. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | Le immagini raster distinte saranno separate come file PNG ma saranno referenziate tramite immagini SVG di avvolgimento, cioè verrà generato un file PNG e un file SVG per ciascuna immagine raster, e ciascuno di questi SVG conterrà collegamenti al relativo file PNG. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | Per ogni file raster distinto verrà generato un'immagine SVG di avvolgimento, e l'immagine raster sarà incorporata come stringhe codificate Base64 in quel SVG. |
| [DontSave](#DontSave) | Non salvare le immagini per il layout fisso. |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

Verrà generato un unico grande file PNG di sfondo per ogni pagina di risultato. Le immagini raster saranno incorporate in quel file e renderizzate come regioni di quell'immagine. Non verranno generate file PNG esterni per ciascuna immagine, ma sarà presente un solo file PNG per pagina nel set di risultati della conversione.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

Le immagini raster distinte saranno separate come file PNG ma saranno referenziate tramite immagini SVG di avvolgimento, cioè verrà generato un file PNG e un file SVG per ciascuna immagine raster, e ciascuno di questi SVG conterrà collegamenti al relativo file PNG.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

Per ogni file raster distinto verrà generato un'immagine SVG di avvolgimento, e l'immagine raster sarà incorporata come stringhe codificate Base64 in quel SVG.

### DontSave {#DontSave}
```
public static final int DontSave
```

Non salvare le immagini per il layout fisso.
