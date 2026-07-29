---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi penggantian teks"
type: docs
weight: 5250
url: /id/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Mewakili opsi penggantian teks

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Menginisialisasi instance baru dari objek {@code TextReplaceOptions} untuk penyesuaian default dan ruang lingkup: ReplaceAdjustment.None dan Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Menginisialisasi instance baru dari objek {@code TextReplaceOptions} untuk aksi setelah penggantian yang ditentukan. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Menginisialisasi instance baru dari objek {@code TextReplaceOptions} untuk penyesuaian default dan ruang lingkup: ReplaceAdjustment.None dan Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Menginisialisasi instance baru dari objek {@code TextReplaceOptions} untuk penyesuaian default dan ruang lingkup: ReplaceAdjustment.None dan Scope.REPLACE_FIRST |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Mendapatkan atau mengatur nilai spasi baris yang digunakan jika penyesuaian penggantian dipaksa untuk membuat baris teks baru. Nilai yang diharapkan adalah pengali ukuran font teks yang diganti. Default adalah 1.2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | Mendapatkan atau mengatur kebijakan untuk menyesuaikan ukuran font agar sesuai dengan batas yang didefinisikan oleh {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}). |
| [getLeftAdjustment](#getLeftAdjustment--) | Mendapatkan penyesuaian posisi kiri untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | Mendapatkan atau mengatur persegi panjang untuk menyesuaikan teks setelah penggantian. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Mendapatkan aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek. |
| [getReplaceScope](#getReplaceScope--) | Mendapatkan ruang lingkup dimana operasi penggantian teks diterapkan |
| [getRightAdjustment](#getRightAdjustment--) | Mengatur atau mendapatkan penyesuaian posisi kanan untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan paragraf terpisah saat menyesuaikan teks pada halaman setelah penggantian teks. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Mendapatkan atau mengatur nilai spasi baris yang digunakan jika penyesuaian penggantian dipaksa untuk membuat baris teks baru. Nilai yang diharapkan adalah pengali ukuran font teks yang diganti. Default adalah 1.2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | Mendapatkan atau mengatur kebijakan untuk menyesuaikan ukuran font agar sesuai dengan batas yang didefinisikan oleh TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan paragraf terpisah saat menyesuaikan teks pada halaman setelah penggantian teks. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | Mengatur atau mendapatkan penyesuaian posisi kiri untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Mendapatkan atau mengatur persegi panjang untuk menyesuaikan teks setelah penggantian. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Mengatur aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Mengatur ruang lingkup dimana operasi penggantian teks diterapkan |
| [setRightAdjustment](#setRightAdjustment-double-) | Mengatur penyesuaian posisi kanan untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Menginisialisasi instance baru dari objek {@code TextReplaceOptions} untuk penyesuaian default dan ruang lingkup: ReplaceAdjustment.None dan Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Menginisialisasi instance baru dari objek {@code TextReplaceOptions} untuk aksi setelah penggantian yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| penyesuaian |  | Objek ReplaceAdjustment. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Menginisialisasi instance baru dari objek {@code TextReplaceOptions} untuk penyesuaian default dan ruang lingkup: ReplaceAdjustment.None dan Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Menginisialisasi instance baru dari objek {@code TextReplaceOptions} untuk penyesuaian default dan ruang lingkup: ReplaceAdjustment.None dan Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Mendapatkan atau mengatur nilai spasi baris yang digunakan jika penyesuaian penggantian dipaksa untuk membuat baris teks baru. Nilai yang diharapkan adalah pengali ukuran font teks yang diganti. Default adalah 1.2.

**Returns:**
nilai double

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

Mendapatkan atau mengatur kebijakan untuk menyesuaikan ukuran font agar sesuai dengan batas yang didefinisikan oleh {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}).

**Returns:**
Elemen FontSizeAdjustment

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

Mendapatkan penyesuaian posisi kiri untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
nilai double

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Mendapatkan atau mengatur persegi panjang untuk menyesuaikan teks setelah penggantian.

**Returns:**
Instansi Rectangle

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Mendapatkan aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek.

**Returns:**
Elemen ReplaceAdjustment @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Mendapatkan ruang lingkup dimana operasi penggantian teks diterapkan

**Returns:**
nilai int @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

Mengatur atau mendapatkan penyesuaian posisi kanan untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
nilai double

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan paragraf terpisah saat menyesuaikan teks pada halaman setelah penggantian teks.

**Returns:**
boolean nilai

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Mendapatkan atau mengatur nilai spasi baris yang digunakan jika penyesuaian penggantian dipaksa untuk membuat baris teks baru. Nilai yang diharapkan adalah pengali ukuran font teks yang diganti. Default adalah 1.2.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
Mendapatkan atau mengatur kebijakan untuk menyesuaikan ukuran font agar sesuai dengan batas yang didefinisikan oleh TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan paragraf terpisah saat menyesuaikan teks pada halaman setelah penggantian teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

Mengatur atau mendapatkan penyesuaian posisi kiri untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Mendapatkan atau mengatur persegi panjang untuk menyesuaikan teks setelah penggantian.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Mengatur aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ReplaceAdjustment @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Mengatur ruang lingkup dimana operasi penggantian teks diterapkan

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

Mengatur penyesuaian posisi kanan untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |
