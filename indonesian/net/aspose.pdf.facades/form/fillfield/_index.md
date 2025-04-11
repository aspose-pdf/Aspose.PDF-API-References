---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengisi field dengan nilai yang valid sesuai dengan nama field yang sepenuhnya memenuhi syarat. Sebelum mengisi field, setiap nama field dan nilai valid yang sesuai harus diketahui. Baik nama field maupun nilai bersifat case sensitive. Harap dicatat bahwa Aspose.Pdf.Facades hanya mendukung nama field lengkap dan tidak berfungsi dengan nama field parsial, berbeda dengan Aspose.Pdf.Kit. Misalnya, jika field memiliki nama lengkap Form.Subform.TextField, Anda harus menentukan nama lengkap dan bukan TextField. Anda dapat menggunakan properti FieldNames untuk menjelajahi nama field yang ada dan mencari field yang diperlukan berdasarkan nama parsialnya.
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Mengisi field dengan nilai yang ditentukan.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field |
| value | String | Nilai baru dari field |
| fitFontSize | Boolean | Jika true, ukuran font di kotak edit akan disesuaikan. |

### Return Value

true jika field ditemukan dan berhasil diisi.

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Mengisi field dengan nilai yang valid sesuai dengan nama field yang sepenuhnya memenuhi syarat. Sebelum mengisi field, setiap nama field dan nilai valid yang sesuai harus diketahui. Baik nama field maupun nilai bersifat case sensitive. Harap dicatat bahwa Aspose.Pdf.Facades hanya mendukung nama field lengkap dan tidak berfungsi dengan nama field parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya, jika field memiliki nama lengkap "Form.Subform.TextField", Anda harus menentukan nama lengkap dan bukan "TextField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama field yang ada dan mencari field yang diperlukan berdasarkan nama parsialnya.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang akan diisi. |
| fieldValue | String | Nilai field yang harus merupakan nilai yang valid untuk beberapa field. |

### Return Value

true jika field ditemukan dan berhasil diisi.

## Contoh

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//how to search field by its partial name:
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

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Mengisi field kotak radio dengan nilai indeks yang valid sesuai dengan nama field yang sepenuhnya memenuhi syarat. Sebelum mengisi field, hanya nama field yang harus diketahui. Sementara nilai dapat ditentukan berdasarkan indeksnya. Catatan: Hanya berlaku untuk field Radio Box, Combo Box, dan List Box. Harap dicatat bahwa Aspose.Pdf.Facades hanya mendukung nama field lengkap dan tidak berfungsi dengan nama field parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya, jika field memiliki nama lengkap "Form.Subform.ListBoxField", Anda harus menentukan nama lengkap dan bukan "ListBoxField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama field yang ada dan mencari field yang diperlukan berdasarkan nama parsialnya.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang akan diisi. |
| index | Int32 | Indeks item yang dipilih. |

### Return Value

true jika field ditemukan dan berhasil diisi.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//how to search field by its partial name:
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

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Mengisi field kotak centang dengan nilai boolean. Catatan: Hanya berlaku untuk Check Box. Harap dicatat bahwa Aspose.Pdf.Facades hanya mendukung nama field lengkap dan tidak berfungsi dengan nama field parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya, jika field memiliki nama lengkap "Form.Subform.CheckBoxField", Anda harus menentukan nama lengkap dan bukan "CheckBoxField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama field yang ada dan mencari field yang diperlukan berdasarkan nama parsialnya.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang akan diisi. |
| beChecked | Boolean | Sebuah flag boolean: true berarti mencentang kotak, sedangkan false untuk menghilangkan centang. |

### Return Value

true jika field ditemukan dan berhasil diisi.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//how to search field by its partial name:
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

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Mengisi field dengan beberapa pilihan. Catatan: hanya untuk Field List Box AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang sepenuhnya memenuhi syarat. |
| fieldValues | String[] | Array string yang berisi beberapa item untuk dipilih. |

## Contoh

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

Mengisi field dengan nilai yang ditentukan.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field |
| value | String | Nilai baru dari field |
| fitFontSize | Boolean | Jika true, ukuran font di kotak edit akan disesuaikan. |

### Return Value

true jika field ditemukan dan berhasil diisi.

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)