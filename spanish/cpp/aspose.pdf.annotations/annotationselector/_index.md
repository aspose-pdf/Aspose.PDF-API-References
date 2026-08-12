---
title: "Aspose::Pdf::Annotations::AnnotationSelector clase"
linktitle: "AnnotationSelector"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::AnnotationSelector clase. Esta clase se utiliza para seleccionar anotaciones usando la idea de plantilla Visitor en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class


Esta clase se usa para seleccionar anotaciones utilizando la idea de plantilla Visitor.

```cpp
class AnnotationSelector : public Aspose::Pdf::Annotations::IAnnotationVisitor
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AnnotationSelector](./annotationselector/)() | Inicializa una nueva instancia de la clase [AnnotationSelector](./). |
| [AnnotationSelector](./annotationselector/)(const System::SharedPtr\<Annotation\>\&) | Inicializa un nuevo objeto [AnnotationSelector](./). |
| [get_Selected](./get_selected/)() const | La lista de objetos seleccionados. |
| [Visit](./visit/)(System::SharedPtr\<LinkAnnotation\>) override | Selecciona la anotación de enlace si [AnnotationSelector](./) se inicializó con el objeto [LinkAnnotation](../linkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<FileAttachmentAnnotation\>) override | Selecciona la anotación de adjunto si [AnnotationSelector](./) se inicializó con el objeto [FileAttachmentAnnotation](../fileattachmentannotation/). |
| [Visit](./visit/)(System::SharedPtr\<TextAnnotation\>) override | Selecciona la anotación de texto si [AnnotationSelector](./) se inicializó con el objeto [TextAnnotation](../textannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<RedactionAnnotation\>\&) | Selecciona la anotación de redacción si [AnnotationSelector](./) fue inicializado con el objeto RedactAnnotation. |
| [Visit](./visit/)(System::SharedPtr\<FreeTextAnnotation\>) override | Selecciona la anotación de texto libre si [AnnotationSelector](./) fue inicializado con el objeto [FreeTextAnnotation](../freetextannotation/). |
| [Visit](./visit/)(System::SharedPtr\<HighlightAnnotation\>) override | Selecciona la anotación de adjunto si [AnnotationSelector](./) fue inicializado con el objeto [FreeTextAnnotation](../freetextannotation/). |
| [Visit](./visit/)(System::SharedPtr\<UnderlineAnnotation\>) override | Selecciona la anotación subrayado si [AnnotationSelector](./) fue inicializado con el objeto [UnderlineAnnotation](../underlineannotation/). |
| [Visit](./visit/)(System::SharedPtr\<StrikeOutAnnotation\>) override | Selecciona la anotación tachado si [AnnotationSelector](./) fue inicializado con el objeto [StrikeOutAnnotation](../strikeoutannotation/). |
| [Visit](./visit/)(System::SharedPtr\<SquigglyAnnotation\>) override | Selecciona la anotación ondulada si [AnnotationSelector](./) fue inicializado con el objeto [SquigglyAnnotation](../squigglyannotation/). |
| [Visit](./visit/)(System::SharedPtr\<PopupAnnotation\>) override | Selecciona la anotación emergente si [AnnotationSelector](./) fue inicializado con el objeto [PopupAnnotation](../popupannotation/). |
| [Visit](./visit/)(System::SharedPtr\<LineAnnotation\>) override | Selecciona la anotación de línea si [AnnotationSelector](./) fue inicializado con el objeto [LineAnnotation](../lineannotation/). |
| [Visit](./visit/)(System::SharedPtr\<CircleAnnotation\>) override | Selecciona la anotación de círculo si [AnnotationSelector](./) fue inicializado con el objeto [CircleAnnotation](../circleannotation/). |
| [Visit](./visit/)(System::SharedPtr\<SquareAnnotation\>) override | Selecciona la anotación cuadrada si [AnnotationSelector](./) fue inicializado con el objeto [SquareAnnotation](../squareannotation/). |
| [Visit](./visit/)(System::SharedPtr\<InkAnnotation\>) override | Selecciona la anotación de tinta si [AnnotationSelector](./) fue inicializado con el objeto [InkAnnotation](../inkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<PolylineAnnotation\>) override | Selecciona la anotación de polilínea si [AnnotationSelector](./) fue inicializado con el objeto [PolylineAnnotation](../polylineannotation/). |
| [Visit](./visit/)(System::SharedPtr\<PolygonAnnotation\>) override | Selecciona la anotación de polígono si [AnnotationSelector](./) fue inicializado con el objeto [PolygonAnnotation](../polygonannotation/). |
| [Visit](./visit/)(System::SharedPtr\<CaretAnnotation\>) override | Selecciona la anotación de cursor si [AnnotationSelector](./) fue inicializado con el objeto [CaretAnnotation](../caretannotation/). |
| [Visit](./visit/)(System::SharedPtr\<StampAnnotation\>) override | Selecciona la anotación de sello si [AnnotationSelector](./) fue inicializado con el objeto [StampAnnotation](../stampannotation/). |
| [Visit](./visit/)(System::SharedPtr\<WidgetAnnotation\>) override | Selecciona la anotación de widget si [AnnotationSelector](./) fue inicializado con el objeto [WidgetAnnotation](../widgetannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<WatermarkAnnotation\>\&) | Selecciona la anotación de marca de agua si [AnnotationSelector](./) fue inicializado con el objeto [WatermarkAnnotation](../watermarkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<MovieAnnotation\>) override | Selecciona la anotación de película si [AnnotationSelector](./) fue inicializado con el objeto [MovieAnnotation](../movieannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<RichMediaAnnotation\>\&) | Selecciona la anotación de película si [AnnotationSelector](./) fue inicializado con el objeto de anotación RichMedia. |
| [Visit](./visit/)(System::SharedPtr\<ScreenAnnotation\>) override | Selecciona la anotación de pantalla si [AnnotationSelector](./) fue inicializado con el objeto [ScreenAnnotation](../screenannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<PDF3DAnnotation\>\&) | Selecciona la anotación PDF3D si [AnnotationSelector](./) fue inicializado con el objeto [PDF3DAnnotation](../pdf3dannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<ColorBarAnnotation\>\&) | Selecciona la anotación ColorBar si [AnnotationSelector](./) fue inicializado con el objeto ColorBar. |
| [Visit](./visit/)(System::SharedPtr\<TrimMarkAnnotation\>) override | Selecciona el *trimMark* si el [AnnotationSelector](./) fue inicializado con un objeto [TrimMarkAnnotation](../trimmarkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<BleedMarkAnnotation\>) override | Selecciona el *bleedMark* si el [AnnotationSelector](./) fue inicializado con un objeto [BleedMarkAnnotation](../bleedmarkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<RegistrationMarkAnnotation\>) override | Selecciona el *registrationMark* si el [AnnotationSelector](./) fue inicializado con un objeto [RegistrationMarkAnnotation](../registrationmarkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<PageInformationAnnotation\>) override | Selecciona el *pageInformation* si el [AnnotationSelector](./) fue inicializado con un objeto [PageInformationAnnotation](../pageinformationannotation/). |
## Ver también

* Class [IAnnotationVisitor](../iannotationvisitor/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
