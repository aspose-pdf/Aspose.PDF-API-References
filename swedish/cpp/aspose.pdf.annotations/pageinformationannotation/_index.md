---
title: "Aspose::Pdf::Annotations::PageInformationAnnotation klass"
linktitle: "PageInformationAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::PageInformationAnnotation klass. Representerar en sidinformation‑annotering i ett PDF‑dokument. Denna annotering innehåller filnamnet, sidnumret samt datum och tid för annoteringens skapande i C++."
type: docs
weight: 7000
url: /sv/cpp/aspose.pdf.annotations/pageinformationannotation/
---
## PageInformationAnnotation class


Representerar en [Page](../../aspose.pdf/page/) Information‑annotering i ett PDF‑dokument. Denna annotering innehåller filnamnet, sidnumret samt datum och tid för annoteringens skapande.

```cpp
class PageInformationAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökare för annoteringsbearbetning. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [PageInformationAnnotation](./pageinformationannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Initierar en ny instans av klassen [PageInformationAnnotation](./) på den angivna sidan på den angivna platsen. |
## Anmärkningar


Denna klass används främst för att lägga till metadata till en specifik sida i PDF-dokumentet, vilket kan vara användbart för spårning och referensändamål. Till exempel kan den användas för att markera sidor under utskriftsprocessen eller för att tillhandahålla ytterligare information om sidan när dokumentet visas.
## Se även

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
