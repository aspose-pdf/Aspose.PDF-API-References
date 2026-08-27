---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor method. Raderar stämplar med angivna ID:n från alla sidor i dokumentet"
type: docs
weight: 350
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Tar bort stämplar med angivna ID:n från alla sidor i dokumentet.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stampIds | Int32[] | Array av stämpel-ID:n. |

## Exempel

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Tar bort stämplar på den angivna sidan efter flera stämpel-ID:n.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Sidnummer där stämplar kommer att raderas. |
| stampIds | Int32[] | Array av stämpel-ID:n. |

## Exempel

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


