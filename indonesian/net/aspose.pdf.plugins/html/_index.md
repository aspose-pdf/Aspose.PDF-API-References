---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.Html. Mewakili plugin Html
type: docs
weight: 8820
url: /id/net/aspose.pdf.plugins/html/
---
## Kelas Html

Mewakili plugin `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Html](html/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implementasi dari IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Memulai pemrosesan `Html` dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara mengonversi PDF menjadi dokumen HTML.

```csharp
// create Html
var converter = new Html();
// create PdfToHtmlOptions object to set output data type as file with embedded resources
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

Contoh ini menunjukkan cara mengonversi HTML menjadi dokumen PDF.

```csharp
// create Html
var converter = new Html();
// create HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Lihat Juga

* antarmuka [IPlugin](../iplugin/)
* ruang nama [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)