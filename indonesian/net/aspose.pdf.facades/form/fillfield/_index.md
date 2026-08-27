---
title: "Form.FillField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengisi bidang dengan nilai yang valid berdasarkan nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi, semua nama bidang dan nilai valid yang sesuai harus diketahui. Baik nama bidang maupun nilai bersifat sensitif huruf. Harap dicatat bahwa Aspose.Pdf.Facades hanya mendukung nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit. Misalnya, jika bidang memiliki nama lengkap Form.Subform.TextField, Anda harus menentukan nama lengkap, bukan TextField. Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya."
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

Isi bidang dengan nilai yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi bidang, setiap nama bidang dan nilai valid yang sesuai harus diketahui. Baik nama bidang maupun nilai bersifat sensitif huruf. Harap perhatikan bahwa Aspose.Pdf.Facades mendukung hanya nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap "Form.Subform.TextField" Anda harus menentukan nama lengkap dan bukan "TextField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang akan diisi. |
| fieldValue | String | Nilai bidang yang harus merupakan nilai valid untuk beberapa bidang. |

### Nilai Kembalian

true jika bidang ditemukan dan berhasil diisi.

## Contoh

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//cara mencari bidang berdasarkan nama parsialnya:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Isi bidang radio box dengan nilai indeks yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi bidang, hanya nama bidang yang harus diketahui. Nilai dapat ditentukan dengan indeksnya. Catatan: Hanya berlaku untuk bidang Radio Box, Combo Box, dan List Box. Harap perhatikan bahwa Aspose.Pdf.Facades mendukung hanya nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap "Form.Subform.ListBoxField" Anda harus menentukan nama lengkap dan bukan "ListBoxField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang akan diisi. |
| index | Int32 | Indeks item yang dipilih. |

### Nilai Kembalian

true jika bidang ditemukan dan berhasil diisi.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//cara mencari bidang berdasarkan nama parsialnya:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Isi bidang kotak centang dengan nilai boolean. Catatan: Hanya berlaku untuk Check Box. Harap perhatikan bahwa Aspose.Pdf.Facades mendukung hanya nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap "Form.Subform.CheckBoxField" Anda harus menentukan nama lengkap dan bukan "CheckBoxField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang akan diisi. |
| beChecked | Boolean | Bendera boolean: true berarti mencentang kotak, sementara false berarti tidak mencentangnya. |

### Nilai Kembalian

true jika bidang ditemukan dan berhasil diisi.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//cara mencari bidang berdasarkan nama parsialnya:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Isi bidang dengan beberapa pilihan. Catatan: hanya untuk AcroForm List Box Field.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi kualifikasi. |
| fieldValues | String[] | Array string yang berisi beberapa item untuk dipilih. |

## Contoh

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

Isi bidang dengan nilai yang ditentukan.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang |
| nilai | String | Nilai baru bidang |
| fitFontSize | Boolean | Jika true, ukuran font dalam kotak edit akan disesuaikan. |

### Nilai Kembalian

true jika bidang ditemukan dan berhasil diisi.

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


