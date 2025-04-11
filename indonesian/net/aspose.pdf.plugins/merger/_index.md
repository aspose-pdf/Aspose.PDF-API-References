---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.Merger. Mewakili plugin Penggabungan
type: docs
weight: 8940
url: /id/net/aspose.pdf.plugins/merger/
---
## Kelas Penggabungan

Mewakili plugin `Merger`.

```csharp
public sealed class Merger : IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Merger](merger/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Memulai pemrosesan `Merger` dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara menggabungkan dua dokumen PDF.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### Lihat Juga

* antarmuka [IPlugin](../iplugin/)
* ruang nama [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)