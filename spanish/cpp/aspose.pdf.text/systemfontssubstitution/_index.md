---
title: "Aspose::Pdf::Text::SystemFontsSubstitution clase"
linktitle: "SystemFontsSubstitution"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::SystemFontsSubstitution clase. Representa una clase para la estrategia de sustitución de fuentes que sustituye fuentes por fuentes del sistema en C++."
type: docs
weight: 3200
url: /es/cpp/aspose.pdf.text/systemfontssubstitution/
---
## SystemFontsSubstitution class


Representa una clase para la estrategia de sustitución de fuentes que sustituye fuentes por fuentes del sistema.

```cpp
class SystemFontsSubstitution : public Aspose::Pdf::Text::FontSubstitution
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_DefaultFont](./get_defaultfont/)() | Obtiene la fuente de sustitución predeterminada. La fuente se usa cuando no se encontró ninguna otra sustitución válida pero la fuente inicial pertenece a la categoría de sustitución objetivo ([FontCategories](../)). |
| [get_FontCategories](./get_fontcategories/)() const | Obtiene las categorías de fuentes de sustitución que deben ser sustituidas por fuentes del sistema. |
| [set_DefaultFont](./set_defaultfont/)(const System::SharedPtr\<Font\>\&) | Establece la fuente de sustitución predeterminada. La fuente se usa cuando no se encontró ninguna otra sustitución válida pero la fuente inicial pertenece a la categoría de sustitución objetivo ([FontCategories](../)). |
| [set_FontCategories](./set_fontcategories/)(SubstitutionFontCategories) | Establece las categorías de fuentes de sustitución que deben ser sustituidas por fuentes del sistema. |
| [SystemFontsSubstitution](./systemfontssubstitution/)(SubstitutionFontCategories) | Inicializa una nueva instancia de la clase [SystemFontsSubstitution](./). |
## Ver también

* Class [FontSubstitution](../fontsubstitution/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
