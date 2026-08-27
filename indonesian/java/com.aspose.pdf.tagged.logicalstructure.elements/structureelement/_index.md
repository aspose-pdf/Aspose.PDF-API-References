---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas dasar untuk elemen struktur dalam struktur logis."
type: docs
weight: 110
url: /id/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Mewakili kelas dasar untuk elemen struktur dalam struktur logis.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Ubah elemen induk untuk elemen struktur saat ini |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Ubah elemen induk untuk elemen struktur saat ini |
| [clearId](#clearId--) | Bersihkan ID untuk elemen struktur. |
| [generateId](#generateId--) | Hasilkan ID untuk elemen struktur. |
| [getActualText](#getActualText--) | Mendapatkan atau mengatur teks sebenarnya untuk elemen struktur. |
| [getAlternativeText](#getAlternativeText--) | Mendapatkan atau mengatur teks alternatif untuk elemen struktur. |
| [getAttributes](#getAttributes--) | Mendapatkan objek {@code StructureAttributeCollection}. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Mendapatkan objek {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. Nilai: objek {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. |
| [getExpansionText](#getExpansionText--) | Mendapatkan atau mengatur teks ekspansi untuk elemen struktur. |
| [getID](#getID--) | Mendapatkan ID untuk elemen struktur. Nilai: ID dari elemen struktur. |
| [getLanguage](#getLanguage--) | Mendapatkan atau mengatur bahasa untuk elemen struktur. |
| [getPage](#getPage--) | Mendapatkan halaman tempat beberapa atau semua elemen anak akan dirender. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Mendapatkan tipe elemen struktur. |
| [getTitle](#getTitle--) | Mendapatkan atau mengatur judul untuk elemen struktur. |
| [remove](#remove--) | Menghapus: sebuah elemen dari struktur, referensi kepadanya dari objek induk, referensi kepadanya dari objek anak, objek yang bersangkutan dari dokumen. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Menghapus sebuah elemen dari struktur, referensi kepadanya dari objek induk, referensi kepadanya dari objek anak, dan objek yang bersangkutan dari dokumen. Menyisipkan objek anak dari objek yang dihapus ke dalam koleksi objek anak induk sebelumnya mulai dari indeks objek yang dihapus. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Menghapus sebuah elemen dari struktur, referensi kepadanya dari objek induk, referensi kepadanya dari objek anak, dan objek yang bersangkutan dari dokumen. Menyisipkan objek anak dari objek yang dihapus ke dalam koleksi objek anak induk sebelumnya mulai dari indeks objek yang dihapus. |
| [setActualText](#setActualText-java.lang.String-) | Mendapatkan atau mengatur teks sebenarnya untuk elemen struktur. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Mendapatkan atau mengatur teks alternatif untuk elemen struktur. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Mendapatkan atau mengatur teks ekspansi untuk elemen struktur. |
| [setId](#setId-java.lang.String-) | Mengatur ID untuk elemen struktur. |
| [setLanguage](#setLanguage-java.lang.String-) | Mendapatkan atau mengatur bahasa untuk elemen struktur. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | atur Elemen Induk |
| [setTag](#setTag-java.lang.String-) | Mengatur tag khusus untuk elemen struktur. |
| [setTitle](#setTitle-java.lang.String-) | Mendapatkan atau mengatur judul untuk elemen struktur. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Mengikat elemen struktur ke Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Mengikat elemen struktur ke Artefak. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Mengikat elemen struktur ke operator BDC aliran konten. |
| [tag](#tag-com.aspose.pdf.XForm-) | Mengikat elemen struktur ke XForm aliran konten. |
| [tag](#tag-com.aspose.pdf.XImage-) | Mengikat elemen struktur ke XImage. |
| [toString](#toString--) | Mengembalikan string yang mewakili objek saat ini. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Ubah elemen induk untuk elemen struktur saat ini

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Ubah elemen induk untuk elemen struktur saat ini

### clearId {#clearId--}
```
public final void clearId()
```

Bersihkan ID untuk elemen struktur.

### generateId {#generateId--}
```
public final void generateId()
```

Hasilkan ID untuk elemen struktur.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Mendapatkan atau mengatur teks sebenarnya untuk elemen struktur.

**Returns:**
Nilai: Teks aktual dari elemen struktur.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Mendapatkan atau mengatur teks alternatif untuk elemen struktur.

**Returns:**
Nilai: Teks alternatif dari elemen struktur.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Mendapatkan objek {@code StructureAttributeCollection}.

**Returns:**
{@code StructureAttributeCollection} objek.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Mendapatkan objek {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. Nilai: objek {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}.

**Returns:**
Instansi AttributeOwnerStandard

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Mendapatkan atau mengatur teks ekspansi untuk elemen struktur.

**Returns:**
Nilai: Teks ekspansi dari elemen struktur.

### getID {#getID--}
```
public final String getID()
```

Mendapatkan ID untuk elemen struktur. Nilai: ID dari elemen struktur.

**Returns:**
nilai String

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Mendapatkan atau mengatur bahasa untuk elemen struktur.

**Returns:**
Nilai: Bahasa dari elemen struktur.

### getPage {#getPage--}
```
public final Page getPage()
```

Mendapatkan halaman tempat beberapa atau semua elemen anak akan dirender.

**Returns:**
Instance Page

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Mendapatkan tipe elemen struktur.

**Returns:**
Nilai: {@code StructureTypeStandard} objek dari elemen struktur.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Mendapatkan atau mengatur judul untuk elemen struktur.

**Returns:**
Nilai: Judul dari elemen struktur.

### remove {#remove--}
```
public final void remove()
```

Menghapus: sebuah elemen dari struktur, referensi kepadanya dari objek induk, referensi kepadanya dari objek anak, objek yang bersangkutan dari dokumen.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Menghapus sebuah elemen dari struktur, referensi kepadanya dari objek induk, referensi kepadanya dari objek anak, dan objek yang bersangkutan dari dokumen. Menyisipkan objek anak dari objek yang dihapus ke dalam koleksi objek anak induk sebelumnya mulai dari indeks objek yang dihapus.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Menghapus sebuah elemen dari struktur, referensi kepadanya dari objek induk, referensi kepadanya dari objek anak, dan objek yang bersangkutan dari dokumen. Menyisipkan objek anak dari objek yang dihapus ke dalam koleksi objek anak induk sebelumnya mulai dari indeks objek yang dihapus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Periksa apakah objek anak dari objek yang dihapus dapat disisipkan ke dalam koleksi objek anak induknya. |

### setActualText {#setActualText-java.lang.String-}
Mendapatkan atau mengatur teks sebenarnya untuk elemen struktur.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Mendapatkan atau mengatur teks alternatif untuk elemen struktur.

### setExpansionText {#setExpansionText-java.lang.String-}
Mendapatkan atau mengatur teks ekspansi untuk elemen struktur.

### setId {#setId-java.lang.String-}
Mengatur ID untuk elemen struktur.

### setLanguage {#setLanguage-java.lang.String-}
Mendapatkan atau mengatur bahasa untuk elemen struktur.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
atur Elemen Induk

### setTag {#setTag-java.lang.String-}
Mengatur tag khusus untuk elemen struktur.

### setTitle {#setTitle-java.lang.String-}
Mendapatkan atau mengatur judul untuk elemen struktur.

### tag {#tag-com.aspose.pdf.Annotation-}
Mengikat elemen struktur ke Annotation.

### tag {#tag-com.aspose.pdf.Artifact-}
Mengikat elemen struktur ke Artefak.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Mengikat elemen struktur ke operator BDC aliran konten.

### tag {#tag-com.aspose.pdf.XForm-}
Mengikat elemen struktur ke XForm aliran konten.

### tag {#tag-com.aspose.pdf.XImage-}
Mengikat elemen struktur ke XImage.

### toString {#toString--}
```
public String toString()
```

Mengembalikan string yang mewakili objek saat ini.

**Returns:**
String yang mewakili objek saat ini.
