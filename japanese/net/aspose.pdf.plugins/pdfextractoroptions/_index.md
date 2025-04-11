---
title: Class PdfExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractorOptions クラス。TextExtractor および ImageExtractor プラグインのオプションを表します
type: docs
weight: 9070
url: /ja/net/aspose.pdf.plugins/pdfextractoroptions/
---
## PdfExtractorOptions クラス

TextExtractor および ImageExtractor プラグインのオプションを表します。

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | PdfExtractor プラグインデータコレクションを返します。 |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | 操作名を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | PdfExtractor プラグインデータコレクションに新しいデータソースを追加します。 |

## 備考

`PdfExtractorOptions` は、入力 PDF ドキュメントを表すデータ（ファイル、ストリーム）を追加するための基本機能を含んでいます。この代わりに [`TextExtractorOptions`](../textextractoroptions/) または ImageExtractorOptions を作成してください。

### 参照

* インターフェース [IPluginOptions](../ipluginoptions/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)