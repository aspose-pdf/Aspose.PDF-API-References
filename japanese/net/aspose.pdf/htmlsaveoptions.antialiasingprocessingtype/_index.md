---
title: "列挙型 HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType 列挙型。変換中の可能なアンチエイリアス処理を示します。"
type: docs
weight: 5700
url: /ja/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

この列挙型は、変換中の可能なアンチエイリアス処理を示します。

```csharp
public enum AntialiasingProcessingType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | 特別なアンチエイリアス処理は使用されていません。これは大多数の文書に最適なオプションであり、変換時に追加の時間を要しません。 |
| TryCorrectResultHtml | `1` | この場合、コンバータは隣接する背景グラフィック要素がある場所を検出し、結果の HTML を適切に修正しようとします。このオプションは、複数の隣接するグラフィック要素で構成された背景を持つ文書のエクスポート結果を向上させます（この種の文書では、PDF レンダラ（例: Acrobat Reader）は通常、レンダリング時に要素の境界を滑らかにしようとします。このオプションにより、コンバータは PDF レンダラの動作を模倣します）。このオプションは、そうした複合背景を使用する特定の文書のエクスポート結果のレイアウトを改善しますが、処理に追加の時間が必要です（通常は追加時間の約 10〜15%）。したがって、一般的なケースでこのモードを使用することは推奨されません。 |

### 関連項目

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


