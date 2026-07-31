---
title: "FormEditor.SetFieldAppearance"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "FormEditor method. Menetapkan flag field"
type: docs
weight: 280
url: /id/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

Mengatur flag field.

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang flag-nya harus diperbarui. |
| flags | AnnotationFlags | Flag dari field. |

### Nilai Kembalian

true jika flag berhasil diperbarui.

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


