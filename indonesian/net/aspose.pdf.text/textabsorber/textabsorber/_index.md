---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Konstruktor TextAbsorber. Menginisialisasi instance baru dari TextAbsorber
type: docs
weight: 10
url: /id/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Menginisialisasi instance baru dari [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Remarks

Melakukan ekstraksi teks dan memberikan akses ke teks yang diekstrak melalui objek [`Text`](../text/).

## Examples

Contoh ini menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Menginisialisasi instance baru dari [`TextAbsorber`](../) dengan opsi ekstraksi.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opsi ekstraksi teks |

## Remarks

Melakukan ekstraksi teks dan memberikan akses ke teks yang diekstrak melalui objek [`Text`](../text/).

## Examples

Contoh ini menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opsi ekstraksi teks |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks |

## Remarks

Melakukan ekstraksi teks dan memberikan akses ke teks yang diekstrak melalui objek [`Text`](../text/).

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks |

## Remarks

Melakukan ekstraksi teks dan memberikan akses ke teks yang diekstrak melalui objek [`Text`](../text/).

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)