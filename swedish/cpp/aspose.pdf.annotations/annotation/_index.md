---
title: "Aspose::Pdf::Annotations::Annotation-klass"
linktitle: "Annotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::Annotation-klass. Klass som representerar annoteringsobjekt i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.annotations/annotation/
---
## Annotation class


Klass som representerar annoteringsobjekt.

```cpp
class Annotation : public Aspose::Pdf::BaseParagraph
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) | Accepterar besökare för annoteringsbearbetning. |
| virtual [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| virtual [Flatten](./flatten/)() | Placera annoteringsinnehåll direkt på sidan, annoteringsobjektet kommer att tas bort. |
| [get_Actions](./get_actions/)() | Hämtar lista över annoteringsåtgärder. |
| virtual [get_ActiveState](./get_activestate/)() | Hämtar aktuellt annoteringsutseende. |
| [get_Alignment](./get_alignment/)() | [Annotation](./) justering. Denna egenskap är föråldrad. Använd HorizontalAligment istället. |
| virtual [get_AnnotationType](./get_annotationtype/)() | Hämtar typ av annotation. |
| [get_Appearance](./get_appearance/)() | Hämtar utseendedictionary för annoteringen. |
| [get_Border](./get_border/)() const | Hämtar annoteringskantens egenskaper. [Border](../border/) |
| [get_Characteristics](./get_characteristics/)() | Hämtar annoteringsegenskaper. |
| [get_Color](./get_color/)() | Hämtar annoteringsfärg. |
| [get_Contents](./get_contents/)() | Hämtar annoteringstext. |
| [get_Flags](./get_flags/)() | Flaggor för annoteringen. |
| [get_FullName](./get_fullname/)() | Hämtar fullt kvalificerat namn för annoteringen. |
| virtual [get_Height](./get_height/)() | Hämtar höjd på annoteringen. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Hämtar textjustering för annoteringen. |
| [get_Modified](./get_modified/)() | Hämtar datum och tid då annoteringen senast ändrades. |
| [get_Name](./get_name/)() | Hämtar annoteringsnamn på sidan. |
| virtual [get_PageIndex](./get_pageindex/)() | Hämtar sidindex som innehåller annoteringen. |
| virtual [get_Rect](./get_rect/)() | Hämtar annoteringsrektangel. |
| [get_States](./get_states/)() | Hämtar utseendedictionary för annoteringen. |
| [get_TextHorizontalAlignment](./get_texthorizontalalignment/)() | Hämtar textjustering för annoteringen. |
| static [get_UpdateAppearanceOnConvert](./get_updateappearanceonconvert/)() | Om sant uppdateras annoteringens utseende innan PF-dokumentet konverteras till bild. Detta möjliggör korrekt konvertering av fält men kräver sannolikt mer tid. |
| static [get_UseFontSubset](./get_usefontsubset/)() | Om den här egenskapen sätts till sant kommer teckensnitt att läggas till dokumentet som delmängder. Standardvärdet är sant. |
| virtual [get_Width](./get_width/)() | Hämtar bredden på annoteringen. |
| [GetRectangle](./getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| virtual [set_ActiveState](./set_activestate/)(System::String) | Ställer in aktuellt annoteringsutseende. |
| [set_Alignment](./set_alignment/)(TextAlignment) | [Annotation](./) justering. Denna egenskap är föråldrad. Använd HorizontalAligment istället. |
| [set_Border](./set_border/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Border\>\&) | Ställer in annoteringens kantegenskaper. [Border](../border/) |
| [set_Color](./set_color/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Ställer in annoteringens färg. |
| [set_Contents](./set_contents/)(const System::String\&) | Ställer in annoteringens text. |
| [set_Flags](./set_flags/)(AnnotationFlags) | Flaggor för annoteringen. |
| virtual [set_Height](./set_height/)(double) | Ställer in höjden på annoteringen. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Ställer in textjustering för annoteringen. |
| [set_Modified](./set_modified/)(System::DateTime) | Ställer in datum och tid då annoteringen senast ändrades. |
| [set_Name](./set_name/)(const System::String\&) | Ställer in annoteringens namn på sidan. |
| virtual [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) | Ställer in annoteringens rektangel. |
| [set_TextHorizontalAlignment](./set_texthorizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Ställer in textjustering för annoteringen. |
| static [set_UpdateAppearanceOnConvert](./set_updateappearanceonconvert/)(bool) | Om sant uppdateras annoteringens utseende innan PF-dokumentet konverteras till bild. Detta möjliggör korrekt konvertering av fält men kräver sannolikt mer tid. |
| static [set_UseFontSubset](./set_usefontsubset/)(bool) | Om den här egenskapen sätts till sant kommer teckensnitt att läggas till dokumentet som delmängder. Standardvärdet är sant. |
| virtual [set_Width](./set_width/)(double) | Ställer in bredden på annoteringen. |
## Se även

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
