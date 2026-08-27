---
title: "TextFragment.Text"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragment プロパティ。TextFragment オブジェクトが表す文字列テキストオブジェクトを取得または設定します。"
type: docs
weight: 130
url: /ja/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

[`TextFragment`](../) オブジェクトが表す文字列テキストオブジェクトを取得または設定します。

```csharp
public string Text { get; set; }
```

## 例

この例は、テキストを検索し、[`TextFragment`](../) オブジェクトで表される最初の出現箇所を置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントを変更
absorber.TextFragments[1].Text = "hi world";

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


