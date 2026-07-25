---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente une annotation de tampon en caoutchouc. Ce type d'annotation affiche du texte ou des graphiques destinés à donner l'impression d'être tamponnés sur la page avec un tampon en caoutchouc. </p> <hr>."
type: docs
weight: 4630
url: /fr/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Représente l'annotation de tampon en caoutchouc. Ce type d'annotation affiche du texte ou des graphiques destinés à ressembler à un tampon appliqué sur la page. </p> <hr> <pre> Le fragment de code suivant montre comment ajouter 2 tampons à la première page du document PDF. Le document d'entrée provient de inFile et les modifications sont enregistrées dans outFile. Le premier tampon a l'icône NotForPublicRelease et le second utilise l'image provenant de rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Constructeur |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crée une nouvelle annotation de tampon sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte le visiteur {@code AnnotationSelector} lors de la navigation dans la collection d'annotations. |
| [clear](#clear--) | Effacer les instances statiques |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getIcon](#getIcon--) | Obtient l'icône du tampon en caoutchouc. |
| [getImage](#getImage--) | Obtient l'image de l'annotation. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Définit l'image SVG de l'annotation sous forme de chaîne Base64. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Définit l'icône du tampon en caoutchouc. |
| [setImage](#setImage-java.io.InputStream-) | Définit l'image de l'annotation. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Constructeur

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crée une nouvelle annotation de tampon sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte le visiteur {@code AnnotationSelector} lors de la navigation dans la collection d'annotations.

### clear {#clear--}
```
public static void clear()
```

Effacer les instances statiques

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Obtient l'icône du tampon en caoutchouc.

**Returns:**
Valeur StampIcon

### getImage {#getImage--}
```
public InputStream getImage()
```

Obtient l'image de l'annotation.

**Returns:**
Objet InputStream

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Définit l'image SVG de l'annotation sous forme de chaîne Base64.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Définit l'icône du tampon en caoutchouc.

### setImage {#setImage-java.io.InputStream-}
Définit l'image de l'annotation.
