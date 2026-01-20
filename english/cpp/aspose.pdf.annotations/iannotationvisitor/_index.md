---
title: Aspose::Pdf::Annotations::IAnnotationVisitor class
linktitle: IAnnotationVisitor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::IAnnotationVisitor class. Defines Visitor for visiting different document annotations in C++.'
type: docs
weight: 4900
url: /cpp/aspose.pdf.annotations/iannotationvisitor/
---
## IAnnotationVisitor class


Defines Visitor for visiting different document annotations.

```cpp
class IAnnotationVisitor : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Visit](./visit/)(System::SharedPtr\<LinkAnnotation\>) | Visit/select link annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<FileAttachmentAnnotation\>) | Visit/select attachment annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<TextAnnotation\>) | Visit/select text annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<FreeTextAnnotation\>) | Visit/select freetext annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<HighlightAnnotation\>) | Visit/select highlight annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<UnderlineAnnotation\>) | Visit/select underline annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<StrikeOutAnnotation\>) | Visit/select strikeOut annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<SquigglyAnnotation\>) | Visit/select squiggly annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<PopupAnnotation\>) | Visit/select popup annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<LineAnnotation\>) | Visit/select line annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<CircleAnnotation\>) | Visit/select circle annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<SquareAnnotation\>) | Visit/select square annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<InkAnnotation\>) | Visit/select ink annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<PolylineAnnotation\>) | Visit/select polyline annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<PolygonAnnotation\>) | Visit/select polygon annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<CaretAnnotation\>) | Visit/select caret annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<StampAnnotation\>) | Visit/select stamp annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<WidgetAnnotation\>) | Visit/select widget annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<MovieAnnotation\>) | Visit/select movie annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<ScreenAnnotation\>) | Visit/select screen annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<TrimMarkAnnotation\>) | Visit/select a trim mark annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<BleedMarkAnnotation\>) | Visit/select a bleed mark annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<RegistrationMarkAnnotation\>) | Visit/select a registration mark annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<PageInformationAnnotation\>) | Visit/select a page information annotation. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
