---
title: "Classe Signature"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.Signature. Rappresenta il plugin Signature"
type: docs
weight: 9410
url: /it/net/aspose.pdf.plugins/signature/
---
## Signature class

Rappresenta il plugin `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Signature](signature/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Avvia l'elaborazione `Signature` con i parametri specificati. |

## Esempi

L'esempio dimostra come firmare un documento PDF.

```csharp
// crea Signature
var plugin = new Signature();
// crea oggetto SignOptions per impostare le istruzioni
var opt = new SignOptions(inputPfx, inputPfxPassword);
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


