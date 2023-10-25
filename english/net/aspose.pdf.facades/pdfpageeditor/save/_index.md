---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor method. Saves changed document into file
type: docs
weight: 180
url: /net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Saves changed document into file.

```csharp
public override void Save(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | Path to file where document will be saved. |

## Examples

The following sample demonstrates how to save changed PDF document

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### See Also

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Saves changed document into stream.

```csharp
public override void Save(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where changed PDF document will be saved. |

## Examples

The following sample demonstrates how to save changed PDF document into stream.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### See Also

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


