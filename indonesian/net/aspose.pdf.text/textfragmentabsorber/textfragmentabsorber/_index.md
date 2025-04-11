---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Konstruktor TextFragmentAbsorber. Menginisialisasi instance baru dari TextFragmentAbsorber yang melakukan pencarian semua segmen teks dari dokumen atau halaman
type: docs
weight: 10
url: /id/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Menginisialisasi instance baru dari [`TextFragmentAbsorber`](../) yang melakukan pencarian semua segmen teks dari dokumen atau halaman.

```csharp
public TextFragmentAbsorber()
```

## Remarks

Melakukan pencarian teks dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Examples

Contoh ini menunjukkan cara menemukan teks di halaman pertama dokumen PDF dan mengganti teks tersebut.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Make the absorber to search all "hello world" text occurrences
absorber.Phrase = "hello world";

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Menginisialisasi instance baru dari [`TextFragmentAbsorber`](../) dengan opsi edit teks, yang melakukan pencarian semua segmen teks dari dokumen atau halaman.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Opsi edit teks (Memungkinkan untuk mengaktifkan beberapa fitur edit). |

## Remarks

Melakukan pencarian teks dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Examples

Contoh ini menunjukkan cara menemukan semua fragmen teks di halaman pertama dokumen PDF dan mengganti font untuk mereka.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Find Courier font
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Set the font for all the text fragments
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| phrase | String | Frasa yang dicari oleh [`TextFragmentAbsorber`](../) |

## Remarks

Melakukan pencarian teks dari frasa yang ditentukan dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Examples

Contoh ini menunjukkan cara menemukan teks di halaman pertama dokumen PDF dan mengganti teks serta font-nya.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk objek kelas System.Text.RegularExpressions.Regex yang ditentukan.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | Regex | Objek kelas System.Text.RegularExpressions.Regex yang dicari oleh [`TextFragmentAbsorber`](../) |

## Remarks

Melakukan pencarian teks dari frasa yang ditentukan dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Examples

Contoh ini menunjukkan cara menemukan teks di halaman pertama dokumen PDF dan mengganti teks serta font-nya.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextAbsorber object to find all instances of the input regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan dan opsi pencarian teks.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| phrase | String | Frasa yang dicari oleh [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks (Memungkinkan untuk mengaktifkan beberapa fitur pencarian. Misalnya, pencarian dengan ekspresi reguler) |

## Remarks

Melakukan pencarian teks dari frasa yang ditentukan dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Examples

Contoh ini menunjukkan cara menemukan teks dengan ekspresi reguler di halaman pertama dokumen PDF dan mengganti teks tersebut.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan dan opsi pencarian teks.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | Regex | Objek kelas System.Text.RegularExpressions.Regex yang dicari oleh [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks (Memungkinkan untuk mengaktifkan beberapa fitur pencarian.) |

## Remarks

Melakukan pencarian teks dari frasa yang ditentukan dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Examples

Contoh ini menunjukkan cara menemukan teks dengan ekspresi reguler di halaman pertama dokumen PDF dan mengganti teks tersebut.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan dan opsi pencarian teks.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regexes | Regex[] | Array dari objek kelas System.Text.RegularExpressions.Regex yang dicari oleh [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks (Memungkinkan untuk mengaktifkan beberapa fitur pencarian.). |

## Remarks

Melakukan pencarian teks dari array frasa yang ditentukan dan memberikan akses ke hasil pencarian melalui kamus [`RegexResults`](../regexresults/).

## Examples

Contoh ini menunjukkan cara menemukan teks dengan array ekspresi reguler di halaman pertama dokumen PDF.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results of 
var results = absorber.RegexResults;
```

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan, opsi pencarian teks, dan opsi edit teks.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| phrase | String | Frasa yang dicari oleh [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks (Memungkinkan untuk mengaktifkan beberapa fitur pencarian. Misalnya, pencarian dengan ekspresi reguler) |
| textEditOptions | TextEditOptions | Opsi edit teks (Memungkinkan untuk mengaktifkan beberapa fitur edit). |

## Remarks

Melakukan pencarian teks dari frasa yang ditentukan dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Examples

Contoh ini menunjukkan cara menemukan teks dengan ekspresi reguler di halaman pertama dokumen PDF dan mengganti teks tersebut.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan dan opsi edit teks.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| phrase | String | Frasa yang dicari oleh [`TextFragmentAbsorber`](../) |
| textEditOptions | TextEditOptions | Opsi edit teks (Memungkinkan untuk mengaktifkan beberapa fitur edit). |

## Remarks

Melakukan pencarian teks dari frasa yang ditentukan dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan dan opsi edit teks.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | Regex | Objek kelas System.Text.RegularExpressions.Regex yang dicari oleh [`TextFragmentAbsorber`](../) |
| textEditOptions | TextEditOptions | Opsi edit teks (Memungkinkan untuk mengaktifkan beberapa fitur edit). |

## Remarks

Melakukan pencarian teks dari frasa yang ditentukan dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)