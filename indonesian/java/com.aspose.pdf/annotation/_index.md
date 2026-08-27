---
title: "Annotation"
linktitle: "Annotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili objek anotasi."
type: docs
weight: 60
url: /id/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Kelas yang mewakili objek anotasi.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima visitor untuk pemrosesan anotasi. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Perbarui parameter dan tampilan, sesuai dengan transformasi matriks. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Hanya untuk penggunaan internal |
| [flatten](#flatten--) | Menempatkan konten anotasi langsung pada halaman, objek anotasi akan dihapus. |
| [getActiveState](#getActiveState--) | Mendapatkan status tampilan anotasi saat ini. |
| [getAlignment](#getAlignment--) | ff / * / * Mengembalikan nama status "checked" sesuai dengan nama status yang ada. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getAppearance](#getAppearance--) | Mendapatkan kamus tampilan anotasi. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Mendapatkan indeks halaman (berbasis satu) tempat anotasi harus muncul. |
| [getBorder](#getBorder--) | Mendapatkan karakteristik batas anotasi. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Mendapatkan karakteristik anotasi. |
| [getColor](#getColor--) | Mendapatkan warna anotasi. |
| [getContents](#getContents--) | Mendapatkan teks anotasi. |
| [getEngineDict](#getEngineDict--) | Hanya internal |
| [getEngineObj](#getEngineObj--) | Hanya untuk penggunaan internal |
| [getFlags](#getFlags--) | Mendapatkan flag anotasi. |
| [getFullName](#getFullName--) | Mendapatkan nama lengkap anotasi. |
| [getHeight](#getHeight--) | Mendapatkan tinggi anotasi. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| [getModified](#getModified--) | Mendapatkan tanggal dan waktu ketika anotasi terakhir dimodifikasi. |
| [getModifiedInternal](#getModifiedInternal--) | Mendapatkan tanggal dan waktu ketika anotasi terakhir dimodifikasi. |
| [getName](#getName--) | Mendapatkan nama anotasi pada halaman. |
| [getNormalAppearance](#getNormalAppearance--) | Mendapatkan tampilan normal. |
| [getPage](#getPage--) | Mendapatkan objek halaman yang terkait dengan anotasi ini. |
| [getPageIndex](#getPageIndex--) | Mendapatkan indeks halaman yang berisi anotasi. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Mendapatkan indeks halaman yang berisi anotasi. |
| [getPdfActions](#getPdfActions--) | Mendapatkan daftar aksi anotasi. |
| [getRect](#getRect--) | Mendapatkan persegi panjang anotasi. |
| [getRectangle](#getRectangle-boolean-) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| [getStates](#getStates--) | Mendapatkan kamus tampilan anotasi. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Mendapatkan perataan teks untuk anotasi. |
| [getWidth](#getWidth--) | Mendapatkan lebar anotasi. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Inisialisasi instance |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | Jika true, tampilan anotasi akan diperbarui sebelum mengonversi dokumen PDF menjadi gambar. Ini memungkinkan konversi bidang secara benar tetapi mungkin membutuhkan lebih banyak waktu. |
| [isUseFontSubset](#isUseFontSubset--) | Jika properti ini disetel ke true, font akan ditambahkan ke dokumen sebagai subset. Nilai default adalah true. |
| [setActiveState](#setActiveState-java.lang.String-) | Mengatur status tampilan anotasi saat ini. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Penjajaran anotasi. Properti ini sudah usang. Gunakan getHorizontalAlignment_Annotation_New sebagai gantinya. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Mengatur indeks halaman (berbasis satu) tempat anotasi harus muncul. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Mengatur karakteristik batas anotasi. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Mengatur warna anotasi. |
| [setContents](#setContents-java.lang.String-) | Mengatur teks anotasi. |
| [setFlags](#setFlags-int-) | Mengatur flag anotasi. |
| [setHeight](#setHeight-double-) | Mengatur tinggi anotasi. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| [setModified](#setModified-java.util.Date-) | Mengatur tanggal dan waktu ketika anotasi terakhir dimodifikasi. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Mengatur tanggal dan waktu ketika anotasi terakhir dimodifikasi. |
| [setName](#setName-java.lang.String-) | Mengatur nama anotasi pada halaman. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Mengatur persegi panjang anotasi. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur perataan teks untuk anotasi. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | Jika true, tampilan anotasi akan diperbarui sebelum mengonversi dokumen PDF menjadi gambar. Ini memungkinkan konversi bidang secara benar tetapi mungkin membutuhkan lebih banyak waktu. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | Jika properti ini disetel ke true, font akan ditambahkan ke dokumen sebagai subset. Nilai default adalah true. |
| [setWidth](#setWidth-double-) | Mengatur lebar anotasi. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima visitor untuk pemrosesan anotasi.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Perbarui parameter dan tampilan, sesuai dengan transformasi matriks.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
Hanya untuk penggunaan internal

### flatten {#flatten--}
```
public void flatten()
```

Menempatkan konten anotasi langsung pada halaman, objek anotasi akan dihapus.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Mendapatkan status tampilan anotasi saat ini.

**Returns:**
nilai String

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Mengembalikan nama status "checked" sesuai dengan nama status yang ada. / * / * / *

**Returns:**
Nilai string /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
nilai int @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Mendapatkan kamus tampilan anotasi.

**Returns:**
objek AppearanceDictionary

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Mendapatkan indeks halaman (berbasis satu) tempat anotasi harus muncul.

**Returns:**
indeks halaman (berbasis satu) tempat anotasi harus muncul.

### getBorder {#getBorder--}
```
public Border getBorder()
```

Mendapatkan karakteristik batas anotasi. {@code Border}

**Returns:**
objek Border

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Mendapatkan karakteristik anotasi.

**Returns:**
objek Characteristics

### getColor {#getColor--}
```
public Color getColor()
```

Mendapatkan warna anotasi.

**Returns:**
objek Color

### getContents {#getContents--}
```
public String getContents()
```

Mendapatkan teks anotasi.

**Returns:**
nilai String

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Hanya internal

**Returns:**
objek IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Hanya untuk penggunaan internal

**Returns:**
Objek internal

### getFlags {#getFlags--}
```
public int getFlags()
```

Mendapatkan flag anotasi.

**Returns:**
Flag anotasi @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Mendapatkan nama lengkap anotasi.

**Returns:**
nilai String

### getHeight {#getHeight--}
```
public double getHeight()
```

Mendapatkan tinggi anotasi.

**Returns:**
tinggi anotasi

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Mendapatkan atau mengatur perataan teks untuk anotasi.

**Returns:**
perataan teks untuk anotasi. @see HorizontalAlignment @deprecated Gunakan properti TextHorizontalAlignment

### getModified {#getModified--}
```
public Date getModified()
```

Mendapatkan tanggal dan waktu ketika anotasi terakhir dimodifikasi.

**Returns:**
tanggal dan waktu ketika anotasi terakhir dimodifikasi.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Mendapatkan tanggal dan waktu ketika anotasi terakhir dimodifikasi.

**Returns:**
objek DateTime

### getName {#getName--}
```
public String getName()
```

Mendapatkan nama anotasi pada halaman.

**Returns:**
nilai String

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Mendapatkan tampilan normal.

**Returns:**
objek XForm

### getPage {#getPage--}
```
public Page getPage()
```

Mendapatkan objek halaman yang terkait dengan anotasi ini.

**Returns:**
objek Page

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Mendapatkan indeks halaman yang berisi anotasi.

**Returns:**
nilai int

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Mendapatkan indeks halaman yang berisi anotasi.

**Returns:**
nilai int

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Mendapatkan daftar aksi anotasi.

**Returns:**
instansi PdfActionCollection

### getRect {#getRect--}
```
public Rectangle getRect()
```

Mendapatkan persegi panjang anotasi.

**Returns:**
objek Rectangle

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| considerRotation |  | Jika true, rotasi halaman dipertimbangkan. |

**Returns:**
objek Rectangle

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Mendapatkan kamus tampilan anotasi.

**Returns:**
objek AppearanceDictionary

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Mendapatkan perataan teks untuk anotasi.

**Returns:**
perataan teks untuk anotasi. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Mendapatkan lebar anotasi.

**Returns:**
nilai double, lebar anotasi.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Inisialisasi instance

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

Jika true, tampilan anotasi akan diperbarui sebelum mengonversi dokumen PDF menjadi gambar. Ini memungkinkan konversi bidang secara benar tetapi mungkin membutuhkan lebih banyak waktu.

**Returns:**
nilai boolean

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

Jika properti ini disetel ke true, font akan ditambahkan ke dokumen sebagai subset. Nilai default adalah true.

**Returns:**
nilai boolean

### setActiveState {#setActiveState-java.lang.String-}
Mengatur status tampilan anotasi saat ini.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Penjajaran anotasi. Properti ini sudah usang. Gunakan getHorizontalAlignment_Annotation_New sebagai gantinya.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Mengatur indeks halaman (berbasis satu) tempat anotasi harus muncul.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Mengatur karakteristik batas anotasi. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Mengatur warna anotasi.

### setContents {#setContents-java.lang.String-}
Mengatur teks anotasi.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Mengatur flag anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | flag anotasi @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Mengatur tinggi anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | tinggi anotasi |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Mendapatkan atau mengatur perataan teks untuk anotasi.

### setModified {#setModified-java.util.Date-}
Mengatur tanggal dan waktu ketika anotasi terakhir dimodifikasi.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Mengatur tanggal dan waktu ketika anotasi terakhir dimodifikasi.

### setName {#setName-java.lang.String-}
Mengatur nama anotasi pada halaman.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Mengatur persegi panjang anotasi.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur perataan teks untuk anotasi.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

Jika true, tampilan anotasi akan diperbarui sebelum mengonversi dokumen PDF menjadi gambar. Ini memungkinkan konversi bidang secara benar tetapi mungkin membutuhkan lebih banyak waktu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

Jika properti ini disetel ke true, font akan ditambahkan ke dokumen sebagai subset. Nilai default adalah true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Mengatur lebar anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | lebar anotasi. |
