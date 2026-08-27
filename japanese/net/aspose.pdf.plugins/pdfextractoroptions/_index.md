---
title: "クラス PdfExtractorOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.PdfExtractorOptions クラス。TextExtractor と ImageExtractor プラグインのオプションを表します。"
type: docs
weight: 9220
url: /ja/net/aspose.pdf.plugins/pdfextractoroptions/
---
## PdfExtractorOptions class

TextExtractor と ImageExtractor プラグインのオプションを表します。

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | PdfExtractor プラグインのデータコレクションを返します。 |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | 操作名を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | PdfExtractor プラグインのデータコレクションに新しいデータソースを追加します。 |

## 備考

`PdfExtractorOptions` には、入力 PDF ドキュメントを表すデータ（ファイル、ストリーム）を追加する基本機能が含まれています。代わりに [`TextExtractorOptions`](../textextractoroptions/) または ImageExtractorOptions を作成してください。

### 関連項目

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


