---
title: "Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution method"
linktitle: "RegistrySubstitution"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution metod. Registrera ersättning för typsnitt som representeras via FontDefinition-objekt. Denna metod lades till på grund av behovet att registrera \\\"implicita\\\" ersättningar som har plats i PdfFont-objekt i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.text/ifontsubstitutionregistrator/registrysubstitution/
---
## IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>, System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) method


Registrera substitution för teckensnitt som representeras via FontDefinition-objekt. Denna metod lades till på grund av behovet att registrera \"implicita\" substitutioner som har plats i PdfFont-objekt.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr<Aspose::Font::Sources::FontDefinition> oldFontDef, System::SharedPtr<Aspose::Font::Sources::FontDefinition> newFontDef)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldFontDef | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | [Font](../../font/) definition för originaltypsnitt |
| newFontDef | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | [Font](../../font/) definition för nytt typsnitt |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSubstitutionRegistrator](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::Data::ITrailerable\>) method


Registrera substitution för överförda teckensnitt. Teckensnitt överförs som IPdfFont-objekt i denna metod.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr<Engine::CommonData::Text::Fonts::IPdfFont> oldFont, System::SharedPtr<Engine::CommonData::Text::Fonts::IPdfFont> newFont, System::SharedPtr<Engine::Data::ITrailerable> trailerable)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldFont | System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\> | originalt typsnitt |
| newFont | System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\> | nytt typsnitt som ersätter ett originaltypsnitt |
| trailerable | System::SharedPtr\<Engine::Data::ITrailerable\> | trailerable |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSubstitutionRegistrator](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
