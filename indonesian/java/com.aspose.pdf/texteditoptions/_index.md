---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menjelaskan opsi operasi penyuntingan teks."
type: docs
weight: 4970
url: /id/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Menjelaskan opsi operasi penyuntingan teks.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Menginisialisasi instance baru dari objek {@code TextEditOptions} untuk mode penataan ulang teks yang ditentukan. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Mendapatkan nilai yang memungkinkan penggunaan transformasi bahasa saat menambahkan atau mengedit teks. true - transformasi bahasa akan diterapkan jika diperlukan (nilai default). false - transformasi bahasa TIDAK akan diterapkan. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Mendapatkan mode untuk memproses clipping path teks yang diedit. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Mendapatkan mode yang menentukan perilaku untuk skenario penggantian font. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Mendapatkan mode yang menentukan perilaku untuk skenario transformasi bahasa. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Mendapatkan mode yang menentukan perilaku jika font tidak mengandung karakter yang diminta. |
| [getReplacementFont](#getReplacementFont--) | Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Mendapatkan atau mengatur nilai yang memungkinkan pencarian garis bawah teks pada halaman dokumen sumber. <p> (Usang) Silakan gunakan TextSearchOptions.SearchForTextRelatedGraphics alih-alih ini. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Mengatur nilai yang memungkinkan penggunaan transformasi bahasa saat menambahkan atau mengedit teks. true - transformasi bahasa akan diterapkan jika diperlukan (nilai default). false - transformasi bahasa TIDAK akan diterapkan. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Mendapatkan mode untuk memproses clipping path teks yang diedit. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Mengatur mode yang menentukan perilaku untuk skenario penggantian font. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Mengatur mode yang menentukan perilaku untuk skenario transformasi bahasa. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Mengatur mode yang menentukan perilaku jika font tidak mengandung karakter yang diminta. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Mendapatkan atau mengatur nilai yang memungkinkan pencarian garis bawah teks pada halaman dokumen sumber. <p> (Usang) Silakan gunakan TextSearchOptions.SearchForTextRelatedGraphics alih-alih ini. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Menginisialisasi instance baru dari objek {@code TextEditOptions} untuk mode penataan ulang teks yang ditentukan. / * / *

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Menginisialisasi instance baru dari objek {@code TextEditOptions} dengan opsi default. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Mendapatkan nilai yang memungkinkan penggunaan transformasi bahasa saat menambahkan atau mengedit teks. true - transformasi bahasa akan diterapkan jika diperlukan (nilai default). false - transformasi bahasa TIDAK akan diterapkan.

**Returns:**
nilai boolean

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Mendapatkan mode untuk memproses clipping path teks yang diedit.

**Returns:**
Elemen ClippingPathsProcessingMode

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Mendapatkan mode yang menentukan perilaku untuk skenario penggantian font.

**Returns:**
FontReplace nilai @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Mendapatkan mode yang menentukan perilaku untuk skenario transformasi bahasa.

**Returns:**
LanguageTransformation nilai @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Mendapatkan mode yang menentukan perilaku jika font tidak mengandung karakter yang diminta.

**Returns:**
NoCharacterAction nilai @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan

**Returns:**
Instansi Font

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Mendapatkan atau mengatur nilai yang memungkinkan pencarian garis bawah teks pada halaman dokumen sumber. <p> (Usang) Silakan gunakan TextSearchOptions.SearchForTextRelatedGraphics alih-alih ini. </p>

**Returns:**
nilai boolean

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Mengatur nilai yang memungkinkan penggunaan transformasi bahasa saat menambahkan atau mengedit teks. true - transformasi bahasa akan diterapkan jika diperlukan (nilai default). false - transformasi bahasa TIDAK akan diterapkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Mendapatkan mode untuk memproses clipping path teks yang diedit.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Mengatur mode yang menentukan perilaku untuk skenario penggantian font.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Mengatur mode yang menentukan perilaku untuk skenario transformasi bahasa.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Mengatur mode yang menentukan perilaku jika font tidak mengandung karakter yang diminta.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Mendapatkan atau mengatur nilai yang memungkinkan pencarian garis bawah teks pada halaman dokumen sumber. <p> (Usang) Silakan gunakan TextSearchOptions.SearchForTextRelatedGraphics alih-alih ini. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
