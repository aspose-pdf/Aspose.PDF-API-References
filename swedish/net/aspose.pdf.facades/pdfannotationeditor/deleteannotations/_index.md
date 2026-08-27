---
title: "PdfAnnotationEditor.DeleteAnnotations"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor metod. Raderar alla annotationer i dokumentet"
type: docs
weight: 30
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

Tar bort alla Annotation i Document.

```csharp
public void DeleteAnnotations()
```

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Tar bort alla Annotation av den angivna typen i Document.

```csharp
public void DeleteAnnotations(string annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotType | String | Typen av annotation som ska raderas. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


