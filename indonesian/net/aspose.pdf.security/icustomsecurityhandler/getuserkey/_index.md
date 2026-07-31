---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode ICustomSecurityHandler. Membuat array terenkode berdasarkan kata sandi pengguna. Nilai ini biasanya digunakan untuk memeriksa apakah kata sandi termasuk milik pengguna atau pemilik serta untuk mendapatkan kunci enkripsi. Dipanggil selama enkripsi untuk menyiapkannya dan mengisi kamus enkripsi. Kata sandi yang ditentukan pengguna diteruskan sebagai argumen saat memanggil enkripsi dokumen."
type: docs
weight: 110
url: /id/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

Membuat array terenkode berdasarkan kata sandi pengguna. Nilai ini biasanya digunakan untuk memeriksa apakah kata sandi milik pengguna atau pemilik, dan untuk mendapatkan kunci enkripsi. Dipanggil selama enkripsi untuk menyiapkannya dan mengisi kamus enkripsi. Kata sandi yang ditentukan pengguna diteruskan sebagai argumen saat memanggil enkripsi Document.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |

### Nilai Kembalian

Array kunci pengguna.

### Lihat Juga

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


