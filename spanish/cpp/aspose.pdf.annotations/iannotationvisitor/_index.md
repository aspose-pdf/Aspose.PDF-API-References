---
title: "Aspose::Pdf::Annotations::IAnnotationVisitor clase"
linktitle: "IAnnotationVisitor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::IAnnotationVisitor clase. Define Visitor para visitar diferentes anotaciones de documento en C++."
type: docs
weight: 4900
url: /es/cpp/aspose.pdf.annotations/iannotationvisitor/
---
## IAnnotationVisitor class


Define Visitor para visitar diferentes anotaciones del documento.

```cpp
class IAnnotationVisitor : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Visit](./visit/)(System::SharedPtr\<LinkAnnotation\>) | Visitar/seleccionar anotación de enlace. |
| virtual [Visit](./visit/)(System::SharedPtr\<FileAttachmentAnnotation\>) | Visitar/seleccionar anotación de adjunto. |
| virtual [Visit](./visit/)(System::SharedPtr\<TextAnnotation\>) | Visitar/seleccionar anotación de texto. |
| virtual [Visit](./visit/)(System::SharedPtr\<FreeTextAnnotation\>) | Visitar/seleccionar anotación de texto libre. |
| virtual [Visit](./visit/)(System::SharedPtr\<HighlightAnnotation\>) | Visitar/seleccionar anotación de resaltado. |
| virtual [Visit](./visit/)(System::SharedPtr\<UnderlineAnnotation\>) | Visitar/seleccionar anotación de subrayado. |
| virtual [Visit](./visit/)(System::SharedPtr\<StrikeOutAnnotation\>) | Visitar/seleccionar anotación de tachado. |
| virtual [Visit](./visit/)(System::SharedPtr\<SquigglyAnnotation\>) | Visitar/seleccionar anotación ondulada. |
| virtual [Visit](./visit/)(System::SharedPtr\<PopupAnnotation\>) | Visitar/seleccionar anotación emergente. |
| virtual [Visit](./visit/)(System::SharedPtr\<LineAnnotation\>) | Visitar/seleccionar anotación de línea. |
| virtual [Visit](./visit/)(System::SharedPtr\<CircleAnnotation\>) | Visitar/seleccionar anotación de círculo. |
| virtual [Visit](./visit/)(System::SharedPtr\<SquareAnnotation\>) | Visitar/seleccionar anotación de cuadrado. |
| virtual [Visit](./visit/)(System::SharedPtr\<InkAnnotation\>) | Visitar/seleccionar anotación de tinta. |
| virtual [Visit](./visit/)(System::SharedPtr\<PolylineAnnotation\>) | Visitar/seleccionar anotación de polilínea. |
| virtual [Visit](./visit/)(System::SharedPtr\<PolygonAnnotation\>) | Visitar/seleccionar anotación de polígono. |
| virtual [Visit](./visit/)(System::SharedPtr\<CaretAnnotation\>) | Visitar/seleccionar anotación de cursor. |
| virtual [Visit](./visit/)(System::SharedPtr\<StampAnnotation\>) | Visitar/seleccionar anotación de sello. |
| virtual [Visit](./visit/)(System::SharedPtr\<WidgetAnnotation\>) | Visitar/seleccionar anotación de widget. |
| virtual [Visit](./visit/)(System::SharedPtr\<MovieAnnotation\>) | Visitar/seleccionar anotación de película. |
| virtual [Visit](./visit/)(System::SharedPtr\<ScreenAnnotation\>) | Visitar/seleccionar anotación de pantalla. |
| virtual [Visit](./visit/)(System::SharedPtr\<TrimMarkAnnotation\>) | Visitar/seleccionar una anotación de marca de recorte. |
| virtual [Visit](./visit/)(System::SharedPtr\<BleedMarkAnnotation\>) | Visitar/seleccionar una anotación de marca de sangrado. |
| virtual [Visit](./visit/)(System::SharedPtr\<RegistrationMarkAnnotation\>) | Visitar/seleccionar una anotación de marca de registro. |
| virtual [Visit](./visit/)(System::SharedPtr\<PageInformationAnnotation\>) | Visitar/seleccionar una anotación de información de página. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
