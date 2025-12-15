---
title: Aspose::Pdf::PdfANonSpecificationFlags class
linktitle: PdfANonSpecificationFlags
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfANonSpecificationFlags class. This class holds flags to control PDF/A conversion for cases when source PDF document doesn''t correspond to PDF specification. If flags of this clas are used it decreases performance but it''s necessary when source PDF document can''t be convert into PDF/A format by usual way. By default all flags are set to false in C++.'
type: docs
weight: 15000
url: /cpp/aspose.pdf/pdfanonspecificationflags/
---
## PdfANonSpecificationFlags class


This class holds flags to control PDF/A conversion for cases when source PDF document doesn't correspond to PDF specification. If flags of this clas are used it decreases performance but it's necessary when source PDF document can't be convert into PDF/A format by usual way. By default all flags are set to false.

```cpp
class PdfANonSpecificationFlags : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_CheckDifferentNamesInFontDictionaries](./get_checkdifferentnamesinfontdictionaries/)() const | Some PDF documents contain fonts which have different names in internal data. Use of this flag enforces special processing logic for cases when fields BaseFont and FontDescriptor.FontName are different. |
| [PdfANonSpecificationFlags](./pdfanonspecificationflags/)() | Constructor. |
| [set_CheckDifferentNamesInFontDictionaries](./set_checkdifferentnamesinfontdictionaries/)(bool) | Some PDF documents contain fonts which have different names in internal data. Use of this flag enforces special processing logic for cases when fields BaseFont and FontDescriptor.FontName are different. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
