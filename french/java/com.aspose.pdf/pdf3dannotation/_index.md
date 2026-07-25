---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe PDF3DAnnotation. Cette classe ne peut pas être héritée. @see Annotation"
type: docs
weight: 3560
url: /fr/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

Classe PDF3DAnnotation. Cette classe ne peut pas être héritée. @see Annotation

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Initialise une nouvelle instance de la classe {@code PDF3DAnnotation}. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Initialise une nouvelle instance de la classe {@code PDF3DAnnotation}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte le visiteur pour le traitement des annotations. |
| [clearImagePreview](#clearImagePreview--) | Efface l'aperçu de l'image. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. Valeur : le type de l'annotation. |
| [getContent](#getContent--) | Obtient ou définit le contenu. Valeur : le contenu. |
| [getImagePreview](#getImagePreview--) | Obtient l'aperçu de l'image. |
| [getLightingScheme](#getLightingScheme--) | Obtient le schéma d'éclairage. Valeur : le schéma d'éclairage. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | Obtient l'œuvre 3D. Valeur : l'œuvre PDF3 d. |
| [getRenderMode](#getRenderMode--) | Obtient le mode de rendu. Valeur : le mode de rendu. |
| [getViewArray](#getViewArray--) | Obtient le tableau de vues. Valeur : le tableau de vues. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | Obtient ou définit le contenu. Valeur : le contenu. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Définit l'index de la vue par défaut. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Définit l'aperçu de l'image. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Définit l'aperçu de l'image. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Initialise une nouvelle instance de la classe {@code PDF3DAnnotation}.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Initialise une nouvelle instance de la classe {@code PDF3DAnnotation}.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte le visiteur pour le traitement des annotations.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Efface l'aperçu de l'image.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation. Valeur : le type de l'annotation.

**Returns:**
valeur int

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

Obtient ou définit le contenu. Valeur : le contenu.

**Returns:**
PDF3DContent object

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Obtient l'aperçu de l'image.

**Returns:**
Aperçu de l'image sous forme de flux.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Obtient le schéma d'éclairage. Valeur : le schéma d'éclairage.

**Returns:**
PDF3DLightingScheme object

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

Obtient l'œuvre 3D. Valeur : l'œuvre PDF3 d.

**Returns:**
PDF3DArtwork objet

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Obtient le mode de rendu. Valeur : le mode de rendu.

**Returns:**
PDF3DRenderMode objet

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Obtient le tableau de vues. Valeur : le tableau de vues.

**Returns:**
PDF3DViewArray objet

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
Obtient ou définit le contenu. Valeur : le contenu.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Définit l'index de la vue par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'index de vue par défaut. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Définit l'aperçu de l'image.

### setImagePreview {#setImagePreview-java.lang.String-}
Définit l'aperçu de l'image.
