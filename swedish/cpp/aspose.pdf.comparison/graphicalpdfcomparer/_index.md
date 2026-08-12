---
title: "Aspose::Pdf::Comparison::GraphicalPdfComparer klass"
linktitle: "GraphicalPdfComparer"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::GraphicalPdfComparer klass. Representerar en klass för grafisk jämförelse av PDF-dokument. Bör användas för att söka efter små förändringar, främst av grafisk natur. För att jämföra förändringar i textinnehåll, använd andra PDF-jämförelseklasser i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class


Representerar en klass för grafisk jämförelse av PDF‑dokument. Bör användas för att söka efter små förändringar, främst av grafisk natur. För att jämföra förändringar i textinnehåll, använd andra PDF‑jämförelsklasser.

```cpp
class GraphicalPdfComparer : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CompareDocumentsToImages](./comparedocumentstoimages/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Jämför dokument grafiskt. Jämförelsresultatet placeras i bilder. |
| [CompareDocumentsToPdf](./comparedocumentstopdf/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&) | Jämför dokument grafiskt. Jämförelsresultatet placeras i ett PDF-dokument. |
| [ComparePagesToImage](./comparepagestoimage/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Jämför sidor grafiskt. Jämförelsresultatet placeras i en bild. |
| [ComparePagesToPdf](./comparepagestopdf/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Jämför sidor grafiskt. Jämförelsresultatet placeras i ett PDF-dokument. |
| [ComparePagesToPdf](./comparepagestopdf/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Document\>\&) | Jämför sidor grafiskt. Jämförelsresultatet placeras i ett PDF-dokument. |
| [get_Color](./get_color/)() const | Hämtar och anger färgen på ändringsflaggan. Standardfärgen är röd. |
| [get_Resolution](./get_resolution/)() const | Hämtar och anger upplösningen för de resulterande bilderna. Standardvärdet är 150 dpi. |
| [get_Threshold](./get_threshold/)() const | Hämtar och anger tröskelvärdet i procent. Detta värde låter dig ignorera små förändringar om de inte är betydande för dig. Standardvärdet är 0 %. |
| [GetDifference](./getdifference/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&) | Hämtar skillnader mellan sidbilder. Resultatet innehåller en bild av den första jämförda sidan och en array av skillnader. |
| [GraphicalPdfComparer](./graphicalpdfcomparer/)() | Skapar en instans av [GraphicalPdfComparer](./) klass. |
| [set_Color](./set_color/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Hämtar och anger färgen på ändringsflaggan. Standardfärgen är röd. |
| [set_Resolution](./set_resolution/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Hämtar och anger upplösningen för de resulterande bilderna. Standardvärdet är 150 dpi. |
| [set_Threshold](./set_threshold/)(double) | Hämtar och anger tröskelvärdet i procent. Detta värde låter dig ignorera små förändringar om de inte är betydande för dig. Standardvärdet är 0 %. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
