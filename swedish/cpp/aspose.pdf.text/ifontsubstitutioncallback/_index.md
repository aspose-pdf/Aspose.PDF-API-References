---
title: "Aspose::Pdf::Text::IFontSubstitutionCallback-klass"
linktitle: "IFontSubstitutionCallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::IFontSubstitutionCallback-klass. Detta gränssnitt deklarerar en återuppringningsmekanism för att skicka aviseringar i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf.text/ifontsubstitutioncallback/
---
## IFontSubstitutionCallback class


Detta gränssnitt deklarerar en återuppringningsmekanism för att skicka aviseringar.

```cpp
class IFontSubstitutionCallback : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_NotifyAboutFontSubstitutions](./get_notifyaboutfontsubstitutions/)() | Returnerar true om teckensnittssubstitutioner är aktiverade. |
| virtual [get_Registrar](./get_registrar/)() | IRegistrar för det aktuella dokumentet. |
| virtual [NotifyAboutSubstitution](./notifyaboutsubstitution/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>, System::SharedPtr\<Aspose::Pdf::Text::Font\>) | Skickar en avisering om teckensnittssubstitution via händelsemekanism. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
