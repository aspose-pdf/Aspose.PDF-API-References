---
title: "Aspose::Pdf::Comparison::TextPdfComparer klass"
linktitle: "TextPdfComparer"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::TextPdfComparer klass. Representerar en klass för att jämföra två PDF‑sidor eller PDF‑dokument i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf.comparison/textpdfcomparer/
---
## TextPdfComparer class


Representerar en klass för att jämföra två PDF-sidor eller PDF-dokument.

```cpp
class TextPdfComparer : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [AssemblyDestinationPageText](./assemblydestinationpagetext/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Återställer ändrad text från listan över förändringar. |
| static [AssemblySourcePageText](./assemblysourcepagetext/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Återställer originaltexten från listan över förändringar. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Jämför två dokument sida för sida. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) | Jämför två dokument sida för sida. Resultatet sparas i en PDF‑fil. |
| static [CompareFlatDocuments](./compareflatdocuments/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Jämför två dokument sida för sida. Dokumenten jämförs som helhet. Innan text jämförs kombineras texterna på dokumentens sidor till en enda text. |
| static [CompareFlatDocuments](./compareflatdocuments/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) | Jämför två dokument sida för sida. Resultatet sparas i en PDF‑fil. Dokumenten jämförs som helhet. Innan text jämförs kombineras texterna på dokumentens sidor till en enda text. |
| static [ComparePages](./comparepages/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Jämför dokumentsidor. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Hämtar jämförelsestatistik. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) | Hämtar statistik för dokumentjämförelse. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
