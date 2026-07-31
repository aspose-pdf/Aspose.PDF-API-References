---
title: "TextAbsorber.TextAbsorber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Konstruktor TextAbsorber. Menginisialisasi instance baru dari TextAbsorber"
type: docs
weight: 10
url: /id/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Menginisialisasi instance baru dari [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Catatan

Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek [`Text`](../text/).

## Contoh

Contoh ini menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek TextAbsorber untuk mengekstrak teks
TextAbsorber absorber = new TextAbsorber();

// terima absorber untuk semua halaman dokumen
doc.Pages.Accept(absorber);

// dapatkan teks yang diekstrak
string extractedText = absorber.Text;

```

### Lihat Juga

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Menginisialisasi instance baru dari [`TextAbsorber`](../) dengan opsi ekstraksi.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opsi ekstraksi teks |

## Catatan

Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek [`Text`](../text/).

## Contoh

Contoh ini menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek TextAbsorber untuk mengekstrak teks dengan pemformatan
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// terima absorber untuk semua halaman dokumen
doc.Pages.Accept(absorber);

// dapatkan teks yang diekstrak
string extractedText = absorber.Text;

```

### Lihat Juga

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Menginisialisasi instance baru dari [`TextAbsorber`](../) dengan opsi ekstraksi dan pencarian teks.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opsi ekstraksi teks |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks |

## Catatan

Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek [`Text`](../text/).

### Lihat Juga

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Menginisialisasi instance baru dari [`TextAbsorber`](../) dengan opsi pencarian teks.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks |

## Catatan

Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek [`Text`](../text/).

### Lihat Juga

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


