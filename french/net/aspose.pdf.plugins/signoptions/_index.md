---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.SignOptions. Représente les options de signature pour le plugin Signature
type: docs
weight: 9250
url: /fr/net/aspose.pdf.plugins/signoptions/
---
## Classe SignOptions

Représente les options de signature pour le plugin [`Signature`](../signature/).

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | Initialise une nouvelle instance de l'objet `SignOptions` avec des options par défaut. |
| [SignOptions](signoptions/#constructor_1)(string, string) | Initialise une nouvelle instance de l'objet `SignOptions` avec des options par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Ferme les flux d'entrée après la fin de l'opération. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Ferme les flux de sortie après la fin de l'opération. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | Le contact de la signature. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Renvoie la collection de données du plugin OrganizerOptions. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | L'emplacement de la signature. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | Le nom du champ de signature existant. Null pour créer un nouveau champ. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Obtient la collection des cibles ajoutées pour enregistrer les résultats de l'opération. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | Le numéro de page sur lequel la signature est faite. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | La raison de la signature. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | Le rectangle de la signature. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | La visibilité de la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin PdfOrganizer. |

### Voir aussi

* classe [OrganizerBaseOptions](../organizerbaseoptions/)
* espace de noms [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)