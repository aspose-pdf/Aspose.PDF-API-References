---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas dasar untuk bidang pilihan."
type: docs
weight: 590
url: /id/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Mewakili kelas dasar untuk bidang pilihan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Membuat bidang pilihan (untuk Generator) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Konstruktor untuk ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor untuk ChoiceField. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Menambahkan opsi baru dengan nama yang ditentukan. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Menambahkan opsi baru dengan nilai ekspor dan nama yang ditentukan. |
| [deleteOption](#deleteOption-java.lang.String-) | Menghapus opsi berdasarkan namanya. |
| [getCommitImmediately](#getCommitImmediately--) | Mendapatkan flag commit pada perubahan pilihan. |
| [getMultiSelect](#getMultiSelect--) | Mendapatkan flag multiseleksi. |
| [getOptions](#getOptions--) | Mendapatkan koleksi opsi pilihan. |
| [getSelected](#getSelected--) | Mendapatkan indeks opsi yang dipilih. Properti ini memungkinkan mengubah pilihan. |
| [getSelectedItems](#getSelectedItems--) | Mengatur array item yang dipilih. Untuk daftar multiseleksi, array berisi lebih dari satu item. Untuk daftar seleksi tunggal, array berisi satu item. |
| [getValue](#getValue--) | Mendapatkan nilai bidang. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Mengatur flag commit pada perubahan pilihan. |
| [setMultiSelect](#setMultiSelect-boolean-) | Mengatur flag multiseleksi. |
| [setOptions](#setOptions-java.util.List-) | Mengganti opsi yang tersedia dengan yang namanya diberikan dalam parameter opsi. |
| [setSelected](#setSelected-int-) | Mengatur indeks opsi yang dipilih. Properti ini memungkinkan mengubah pilihan. |
| [setSelectedItems](#setSelectedItems-int:A-) | Mengatur array item yang dipilih. Untuk daftar multiseleksi, array berisi lebih dari satu item. Untuk daftar seleksi tunggal, array berisi satu item. |
| [setValue](#setValue-java.lang.String-) | Mengatur nilai bidang. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Membuat bidang pilihan (untuk Generator)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Konstruktor untuk ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor untuk ChoiceField.

### addOption {#addOption-java.lang.String-}
Menambahkan opsi baru dengan nama yang ditentukan.

### addOption {#addOption-java.lang.String-java.lang.String-}
Menambahkan opsi baru dengan nilai ekspor dan nama yang ditentukan.

### deleteOption {#deleteOption-java.lang.String-}
Menghapus opsi berdasarkan namanya.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Mendapatkan flag commit pada perubahan pilihan.

**Returns:**
nilai boolean

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Mendapatkan flag multiseleksi.

**Returns:**
nilai boolean

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Mendapatkan koleksi opsi pilihan.

**Returns:**
Objek OptionCollection

### getSelected {#getSelected--}
```
public int getSelected()
```

Mendapatkan indeks opsi yang dipilih. Properti ini memungkinkan mengubah pilihan.

**Returns:**
nilai int

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Mengatur array item yang dipilih. Untuk daftar multiseleksi, array berisi lebih dari satu item. Untuk daftar seleksi tunggal, array berisi satu item.

**Returns:**
array nilai int

### getValue {#getValue--}
```
public String getValue()
```

Mendapatkan nilai bidang.

**Returns:**
nilai String

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Mengatur flag commit pada perubahan pilihan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Mengatur flag multiseleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOptions {#setOptions-java.util.List-}
Mengganti opsi yang tersedia dengan yang namanya diberikan dalam parameter opsi.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Mengatur indeks opsi yang dipilih. Properti ini memungkinkan mengubah pilihan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Mengatur array item yang dipilih. Untuk daftar multiseleksi, array berisi lebih dari satu item. Untuk daftar seleksi tunggal, array berisi satu item.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | array nilai int |

### setValue {#setValue-java.lang.String-}
Mengatur nilai bidang.
