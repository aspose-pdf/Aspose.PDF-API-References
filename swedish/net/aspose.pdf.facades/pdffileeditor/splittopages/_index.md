---
title: "PdfFileEditor.SplitToPages"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metod. Delar PDF-filen i singlepage documents."
type: docs
weight: 370
url: /sv/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Delar PDF-filen i enkelsidiga dokument.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings-PDF-filnamn. |

### Returvärde

Utdata-PDF-strömmar, varje stream buffrar ett single-page PDF document.

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Delar Pdf-filen i enkelsidiga dokument.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑Pdf‑ström. |

### Returvärde

Array av minnesströmmar som innehåller pages i document.

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Dela Pdf-filen i enkelsidiga dokument och spara den i angiven sökväg. Sökvägen anges av fältet namn temaplate.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatningsfilnamn. |
| fileNameTemplate | String | Mall för det resulterande filnamnet. Måste innehålla %NUM% som ersätts med page number. Till exempel, om c:/dir/page%NUM%.pdf anges, kommer de resulterande filerna att ha följande namn: c:/dir/page1.pdf, c:/dir/page2.pdf osv. |

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Dela Pdf-filen i enkelsidiga dokument och spara den i angiven sökväg. Sökvägen anges av fältet namn temaplate.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström av source document. |
| fileNameTemplate | String | Mall för det resulterande filnamnet. Måste innehålla %NUM% som ersätts med page number. Till exempel, om c:/dir/page%NUM%.pdf anges, kommer de resulterande filerna att ha följande namn: c:/dir/page1.pdf, c:/dir/page2.pdf osv. |

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


