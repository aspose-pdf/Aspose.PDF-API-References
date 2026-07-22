---
title: "Aspose::Pdf::ExcelSaveOptions klass"
linktitle: "ExcelSaveOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ExcelSaveOptions klass. Spara alternativ för export till Excel-format i C++."
type: docs
weight: 4700
url: /sv/cpp/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class


Spara alternativ för export till Excel-format.

```cpp
class ExcelSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [ExcelFormat](./excelformat/) | Tillåter att specificera .xlsx-, .xls/xml- eller csv-filformat. Standardvärdet är XLSX;. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ExcelSaveOptions](./excelsaveoptions/)() | Konstruktor. |
| [get_Format](./get_format/)() const | Utdataformat. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Sätt true om du behöver infoga en tom kolumn som den första kolumnen i kalkylbladet. Standardvärdet är false; det betyder att den tomma kolumnen inte kommer att infogas. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Sätt true om du behöver minimera antalet kalkylblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF‑sida sparas som ett separat kalkylblad. |
| [get_UniformWorksheets](./get_uniformworksheets/)() const | Sätt till true för att använda enhetlig kolumnindelning i hela dokumentet. Standardvärdet är false; det betyder att kolumnindelning kommer att vara oberoende för varje sida. |
| [set_Format](./set_format/)(ExcelSaveOptions::ExcelFormat) | Utdataformat. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Sätt true om du behöver infoga en tom kolumn som den första kolumnen i kalkylbladet. Standardvärdet är false; det betyder att den tomma kolumnen inte kommer att infogas. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Sätt true om du behöver minimera antalet kalkylblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF‑sida sparas som ett separat kalkylblad. |
| [set_UniformWorksheets](./set_uniformworksheets/)(bool) | Sätt till true för att använda enhetlig kolumnindelning i hela dokumentet. Standardvärdet är false; det betyder att kolumnindelning kommer att vara oberoende för varje sida. |
## Se även

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
