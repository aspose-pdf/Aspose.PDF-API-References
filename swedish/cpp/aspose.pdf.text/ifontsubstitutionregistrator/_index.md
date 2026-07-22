---
title: "Aspose::Pdf::Text::IFontSubstitutionRegistrator klass"
linktitle: "IFontSubstitutionRegistrator"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::IFontSubstitutionRegistrator klass. Detta gränssnitt deklarerar nödvändig funktionalitet för att registrera teckensnittssubstitutioner i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf.text/ifontsubstitutionregistrator/
---
## IFontSubstitutionRegistrator class


Detta gränssnitt deklarerar nödvändig funktionalitet för att registrera teckensnittssubstitutioner.

```cpp
class IFontSubstitutionRegistrator : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetAllSubstitutions](./getallsubstitutions/)() | Denna metod måste returnera alla substitutioner som registrerats för det aktuella dokumentet. Tillagd för spårningsändamål. |
| virtual [RegistrySubstitution](./registrysubstitution/)(System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::Data::ITrailerable\>) | Registrera substitution för överförda teckensnitt. Teckensnitt överförs som IPdfFont-objekt i denna metod. |
| virtual [RegistrySubstitution](./registrysubstitution/)(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>, System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) | Registrera substitution för teckensnitt som representeras via FontDefinition-objekt. Denna metod lades till på grund av behovet att registrera \"implicita\" substitutioner som har plats i PdfFont-objekt. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
