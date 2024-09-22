---
title: Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution method
linktitle: RegistrySubstitution
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution method. Register substitution for fonts which are represented via FontDefinition objects. This method was added due to necessity to register "implicit" substitutions which have place in PdfFont object in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.text/ifontsubstitutionregistrator/registrysubstitution/
---
## IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>, System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) method


Register substitution for fonts which are represented via FontDefinition objects. This method was added due to necessity to register "implicit" substitutions which have place in PdfFont object.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr<Aspose::Font::Sources::FontDefinition> oldFontDef, System::SharedPtr<Aspose::Font::Sources::FontDefinition> newFontDef)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| oldFontDef | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | [Font](../../font/) definition for original font |
| newFontDef | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | [Font](../../font/) definition for new font |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSubstitutionRegistrator](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr\<Aspose::Pdf::Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Aspose::Pdf::Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Aspose::Pdf::Engine::Data::ITrailerable\>) method


Register substitution for passed fonts. Fonts passed as IPdfFont objects in this method.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr<Aspose::Pdf::Engine::CommonData::Text::Fonts::IPdfFont> oldFont, System::SharedPtr<Aspose::Pdf::Engine::CommonData::Text::Fonts::IPdfFont> newFont, System::SharedPtr<Aspose::Pdf::Engine::Data::ITrailerable> trailerable)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| oldFont | System::SharedPtr\<Aspose::Pdf::Engine::CommonData::Text::Fonts::IPdfFont\> | original font |
| newFont | System::SharedPtr\<Aspose::Pdf::Engine::CommonData::Text::Fonts::IPdfFont\> | new font which replaces an original font |
| trailerable | System::SharedPtr\<Aspose::Pdf::Engine::Data::ITrailerable\> | trailerable |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSubstitutionRegistrator](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
