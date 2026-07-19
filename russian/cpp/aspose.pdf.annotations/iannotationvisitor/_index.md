---
title: "Aspose::Pdf::Annotations::IAnnotationVisitor класс"
linktitle: "IAnnotationVisitor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::IAnnotationVisitor класс. Определяет Visitor для обхода различных аннотаций документа в C++."
type: docs
weight: 4900
url: /ru/cpp/aspose.pdf.annotations/iannotationvisitor/
---
## IAnnotationVisitor class


Определяет Visitor для обхода различных аннотаций документа.

```cpp
class IAnnotationVisitor : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Visit](./visit/)(System::SharedPtr\<LinkAnnotation\>) | Посетить/выбрать аннотацию ссылки. |
| virtual [Visit](./visit/)(System::SharedPtr\<FileAttachmentAnnotation\>) | Посетить/выбрать аннотацию вложения. |
| virtual [Visit](./visit/)(System::SharedPtr\<TextAnnotation\>) | Посетить/выбрать текстовую аннотацию. |
| virtual [Visit](./visit/)(System::SharedPtr\<FreeTextAnnotation\>) | Посетить/выбрать аннотацию свободного текста. |
| virtual [Visit](./visit/)(System::SharedPtr\<HighlightAnnotation\>) | Посетить/выбрать аннотацию выделения. |
| virtual [Visit](./visit/)(System::SharedPtr\<UnderlineAnnotation\>) | Посетить/выбрать аннотацию подчеркивания. |
| virtual [Visit](./visit/)(System::SharedPtr\<StrikeOutAnnotation\>) | Посетить/выбрать аннотацию зачеркивания. |
| virtual [Visit](./visit/)(System::SharedPtr\<SquigglyAnnotation\>) | Посетить/выбрать аннотацию волнистого подчеркивания. |
| virtual [Visit](./visit/)(System::SharedPtr\<PopupAnnotation\>) | Посетить/выбрать всплывающую аннотацию. |
| virtual [Visit](./visit/)(System::SharedPtr\<LineAnnotation\>) | Посетить/выбрать линейную аннотацию. |
| virtual [Visit](./visit/)(System::SharedPtr\<CircleAnnotation\>) | Посетить/выбрать круговую аннотацию. |
| virtual [Visit](./visit/)(System::SharedPtr\<SquareAnnotation\>) | Посетить/выбрать квадратную аннотацию. |
| virtual [Visit](./visit/)(System::SharedPtr\<InkAnnotation\>) | Посетить/выбрать аннотацию чернил. |
| virtual [Visit](./visit/)(System::SharedPtr\<PolylineAnnotation\>) | Посетить/выбрать аннотацию полилинии. |
| virtual [Visit](./visit/)(System::SharedPtr\<PolygonAnnotation\>) | Посетить/выбрать аннотацию многоугольника. |
| virtual [Visit](./visit/)(System::SharedPtr\<CaretAnnotation\>) | Посетить/выбрать аннотацию каретки. |
| virtual [Visit](./visit/)(System::SharedPtr\<StampAnnotation\>) | Посетить/выбрать аннотацию штампа. |
| virtual [Visit](./visit/)(System::SharedPtr\<WidgetAnnotation\>) | Посетить/выбрать аннотацию виджета. |
| virtual [Visit](./visit/)(System::SharedPtr\<MovieAnnotation\>) | Посетить/выбрать аннотацию фильма. |
| virtual [Visit](./visit/)(System::SharedPtr\<ScreenAnnotation\>) | Посетить/выбрать аннотацию экрана. |
| virtual [Visit](./visit/)(System::SharedPtr\<TrimMarkAnnotation\>) | Посетить/выбрать аннотацию метки обрезки. |
| virtual [Visit](./visit/)(System::SharedPtr\<BleedMarkAnnotation\>) | Посетить/выбрать аннотацию метки вырезки. |
| virtual [Visit](./visit/)(System::SharedPtr\<RegistrationMarkAnnotation\>) | Посетить/выбрать аннотацию регистрационной метки. |
| virtual [Visit](./visit/)(System::SharedPtr\<PageInformationAnnotation\>) | Посетить/выбрать аннотацию информации о странице. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
