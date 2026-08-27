---
title: "PdfFileEditor.SplitToPages"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Membagi file PDF menjadi dokumen satu halaman."
type: docs
weight: 370
url: /id/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Membagi file PDF menjadi dokumen satu halaman.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Nama file PDF input. |

### Nilai Kembalian

Aliran PDF keluaran, setiap aliran menampung sebuah dokumen PDF satu halaman.

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Membagi file Pdf menjadi dokumen satu halaman.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran Pdf masukan. |

### Nilai Kembalian

Array aliran memori yang berisi halaman-halaman dokumen.

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Membagi file Pdf menjadi dokumen satu halaman dan menyimpannya ke jalur yang ditentukan. Jalur ditentukan oleh nama bidang temaplate.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Nama file masukan. |
| fileNameTemplate | String | Templat nama file hasil. Harus mengandung %NUM% yang akan diganti dengan nomor halaman. Misalnya, jika c:/dir/page%NUM%.pdf ditentukan, file hasil akan memiliki nama berikut: c:/dir/page1.pdf, c:/dir/page2.pdf, dll. |

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Membagi file Pdf menjadi dokumen satu halaman dan menyimpannya ke jalur yang ditentukan. Jalur ditentukan oleh nama bidang temaplate.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran dokumen sumber. |
| fileNameTemplate | String | Templat nama file hasil. Harus mengandung %NUM% yang akan diganti dengan nomor halaman. Misalnya, jika c:/dir/page%NUM%.pdf ditentukan, file hasil akan memiliki nama berikut: c:/dir/page1.pdf, c:/dir/page2.pdf, dll. |

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


