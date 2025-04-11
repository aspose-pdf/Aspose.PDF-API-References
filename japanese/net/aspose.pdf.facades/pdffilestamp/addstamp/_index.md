---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp メソッド。ファイルにスタンプを追加します
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp メソッド

ファイルにスタンプを追加します。

```csharp
public void AddStamp(Stamp stamp)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stamp | Stamp | スタンプオブジェクト。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 参照

* クラス [Stamp](../../stamp/)
* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)