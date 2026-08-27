---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragmentAbsorber 생성자. 문서 또는 페이지의 모든 텍스트 세그먼트를 검색하는 TextFragmentAbsorber의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

문서 또는 페이지의 모든 텍스트 세그먼트를 검색하는 [`TextFragmentAbsorber`](../)의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber()
```

## 비고

텍스트 검색을 수행하고 검색 결과에 대한 액세스를 [`TextFragments`](../textfragments/) 컬렉션을 통해 제공합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 해당 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 문서 텍스트 폰트를 변경하는 데 사용할 폰트를 찾습니다.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// 흡수기가 "hello world" 텍스트 발생을 모두 검색하도록 합니다.
absorber.Phrase = "hello world";

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 텍스트를 변경합니다.
absorber.TextFragments[1].Text = "hi world";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

`[`TextFragmentAbsorber`](../)`를 텍스트 편집 옵션과 함께 초기화하여 문서 또는 페이지의 모든 텍스트 세그먼트를 검색합니다.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textEditOptions | TextEditOptions | 텍스트 편집 옵션(일부 편집 기능을 활성화할 수 있음). |

## 비고

텍스트 검색을 수행하고 검색 결과에 대한 액세스를 [`TextFragments`](../textfragments/) 컬렉션을 통해 제공합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 모든 텍스트 조각을 찾아 해당 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// Courier 글꼴을 찾습니다.
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// 모든 텍스트 조각에 대한 글꼴을 설정합니다.
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");
```

### 또 보기

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

지정된 텍스트 구문에 대해 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(string phrase)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| phrase | String | `[`TextFragmentAbsorber`](../)`가 검색하는 구문 |

## 비고

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 해당 텍스트와 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 문서 텍스트 폰트를 변경하는 데 사용할 폰트를 찾습니다.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 텍스트와 폰트를 변경합니다.
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

지정된 System.Text.RegularExpressions.Regex 클래스 객체에 대해 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| regex | Regex | `[`TextFragmentAbsorber`](../)`가 검색하는 System.Text.RegularExpressions.Regex 클래스 객체 |

## 비고

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 해당 텍스트와 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 문서 텍스트 폰트를 변경하는 데 사용할 폰트를 찾습니다.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 입력된 정규식의 모든 인스턴스를 찾기 위해 TextAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// "hello" 단어를 찾아 "Hi"로 교체해야 합니다.
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");
```

### 또 보기

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

지정된 텍스트 구문과 텍스트 검색 옵션에 대해 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| phrase | String | `[`TextFragmentAbsorber`](../)`가 검색하는 구문 |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션 (일부 검색 기능을 활성화할 수 있습니다. 예를 들어, 정규식을 사용한 검색). |

## 비고

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 정규식을 사용해 텍스트를 찾고 해당 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 정규식을 사용하여 'h'로 시작하고 'o'로 끝나는 모든 단어를 검색하는 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// "hello" 단어를 찾아 "Hi"로 교체해야 합니다.
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

지정된 텍스트 구문과 텍스트 검색 옵션에 대해 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| regex | Regex | `[`TextFragmentAbsorber`](../)`가 검색하는 System.Text.RegularExpressions.Regex 클래스 객체 |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션 (일부 검색 기능을 활성화할 수 있습니다.) |

## 비고

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 정규식을 사용해 텍스트를 찾고 해당 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 정규식을 사용하여 'h'로 시작하고 'o'로 끝나는 모든 단어를 검색하는 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// "hello" 단어를 찾아 "Hi"로 교체해야 합니다.
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");
```

### 또 보기

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

지정된 텍스트 구문과 텍스트 검색 옵션에 대해 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| regexes | Regex[] | `[`TextFragmentAbsorber`](../)`가 검색하는 System.Text.RegularExpressions.Regex 클래스 객체 배열. |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션 (일부 검색 기능을 활성화할 수 있습니다.). |

## 비고

지정된 구문 배열에 대한 텍스트 검색을 수행하고 [`RegexResults`](../regexresults/) 사전을 통해 검색 결과에 접근할 수 있게 합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 정규식 배열을 사용해 텍스트를 찾는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// 정규식을 사용하여 'h'로 시작하고 'o'로 끝나는 모든 단어를 검색하는 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// 다음의 결과를 가져옵니다
var results = absorber.RegexResults;
```

### 또 보기

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

지정된 텍스트 구문, 텍스트 검색 옵션 및 텍스트 편집 옵션에 대해 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| phrase | String | `[`TextFragmentAbsorber`](../)`가 검색하는 구문 |
| textSearchOptions | TextSearchOptions | 텍스트 검색 옵션 (일부 검색 기능을 활성화할 수 있습니다. 예를 들어, 정규식을 사용한 검색). |
| textEditOptions | TextEditOptions | 텍스트 편집 옵션(일부 편집 기능을 활성화할 수 있음). |

## 비고

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 정규식을 사용해 텍스트를 찾고 해당 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 정규식을 사용하여 'h'로 시작하고 'o'로 끝나는 모든 단어를 검색하는 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// "hello" 단어를 찾아 "Hi"로 교체해야 합니다.
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

지정된 텍스트 구문과 텍스트 편집 옵션에 대해 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| phrase | String | `[`TextFragmentAbsorber`](../)`가 검색하는 구문 |
| textEditOptions | TextEditOptions | 텍스트 편집 옵션(일부 편집 기능을 활성화할 수 있음). |

## 비고

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

### 또 보기

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

지정된 텍스트 구문과 텍스트 편집 옵션에 대해 [`TextFragmentAbsorber`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| regex | Regex | `[`TextFragmentAbsorber`](../)`가 검색하는 System.Text.RegularExpressions.Regex 클래스 객체 |
| textEditOptions | TextEditOptions | 텍스트 편집 옵션(일부 편집 기능을 활성화할 수 있음). |

## 비고

지정된 구문에 대한 텍스트 검색을 수행하고 [`TextFragments`](../textfragments/) 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

### 또 보기

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


