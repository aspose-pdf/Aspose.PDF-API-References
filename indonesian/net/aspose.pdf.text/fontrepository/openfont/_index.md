---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: Metode FontRepository. Membuka font dengan aliran font yang ditentukan
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

### Return Value

Objek Font.

## Contoh

Contoh ini menunjukkan cara membuka font dan mengganti font teks pada halaman pertama.

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

    // Open document
    Document doc = new Document(@"D:\Tests\input.pdf");

    // Create TextFragmentAbsorber object to find all "hello world" text occurrences
    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

    // Accept the absorber for first page
    doc.Pages[1].Accept(absorber);

    // Change font of the first text occurrence
    absorber.TextFragments[1].TextState.Font = font;

    // Save document
    doc.Save(@"D:\Tests\output.pdf"); 
}
```

### Lihat Juga

* kelas [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* kelas [FontRepository](../)
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
| fontFilePath | String | Jalur file font. |

### Return Value

Objek Font.

## Contoh

Contoh ini menunjukkan cara membuka font dan mengganti font teks pada halaman pertama.

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [Font](../../font/)
* kelas [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Membuka font dengan jalur file font yang ditentukan dan jalur file metrik.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFilePath | String | Jalur file font. |
| metricsFilePath | String | Jalur file metrik font. |

### Return Value

Objek Font.

## Contoh

Contoh ini menunjukkan cara membuka font Type1 dengan metrik dan mengganti font teks pada halaman pertama.

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [Font](../../font/)
* kelas [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)