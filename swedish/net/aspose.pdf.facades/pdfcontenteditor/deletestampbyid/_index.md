---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Tar bort stämpel på den angivna sidan med stämpel-ID
type: docs
weight: 340
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Tar bort stämpel på den angivna sidan med stämpel-ID.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Sidnummer där stämpeln kommer att tas bort. |
| stampId | Int32 | Identifierare för stämpeln som ska tas bort. |

## Exempel

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Ta bort stämpel med ID från alla sidor i dokumentet.

```csharp
public void DeleteStampById(int stampId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stampId | Int32 | Identifierare för stämpeln som ska tas bort. |

## Exempel

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)