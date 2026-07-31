---
title: "Classe Security"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.Security. Rappresenta il plugin Security"
type: docs
weight: 9380
url: /it/net/aspose.pdf.plugins/security/
---
## Security class

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
// crea Security
var plugin = new Security();
// crea oggetto EncryptionOptions per impostare le istruzioni
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// aggiungi percorso del file di input
opt.AddInput(new FileDataSource(inputPath));
// imposta il percorso del file di output
opt.AddOutput(new FileDataSource(outputPath));
// esegui il processo
plugin.Process(opt);
```

L'esempio dimostra come decrittografare un documento PDF.

```csharp
// crea Security
var plugin = new Security();
// crea oggetto DecryptionOptions per impostare le istruzioni
var opt = new DecryptionOptions("123456"));
// aggiungi percorso del file di input
opt.AddInput(new FileDataSource(inputPath));
// imposta il percorso del file di output
opt.AddOutput(new FileDataSource(outputPath));
// esegui il processo
plugin.Process(opt);
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


