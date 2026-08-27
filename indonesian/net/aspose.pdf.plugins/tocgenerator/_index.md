---
title: "Kelas TocGenerator"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.TocGenerator. Mewakili plugin Aspose.PDF TocGenerator"
type: docs
weight: 9580
url: /id/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Mewakili plugin Aspose.PDF TocGenerator.

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
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementasi IDisposable. Pada kenyataannya, tidak diperlukan untuk TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Memulai pemrosesan PdfGenerator dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara menambahkan TOC ke file PDF.

```csharp
// buat TocGenerator
var generator = new TocGenerator();
// buat objek TocOptions untuk mengatur instruksi
var opt = new TocOptions();
// tambahkan jalur file input
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// atur jalur file output
opt.AddOutput(new FileDataSource(outputPath));
// lakukan proses ekstraksi
generator.Process(opt);
```

### Lihat Juga

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


