---
title: "PdfFileEditor.AddMargins"
linktitle: "AddMargins"
articleTitle: "AddMargins"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Resizes page contents and add specifed margins. Margins are specified in default space units."
type: docs
weight: 900
url: "/net/aspose.pdf.facades/pdffileeditor/addmargins/"
product_version: "26.9.0"
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Resizes page contents and add specifed margins. 
 Margins are specified in default space units.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream which contains source document. |
| destination | Stream | Stream where resultant document will be saved. |
| pages | Int32[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | Double | Left margin. |
| rightMargin | Double | Right margin. |
| topMargin | Double | Top margin. |
| bottomMargin | Double | Bottom margin. |

### Return Value

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
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | Path to source document. |
| destination | String | Path where resultant document will be saved. |
| pages | Int32[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | Double | Left margin. |
| rightMargin | Double | Right margin. |
| topMargin | Double | Top margin. |
| bottomMargin | Double | Bottom margin. |

### Return Value

true if resize was successful.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

