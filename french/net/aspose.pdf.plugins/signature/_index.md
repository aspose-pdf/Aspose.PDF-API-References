---
title: "Classe Signature"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.Signature. Représente le plugin Signature"
type: docs
weight: 9410
url: /fr/net/aspose.pdf.plugins/signature/
---
## Signature class

Représente le plugin `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Signature](signature/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Démarre le traitement `Signature` avec les paramètres spécifiés. |

## Exemples

L'exemple montre comment signer un document PDF.

```csharp
// créer Signature
var plugin = new Signature();
// créer SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// ajouter le chemin du fichier d'entrée
opt.AddInput(new FileDataSource(inputPath));
// définir le chemin du fichier de sortie
opt.AddOutput(new FileDataSource(outputPath));
// exécuter le processus
plugin.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


