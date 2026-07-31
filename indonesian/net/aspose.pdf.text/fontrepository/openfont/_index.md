---
title: "FontRepository.OpenFont"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FontRepository. Membuka font dengan aliran font yang ditentukan"
type: docs
weight: 60
url: /id/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Membuka font dengan aliran font yang ditentukan.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontStream | Stream | Aliran font. |
| fontType | FontTypes | Nilai tipe font. |

### Nilai Kembalian

Objek font.

## Contoh

Contoh ini menunjukkan cara membuka font dan mengganti font teks pada page pertama.

```csharp
// Buka font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### Lihat Juga

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Membuka font dengan jalur file font yang ditentukan.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFilePath | String | Path file font. |

### Nilai Kembalian

Objek font.

## Contoh

Contoh ini menunjukkan cara membuka font dan mengganti font teks pada page pertama.

```csharp
// Buka font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

## OpenFont(string, string) {#openfont_2}

Membuka font dengan jalur file font dan jalur file metrik yang ditentukan.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFilePath | String | Path file font. |
| metricsFilePath | String | Path file metrik font. |

### Nilai Kembalian

Objek font.

## Contoh

Contoh ini menunjukkan cara membuka font Type1 dengan metrik dan mengganti font teks pada page pertama.

```csharp
// Buka font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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


