---
title: "Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare metod"
linktitle: "Compare"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare metod. Jämför två dokument. Sidorna jämförs en efter en. Sidorna i de jämförda dokumenten kopieras en efter en in i det resulterande dokumentet. Först den första sidan från det första dokumentet, sedan den första sidan från det andra dokumentet. Därefter den andra från det första dokumentet och sedan den andra från det andra dokumentet, osv. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se förändringarna sida vid sida. Raderingar noteras på sidan till vänster och insättningar noteras på sidan till höger i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Jämför två dokument. Sidorna jämförs en efter en. Sidorna i de jämförda dokumenten kopieras sekventiellt in i det resulterande dokumentet. Först den första sidan från det första dokumentet, sedan den första sidan från det andra dokumentet. Därefter den andra sidan från det första dokumentet och sedan den andra sidan från det andra dokumentet osv. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se ändringarna sida vid sida. Raderingar noteras på sidan till vänster och insättningar noteras på sidan till höger.

```cpp
static System::SharedPtr<SideBySideDocsComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<System::IO::Stream> &targetStream, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Det första dokumentet att jämföra. |
| document2 | const System::SharedPtr\<Document\>\& | Det andra dokumentet att jämföra. |
| targetStream | const System::SharedPtr\<System::IO::Stream\>\& | Målsströmmen för att spara ett jämförelsresultat. |
| options | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Jämförelsalternativen. |

### ReturnValue

Jämförelsresultatet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySideDocsComparisonResult](../../sidebysidedocscomparisonresult/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Jämför två dokument. Sidorna jämförs en efter en. Sidorna i de jämförda dokumenten kopieras sekventiellt in i det resulterande dokumentet. Först den första sidan från det första dokumentet, sedan den första sidan från det andra dokumentet. Därefter den andra sidan från det första dokumentet och sedan den andra sidan från det andra dokumentet osv. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se ändringarna sida vid sida. Raderingar noteras på sidan till vänster och insättningar noteras på sidan till höger.

```cpp
static System::SharedPtr<SideBySideDocsComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::String &targetPdfPath, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Det första dokumentet att jämföra. |
| document2 | const System::SharedPtr\<Document\>\& | Det andra dokumentet att jämföra. |
| targetPdfPath | const System::String\& | Sökvägen till PDF-filen för att spara ett jämförelsresultat. |
| options | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Jämförelsalternativen. |

### ReturnValue

Jämförelsresultatet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySideDocsComparisonResult](../../sidebysidedocscomparisonresult/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Jämför två sidor. Resultatet sparas i ett PDF‑dokument där den första sidan skrivs först, och sedan den andra. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se ändringarna sida vid sida. Raderingar noteras på sidan till vänster och insättningar noteras på sidan till höger.

```cpp
static System::SharedPtr<SideBySidePagesComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::SharedPtr<System::IO::Stream> &targetStream, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | Den första sidan att jämföra. |
| page2 | const System::SharedPtr\<Page\>\& | Den första sidan att jämföra. |
| targetStream | const System::SharedPtr\<System::IO::Stream\>\& | Målsströmmen för att spara ett jämförelsresultat. |
| options | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Jämförelsalternativen. |

### ReturnValue

Jämförelsresultatet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySidePagesComparisonResult](../../sidebysidepagescomparisonresult/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Jämför två sidor. Resultatet sparas i ett PDF‑dokument där den första sidan skrivs först, och sedan den andra. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se ändringarna sida vid sida. Raderingar noteras på sidan till vänster och insättningar noteras på sidan till höger.

```cpp
static System::SharedPtr<SideBySidePagesComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::String &targetPdfPath, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | Den första sidan att jämföra. |
| page2 | const System::SharedPtr\<Page\>\& | Den första sidan att jämföra. |
| targetPdfPath | const System::String\& | Sökvägen till PDF-filen för att spara ett jämförelsresultat. |
| options | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Jämförelsalternativen. |

### ReturnValue

Jämförelsresultatet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySidePagesComparisonResult](../../sidebysidepagescomparisonresult/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
