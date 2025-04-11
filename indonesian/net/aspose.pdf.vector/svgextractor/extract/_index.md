---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Metode SvgExtractor. Mengekstrak gambar svg ke string dari elemen grafis yang diwakili oleh absorber dengan filter predikat
type: docs
weight: 20
url: /id/net/aspose.pdf.vector/svgextractor/extract/
---
## Ekstrak(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Mengekstrak gambar svg ke string dari elemen grafis yang diwakili oleh !:absorber dengan filter predikat.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Objek GraphicsAbsorber yang berisi elemen grafis. |
| filter | Predicate`1 | Fungsi predikat yang digunakan untuk memfilter elemen grafis. |
| page | Page | Halaman tempat absorber mendapatkan elemen grafis. |

### Nilai Kembali

String dengan konten SVG.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* kelas [GraphicsAbsorber](../../graphicsabsorber/)
* kelas [GraphicElement](../../graphicelement/)
* kelas [Page](../../../aspose.pdf/page/)
* kelas [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Ekstrak(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Mengekstrak gambar svg ke file dari elemen grafis yang diwakili oleh !:absorber dengan filter predikat.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Objek GraphicsAbsorber yang berisi elemen grafis. |
| filter | Predicate`1 | Fungsi predikat yang digunakan untuk memfilter elemen grafis. |
| page | Page | Halaman tempat absorber mendapatkan elemen grafis. |
| svgFilePath | String | Jalur file SVG target. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* kelas [GraphicsAbsorber](../../graphicsabsorber/)
* kelas [GraphicElement](../../graphicelement/)
* kelas [Page](../../../aspose.pdf/page/)
* kelas [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Ekstrak(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Mengekstrak elemen grafis menjadi string SVG. Opsi diabaikan - pengelompokan, mengekstrak dari persegi panjang

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elements | IEnumerable`1 | Elemen grafis yang akan dikonversi. |
| page | Page | Halaman tempat absorber mendapatkan elemen grafis. |

### Nilai Kembali

String dengan konten SVG.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* kelas [GraphicElement](../../graphicelement/)
* kelas [Page](../../../aspose.pdf/page/)
* kelas [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Ekstrak(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Mengekstrak elemen grafis menjadi satu file SVG. Opsi diabaikan - pengelompokan, mengekstrak dari persegi panjang

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elements | IEnumerable`1 | Elemen grafis yang akan dikonversi. |
| page | Page | Halaman tempat absorber mendapatkan elemen grafis. |
| svgFilePath | String | Jalur file SVG target. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* kelas [GraphicElement](../../graphicelement/)
* kelas [Page](../../../aspose.pdf/page/)
* kelas [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Ekstrak(Page) {#extract}

Mengekstrak gambar Svg dari halaman ke string.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Page | Halaman untuk diekstrak. |

### Nilai Kembali

Daftar string konten SVG.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* kelas [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Ekstrak(Page, string) {#extract_3}

Mengekstrak gambar Svg dari halaman ke file.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Page | Halaman untuk diekstrak. |
| directory | String | Direktori target untuk menempatkan gambar SVG. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* kelas [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)