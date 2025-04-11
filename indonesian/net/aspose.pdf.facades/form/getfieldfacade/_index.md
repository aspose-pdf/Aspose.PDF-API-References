---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengembalikan objek FrofmFieldFacade yang berisi semua atribut tampilan
type: docs
weight: 210
url: /id/net/aspose.pdf.facades/form/getfieldfacade/
---
## Metode Form.GetFieldFacade

Mengembalikan objek FrofmFieldFacade yang berisi semua atribut tampilan.

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
| fieldName | String | Nama field yang akan dibaca. |

### Nilai Kembali

Objek FormFieldFacade

### Lihat Juga

* kelas [FormFieldFacade](../../formfieldfacade/)
* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)