---
title: Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute method
linktitle: TrySubstitute
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute method. Substitutes original font with another font in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase::TrySubstitute method


Substitutes original font with another font.

```cpp
virtual bool Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute(System::SharedPtr<CustomFontSubstitutionBase::OriginalFontSpecification> originalFontSpecification, System::SharedPtr<Font> &substitutionFont)
```


| Parameter | Type | Description |
| --- | --- | --- |
| originalFontSpecification | System::SharedPtr\<CustomFontSubstitutionBase::OriginalFontSpecification\> | Original font specification. |
| substitutionFont | System::SharedPtr\<Font\>\& | Substitution font. |

### ReturnValue

True in case substitution was successfull.
## Remarks


The class [CustomFontSubstitutionBase](../) should be inherited to implement custom font substitution logic. TrySubstitute method should be overridden properly:

Must return true in case substitution is required. substitutionFont must be set to valid [Font](../../font/) object. Must return false in case no substitution is required. substitutionFont may be set to null. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [OriginalFontSpecification](../originalfontspecification/)
* Class [Font](../../font/)
* Class [CustomFontSubstitutionBase](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
