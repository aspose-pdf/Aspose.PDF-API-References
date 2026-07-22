---
title: "Aspose::Pdf::HtmlSaveOptions::RasterImagesSavingModes enum"
linktitle: "RasterImagesSavingModes"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::RasterImagesSavingModes enum. En konverterad PDF kan innehålla rasterbilder (.png, *.jpeg etc.). Denna enum definierar sätt att hantera rasterbilder under konvertering av PDF till HTML i C++."
type: docs
weight: 5900
url: /sv/cpp/aspose.pdf/htmlsaveoptions/rasterimagessavingmodes/
---
## RasterImagesSavingModes enum


Konverterad PDF kan innehålla rasterbilder (.png, *.jpeg etc.). Denna enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML.

```cpp
enum class RasterImagesSavingModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | 0 | för varje distinkt rasterfil kommer en omslutande SVG‑bild att genereras, och rasterbilden kommer att bäddas in som Base64‑kodade strängar i den SVG‑bilden |
| AsExternalPngFilesReferencedViaSvg | 1 | distinkta rasterbilder kommer att separeras som PNG‑filer men refereras via omslutande SVG‑bilder, d.v.s. en PNG‑fil och en SVG‑fil genereras för varje rasterbild, och varje sådan SVG innehåller länkar till den motsvarande PNG‑filen |
| AsEmbeddedPartsOfPngPageBackground | 2 | En stor PNG‑bakgrundsfil kommer att genereras för varje resultatsida. Rasterbilder kommer att bäddas in i den filen och renderas som regioner i bilden. Inga externa PNG‑filer för varje bild kommer att genereras, endast en PNG‑fil per sida kommer att finnas i konverteringsresultatets filuppsättning. |
| DontSave | 3 | Spara inte bilder för Fast layout. |

## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
