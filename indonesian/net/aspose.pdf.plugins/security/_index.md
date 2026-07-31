---
title: "Kelas Security"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.Security. Menyatakan plugin Security"
type: docs
weight: 9380
url: /id/net/aspose.pdf.plugins/security/
---
## Security class

Menyatakan plugin `Security`.

```csharp
public sealed class Security : IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Security](security/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Memulai pemrosesan `Security` dengan parameter yang ditentukan. |

## Contoh

Contoh ini menunjukkan cara mengenkripsi dokumen PDF.

```csharp
// buat Security 
var plugin = new Security();
// buat objek EncryptionOptions untuk mengatur instruksi
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// tambahkan jalur file input
opt.AddInput(new FileDataSource(inputPath));
// atur jalur file output
opt.AddOutput(new FileDataSource(outputPath));
// lakukan proses
plugin.Process(opt);
```

Contoh ini menunjukkan cara mendekripsi dokumen PDF.

```csharp
// buat Security 
var plugin = new Security();
// buat objek DecryptionOptions untuk mengatur instruksi
var opt = new DecryptionOptions("123456"));
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


