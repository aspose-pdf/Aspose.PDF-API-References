---
title: "Aspose::Pdf::PaginationArtifact class"
linktitle: "PaginationArtifact"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PaginationArtifact class. Representerar en abstrakt basklass för pagineringsartefakter i ett dokument i C++."
type: docs
weight: 14500
url: /sv/cpp/aspose.pdf/paginationartifact/
---
## PaginationArtifact class


Representerar en abstrakt basklass för pagineringsartefakter i ett dokument.

```cpp
class PaginationArtifact : public Aspose::Pdf::Artifact
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_EndPage](./get_endpage/)() const | Hämtar det avslutande sidnumret för artefakten. Värdet måste vara större än eller lika med 0. Om ett värde mindre än 0 anges, justeras det till 0. Standardvärdet 0 betyder att det inte finns några slutsidgränser. |
| [get_StartPage](./get_startpage/)() const | Hämtar det startande sidnumret för artefakten. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [get_Subset](./get_subset/)() const | Hämtar delmängden av sidor som artefakten gäller för (t.ex. alla sidor, jämna sidor, udda sidor). |
| [set_EndPage](./set_endpage/)(int32_t) | Ställer in det avslutande sidnumret för artefakten. Värdet måste vara större än eller lika med 0. Om ett värde mindre än 0 anges, justeras det till 0. Standardvärdet 0 betyder att det inte finns några slutsidgränser. |
| [set_StartPage](./set_startpage/)(int32_t) | Ställer in det startande sidnumret för artefakten. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [set_Subset](./set_subset/)(Aspose::Pdf::Subset) | Ställer in delmängden av sidor som artefakten gäller för (t.ex. alla sidor, jämna sidor, udda sidor). |
## Se även

* Class [Artifact](../artifact/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
