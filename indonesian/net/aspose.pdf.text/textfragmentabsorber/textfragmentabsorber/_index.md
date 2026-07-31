---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Konstruktor TextFragmentAbsorber. Menginisialisasi instance baru dari TextFragmentAbsorber yang melakukan pencarian semua segmen teks pada document atau page."
type: docs
weight: 10
url: /id/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Menginisialisasi instance baru dari [`TextFragmentAbsorber`](../) yang melakukan pencarian semua segmen teks pada document atau page.

```csharp
public TextFragmentAbsorber()
```

## Catatan

Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Contoh

Contoh ini menunjukkan cara menemukan teks pada page pertama document PDF dan mengganti teks tersebut.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Temukan font yang akan digunakan untuk mengubah font teks dokumen
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Buat objek TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Buat absorber mencari semua kemunculan teks "hello world"
absorber.Phrase = "hello world";

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah teks pada kemunculan teks pertama
absorber.TextFragments[1].Text = "hi world";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Menginisialisasi instance baru dari [`TextFragmentAbsorber`](../) dengan opsi penyuntingan teks, yang melakukan pencarian semua segmen teks pada document atau page.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Opsi penyuntingan teks (Mengizinkan mengaktifkan beberapa fitur penyuntingan). |

## Catatan

Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Contoh

Contoh ini menunjukkan cara menemukan semua fragmen teks pada halaman pertama dokumen PDF dan mengganti font untuknya.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Temukan font Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Atur font untuk semua fragmen teks
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");
```

### Lihat Juga

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

## Catatan

Melakukan pencarian teks pada frasa yang ditentukan dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Contoh

Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks serta fontnya.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Temukan font yang akan digunakan untuk mengubah font teks dokumen
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah teks dan font pada kemunculan teks pertama
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

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

## Catatan

Melakukan pencarian teks pada frasa yang ditentukan dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Contoh

Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks serta fontnya.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Temukan font yang akan digunakan untuk mengubah font teks dokumen
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Buat objek TextAbsorber untuk menemukan semua instance regex input
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// kita harus menemukan kata "hello" dan menggantinya dengan "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");
```

### Lihat Juga

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
| textSearchOptions | TextSearchOptions | Opsi pencarian teks (Mengizinkan mengaktifkan beberapa fitur pencarian. Misalnya, pencarian dengan ekspresi reguler) |

## Catatan

Melakukan pencarian teks pada frasa yang ditentukan dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Contoh

Contoh ini menunjukkan cara menemukan teks dengan ekspresi reguler pada halaman pertama dokumen PDF dan mengganti teks tersebut.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber yang mencari semua kata yang dimulai dengan 'h' dan diakhiri dengan 'o' menggunakan ekspresi reguler.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// kita harus menemukan kata "hello" dan menggantinya dengan "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

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
| textSearchOptions | TextSearchOptions | Opsi pencarian teks (Mengizinkan mengaktifkan beberapa fitur pencarian.) |

## Catatan

Melakukan pencarian teks pada frasa yang ditentukan dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Contoh

Contoh ini menunjukkan cara menemukan teks dengan ekspresi reguler pada halaman pertama dokumen PDF dan mengganti teks tersebut.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber yang mencari semua kata yang dimulai dengan 'h' dan diakhiri dengan 'o' menggunakan ekspresi reguler.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// kita harus menemukan kata "hello" dan menggantinya dengan "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");
```

### Lihat Juga

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
| regexes | Regex[] | Array objek kelas System.Text.RegularExpressions.Regex yang dicari oleh [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks (Mengizinkan mengaktifkan beberapa fitur pencarian.). |

## Catatan

Melakukan pencarian teks pada array frasa yang ditentukan dan menyediakan akses ke hasil pencarian melalui kamus [`RegexResults`](../regexresults/).

## Contoh

Contoh ini menunjukkan cara menemukan teks dengan array ekspresi reguler pada halaman pertama dokumen PDF.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Buat objek TextFragmentAbsorber yang mencari semua kata yang dimulai dengan 'h' dan diakhiri dengan 'o' menggunakan ekspresi reguler.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Dapatkan hasil dari 
var results = absorber.RegexResults;
```

### Lihat Juga

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan, opsi pencarian teks, dan opsi penyuntingan teks.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| phrase | String | Frasa yang dicari oleh [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | Opsi pencarian teks (Mengizinkan mengaktifkan beberapa fitur pencarian. Misalnya, pencarian dengan ekspresi reguler) |
| textEditOptions | TextEditOptions | Opsi penyuntingan teks (Mengizinkan mengaktifkan beberapa fitur penyuntingan). |

## Catatan

Melakukan pencarian teks pada frasa yang ditentukan dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

## Contoh

Contoh ini menunjukkan cara menemukan teks dengan ekspresi reguler pada halaman pertama dokumen PDF dan mengganti teks tersebut.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber yang mencari semua kata yang dimulai dengan 'h' dan diakhiri dengan 'o' menggunakan ekspresi reguler.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// kita harus menemukan kata "hello" dan menggantinya dengan "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan dan opsi penyuntingan teks.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| phrase | String | Frasa yang dicari oleh [`TextFragmentAbsorber`](../) |
| textEditOptions | TextEditOptions | Opsi penyuntingan teks (Mengizinkan mengaktifkan beberapa fitur penyuntingan). |

## Catatan

Melakukan pencarian teks pada frasa yang ditentukan dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

### Lihat Juga

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Menginisialisasi instance baru dari kelas [`TextFragmentAbsorber`](../) untuk frasa teks yang ditentukan dan opsi penyuntingan teks.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | Regex | Objek kelas System.Text.RegularExpressions.Regex yang dicari oleh [`TextFragmentAbsorber`](../) |
| textEditOptions | TextEditOptions | Opsi penyuntingan teks (Mengizinkan mengaktifkan beberapa fitur penyuntingan). |

## Catatan

Melakukan pencarian teks pada frasa yang ditentukan dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](../textfragments/).

### Lihat Juga

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


