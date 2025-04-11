---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.Optimizer. Mewakili plugin Optimizer
type: docs
weight: 8970
url: /id/net/aspose.pdf.plugins/optimizer/
---
## Kelas Optimizer

Mewakili plugin `Optimizer`.

```csharp
public sealed class Optimizer : IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Optimizer](optimizer/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Memulai pemrosesan `Optimizer` dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara mengoptimalkan dokumen PDF.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### Lihat Juga

* antarmuka [IPlugin](../iplugin/)
* ruang nama [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)