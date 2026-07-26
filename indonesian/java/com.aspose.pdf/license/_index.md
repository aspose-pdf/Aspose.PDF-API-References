---
title: "License"
linktitle: "License"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menyediakan metode untuk melisensikan komponen. Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di dalam."
type: docs
weight: 2670
url: /id/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Menyediakan metode untuk melisensikan komponen. Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. License license = new License(); license.setLicense("MyLicense.lic");

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License](#License--) | Menginisialisasi instance baru dari kelas ini. Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. License license = new License(); license.setLicense("MyLicense.lic"); |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [clearLicense](#clearLicense--) | Menghapus lisensi saat ini. |
| [getLicenseInfo](#getLicenseInfo--) | Mendapatkan informasi lisensi saat ini. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | Secara default, kami menggunakan keamanan jdk default. Nilai default == false. Dalam beberapa kasus lingkungan java yang disesuaikan tidak dapat mendukung algoritma yang diperlukan, sehingga kami dapat menyarankan untuk menggunakan keamanan FIPS internal bawaan. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | Secara default, kami menggunakan keamanan jre default. Nilai default == false. Dalam beberapa kasus lingkungan java yang disesuaikan tidak dapat mendukung algoritma yang diperlukan, sehingga kami dapat menyarankan untuk menggunakan keamanan FIPS internal bawaan. <p> Perhatikan juga: Menurut algoritma JVM SecureRandom pada beberapa sistem operasi /dev/random menunggu sejumlah “noise” dihasilkan pada mesin host sebelum mengembalikan hasil. Perpustakaan yang digunakan untuk menghasilkan angka acak di JVM Oracle mengandalkan /dev/random secara default untuk platform UNIX. Meskipun /dev/random lebih aman, disarankan untuk menggunakan /dev/urandom jika konfigurasi JVM default mengalami penundaan, atau menambahkan perangkat yang menghasilkan entropi untuk /dev/random. <p> Opsi java berikut dapat membantu menghindari penundaan dan mengganti pengaturan securerandom.source. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Melisensikan komponen. Sebuah aliran yang berisi lisensi. Gunakan metode ini untuk memuat lisensi dari aliran. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Melisensikan komponen. Mencoba menemukan lisensi di lokasi berikut: 1. Jalur eksplisit. 2. Folder file jar komponen. Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Menginisialisasi instance baru dari kelas ini. Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Menghapus lisensi saat ini.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Mendapatkan informasi lisensi saat ini.

**Returns:**
Instansi LicenseInfo

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

Secara default, kami menggunakan keamanan jdk default. Nilai default == false. Dalam beberapa kasus lingkungan java yang disesuaikan tidak dapat mendukung algoritma yang diperlukan, sehingga kami dapat menyarankan untuk menggunakan keamanan FIPS internal bawaan.

**Returns:**
nilai boolean

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

Secara default, kami menggunakan keamanan jre default. Nilai default == false. Dalam beberapa kasus lingkungan java yang disesuaikan tidak dapat mendukung algoritma yang diperlukan, sehingga kami dapat menyarankan untuk menggunakan keamanan FIPS internal bawaan. <p> Perhatikan juga: Menurut algoritma JVM SecureRandom pada beberapa sistem operasi /dev/random menunggu sejumlah “noise” dihasilkan pada mesin host sebelum mengembalikan hasil. Perpustakaan yang digunakan untuk menghasilkan angka acak di JVM Oracle mengandalkan /dev/random secara default untuk platform UNIX. Meskipun /dev/random lebih aman, disarankan untuk menggunakan /dev/urandom jika konfigurasi JVM default mengalami penundaan, atau menambahkan perangkat yang menghasilkan entropi untuk /dev/random. <p> Opsi java berikut dapat membantu menghindari penundaan dan mengganti pengaturan securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| internalFIPSSecurity |  | nilai boolean |

### setLicense {#setLicense-java.io.InputStream-}
Melisensikan komponen. Sebuah aliran yang berisi lisensi. Gunakan metode ini untuk memuat lisensi dari aliran. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Melisensikan komponen. Mencoba menemukan lisensi di lokasi berikut: 1. Jalur eksplisit. 2. Folder file jar komponen. Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. License license = new License(); license.setLicense("MyLicense.lic");
