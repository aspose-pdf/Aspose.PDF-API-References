---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang merepresentasikan bidang tombol radio."
type: docs
weight: 4080
url: /id/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Kelas yang merepresentasikan bidang tombol radio.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | Konstruktor untuk RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | Konstruktor untuk RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Mengatur bidang tombol radio |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | Menambahkan bidang opsi baru ke bidang RadioButton |
| [addOption](#addOption-java.lang.String-) | Menambahkan opsi ke tombol radion. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Menambahkan ke opsi tombol radio dengan persegi panjang yang ditentukan. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Mendapatkan atau mengatur flag yang memungkinkan tombol radio tidak memiliki nilai terpilih. Jika {@code }, tepat satu tombol radio harus dipilih setiap saat; memilih tombol yang sudah dipilih tidak berpengaruh. Jika {@code }, mengklik tombol yang dipilih akan membatalkannya, sehingga tidak ada tombol yang dipilih. </p> <hr> Beberapa pembaca PDF (termasuk Adobe Acrobat) mungkin mengabaikan keadaan flag tersebut. |
| [getOptions](#getOptions--) | Mendapatkan koleksi opsi tombol radio. |
| [getPageIndex](#getPageIndex--) | Mendapatkan indeks halaman yang berisi bidang RadioButton ini. |
| [getSelected](#getSelected--) | Mendapatkan indeks item yang dipilih. Penomoran item dimulai dari 1. |
| [getStyle](#getStyle--) | Gaya kotak bidang. |
| [getValue](#getValue--) | Mendapatkan nilai bidang. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Mendapatkan atau mengatur flag yang memungkinkan tombol radio tidak memiliki nilai terpilih. Jika {@code }, tepat satu tombol radio harus dipilih setiap saat; memilih tombol yang sudah dipilih tidak berpengaruh. Jika {@code }, mengklik tombol yang dipilih akan membatalkannya, sehingga tidak ada tombol yang dipilih. </p> <hr> Beberapa pembaca PDF (termasuk Adobe Acrobat) mungkin mengabaikan keadaan flag tersebut. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Pindahkan semua subitem tombol radio ke posisi yang ditentukan pada halaman. |
| [setSelected](#setSelected-int-) | Mengatur indeks item yang dipilih. Penomoran item dimulai dari 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Gaya kotak bidang. |
| [setValue](#setValue-java.lang.String-) | Mengatur nilai bidang. |
| [updateAppearances](#updateAppearances--) | Perbarui nilai tampilan. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
Konstruktor untuk RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
Konstruktor untuk RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Mengatur bidang tombol radio

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
Menambahkan bidang opsi baru ke bidang RadioButton

### addOption {#addOption-java.lang.String-}
Menambahkan opsi ke tombol radion.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Menambahkan ke opsi tombol radio dengan persegi panjang yang ditentukan.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Mendapatkan atau mengatur flag yang memungkinkan tombol radio tidak memiliki nilai terpilih. Jika {@code }, tepat satu tombol radio harus dipilih setiap saat; memilih tombol yang sudah dipilih tidak berpengaruh. Jika {@code }, mengklik tombol yang dipilih akan membatalkannya, sehingga tidak ada tombol yang dipilih. </p> <hr> Beberapa pembaca PDF (termasuk Adobe Acrobat) mungkin mengabaikan keadaan flag tersebut.

**Returns:**
nilai boolean

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Mendapatkan koleksi opsi tombol radio.

**Returns:**
Objek OptionCollection

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Mendapatkan indeks halaman yang berisi bidang RadioButton ini.

**Returns:**
nilai int

### getSelected {#getSelected--}
```
public int getSelected()
```

Mendapatkan indeks item yang dipilih. Penomoran item dimulai dari 1.

**Returns:**
nilai int

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Gaya kotak bidang.

**Returns:**
Nilai BoxStyle @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Mendapatkan nilai bidang.

**Returns:**
nilai String

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Mendapatkan atau mengatur flag yang memungkinkan tombol radio tidak memiliki nilai terpilih. Jika {@code }, tepat satu tombol radio harus dipilih setiap saat; memilih tombol yang sudah dipilih tidak berpengaruh. Jika {@code }, mengklik tombol yang dipilih akan membatalkannya, sehingga tidak ada tombol yang dipilih. </p> <hr> Beberapa pembaca PDF (termasuk Adobe Acrobat) mungkin mengabaikan keadaan flag tersebut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Pindahkan semua subitem tombol radio ke posisi yang ditentukan pada halaman.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Mengatur indeks item yang dipilih. Penomoran item dimulai dari 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Gaya kotak bidang.

### setValue {#setValue-java.lang.String-}
Mengatur nilai bidang.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Perbarui nilai tampilan.
