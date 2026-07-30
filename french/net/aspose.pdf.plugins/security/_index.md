---
title: "Classe Security"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Plugins.Security classe. Représente le plugin Security"
type: docs
weight: 9380
url: /fr/net/aspose.pdf.plugins/security/
---
## Security class

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

L'exemple montre comment chiffrer un document PDF.

```csharp
// créer Security 
var plugin = new Security();
// créer l'objet EncryptionOptions pour définir les instructions
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// ajouter le chemin du fichier d'entrée
opt.AddInput(new FileDataSource(inputPath));
// définir le chemin du fichier de sortie
opt.AddOutput(new FileDataSource(outputPath));
// exécuter le processus
plugin.Process(opt);
```

L'exemple montre comment déchiffrer un document PDF.

```csharp
// créer Security 
var plugin = new Security();
// créer l'objet DecryptionOptions pour définir les instructions
var opt = new DecryptionOptions("123456"));
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


