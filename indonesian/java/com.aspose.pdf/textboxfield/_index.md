---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili bidang kotak teks."
type: docs
weight: 4930
url: /id/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

Kelas yang mewakili bidang kotak teks.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextBoxField](#TextBoxField--) | Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc) |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | Menambahkan barcode 128 ke dalam bidang. Nilai bidang akan diubah menjadi kode dan bidang menjadi hanya-baca. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Menambahkan gambar ke dalam sumber daya bidang dan menggambarnya. |
| [getForceCombs](#getForceCombs--) | Mendapatkan flag yang menunjukkan apakah bidang dibagi menjadi posisi berjarak. |
| [getMaxLen](#getMaxLen--) | Mendapatkan panjang maksimum teks dalam bidang. |
| [getMultiline](#getMultiline--) | Mendapatkan flag multiline dari bidang. Jika Multiline bernilai true, bidang dapat berisi beberapa baris teks. |
| [getScrollable](#getScrollable--) | Mendapatkan flag dapat digulir dari bidang. Jika true, bidang dapat digulir. |
| [getSpellCheck](#getSpellCheck--) | Mendapatkan flag pemeriksaan ejaan untuk bidang. Jika true, bidang akan diperiksa ejaannya. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | Mendapatkan atau mengatur perataan vertikal teks untuk anotasi. |
| [getValue](#getValue--) | Mendapatkan nilai bidang. |
| [setForceCombs](#setForceCombs-boolean-) | Mengatur flag yang menunjukkan apakah bidang dibagi menjadi posisi berjarak. |
| [setJustification](#setJustification-boolean-) | Mengatur perataan |
| [setMaxLen](#setMaxLen-int-) | Mengatur panjang maksimum teks dalam bidang. |
| [setMultiline](#setMultiline-boolean-) | Mengatur flag multiline pada bidang. Jika Multiline bernilai true, bidang dapat berisi beberapa baris teks. |
| [setScrollable](#setScrollable-boolean-) | Mengatur flag dapat digulir pada bidang. Jika true, bidang dapat digulir. |
| [setSpellCheck](#setSpellCheck-boolean-) | Mengatur flag pemeriksaan ejaan untuk bidang. Jika true, bidang akan diperiksa ejaannya. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mendapatkan atau mengatur perataan vertikal teks untuk anotasi. |
| [setValue](#setValue-java.lang.String-) | Mengatur nilai bidang. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
Buat instance dari TextBoxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
Menambahkan barcode 128 ke dalam bidang. Nilai bidang akan diubah menjadi kode dan bidang menjadi hanya-baca.

### addImage {#addImage-java.awt.image.BufferedImage-}
Menambahkan gambar ke dalam sumber daya bidang dan menggambarnya.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

Mendapatkan flag yang menunjukkan apakah bidang dibagi menjadi posisi berjarak.

**Returns:**
nilai boolean

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

Mendapatkan panjang maksimum teks dalam bidang.

**Returns:**
nilai int

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

Mendapatkan flag multiline dari bidang. Jika Multiline bernilai true, bidang dapat berisi beberapa baris teks.

**Returns:**
nilai boolean

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

Mendapatkan flag dapat digulir dari bidang. Jika true, bidang dapat digulir.

**Returns:**
nilai boolean

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

Mendapatkan flag pemeriksaan ejaan untuk bidang. Jika true, bidang akan diperiksa ejaannya.

**Returns:**
nilai boolean

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

Mendapatkan atau mengatur perataan vertikal teks untuk anotasi.

**Returns:**
Elemen VerticalAlignment

### getValue {#getValue--}
```
public String getValue()
```

Mendapatkan nilai bidang.

**Returns:**
nilai String

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

Mengatur flag yang menunjukkan apakah bidang dibagi menjadi posisi berjarak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

Mengatur perataan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

Mengatur panjang maksimum teks dalam bidang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

Mengatur flag multiline pada bidang. Jika Multiline bernilai true, bidang dapat berisi beberapa baris teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

Mengatur flag dapat digulir pada bidang. Jika true, bidang dapat digulir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

Mengatur flag pemeriksaan ejaan untuk bidang. Jika true, bidang akan diperiksa ejaannya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mendapatkan atau mengatur perataan vertikal teks untuk anotasi.

### setValue {#setValue-java.lang.String-}
Mengatur nilai bidang.
