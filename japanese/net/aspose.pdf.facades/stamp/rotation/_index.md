---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: スタンププロパティ。スタンプの回転を度単位で取得または設定します
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation プロパティ

スタンプの回転を度単位で取得または設定します。

```csharp
public float Rotation { get; set; }
```

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 関連項目

* クラス [Stamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)