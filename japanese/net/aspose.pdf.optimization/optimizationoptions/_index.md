---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.OptimizationOptions クラス。ドキュメント最適化アルゴリズムを説明するクラス。このクラスのインスタンスは OptimizeResources メソッドのパラメーターとして使用できます。
type: docs
weight: 7980
url: /ja/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions クラス

ドキュメント最適化アルゴリズムを説明するクラス。このクラスのインスタンスは OptimizeResources() メソッドのパラメーターとして使用できます。

```csharp
public class OptimizationOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | デフォルトコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | true の場合、ドキュメントが等しいページのために最適化されるときにページコンテンツが再利用されます。 |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | このフラグが `true` に設定されている場合、Pdf オブジェクトはオブジェクトストリームにパックされ、PDF ファイルサイズを削減するために圧縮されます。 |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | ドキュメント内の画像が圧縮されるかどうかと圧縮のパラメーターを説明するオプションのセット。 |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | 使用される画像エンコーダ。 |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | このフラグが true に設定されている場合、リソースストリームが分析されます。重複ストリームが見つかった場合（すなわち、ストリームの内容が等しい場合）、これらのストリームは1つのオブジェクトとして保存されます。これにより、同じドキュメントが複数回連結された場合などに、ドキュメントサイズを減少させることができます。 |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | スキャンのレベル。より深いスキャン（値が高い）は時間がかかりますが、より小さい結果ファイルを生成する可能性があります。デフォルト値: 10。 |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | 画像の最大解像度を指定します。画像の解像度が高い場合はスケーリングされます。 |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | プライベート情報（ページの部分情報）を削除します。 |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | このフラグが true に設定されている場合、すべてのドキュメントオブジェクトがチェックされ、未使用のオブジェクト（すなわち、参照がないオブジェクト）がドキュメントから削除されます。 |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | このフラグが true に設定されている場合、すべてのリソースがその使用状況についてチェックされます。リソースが使用されていない場合、そのリソースは削除されます。これにより、ページがドキュメントから抽出された場合などに、ドキュメントサイズが減少する可能性があります。 |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | true に設定されている場合、フォントはサブセットに変換されます。 |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | true に設定されている場合、フォントは埋め込まれないようにします。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | すべてのオプションが有効化された最適化戦略を作成します。ドキュメントの機能を変更しないオプションのみが有効化されることに注意してください。すなわち、画像の圧縮とフォントの埋め込み解除は有効にならず（手動で埋め込むことができます）。 |

### 参照

* 名前空間 [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* アセンブリ [Aspose.PDF](../../)