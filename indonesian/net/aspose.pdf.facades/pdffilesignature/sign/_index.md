---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSignature. Buat tanda tangan pada dokumen pdf
type: docs
weight: 300
url: /id/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Buat tanda tangan pada dokumen pdf.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Nomor halaman di mana tanda tangan dibuat. |
| SigReason | String | Alasan tanda tangan. |
| SigContact | String | Kontak tanda tangan. |
| SigLocation | String | Lokasi tanda tangan. |
| visible | Boolean | Visibilitas tanda tangan. |
| annotRect | Rectangle | Rect tanda tangan. |

## Contoh

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PdfFileSignature pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile);
System.Drawing.Rectangle rect = new System.Drawing.Rectangle(100, 100, 200, 200);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.SetCertificate("certificate.pfx", "password");
pdfSign.Sign(2, "Allen", "success", "ChangSha", true, rect);
pdfSign.Save(outFile);

[Visual Basic]
Dim pdfSign = new PdfFileSignature()
pdfSign.BindPdf(inFile)
Dim rect as System.Drawing.Rectangle = new System.Drawing.Rectangle(100, 100, 200, 200)
pdfSign.SetCertificate("certificate.pfx", "password")
pdfSign.Sign(2, "Allen", "success", "ChangSha", true, rect)
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg"
pdfSign.Save(outFile)
```

### Lihat Juga

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Tandatangani dokumen dengan jenis tanda tangan yang diberikan.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Nomor halaman di mana tanda tangan dibuat. |
| SigReason | String | Alasan tanda tangan. |
| SigContact | String | Kontak tanda tangan. |
| SigLocation | String | Lokasi tanda tangan. |
| visible | Boolean | Visibilitas tanda tangan. |
| annotRect | Rectangle | Rect tanda tangan. |
| sig | Signature | Jenis tanda tangan, bisa PKCS1, PKCS7 dan PKCS7Detached. |

## Contoh

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
System.Drawing.Rectangle rect = new System.Drawing.Rectangle(100, 100, 200, 100);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.Sign(2, "Allen", "success", "ChangSha", true, rect, new PKCS1("certificate.pfx", "password"));
pdfSign.Save();

[Visual Basic]
Dim inFile As String = TestPath & "example1.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS1 = new PKCS1("certificate.pfx", "password")
Dim pdfSign = new PdfFileSignature(inFile, outFile)
Dim rect as System.Drawing.Rectangle = new System.Drawing.Rectangle(100, 100, 200, 100)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign(2, "Allen", "success", "ChangSha", true, rect, sig)
pdfSign.Save()
```

### Lihat Juga

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Tandatangani dokumen dengan jenis tanda tangan yang diberikan.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Nomor halaman di mana tanda tangan dibuat. |
| visible | Boolean | Visibilitas tanda tangan. |
| annotRect | Rectangle | Rect tanda tangan. |
| sig | Signature | Jenis tanda tangan, bisa PKCS1, PKCS7 dan PKCS7Detached. Data seperti alasan tanda tangan, kontak, dan lokasi harus sudah ada dalam objek ini (lihat properti yang sesuai). |

## Contoh

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PKCS1 sig = new PKCS1("certificate.pfx", "password");
sig.Reason = "Some reason";
sig.Contact = "Smith";
sig.Location = "New York";
PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
System.Drawing.Rectangle rect = new System.Drawing.Rectangle(100, 100, 200, 100);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.Sign(2, true, rect, sig);
pdfSign.Save();

[Visual Basic]
Dim inFile As String = TestPath & "example1.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS1 = new PKCS1("certificate.pfx", "password")
sig.Reason = "Some reason"
sig.Contact = "Smith"
sig.Location = "New York"
Dim pdfSign = new PdfFileSignature(inFile, outFile)
Dim rect as System.Drawing.Rectangle = new System.Drawing.Rectangle(100, 100, 200, 100)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign(2, true, rect, sig)
pdfSign.Save()
```

### Lihat Juga

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Tandatangani dokumen dengan jenis tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh mengandung kamus tanda tangan. Dengan demikian, dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan rectangle yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| SigName | String | Nama bidang tanda tangan. |
| SigReason | String | Alasan tanda tangan. |
| SigContact | String | Kontak tanda tangan. |
| SigLocation | String | Lokasi tanda tangan. |
| sig | Signature | Jenis tanda tangan, bisa PKCS1, PKCS7 dan PKCS7Detached. |

## Contoh

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PKCS1 sig = new PKCS1("certificate.pfx", "password");
PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.Sign("Signature1", "Allen", "success", "ChangSha", sig);
pdfSign.Save();

[Visual Basic]
Dim inFile As String = TestPath & "example1.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS1 = new PKCS1("certificate.pfx", "password")
Dim pdfSign = new PdfFileSignature(inFile, outFile)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign("Signature1", "Allen", "success", "ChangSha", sig)
pdfSign.Save()
```

### Lihat Juga

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Tandatangani dokumen dengan jenis tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, dokumen pdf harus sudah memiliki bidang tanda tangan, halaman dan rectangle yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Nomor halaman di mana tanda tangan dibuat. |
| SigName | String | Nama bidang tanda tangan. |
| SigReason | String | Alasan tanda tangan. |
| SigContact | String | Kontak tanda tangan. |
| SigLocation | String | Lokasi tanda tangan. |
| visible | Boolean | Visibilitas tanda tangan. |
| annotRect | Rectangle | Rect tanda tangan. |
| sig | Signature | Jenis tanda tangan, bisa PKCS1, PKCS7 dan PKCS7Detached. |

## Contoh

```csharp
[C#]
string inFile = TestPath + "blankWithSignature.pdf";
string outFile = TestPath + "signature.pdf";
PKCS7 sig = new PKCS7("certificate.pfx", "password");
PdfFileSignature pdfSign = new PdfFileSignature(inFile);
System.Drawing.Rectangle rect = new System.Drawing.Rectangle(100, 100, 100, 100);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg"
pdfSign.Sign(1, "Signature1", "ReasonToTest", "ContactMe", "SomeLocation", true, rect, sig);                
pdfSign.Save(outFile);                

[Visual Basic]
Dim inFile As String = TestPath & "blankWithSignature.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS7 = new PKCS7("certificate.pfx", "password")
Dim pdfSign = new PdfFileSignature(inFile, outFile)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign("Signature1",  "ReasonToTest", "ContactMe", "SomeLocation", true, rect, sig)
pdfSign.Save(outFile)
```

### Lihat Juga

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Tandatangani dokumen dengan jenis tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh mengandung kamus tanda tangan. Dengan demikian, dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan rectangle yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan oleh properti yang sesuai dari objek Signature sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| SigName | String | Nama bidang tanda tangan. |
| sig | Signature | Jenis tanda tangan, bisa PKCS1 (objek Pkcs1Signature), PKCS7 dan PKCS7 terpisah (objek Pkcs7Signature) |

## Contoh

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PKCS1 sig = new PKCS1("certificate.pfx", "password");
sig.Reason = "Some reason";
sig.Contact = "Smith";
sig.Location = "New York";
PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.Sign("Signature1", sig);
pdfSign.Save();

[Visual Basic]
Dim inFile As String = TestPath & "example1.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS1 = new PKCS1("certificate.pfx", "password")
sig.Reason = "Some reason"
sig.Contact = "Smith"
sig.Location = "New York"
Dim pdfSign = new PdfFileSignature(inFile, outFile)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign("Signature1", sig)
pdfSign.Save()
```

### Lihat Juga

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)