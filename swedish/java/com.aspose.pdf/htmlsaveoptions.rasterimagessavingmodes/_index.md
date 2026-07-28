---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF för Java API-referens"
description: "En konverterad PDF kan innehålla rasterbilder (.png, *.jpeg osv.). Denna enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML"
type: docs
weight: 2140
url: /sv/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

En konverterad PDF kan innehålla rasterbilder (.png, *.jpeg osv.). Denna enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML

## Fält

| Fält | Beskrivning |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | En stor PNG-bakgrundsfil kommer att genereras för varje resultatsida. Rasterbilder kommer att bäddas in i den filen och renderas som regioner av bilden. Inga externa PNG-filer för varje bild kommer att genereras, endast en PNG-fil per sida kommer att finnas i konverteringsresultatets filuppsättning. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | Distinkta rasterbilder kommer att placeras som separata PNG-filer men kommer att refereras via omslutande SVG-bilder, d.v.s. en PNG-fil och en SVG kommer att genereras för varje rasterbild, och varje sådan SVG kommer att innehålla länkar till den relevanta PNG-filen. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | För varje distinkt rasterfil kommer en omslutande SVG-bild att genereras, och rasterbilden kommer att bäddas in som Base64‑kodade strängar i den SVG-bilden. |
| [DontSave](#DontSave) | Spara inte bilder för Fast layout |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

En stor PNG-bakgrundsfil kommer att genereras för varje resultatsida. Rasterbilder kommer att bäddas in i den filen och renderas som regioner av bilden. Inga externa PNG-filer för varje bild kommer att genereras, endast en PNG-fil per sida kommer att finnas i konverteringsresultatets filuppsättning.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

Distinkta rasterbilder kommer att placeras som separata PNG-filer men kommer att refereras via omslutande SVG-bilder, d.v.s. en PNG-fil och en SVG kommer att genereras för varje rasterbild, och varje sådan SVG kommer att innehålla länkar till den relevanta PNG-filen.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

För varje distinkt rasterfil kommer en omslutande SVG-bild att genereras, och rasterbilden kommer att bäddas in som Base64‑kodade strängar i den SVG-bilden.

### DontSave {#DontSave}
```
public static final int DontSave
```

Spara inte bilder för Fast layout
