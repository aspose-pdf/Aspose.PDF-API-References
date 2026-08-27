---
title: "PdfFileStamp.AddStamp"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileStamp メソッド。ファイルにスタンプを追加します"
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

ファイルにスタンプを追加します。

```csharp
public void AddStamp(Stamp stamp)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| スタンプ | スタンプ | スタンプ オブジェクト。 |

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

### 関連項目

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


