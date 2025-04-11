---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Memisahkan file PDF menjadi dokumen halaman tunggal
type: docs
weight: 370
url: /id/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Memisahkan file PDF menjadi dokumen halaman tunggal.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Nama file PDF masukan. |

### Return Value

Aliran PDF keluaran, setiap aliran menyimpan dokumen PDF halaman tunggal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Memisahkan file Pdf menjadi dokumen halaman tunggal.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran Pdf masukan. |

### Return Value

Array aliran memori yang berisi halaman-halaman dokumen.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Memisahkan file Pdf menjadi dokumen halaman tunggal dan menyimpannya ke dalam jalur yang ditentukan. Jalur ditentukan oleh nama template field.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Nama file masukan. |
| fileNameTemplate | String | Template nama file hasil. Harus mengandung %NUM% yang diganti dengan nomor halaman. Misalnya, jika c:/dir/page%NUM%.pdf ditentukan, file hasil akan memiliki nama sebagai berikut: c:/dir/page1.pdf, c:/dir/page2.pdf, dll. |

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Memisahkan file Pdf menjadi dokumen halaman tunggal dan menyimpannya ke dalam jalur yang ditentukan. Jalur ditentukan oleh nama template field.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran dokumen sumber. |
| fileNameTemplate | String | Template nama file hasil. Harus mengandung %NUM% yang diganti dengan nomor halaman. Misalnya, jika c:/dir/page%NUM%.pdf ditentukan, file hasil akan memiliki nama sebagai berikut: c:/dir/page1.pdf, c:/dir/page2.pdf, dll. |

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)