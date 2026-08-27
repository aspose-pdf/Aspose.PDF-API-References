---
title: "Artefak"
linktitle: "Artefak"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili objek PDF Artifact."
type: docs
weight: 190
url: /id/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Kelas yang mewakili objek PDF Artifact.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Konstruktor artefak dengan tipe dan subtipe yang ditentukan |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | Konstruktor ini digunakan ketika artefak dibaca dari halaman. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Konstruktor artefak dengan tipe dan subtipe yang ditentukan |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Mulai pembaruan yang dihapus. Gunakan fitur ini jika Anda perlu melakukan beberapa perubahan pada artefak yang sama untuk meningkatkan kinerja. Biasanya operator artefak diubah setiap kali properti artefak diubah. Hal ini menyebabkan perubahan konten halaman setiap kali artefak diubah. Untuk menghindari efek ini, letakkan semua pembaruan artefak di antara panggilan StartUpdates/SaveUpdates. Ini memungkinkan mengubah konten halaman hanya sekali. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Menutup semua sumber daya yang digunakan oleh dokumen ini. |
| [dispose](#dispose--) | Buang artefak. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Mendapatkan perataan horizontal artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Mendapatkan perataan vertikal artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| [getBottomMargin](#getBottomMargin--) | Mendapatkan margin bawah artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| [getContents](#getContents--) | Mendapatkan koleksi operator internal artefak. |
| [getCustomSubtype](#getCustomSubtype--) | Mendapatkan nama subtipe artefak. Dapat digunakan jika subtipe artefak bukan subtipe standar. |
| [getCustomType](#getCustomType--) | Mendapatkan nama tipe artefak. Dapat digunakan jika tipe artefak tidak standar. |
| [getForm](#getForm--) | Mendapatkan XForm artefak (jika XForm digunakan). |
| [getImage](#getImage--) | Mendapatkan gambar artefak (jika ada). |
| [getLeftMargin](#getLeftMargin--) | Mendapatkan margin kiri artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| [getLines](#getLines--) | Baris-baris artefak teks multiline. |
| [getOpacity](#getOpacity--) | Mendapatkan opasitas artefak. Nilai yang mungkin berada dalam rentang 0..1. |
| [getPosition](#getPosition--) | Mendapatkan posisi artefak. Jika properti ini ditentukan, maka margin dan perataan diabaikan. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang artefak. |
| [getRightMargin](#getRightMargin--) | Mendapatkan margin kanan artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| [getRotation](#getRotation--) | Mendapatkan sudut rotasi artefak. |
| [getSubtype](#getSubtype--) | Mendapatkan subtipe artefak. Jika artefak memiliki subtipe non-standar, nama subtipe dapat dibaca melalui CustomSubtype. |
| [getText](#getText--) | Mendapatkan teks artefak. |
| [getTextState](#getTextState--) | Status teks untuk teks artefak. |
| [getTopMargin](#getTopMargin--) | Mendapatkan margin atas artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| [getType](#getType--) | Mendapatkan tipe artefak. |
| [getValue](#getValue-java.lang.String-) | Mendapatkan nilai khusus artefak. |
| [isBackground](#isBackground--) | Jika true, Artefak ditempatkan di belakang konten halaman. |
| [removeValue](#removeValue-java.lang.String-) | Hapus nilai khusus dari artefak. |
| [saveUpdates](#saveUpdates--) | Menyimpan semua pembaruan pada artefak yang dibuat setelah pemanggilan BeginUpdates(). |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Mendapatkan perataan horizontal artefak. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mengatur perataan vertikal artefak. |
| [setBackground](#setBackground-boolean-) | Jika true, Artefak ditempatkan di belakang konten halaman. |
| [setBottomMargin](#setBottomMargin-double-) | Mengatur margin bawah artefak. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Mengatur nama tipe artefak. Dapat digunakan jika tipe artefak tidak standar. |
| [setImage](#setImage-java.io.InputStream-) | Mengatur gambar artefak. |
| [setImage](#setImage-java.lang.String-) | Mengatur gambar artefak. |
| [setLeftMargin](#setLeftMargin-double-) | Mengatur margin kiri artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Atur teks dan properti teks artefak. Memungkinkan menentukan beberapa baris. |
| [setOpacity](#setOpacity-double-) | Mengatur opasitas artefak. Nilai yang mungkin berada dalam rentang 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Mengatur string apa yang akan diganti dengan nomor halaman. Nilai default adalah #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Mengatur halaman PDF yang ditempatkan pada halaman dokumen sebagai artefak. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Mengatur posisi artefak. |
| [setRightMargin](#setRightMargin-double-) | Mengatur margin kanan artefak. |
| [setRotation](#setRotation-double-) | Mengatur sudut rotasi artefak. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Mengatur subtipe artefak. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Mengatur teks artefak. |
| [setText](#setText-java.lang.String-) | Mengatur teks artefak. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Atur teks dan properti teks artefak. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Status teks untuk teks artefak. |
| [setTopMargin](#setTopMargin-double-) | Mengatur margin atas artefak. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Mengatur tipe artefak. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Mengatur nilai khusus artefak. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Konstruktor artefak dengan tipe dan subtipe yang ditentukan

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
Konstruktor ini digunakan ketika artefak dibaca dari halaman.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Konstruktor artefak dengan tipe dan subtipe yang ditentukan

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Mulai pembaruan yang dihapus. Gunakan fitur ini jika Anda perlu melakukan beberapa perubahan pada artefak yang sama untuk meningkatkan kinerja. Biasanya operator artefak diubah setiap kali properti artefak diubah. Hal ini menyebabkan perubahan konten halaman setiap kali artefak diubah. Untuk menghindari efek ini, letakkan semua pembaruan artefak di antara panggilan StartUpdates/SaveUpdates. Ini memungkinkan mengubah konten halaman hanya sekali. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Menutup semua sumber daya yang digunakan oleh dokumen ini.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Buang artefak. Metode ini sudah usang, gunakan close() sebagai gantinya.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Mendapatkan perataan horizontal artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan.

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Mendapatkan perataan vertikal artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan.

**Returns:**
Nilai VerticalAlignment. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Mendapatkan margin bawah artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan.

**Returns:**
margin bawah.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Mendapatkan koleksi operator internal artefak.

**Returns:**
daftar operator internal artefak.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Mendapatkan nama subtipe artefak. Dapat digunakan jika subtipe artefak bukan subtipe standar.

**Returns:**
nilai String

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Mendapatkan nama tipe artefak. Dapat digunakan jika tipe artefak tidak standar.

**Returns:**
String nama artefak

### getForm {#getForm--}
```
public XForm getForm()
```

Mendapatkan XForm artefak (jika XForm digunakan).

**Returns:**
objek XForm

### getImage {#getImage--}
```
public XImage getImage()
```

Mendapatkan gambar artefak (jika ada).

**Returns:**
objek XImage

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Mendapatkan margin kiri artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan.

**Returns:**
margin kiri artefak.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Baris-baris artefak teks multiline.

**Returns:**
Daftar String

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Mendapatkan opasitas artefak. Nilai yang mungkin berada dalam rentang 0..1.

**Returns:**
opasitas artefak.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Mendapatkan posisi artefak. Jika properti ini ditentukan, maka margin dan perataan diabaikan.

**Returns:**
posisi artefak.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang artefak.

**Returns:**
objek Rectangle

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Mendapatkan margin kanan artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan.

**Returns:**
margin kanan artefak.

### getRotation {#getRotation--}
```
public double getRotation()
```

Mendapatkan sudut rotasi artefak.

**Returns:**
sudut rotasi artefak.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Mendapatkan subtipe artefak. Jika artefak memiliki subtipe non-standar, nama subtipe dapat dibaca melalui CustomSubtype.

**Returns:**
subtipe artefak. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Mendapatkan teks artefak.

**Returns:**
nilai String

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

Status teks untuk teks artefak.

**Returns:**
instansi TextState

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Mendapatkan margin atas artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan.

**Returns:**
margin atas artefak.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Mendapatkan tipe artefak.

**Returns:**
nilai tipe artefak. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Mendapatkan nilai khusus artefak.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Jika true, Artefak ditempatkan di belakang konten halaman.

**Returns:**
nilai boolean

### removeValue {#removeValue-java.lang.String-}
Hapus nilai khusus dari artefak.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

Menyimpan semua pembaruan pada artefak yang dibuat setelah pemanggilan BeginUpdates().

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Mendapatkan perataan horizontal artefak.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mengatur perataan vertikal artefak.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Jika true, Artefak ditempatkan di belakang konten halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Mengatur margin bawah artefak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | margin bawah. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Mengatur nama tipe artefak. Dapat digunakan jika tipe artefak tidak standar.

### setImage {#setImage-java.io.InputStream-}
Mengatur gambar artefak.

### setImage {#setImage-java.lang.String-}
Mengatur gambar artefak.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Mengatur margin kiri artefak. Jika posisi ditentukan secara eksplisit (pada properti Position) nilai ini diabaikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | margin kiri artefak. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Atur teks dan properti teks artefak. Memungkinkan menentukan beberapa baris.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Mengatur opasitas artefak. Nilai yang mungkin berada dalam rentang 0..1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | opasitas artefak. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Mengatur string apa yang akan diganti dengan nomor halaman. Nilai default adalah #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Mengatur halaman PDF yang ditempatkan pada halaman dokumen sebagai artefak.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Mengatur posisi artefak.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Mengatur margin kanan artefak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | margin kanan artefak. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Mengatur sudut rotasi artefak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | sudut rotasi artefak. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Mengatur subtipe artefak.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Mengatur teks artefak.

### setText {#setText-java.lang.String-}
Mengatur teks artefak.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Atur teks dan properti teks artefak.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Status teks untuk teks artefak.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Mengatur margin atas artefak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | margin atas artefak. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Mengatur tipe artefak.

### setValue {#setValue-java.lang.String-java.lang.String-}
Mengatur nilai khusus artefak.
