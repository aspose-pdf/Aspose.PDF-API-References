---
title: "TextSegment.TextSegment"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextSegment コンストラクタ。TextSegment オブジェクトを作成します"
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

この例では、テキストフラグメントオブジェクトを作成し、テキストセグメントをテキストフラグメントコレクションに追加して、Pdf ページに追加する方法を示します。

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// テキストフラグメントを作成する
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// テキストのプロパティを設定する
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// テキスト フラグメントの Segments コレクションにさらに 1 つのセグメントを追加します
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// TextBuilder オブジェクトを作成します
TextBuilder builder = new TextBuilder(page);

// テキスト フラグメントを Pdf ページに追加します
builder.AppendText(tf);

//ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

TextSegment オブジェクトを作成します。

```csharp
public TextSegment(string text)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| テキスト | String | テキストセグメントのテキスト。 |

## 例

この例では、テキストフラグメントオブジェクトを作成し、テキストセグメントをテキストフラグメントコレクションに追加して、Pdf ページに追加する方法を示します。

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// テキストフラグメントを作成する
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// テキストのプロパティを設定する
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// テキスト フラグメントの Segments コレクションにさらに 1 つのセグメントを追加します
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// TextBuilder オブジェクトを作成します
TextBuilder builder = new TextBuilder(page);

// テキスト フラグメントを Pdf ページに追加します
builder.AppendText(tf);

//ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


