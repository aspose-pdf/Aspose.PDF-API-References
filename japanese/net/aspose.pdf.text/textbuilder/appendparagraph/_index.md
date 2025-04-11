---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder メソッド。Pdf ページにテキスト段落を追加します
type: docs
weight: 20
url: /ja/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph メソッド

Pdf ページにテキスト段落を追加します。

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textParagraph | TextParagraph | テキスト段落オブジェクト。 |

## 例

この例では、テキスト段落オブジェクトを作成し、それを Pdf ページに追加する方法を示します。

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### 参照

* クラス [TextParagraph](../../textparagraph/)
* クラス [TextBuilder](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)