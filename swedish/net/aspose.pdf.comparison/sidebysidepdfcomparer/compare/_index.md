---
title: "SideBySidePdfComparer.Compare"
second_title: "Aspose.PDF för .NET API‑referens"
description: "SideBySidePdfComparer metod. Jämför två sidor. Resultatet sparas i ett PDF-dokument där den första sidan skrivs först och sedan den andra. Du kan öppna det i Adobe Acrobat i tvåsidig vy för att se förändringarna sida vid sida. Borttagningar noteras på sidan till vänster och insättningar noteras på sidan till höger"
type: docs
weight: 10
url: /sv/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Jämför två sidor. Resultatet sparas i ett PDF‑dokument där den första sidan skrivs först, och sedan den andra. Du kan öppna det i Adobe Acrobat i Tvåsidig vy för att se ändringarna sida vid sida. Borttagningar noteras på sidan till vänster, och insättningar noteras på sidan till höger.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | Page | Den första sidan att jämföra. |
| page2 | Page | Den första sidan att jämföra. |
| targetPdfPath | String | Sökvägen till PDF-filen för att spara ett jämförelseresultat. |
| options | SideBySideComparisonOptions | Jämförelsealternativen. |

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Jämför två dokument. Sidorna jämförs en efter en. Sidorna i de jämförda dokumenten kopieras efter varandra in i det resulterande dokumentet. Först den första sidan från det första dokumentet, sedan den första sidan från det andra dokumentet. Därefter den andra från det första dokumentet och sedan den andra från det andra dokumentet, osv. Du kan öppna det i Adobe Acrobat i Tvåsidig vy för att se ändringarna sida vid sida. Borttagningar noteras på sidan till vänster, och insättningar noteras på sidan till höger.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Dokument | Det första dokumentet att jämföra. |
| document2 | Dokument | Det andra dokumentet att jämföra. |
| targetPdfPath | String | Sökvägen till PDF-filen för att spara ett jämförelseresultat. |
| options | SideBySideComparisonOptions | Jämförelsealternativen. |

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


