---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Security. Rappresenta il plugin di Sicurezza
type: docs
weight: 9230
url: /it/net/aspose.pdf.plugins/security/
---
## Classe Sicurezza

Rappresenta il plugin `Security`.

```csharp
public sealed class Security : IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Security](security/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Avvia l'elaborazione `Security` con i parametri specificati. |

## Esempi

L'esempio dimostra come crittografare un documento PDF.

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

L'esempio dimostra come decrittografare un documento PDF.

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

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)