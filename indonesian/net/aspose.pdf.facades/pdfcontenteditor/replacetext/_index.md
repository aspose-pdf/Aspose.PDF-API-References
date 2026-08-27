---
title: "PdfContentEditor.ReplaceText"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Mengganti teks dalam file PDF pada halaman yang ditentukan. Objek TextState font family dan warna dapat ditentukan untuk teks yang diganti."
type: docs
weight: 450
url: /id/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Mengganti teks dalam file PDF pada halaman yang ditentukan. Objek [`TextState`](../../../aspose.pdf.text/textstate/) (font family, warna) dapat ditentukan untuk teks yang diganti.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcString | String | String yang akan diganti. |
| thePage | Int32 | Nomor halaman (0 berarti "semua halaman"). |
| destString | String | String yang telah diganti. |
| textState | TextState | Status teks (Warna Teks, Font, dll). |

### Nilai Kembalian

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks pada halaman pertama dokumen PDF dan mengatur properti teks [`TextState`](../../../aspose.pdf.text/textstate/) untuk teks baru.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// Buat font dan tandai agar disematkan
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// buat objek PdfContentEditor untuk mengedit teks
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// buat objek textState
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// ubah teks dengan font yang ditentukan
editor.ReplaceText("hello world", 1, "hi world", textState);

// simpan dokumen
doc.Save(outFile);
```

### Lihat Juga

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Mengganti teks dalam file PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcString | String | String yang akan diganti. |
| destString | String | Mengganti string. |

### Nilai Kembalian

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks dalam dokumen PDF.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek PdfContentEditor untuk mengedit teks
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ubah teks 
editor.ReplaceText("hello world", "hi world");

// simpan dokumen
doc.Save(outFile);
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Mengganti teks dalam file PDF pada halaman yang ditentukan.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcString | String | String yang akan diganti. |
| thePage | Int32 | Nomor halaman (0 untuk semua halaman) |
| destString | String | Mengganti string. |

### Nilai Kembalian

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks dalam dokumen PDF pada halaman yang ditentukan.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek PdfContentEditor untuk mengedit teks
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ubah teks 
editor.ReplaceText("hello world", 1, "hi world");

// simpan dokumen
doc.Save(outFile);
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Mengganti teks dalam file PDF menggunakan objek [`TextState`](../../../aspose.pdf.text/textstate/) yang ditentukan.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcString | String | String yang akan diganti |
| destString | String | Mengganti string |
| textState | TextState | Status teks (Warna Teks, Font, dll) |

### Nilai Kembalian

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks dan mengatur properti teks [`TextState`](../../../aspose.pdf.text/textstate/) untuk teks baru.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// Buat font dan tandai agar disematkan
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// buat objek PdfContentEditor untuk mengedit teks
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// buat objek textState
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// ubah teks dengan font yang ditentukan
editor.ReplaceText("hello world", "hi world", textState);

// simpan dokumen
doc.Save(outFile);
```

### Lihat Juga

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Mengganti teks dalam file PDF dan mengatur ukuran font.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcString | String | String yang akan diganti. |
| destString | String | Mengganti string. |
| fontSize | Int32 | Ukuran font. |

### Nilai Kembalian

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks dan mengatur ukuran font untuk teks baru.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// Buat font dan tandai agar disematkan
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// buat objek PdfContentEditor untuk mengedit teks
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ubah teks dengan font yang ditentukan
editor.ReplaceText("hello world", "hi world", 14);

// simpan dokumen
doc.Save(outFile);
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


