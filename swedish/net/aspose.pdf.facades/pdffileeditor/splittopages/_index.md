---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Delar PDF-filen i dokument med en sida
type: docs
weight: 370
url: /sv/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Delar PDF-filen i dokument med en sida.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Inmatnings-PDF-filnamn. |

### Returvärde

Utdata-PDF-strömmar, varje ström buffrar ett PDF-dokument med en sida.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Delar PDF-filen i dokument med en sida.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Inmatnings-PDF-ström. |

### Returvärde

Array av minnesströmmar som innehåller sidor av dokumentet.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Dela PDF-filen i dokument med en sida och spara den i angiven sökväg. Sökvägen specificeras av fältnamnet mall.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Inmatningsfilnamn. |
| fileNameTemplate | Sträng | Mall för det resulterande filnamnet. Måste innehålla %NUM% som ersätts med sidnummer. Till exempel, om c:/dir/page%NUM%.pdf anges, kommer de resulterande filerna att ha följande namn: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Dela PDF-filen i dokument med en sida och spara den i angiven sökväg. Sökvägen specificeras av fältnamnet mall.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Ström av källdokumentet. |
| fileNameTemplate | Sträng | Mall för det resulterande filnamnet. Måste innehålla %NUM% som ersätts med sidnummer. Till exempel, om c:/dir/page%NUM%.pdf anges, kommer de resulterande filerna att ha följande namn: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)