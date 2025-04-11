---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber コンストラクタ。ドキュメントまたはページのすべてのテキストセグメントを検索する TextFragmentAbsorber の新しいインスタンスを初期化します。
type: docs
weight: 10
url: /ja/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

[`TextFragmentAbsorber`](../) の新しいインスタンスを初期化し、ドキュメントまたはページのすべてのテキストセグメントを検索します。

```csharp
public TextFragmentAbsorber()
```

## 備考

テキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

## 例

この例では、最初の PDF ドキュメントページでテキストを見つけて、テキストを置き換える方法を示します。

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

### 関連項目

* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

テキスト編集オプションを使用して、ドキュメントまたはページのすべてのテキストセグメントを検索する [`TextFragmentAbsorber`](../) の新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textEditOptions | TextEditOptions | テキスト編集オプション (いくつかの編集機能をオンにすることができます)。 |

## 備考

テキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

## 例

この例では、最初の PDF ドキュメントページでテキストフラグメントをすべて見つけて、それらのフォントを置き換える方法を示します。

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

### 関連項目

* クラス [TextEditOptions](../../texteditoptions/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

指定されたテキストフレーズのための [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(string phrase)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) が検索するフレーズ |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

## 例

この例では、最初の PDF ドキュメントページでテキストを見つけて、テキストとそのフォントを置き換える方法を示します。

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

### 関連項目

* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

指定された System.Text.RegularExpressions.Regex クラスオブジェクトのための [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(Regex regex)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) が検索する System.Text.RegularExpressions.Regex クラスオブジェクト |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

## 例

この例では、最初の PDF ドキュメントページでテキストを見つけて、テキストとそのフォントを置き換える方法を示します。

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

### 関連項目

* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

指定されたテキストフレーズとテキスト検索オプションのための [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) が検索するフレーズ |
| textSearchOptions | TextSearchOptions | テキスト検索オプション (いくつかの検索機能をオンにすることができます。たとえば、正規表現での検索) |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

## 例

この例では、最初の PDF ドキュメントページで正規表現を使用してテキストを見つけて、テキストを置き換える方法を示します。

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

### 関連項目

* クラス [TextSearchOptions](../../textsearchoptions/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

指定されたテキストフレーズとテキスト検索オプションのための [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) が検索する System.Text.RegularExpressions.Regex クラスオブジェクト |
| textSearchOptions | TextSearchOptions | テキスト検索オプション (いくつかの検索機能をオンにすることができます。) |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

## 例

この例では、最初の PDF ドキュメントページで正規表現を使用してテキストを見つけて、テキストを置き換える方法を示します。

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

### 関連項目

* クラス [TextSearchOptions](../../textsearchoptions/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

指定されたテキストフレーズとテキスト検索オプションのための [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| regexes | Regex[] | [`TextFragmentAbsorber`](../) が検索する System.Text.RegularExpressions.Regex クラスオブジェクトの配列。 |
| textSearchOptions | TextSearchOptions | テキスト検索オプション (いくつかの検索機能をオンにすることができます)。 |

## 備考

指定されたフレーズの配列のテキスト検索を実行し、[`RegexResults`](../regexresults/) 辞書を介して検索結果にアクセスします。

## 例

この例では、最初の PDF ドキュメントページで正規表現の配列を使用してテキストを見つける方法を示します。

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

### 関連項目

* クラス [TextSearchOptions](../../textsearchoptions/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

指定されたテキストフレーズ、テキスト検索オプション、およびテキスト編集オプションのための [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) が検索するフレーズ |
| textSearchOptions | TextSearchOptions | テキスト検索オプション (いくつかの検索機能をオンにすることができます。たとえば、正規表現での検索) |
| textEditOptions | TextEditOptions | テキスト編集オプション (いくつかの編集機能をオンにすることができます)。 |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

## 例

この例では、最初の PDF ドキュメントページで正規表現を使用してテキストを見つけて、テキストを置き換える方法を示します。

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

### 関連項目

* クラス [TextSearchOptions](../../textsearchoptions/)
* クラス [TextEditOptions](../../texteditoptions/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

指定されたテキストフレーズとテキスト編集オプションのための [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) が検索するフレーズ |
| textEditOptions | TextEditOptions | テキスト編集オプション (いくつかの編集機能をオンにすることができます)。 |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

### 関連項目

* クラス [TextEditOptions](../../texteditoptions/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

指定されたテキストフレーズとテキスト編集オプションのための [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) が検索する System.Text.RegularExpressions.Regex クラスオブジェクト |
| textEditOptions | TextEditOptions | テキスト編集オプション (いくつかの編集機能をオンにすることができます)。 |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果にアクセスします。

### 関連項目

* クラス [TextEditOptions](../../texteditoptions/)
* クラス [TextFragmentAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)