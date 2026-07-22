---
title: "Aspose::Pdf::LogicalStructure::StructureTypeCategory class"
linktitle: "StructureTypeCategory"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::StructureTypeCategory class. Representerar kategorier av standardstrukturtyper i C++."
type: docs
weight: 5800
url: /sv/cpp/aspose.pdf.logicalstructure/structuretypecategory/
---
## StructureTypeCategory class


Representerar kategorier av standard [Structure](../../aspose.pdf.structure/) typer.

```cpp
class StructureTypeCategory : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [BLSEs](./blses/)() | Blocknivå-strukturelement (BLSEs) beskriver den övergripande layouten av innehållet på sidan och fortskrider i block-progressionsriktningen. |
| static [GroupingElements](./groupingelements/)() | Grupperings-element grupperar andra element i sekvenser eller hierarkier men innehåller inget innehåll direkt och har ingen direkt inverkan på layouten. |
| static [IllustrationElements](./illustrationelements/)() | Illustrationselement är kompakta sekvenser av innehåll, i sidans innehållsordning, som betraktas som enhetliga objekt med avseende på sidlayouten. En illustration kan behandlas som antingen en BLSE eller en ILSE. |
| static [ILSEs](./ilses/)() | Inline-nivå-strukturelement (ILSEs) beskriver layouten av innehåll inom en BLSE och fortskrider i inline-progressionsriktningen. |
| static [to_StructureTypeCategory](./to_structuretypecategory/)(const System::String\&) | Utför en explicit konvertering från [System::String](../../system/string/) till [Aspose::Pdf::LogicalStructure::StructureTypeCategory](./). |
| [ToString](./tostring/)() const override | Returnerar en sträng som representerar det aktuella objektet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
