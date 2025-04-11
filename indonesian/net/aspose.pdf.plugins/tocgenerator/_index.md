---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.TocGenerator. Mewakili plugin TocGenerator Aspose.PDF
type: docs
weight: 9430
url: /id/net/aspose.pdf.plugins/tocgenerator/
---
## Kelas TocGenerator

Mewakili plugin TocGenerator Aspose.PDF.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementasi dari IDisposable. Sebenarnya, tidak diperlukan untuk TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Memulai pemrosesan PdfGenerator dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara menambahkan TOC ke file PDF.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### Lihat Juga

* antarmuka [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)