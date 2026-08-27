---
title: "Kelas Html"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.Html. Mewakili plugin Html"
type: docs
weight: 8950
url: /id/net/aspose.pdf.plugins/html/
---
## Html class

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
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implementasi IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Memulai pemrosesan `Html` dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara mengonversi PDF ke dokumen HTML.

```csharp
// buat Html
var converter = new Html();
// buat objek PdfToHtmlOptions untuk mengatur tipe data output sebagai file dengan sumber daya tersemat
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// tambahkan jalur file input
opt.AddInput(new FileDataSource(inputPath));
// atur jalur file output
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

Contoh ini menunjukkan cara mengonversi HTML ke dokumen PDF.

```csharp
// buat Html
var converter = new Html();
// buat HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// tambahkan jalur file input
opt.AddInput(new FileDataSource(inputPath));
// atur jalur file output
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Lihat Juga

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


