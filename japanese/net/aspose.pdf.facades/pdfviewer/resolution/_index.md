---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer プロパティ。表示および印刷中の解像度を取得または設定します。解像度が高いほど、速度は遅くなります。デフォルト値は 150 です。
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution プロパティ

表示および印刷中の解像度を取得または設定します。解像度が高いほど、速度は遅くなります。デフォルト値は 150 です。

```csharp
public int Resolution { get; set; }
```

## 備考

このプロパティは、ページから画像への変換フローにおける画像解像度を変更します：[`PrintAsImage`](../printasimage/) が `true` に設定されている場合、または [`DecodePage`](../decodepage/) または [`DecodeAllPages`](../decodeallpages/) メソッドが呼び出される場合です。プリンタに直接印刷するためのプリンタ解像度を設定するには、[`PageSettings`](../../../aspose.pdf.printing/pagesettings/) クラスの [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) プロパティを使用します。

### 関連項目

* クラス [PdfViewer](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)