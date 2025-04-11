---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber yapıcısı. Belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir TextFragmentAbsorber örneğini başlatır.
type: docs
weight: 10
url: /tr/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir [`TextFragmentAbsorber`](../) örneğini başlatır.

```csharp
public TextFragmentAbsorber()
```

## Açıklamalar

Metin araması yapar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

## Örnekler

Örnek, ilk PDF belgesi sayfasında metin bulmayı ve metni değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Belgenin veya sayfanın tüm metin segmentlerini arayan metin düzenleme seçenekleri ile yeni bir [`TextFragmentAbsorber`](../) örneğini başlatır.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Metin düzenleme seçenekleri (Bazı düzenleme özelliklerini açmaya izin verir). |

## Açıklamalar

Metin araması yapar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

## Örnekler

Örnek, ilk PDF belgesi sayfasındaki tüm metin parçalarını bulmayı ve bunlar için yazı tipini değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextEditOptions](../../texteditoptions/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Belirtilen metin ifadesi için yeni bir [`TextFragmentAbsorber`](../) sınıf örneğini başlatır.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) tarafından aranan ifade |

## Açıklamalar

Belirtilen ifadeyi arar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

## Örnekler

Örnek, ilk PDF belgesi sayfasında metin bulmayı ve metni ve yazı tipini değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Belirtilen System.Text.RegularExpressions.Regex sınıf nesnesi için yeni bir [`TextFragmentAbsorber`](../) sınıf örneğini başlatır.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) tarafından aranan System.Text.RegularExpressions.Regex sınıf nesnesi |

## Açıklamalar

Belirtilen ifadeyi arar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

## Örnekler

Örnek, ilk PDF belgesi sayfasında metin bulmayı ve metni ve yazı tipini değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Belirtilen metin ifadesi ve metin arama seçenekleri için yeni bir [`TextFragmentAbsorber`](../) sınıf örneğini başlatır.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) tarafından aranan ifade |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri (Bazı arama özelliklerini açmaya izin verir. Örneğin, düzenli ifadelerle arama) |

## Açıklamalar

Belirtilen ifadeyi arar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

## Örnekler

Örnek, ilk PDF belgesi sayfasında düzenli ifadelerle metin bulmayı ve metni değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextSearchOptions](../../textsearchoptions/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Belirtilen metin ifadesi ve metin arama seçenekleri için yeni bir [`TextFragmentAbsorber`](../) sınıf örneğini başlatır.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) tarafından aranan System.Text.RegularExpressions.Regex sınıf nesnesi |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri (Bazı arama özelliklerini açmaya izin verir.) |

## Açıklamalar

Belirtilen ifadeyi arar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

## Örnekler

Örnek, ilk PDF belgesi sayfasında düzenli ifadelerle metin bulmayı ve metni değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextSearchOptions](../../textsearchoptions/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Belirtilen metin ifadesi ve metin arama seçenekleri için yeni bir [`TextFragmentAbsorber`](../) sınıf örneğini başlatır.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regexes | Regex[] | [`TextFragmentAbsorber`](../) tarafından aranan System.Text.RegularExpressions.Regex sınıf nesnelerinin dizisi. |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri (Bazı arama özelliklerini açmaya izin verir.). |

## Açıklamalar

Belirtilen ifade dizisini arar ve arama sonuçlarına [`RegexResults`](../regexresults/) sözlüğü aracılığıyla erişim sağlar.

## Örnekler

Örnek, ilk PDF belgesi sayfasında düzenli ifadelerle metin bulmayı gösterir.

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

### Ayrıca Bakınız

* sınıf [TextSearchOptions](../../textsearchoptions/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Belirtilen metin ifadesi, metin arama seçenekleri ve metin düzenleme seçenekleri için yeni bir [`TextFragmentAbsorber`](../) sınıf örneğini başlatır.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) tarafından aranan ifade |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri (Bazı arama özelliklerini açmaya izin verir. Örneğin, düzenli ifadelerle arama) |
| textEditOptions | TextEditOptions | Metin düzenleme seçenekleri (Bazı düzenleme özelliklerini açmaya izin verir). |

## Açıklamalar

Belirtilen ifadeyi arar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

## Örnekler

Örnek, ilk PDF belgesi sayfasında düzenli ifadelerle metin bulmayı ve metni değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextSearchOptions](../../textsearchoptions/)
* sınıf [TextEditOptions](../../texteditoptions/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Belirtilen metin ifadesi ve metin düzenleme seçenekleri için yeni bir [`TextFragmentAbsorber`](../) sınıf örneğini başlatır.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) tarafından aranan ifade |
| textEditOptions | TextEditOptions | Metin düzenleme seçenekleri (Bazı düzenleme özelliklerini açmaya izin verir). |

## Açıklamalar

Belirtilen ifadeyi arar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

### Ayrıca Bakınız

* sınıf [TextEditOptions](../../texteditoptions/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Belirtilen metin ifadesi ve metin düzenleme seçenekleri için yeni bir [`TextFragmentAbsorber`](../) sınıf örneğini başlatır.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) tarafından aranan System.Text.RegularExpressions.Regex sınıf nesnesi |
| textEditOptions | TextEditOptions | Metin düzenleme seçenekleri (Bazı düzenleme özelliklerini açmaya izin verir). |

## Açıklamalar

Belirtilen ifadeyi arar ve arama sonuçlarına [`TextFragments`](../textfragments/) koleksiyonu aracılığıyla erişim sağlar.

### Ayrıca Bakınız

* sınıf [TextEditOptions](../../texteditoptions/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)