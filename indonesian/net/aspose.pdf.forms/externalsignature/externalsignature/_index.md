---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Konstruktor ExternalSignature. Membuat tanda tangan PKCS7 terpisah menggunakan X509Certificate2. Ini mendukung token kartu pintar usb tanpa kunci pribadi yang dapat diekspor
type: docs
weight: 10
url: /id/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Membuat tanda tangan PKCS#7 `(terpisah)` menggunakan X509Certificate2. Ini mendukung kartu pintar usb, token tanpa kunci pribadi yang dapat diekspor.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| certificate | X509Certificate2 | Sertifikat dengan kunci pribadi. |

## Catatan

Algoritma digest akan dipilih secara otomatis berdasarkan data kunci sertifikat.

### Lihat Juga

* kelas [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Membuat tanda tangan PKCS#7 `(terpisah)` menggunakan X509Certificate2. Ini mendukung kartu pintar usb, token tanpa kunci pribadi yang dapat diekspor.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| certificate | X509Certificate2 | Sertifikat dengan kunci pribadi. |
| digestHashAlgorithm | DigestHashAlgorithm | Algoritma digest untuk menandatangani dokumen. |

### Lihat Juga

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* kelas [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Membuat tanda tangan PKCS#7 menggunakan X509Certificate2. Ini mendukung kartu pintar usb, token tanpa kunci pribadi yang dapat diekspor.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| certificate | X509Certificate2 | Sertifikat dengan kunci pribadi. |
| detached | Boolean | Benar jika tanda tangan harus terpisah, jika tidak salah. |

## Catatan

Untuk detached yang disetel ke false, algoritma digest akan selalu `SHA1`. Jika tidak, algoritma digest akan dipilih secara otomatis berdasarkan data kunci sertifikat (lihat Auto).

### Lihat Juga

* kelas [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Membuat tanda tangan PKCS#7 menggunakan X509Certificate2 sebagai string base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| base64 | String | X509Certificate2 sebagai string base64. |
| detached | Boolean | Benar jika tanda tangan harus terpisah, jika tidak salah. |

## Catatan

Untuk detached yang disetel ke false, algoritma digest akan selalu `SHA1`. Jika tidak, algoritma digest akan dipilih secara otomatis berdasarkan data kunci sertifikat (lihat Auto).

### Lihat Juga

* kelas [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Membuat tanda tangan PKCS#7 `(terpisah)` menggunakan X509Certificate2 sebagai string base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| base64 | String | X509Certificate2 sebagai string base64. |
| digestHashAlgorithm | DigestHashAlgorithm | Algoritma digest untuk menandatangani dokumen. |

### Lihat Juga

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* kelas [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)