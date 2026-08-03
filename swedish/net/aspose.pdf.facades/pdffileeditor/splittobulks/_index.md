---
title: "PdfFileEditor.SplitToBulks"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metod. Delar PDF-filen i flera dokument. Dokumenten kan vara enkelsidiga eller flersidiga."
type: docs
weight: 350
url: /sv/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Delar Pdf-filen i flera dokument. Dokumenten kan vara enkelsidiga eller flersidiga.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings-PDF-fil. |
| numberOfPage | Int32[][] | Array som innehåller en array av double-element, som är start- och slut sidorna för dokumentet. |

### Returvärde

Utdata-PDF-strömmar, varje ström buffrar ett PDF-dokument.

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Delar Pdf-filen i flera dokument. Dokumenten kan vara enkelsidiga eller flersidiga.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑PDF‑ström. |
| numberOfPage | Int32[][] | Start- och slutssidan för varje dokument. |

### Returvärde

Utdata-PDF-strömmar, varje ström buffrar ett PDF-dokument.

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


