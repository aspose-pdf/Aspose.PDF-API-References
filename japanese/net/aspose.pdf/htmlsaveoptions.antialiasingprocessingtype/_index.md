---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType enum。この列挙型は、変換中の可能なアンチエイリアス処理を説明します
type: docs
weight: 5570
url: /ja/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType 列挙型

この列挙型は、変換中の可能なアンチエイリアス処理を説明します

```csharp
public enum AntialiasingProcessingType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | 特別なアンチエイリアス処理は使用されません。これは、圧倒的多数の文書にとって最適なオプションであり、変換中に追加の時間を必要としません |
| TryCorrectResultHtml | `1` | この場合、コンバータは隣接する背景グラフィック要素のある場所を検出し、関連する方法で結果のHTMLを修正しようとします。このオプションは、いくつかの隣接するグラフィック要素から構成される背景を含む文書のエクスポート結果を向上させることができます（この種の文書では、PDFレンダラー、例えばAcrobat Readerは、レンダリング中に要素の境界を滑らかにしようとします。このオプションでは、コンバータがPDFレンダラーのその動作を模倣します。このオプションは、特定の文書（そのような複合背景を使用する）に対するエクスポート結果のレイアウトを向上させることができますが、処理には追加の時間が必要です（通常、追加の時間は約10-15%です）。したがって、一般的な場合にこのモードの使用は推奨されません。 |

### 参照

* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)