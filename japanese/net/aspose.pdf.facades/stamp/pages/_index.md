---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: スタンププロパティ。スタンプの影響を受けるページ番号の配列を取得または設定します。Pages が null の場合、ドキュメントのすべてのページが影響を受けます。
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages プロパティ

スタンプの影響を受けるページ番号の配列を取得または設定します。Pages = null の場合、ドキュメントのすべてのページが影響を受けます。

```csharp
public int[] Pages { get; set; }
```

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 関連項目

* クラス [Stamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)