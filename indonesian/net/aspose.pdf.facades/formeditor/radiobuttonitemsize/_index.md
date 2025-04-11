---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: Properti FormEditor. Mendapatkan atau mengatur ukuran item tombol radio saat bidang tombol radio baru ditambahkan
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## Properti FormEditor.RadioButtonItemSize

Mendapatkan atau mengatur ukuran item tombol radio (saat bidang tombol radio baru ditambahkan).

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.RadioButtonItemSize = 20;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public double RadioButtonItemSize { get; set; }
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)