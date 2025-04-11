---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: Metode FontRepository. Mencari dan mengembalikan font dengan nama font yang ditentukan
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

### Return Value

Objek Font.

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, bool) {#findfont_3}

Mencari dan mengembalikan font dengan nama font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf besar/kecil.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Nama font. |
| ignoreCase | Boolean | sensitivitas huruf besar/kecil |

### Return Value

Objek Font.

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, FontStyles) {#findfont_1}

Mencari dan mengembalikan font dengan nama font yang ditentukan dan gaya font.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFamilyName | String | Nama keluarga font. |
| stl | FontStyles | Nilai gaya font. |

### Return Value

Objek Font yang sesuai dengan parameter permintaan pencarian.

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* kelas [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Mencari dan mengembalikan font dengan nama font yang ditentukan dan gaya font dengan mengabaikan atau menghormati sensitivitas huruf besar/kecil.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFamilyName | String | Nama keluarga font. |
| stl | FontStyles | Nilai gaya font. |
| ignoreCase | Boolean | sensitivitas huruf besar/kecil |

### Return Value

Objek Font yang sesuai dengan parameter permintaan pencarian.

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* kelas [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)