---
title: "Signature"
linktitle: "Signature"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Sebuah kelas abstrak yang mewakili objek tanda tangan dalam dokumen pdf. Tanda tangan adalah bidang dengan nilai objek tanda tangan, yang terakhir berisi data yang digunakan untuk memverifikasi."
type: docs
weight: 4490
url: /id/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

Kelas abstrak yang mewakili objek tanda tangan dalam dokumen pdf. Tanda tangan adalah bidang dengan nilai objek tanda tangan, yang terakhir berisi data yang digunakan untuk memverifikasi keabsahan dokumen.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Signature](#Signature--) | Menginisialisasi instance baru dari kelas {@code Signature}. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Menginisialisasi instance baru dari kelas {@code Signature}. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas {@code Signature}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [close](#close--) | Destruktor yang menutup aliran sementara (jika diperlukan). |
| [getAuthority](#getAuthority--) | Nama orang atau otoritas yang menandatangani dokumen. |
| [getByteRange](#getByteRange--) | Dapatkan array pasangan bilangan bulat (offset byte mulai, panjang dalam byte) yang akan menggambarkan rentang byte yang tepat untuk perhitungan digest. |
| [getContactInfo](#getContactInfo--) | Dapatkan informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan guna memverifikasi tanda tangan, misalnya nomor telepon. |
| [getCustomAppearance](#getCustomAppearance--) | Mendapatkan/mengatur tampilan khusus. |
| [getCustomSign](#getCustomSign--) | Delegasi untuk hash khusus dan menandatangani dokumen (Beta). {@code Algoritma yang Anda gunakan untuk melakukan hash dan menandatangani dokumen dalam delegasi harus cocok dengan tipe kunci pribadi sertifikat.} |
| [getCustomSignHash](#getCustomSignHash--) | Delegasi untuk menandatangani hash dokumen secara khusus (Beta). {@code Algoritma yang Anda gunakan untuk menandatangani hash dalam delegasi harus cocok dengan tipe kunci pribadi sertifikat.} |
| [getDate](#getDate--) | Mendapatkan waktu penandatanganan. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | Mendapatkan atau mengatur panjang default untuk data tanda tangan dalam byte. Ini adalah perkiraan panjang tanda tangan dalam byte. Digunakan untuk penandatanganan melalui {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) jika parameter {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) diatur. Nilai default adalah 3000. |
| [getImageInternal](#getImageInternal--) | Mendapatkan aliran gambar. Hanya untuk penggunaan internal. |
| [getLocation](#getLocation--) | Mendapatkan nama host CPU atau lokasi fisik penandatanganan. |
| [getOcspSettings](#getOcspSettings--) | Mendapatkan/mengatur pengaturan ocsp. |
| [getReason](#getReason--) | Mendapatkan alasan penandatanganan, seperti (Saya setuju!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | Mengambil informasi tentang algoritma tanda tangan yang digunakan dalam tanda tangan. |
| [getSignatureReferences](#getSignatureReferences--) | dapatkan Referensi Tanda Tangan |
| [getTimestampSettings](#getTimestampSettings--) | Mendapatkan pengaturan timestamp. |
| [getUseLtv](#getUseLtv--) | Mendapatkan/mengatur flag validasi ltv. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | Mendapatkan dan mengatur opsi yang menentukan apakah menghindari perkiraan panjang tanda tangan. Menghindari memperkirakan panjang tanda tangan sebelum dokumen ditandatangani. Digunakan untuk penandatanganan melalui {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) dan melalui {@code ExternalSignature}. Jika {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) mengembalikan tanda tangan yang lebih panjang daripada {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), maka {@code SignatureLengthMismatchException} akan dilempar. Nilai default adalah {@code false}. |
| [isShowProperties](#isShowProperties--) | Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties bernilai true, bidang tanda tangan memiliki format tampilan yang telah ditentukan (string untuk merepresentasikan): ------------------------------------------- Ditandatangani secara digital oleh {certificate subject} Tanggal: {signature.Date} Alasan: {signature.Reason} Lokasi: {signature.Location} ------------------------------------------- dimana {X} adalah placeholder untuk nilai X. Tanda tangan juga dapat memiliki gambar, dalam hal ini string yang terdaftar ditempatkan di atas gambar. ShowProperties bernilai true secara default. |
| [setAuthority](#setAuthority-java.lang.String-) | Mengatur nama orang atau otoritas yang menandatangani dokumen. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | Mendapatkan dan mengatur opsi yang menentukan apakah menghindari perkiraan panjang tanda tangan. Menghindari memperkirakan panjang tanda tangan sebelum dokumen ditandatangani. Digunakan untuk penandatanganan melalui {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) dan melalui {@code ExternalSignature}. Jika {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) mengembalikan tanda tangan yang lebih panjang daripada {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), maka {@code SignatureLengthMismatchException} akan dilempar. Nilai default adalah {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | Mengatur informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan guna memverifikasi tanda tangan, misalnya nomor telepon. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Mendapatkan/mengatur tampilan khusus. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | Delegasi untuk hash khusus dan menandatangani dokumen (Beta). {@code Algoritma yang Anda gunakan untuk melakukan hash dan menandatangani dokumen dalam delegasi harus cocok dengan tipe kunci pribadi sertifikat.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | Delegasi untuk menandatangani hash dokumen secara khusus (Beta). {@code Algoritma yang Anda gunakan untuk menandatangani hash dalam delegasi harus cocok dengan tipe kunci pribadi sertifikat.} |
| [setDate](#setDate-java.util.Date-) | Mengatur waktu penandatanganan. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | Mendapatkan atau mengatur panjang default untuk data tanda tangan dalam byte. Ini adalah perkiraan panjang tanda tangan dalam byte. Digunakan untuk penandatanganan melalui {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) jika parameter {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) diatur. Nilai default adalah 3000. |
| [setImage](#setImage-java.io.InputStream-) | Mengatur aliran gambar. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | Mengatur nama host CPU atau lokasi fisik penandatanganan. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Mendapatkan/mengatur pengaturan ocsp. |
| [setReason](#setReason-java.lang.String-) | Mengatur alasan penandatanganan, seperti (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties bernilai true, bidang tanda tangan memiliki format tampilan yang telah ditentukan (string untuk merepresentasikan): ------------------------------------------- Ditandatangani secara digital oleh {certificate subject} Tanggal: {signature.Date} Alasan: {signature.Reason} Lokasi: {signature.Location} ------------------------------------------- dimana {X} adalah placeholder untuk nilai X. Tanda tangan juga dapat memiliki gambar, dalam hal ini string yang terdaftar ditempatkan di atas gambar. ShowProperties bernilai true secara default. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Mengatur pengaturan cap waktu. |
| [setUseLtv](#setUseLtv-boolean-) | Mendapatkan/mengatur flag validasi ltv. |
| [verify](#verify--) | Verifikasi dokumen terkait tanda tangan ini dan kembalikan true jika dokumen valid atau false sebaliknya. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifikasi dokumen terkait tanda tangan ini dan kembalikan true jika dokumen valid atau false sebaliknya. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifikasi dokumen terkait tanda tangan ini dan kembalikan true jika dokumen valid atau false sebaliknya. |

### Signature {#Signature--}
```
public Signature()
```

Menginisialisasi instance baru dari kelas {@code Signature}.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Menginisialisasi instance baru dari kelas {@code Signature}.

### Signature {#Signature-java.lang.String-java.lang.String-}
Menginisialisasi instance baru dari kelas {@code Signature}.

### close {#close--}
```
public void close()
```

Destruktor yang menutup aliran sementara (jika diperlukan).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

Nama orang atau otoritas yang menandatangani dokumen.

**Returns:**
nilai String

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Dapatkan array pasangan bilangan bulat (offset byte mulai, panjang dalam byte) yang akan menggambarkan rentang byte yang tepat untuk perhitungan digest.

**Returns:**
array nilai int

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

Dapatkan informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan guna memverifikasi tanda tangan, misalnya nomor telepon.

**Returns:**
nilai String

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Mendapatkan/mengatur tampilan khusus.

**Returns:**
instance SignatureCustomAppearance

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

Delegasi untuk hash khusus dan menandatangani dokumen (Beta). {@code Algoritma yang Anda gunakan untuk melakukan hash dan menandatangani dokumen dalam delegasi harus cocok dengan tipe kunci pribadi sertifikat.}

**Returns:**
instance SignHash

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

Delegasi untuk menandatangani hash dokumen secara khusus (Beta). {@code Algoritma yang Anda gunakan untuk menandatangani hash dalam delegasi harus cocok dengan tipe kunci pribadi sertifikat.}

**Returns:**
instance SignHash

### getDate {#getDate--}
```
public Date getDate()
```

Mendapatkan waktu penandatanganan.

**Returns:**
nilai Date

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

Mendapatkan atau mengatur panjang default untuk data tanda tangan dalam byte. Ini adalah perkiraan panjang tanda tangan dalam byte. Digunakan untuk penandatanganan melalui {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) jika parameter {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) diatur. Nilai default adalah 3000.

**Returns:**
nilai int

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Mendapatkan aliran gambar. Hanya untuk penggunaan internal.

**Returns:**
objek Stream

### getLocation {#getLocation--}
```
public String getLocation()
```

Mendapatkan nama host CPU atau lokasi fisik penandatanganan.

**Returns:**
nilai String

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

Mendapatkan/mengatur pengaturan ocsp.

**Returns:**
instance OcspSettings

### getReason {#getReason--}
```
public String getReason()
```

Mendapatkan alasan penandatanganan, seperti (Saya setuju!, Pip B.).

**Returns:**
nilai String

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

Mengambil informasi tentang algoritma tanda tangan yang digunakan dalam tanda tangan.

**Returns:**
Sebuah instance dari { SignatureAlgorithmInfo} yang berisi detail tentang algoritma tanda tangan.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

dapatkan Referensi Tanda Tangan

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Mendapatkan pengaturan timestamp.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

Mendapatkan/mengatur flag validasi ltv.

**Returns:**
nilai boolean

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

Mendapatkan dan mengatur opsi yang menentukan apakah menghindari perkiraan panjang tanda tangan. Menghindari memperkirakan panjang tanda tangan sebelum dokumen ditandatangani. Digunakan untuk penandatanganan melalui {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) dan melalui {@code ExternalSignature}. Jika {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) mengembalikan tanda tangan yang lebih panjang daripada {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), maka {@code SignatureLengthMismatchException} akan dilempar. Nilai default adalah {@code false}.

**Returns:**
nilai boolean

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties bernilai true, bidang tanda tangan memiliki format tampilan yang telah ditentukan (string untuk merepresentasikan): ------------------------------------------- Ditandatangani secara digital oleh {certificate subject} Tanggal: {signature.Date} Alasan: {signature.Reason} Lokasi: {signature.Location} ------------------------------------------- dimana {X} adalah placeholder untuk nilai X. Tanda tangan juga dapat memiliki gambar, dalam hal ini string yang terdaftar ditempatkan di atas gambar. ShowProperties bernilai true secara default.

**Returns:**
nilai boolean

### setAuthority {#setAuthority-java.lang.String-}
Mengatur nama orang atau otoritas yang menandatangani dokumen.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

Mendapatkan dan mengatur opsi yang menentukan apakah menghindari perkiraan panjang tanda tangan. Menghindari memperkirakan panjang tanda tangan sebelum dokumen ditandatangani. Digunakan untuk penandatanganan melalui {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) dan melalui {@code ExternalSignature}. Jika {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) mengembalikan tanda tangan yang lebih panjang daripada {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), maka {@code SignatureLengthMismatchException} akan dilempar. Nilai default adalah {@code false}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setContactInfo {#setContactInfo-java.lang.String-}
Mengatur informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan guna memverifikasi tanda tangan, misalnya nomor telepon.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Mendapatkan/mengatur tampilan khusus.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
Delegasi untuk hash khusus dan menandatangani dokumen (Beta). {@code Algoritma yang Anda gunakan untuk melakukan hash dan menandatangani dokumen dalam delegasi harus cocok dengan tipe kunci pribadi sertifikat.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
Delegasi untuk menandatangani hash dokumen secara khusus (Beta). {@code Algoritma yang Anda gunakan untuk menandatangani hash dalam delegasi harus cocok dengan tipe kunci pribadi sertifikat.}

### setDate {#setDate-java.util.Date-}
Mengatur waktu penandatanganan.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

Mendapatkan atau mengatur panjang default untuk data tanda tangan dalam byte. Ini adalah perkiraan panjang tanda tangan dalam byte. Digunakan untuk penandatanganan melalui {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) jika parameter {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) diatur. Nilai default adalah 3000.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setImage {#setImage-java.io.InputStream-}
Mengatur aliran gambar.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
Mengatur nama host CPU atau lokasi fisik penandatanganan.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
Mendapatkan/mengatur pengaturan ocsp.

### setReason {#setReason-java.lang.String-}
Mengatur alasan penandatanganan, seperti (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties bernilai true, bidang tanda tangan memiliki format tampilan yang telah ditentukan (string untuk merepresentasikan): ------------------------------------------- Ditandatangani secara digital oleh {certificate subject} Tanggal: {signature.Date} Alasan: {signature.Reason} Lokasi: {signature.Location} ------------------------------------------- dimana {X} adalah placeholder untuk nilai X. Tanda tangan juga dapat memiliki gambar, dalam hal ini string yang terdaftar ditempatkan di atas gambar. ShowProperties bernilai true secara default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Mengatur pengaturan cap waktu.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

Mendapatkan/mengatur flag validasi ltv.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### verify {#verify--}
```
public boolean verify()
```

Verifikasi dokumen terkait tanda tangan ini dan kembalikan true jika dokumen valid atau false sebaliknya.

**Returns:**
true jika dokumen valid.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifikasi dokumen terkait tanda tangan ini dan kembalikan true jika dokumen valid atau false sebaliknya.

**Returns:**
true jika dokumen valid.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifikasi dokumen terkait tanda tangan ini dan kembalikan true jika dokumen valid atau false sebaliknya.

**Returns:**
true jika dokumen valid.
