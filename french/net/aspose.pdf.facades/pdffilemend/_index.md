---
title: "Classe PdfFileMend"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Facades.PdfFileMend class. Représente une classe permettant d'ajouter du texte et des images sur les pages d'un document PDF existant"
type: docs
weight: 4650
url: /fr/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

Représente une classe pour ajouter du texte et des images sur les pages d'un PDF Document existant.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Constructeur. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Initialise un nouvel objet `PdfFileMend` basé sur le *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur laquelle travaille. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Définit une valeur booléenne qui indique le retour à la ligne dans les méthodes AddText. Si la valeur est vraie, le texte dans FormattedText sera renvoyé à la ligne. Par défaut, la valeur est fausse. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Définit ou obtient la stratégie de positionnement du texte. [`PositioningMode`](../positioningmode/) Le mode par défaut est Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Définit ou obtient l'algorithme de retour à la ligne. Voir WordWrapMode et IsWordWrap. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Non implémenté. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Non implémenté. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Non implémenté. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Ferme l'objet PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libère la façade. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Enregistre le document PDF dans le fichier spécifié. |

### Voir aussi

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


