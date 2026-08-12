---
title: "Aspose::Pdf::Annotations::RichMediaAnnotation klass"
linktitle: "RichMediaAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::RichMediaAnnotation klass. Klassen beskriver RichMediaAnnotation som möjliggör inbäddning av video-/ljudinnehåll i PDF-dokument i C++."
type: docs
weight: 9700
url: /sv/cpp/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class


Klassen beskriver [RichMediaAnnotation](./) som möjliggör inbäddning av video-/ljudinnehåll i PDF-dokument.

```cpp
class RichMediaAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [ActivationEvent](./activationevent/) | Händelse som aktiverar annotationen. |
| [ContentType](./contenttype/) | Typ av multimedia. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökare för denna annotation. |
| [AddCustomData](./addcustomdata/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Lägg till anpassad namngiven data (till exempel som krävs för flash‑script). |
| [get_ActivateOn](./get_activateon/)() | Händelse som aktiverar applikationen. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Content](./get_content/)() | Data för Rich Media-innehållet. |
| [get_CustomFlashVariables](./get_customflashvariables/)() const | Ställer in eller hämtar flash-variabler som skickas till spelaren. |
| [get_CustomPlayer](./get_customplayer/)() const | Ställer in eller hämtar anpassad flash-spelare för att spela video-/ljuddata. |
| [get_Type](./get_type/)() | Hämtar innehållstyp. Möjliga värden: Audio, Video. |
| [RichMediaAnnotation](./richmediaannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Initierar [RichMediaAnnotation](./). |
| [set_ActivateOn](./set_activateon/)(RichMediaAnnotation::ActivationEvent) | Händelse som aktiverar applikationen. |
| [set_CustomFlashVariables](./set_customflashvariables/)(const System::String\&) | Ställer in eller hämtar flash-variabler som skickas till spelaren. |
| [set_CustomPlayer](./set_customplayer/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in eller hämtar anpassad flash-spelare för att spela video-/ljuddata. |
| [set_Type](./set_type/)(RichMediaAnnotation::ContentType) | Ställer in innehållstyp. Möjliga värden: Audio, Video. |
| [SetContent](./setcontent/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Ange innehållsström. |
| [SetPoster](./setposter/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ange poster för annoteringen. |
| [Update](./update/)() | Uppdaterar data med angivna parametrar. |
## Se även

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
