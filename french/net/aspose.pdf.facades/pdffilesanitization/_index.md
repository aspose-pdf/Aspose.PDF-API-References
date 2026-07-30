---
title: "Classe PdfFileSanitization"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Facades.PdfFileSanitization classe. Représente l'API de désinfection et de récupération. Utilisez‑la si vous ne pouvez pas créer/ouvrir des documents d'une autre manière."
type: docs
weight: 4660
url: /fr/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur laquelle travaille. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Après que le fichier a été enregistré, vous pouvez vérifier ce qui a été fait avec le fichier. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Permet de générer un nouveau xref et un nouveau trailer pour le document. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Permet de supprimer les données après les données pdf |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Permet de supprimer les données avant les données pdf. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Lie un flux Pdf pour Sanitize. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Lie un fichier Pdf pour Sanitize. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Ferme la façade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libère la façade. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Supprime l'ancien xref avec trailer et crée un nouveau xref avec trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Récupère le document. Utilisez les propriétés pour le personnaliser. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Enregistre le PDF résultant dans le flux. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Enregistre le PDF résultant dans le fichier. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Supprime les données après le dernier %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Supprime les données avant %PDF. |

### Voir aussi

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


