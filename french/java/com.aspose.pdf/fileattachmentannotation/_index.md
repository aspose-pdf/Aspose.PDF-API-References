---
title: "FileAttachmentAnnotation"
linktitle: "FileAttachmentAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe décrivant l'annotation de pièce jointe de fichier."
type: docs
weight: 1430
url: /fr/java/com.aspose.pdf/fileattachmentannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FileAttachmentAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FileAttachmentAnnotation extends MarkupAnnotation
```

Classe décrivant l'annotation de pièce jointe de fichier.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileAttachmentAnnotation](#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-) | Crée une nouvelle annotation FileAttachment sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte l'objet visiteur pour traiter l'annotation. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getFile](#getFile--) | Récupère la spécification du fichier associé à cette annotation. |
| [getIcon](#getIcon--) | Obtient l'icône qui doit être utilisée pour afficher l'annotation. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Définit la spécification du fichier associé à cette annotation. |
| [setIcon](#setIcon-com.aspose.pdf.FileIcon-) | Définit l'icône qui doit être utilisée pour afficher l'annotation. |

### FileAttachmentAnnotation {#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-}
Crée une nouvelle annotation FileAttachment sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte l'objet visiteur pour traiter l'annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Valeur int @see AnnotationType

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Récupère la spécification du fichier associé à cette annotation.

**Returns:**
spécification du fichier.

### getIcon {#getIcon--}
```
public FileIcon getIcon()
```

Obtient l'icône qui doit être utilisée pour afficher l'annotation.

**Returns:**
Valeur FileIcon @see FileIcon

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Définit la spécification du fichier associé à cette annotation.

### setIcon {#setIcon-com.aspose.pdf.FileIcon-}
Définit l'icône qui doit être utilisée pour afficher l'annotation.
