---
title: "Aspose::Pdf::Comparison::PdfOutputGenerator klass"
linktitle: "PdfOutputGenerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::PdfOutputGenerator klass. Representerar en klass för att generera PDF-representation av textskillnader i C++."
type: docs
weight: 1300
url: /sv/cpp/aspose.pdf.comparison/pdfoutputgenerator/
---
## PdfOutputGenerator class


Representerar en klass för att generera PDF‑representation av textskillnader.

```cpp
class PdfOutputGenerator : public Aspose::Pdf::Comparison::IFileOutputGenerator,
                           public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [PdfOutputGenerator](./pdfoutputgenerator/)() | Skapar en instans av [PdfOutputGenerator](./) klass. |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<PageInfo\>\&) | Skapar en instans av [PdfOutputGenerator](./) klass. |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&) | Skapar en instans av [PdfOutputGenerator](./) klass. |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&, const System::SharedPtr\<PageInfo\>\&) | Skapar en instans av [PdfOutputGenerator](./) klass. |
## Se även

* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
