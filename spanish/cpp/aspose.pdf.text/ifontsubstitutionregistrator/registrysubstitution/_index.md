---
title: "Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution método"
linktitle: "RegistrySubstitution"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution método. Registra una sustitución para fuentes que están representadas mediante objetos FontDefinition. Este método se añadió por la necesidad de registrar sustituciones \\\"implicit\\\" que tienen lugar en el objeto PdfFont en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.text/ifontsubstitutionregistrator/registrysubstitution/
---
## IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>, System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) method


Registrar sustitución para fuentes que se representan mediante objetos FontDefinition. Este método se añadió por la necesidad de registrar sustituciones "implícitas" que tienen lugar en el objeto PdfFont.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr<Aspose::Font::Sources::FontDefinition> oldFontDef, System::SharedPtr<Aspose::Font::Sources::FontDefinition> newFontDef)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldFontDef | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | [Font](../../font/) definición para la fuente original |
| newFontDef | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | [Font](../../font/) definición para la nueva fuente |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSubstitutionRegistrator](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::Data::ITrailerable\>) method


Registrar sustitución para fuentes proporcionadas. Las fuentes se pasan como objetos IPdfFont en este método.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionRegistrator::RegistrySubstitution(System::SharedPtr<Engine::CommonData::Text::Fonts::IPdfFont> oldFont, System::SharedPtr<Engine::CommonData::Text::Fonts::IPdfFont> newFont, System::SharedPtr<Engine::Data::ITrailerable> trailerable)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldFont | System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\> | fuente original |
| newFont | System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\> | nueva fuente que reemplaza una fuente original |
| trailerable | System::SharedPtr\<Engine::Data::ITrailerable\> | trailerable |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSubstitutionRegistrator](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
