---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.TableGenerator. Mewakili plugin TableGenerator Aspose.PDF
type: docs
weight: 9350
url: /id/net/aspose.pdf.plugins/tablegenerator/
---
## Kelas TableGenerator

Mewakili plugin TableGenerator Aspose.PDF.

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
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementasi dari IDisposable. Sebenarnya, tidak diperlukan untuk TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Memulai pemrosesan PdfGenerator dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara menambahkan tabel ke file PDF.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
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
* ruang nama [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)