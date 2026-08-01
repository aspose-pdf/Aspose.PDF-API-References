---
title: "Font.IsAccessible"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Font プロパティ。フォントがシステムにインストールされているかどうかを示す値を取得します"
type: docs
weight: 50
url: /ja/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

システムにフォントが存在（インストール）しているかどうかを示す値を取得します。

```csharp
public bool IsAccessible { get; }
```

## 備考

システムで見つからないフォントに対しては、一部の操作は利用できません。

## 例

この例は、最初のページでテキストを検索し、フォントがシステムにインストールされているかどうかを示す値を取得する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントの IsSubset 値を表示します
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### 関連項目

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


