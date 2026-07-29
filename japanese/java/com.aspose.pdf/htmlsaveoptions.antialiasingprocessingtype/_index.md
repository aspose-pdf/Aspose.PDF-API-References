---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "この列挙体は変換中の可能なアンチエイリアス手法を説明します"
type: docs
weight: 2000
url: /ja/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

この列挙体は変換中の可能なアンチエイリアス手法を説明します

## フィールド

| フィールド | 説明 |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | 特別なアンチエイリアス処理は使用されていません。これは大多数の文書に対して最適なオプションであり、変換時に追加の時間を必要としません。 |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | このような場合、コンバータは隣接する背景グラフィック要素がある場所を検出し、結果の HTML を適切に修正しようとします。このオプションは、複数の隣接するグラフィック要素で構成された背景を持つ文書のエクスポート結果を向上させます（この種の文書では、PDF レンダラ（例: Acrobat Reader）は通常、レンダリング時に要素の境界を滑らかにしようとします。このオプションにより、コンバータは PDF レンダラの動作を模倣します）。このオプションは、複合背景を使用する特定の文書のエクスポートレイアウトを改善しますが、処理に追加の時間が必要です（通常、追加で約 10〜15% の時間がかかります）。したがって、一般的なケースでこのモードを使用することは推奨されません。 |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

特別なアンチエイリアス処理は使用されていません。これは大多数の文書に対して最適なオプションであり、変換時に追加の時間を必要としません。

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

このような場合、コンバータは隣接する背景グラフィック要素がある場所を検出し、結果の HTML を適切に修正しようとします。このオプションは、複数の隣接するグラフィック要素で構成された背景を持つ文書のエクスポート結果を向上させます（この種の文書では、PDF レンダラ（例: Acrobat Reader）は通常、レンダリング時に要素の境界を滑らかにしようとします。このオプションにより、コンバータは PDF レンダラの動作を模倣します）。このオプションは、複合背景を使用する特定の文書のエクスポートレイアウトを改善しますが、処理に追加の時間が必要です（通常、追加で約 10〜15% の時間がかかります）。したがって、一般的なケースでこのモードを使用することは推奨されません。
