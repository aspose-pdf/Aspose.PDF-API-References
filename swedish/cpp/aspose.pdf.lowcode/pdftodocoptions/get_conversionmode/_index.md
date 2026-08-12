---
title: "Aspose::Pdf::LowCode::PdfToDocOptions::get_ConversionMode metod"
linktitle: "get_ConversionMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfToDocOptions::get_ConversionMode method. Tillåter att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.lowcode/pdftodocoptions/get_conversionmode/
---
## PdfToDocOptions::get_ConversionMode method


Gör det möjligt att kontrollera hur ett PDF-dokument konverteras till ett ordbehandlingsdokument.

```cpp
Aspose::Pdf::LowCode::ConversionMode Aspose::Pdf::LowCode::PdfToDocOptions::get_ConversionMode() const
```

## Anmärkningar


Använd läget [ConversionMode::TextBox](../../conversionmode/) när det resulterande dokumentet inte kommer att redigeras mycket vidare. Textrutor är enkla att ändra när det inte finns mycket att göra.

Använd läget [ConversionMode::Flow](../../conversionmode/) när utdata-dokumentet kräver vidare redigering. [Paragraphs](../../../aspose.pdf/paragraphs/) och textrader i flödesläget möjliggör enkel ändring av text, men ej stödjade formateringsobjekt ser sämre ut än i [ConversionMode::TextBox](../../conversionmode/)-läget.
## Se även

* Enum [ConversionMode](../../conversionmode/)
* Class [PdfToDocOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
