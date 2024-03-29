---
title: HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF för .NET API Referens
description: Konverterad PDF kan innehålla rasterbilder .png .jpeg etc. Denna uppräkning definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML
type: docs
weight: 3590
url: /sv/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Konverterad PDF kan innehålla rasterbilder (.png, *.jpeg etc.) Denna uppräkning definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML

```csharp
public enum RasterImagesSavingModes
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | för varje distinkt rasterfil kommer att genereras omslags-SVG-bild, och rasterbild kommer att bäddas in som Base64-kodade strängar i den SVG-bilden |
| AsExternalPngFilesReferencedViaSvg | `1` | distinkta rasterbilder kommer att sättas isär som PNG-filer men kommer att refereras genom svepande SVG-bilder, dvs kommer att genereras en PNG-fil och en SVG för varje rasterbild, och varje sådan SVG kommer att innehålla länkar till relevant PNG-fil |
| AsEmbeddedPartsOfPngPageBackground | `2` | Kommer att genereras en stor PNG-bakgrundsfil för varje resultatsida. Rasterbilder kommer att bäddas in i den filen och renderas som regioner av den bilden. Inga externa PNG-filer för varje bild kommer att genereras, endast en PNG-fil per sida kommer att finnas i konverteringsresultatuppsättningen filer. |

### Se även

* class [HtmlSaveOptions](../htmlsaveoptions)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
