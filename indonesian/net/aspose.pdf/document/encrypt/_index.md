---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Metode dokumen. Mengenkripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi terenkripsi dari dokumen
type: docs
weight: 620
url: /id/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Mengenkripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi terenkripsi dari dokumen.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Kata sandi pemilik. |
| privileges | DocumentPrivilege | Izin dokumen, lihat [`Permissions`](../permissions/) untuk detail. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritma kriptografi, lihat [`CryptoAlgorithm`](../cryptoalgorithm/) untuk detail. |
| usePdf20 | Boolean | Dukungan untuk revisi 6 (Ekstensi 8). |

### Contoh

Contoh berikut menunjukkan cara mengenkripsi file PDF dengan [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

```csharp
[C#]

	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document document = new Document(pdfFilePath))
	{
	// Encrypt PDF
	document.Encrypt("YOUR_USER_PASSWORD", "YOUR_OWNER_PASSWORD", DocumentPrivilege.AllowAll, CryptoAlgorithm.RC4x128, true);

	// Save updated PDF
	document.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
    
	' Open document
    Using document As Document = New Document(pdfFilePath)
        ' Encrypt PDF
        document.Encrypt("YOUR_USER_PASSWORD", "YOUR_OWNER_PASSWORD", DocumentPrivilege.AllowAll, CryptoAlgorithm.RC4x128, True)
        ' Save updated PDF
        document.Save(pdfFilePath)
    End Using
```

### Lihat Juga

* kelas [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Mengenkripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi terenkripsi dari dokumen.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Kata sandi pemilik. |
| permissions | Permissions | Izin dokumen, lihat [`Permissions`](../permissions/) untuk detail. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritma kriptografi, lihat [`CryptoAlgorithm`](../cryptoalgorithm/) untuk detail. |

### Lihat Juga

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Mengenkripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi terenkripsi dari dokumen.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Kata sandi pemilik. |
| permissions | Permissions | Izin dokumen, lihat [`Permissions`](../permissions/) untuk detail. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritma kriptografi, lihat [`CryptoAlgorithm`](../cryptoalgorithm/) untuk detail. |
| usePdf20 | Boolean | Dukungan untuk revisi 6 (Ekstensi 8). |

### Lihat Juga

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)