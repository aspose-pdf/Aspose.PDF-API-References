---
title: PdfAnnotationEditor.DeleteAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metod. Tar bort alla anteckningar i dokumentet
type: docs
weight: 30
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

Tar bort alla anteckningar i dokumentet.

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

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Tar bort alla anteckningar av den angivna typen i dokumentet.

```csharp
public void DeleteAnnotations(string annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotType | Sträng | Typen av anteckning som kommer att tas bort. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)