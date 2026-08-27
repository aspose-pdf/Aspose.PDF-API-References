---
title: "Stamp.IsBackground"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Stamp プロパティ。背景ステータスを取得または設定します。true の場合、スタンプは対象ページの背景として配置されます。デフォルトは false に設定されています。"
type: docs
weight: 30
url: /ja/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

背景ステータスを取得または設定します。true の場合、スタンプはページの背景として配置されます。デフォルトは false に設定されています。

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

### 関連項目

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


