---
title: "Aspose::Pdf::Annotations::IAnnotationVisitor class"
linktitle: "IAnnotationVisitor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::IAnnotationVisitor class. Definierar Visitor för att besöka olika dokumentannotationer i C++."
type: docs
weight: 4900
url: /sv/cpp/aspose.pdf.annotations/iannotationvisitor/
---
## IAnnotationVisitor class


Definierar Visitor för att besöka olika dokumentanteckningar.

```cpp
class IAnnotationVisitor : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Visit](./visit/)(System::SharedPtr\<LinkAnnotation\>) | Besök/välj länkannotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<FileAttachmentAnnotation\>) | Besök/välj attachment annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<TextAnnotation\>) | Besök/välj textannotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<FreeTextAnnotation\>) | Besök/välj freetext-annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<HighlightAnnotation\>) | Besök/välj highlight-annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<UnderlineAnnotation\>) | Besök/välj understruken annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<StrikeOutAnnotation\>) | Besök/välj genomstruken annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<SquigglyAnnotation\>) | Besök/välj slingrande annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<PopupAnnotation\>) | Besök/välj popup annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<LineAnnotation\>) | Besök/välj linje annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<CircleAnnotation\>) | Besök/välj cirkulär annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<SquareAnnotation\>) | Besök/välj fyrkantig annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<InkAnnotation\>) | Besök/välj bläckannotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<PolylineAnnotation\>) | Besök/välj polylinje annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<PolygonAnnotation\>) | Besök/välj polygon annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<CaretAnnotation\>) | Besök/välj insättningsmarkör annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<StampAnnotation\>) | Besök/välj stämpel annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<WidgetAnnotation\>) | Besök/välj widget annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<MovieAnnotation\>) | Besök/välj film annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<ScreenAnnotation\>) | Besök/välj skärm annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<TrimMarkAnnotation\>) | Besök/välj en trimmarkering annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<BleedMarkAnnotation\>) | Besök/välj en blödningsmarkering annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<RegistrationMarkAnnotation\>) | Besök/välj en registreringsmarkering annotation. |
| virtual [Visit](./visit/)(System::SharedPtr\<PageInformationAnnotation\>) | Besök/välj en sidinformation annotation. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
