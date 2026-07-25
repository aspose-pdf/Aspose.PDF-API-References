---
title: "PageInformationAnnotation"
linktitle: "PageInformationAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une annotation d'informations de page dans un document PDF. Cette annotation contient le nom du fichier, le numéro de page ainsi que la date et l'heure de création de l'annotation. Cette classe est."
type: docs
weight: 3380
url: /fr/java/com.aspose.pdf/pageinformationannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.PageInformationAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PageInformationAnnotation extends PrinterMarkAnnotation
```

Représente une annotation Page Information dans un document PDF. Cette annotation contient le nom du fichier, le numéro de page, ainsi que la date et l'heure de création de l'annotation. Cette classe est principalement utilisée pour ajouter des métadonnées à une page spécifique du document PDF, ce qui peut être utile pour le suivi et la référence. Par exemple, elle peut être utilisée pour marquer des pages lors du processus d'impression ou pour fournir des informations supplémentaires sur la page lors de la visualisation du document.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PageInformationAnnotation](#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initialise une nouvelle instance de la classe {@link PageInformationAnnotation} sur la page donnée à l'emplacement indiqué. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte le visiteur pour le traitement des annotations. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |

### PageInformationAnnotation {#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initialise une nouvelle instance de la classe {@link PageInformationAnnotation} sur la page donnée à l'emplacement indiqué.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte le visiteur pour le traitement des annotations.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
valeur int
