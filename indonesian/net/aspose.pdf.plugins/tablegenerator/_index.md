---
title: "Kelas TableGenerator"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.TableGenerator. Mewakili plugin Aspose.PDF TableGenerator"
type: docs
weight: 9500
url: /id/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

Mewakili plugin Aspose.PDF TableGenerator.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementasi IDisposable. Faktanya, ini tidak diperlukan untuk TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Memulai pemrosesan PdfGenerator dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara menambahkan tabel ke file PDF.

```csharp
// buat TableGenerator
var generator = new TableGenerator();
// buat objek TableOptions untuk mengatur instruksi
var opt = new TableOptions();
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


