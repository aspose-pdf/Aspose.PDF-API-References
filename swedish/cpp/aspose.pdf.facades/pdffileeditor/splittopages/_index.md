---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitToPages method"
linktitle: "SplitToPages"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitToPages metod. Delar upp Pdf-filen i enstaka sidokument i C++."
type: docs
weight: 6100
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/splittopages/
---
## PdfFileEditor::SplitToPages(const System::SharedPtr\<System::IO::Stream\>\&) method


Delar upp [Pdf](../../../aspose.pdf/) filen i enstaka sidokument.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::SharedPtr<System::IO::Stream> &inputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Indata [Pdf](../../../aspose.pdf/) ström. |

### ReturnValue

Array av minnesströmmar som innehåller dokumentets sidor.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Dela upp [Pdf](../../../aspose.pdf/) filen i enstaka sidokument och sparar den i angiven sökväg. Sökvägen anges av fältet namnmall.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::SharedPtr<System::IO::Stream> &inputStream, const System::String &fileNameTemplate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström av källdokumentet. |
| fileNameTemplate | const System::String\& | Mall för resulterande filnamn. Måste innehålla NUM% som ersätts med sidnummer. Till exempel, om c:/dir/pageNUM%.pdf anges, kommer de resulterande filerna att ha följande namn: c:/dir/page1.pdf, c:/dir/page2.pdf osv. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::String\&) method


Delar PDF-filen i enkel‑sidiga dokument.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::String &inputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Inmatnings-PDF-filnamn. |

### ReturnValue

Utdata-PDF-strömmar, varje ström buffrar ett enstaka sid-PDF-dokument.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::String\&, const System::String\&) method


Dela upp [Pdf](../../../aspose.pdf/) filen i enstaka sidokument och sparar den i angiven sökväg. Sökvägen anges av fältet namnmall.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::String &inputFile, const System::String &fileNameTemplate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Indatafilnamn. |
| fileNameTemplate | const System::String\& | Mall för resulterande filnamn. Måste innehålla NUM% som ersätts med sidnummer. Till exempel, om c:/dir/pageNUM%.pdf anges, kommer de resulterande filerna att ha följande namn: c:/dir/page1.pdf, c:/dir/page2.pdf osv. |

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
