---
title: "Classe OcrDetail"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.OcrDetail classe. Représente le résultat OCR d’une seule page d’un document ou d’un fichier image unique."
type: docs
weight: 860
url: /fr/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Représente le résultat OCR d'une seule page d'un document ou d'un seul fichier image.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OcrDetail](ocrdetail/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Un message d’erreur décrivant pourquoi l’OCR a échoué pour cette page, si Success est false. Null sinon. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | Le contenu texte extrait de la page. Null si Success est false ou aucun texte n’a été trouvé. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | Le numéro de page basé sur 1 dans le document source. Pour les images à page unique, ce sera toujours 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Indique si l’extraction OCR pour cette page spécifique a réussi. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Obtient ou définit les statistiques d’utilisation. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Compare l’instance OcrDetail actuelle avec un autre objet OcrDetail en fonction de leur propriété PageNumber. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


