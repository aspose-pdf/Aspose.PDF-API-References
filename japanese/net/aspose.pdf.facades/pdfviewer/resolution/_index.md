---
title: "PdfViewer.Resolution"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfViewer プロパティ。表示および印刷時の解像度を取得/設定します。解像度が高いほど速度が遅くなります。デフォルト値は 150 です。"
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

表示および印刷時の解像度を取得または設定します。解像度が高いほど速度が遅くなります。既定値は 150 です。

```csharp
public int Resolution { get; set; }
```

## 備考

このプロパティは、ページから画像への変換フローにおける画像解像度を変更します。[`PrintAsImage`](../printasimage/) が `true` に設定されている場合、または [`DecodePage`](../decodepage/) や [`DecodeAllPages`](../decodeallpages/) メソッドが呼び出された場合に適用されます。プリンターへの直接印刷用にプリンター解像度を設定するには、[`PageSettings`](../../../aspose.pdf.printing/pagesettings/) クラスの [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) プロパティを使用してください。

### 関連項目

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


