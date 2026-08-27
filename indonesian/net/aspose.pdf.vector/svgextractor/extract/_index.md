---
title: "SvgExtractor.Extract"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode SvgExtractor. Mengekstrak gambar svg menjadi string dari elemen grafis yang direpresentasikan oleh absorber dengan filter predikat"
type: docs
weight: 20
url: /id/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Mengekstrak gambar svg menjadi string dari elemen grafis yang diwakili oleh !:absorber dengan filter predikat.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Objek GraphicsAbsorber yang berisi elemen grafis. |
| filter | Predicate`1 | Fungsi predikat yang digunakan untuk memfilter elemen grafis. |
| halaman | Halaman | Halaman tempat absorber mendapatkan elemen grafis. |

### Nilai Kembalian

String dengan konten SVG.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Mengekstrak gambar svg ke file dari elemen grafis yang diwakili oleh !:absorber dengan filter predikat.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Objek GraphicsAbsorber yang berisi elemen grafis. |
| filter | Predicate`1 | Fungsi predikat yang digunakan untuk memfilter elemen grafis. |
| halaman | Halaman | Halaman tempat absorber mendapatkan elemen grafis. |
| svgFilePath | String | Jalur file SVG target. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Mengekstrak elemen grafis menjadi string SVG. Opsi diabaikan - pengelompokan, ekstraksi dari persegi panjang.

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elements | IEnumerable`1 | Elemen grafis yang akan dikonversi. |
| halaman | Halaman | Halaman tempat absorber mendapatkan elemen grafis. |

### Nilai Kembalian

String dengan konten SVG.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Mengekstrak elemen grafis menjadi satu file SVG. Opsi diabaikan - pengelompokan, ekstraksi dari persegi panjang.

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elements | IEnumerable`1 | Elemen grafis yang akan dikonversi. |
| halaman | Halaman | Halaman tempat absorber mendapatkan elemen grafis. |
| svgFilePath | String | Jalur file SVG target. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Mengekstrak gambar Svg dari sebuah halaman menjadi string.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Halaman | Halaman yang akan diekstrak. |

### Nilai Kembalian

Daftar string konten SVG.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Mengekstrak gambar Svg dari sebuah halaman ke file.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Halaman | Halaman yang akan diekstrak. |
| direktori | String | Direktori target untuk menempatkan gambar SVG. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Jika terjadi kesalahan saat mengonversi ke SVG. |

### Lihat Juga

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


