---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Konstruktor Form. Konstruktor Form tanpa parameter
type: docs
weight: 10
url: /id/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Konstruktor Form tanpa parameter.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Konstruktor Form.

```csharp
public Form(string srcFileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Jalur file sumber. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Konstruktor untuk form.

```csharp
public Form(Stream srcStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcStream | Stream | aliran sumber. |

## Contoh

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Menginisialisasi objek [`Form`](../) baru berdasarkan *dokumen*.

```csharp
public Form(Document document)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Document | Dokumen Pdf. |

### Lihat Juga

* kelas [Document](../../../aspose.pdf/document/)
* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)