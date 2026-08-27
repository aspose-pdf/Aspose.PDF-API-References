---
title: "FormEditor.RadioHoriz"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti FormEditor. Bendera untuk menunjukkan apakah radio diatur secara horizontal atau vertikal, nilai default adalah true"
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

Bendera untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true.

```csharp
public bool RadioHoriz { get; set; }
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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


