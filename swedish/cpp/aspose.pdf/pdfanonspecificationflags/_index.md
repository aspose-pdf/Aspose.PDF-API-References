---
title: "Aspose::Pdf::PdfANonSpecificationFlags-klass"
linktitle: "PdfANonSpecificationFlags"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PdfANonSpecificationFlags-klass. Denna klass innehåller flaggor för att styra PDF/A-konvertering i fall då källdokumentet PDF inte motsvarar PDF-specifikationen. Om flaggorna i denna klass används minskar prestandan men det är nödvändigt när källdokumentet PDF inte kan konverteras till PDF/A-format på vanligt sätt. Som standard är alla flaggor satta till false i C++."
type: docs
weight: 14800
url: /sv/cpp/aspose.pdf/pdfanonspecificationflags/
---
## PdfANonSpecificationFlags class


Denna klass innehåller flaggor för att styra PDF/A-konvertering för fall då källdokumentet PDF inte överensstämmer med PDF-specifikationen. Om flaggorna i denna klass används minskar prestandan, men det är nödvändigt när källdokumentet PDF inte kan konverteras till PDF/A-format på vanligt sätt. Som standard är alla flaggor satta till falskt.

```cpp
class PdfANonSpecificationFlags : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CheckDifferentNamesInFontDictionaries](./get_checkdifferentnamesinfontdictionaries/)() const | Vissa PDF-dokument innehåller typsnitt som har olika namn i intern data. Användning av denna flagga tvingar fram speciell bearbetningslogik för fall då fälten BaseFont och FontDescriptor.FontName är olika. |
| [PdfANonSpecificationFlags](./pdfanonspecificationflags/)() | Konstruktor. |
| [set_CheckDifferentNamesInFontDictionaries](./set_checkdifferentnamesinfontdictionaries/)(bool) | Vissa PDF-dokument innehåller typsnitt som har olika namn i intern data. Användning av denna flagga tvingar fram speciell bearbetningslogik för fall då fälten BaseFont och FontDescriptor.FontName är olika. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
