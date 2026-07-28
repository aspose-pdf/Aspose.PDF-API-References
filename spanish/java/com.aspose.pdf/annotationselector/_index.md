---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase se usa para seleccionar anotaciones utilizando la idea de plantilla Visitor."
type: docs
weight: 100
url: /es/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

Esta clase se usa para seleccionar anotaciones utilizando la idea de plantilla Visitor.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | Inicializa una nueva instancia de la clase AnnotationSelector. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | Inicializa una nueva instancia de la clase AnnotationSelector. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getSelected](#getSelected--) | La lista de objetos seleccionados. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | Selecciona el {@code bleedMark} si el {@link AnnotationSelector} fue inicializado con un objeto {@link BleedMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | Selecciona la anotación de cursor si AnnotationSelector fue inicializado con un objeto CaretAnnotation. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | Selecciona la anotación de círculo si AnnotationSelector fue inicializado con un objeto CircleAnnotation. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | Selecciona la anotación ColorBar si AnnotationSelector fue inicializado con un objeto ColorBar. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Selecciona la anotación de adjunto si AnnotationSelector fue inicializado con un objeto FileAttachmentAnnotation. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | Selecciona la anotación de texto libre si AnnotationSelector fue inicializado con un objeto FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | Selecciona la anotación de adjunto si AnnotationSelector fue inicializado con un objeto FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | Selecciona la anotación de tinta si AnnotationSelector fue inicializado con un objeto InkAnnotation. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | Selecciona la anotación de línea si AnnotationSelector fue inicializado con un objeto LineAnnotation. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | Selecciona la anotación de enlace si AnnotationSelector fue inicializado con un objeto LinkAnnotation. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | Selecciona la anotación de película si AnnotationSelector fue inicializado con un objeto MovieAnnotation. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | Selecciona el {@code pageInformation} si el {@link AnnotationSelector} fue inicializado con un objeto {@link PageInformationAnnotation}. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | Selecciona la anotación PDF3D si AnnotationSelector fue inicializado con un objeto PDF3DAnnotation. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | Selecciona la anotación de polígono si AnnotationSelector fue inicializado con un objeto PolygonAnnotation. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | Seleccionar la anotación de polilínea si AnnotationSelector se inicializó con un objeto PolylineAnnotation. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | Seleccionar la anotación emergente si AnnotationSelector se inicializó con un objeto PopupAnnotation. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | Seleccionar la anotación de redactado si AnnotationSelector se inicializó con un objeto RedactAnnotation. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | Selecciona el {@code registrationMark} si el {@link AnnotationSelector} se inicializó con un {@link RegistrationMarkAnnotation} objeto. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | Seleccionar la anotación de película si AnnotationSelector se inicializó con un objeto RichMedia annotation. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | Seleccionar la anotación de pantalla si AnnotationSelector se inicializó con un objeto ScreenAnnotation. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | Seleccionar la anotación cuadrada si AnnotationSelector se inicializó con un objeto SquareAnnotation. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | Seleccionar la anotación ondulada si AnnotationSelector se inicializó con un objeto SquigglyAnnotation. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | Seleccionar la anotación de sello si AnnotationSelector se inicializó con un objeto StampAnnotation. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Seleccionar la anotación tachada si AnnotationSelector se inicializó con un objeto StrikeOutAnnotation. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | Seleccionar la anotación de texto si AnnotationSelector se inicializó con un objeto TextAnnotation. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | Selecciona el {@code trimMark} si el {@link AnnotationSelector} se inicializó con un {@link TrimMarkAnnotation} objeto. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | Seleccionar la anotación subrayada si AnnotationSelector se inicializó con un objeto UnderlineAnnotation. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | Seleccionar la anotación de marca de agua si AnnotationSelector se inicializó con un objeto WatermarkAnnotation. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | Seleccionar la anotación de widget si AnnotationSelector se inicializó con un objeto WidgetAnnotation. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

Inicializa una nueva instancia de la clase AnnotationSelector.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
Inicializa una nueva instancia de la clase AnnotationSelector.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

La lista de objetos seleccionados.

**Returns:**
Lista de instancias de Annotation

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
Selecciona el {@code bleedMark} si el {@link AnnotationSelector} fue inicializado con un objeto {@link BleedMarkAnnotation}.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
Selecciona la anotación de cursor si AnnotationSelector fue inicializado con un objeto CaretAnnotation.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
Selecciona la anotación de círculo si AnnotationSelector fue inicializado con un objeto CircleAnnotation.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
Selecciona la anotación ColorBar si AnnotationSelector fue inicializado con un objeto ColorBar.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
Selecciona la anotación de adjunto si AnnotationSelector fue inicializado con un objeto FileAttachmentAnnotation.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
Selecciona la anotación de texto libre si AnnotationSelector fue inicializado con un objeto FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
Selecciona la anotación de adjunto si AnnotationSelector fue inicializado con un objeto FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
Selecciona la anotación de tinta si AnnotationSelector fue inicializado con un objeto InkAnnotation.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
Selecciona la anotación de línea si AnnotationSelector fue inicializado con un objeto LineAnnotation.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
Selecciona la anotación de enlace si AnnotationSelector fue inicializado con un objeto LinkAnnotation.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
Selecciona la anotación de película si AnnotationSelector fue inicializado con un objeto MovieAnnotation.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
Selecciona el {@code pageInformation} si el {@link AnnotationSelector} fue inicializado con un objeto {@link PageInformationAnnotation}.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
Selecciona la anotación PDF3D si AnnotationSelector fue inicializado con un objeto PDF3DAnnotation.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
Selecciona la anotación de polígono si AnnotationSelector fue inicializado con un objeto PolygonAnnotation.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
Seleccionar la anotación de polilínea si AnnotationSelector se inicializó con un objeto PolylineAnnotation.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
Seleccionar la anotación emergente si AnnotationSelector se inicializó con un objeto PopupAnnotation.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
Seleccionar la anotación de redactado si AnnotationSelector se inicializó con un objeto RedactAnnotation.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
Selecciona el {@code registrationMark} si el {@link AnnotationSelector} se inicializó con un {@link RegistrationMarkAnnotation} objeto.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
Seleccionar la anotación de película si AnnotationSelector se inicializó con un objeto RichMedia annotation.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
Seleccionar la anotación de pantalla si AnnotationSelector se inicializó con un objeto ScreenAnnotation.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
Seleccionar la anotación cuadrada si AnnotationSelector se inicializó con un objeto SquareAnnotation.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
Seleccionar la anotación ondulada si AnnotationSelector se inicializó con un objeto SquigglyAnnotation.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
Seleccionar la anotación de sello si AnnotationSelector se inicializó con un objeto StampAnnotation.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
Seleccionar la anotación tachada si AnnotationSelector se inicializó con un objeto StrikeOutAnnotation.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
Seleccionar la anotación de texto si AnnotationSelector se inicializó con un objeto TextAnnotation.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
Selecciona el {@code trimMark} si el {@link AnnotationSelector} se inicializó con un {@link TrimMarkAnnotation} objeto.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
Seleccionar la anotación subrayada si AnnotationSelector se inicializó con un objeto UnderlineAnnotation.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
Seleccionar la anotación de marca de agua si AnnotationSelector se inicializó con un objeto WatermarkAnnotation.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
Seleccionar la anotación de widget si AnnotationSelector se inicializó con un objeto WidgetAnnotation.
