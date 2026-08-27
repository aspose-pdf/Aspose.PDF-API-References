---
title: "Kelas XlsConverter"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.XlsConverter. Mewakili plugin XlsConverter"
type: docs
weight: 9600
url: /id/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

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
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementasi IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Memulai pemrosesan PdfToExcel dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara mengonversi PDF ke dokumen XLSX.

```csharp
// buat konverter XlsConverter
var converter = new XlsConverter();
// buat PdfToXLSOptions
var opt = new PdfToXLSOptions();
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


