---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: SideBySidePdfComparer-metod. Jämför två sidor. Resultatet sparas i ett PDF-dokument där den första sidan skrivs först och sedan den andra. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se ändringarna sida vid sida. Borttagningar noteras på sidan till vänster och insättningar noteras på sidan till höger
type: docs
weight: 10
url: /sv/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Jämför två sidor. Resultatet sparas i ett PDF-dokument där den första sidan skrivs först, och sedan den andra. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se ändringarna sida vid sida. Borttagningar noteras på sidan till vänster, och insättningar noteras på sidan till höger.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | Page | Den första sidan att jämföra. |
| page2 | Page | Den andra sidan att jämföra. |
| targetPdfPath | String | Sökvägen till PDF-filen för att spara ett jämförelsesresultat. |
| options | SideBySideComparisonOptions | Jämförelsealternativen. |

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* klass [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Jämför två dokument. Sidorna jämförs en efter en. Sidorna i de jämförda dokumenten kopieras en efter en in i det resulterande dokumentet. Först den första sidan från det första dokumentet, sedan den första sidan från det andra dokumentet. Nästa är den andra från det första dokumentet och sedan den andra från det andra dokumentet, osv. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se ändringarna sida vid sida. Borttagningar noteras på sidan till vänster, och insättningar noteras på sidan till höger.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Document | Det första dokumentet att jämföra. |
| document2 | Document | Det andra dokumentet att jämföra. |
| targetPdfPath | String | Sökvägen till PDF-filen för att spara ett jämförelsesresultat. |
| options | SideBySideComparisonOptions | Jämförelsealternativen. |

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* klass [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)