---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode ICustomSecurityHandler. Membuat array terenkode berdasarkan kata sandi yang akan ditulis ke bidang O dari kamus enkripsi. Harus hanya mengandalkan argumen yang diberikan. Kata sandi pengguna dapat dihitung dari bidang ini menggunakan kata sandi pemilik. Dipanggil selama enkripsi untuk menyiapkannya dan mengisi kamus enkripsi. Nilai akan tersedia di CalculateEncryptionKey untuk mendapatkan kunci dari UserKey. Kata sandi yang ditentukan oleh pengguna saat memanggil enkripsi dokumen akan diteruskan. Kata sandi mungkin tidak ditentukan atau hanya satu yang dapat ditentukan."
type: docs
weight: 100
url: /id/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Membuat array terenkode berdasarkan kata sandi yang akan ditulis ke bidang O dari kamus enkripsi. Harus hanya mengandalkan argumen yang diberikan. Kata sandi pengguna dapat dihitung dari bidang ini menggunakan kata sandi pemilik. Dipanggil selama enkripsi untuk menyiapkannya dan mengisi kamus enkripsi. Nilai akan tersedia di [`CalculateEncryptionKey`](../calculateencryptionkey/) untuk mendapatkan kunci dari UserKey. Kata sandi yang ditentukan oleh pengguna saat memanggil enkripsi dokumen akan diteruskan. Kata sandi mungkin tidak ditentukan atau hanya satu yang dapat ditentukan.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Kata sandi pemilik. |

### Nilai Kembalian

Array kunci pemilik.

### Lihat Juga

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


