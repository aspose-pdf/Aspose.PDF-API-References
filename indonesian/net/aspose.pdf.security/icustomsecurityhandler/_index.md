---
title: "Antarmuka ICustomSecurityHandler"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Antarmuka Aspose.Pdf.Security.ICustomSecurityHandler. Antarmuka penangan keamanan khusus."
type: docs
weight: 10150
url: /id/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

Antarmuka penangan keamanan khusus.

```csharp
public interface ICustomSecurityHandler
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Mendapatkan nama filter. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Mendapatkan panjang kunci. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Mendapatkan revisi penangan atau algoritma enkripsi. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Mendapatkan nama sub-filter. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Mendapatkan versi penangan atau algoritma enkripsi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Hitung EncryptionKey. Secara umum kunci dihitung berdasarkan UserKey. Anda dapat menggunakan nilai dari EncryptionParams, yang berisi parameter saat ini pada saat pemanggilan. Nilai ini diteruskan sebagai argumen key dalam [`Encrypt`](./encrypt/) dan [`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Dekripsi array data. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Enkripsi array data. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Enkripsi bidang izin Document. Hasilnya akan ditulis ke bidang kamus enkripsi Perms. Saat membuka Document, nilai dapat diperoleh di [`EncryptionParameters`](../encryptionparameters/) melalui bidang Perms. Memungkinkan Anda memeriksa apakah izin Document telah berubah. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Membuat array terenkode berdasarkan kata sandi yang akan ditulis ke bidang O pada kamus enkripsi. Harus hanya bergantung pada argumen yang diberikan. Kata sandi pengguna dapat dihitung dari bidang ini menggunakan kata sandi pemilik. Dipanggil selama enkripsi untuk menyiapkannya dan mengisi kamus enkripsi. Nilai akan tersedia di [`CalculateEncryptionKey`](./calculateencryptionkey/) untuk mendapatkan kunci dari UserKey. Kata sandi yang ditentukan oleh pengguna saat memanggil enkripsi Document akan diteruskan. Kata sandi mungkin tidak ditentukan atau hanya satu yang dapat ditentukan. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Membuat array terenkode berdasarkan kata sandi pengguna. Nilai ini biasanya digunakan untuk memeriksa apakah kata sandi milik pengguna atau pemilik, dan untuk mendapatkan kunci enkripsi. Dipanggil selama enkripsi untuk menyiapkannya dan mengisi kamus enkripsi. Kata sandi yang ditentukan pengguna diteruskan sebagai argumen saat memanggil enkripsi Document. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Dipanggil untuk menginisialisasi instance saat ini untuk enkripsi. Perhatikan bahwa saat mengenkripsi, instance akan diisi dengan data properti yang dipindahkan `ICustomSecurityHandler`, dan saat membuka Document dari kamus enkripsi. Jika metode dipanggil selama enkripsi baru, maka [`UserKey`](../encryptionparameters/userkey/) dan [`OwnerKey`](../encryptionparameters/ownerkey/) akan bernilai null. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Periksa apakah kata sandi adalah kata sandi pemilik Document. Metode ini dipanggil setelah Initialize. Pemanggilan metode ini digunakan dalam API PDF. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Periksa apakah kata sandi milik pengguna (kata sandi untuk membuka dokumen). Metode dipanggil setelah Initialize. Pemanggilan metode digunakan dalam PDF API. |

### Lihat Juga

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


