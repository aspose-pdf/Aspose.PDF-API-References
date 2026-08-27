---
title: "PdfAnnotationEditor.DeleteAnnotations"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfAnnotationEditor. Menghapus semua anotasi dalam dokumen"
type: docs
weight: 30
url: /id/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

Menghapus semua anotasi dalam dokumen.

```csharp
public void DeleteAnnotations()
```

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Menghapus semua anotasi dari tipe yang ditentukan dalam dokumen.

```csharp
public void DeleteAnnotations(string annotType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| annotType | String | Tipe anotasi akan dihapus. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


