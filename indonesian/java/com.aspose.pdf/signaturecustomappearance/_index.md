---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas abstrak yang mewakili objek tampilan khusus tanda tangan."
type: docs
weight: 4500
url: /id/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

Kelas abstrak yang mewakili objek tampilan khusus tanda tangan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | Menginisialisasi instance baru dari kelas {@link SignatureCustomAppearance}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | Mendapatkan/mengatur warna latar belakang. Nilai default: Transparan. |
| [getContactInfoLabel](#getContactInfoLabel--) | Mendapatkan/mengatur label info kontak. Nilai default: "Contact". |
| [getCulture](#getCulture--) | Mendapatkan/mengatur nilai info budaya. Nilai default: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | Mendapatkan/mengatur label tanggal ditandatangani. Nilai default: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | Mendapatkan/mengatur format datetime. Nilai default: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | Mendapatkan/mengatur format datetime lokal. Nilai default: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | Mendapatkan/mengatur label tanda tangan digital. Nilai default: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Mendapatkan/mengatur format urutan elemen dalam string Subject. Contoh hasil: C=UK, CN=Org, O=Organization atau CN=Org, C=UK, O=Organization atau O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | Mendapatkan/mengatur nama keluarga font. Harus ada dalam dokumen. Nilai default: Arial. |
| [getFontSize](#getFontSize--) | Mendapatkan/mengatur ukuran font. Nilai default: 10. |
| [getForegroundColor](#getForegroundColor--) | Mendapatkan/mengatur warna latar depan (warna teks). Nilai default: Biru. |
| [getLocationLabel](#getLocationLabel--) | Mendapatkan/mengatur label lokasi. Nilai default: "Location". |
| [getReasonLabel](#getReasonLabel--) | Mendapatkan/mengatur label alasan. Nilai default: "Reason". |
| [getRotation](#getRotation--) | Mendapatkan atau mengatur rotasi tanda tangan. |
| [isForegroundImage](#isForegroundImage--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar dalam tampilan tanda tangan digambar sebagai gambar latar depan. Nilai default: false. |
| [isShowContactInfo](#isShowContactInfo--) | Mendapatkan/mengatur visibilitas info kontak. Nilai default: true. |
| [isShowLocation](#isShowLocation--) | Mendapatkan/mengatur visibilitas lokasi. Nilai default: true. |
| [isShowReason](#isShowReason--) | Mendapatkan/mengatur visibilitas alasan. Nilai default: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | Mendapatkan/mengatur status penggunaan {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mendapatkan/mengatur warna latar belakang. Nilai default: Transparan. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | Mendapatkan/mengatur label info kontak. Nilai default: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | Mendapatkan/mengatur nilai informasi budaya. |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | Mendapatkan/mengatur label tanggal ditandatangani. Nilai default: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | Mendapatkan/mengatur format datetime. Nilai default: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | Mendapatkan/mengatur format datetime lokal. Nilai default: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | Mendapatkan/mengatur label tanda tangan digital. Nilai default: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Mendapatkan/mengatur format urutan elemen dalam string Subject. Contoh hasil: C=UK, CN=Org, O=Organization atau CN=Org, C=UK, O=Organization atau O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | Mendapatkan/mengatur nama keluarga font. Harus ada dalam dokumen. Nilai default: Arial. |
| [setFontSize](#setFontSize-double-) | Mendapatkan/mengatur ukuran font. Nilai default: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Mendapatkan/mengatur warna latar depan (warna teks). Nilai default: Biru. |
| [setForegroundImage](#setForegroundImage-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar dalam tampilan tanda tangan digambar sebagai gambar latar depan. Nilai default: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | Mendapatkan/mengatur label lokasi. Nilai default: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | Mendapatkan/mengatur label alasan. Nilai default: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | Mendapatkan atau mengatur rotasi tanda tangan. |
| [setShowContactInfo](#setShowContactInfo-boolean-) | Mendapatkan/mengatur visibilitas info kontak. Nilai default: true. |
| [setShowLocation](#setShowLocation-boolean-) | Mendapatkan/mengatur visibilitas lokasi. Nilai default: true. |
| [setShowReason](#setShowReason-boolean-) | Mendapatkan/mengatur visibilitas alasan. Nilai default: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | Mendapatkan/mengatur status penggunaan {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}). |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

Menginisialisasi instance baru dari kelas {@link SignatureCustomAppearance}.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Mendapatkan/mengatur warna latar belakang. Nilai default: Transparan.

**Returns:**
instance com.aspose.pdf.Color

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

Mendapatkan/mengatur label info kontak. Nilai default: "Contact".

**Returns:**
nilai String

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

Mendapatkan/mengatur nilai info budaya. Nilai default: InvariantCulture.

**Returns:**
nilai Locale

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

Mendapatkan/mengatur label tanggal ditandatangani. Nilai default: "Date".

**Returns:**
nilai String

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

Mendapatkan/mengatur format datetime. Nilai default: "yyyy.MM.dd HH:mm:ss".

**Returns:**
nilai String

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

Mendapatkan/mengatur format datetime lokal. Nilai default: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
nilai String

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

Mendapatkan/mengatur label tanda tangan digital. Nilai default: "Digitally signed by".

**Returns:**
nilai String

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Mendapatkan/mengatur format urutan elemen dalam string Subject. Contoh hasil: C=UK, CN=Org, O=Organization atau CN=Org, C=UK, O=Organization atau O=Organization

**Returns:**
array of int @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

Mendapatkan/mengatur nama keluarga font. Harus ada dalam dokumen. Nilai default: Arial.

**Returns:**
nilai String

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

Mendapatkan/mengatur ukuran font. Nilai default: 10.

**Returns:**
nilai double

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Mendapatkan/mengatur warna latar depan (warna teks). Nilai default: Biru.

**Returns:**
instance com.aspose.pdf.Color

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

Mendapatkan/mengatur label lokasi. Nilai default: "Location".

**Returns:**
nilai String

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

Mendapatkan/mengatur label alasan. Nilai default: "Reason".

**Returns:**
nilai String

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

Mendapatkan atau mengatur rotasi tanda tangan.

**Returns:**
elemen Rotasi

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar dalam tampilan tanda tangan digambar sebagai gambar latar depan. Nilai default: false.

**Returns:**
nilai boolean

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

Mendapatkan/mengatur visibilitas info kontak. Nilai default: true.

**Returns:**
nilai boolean

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

Mendapatkan/mengatur visibilitas lokasi. Nilai default: true.

**Returns:**
nilai boolean

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

Mendapatkan/mengatur visibilitas alasan. Nilai default: true.

**Returns:**
nilai boolean

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

Mendapatkan/mengatur status penggunaan {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Returns:**
nilai boolean

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mendapatkan/mengatur warna latar belakang. Nilai default: Transparan.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
Mendapatkan/mengatur label info kontak. Nilai default: "Contact".

### setCulture {#setCulture-java.util.Locale-}
Mendapatkan/mengatur nilai informasi budaya.

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
Mendapatkan/mengatur label tanggal ditandatangani. Nilai default: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
Mendapatkan/mengatur format datetime. Nilai default: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
Mendapatkan/mengatur format datetime lokal. Nilai default: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
Mendapatkan/mengatur label tanda tangan digital. Nilai default: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Mendapatkan/mengatur format urutan elemen dalam string Subject. Contoh hasil: C=UK, CN=Org, O=Organization atau CN=Org, C=UK, O=Organization atau O=Organization

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | array of int @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
Mendapatkan/mengatur nama keluarga font. Harus ada dalam dokumen. Nilai default: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

Mendapatkan/mengatur ukuran font. Nilai default: 10.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Mendapatkan/mengatur warna latar depan (warna teks). Nilai default: Biru.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar dalam tampilan tanda tangan digambar sebagai gambar latar depan. Nilai default: false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLocationLabel {#setLocationLabel-java.lang.String-}
Mendapatkan/mengatur label lokasi. Nilai default: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
Mendapatkan/mengatur label alasan. Nilai default: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
Mendapatkan atau mengatur rotasi tanda tangan.

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

Mendapatkan/mengatur visibilitas info kontak. Nilai default: true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

Mendapatkan/mengatur visibilitas lokasi. Nilai default: true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

Mendapatkan/mengatur visibilitas alasan. Nilai default: true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

Mendapatkan/mengatur status penggunaan {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
