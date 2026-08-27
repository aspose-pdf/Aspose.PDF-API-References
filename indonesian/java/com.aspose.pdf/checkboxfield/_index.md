---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili bidang kotak centang"
type: docs
weight: 580
url: /id/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Kelas yang mewakili bidang kotak centang

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CheckboxField](#CheckboxField--) | Buat instance dari CheckboxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | Buat instance dari CheckboxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Buat instance dari CheckboxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Buat instance dari CheckboxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan CheckboxField(Document doc) |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dipilih pada satu waktu. Kotak centang baru ditambahkan ke bagian bawah grup. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dipilih pada satu waktu. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dipilih pada satu waktu. |
| [deepClone](#deepClone--) | Gandakan kotak centang. |
| [getActiveState](#getActiveState--) | Mendapatkan status tampilan anotasi saat ini. |
| [getAllowedStates](#getAllowedStates--) | Mengembalikan daftar status yang diizinkan. |
| [getChecked](#getChecked--) | Mendapatkan status kotak centang. |
| [getExportValue](#getExportValue--) | Mendapatkan atau mengatur nilai ekspor bidang CheckBox. |
| [getNormalCaption](#getNormalCaption--) | Mendapatkan keterangan normal dari bidang. |
| [getOnState](#getOnState--) | Mengembalikan nama status yang merupakan status "Checked" dari kotak centang. Ini adalah "Yes" jika ada atau nilai lain selain "Off" dan "No"; |
| [getStyle](#getStyle--) | Mendapatkan gaya kotak centang. |
| [getValue](#getValue--) | Mendapatkan nilai bidang kotak centang. |
| [setActiveState](#setActiveState-java.lang.String-) | Mengatur status tampilan anotasi saat ini. |
| [setChecked](#setChecked-boolean-) | Mengatur status kotak centang. |
| [setExportValue](#setExportValue-java.lang.String-) | Mendapatkan atau mengatur nilai ekspor bidang CheckBox. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Mengatur gaya kotak centang. |
| [setValue](#setValue-java.lang.String-) | Mengatur nilai bidang kotak centang. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

Buat instance dari CheckboxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
Buat instance dari CheckboxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Buat instance dari CheckboxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Buat instance dari CheckboxField. @deprecated Untuk fungsionalitas bidang penuh, diperlukan pengikatan ke dokumen - gunakan CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dipilih pada satu waktu. Kotak centang baru ditambahkan ke bagian bawah grup.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dipilih pada satu waktu.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dipilih pada satu waktu.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Gandakan kotak centang.

**Returns:**
Objek yang diklon.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Mendapatkan status tampilan anotasi saat ini.

**Returns:**
nilai String

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

Mengembalikan daftar status yang diizinkan.

**Returns:**
daftar nilai String

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Mendapatkan status kotak centang.

**Returns:**
nilai boolean

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

Mendapatkan atau mengatur nilai ekspor bidang CheckBox.

**Returns:**
nilai String

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Mendapatkan keterangan normal dari bidang.

**Returns:**
nilai String

### getOnState {#getOnState--}
```
public String getOnState()
```

Mengembalikan nama status yang merupakan status "Checked" dari kotak centang. Ini adalah "Yes" jika ada atau nilai lain selain "Off" dan "No";

**Returns:**
nilai String

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Mendapatkan gaya kotak centang.

**Returns:**
gaya kotak centang. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Mendapatkan nilai bidang kotak centang.

**Returns:**
nilai String

### setActiveState {#setActiveState-java.lang.String-}
Mengatur status tampilan anotasi saat ini.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Mengatur status kotak centang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setExportValue {#setExportValue-java.lang.String-}
Mendapatkan atau mengatur nilai ekspor bidang CheckBox.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Mengatur gaya kotak centang.

### setValue {#setValue-java.lang.String-}
Mengatur nilai bidang kotak centang.
