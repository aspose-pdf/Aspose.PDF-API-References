---
title: "Aspose::Pdf::FileSpecificationComparer-klass"
linktitle: "FileSpecificationComparer"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::FileSpecificationComparer-klass. Representerar en jämförelseklass för en filspecificering. Jämförelsen jämför enligt specificeringen, med hjälp av listan över fält att sortera i samlingsdefinitionen. Enligt specificeringen sker sortering efter samlingsobjektens värden. Om det inte finns någon samlingsobjektsordbok, sker sortering efter Params‑värden i C++."
type: docs
weight: 5600
url: /sv/cpp/aspose.pdf/filespecificationcomparer/
---
## FileSpecificationComparer class


Representerar en jämförelseklass för en filspecificering. Jämförelsen jämför enligt specifikationen, med hjälp av listan av fält att sortera i samlingsdefinitionen. Enligt specifikationen sker sortering efter samlingsobjektens värden. Om det inte finns någon samlingsobjektordbok, sker sortering efter Params-värden.

```cpp
class FileSpecificationComparer : public System::Collections::Generic::IComparer<System::SharedPtr<FileSpecification>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Compare](./compare/)(const System::SharedPtr\<FileSpecification\>\&, const System::SharedPtr\<FileSpecification\>\&) const override | Jämför två filspecificeringar enligt samlingsdefinitionen, med den angivna sorteringen. |
| [FileSpecificationComparer](./filespecificationcomparer/)(const System::SharedPtr\<CollectionSort\>\&) | Skapar en filspecificeringsjämförare. |
## Se även

* Class [IComparer](../../system.collections.generic/icomparer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
