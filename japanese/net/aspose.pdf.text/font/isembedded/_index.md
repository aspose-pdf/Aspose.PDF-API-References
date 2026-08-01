---
title: "Font.IsEmbedded"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Font プロパティ。フォントが埋め込まれているかどうかを示す値を取得または設定します。IFont に基づく Font は自動的にサブセット化され、埋め込まれます。"
type: docs
weight: 60
url: /ja/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

フォントが埋め込まれているかどうかを示す値を取得または設定します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。

```csharp
public bool IsEmbedded { get; set; }
```

## 例

以下の例は、フォントを検索し、埋め込みとしてマークし、document のページ上でテキストを検索してテキストフォントを置換する方法を示しています。

```csharp
// フォントを作成し、埋め込み対象としてマークします。
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// ドキュメントを開く
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// 最初のページに対して absorber を受け入れます。
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントを変更します
absorber.TextFragments[1].TextState.Font = font;

// ドキュメントを保存する
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


