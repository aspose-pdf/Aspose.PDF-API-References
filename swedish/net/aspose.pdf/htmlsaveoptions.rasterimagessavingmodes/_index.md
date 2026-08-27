---
title: "Enum HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. Konverterad PDF kan innehålla rasterbilder.png .jpeg etc. Detta enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML"
type: docs
weight: 5850
url: /sv/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Konverterad PDF kan innehålla rasterbilder(.png, *.jpeg etc.) Detta enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML

```csharp
public enum RasterImagesSavingModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | för varje distinkt rasterfil kommer en omslutande SVG-bild att genereras, och rasterbilden kommer att bäddas in som Base64-kodade strängar i den SVG-bilden |
| AsExternalPngFilesReferencedViaSvg | `1` | distinkta rasterbilder kommer att separeras som PNG-filer men kommer att refereras via omslutande SVG-bilder, d.v.s. en PNG-fil och en SVG kommer att genereras för varje rasterbild, och varje sådan SVG kommer att innehålla länkar till relevant PNG-fil |
| AsEmbeddedPartsOfPngPageBackground | `2` | En stor PNG-bakgrundsfil kommer att genereras för varje resultatsida. Rasterbilder kommer att bäddas in i den filen och renderas som regioner av bilden. Inga externa PNG-filer för varje bild kommer att genereras, endast en PNG-fil per sida kommer att finnas i konverteringsresultatets filuppsättning. |
| DontSave | `3` | Spara inte bilder för Fixed Layout |

### Se även

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


