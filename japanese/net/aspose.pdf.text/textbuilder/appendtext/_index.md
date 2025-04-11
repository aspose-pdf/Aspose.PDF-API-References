---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder メソッド。Pdf ページにテキストフラグメントを追加します
type: docs
weight: 30
url: /ja/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Pdf ページにテキストフラグメントを追加します

```csharp
public void AppendText(TextFragment textFragment)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textFragment | TextFragment | テキストフラグメントオブジェクト。 |

## 例

この例では、テキストフラグメントオブジェクトを作成し、そのテキストセグメントをカスタマイズして Pdf ページに追加する方法を示します。

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

* クラス [TextFragment](../../textfragment/)
* クラス [TextBuilder](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Pdf ページにテキストフラグメントのリストを追加します。

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textFragments | List`1 | テキストフラグメントのコレクション |

### 関連項目

* クラス [TextFragment](../../textfragment/)
* クラス [TextBuilder](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)