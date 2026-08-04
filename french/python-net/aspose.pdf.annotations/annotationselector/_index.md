---
title: "AnnotationSelector"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Cette classe est utilisée pour sélectionner des annotations en utilisant le concept de modèle Visitor."
type: docs
weight: 50
url: /fr/python-net/aspose.pdf.annotations/annotationselector/
---

## AnnotationSelector class

Cette classe est utilisée pour sélectionner des annotations en utilisant le concept de modèle Visitor.

Le type AnnotationSelector expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| AnnotationSelector() | Initialise une nouvelle instance de la classe AnnotationSelector. |
| AnnotationSelector(annotation) | Initialise une nouvelle instance de la classe AnnotationSelector |
## Propriétés
| Nom | Description |
| :- | :- |
| sélectionné | La liste des objets sélectionnés. |
## Méthodes
| Nom | Description |
| :- | :- |
| visit(link) | Sélectionnez l'annotation de lien si AnnotationSelector a été initialisé avec l'objet LinkAnnotation. |
| visit(attachment) | Sélectionnez l'annotation de pièce jointe si AnnotationSelector a été initialisé avec l'objet FileAttachmentAnnotation. |
| visit(text) | Sélectionnez l'annotation de texte si AnnotationSelector a été initialisé avec l'objet TextAnnotation. |
| visit(redact) | Sélectionnez l'annotation de rédaction si AnnotationSelector a été initialisé avec l'objet RedactAnnotation. |
| visit(freetext) | Sélectionnez l'annotation de texte libre si AnnotationSelector a été initialisé avec l'objet FreeTextAnnotation. |
| visit(highlight) | Sélectionnez l'annotation de pièce jointe si AnnotationSelector a été initialisé avec l'objet FreeTextAnnotation. |
| visit(underline) | Sélectionnez l'annotation de soulignement si AnnotationSelector a été initialisé avec l'objet UnderlineAnnotation. |
| visit(strike_out) | Sélectionnez l'annotation de barré si AnnotationSelector a été initialisé avec l'objet StrikeOutAnnotation. |
| visit(squiggly) | Sélectionnez l'annotation ondulée si AnnotationSelector a été initialisé avec l'objet SquigglyAnnotation. |
| visit(popup) | Sélectionnez l'annotation contextuelle si AnnotationSelector a été initialisé avec l'objet PopupAnnotation. |
| visit(line) | Sélectionnez l'annotation de soulignement si AnnotationSelector a été initialisé avec l'objet UnderlineAnnotation. |
| visit(circle) | Sélectionnez l'annotation de cercle si AnnotationSelector a été initialisé avec l'objet CircleAnnotation. |
| visit(square) | Sélectionnez l'annotation carrée si AnnotationSelector a été initialisé avec l'objet SquareAnnotation. |
| visit(ink) | Sélectionnez l'annotation de lien si AnnotationSelector a été initialisé avec l'objet LinkAnnotation. |
| visit(polyline) | Sélectionnez l'annotation de polyligne si AnnotationSelector a été initialisé avec l'objet PolylineAnnotation. |
| visit(polygon) | Sélectionnez l'annotation de polygone si AnnotationSelector a été initialisé avec l'objet PolygonAnnotation. |
| visit(caret) | Sélectionnez l'annotation de caret si AnnotationSelector a été initialisé avec l'objet CaretAnnotation. |
| visit(stamp) | Sélectionnez l'annotation de tampon si AnnotationSelector a été initialisé avec l'objet StampAnnotation. |
| visit(widget) | Sélectionnez l'annotation de widget si AnnotationSelector a été initialisé avec l'objet WidgetAnnotation. |
| visit(watermark) | Sélectionnez l'annotation de filigrane si AnnotationSelector a été initialisé avec l'objet WatermarkAnnotation. |
| visit(movie) | Sélectionnez l'annotation vidéo si AnnotationSelector a été initialisé avec l'objet MovieAnnotation. |
| visit(rich_media) | Sélectionnez l'annotation vidéo si AnnotationSelector a été initialisé avec un objet d'annotation RichMedia. |
| visit(screen) | Sélectionnez l'annotation d'écran si AnnotationSelector a été initialisé avec un objet ScreenAnnotation. |
| visit(pdf_3d) | Sélectionnez l'annotation PDF3D si AnnotationSelector a été initialisé avec un objet PDF3DAnnotation. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

