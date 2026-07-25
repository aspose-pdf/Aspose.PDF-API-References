---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une annotation sonore contenant un son enregistré depuis le microphone de l'ordinateur ou importé depuis un fichier."
type: docs
weight: 4530
url: /fr/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Représente une annotation sonore contenant un son enregistré depuis le microphone de l'ordinateur ou importé depuis un fichier.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Crée une nouvelle annotation Sound sur la page spécifiée. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Crée une nouvelle annotation Sound sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getIcon](#getIcon--) | Obtient une icône à utiliser pour l'affichage de l'annotation. |
| [getSoundData](#getSoundData--) | Obtient un objet son définissant le son à lire lorsque l'annotation est activée. |
| [setIcon](#setIcon-int-) | Définit une icône à utiliser pour l'affichage de l'annotation. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Crée une nouvelle annotation Sound sur la page spécifiée.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Crée une nouvelle annotation Sound sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
AnnotationType valeur @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Obtient une icône à utiliser pour l'affichage de l'annotation.

**Returns:**
SoundIcon valeur @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Obtient un objet son définissant le son à lire lorsque l'annotation est activée.

**Returns:**
SoundData valeur

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Définit une icône à utiliser pour l'affichage de l'annotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | SoundIcon valeur @see SoundIcon |
