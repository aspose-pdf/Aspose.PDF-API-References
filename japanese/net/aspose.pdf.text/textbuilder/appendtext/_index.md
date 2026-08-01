---
title: "TextBuilder.AppendText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextBuilder メソッド。Pdf ページにテキストフラグメントを追加します"
type: docs
weight: 30
url: /ja/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Pdf ページにテキスト フラグメントを追加します

```csharp
public void AppendText(TextFragment textFragment)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| textFragment | TextFragment | テキストフラグメントオブジェクト。 |

## 例

この例では、テキストフラグメントオブジェクトを作成し、そのテキストセグメントをカスタマイズして Pdf ページに追加する方法を示しています。

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

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Pdf ページにテキスト フラグメントのリストを追加します。

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| textFragments | List`1 | テキスト フラグメントのコレクション |

### 関連項目

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


