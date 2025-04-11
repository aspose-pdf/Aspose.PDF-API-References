---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: TextSegment コンストラクタ。TextSegment オブジェクトを作成します。
type: docs
weight: 10
url: /ja/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

TextSegment オブジェクトを作成します。

```csharp
public TextSegment()
```

## 例

この例では、テキストフラグメントオブジェクトを作成し、テキストフラグメントコレクションにテキストセグメントを追加し、それを Pdf ページに追加する方法を示します。

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// create text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// set it's text properties
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// add one more segment to text fragment's Segments collection
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### 関連項目

* クラス [TextSegment](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

TextSegment オブジェクトを作成します。

```csharp
public TextSegment(string text)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | 文字列 | テキストセグメントのテキスト。 |

## 例

この例では、テキストフラグメントオブジェクトを作成し、テキストフラグメントコレクションにテキストセグメントを追加し、それを Pdf ページに追加する方法を示します。

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// create text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// set it's text properties
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// add one more segment to text fragment's Segments collection
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### 関連項目

* クラス [TextSegment](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)