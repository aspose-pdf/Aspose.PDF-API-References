---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Stamp プロパティ。バックグラウンドステータスを取得または設定します。true の場合、スタンプはスタンプされたページのバックグラウンドとして配置されます。デフォルトでは false に設定されています。
type: docs
weight: 30
url: /ja/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground プロパティ

バックグラウンドステータスを取得または設定します。true の場合、スタンプはスタンプされたページのバックグラウンドとして配置されます。デフォルトでは false に設定されています。

```csharp
public bool IsBackground { get; set; }
```

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 参照

* クラス [Stamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)