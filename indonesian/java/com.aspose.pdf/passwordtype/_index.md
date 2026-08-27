---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Enum ini mewakili tipe kata sandi yang dikenal yang digunakan untuk dokumen PDF yang dilindungi kata sandi."
type: docs
weight: 3520
url: /id/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

Enum ini mewakili tipe kata sandi yang dikenal yang digunakan untuk dokumen PDF yang dilindungi kata sandi.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Inaccessible](#Inaccessible) | Dokumen PDF dilindungi kata sandi, namun kedua kata sandi pengguna dan pemilik tidak kosong, dan tidak ada kata sandi yang didefinisikan atau kata sandi yang diberikan salah. |
| [None](#None) | Dokumen PDF tidak dilindungi kata sandi. |
| [Owner](#Owner) | Dokumen PDF dibuka menggunakan kata sandi ubah izin (akses penuh). |
| [User](#User) | Dokumen PDF dibuka menggunakan kata sandi buka dokumen (akses terbatas). |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan. |
| [values](#values--) | Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

Dokumen PDF dilindungi kata sandi, namun kedua kata sandi pengguna dan pemilik tidak kosong, dan tidak ada kata sandi yang didefinisikan atau kata sandi yang diberikan salah.

### None {#None}
```
public static final PasswordType None
```

Dokumen PDF tidak dilindungi kata sandi.

### Owner {#Owner}
```
public static final PasswordType Owner
```

Dokumen PDF dibuka menggunakan kata sandi ubah izin (akses penuh).

### User {#User}
```
public static final PasswordType User
```

Dokumen PDF dibuka menggunakan kata sandi buka dokumen (akses terbatas).

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan.

### values {#values--}
```
public static PasswordType [] values()
```

Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan.

**Returns:**
array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan
