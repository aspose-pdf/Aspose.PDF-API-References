---
title: "Document.Encrypt"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Document. Mengenkripsi dokumen"
type: docs
weight: 640
url: /id/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

Mengenkripsi document.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| permissions | Permissions | Izin Document, lihat [`Permissions`](../permissions/) untuk detail. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritma kriptografi, lihat [`CryptoAlgorithm`](../cryptoalgorithm/) untuk detail. |
| publicCertificates | IList`1 | Sertifikat publik yang digunakan untuk enkripsi — satu per penerima. |

## Catatan

Metode ini mempersiapkan enkripsi. Untuk mengenkripsi dokumen, Anda perlu memanggil metode Save untuk menyimpannya.

### Lihat Juga

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

Mengenkripsi document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Password pemilik. |
| privileges | DocumentPrivilege | Izin Document, lihat [`Permissions`](../permissions/) untuk detail. |
| customHandler | ICustomSecurityHandler | Handler keamanan khusus. |

## Catatan

Metode ini mempersiapkan enkripsi. Untuk mengenkripsi dokumen, Anda perlu memanggil metode Save untuk menyimpannya.

### Lihat Juga

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

Mengenkripsi document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Password pemilik. |
| permissions | Permissions | Izin Document, lihat [`Permissions`](../permissions/) untuk detail. |
| customHandler | ICustomSecurityHandler | Handler keamanan khusus. |

## Catatan

Metode ini mempersiapkan enkripsi. Untuk mengenkripsi dokumen, Anda perlu memanggil metode Save untuk menyimpannya.

### Lihat Juga

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

Mengenkripsi document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Password pemilik. |
| privileges | DocumentPrivilege | Izin Document, lihat [`Permissions`](../permissions/) untuk detail. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritma kriptografi, lihat [`CryptoAlgorithm`](../cryptoalgorithm/) untuk detail. |
| usePdf20 | Boolean | Dukungan untuk revisi 6 (Ekstensi 8). |

## Catatan

Metode ini mempersiapkan enkripsi. Untuk mengenkripsi dokumen, Anda perlu memanggil metode Save untuk menyimpannya.

### Lihat Juga

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

Mengenkripsi document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Password pemilik. |
| permissions | Permissions | Izin Document, lihat [`Permissions`](../permissions/) untuk detail. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritma kriptografi, lihat [`CryptoAlgorithm`](../cryptoalgorithm/) untuk detail. |

## Catatan

Metode ini mempersiapkan enkripsi. Untuk mengenkripsi dokumen, Anda perlu memanggil metode Save untuk menyimpannya.

### Lihat Juga

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

Mengenkripsi document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Password pemilik. |
| permissions | Permissions | Izin Document, lihat [`Permissions`](../permissions/) untuk detail. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritma kriptografi, lihat [`CryptoAlgorithm`](../cryptoalgorithm/) untuk detail. |
| usePdf20 | Boolean | Dukungan untuk revisi 6 (Ekstensi 8). |

## Catatan

Metode ini mempersiapkan enkripsi. Untuk mengenkripsi dokumen, Anda perlu memanggil metode Save untuk menyimpannya.

### Lihat Juga

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


