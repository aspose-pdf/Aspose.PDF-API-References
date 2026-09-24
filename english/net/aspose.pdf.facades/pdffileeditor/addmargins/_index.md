---
title: "PdfFileEditor.AddMargins"
linktitle: "AddMargins"
articleTitle: "AddMargins"
second_title: "Aspose.PDF for .NET"
description: "Resizes page contents and add specifed margins. Margins are specified in default space units."
type: docs
weight: 900
url: "/net/aspose.pdf.facades/pdffileeditor/addmargins/"
product_version: "26.9.0"
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Resizes page contents and add specifed margins. 
 Margins are specified in default space units.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream which contains source document. |
| destination | Stream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin. |
| rightMargin | double | Right margin. |
| topMargin | double | Top margin. |
| bottomMargin | double | Bottom margin. |

### Return Value

bool

true if operation was successful.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Resizes page contents and add specifed margins. 
 Margins are specified in default space units.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | string | Path to source document. |
| destination | string | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin. |
| rightMargin | double | Right margin. |
| topMargin | double | Top margin. |
| bottomMargin | double | Bottom margin. |

### Return Value

bool

true if resize was successful.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

