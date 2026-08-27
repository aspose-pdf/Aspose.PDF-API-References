---
title: "Kelas Optimizer"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.Optimizer. Mewakili plugin Optimizer"
type: docs
weight: 9120
url: /id/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

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
// buat Optimizer
var optimizer = new Optimizer();
// buat objek OptimizeOptions untuk mengatur instruksi
var opt = new OptimizeOptions();
// tambahkan jalur file input
opt.AddInput(new FileDataSource(inputPath));
// atur jalur file output
opt.AddOutput(new FileDataSource(outputPath));
// lakukan proses
optimizer.Process(opt);
```

### Lihat Juga

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


