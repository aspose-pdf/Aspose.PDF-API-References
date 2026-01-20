---
title: Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage method
linktitle: AddEntryToTocPage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage method. Creates a header on the specified Table of Contents (TOC) page and associates it with a TOCI element in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.logicalstructure/headerelement/addentrytotocpage/
---
## HeaderElement::AddEntryToTocPage(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<ListLIElement\>) method


Creates a header on the specified [Table](../../../aspose.pdf/table/) of Contents (TOC) page and associates it with a TOCI element.

```cpp
void Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage(System::SharedPtr<Aspose::Pdf::Page> tocPage, System::SharedPtr<ListLIElement> tocEntry)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tocPage | System::SharedPtr\<Aspose::Pdf::Page\> | The [Page](../../../aspose.pdf/page/) object representing the TOC page where the header should be created. |
| tocEntry | System::SharedPtr\<ListLIElement\> | The [ListLIElement](../../listlielement/) object acting as the TOCI entry to associate with the created header on the specified TOC page. |
## Remarks



This overload addresses scenarios involving nested [Table](../../../aspose.pdf/table/) of Contents (TOC) structures, as specified in PDF/UA and PDF 1.7 standards, where a **TOCI** element cannot be a child of another **TOCI** or where a **TOC** cannot be nested directly under a **TOCI**. To maintain compliance with these structural requirements, nested TOC entries should be represented using **List** and **[ListLIElement](../../listlielement/)** elements. This method facilitates the association of the header element with such a [ListLIElement](../../listlielement/) on the designated TOC page, ensuring proper logical structuring and enhancing navigation capabilities in tagged PDF documents. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [ListLIElement](../../listlielement/)
* Class [HeaderElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
## HeaderElement::AddEntryToTocPage(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<TOCIElement\>) method


Creates a header on the specified [Table](../../../aspose.pdf/table/) of Contents (TOC) page and associates it with a TOCI element.

```cpp
void Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage(System::SharedPtr<Aspose::Pdf::Page> tocPage, System::SharedPtr<TOCIElement> tocEntry)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tocPage | System::SharedPtr\<Aspose::Pdf::Page\> | The [Page](../../../aspose.pdf/page/) object representing the TOC page where the header should be created. |
| tocEntry | System::SharedPtr\<TOCIElement\> | The [TOCIElement](../../tocielement/) serving as the TOC entry to associate with the header being created. |
## Remarks



This method ensures that the header is properly linked to a TOC page and a TOCI element, maintaining the document's logical hierarchy and supporting navigation in tagged PDF structures. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [TOCIElement](../../tocielement/)
* Class [HeaderElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
