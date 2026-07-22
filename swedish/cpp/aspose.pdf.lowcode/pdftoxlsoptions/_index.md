---
title: "Aspose::Pdf::LowCode::PdfToXlsOptions-klass"
linktitle: "PdfToXlsOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfToXlsOptions-klass. Representerar PDF‑till‑XLSX‑konverterarens alternativ för XlsConverter‑plugin i C++."
type: docs
weight: 6600
url: /sv/cpp/aspose.pdf.lowcode/pdftoxlsoptions/
---
## PdfToXlsOptions class


Representerar PDF‑till‑XLSX‑konverterarens alternativ för [XlsConverter](../xlsconverter/)‑plugin.

```cpp
class PdfToXlsOptions : public Aspose::Pdf::LowCode::PdfConverterOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [ExcelFormat](./excelformat/) | Tillåter att ange filformatet .xlsx, .xls/xml eller csv. Standardvärdet är XLSX. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Format](./get_format/)() const | Utdataformat. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Sätt true om du behöver infoga en tom kolumn som den första kolumnen i kalkylbladet. Standardvärdet är false; det betyder att den tomma kolumnen inte kommer att infogas. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Sätt true om du behöver minimera antalet kalkylblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF‑sida sparas som ett separat kalkylblad. |
| [get_OperationName](./get_operationname/)() override | Hämtar namn på operationen. |
| [PdfToXlsOptions](./pdftoxlsoptions/)() | Initierar en ny instans av objektet [PdfToXlsOptions](./) med standardalternativ. |
| [set_Format](./set_format/)(PdfToXlsOptions::ExcelFormat) | Utdataformat. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Sätt true om du behöver infoga en tom kolumn som den första kolumnen i kalkylbladet. Standardvärdet är false; det betyder att den tomma kolumnen inte kommer att infogas. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Sätt true om du behöver minimera antalet kalkylblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF‑sida sparas som ett separat kalkylblad. |
## Se även

* Class [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
