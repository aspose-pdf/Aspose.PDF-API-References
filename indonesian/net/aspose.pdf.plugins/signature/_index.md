---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.Tanda Tangan. Mewakili plugin Tanda Tangan
type: docs
weight: 9260
url: /id/net/aspose.pdf.plugins/signature/
---
## Kelas Tanda Tangan

Mewakili plugin `Tanda Tangan`.

```csharp
public sealed class Signature : IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Tanda Tangan](signature/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Proses](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Memulai pemrosesan `Tanda Tangan` dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara menandatangani dokumen PDF.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### Lihat Juga

* antarmuka [IPlugin](../iplugin/)
* ruang nama [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)