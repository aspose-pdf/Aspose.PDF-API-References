---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe est utilisée pour sélectionner des annotations en utilisant le concept de modèle Visitor."
type: docs
weight: 100
url: /fr/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

Cette classe est utilisée pour sélectionner des annotations en utilisant le concept de modèle Visitor.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | Initialise une nouvelle instance de la classe AnnotationSelector. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | Initialise une nouvelle instance de la classe AnnotationSelector. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getSelected](#getSelected--) | La liste des objets sélectionnés. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | Sélectionne le {@code bleedMark} si le {@link AnnotationSelector} a été initialisé avec un objet {@link BleedMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | Sélectionne l'annotation caret si AnnotationSelector a été initialisé avec un objet CaretAnnotation. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | Sélectionne l'annotation cercle si AnnotationSelector a été initialisé avec un objet CircleAnnotation. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | Sélectionne l'annotation ColorBar si AnnotationSelector a été initialisé avec un objet ColorBar. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Sélectionne l'annotation pièce jointe si AnnotationSelector a été initialisé avec un objet FileAttachmentAnnotation. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | Sélectionne l'annotation texte libre si AnnotationSelector a été initialisé avec un objet FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | Sélectionne l'annotation pièce jointe si AnnotationSelector a été initialisé avec un objet FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | Sélectionne l'annotation encre si AnnotationSelector a été initialisé avec un objet InkAnnotation. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | Sélectionne l'annotation ligne si AnnotationSelector a été initialisé avec un objet LineAnnotation. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | Sélectionne l'annotation lien si AnnotationSelector a été initialisé avec un objet LinkAnnotation. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | Sélectionne l'annotation film si AnnotationSelector a été initialisé avec un objet MovieAnnotation. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | Sélectionne le {@code pageInformation} si le {@link AnnotationSelector} a été initialisé avec un objet {@link PageInformationAnnotation}. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | Sélectionne l'annotation PDF3D si AnnotationSelector a été initialisé avec un objet PDF3DAnnotation. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | Sélectionne l'annotation polygone si AnnotationSelector a été initialisé avec un objet PolygonAnnotation. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | Sélectionnez l'annotation polyline si AnnotationSelector a été initialisé avec l'objet PolylineAnnotation. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | Sélectionnez l'annotation popup si AnnotationSelector a été initialisé avec l'objet PopupAnnotation. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | Sélectionnez l'annotation de rédaction si AnnotationSelector a été initialisé avec l'objet RedactAnnotation. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | Sélectionne le {@code registrationMark} si le {@link AnnotationSelector} a été initialisé avec un objet {@link RegistrationMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | Sélectionnez l'annotation movie si AnnotationSelector a été initialisé avec l'objet d'annotation RichMedia. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | Sélectionnez l'annotation d'écran si AnnotationSelector a été initialisé avec l'objet ScreenAnnotation. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | Sélectionnez l'annotation carrée si AnnotationSelector a été initialisé avec l'objet SquareAnnotation. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | Sélectionnez l'annotation ondulée si AnnotationSelector a été initialisé avec l'objet SquigglyAnnotation. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | Sélectionnez l'annotation tampon si AnnotationSelector a été initialisé avec l'objet StampAnnotation. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Sélectionnez l'annotation barrée si AnnotationSelector a été initialisé avec l'objet StrikeOutAnnotation. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | Sélectionnez l'annotation texte si AnnotationSelector a été initialisé avec l'objet TextAnnotation. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | Sélectionne le {@code trimMark} si le {@link AnnotationSelector} a été initialisé avec un objet {@link TrimMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | Sélectionnez l'annotation soulignée si AnnotationSelector a été initialisé avec l'objet UnderlineAnnotation. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | Sélectionnez l'annotation filigrane si AnnotationSelector a été initialisé avec l'objet WatermarkAnnotation. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | Sélectionnez l'annotation widget si AnnotationSelector a été initialisé avec l'objet WidgetAnnotation. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

Initialise une nouvelle instance de la classe AnnotationSelector.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
Initialise une nouvelle instance de la classe AnnotationSelector.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

La liste des objets sélectionnés.

**Returns:**
Liste des instances d'Annotation

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
Sélectionne le {@code bleedMark} si le {@link AnnotationSelector} a été initialisé avec un objet {@link BleedMarkAnnotation}.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
Sélectionne l'annotation caret si AnnotationSelector a été initialisé avec un objet CaretAnnotation.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
Sélectionne l'annotation cercle si AnnotationSelector a été initialisé avec un objet CircleAnnotation.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
Sélectionne l'annotation ColorBar si AnnotationSelector a été initialisé avec un objet ColorBar.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
Sélectionne l'annotation pièce jointe si AnnotationSelector a été initialisé avec un objet FileAttachmentAnnotation.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
Sélectionne l'annotation texte libre si AnnotationSelector a été initialisé avec un objet FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
Sélectionne l'annotation pièce jointe si AnnotationSelector a été initialisé avec un objet FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
Sélectionne l'annotation encre si AnnotationSelector a été initialisé avec un objet InkAnnotation.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
Sélectionne l'annotation ligne si AnnotationSelector a été initialisé avec un objet LineAnnotation.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
Sélectionne l'annotation lien si AnnotationSelector a été initialisé avec un objet LinkAnnotation.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
Sélectionne l'annotation film si AnnotationSelector a été initialisé avec un objet MovieAnnotation.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
Sélectionne le {@code pageInformation} si le {@link AnnotationSelector} a été initialisé avec un objet {@link PageInformationAnnotation}.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
Sélectionne l'annotation PDF3D si AnnotationSelector a été initialisé avec un objet PDF3DAnnotation.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
Sélectionne l'annotation polygone si AnnotationSelector a été initialisé avec un objet PolygonAnnotation.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
Sélectionnez l'annotation polyline si AnnotationSelector a été initialisé avec l'objet PolylineAnnotation.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
Sélectionnez l'annotation popup si AnnotationSelector a été initialisé avec l'objet PopupAnnotation.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
Sélectionnez l'annotation de rédaction si AnnotationSelector a été initialisé avec l'objet RedactAnnotation.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
Sélectionne le {@code registrationMark} si le {@link AnnotationSelector} a été initialisé avec un objet {@link RegistrationMarkAnnotation}.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
Sélectionnez l'annotation movie si AnnotationSelector a été initialisé avec l'objet d'annotation RichMedia.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
Sélectionnez l'annotation d'écran si AnnotationSelector a été initialisé avec l'objet ScreenAnnotation.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
Sélectionnez l'annotation carrée si AnnotationSelector a été initialisé avec l'objet SquareAnnotation.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
Sélectionnez l'annotation ondulée si AnnotationSelector a été initialisé avec l'objet SquigglyAnnotation.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
Sélectionnez l'annotation tampon si AnnotationSelector a été initialisé avec l'objet StampAnnotation.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
Sélectionnez l'annotation barrée si AnnotationSelector a été initialisé avec l'objet StrikeOutAnnotation.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
Sélectionnez l'annotation texte si AnnotationSelector a été initialisé avec l'objet TextAnnotation.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
Sélectionne le {@code trimMark} si le {@link AnnotationSelector} a été initialisé avec un objet {@link TrimMarkAnnotation}.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
Sélectionnez l'annotation soulignée si AnnotationSelector a été initialisé avec l'objet UnderlineAnnotation.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
Sélectionnez l'annotation filigrane si AnnotationSelector a été initialisé avec l'objet WatermarkAnnotation.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
Sélectionnez l'annotation widget si AnnotationSelector a été initialisé avec l'objet WidgetAnnotation.
