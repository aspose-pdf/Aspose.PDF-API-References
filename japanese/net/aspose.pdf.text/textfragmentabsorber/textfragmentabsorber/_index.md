---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragmentAbsorber コンストラクタ。ドキュメントまたはページのすべてのテキストセグメントを検索する TextFragmentAbsorber の新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

`[`TextFragmentAbsorber`](../)` がドキュメントまたはページのすべてのテキストセグメントを検索する新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber()
```

## 備考

テキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

## 例

この例では、最初の PDF ドキュメントページ上のテキストを見つけて置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// document テキストフォントを変更するために使用されるフォントを検索します
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// 吸収器に "hello world" テキストのすべての出現箇所を検索させます。
absorber.Phrase = "hello world";

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のテキストを変更します。
absorber.TextFragments[1].Text = "hi world";

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

`[`TextFragmentAbsorber`](../)` をテキスト編集オプションと共に初期化し、ドキュメントまたはページのすべてのテキストセグメントを検索します。

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| textEditOptions | TextEditOptions | テキスト編集オプション（いくつかの編集機能を有効にできます）。 |

## 備考

テキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

## 例

この例では、最初の PDF ドキュメントページ上のすべてのテキストフラグメントを見つけ、それらのフォントを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// Courier フォントを検索します。
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// すべてのテキストフラグメントのフォントを設定します。
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// 保存 document
doc.Save(@"D:\Tests\output.pdf");
```

### 関連項目

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

指定されたテキストフレーズ用に [`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(string phrase)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| phrase | String | `[`TextFragmentAbsorber`](../)` が検索するフレーズ |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

## 例

この例では、最初の PDF 文書ページでテキストを検索し、そのテキストとフォントを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// document テキストフォントを変更するために使用されるフォントを検索します
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のテキストとフォントを変更します
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

指定された System.Text.RegularExpressions.Regex クラス オブジェクト用に、[`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(Regex regex)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) が検索する System.Text.RegularExpressions.Regex クラス オブジェクト |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

## 例

この例では、最初の PDF 文書ページでテキストを検索し、そのテキストとフォントを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// document テキストフォントを変更するために使用されるフォントを検索します
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 入力正規表現のすべてのインスタンスを見つけるために TextAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 「hello」単語を見つけて「Hi」に置き換える必要があります
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 保存 document
doc.Save(@"D:\Tests\output.pdf");
```

### 関連項目

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

指定されたテキストフレーズとテキスト検索オプション用に、[`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| phrase | String | `[`TextFragmentAbsorber`](../)` が検索するフレーズ |
| textSearchOptions | TextSearchOptions | テキスト検索オプション（いくつかの検索機能を有効にできます。例として、正規表現で検索する） |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

## 例

この例は、最初の PDF document page で正規表現を使用してテキストを検索し、テキストを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// 正規表現を使用して、'h' で始まり 'o' で終わるすべての単語を検索する TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// 「hello」単語を見つけて「Hi」に置き換える必要があります
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

指定されたテキストフレーズとテキスト検索オプション用に、[`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) が検索する System.Text.RegularExpressions.Regex クラス オブジェクト |
| textSearchOptions | TextSearchOptions | テキスト検索オプション（いくつかの検索機能を有効にできます。） |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

## 例

この例は、最初の PDF document page で正規表現を使用してテキストを検索し、テキストを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// 正規表現を使用して、'h' で始まり 'o' で終わるすべての単語を検索する TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// 「hello」単語を見つけて「Hi」に置き換える必要があります
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 保存 document
doc.Save(@"D:\Tests\output.pdf");
```

### 関連項目

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

指定されたテキストフレーズとテキスト検索オプション用に、[`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| regexes | Regex[] | [`TextFragmentAbsorber`](../) が検索する System.Text.RegularExpressions.Regex クラス オブジェクトの配列。 |
| textSearchOptions | TextSearchOptions | テキスト検索オプション（いくつかの検索機能を有効にできます）。 |

## 備考

指定されたフレーズの配列をテキスト検索し、[`RegexResults`](../regexresults/) 辞書を介して検索結果へのアクセスを提供します。

## 例

この例は、最初の PDF document page で正規表現の配列を使用してテキストを検索する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// 正規表現を使用して、'h' で始まり 'o' で終わるすべての単語を検索する TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// 取得結果 
var results = absorber.RegexResults;
```

### 関連項目

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

指定されたテキストフレーズ、テキスト検索オプション、およびテキスト編集オプション用に、[`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| phrase | String | `[`TextFragmentAbsorber`](../)` が検索するフレーズ |
| textSearchOptions | TextSearchOptions | テキスト検索オプション（いくつかの検索機能を有効にできます。例として、正規表現で検索する） |
| textEditOptions | TextEditOptions | テキスト編集オプション（いくつかの編集機能を有効にできます）。 |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

## 例

この例は、最初の PDF document page で正規表現を使用してテキストを検索し、テキストを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// 正規表現を使用して、'h' で始まり 'o' で終わるすべての単語を検索する TextFragmentAbsorber オブジェクトを作成します。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// 「hello」単語を見つけて「Hi」に置き換える必要があります
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

指定されたテキストフレーズとテキスト編集オプション用に、[`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| phrase | String | `[`TextFragmentAbsorber`](../)` が検索するフレーズ |
| textEditOptions | TextEditOptions | テキスト編集オプション（いくつかの編集機能を有効にできます）。 |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

### 関連項目

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

指定されたテキストフレーズとテキスト編集オプション用に、[`TextFragmentAbsorber`](../) クラスの新しいインスタンスを初期化します。

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) が検索する System.Text.RegularExpressions.Regex クラス オブジェクト |
| textEditOptions | TextEditOptions | テキスト編集オプション（いくつかの編集機能を有効にできます）。 |

## 備考

指定されたフレーズのテキスト検索を実行し、[`TextFragments`](../textfragments/) コレクションを介して検索結果へのアクセスを提供します。

### 関連項目

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


