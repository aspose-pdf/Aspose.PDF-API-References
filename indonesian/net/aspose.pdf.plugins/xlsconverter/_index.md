---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.XlsConverter. Mewakili plugin XlsConverter
type: docs
weight: 9450
url: /id/net/aspose.pdf.plugins/xlsconverter/
---
## Kelas XlsConverter

Mewakili plugin `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementasi dari IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Memulai pemrosesan PdfToExcel dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara mengonversi PDF ke dokumen XLSX.

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
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