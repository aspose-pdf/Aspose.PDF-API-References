---
title: "Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable método"
linktitle: "get_IsSubstitutionUnavoidable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable método. Obtiene un valor que indica que la sustitución es inevitable en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.text/customfontsubstitutionbase/originalfontspecification/get_issubstitutionunavoidable/
---
## OriginalFontSpecification::get_IsSubstitutionUnavoidable method


Obtiene un valor que indica que la sustitución es inevitable.

```cpp
bool Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable() const
```

## Observaciones


Devuelve true en caso de que la sustitución se haya solicitado debido a la ausencia de la fuente original o en caso de que la fuente original no pueda usarse en el contexto de alguna tarea. Si el usuario ignora la bandera y no sustituye la fuente, se ejecuta el procedimiento de sustitución de fuentes predeterminado. Pero brinda la oportunidad al usuario de alternar el procedimiento estándar de sustitución de fuentes y establecer una fuente mejor en el sistema.

Devuelve false en caso de que la fuente original esté presente, sea válida, pero se permita al usuario sustituirla.
## Ver también

* Class [OriginalFontSpecification](../)
* Class [CustomFontSubstitutionBase](../../)
* Namespace [Aspose::Pdf::Text](../../../)
* Library [Aspose.PDF for C++](../../../../)
