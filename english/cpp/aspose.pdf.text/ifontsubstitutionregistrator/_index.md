---
title: Aspose::Pdf::Text::IFontSubstitutionRegistrator class
linktitle: IFontSubstitutionRegistrator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::IFontSubstitutionRegistrator class. This interface declares necessary functionality for register font substitutions in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf.text/ifontsubstitutionregistrator/
---
## IFontSubstitutionRegistrator class


This interface declares necessary functionality for register font substitutions.

```cpp
class IFontSubstitutionRegistrator : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetAllSubstitutions](./getallsubstitutions/)() | This method must return all the substitutions registered for current document. Added for trace objectives. |
| virtual [RegistrySubstitution](./registrysubstitution/)(System::SharedPtr\<Aspose::Pdf::Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Aspose::Pdf::Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Aspose::Pdf::Engine::Data::ITrailerable\>) | Register substitution for passed fonts. Fonts passed as IPdfFont objects in this method. |
| virtual [RegistrySubstitution](./registrysubstitution/)(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>, System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) | Register substitution for fonts which are represented via FontDefinition objects. This method was added due to necessity to register "implicit" substitutions which have place in PdfFont object. |
## See Also

* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
