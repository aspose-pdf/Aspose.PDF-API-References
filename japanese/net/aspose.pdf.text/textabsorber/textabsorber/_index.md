---
title: "TextAbsorber.TextAbsorber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextAbsorber コンストラクタ。TextAbsorber の新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

[`TextAbsorber`](../) の新しいインスタンスを初期化します。

```csharp
public TextAbsorber()
```

## 備考

テキスト抽出を実行し、抽出されたテキストへ [`Text`](../text/) オブジェクトを介してアクセスできるようにします。

## 例

この例は PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// テキストを抽出するために TextAbsorber オブジェクトを作成します。
TextAbsorber absorber = new TextAbsorber();

// すべての document のページに対してアブソーバーを受け入れます
doc.Pages.Accept(absorber);

// 抽出されたテキストを取得します。
string extractedText = absorber.Text;

```

### 関連項目

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

[`TextAbsorber`](../) を抽出オプションとともに新しいインスタンスとして初期化します。

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | テキスト抽出オプション |

## 備考

テキスト抽出を実行し、抽出されたテキストへ [`Text`](../text/) オブジェクトを介してアクセスできるようにします。

## 例

この例は PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// 書式設定付きでテキストを抽出するために TextAbsorber オブジェクトを作成します。
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// すべての document のページに対してアブソーバーを受け入れます
doc.Pages.Accept(absorber);

// 抽出されたテキストを取得します。
string extractedText = absorber.Text;

```

### 関連項目

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

抽出およびテキスト検索オプションで [`TextAbsorber`](../) の新しいインスタンスを初期化します。

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | テキスト抽出オプション |
| textSearchOptions | TextSearchOptions | テキスト検索オプション |

## 備考

テキスト抽出を実行し、抽出されたテキストへ [`Text`](../text/) オブジェクトを介してアクセスできるようにします。

### 関連項目

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

テキスト検索オプションで [`TextAbsorber`](../) の新しいインスタンスを初期化します。

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | テキスト検索オプション |

## 備考

テキスト抽出を実行し、抽出されたテキストへ [`Text`](../text/) オブジェクトを介してアクセスできるようにします。

### 関連項目

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


