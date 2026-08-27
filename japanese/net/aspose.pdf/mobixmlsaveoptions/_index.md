---
title: "クラス MobiXmlSaveOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.MobiXmlSaveOptions クラス。Xml 形式へのエクスポート用の保存オプションです。"
type: docs
weight: 7120
url: /ja/net/aspose.pdf/mobixmlsaveoptions/
---
## MobiXmlSaveOptions class

Xml 形式へのエクスポート用の保存オプション。

```csharp
public class MobiXmlSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MobiXmlSaveOptions](mobixmlsaveoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを使用して PDF Document から画像またはテキストを抽出する機能を有効にします。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 数スレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | PDF には、ページや表セルの背景画像が、同じタイル背景画像を複数組み合わせて隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされた文書に同じ背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、実際に必要なときにのみこのオプションを使用してください。 |

### 関連項目

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


