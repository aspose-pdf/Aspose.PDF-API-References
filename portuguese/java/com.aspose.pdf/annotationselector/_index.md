---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe é usada para selecionar anotações usando a ideia de template Visitor."
type: docs
weight: 100
url: /pt/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

Esta classe é usada para selecionar anotações usando a ideia de template Visitor.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | Inicializa uma nova instância da classe AnnotationSelector. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | Inicializa uma nova instância da classe AnnotationSelector. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getSelected](#getSelected--) | A lista de objetos selecionados. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | Seleciona o {@code bleedMark} se o {@link AnnotationSelector} foi inicializado com um objeto {@link BleedMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | Seleciona a anotação caret se o AnnotationSelector foi inicializado com um objeto CaretAnnotation. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | Seleciona a anotação de círculo se o AnnotationSelector foi inicializado com um objeto CircleAnnotation. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | Seleciona a anotação ColorBar se o AnnotationSelector foi inicializado com um objeto ColorBar. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Seleciona a anotação de anexo se o AnnotationSelector foi inicializado com um objeto FileAttachmentAnnotation. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | Seleciona a anotação de texto livre se o AnnotationSelector foi inicializado com um objeto FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | Seleciona a anotação de anexo se o AnnotationSelector foi inicializado com um objeto FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | Seleciona a anotação de tinta se o AnnotationSelector foi inicializado com um objeto InkAnnotation. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | Seleciona a anotação de linha se o AnnotationSelector foi inicializado com um objeto LineAnnotation. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | Seleciona a anotação de link se o AnnotationSelector foi inicializado com um objeto LinkAnnotation. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | Seleciona a anotação de filme se o AnnotationSelector foi inicializado com um objeto MovieAnnotation. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | Seleciona o {@code pageInformation} se o {@link AnnotationSelector} foi inicializado com um objeto {@link PageInformationAnnotation}. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | Seleciona a anotação PDF3D se o AnnotationSelector foi inicializado com um objeto PDF3DAnnotation. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | Seleciona a anotação de polígono se o AnnotationSelector foi inicializado com um objeto PolygonAnnotation. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | Selecione a anotação de polilinha se AnnotationSelector foi inicializado com o objeto PolylineAnnotation. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | Selecione a anotação popup se AnnotationSelector foi inicializado com o objeto PopupAnnotation. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | Selecione a anotação de redação se AnnotationSelector foi inicializado com o objeto RedactAnnotation. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | Seleciona o {@code registrationMark} se o {@link AnnotationSelector} foi inicializado com um objeto {@link RegistrationMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | Selecione a anotação de filme se AnnotationSelector foi inicializado com o objeto RichMedia annotation. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | Selecione a anotação de tela se AnnotationSelector foi inicializado com o objeto ScreenAnnotation. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | Selecione a anotação quadrada se AnnotationSelector foi inicializado com o objeto SquareAnnotation. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | Selecione a anotação ondulada se AnnotationSelector foi inicializado com o objeto SquigglyAnnotation. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | Selecione a anotação de selo se AnnotationSelector foi inicializado com o objeto StampAnnotation. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Selecione a anotação de tachado se AnnotationSelector foi inicializado com o objeto StrikeOutAnnotation. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | Selecione a anotação de texto se AnnotationSelector foi inicializado com o objeto TextAnnotation. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | Seleciona o {@code trimMark} se o {@link AnnotationSelector} foi inicializado com um objeto {@link TrimMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | Selecione a anotação sublinhada se AnnotationSelector foi inicializado com o objeto UnderlineAnnotation. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | Selecione a anotação de marca d'água se AnnotationSelector foi inicializado com o objeto WatermarkAnnotation. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | Selecione a anotação de widget se AnnotationSelector foi inicializado com o objeto WidgetAnnotation. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

Inicializa uma nova instância da classe AnnotationSelector.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
Inicializa uma nova instância da classe AnnotationSelector.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

A lista de objetos selecionados.

**Returns:**
Lista de instâncias de Annotation

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
Seleciona o {@code bleedMark} se o {@link AnnotationSelector} foi inicializado com um objeto {@link BleedMarkAnnotation}.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
Seleciona a anotação caret se o AnnotationSelector foi inicializado com um objeto CaretAnnotation.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
Seleciona a anotação de círculo se o AnnotationSelector foi inicializado com um objeto CircleAnnotation.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
Seleciona a anotação ColorBar se o AnnotationSelector foi inicializado com um objeto ColorBar.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
Seleciona a anotação de anexo se o AnnotationSelector foi inicializado com um objeto FileAttachmentAnnotation.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
Seleciona a anotação de texto livre se o AnnotationSelector foi inicializado com um objeto FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
Seleciona a anotação de anexo se o AnnotationSelector foi inicializado com um objeto FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
Seleciona a anotação de tinta se o AnnotationSelector foi inicializado com um objeto InkAnnotation.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
Seleciona a anotação de linha se o AnnotationSelector foi inicializado com um objeto LineAnnotation.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
Seleciona a anotação de link se o AnnotationSelector foi inicializado com um objeto LinkAnnotation.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
Seleciona a anotação de filme se o AnnotationSelector foi inicializado com um objeto MovieAnnotation.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
Seleciona o {@code pageInformation} se o {@link AnnotationSelector} foi inicializado com um objeto {@link PageInformationAnnotation}.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
Seleciona a anotação PDF3D se o AnnotationSelector foi inicializado com um objeto PDF3DAnnotation.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
Seleciona a anotação de polígono se o AnnotationSelector foi inicializado com um objeto PolygonAnnotation.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
Selecione a anotação de polilinha se AnnotationSelector foi inicializado com o objeto PolylineAnnotation.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
Selecione a anotação popup se AnnotationSelector foi inicializado com o objeto PopupAnnotation.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
Selecione a anotação de redação se AnnotationSelector foi inicializado com o objeto RedactAnnotation.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
Seleciona o {@code registrationMark} se o {@link AnnotationSelector} foi inicializado com um objeto {@link RegistrationMarkAnnotation}.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
Selecione a anotação de filme se AnnotationSelector foi inicializado com o objeto RichMedia annotation.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
Selecione a anotação de tela se AnnotationSelector foi inicializado com o objeto ScreenAnnotation.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
Selecione a anotação quadrada se AnnotationSelector foi inicializado com o objeto SquareAnnotation.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
Selecione a anotação ondulada se AnnotationSelector foi inicializado com o objeto SquigglyAnnotation.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
Selecione a anotação de selo se AnnotationSelector foi inicializado com o objeto StampAnnotation.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
Selecione a anotação de tachado se AnnotationSelector foi inicializado com o objeto StrikeOutAnnotation.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
Selecione a anotação de texto se AnnotationSelector foi inicializado com o objeto TextAnnotation.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
Seleciona o {@code trimMark} se o {@link AnnotationSelector} foi inicializado com um objeto {@link TrimMarkAnnotation}.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
Selecione a anotação sublinhada se AnnotationSelector foi inicializado com o objeto UnderlineAnnotation.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
Selecione a anotação de marca d'água se AnnotationSelector foi inicializado com o objeto WatermarkAnnotation.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
Selecione a anotação de widget se AnnotationSelector foi inicializado com o objeto WidgetAnnotation.
