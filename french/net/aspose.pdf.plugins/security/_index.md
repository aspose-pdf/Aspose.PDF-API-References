---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Security. Représente le plugin de sécurité
type: docs
weight: 9230
url: /fr/net/aspose.pdf.plugins/security/
---
## Classe Sécurité

Représente le plugin `Security`.

```csharp
public sealed class Security : IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Security](security/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Démarre le traitement `Security` avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment chiffrer un document PDF.

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

L'exemple démontre comment déchiffrer un document PDF.

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

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)