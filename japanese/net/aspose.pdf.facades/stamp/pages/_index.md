---
title: "Stamp.Pages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Stamp プロパティ。スタンプの影響を受けるページ番号の配列を取得または設定します。Pages が null の場合、ドキュメントのすべてのページが対象になります"
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

スタンプの影響を受けるページ番号の配列を取得または設定します。Pages が null の場合、ドキュメントのすべてのページが対象になります。

```csharp
public int[] Pages { get; set; }
```

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//スタンプは 1 ページ目、4 ページ目、6 ページ目にのみ適用します。
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 関連項目

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


