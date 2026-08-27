---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe décrivant RichMediaAnnotation qui permet d'intégrer des données vidéo/audio dans un document PDF."
type: docs
weight: 4260
url: /fr/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

Classe décrivant RichMediaAnnotation qui permet d'intégrer des données vidéo/audio dans un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initialise RichMediaAnnotation. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte le visiteur pour cette annotation. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Ajoute des données nommées personnalisées (par exemple requises pour le script flash). |
| [getActivateOn](#getActivateOn--) | Événement qui active l'application. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getContent](#getContent--) | Données du contenu Rich Media. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Définit ou obtient les variables flash qui sont passées au lecteur. |
| [getCustomPlayer](#getCustomPlayer--) | Définit ou obtient le lecteur flash personnalisé pour lire les données vidéo/audio. |
| [getType](#getType--) | Obtient ou définit le type de contenu. Valeurs possibles : Audio, Vidéo. |
| [setActivateOn](#setActivateOn-int-) | Événement qui active l'application. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | Définir le flux de contenu. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Définit ou obtient les variables flash qui sont passées au lecteur. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Définit ou obtient le lecteur flash personnalisé pour lire les données vidéo/audio. |
| [setPoster](#setPoster-java.io.InputStream-) | Définir l'affiche de l'annotation. |
| [setType](#setType-int-) | Obtient ou définit le type de contenu. Valeurs possibles : Audio, Vidéo. |
| [update](#update--) | Met à jour les données avec les paramètres spécifiés. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initialise RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte le visiteur pour cette annotation.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Ajoute des données nommées personnalisées (par exemple requises pour le script flash).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Événement qui active l'application.

**Returns:**
Élément ActivationEvent

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Données du contenu Rich Media.

**Returns:**
Objet InputStream

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Définit ou obtient les variables flash qui sont passées au lecteur.

**Returns:**
Objet String

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Définit ou obtient le lecteur flash personnalisé pour lire les données vidéo/audio.

**Returns:**
Objet InputStream

### getType {#getType--}
```
public int getType()
```

Obtient ou définit le type de contenu. Valeurs possibles : Audio, Vidéo.

**Returns:**
Valeur ContentType @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Événement qui active l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ActivationEvent |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
Définir le flux de contenu.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Définit ou obtient les variables flash qui sont passées au lecteur.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Définit ou obtient le lecteur flash personnalisé pour lire les données vidéo/audio.

### setPoster {#setPoster-java.io.InputStream-}
Définir l'affiche de l'annotation.

### setType {#setType-int-}
```
public void setType(int value)
```

Obtient ou définit le type de contenu. Valeurs possibles : Audio, Vidéo.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ContentType |

### update {#update--}
```
public void update()
```

Met à jour les données avec les paramètres spécifiés.
