---
title: "FontRepository.FindFont"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FontRepository. Mencari dan mengembalikan font dengan nama font yang ditentukan."
type: docs
weight: 40
url: /id/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Mencari dan mengembalikan font dengan nama font yang ditentukan.

```csharp
public static Font FindFont(string fontName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Nama font. |

### Nilai Kembalian

Objek font.

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Temukan font
Font font = FontRepository.FindFont("Arial");

// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah font pada kemunculan teks pertama
absorber.TextFragments[1].TextState.Font = font;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Mencari dan mengembalikan font dengan nama font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Nama font. |
| ignoreCase | Boolean | sensitivitas huruf |

### Nilai Kembalian

Objek font.

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Temukan font
Font font = FontRepository.FindFont("Arial");

// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah font pada kemunculan teks pertama
absorber.TextFragments[1].TextState.Font = font;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFamilyName | String | Nama keluarga font. |
| stl | FontStyles | Nilai gaya font. |

### Nilai Kembalian

Objek font yang sesuai dengan parameter permintaan pencarian.

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Temukan font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah font pada kemunculan teks pertama
absorber.TextFragments[1].TextState.Font = font;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFamilyName | String | Nama keluarga font. |
| stl | FontStyles | Nilai gaya font. |
| ignoreCase | Boolean | sensitivitas huruf |

### Nilai Kembalian

Objek font yang sesuai dengan parameter permintaan pencarian.

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Temukan font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah font pada kemunculan teks pertama
absorber.TextFragments[1].TextState.Font = font;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


