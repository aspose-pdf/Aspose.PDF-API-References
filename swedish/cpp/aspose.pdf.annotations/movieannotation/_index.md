---
title: "Aspose::Pdf::Annotations::MovieAnnotation klass"
linktitle: "MovieAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::MovieAnnotation klass. Representerar en filmanteckning som innehåller animerad grafik och ljud som ska visas på datorskärmen och genom högtalarna. När anteckningen aktiveras spelas filmen upp i C++."
type: docs
weight: 6700
url: /sv/cpp/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class


Representerar en filmanteckning som innehåller animerad grafik och ljud som ska visas på datorskärmen och genom högtalarna. När anteckningen aktiveras spelas filmen.

```cpp
class MovieAnnotation : public Aspose::Pdf::Annotations::Annotation,
                        public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Aspect](./get_aspect/)() | Hämtar bredden och höjden på filmens omgivningsruta, i pixlar. |
| [get_File](./get_file/)() | Hämtar en filspecificering som identifierar en självbeskrivande filmfil. |
| [get_Poster](./get_poster/)() | Hämtar en flagga eller ström som anger om och hur en affischbild som representerar filmen ska visas. Om true hämtas affischbilden från filmfilen; om den är false visas ingen affisch. |
| [get_Rotate](./get_rotate/)() | Hämtar antalet grader som filmen ska roteras medurs i förhållande till sidan. Värdet ska vara en multipel av 90. |
| [get_Title](./get_title/)() override | Hämtar titeln på filmanteckningen. |
| [MovieAnnotation](./movieannotation/)(const System::SharedPtr\<Document\>\&, const System::String\&) | Konstruktor för användning med Generator. |
| [MovieAnnotation](./movieannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Skapar en ny ljudanteckning på den angivna sidan. |
| [set_Aspect](./set_aspect/)(const System::SharedPtr\<Point\>\&) | Ställer in bredden och höjden på filmens omgivningsruta, i pixlar. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | Ställer in en filspecificering som identifierar en självbeskrivande filmfil. |
| [set_Poster](./set_poster/)(bool) | Ställer in en flagga eller ström som anger om och hur en affischbild som representerar filmen ska visas. Om true hämtas affischbilden från filmfilen; om den är false visas ingen affisch. |
| [set_Rotate](./set_rotate/)(int32_t) | Ställer in antalet grader som filmen ska roteras medurs i förhållande till sidan. Värdet ska vara en multipel av 90. |
| [set_Title](./set_title/)(System::String) override | Ställer in titeln på filmanteckningen. |
## Se även

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
