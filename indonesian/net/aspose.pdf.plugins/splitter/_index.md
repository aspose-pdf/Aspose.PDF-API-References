---
title: "Kelas Splitter"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Plugins.Splitter class. Mewakili plugin Splitter"
type: docs
weight: 9430
url: /id/net/aspose.pdf.plugins/splitter/
---
## Splitter class

Mewakili plugin `Splitter`.

```csharp
public class Splitter : IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Splitter](splitter/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Memulai pemrosesan `Splitter` dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara memecah dokumen PDF.

```csharp
// buat Splitter
var splitter = new Splitter();
// buat objek SplitOptions untuk mengatur instruksi
var opt = new SplitOptions();
// tambahkan jalur file input
opt.AddInput(new FileDataSource(inputPath));
// atur jalur file output
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// lakukan proses
splitter.Process(opt);
```

### Lihat Juga

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


