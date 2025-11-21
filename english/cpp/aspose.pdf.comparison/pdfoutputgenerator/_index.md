---
title: Aspose::Pdf::Comparison::PdfOutputGenerator class
linktitle: PdfOutputGenerator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::PdfOutputGenerator class. Represents a class for generating PDF representation of texts differences in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf.comparison/pdfoutputgenerator/
---
## PdfOutputGenerator class


Represents a class for generating PDF representation of texts differences.

```cpp
class PdfOutputGenerator : public Aspose::Pdf::Comparison::IFileOutputGenerator,
                           public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Methods

| Method | Description |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Generates the output based on the differences between texts and saves it to a file. |
| [PdfOutputGenerator](./pdfoutputgenerator/)() | Cteates an instance of [PdfOutputGenerator](./) class. |
| [PdfOutputGenerator](./pdfoutputgenerator/)(System::SharedPtr\<PageInfo\>) | Cteates an instance of [PdfOutputGenerator](./) class. |
| [PdfOutputGenerator](./pdfoutputgenerator/)(System::SharedPtr\<OutputTextStyle\>) | Cteates an instance of [PdfOutputGenerator](./) class. |
| [PdfOutputGenerator](./pdfoutputgenerator/)(System::SharedPtr\<OutputTextStyle\>, System::SharedPtr\<PageInfo\>) | Cteates an instance of [PdfOutputGenerator](./) class. |
## See Also

* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
