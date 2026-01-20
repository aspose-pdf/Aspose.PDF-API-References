---
title: Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable method
linktitle: get_IsSubstitutionUnavoidable
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable method. Gets a value that indicates that the substitution is unavoidable in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.text/customfontsubstitutionbase/originalfontspecification/get_issubstitutionunavoidable/
---
## OriginalFontSpecification::get_IsSubstitutionUnavoidable method


Gets a value that indicates that the substitution is unavoidable.

```cpp
bool Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable() const
```

## Remarks


Returns true in case substitution was requested because of absence of the original font or in case original font cannot be used in context of some task. In case user ignores the flag and doesn't substitute the font - default font substitution procedure is performed. But it provides opportunity for the user to alternate standard font substitution procedure and set better font to the system.

Returns false in case original font is present, valid, but it is allowed for the user to substitute it. 
## See Also

* Class [OriginalFontSpecification](../)
* Class [CustomFontSubstitutionBase](../../)
* Namespace [Aspose::Pdf::Text](../../../)
* Library [Aspose.PDF for C++](../../../../)
