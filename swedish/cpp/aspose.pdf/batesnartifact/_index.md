---
title: "Aspose::Pdf::BatesNArtifact klass"
linktitle: "BatesNArtifact"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::BatesNArtifact klass. Klassen beskriver Bates‑numreringsartefakt i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.pdf/batesnartifact/
---
## BatesNArtifact class


Klassen beskriver Bates-numreringsartefakt.

```cpp
class BatesNArtifact : public Aspose::Pdf::PaginationArtifact
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BatesNArtifact](./batesnartifact/)() | Initierar en ny instans av klassen [BatesNArtifact](./). Denna konstruktor är intern och skapar ett rubrikartefakt‑objekt med standardvärden. |
| [get_NumberOfDigits](./get_numberofdigits/)() const | Hämtar antalet siffror för Bates‑numrering. Värdet måste vara mellan 3 och 15 inklusive. Om ett värde mindre än 3 anges justeras det till 3. Om ett värde större än 15 anges justeras det till 15. Standardvärdet är 6. |
| [get_Prefix](./get_prefix/)() const | Hämtar prefixet som ska läggas till Bates‑numret. |
| [get_StartNumber](./get_startnumber/)() const | Hämtar startnumret för Bates‑numrering. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges justeras det till 1. |
| [get_Suffix](./get_suffix/)() const | Hämtar suffixet som ska läggas till Bates‑numret. |
| [set_NumberOfDigits](./set_numberofdigits/)(int32_t) | Ställer in antalet siffror för Bates‑numrering. Värdet måste vara mellan 3 och 15 inklusive. Om ett värde mindre än 3 anges justeras det till 3. Om ett värde större än 15 anges justeras det till 15. Standardvärdet är 6. |
| [set_Prefix](./set_prefix/)(const System::String\&) | Ställer in prefixet som ska läggas till Bates‑numret. |
| [set_StartNumber](./set_startnumber/)(int32_t) | Ställer in startnumret för Bates‑numrering. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges justeras det till 1. |
| [set_Suffix](./set_suffix/)(const System::String\&) | Ställer in suffixet som ska läggas till Bates‑numret. |
## Se även

* Class [PaginationArtifact](../paginationartifact/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
