---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Mengganti teks dalam file PDF pada halaman yang ditentukan. Warna keluarga font objek TextState dapat ditentukan untuk teks yang diganti
type: docs
weight: 450
url: /id/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Mengganti teks dalam file PDF pada halaman yang ditentukan. Objek [`TextState`](../../../aspose.pdf.text/textstate/) (keluarga font, warna) dapat ditentukan untuk teks yang diganti.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcString | String | String yang akan diganti. |
| thePage | Int32 | Nomor halaman (0 berarti "semua halaman"). |
| destString | String | String yang diganti. |
| textState | TextState | Status teks (Warna Teks, Font, dll). |

### Return Value

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks di halaman pertama dokumen PDF dan mengatur properti teks [`TextState`](../../../aspose.pdf.text/textstate/) untuk teks baru.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### Lihat Juga

* kelas [TextState](../../../aspose.pdf.text/textstate/)
* kelas [PdfContentEditor](../)
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
| destString | String | String pengganti. |

### Return Value

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks dalam dokumen PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### Lihat Juga

* kelas [PdfContentEditor](../)
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
| destString | String | String pengganti. |

### Return Value

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks dalam dokumen PDF pada halaman yang ditentukan.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### Lihat Juga

* kelas [PdfContentEditor](../)
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
| destString | String | String pengganti |
| textState | TextState | Status teks (Warna Teks, Font, dll) |

### Return Value

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks dan mengatur properti teks [`TextState`](../../../aspose.pdf.text/textstate/) untuk teks baru.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### Lihat Juga

* kelas [TextState](../../../aspose.pdf.text/textstate/)
* kelas [PdfContentEditor](../)
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
| destString | String | String pengganti. |
| fontSize | Int32 | Ukuran font. |

### Return Value

Mengembalikan true jika penggantian dilakukan.

## Contoh

Contoh ini menunjukkan cara mengganti teks dan mengatur ukuran font untuk teks baru.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)