---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.Splitter. Mewakili plugin Splitter
type: docs
weight: 9280
url: /id/net/aspose.pdf.plugins/splitter/
---
## Kelas Splitter

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

Contoh ini menunjukkan cara membagi dokumen PDF.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### Lihat Juga

* antarmuka [IPlugin](../iplugin/)
* ruang nama [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)