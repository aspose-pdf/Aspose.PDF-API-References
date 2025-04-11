---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileSanitization. Représente l'API de désinfection et de récupération. Utilisez-la si vous ne pouvez pas créer/ouvrir des documents d'une autre manière
type: docs
weight: 4540
url: /fr/net/aspose.pdf.facades/pdffilesanitization/
---
## Classe PdfFileSanitization

Représente l'API de désinfection et de récupération. Utilisez-la si vous ne pouvez pas créer/ouvrir des documents d'une autre manière.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient le document sur lequel la façade travaille. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Après que le fichier a été enregistré, vous pouvez vérifier ce qui a été fait avec le fichier. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Permet de générer un nouveau xref et un nouveau trailer pour le document. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Permet de supprimer les données après les données PDF. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Permet de supprimer les données avant les données PDF. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Lie un flux Pdf pour désinfecter. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Lie un fichier Pdf pour désinfecter. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Ferme la façade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose de la façade. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Supprime l'ancien xref avec trailer et crée un nouveau xref avec trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Récupère le document. Utilisez les propriétés pour personnaliser. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Enregistre le PDF résultant dans le flux. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Enregistre le PDF résultant dans un fichier. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Supprime les données après le dernier %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Supprime les données avant %PDF. |

### Voir aussi

* classe [SaveableFacade](../saveablefacade/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)