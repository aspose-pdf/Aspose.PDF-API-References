---
title: "PdfFileEditor.AddMarginsPct"
linktitle: "AddMarginsPct"
articleTitle: "AddMarginsPct"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileEditor method. Resizes page contents and add specified margins. Margins are specified in percents of intitial page size."
type: docs
weight: 910
url: "/net/aspose.pdf.facades/pdffileeditor/addmarginspct/"
product_version: "26.9.0"
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Resizes page contents and add specified margins.
 Margins are specified in percents of intitial page size.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream which contains source document. |
| destination | Stream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin in percents of initial page size. |
| rightMargin | double | Right margin in percents of initial page size. |
| topMargin | double | Top margin in percents of initial page size. |
| bottomMargin | double | Bottom margin in percents of initial page size. |

### Return Value

bool

true if action was performed successfully.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Resizes page contents and add specified margins.
 Margins are specified in percents of intitial page size.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | string | Path to source document. |
| destination | string | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin in percents of initial page size. |
| rightMargin | double | Right margin in percents of initial page size. |
| topMargin | double | Top margin in percents of initial page size. |
| bottomMargin | double | Bottom margin in percents of initial page size. |

### Return Value

bool

true if resize was successful

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

