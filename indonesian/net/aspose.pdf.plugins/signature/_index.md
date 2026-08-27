---
title: "Kelas Signature"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.Signature. Menyatakan plugin Signature"
type: docs
weight: 9410
url: /id/net/aspose.pdf.plugins/signature/
---
## Signature class

Menyatakan plugin `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Signature](signature/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Memulai pemrosesan `Signature` dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara menandatangani dokumen PDF.

```csharp
// buat Signature
var plugin = new Signature();
// buat objek SignOptions untuk mengatur instruksi
var opt = new SignOptions(inputPfx, inputPfxPassword);
// tambahkan jalur file input
opt.AddInput(new FileDataSource(inputPath));
// atur jalur file output
opt.AddOutput(new FileDataSource(outputPath));
// lakukan proses
plugin.Process(opt);
```

### Lihat Juga

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


