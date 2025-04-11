---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 생성자. 문서 또는 페이지의 모든 텍스트 세그먼트를 검색하는 TextFragmentAbsorber의 새 인스턴스를 초기화합니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

[`TextFragmentAbsorber`](../)의 새 인스턴스를 초기화하여 문서 또는 페이지의 모든 텍스트 세그먼트를 검색합니다.

```csharp
public TextFragmentAbsorber()
```

## Remarks

텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 텍스트를 교체하는 방법을 보여줍니다.

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

텍스트 편집 옵션으로 [`TextFragmentAbsorber`](../)의 새 인스턴스를 초기화하여 문서 또는 페이지의 모든 텍스트 세그먼트를 검색합니다.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textEditOptions | TextEditOptions | 텍스트 편집 옵션(일부 편집 기능을 활성화할 수 있습니다). |

## Remarks

텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 모든 텍스트 조각을 찾고 해당 글꼴을 교체하는 방법을 보여줍니다.

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

지정된 텍스트 구문에 대한 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../)가 검색하는 구문 |

## Remarks

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 텍스트와 글꼴을 교체하는 방법을 보여줍니다.

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

지정된 System.Text.RegularExpressions.Regex 클래스 객체에 대한 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../)가 검색하는 System.Text.RegularExpressions.Regex 클래스 객체 |

## Remarks

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 텍스트와 글꼴을 교체하는 방법을 보여줍니다.

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

지정된 텍스트 구문 및 텍스트 검색 옵션에 대한 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../)가 검색하는 구문 |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션(일부 검색 기능을 활성화할 수 있습니다. 예: 정규 표현식으로 검색) |

## Remarks

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 정규 표현식으로 텍스트를 찾고 텍스트를 교체하는 방법을 보여줍니다.

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

지정된 텍스트 구문 및 텍스트 검색 옵션에 대한 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../)가 검색하는 System.Text.RegularExpressions.Regex 클래스 객체 |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션(일부 검색 기능을 활성화할 수 있습니다.) |

## Remarks

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 정규 표현식으로 텍스트를 찾고 텍스트를 교체하는 방법을 보여줍니다.

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

지정된 텍스트 구문 및 텍스트 검색 옵션에 대한 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regexes | Regex[] | [`TextFragmentAbsorber`](../)가 검색하는 System.Text.RegularExpressions.Regex 클래스 객체의 배열. |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션(일부 검색 기능을 활성화할 수 있습니다.). |

## Remarks

지정된 구문 배열에 대한 텍스트 검색을 수행하고 [`RegexResults`](../regexresults/) 사전을 통해 검색 결과에 대한 액세스를 제공합니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 정규 표현식 배열로 텍스트를 찾는 방법을 보여줍니다.

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

지정된 텍스트 구문, 텍스트 검색 옵션 및 텍스트 편집 옵션에 대한 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../)가 검색하는 구문 |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션(일부 검색 기능을 활성화할 수 있습니다. 예: 정규 표현식으로 검색) |
| textEditOptions | TextEditOptions | 텍스트 편집 옵션(일부 편집 기능을 활성화할 수 있습니다). |

## Remarks

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 정규 표현식으로 텍스트를 찾고 텍스트를 교체하는 방법을 보여줍니다.

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

지정된 텍스트 구문 및 텍스트 편집 옵션에 대한 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../)가 검색하는 구문 |
| textEditOptions | TextEditOptions | 텍스트 편집 옵션(일부 편집 기능을 활성화할 수 있습니다). |

## Remarks

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

지정된 텍스트 구문 및 텍스트 편집 옵션에 대한 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../)가 검색하는 System.Text.RegularExpressions.Regex 클래스 객체 |
| textEditOptions | TextEditOptions | 텍스트 편집 옵션(일부 편집 기능을 활성화할 수 있습니다). |

## Remarks

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)