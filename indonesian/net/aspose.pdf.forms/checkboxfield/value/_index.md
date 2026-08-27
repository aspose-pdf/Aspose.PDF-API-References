---
title: "CheckboxField.Value"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti CheckboxField. Mendapatkan atau mengatur nilai bidang kotak centang"
type: docs
weight: 70
url: /id/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

Mendapatkan atau mengatur nilai bidang kotak centang.

```csharp
public override string Value { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mendapatkan dan mengatur nilai kotak centang multi-nilai.

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// Nilai yang diizinkan dapat diambil dari koleksi AllowedStates
// Atur nilai kotak centang menggunakan properti Value
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// Nilai harus berupa elemen apa pun dari AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Hapus centang kotak dengan mengatur Value ke "Off" atau mengatur Checked ke false
checkbox.Value = "Off";
// atau, secara alternatif:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### Lihat Juga

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


