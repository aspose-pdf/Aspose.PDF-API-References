---
title: "Page.Resources"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page プロパティ。ページのリソースを取得します。Resources オブジェクトは画像、フォーム、フォントのコレクションを含みます。Resources"
type: docs
weight: 240
url: /ja/net/aspose.pdf/page/resources/
---
## Page.Resources property

ページのリソースを取得します。Resources オブジェクトは画像、フォーム、フォントのコレクションを含みます。 `Resources`

```csharp
public Resources Resources { get; }
```

## 例

例ではページ画像のスキャンを示しています：

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### 関連項目

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


