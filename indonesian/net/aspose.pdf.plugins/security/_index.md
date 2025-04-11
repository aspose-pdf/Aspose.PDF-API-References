---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.Security. Mewakili plugin Keamanan
type: docs
weight: 9230
url: /id/net/aspose.pdf.plugins/security/
---
## Kelas Keamanan

Mewakili plugin `Security`.

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
// create Security 
var plugin = new Security();
// create EncryptionOptions object to set instructions
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

Contoh ini menunjukkan cara mendekripsi dokumen PDF.

```csharp
// create Security 
var plugin = new Security();
// create DecryptionOptions object to set instructions
var opt = new DecryptionOptions("123456"));
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