---
title: "Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute método"
linktitle: "TrySubstitute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute método. Sustituye la fuente original por otra fuente en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase::TrySubstitute method


Sustituye la fuente original por otra fuente.

```cpp
virtual bool Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute(System::SharedPtr<CustomFontSubstitutionBase::OriginalFontSpecification> originalFontSpecification, System::SharedPtr<Font> &substitutionFont)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| originalFontSpecification | System::SharedPtr\<CustomFontSubstitutionBase::OriginalFontSpecification\> | Especificación de fuente original. |
| substitutionFont | System::SharedPtr\<Font\>\& | Fuente de sustitución. |

### ReturnValue

Verdadero en caso de que la sustitución haya sido exitosa.
## Observaciones


La clase [CustomFontSubstitutionBase](../) debe heredarse para implementar la lógica de sustitución de fuentes personalizada. El método TrySubstitute debe sobrescribirse correctamente:

Debe devolver verdadero en caso de que se requiera la sustitución. substitutionFont debe establecerse a un objeto [Font](../../font/) válido. Debe devolver falso en caso de que no se requiera sustitución. substitutionFont puede establecerse a null.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [OriginalFontSpecification](../originalfontspecification/)
* Class [Font](../../font/)
* Class [CustomFontSubstitutionBase](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
