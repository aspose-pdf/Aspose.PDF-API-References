---
title: "Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode metod"
linktitle: "set_ConversionMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode metod. Tillåter att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.lowcode/pdftodocoptions/set_conversionmode/
---
## PdfToDocOptions::set_ConversionMode method


Gör det möjligt att kontrollera hur ett PDF-dokument konverteras till ett ordbehandlingsdokument.

```cpp
void Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode(Aspose::Pdf::LowCode::ConversionMode value)
```

## Anmärkningar


Använd läget [ConversionMode::TextBox](../../conversionmode/) när det resulterande dokumentet inte kommer att redigeras mycket vidare. Textrutor är enkla att ändra när det inte finns mycket att göra.

Använd läget [ConversionMode::Flow](../../conversionmode/) när utdata-dokumentet kräver vidare redigering. [Paragraphs](../../../aspose.pdf/paragraphs/) och textrader i flödesläget möjliggör enkel ändring av text, men ej stödjade formateringsobjekt ser sämre ut än i [ConversionMode::TextBox](../../conversionmode/)-läget.
## Se även

* Enum [ConversionMode](../../conversionmode/)
* Class [PdfToDocOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
