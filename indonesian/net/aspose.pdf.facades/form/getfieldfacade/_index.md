---
title: "Form.GetFieldFacade"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengembalikan objek FrofmFieldFacade yang berisi semua atribut tampilan"
type: docs
weight: 210
url: /id/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

Mengembalikan objek FrohmFieldFacade yang berisi semua atribut tampilan.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang akan dibaca. |

### Nilai Kembalian

objek FormFieldFacade

### Lihat Juga

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


