---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Atur bendera field
type: docs
weight: 280
url: /id/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## Metode FormEditor.SetFieldAppearance

Atur bendera field

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang benderanya harus diperbarui. |
| flags | AnnotationFlags | Bendera dari field. |

### Nilai Kembali

true jika bendera diperbarui dengan sukses.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Lihat Juga

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)