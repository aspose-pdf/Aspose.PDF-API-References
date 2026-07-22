---
title: "System::Drawing::Imaging::PixelFormat enum"
linktitle: "PixelFormat"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::PixelFormat enum. Anger färgdatatypen för en pixel i C++."
type: docs
weight: 2600
url: /sv/cpp/system.drawing.imaging/pixelformat/
---
## PixelFormat enum


Anger färgdataformatet för en pixel.

```cpp
enum class PixelFormat
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Indexed | 65536 | Anger att pixeldata innehåller färgindexerade värden, vilket betyder att de är ett index till färger i systemets färgtabell. |
| Gdi | 131072 | Anger att pixeldata innehåller GDI-färger. |
| Alpha | 262144 | Anger att pixeldata innehåller alfavärden som inte är förmultiplicerade. |
| PAlpha | 524288 | Anger att pixeldata innehåller förmultiplicerade alfavärden. |
| Utökad | 1048576 | Reserverad. |
| Kanonisk | 2097152 | Anger pixelformatet på 32 bitar per pixel med 24-bitars färgdjup och en 8-bitars alfakanal. |
| Odefinierad | 0 | Anger att pixelformatet är odefinierat. |
| DontCare | 0 | Pixelformatet är inte specificerat. |
| Format1bppIndexed | n/a | Anger att pixelformatet är 1 bit per pixel med indexerad färg. |
| Format4bppIndexed | n/a | Anger att pixelformatet är 4 bitar per pixel med indexerad färg. |
| Format8bppIndexed | n/a | Anger att pixelformatet är 8 bitar per pixel med indexerad färg. |
| Format16bppGrayScale | n/a | Anger att pixelformatet är 16 bitar per pixel. Färginformationen specificerar 65536 nyanser av grått. |
| Format16bppRgb555 | n/a | Anger att pixelformatet är 16 bitar per pixel med 5 bitar för varje röd, grön och blå komponent och den återstående biten används inte. |
| Format16bppRgb565 | n/a | Anger att pixelformatet är 16 bitar per pixel med 5 bitar för röd, 6 bitar för grön och 5 bitar för blå komponenter. |
| Format16bppArgb1555 | n/a | Anger att pixelformatet är 16 bitar per pixel med 5 bitar för varje röd, grön och blå komponent samt 1 bit för alfa. |
| Format24bppRgb | n/a | Anger att pixelformatet är 24 bitar per pixel med 8 bitar för varje röd, grön och blå komponent. |
| Format32bppRgb | n/a | Anger att pixelformatet är 32 bitar per pixel med 8 bitar för varje röd, grön och blå komponent och de återstående 8 bitarna används inte. |
| Format32bppArgb | n/a | Anger att pixelformatet är 32 bitar per pixel med 8 bitar för varje av röd, grön och blå komponenter samt 8 bitar för alfa. |
| Format32bppPArgb | n/a | Anger att pixelformatet är 32 bitar per pixel med 8 bitar för varje av röd, grön och blå komponenter samt 8 bitar för alfa. De röda, gröna och blå komponenterna är förmultiplikerade enligt alfa‑komponentens värde. |
| Format48bppRgb | n/a | Anger att pixelformatet är 48 bitar per pixel med 16 bitar för varje av röd, grön och blå komponenter. |
| Format64bppArgb | n/a | Anger att pixelformatet är 64 bitar per pixel med 16 bitar för varje av röd, grön och blå komponenter samt 16 bitar för alfa. |
| Format64bppPArgb | n/a | Anger att pixelformatet är 64 bitar per pixel med 16 bitar för varje av röd, grön och blå komponenter samt 16 bitar för alfa. De röda, gröna och blå komponenterna är förmultiplikerade enligt alfa‑komponentens värde. |
| Format32bppCMYK | n/a | Anger att pixelformatet är 32 bitar per pixel med 8 bitar för varje av cyan, magenta, gul och nyckelkomponenterna. |
| Max | 16 | Det maximala värdet för den här uppräkningen. |

## Se även

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
