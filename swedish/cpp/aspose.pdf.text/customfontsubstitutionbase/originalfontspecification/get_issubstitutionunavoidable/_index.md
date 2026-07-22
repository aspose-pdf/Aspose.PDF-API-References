---
title: "Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable method"
linktitle: "get_IsSubstitutionUnavoidable"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable method. Hämtar ett värde som indikerar att ersättningen är oundviklig i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.text/customfontsubstitutionbase/originalfontspecification/get_issubstitutionunavoidable/
---
## OriginalFontSpecification::get_IsSubstitutionUnavoidable method


Hämtar ett värde som indikerar att ersättningen är oundviklig.

```cpp
bool Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable() const
```

## Anmärkningar


Returnerar true om ersättningen begärdes på grund av avsaknad av originalteckensnittet eller om originalteckensnittet inte kan användas i samband med någon uppgift. Om användaren ignorerar flaggan och inte ersätter teckensnittet - utförs standardproceduren för teckensnittsersättning. Men det ger möjlighet för användaren att byta standardproceduren för teckensnittsersättning och ange ett bättre teckensnitt till systemet.

Returnerar false om originalteckensnittet är närvarande, giltigt, men det är tillåtet för användaren att ersätta det.
## Se även

* Class [OriginalFontSpecification](../)
* Class [CustomFontSubstitutionBase](../../)
* Namespace [Aspose::Pdf::Text](../../../)
* Library [Aspose.PDF for C++](../../../../)
