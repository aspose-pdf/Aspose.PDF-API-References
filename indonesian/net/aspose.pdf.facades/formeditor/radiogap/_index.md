---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: Properti FormEditor. Anggota untuk mencatat jarak antara dua tombol radio yang berdekatan dalam piksel, default adalah 50
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/formeditor/radiogap/
---
## Properti FormEditor.RadioGap

Anggota untuk mencatat jarak antara dua tombol radio yang berdekatan dalam piksel, default adalah 50.

```csharp
public float RadioGap { get; set; }
```

## Contoh

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Lihat Juga

* kelas [FormEditor](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)