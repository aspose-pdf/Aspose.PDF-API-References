---
title: Class PdfXmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfXmlSaveOptions クラス。PdfXml 形式の保存オプション
type: docs
weight: 8470
url: /ja/net/aspose.pdf/pdfxmlsaveoptions/
---
## PdfXmlSaveOptions クラス

PdfXml 形式の保存オプション。

```csharp
public class PdfXmlSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfXmlSaveOptions](pdfxmlsaveoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントのグリフが aps ページを準備する際にキャッシュされるかどうかを示すブール値を取得または設定します。PDFから他の形式への変換のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙項目を返します。Continue はデフォルトのアクションで、保存操作は続行されますが、ユーザーは Abort を返すこともでき、その場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 複数のスレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 時々、PDF には、隣接する同じタイル背景画像から構成された背景画像（ページまたはテーブルセルの）を含むことがあります。この場合、ターゲット形式のレンダラー（例：DOCS形式のMsWord）は、背景画像の部分間に目に見える境界を生成することがあります。これは、画像のエッジスムージング（アンチエイリアス）の技術が Acrobat Reader とは異なるためです。エクスポートされたドキュメントに同じ背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用してその不要な効果を取り除くことをお勧めします。注意！この品質の最適化は通常、変換を大幅に遅くするため、本当に必要な場合にのみこのオプションを使用してください。 |

### 参照

* クラス [UnifiedSaveOptions](../unifiedsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)