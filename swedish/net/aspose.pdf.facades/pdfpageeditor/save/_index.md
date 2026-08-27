---
title: "PdfPageEditor.Save"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfPageEditor-metod. Sparar ändrat dokument till fil"
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Sparar ändrat dokument till en fil.

```csharp
public override void Save(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Sökväg till fil där dokumentet kommer att sparas. |

## Exempel

Följande exempel visar hur man sparar ett ändrat PDF-dokument

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Se även

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Sparar ändrat dokument till en ström.

```csharp
public override void Save(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Ström där ändrat PDF-dokument kommer att sparas. |

## Exempel

Följande exempel visar hur man sparar ett ändrat PDF-dokument i en ström.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Se även

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


