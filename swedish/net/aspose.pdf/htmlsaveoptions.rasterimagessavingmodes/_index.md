---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. Den konverterade PDF-filen kan innehålla rasterbilder.png .jpeg etc. Denna enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML
type: docs
weight: 5720
url: /sv/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Den konverterade PDF-filen kan innehålla rasterbilder(.png, *.jpeg etc.) Denna enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML

```csharp
public enum RasterImagesSavingModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | för varje distinkt rasterfil kommer en wrapper SVG-bild att genereras, och rasterbilden kommer att bäddas in som Base64-kodade strängar i den SVG-bilden |
| AsExternalPngFilesReferencedViaSvg | `1` | distinkta rasterbilder kommer att placeras som separata PNG-filer men kommer att refereras genom omslutande SVG-bilder, dvs. en PNG-fil och en SVG kommer att genereras för varje rasterbild, och varje sådan SVG kommer att innehålla länkar till relevant PNG-fil |
| AsEmbeddedPartsOfPngPageBackground | `2` | En stor PNG-bakgrundsfil kommer att genereras för varje resultat sida. Rasterbilder kommer att bäddas in i den filen och renderas som regioner av den bilden. Inga externa PNG-filer för varje bild kommer att genereras, endast en PNG-fil per sida kommer att finnas i konverteringsresultatet av filer. |
| DontSave | `3` | Spara inte bilder för Fast Layout |

### Se Även

* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)