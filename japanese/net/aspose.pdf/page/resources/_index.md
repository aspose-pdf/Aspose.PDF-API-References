---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。ページリソースを取得します。リソースオブジェクトには、画像、フォーム、フォントのコレクションが含まれています。リソース
type: docs
weight: 240
url: /ja/net/aspose.pdf/page/resources/
---
## Page.Resources プロパティ

ページリソースを取得します。リソースオブジェクトには、画像、フォーム、フォントのコレクションが含まれています。 `Resources`

```csharp
public Resources Resources { get; }
```

## 例

例はページ画像をスキャンすることを示しています:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### 参照

* クラス [Resources](../../resources/)
* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)