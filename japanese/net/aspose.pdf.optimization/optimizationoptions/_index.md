---
title: "クラス OptimizationOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Optimization.OptimizationOptions クラス。ドキュメント最適化アルゴリズムを記述するクラスです。このクラスのインスタンスは OptimizeResources メソッドのパラメータとして使用できます。"
type: docs
weight: 8120
url: /ja/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

クラスはdocument 最適化アルゴリズムを記述します。このクラスのインスタンスは OptimizeResources() メソッドのパラメータとして使用できます。

```csharp
public class OptimizationOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | true の場合、同一ページに対してドキュメントが最適化される際にページ内容が再利用されます。 |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | このフラグが `true` に設定されていると、Pdf オブジェクトは Objest Streams にパックされ、圧縮されて PDF ファイルサイズが削減されます。 |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | ドキュメント内の画像が圧縮されるかどうかと圧縮パラメータを記述するオプションのセットです。 |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | 使用される画像エンコードです。 |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | このフラグが true に設定されていると、リソースストリームが解析されます。重複するストリームが見つかった場合（例：ストリーム内容が同じ場合）、それらのストリームは1つのオブジェクトとして保存されます。これにより、同じドキュメントが複数回連結された場合など、いくつかのケースでドキュメントサイズを減少させることができます。 |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | 画像の最大解像度を指定します。画像の解像度がこれより高い場合は縮小されます。 |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | プライベート情報（ページピース情報）を削除します。 |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | このフラグが true に設定されていると、すべてのドキュメントオブジェクトがチェックされ、未使用のオブジェクト（参照がないオブジェクトなど）はドキュメントから削除されます。 |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | このフラグが true に設定されていると、すべてのリソースが使用状況でチェックされます。リソースが使用されていない場合、そのリソースは削除されます。これにより、ドキュメントからページが抽出された場合など、ドキュメントサイズが減少することがあります。 |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | true に設定すると、フォントはサブセットに変換されます。 |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | true に設定すると、フォントを埋め込まないようにします。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | すべてのオプションが有効化された最適化戦略を作成します。なお、ドキュメントの機能を変更しないオプションのみが有効化されます。つまり、画像圧縮やフォントの埋め込み解除は有効にならず（手動で有効化できます）。 |

### 関連項目

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


