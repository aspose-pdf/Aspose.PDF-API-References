---
title: "Kelas Merger"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.Merger. Mewakili plugin Merger"
type: docs
weight: 9070
url: /id/net/aspose.pdf.plugins/merger/
---
## Merger class

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
// buat Merger
var merger = new Merger();
// buat objek MergeOptions untuk mengatur instruksi
var opt = new MergeOptions();
// tambahkan jalur file input
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// atur jalur file output
opt.AddOutput(new FileDataSource(outputPath));
// lakukan proses
merger.Process(opt);
```

### Lihat Juga

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


