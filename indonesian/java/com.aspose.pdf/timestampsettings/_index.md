---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili pengaturan ocsp yang digunakan selama proses penandatanganan."
type: docs
weight: 5360
url: /id/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

Mewakili pengaturan ocsp yang digunakan selama proses penandatanganan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas {@code TimestampSettings}. |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Menginisialisasi sebuah instance baru dari kelas {@code TimestampSettings}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | Mendapatkan kredensial otentikasi dasar, Username dan password digabungkan menjadi string "username:password". |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | Mendapatkan/mengatur algoritma digest untuk fungsi hash internal. |
| [getServerUrl](#getServerUrl--) | Mendapatkan url server timestamp. |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | Mengatur kredensial otentikasi dasar, Username dan password digabungkan menjadi string "username:password". |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | Mendapatkan/mengatur algoritma digest untuk fungsi hash internal. |
| [setServerUrl](#setServerUrl-java.lang.String-) | Mengatur url server timestamp. |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
Menginisialisasi sebuah instance baru dari kelas {@code TimestampSettings}.

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Menginisialisasi sebuah instance baru dari kelas {@code TimestampSettings}.

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

Mendapatkan kredensial otentikasi dasar, Username dan password digabungkan menjadi string "username:password".

**Returns:**
nilai String

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

Mendapatkan/mengatur algoritma digest untuk fungsi hash internal.

**Returns:**
elemen DigestHashAlgorithm @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

Mendapatkan url server timestamp.

**Returns:**
nilai String

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
Mengatur kredensial otentikasi dasar, Username dan password digabungkan menjadi string "username:password".

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
Mendapatkan/mengatur algoritma digest untuk fungsi hash internal.

### setServerUrl {#setServerUrl-java.lang.String-}
Mengatur url server timestamp.
