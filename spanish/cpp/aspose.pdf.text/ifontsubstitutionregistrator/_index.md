---
title: "Clase Aspose::Pdf::Text::IFontSubstitutionRegistrator"
linktitle: "IFontSubstitutionRegistrator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::IFontSubstitutionRegistrator. Esta interfaz declara la funcionalidad necesaria para registrar sustituciones de fuentes en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf.text/ifontsubstitutionregistrator/
---
## IFontSubstitutionRegistrator class


Esta interfaz declara la funcionalidad necesaria para registrar sustituciones de fuentes.

```cpp
class IFontSubstitutionRegistrator : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetAllSubstitutions](./getallsubstitutions/)() | Este método debe devolver todas las sustituciones registradas para el documento actual. Añadido con fines de rastreo. |
| virtual [RegistrySubstitution](./registrysubstitution/)(System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::Data::ITrailerable\>) | Registrar sustitución para fuentes proporcionadas. Las fuentes se pasan como objetos IPdfFont en este método. |
| virtual [RegistrySubstitution](./registrysubstitution/)(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>, System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) | Registrar sustitución para fuentes que se representan mediante objetos FontDefinition. Este método se añadió por la necesidad de registrar sustituciones "implícitas" que tienen lugar en el objeto PdfFont. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
