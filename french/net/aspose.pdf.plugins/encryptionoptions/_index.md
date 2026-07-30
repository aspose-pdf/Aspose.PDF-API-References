---
title: "Classe EncryptionOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.EncryptionOptions. Représente les options de chiffrement pour le plugin Security"
type: docs
weight: 8670
url: /fr/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions class

Représente les options de chiffrement pour le plugin [`Security`](../security/).

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Initialise une nouvelle instance de l'objet `EncryptionOptions` avec les options par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Fermez les flux d'entrée après la fin de l'opération. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Fermez les flux de sortie après la fin de l'opération. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Algorithme cryptographique, voir [`CryptoAlgorithm`](./cryptoalgorithm/) pour plus de détails. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Autorisations du document, voir [`Permissions`](../../aspose.pdf/permissions/) pour plus de détails. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Renvoie la collection de données du plugin OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Obtient la collection des cibles ajoutées pour enregistrer les résultats de l'opération. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Mot de passe du propriétaire. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Mot de passe de l'utilisateur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin PdfOrganizer. |

### Voir aussi

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


