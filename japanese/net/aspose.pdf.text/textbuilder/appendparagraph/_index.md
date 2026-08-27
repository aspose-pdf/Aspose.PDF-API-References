---
title: "TextBuilder.AppendParagraph"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextBuilder メソッド。Pdf ページにテキスト段落を追加します"
type: docs
weight: 20
url: /ja/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

テキスト段落を PDF ページに追加します。

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| textParagraph | TextParagraph | テキスト段落オブジェクト。 |

## 例

この例では、テキスト段落オブジェクトの作成方法とそれを Pdf ページに追加する方法を示しています。

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// テキスト段落を作成する
TextParagraph paragraph = new TextParagraph();
           
// 段落の矩形を設定する
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// ワードラップオプションを設定する
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// 文字列行を追加する
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// TextBuilder を使用して段落を Pdf ページに追加する
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// Pdf ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


