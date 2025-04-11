---
title: Class AnnotationSelector
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.AnnotationSelector. Esta classe é usada para selecionar anotações usando a ideia do template Visitor
type: docs
weight: 1450
url: /pt/net/aspose.pdf.annotations/annotationselector/
---
## Classe AnnotationSelector

Esta classe é usada para selecionar anotações usando a ideia do template Visitor.

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | Inicializa uma nova instância da classe AnnotationSelector. |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | Inicializa um novo objeto `AnnotationSelector`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | A lista de objetos selecionados. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | Seleciona o *bleedMark* se o `AnnotationSelector` foi inicializado com um objeto [`BleedMarkAnnotation`](../bleedmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | Seleciona a anotação de caret se o AnnotationSelector foi inicializado com um objeto CaretAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | Seleciona a anotação de círculo se o AnnotationSelector foi inicializado com um objeto CircleAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | Seleciona a anotação ColorBar se o AnnotationSelector foi inicializado com um objeto ColorBar. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | Seleciona a anotação de anexo se o AnnotationSelector foi inicializado com um objeto FileAttachmentAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | Seleciona a anotação de texto livre se o AnnotationSelector foi inicializado com um objeto FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | Seleciona a anotação de anexo se o AnnotationSelector foi inicializado com um objeto FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | Seleciona a anotação de tinta se o AnnotationSelector foi inicializado com um objeto InkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | Seleciona a anotação de linha se o AnnotationSelector foi inicializado com um objeto LineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | Seleciona a anotação de link se o AnnotationSelector foi inicializado com um objeto LinkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | Seleciona a anotação de filme se o AnnotationSelector foi inicializado com um objeto MovieAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | Seleciona o *pageInformation* se o `AnnotationSelector` foi inicializado com um objeto [`PageInformationAnnotation`](../pageinformationannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | Seleciona a anotação PDF3D se o AnnotationSelector foi inicializado com um objeto PDF3DAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | Seleciona a anotação de polígono se o AnnotationSelector foi inicializado com um objeto PolygonAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | Seleciona a anotação de polilinha se o AnnotationSelector foi inicializado com um objeto PolylineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | Seleciona a anotação de popup se o AnnotationSelector foi inicializado com um objeto PopupAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | Seleciona a anotação de redação se o AnnotationSelector foi inicializado com um objeto RedactAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | Seleciona o *registrationMark* se o `AnnotationSelector` foi inicializado com um objeto [`RegistrationMarkAnnotation`](../registrationmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | Seleciona a anotação de filme se o AnnotationSelector foi inicializado com um objeto de anotação RichMedia. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | Seleciona a anotação de tela se o AnnotationSelector foi inicializado com um objeto ScreenAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | Seleciona a anotação de quadrado se o AnnotationSelector foi inicializado com um objeto SquareAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | Seleciona a anotação ondulada se o AnnotationSelector foi inicializado com um objeto SquigglyAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | Seleciona a anotação de carimbo se o AnnotationSelector foi inicializado com um objeto StampAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | Seleciona a anotação de riscado se o AnnotationSelector foi inicializado com um objeto StrikeOutAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | Seleciona a anotação de texto se o AnnotationSelector foi inicializado com um objeto TextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | Seleciona o *trimMark* se o `AnnotationSelector` foi inicializado com um objeto [`TrimMarkAnnotation`](../trimmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | Seleciona a anotação sublinhada se o AnnotationSelector foi inicializado com um objeto UnderlineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | Seleciona a anotação de marca d'água se o AnnotationSelector foi inicializado com um objeto WatermarkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | Seleciona a anotação de widget se o AnnotationSelector foi inicializado com um objeto WidgetAnnotation. |

### Veja Também

* interface [IAnnotationVisitor](../iannotationvisitor/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)