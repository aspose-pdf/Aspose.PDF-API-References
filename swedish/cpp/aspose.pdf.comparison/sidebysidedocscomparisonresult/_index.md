---
title: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult klass"
linktitle: "SideBySideDocsComparisonResult"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult klass. Representerar klassen för resultatet av en sida‑vid‑sida‑jämförelseoperation som utförs på två dokument i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/
---
## SideBySideDocsComparisonResult class


Representerar klassen för resultatet av en sida-vid-sida-jämförelseoperation utförd på två dokument.

```cpp
class SideBySideDocsComparisonResult : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_FirstDocChanges](./get_firstdocchanges/)() const | Hämta en lista över ändringar på sidorna i det första dokumentet. |
| [get_FullChanges](./get_fullchanges/)() const | Hämta en komplett lista över ändringar på dokumentets sidor. Varje index i listan representerar de två sidorna i dokumentet som jämförs, och listan med ändringsoperationer representerar listan över ändringar på dessa sidor. |
| [get_HasChanges](./get_haschanges/)() const | Hämtar värdet som indikerar om det finns några ändringar mellan de jämförda dokumenten. |
| [get_SecondDocChanges](./get_seconddocchanges/)() const | Hämta en lista över ändringar på sidorna i det andra dokumentet. |
| [SideBySideDocsComparisonResult](./sidebysidedocscomparisonresult/)(bool, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) | Skapar en instans av klassen [SideBySideDocsComparisonResult](./). |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
