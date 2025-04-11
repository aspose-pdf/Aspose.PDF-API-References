---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor metod. Sparar ändrat dokument i fil
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Sparar ändrat dokument i fil.

```csharp
public override void Save(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Sökväg till fil där dokumentet kommer att sparas. |

## Exempel

Följande exempel visar hur man sparar ett ändrat PDF-dokument

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Se Även

* klass [PdfPageEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Sparar ändrat dokument i ström.

```csharp
public override void Save(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Ström där det ändrade PDF-dokumentet kommer att sparas. |

## Exempel

Följande exempel visar hur man sparar ett ändrat PDF-dokument i ström.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Se Även

* klass [PdfPageEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)