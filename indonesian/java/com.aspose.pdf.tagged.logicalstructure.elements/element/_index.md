---
title: "Elemen"
linktitle: "Elemen"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas dasar untuk elemen dalam struktur logis."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Mewakili kelas dasar untuk elemen dalam struktur logis.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Tambahkan {@code /Aspose.Pdf.LogicalStructure.Element} ke koleksi anak. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Tambahkan {@code /Aspose.Pdf.LogicalStructure.Element} ke koleksi anak. |
| [clearChilds](#clearChilds--) | Bersihkan semua anak. |
| [findElements](#findElements-java.lang.Class-) | Temukan Elemen dengan tipe tertentu |
| [findElements](#findElements-java.lang.Class-boolean-) | Temukan Elemen dengan tipe tertentu |
| [getChildElements](#getChildElements--) | Mendapatkan koleksi anak dari objek {@code Element}. |
| [getElementEngine](#getElementEngine--) | Dapatkan elemen induk. |
| [getParentElement](#getParentElement--) | Mendapatkan koleksi induk dari objek {@code Element}. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Metode internal |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Sisipkan {@code /Aspose.Pdf.LogicalStructure.Element} ke koleksi anak pada indeks yang ditentukan. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | Sisipkan {@code /Aspose.Pdf.LogicalStructure.Element} ke koleksi anak pada indeks yang ditentukan. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Hapus anak pada. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Mengikat elemen struktur ke Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Mengikat elemen struktur ke Artefak. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Mengikat elemen struktur ke operator BDC aliran konten. |
| [tag](#tag-com.aspose.pdf.XForm-) | Mengikat elemen struktur ke XForm aliran konten. |
| [tag](#tag-com.aspose.pdf.XImage-) | Mengikat elemen struktur ke XImage. |
| [toString](#toString--) | Mengembalikan string yang mewakili objek saat ini. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Tambahkan {@code /Aspose.Pdf.LogicalStructure.Element} ke koleksi anak.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Tambahkan {@code /Aspose.Pdf.LogicalStructure.Element} ke koleksi anak.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Bersihkan semua anak.

### findElements {#findElements-java.lang.Class-}
Temukan Elemen dengan tipe tertentu

### findElements {#findElements-java.lang.Class-boolean-}
Temukan Elemen dengan tipe tertentu

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

Mendapatkan koleksi anak dari objek {@code Element}.

**Returns:**
Nilai: Koleksi anak dari objek {@code Element}.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Dapatkan elemen induk.

**Returns:**
Nilai: Elemen induk.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

Mendapatkan koleksi induk dari objek {@code Element}.

**Returns:**
Nilai: Koleksi induk dari objek {@code Element}.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

Metode internal

**Returns:**
Elemen internal

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Sisipkan {@code /Aspose.Pdf.LogicalStructure.Element} ke koleksi anak pada indeks yang ditentukan.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
Sisipkan {@code /Aspose.Pdf.LogicalStructure.Element} ke koleksi anak pada indeks yang ditentukan.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Hapus anak pada.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks elemen anak. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


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
