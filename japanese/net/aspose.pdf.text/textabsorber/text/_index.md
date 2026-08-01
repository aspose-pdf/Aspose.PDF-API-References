---
title: "TextAbsorber.Text"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextAbsorber プロパティ。PDF ドキュメントまたはページ上で TextAbsorber が抽出したテキストを取得します。"
type: docs
weight: 50
url: /ja/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

PDF ドキュメントまたはページ上で [`TextAbsorber`](../) が抽出したテキストを取得します。

```csharp
public virtual string Text { get; }
```

## 例

この例は PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// テキストを抽出するために TextAbsorber オブジェクトを作成します。
TextAbsorber absorber = new TextAbsorber();

// すべての document のページに対してアブソーバーを受け入れます
doc.Pages.Accept(absorber);

// 抽出されたテキストを取得します。
string extractedText = absorber.Text;

```

### 関連項目

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


