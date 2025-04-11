---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber コンストラクタ。TextAbsorber の新しいインスタンスを初期化します。
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

テキスト抽出を行い、抽出されたテキストに [`Text`](../text/) オブジェクトを介してアクセスします。

## 例

この例では、PDF ドキュメントのすべてのページからテキストを抽出する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 関連項目

* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

抽出オプションを使用して [`TextAbsorber`](../) の新しいインスタンスを初期化します。

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | テキスト抽出オプション |

## 備考

テキスト抽出を行い、抽出されたテキストに [`Text`](../text/) オブジェクトを介してアクセスします。

## 例

この例では、PDF ドキュメントのすべてのページからテキストを抽出する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 関連項目

* クラス [TextExtractionOptions](../../textextractionoptions/)
* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

抽出およびテキスト検索オプションを使用して [`TextAbsorber`](../) の新しいインスタンスを初期化します。

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | テキスト抽出オプション |
| textSearchOptions | TextSearchOptions | テキスト検索オプション |

## 備考

テキスト抽出を行い、抽出されたテキストに [`Text`](../text/) オブジェクトを介してアクセスします。

### 関連項目

* クラス [TextExtractionOptions](../../textextractionoptions/)
* クラス [TextSearchOptions](../../textsearchoptions/)
* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

テキスト検索オプションを使用して [`TextAbsorber`](../) の新しいインスタンスを初期化します。

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | テキスト検索オプション |

## 備考

テキスト抽出を行い、抽出されたテキストに [`Text`](../text/) オブジェクトを介してアクセスします。

### 関連項目

* クラス [TextSearchOptions](../../textsearchoptions/)
* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)