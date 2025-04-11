---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Delar upp Pdf-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga
type: docs
weight: 350
url: /sv/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Delar upp Pdf-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Inmatnings-PDF-fil. |
| numberOfPage | Int32[][] | Array som innehåller array av dubbla element, som är start- och slut sidor av dokumentet. |

### Returvärde

Utdata-PDF-strömmar, varje ström buffrar ett PDF-dokument.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Delar upp Pdf-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Inmatnings-PDF-ström. |
| numberOfPage | Int32[][] | Startsidans och slutsidans nummer för varje dokument. |

### Returvärde

Utdata-PDF-strömmar, varje ström buffrar ett PDF-dokument.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)