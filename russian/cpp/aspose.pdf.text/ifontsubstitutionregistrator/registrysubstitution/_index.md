---
title: "Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution метод"
linktitle: "RegistrySubstitution"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution. Регистрирует замену шрифтов, представленных объектами FontDefinition. Этот метод был добавлен из‑за необходимости регистрировать \\\"неявные\\\" замены, которые находятся в объекте PdfFont в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.text/ifontsubstitutionregistrator/registrysubstitution/
---
## IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>, System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) method


Регистрировать замену для шрифтов, представленных объектами FontDefinition. Этот метод был добавлен из‑за необходимости регистрировать "неявные" замены, которые находятся в объекте PdfFont.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr<Aspose::Font::Sources::FontDefinition> oldFontDef, System::SharedPtr<Aspose::Font::Sources::FontDefinition> newFontDef)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| oldFontDef | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | [Font](../../font/) определение оригинального шрифта |
| newFontDef | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | [Font](../../font/) определение нового шрифта |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSubstitutionRegistrator](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::Data::ITrailerable\>) method


Регистрировать замену для переданных шрифтов. Шрифты передаются как объекты IPdfFont в этом методе.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr<Engine::CommonData::Text::Fonts::IPdfFont> oldFont, System::SharedPtr<Engine::CommonData::Text::Fonts::IPdfFont> newFont, System::SharedPtr<Engine::Data::ITrailerable> trailerable)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| oldFont | System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\> | оригинальный шрифт |
| newFont | System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\> | новый шрифт, заменяющий оригинальный шрифт |
| trailerable | System::SharedPtr\<Engine::Data::ITrailerable\> | trailerable |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSubstitutionRegistrator](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
