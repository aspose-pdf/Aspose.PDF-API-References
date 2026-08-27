---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une annotation vidéo qui contient des graphiques animés et du son à présenter sur l'écran d'ordinateur et à travers les haut-parleurs. Lorsque l'annotation est activée, le."
type: docs
weight: 3090
url: /fr/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Représente une annotation vidéo qui contient des graphiques animés et du son à présenter sur l'écran de l'ordinateur et via les haut-parleurs. Lorsque l'annotation est activée, la vidéo est lue.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Constructeur à utiliser avec le Générateur. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Crée une nouvelle annotation Sound sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getAspect](#getAspect--) | Obtient ou définit la largeur et la hauteur de la boîte englobante du film, en pixels. |
| [getFile](#getFile--) | Obtient une spécification de fichier identifiant un fichier film auto-descriptif. |
| [getPoster](#getPoster--) | Obtient ou définit un drapeau ou un flux spécifiant si et comment une image d'affiche représentant le film doit être affichée. Si vrai, l'image d'affiche doit être récupérée à partir du fichier du film ; si faux, aucune affiche ne doit être affichée. |
| [getRotate](#getRotate--) | Obtient le titre de l'annotation du film. |
| [getTitle](#getTitle--) | Définit une spécification de fichier identifiant un fichier film auto-descriptif. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Obtient ou définit la largeur et la hauteur de la boîte englobante du film, en pixels. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Définit le titre de l'annotation du film. |
| [setPoster](#setPoster-boolean-) | Obtient ou définit un drapeau ou un flux spécifiant si et comment une image d'affiche représentant le film doit être affichée. Si vrai, l'image d'affiche doit être récupérée à partir du fichier du film ; si faux, aucune affiche ne doit être affichée. |
| [setRotate](#setRotate-int-) | Obtient le titre de l'annotation du film. |
| [setTitle](#setTitle-java.lang.String-) | Élément AnnotationType en tant que valeur int @see AnnotationType |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Constructeur à utiliser avec le Générateur.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Crée une nouvelle annotation Sound sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Valeur FileSpecification

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Obtient ou définit la largeur et la hauteur de la boîte englobante du film, en pixels.

**Returns:**
Instance de Point

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Obtient une spécification de fichier identifiant un fichier film auto-descriptif.

**Returns:**
PolylineAnnotation

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Obtient ou définit un drapeau ou un flux spécifiant si et comment une image d'affiche représentant le film doit être affichée. Si vrai, l'image d'affiche doit être récupérée à partir du fichier du film ; si faux, aucune affiche ne doit être affichée.

**Returns:**
valeur booléenne

### getRotate {#getRotate--}
```
public final int getRotate()
```

Obtient le titre de l'annotation du film.

**Returns:**
valeur int

### getTitle {#getTitle--}
```
public String getTitle()
```

Définit une spécification de fichier identifiant un fichier film auto-descriptif.

**Returns:**
valeur String

### setAspect {#setAspect-com.aspose.pdf.Point-}
Obtient ou définit la largeur et la hauteur de la boîte englobante du film, en pixels.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Définit le titre de l'annotation du film.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Obtient ou définit un drapeau ou un flux spécifiant si et comment une image d'affiche représentant le film doit être affichée. Si vrai, l'image d'affiche doit être récupérée à partir du fichier du film ; si faux, aucune affiche ne doit être affichée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Obtient le titre de l'annotation du film.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setTitle {#setTitle-java.lang.String-}
Élément AnnotationType en tant que valeur int @see AnnotationType
