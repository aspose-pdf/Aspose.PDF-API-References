---
title: "Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage metod"
linktitle: "AddEntryToTocPage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage metod. Skapar en rubrik på den angivna innehållsförteckningssidan (TOC) och associerar den med ett TOCI-element i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.logicalstructure/headerelement/addentrytotocpage/
---
## HeaderElement::AddEntryToTocPage(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<ListLIElement\>\&) method


Skapar ett sidhuvud på den angivna [Table](../../../aspose.pdf/table/) för innehållsförteckning (TOC)-sidan och associerar det med ett TOCI-element.

```cpp
void Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage(const System::SharedPtr<Aspose::Pdf::Page> &tocPage, const System::SharedPtr<ListLIElement> &tocEntry)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tocPage | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Objektet [Page](../../../aspose.pdf/page/) som representerar TOC-sidan där sidhuvudet ska skapas. |
| tocEntry | const System::SharedPtr\<ListLIElement\>\& | Objektet [ListLIElement](../../listlielement/) som fungerar som TOCI-posten att associera med det skapade sidhuvudet på den angivna TOC-sidan. |
## Anmärkningar



Denna överlagring hanterar scenarier med nästlade [Table](../../../aspose.pdf/table/) of Contents (TOC)-strukturer, enligt PDF/UA- och PDF 1.7-standarderna, där ett **TOCI**-element inte kan vara ett barn till ett annat **TOCI** eller där en **TOC** inte kan nästlas direkt under ett **TOCI**. För att upprätthålla efterlevnad av dessa strukturella krav bör nästlade TOC-poster representeras med hjälp av **List**- och **[ListLIElement](../../listlielement/)**-element. Denna metod underlättar associeringen av sidhuvudselementet med ett sådant [ListLIElement](../../listlielement/) på den angivna TOC-sidan, vilket säkerställer korrekt logisk strukturering och förbättrar navigeringsmöjligheter i taggade PDF-dokument.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [ListLIElement](../../listlielement/)
* Class [HeaderElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
## HeaderElement::AddEntryToTocPage(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<TOCIElement\>\&) method


Skapar ett sidhuvud på den angivna [Table](../../../aspose.pdf/table/) för innehållsförteckning (TOC)-sidan och associerar det med ett TOCI-element.

```cpp
void Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage(const System::SharedPtr<Aspose::Pdf::Page> &tocPage, const System::SharedPtr<TOCIElement> &tocEntry)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tocPage | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Objektet [Page](../../../aspose.pdf/page/) som representerar TOC-sidan där sidhuvudet ska skapas. |
| tocEntry | const System::SharedPtr\<TOCIElement\>\& | Objektet [TOCIElement](../../tocielement/) som fungerar som TOC-posten att associera med det sidhuvud som skapas. |
## Anmärkningar



Denna metod säkerställer att sidhuvudet är korrekt länkat till en TOC-sida och ett TOCI-element, upprätthåller dokumentets logiska hierarki och stödjer navigering i taggade PDF-strukturer.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [TOCIElement](../../tocielement/)
* Class [HeaderElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
