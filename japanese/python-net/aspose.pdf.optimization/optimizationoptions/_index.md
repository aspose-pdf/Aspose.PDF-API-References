---
title: "OptimizationOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ドキュメント最適化アルゴリズムを記述するクラスです。<br/>            このクラスのインスタンスは OptimizeResources() メソッドのパラメータとして使用できます。"
type: docs
weight: 20
url: /ja/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

ドキュメント最適化アルゴリズムを記述するクラスです。<br/>            このクラスのインスタンスは OptimizeResources() メソッドのパラメータとして使用できます。

OptimizationOptions 型は以下のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| OptimizationOptions() | OptimizationOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| link_duplcate_streams | このフラグが true に設定されている場合、リソースストリームが解析されます。重複するストリームが見つかった場合（つまり、ストリームの内容が同じ場合）、それらのストリームは 1 つのオブジェクトとして保存されます。<br/>            これにより、特定の場合（例として、同じドキュメントが複数回連結された場合）にドキュメントサイズを削減できます。 |
| allow_reuse_page_content | true の場合、ページが同一であるときにドキュメントが最適化されると、ページ内容が再利用されます。 |
| remove_unused_streams | このフラグが true に設定されている場合、すべてのリソースが使用状況についてチェックされます。リソースが使用されていない場合、リソースは削除されます。<br/>            例えば、ページがドキュメントから抽出された場合など、ドキュメントサイズが減少することがあります。 |
| remove_unused_objects | このフラグが true に設定されている場合、すべてのドキュメントオブジェクトがチェックされ、未使用のオブジェクト（つまり、参照が存在しないオブジェクト）はドキュメントから削除されます。 |
| image_compression_options | ドキュメント内の画像が圧縮されるかどうか、および圧縮のパラメータを記述するオプションのセットです。 |
| compress_images | このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定されます。 |
| resize_images | このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメータより大きいときに画像がリサイズされます。 |
| image_quality | CompressIamges フラグが使用される際の画像圧縮レベルを指定します。 |
| max_resoultion | 画像の最大解像度を指定します。画像の解像度がこれより高い場合は縮小されます。 |
| unembed_fonts | true に設定すると、フォントを埋め込まないようにします。 |
| subset_fonts | true に設定すると、フォントはサブセットに変換されます。 |
| remove_private_info | プライベート情報（ページピース情報）を削除します。 |
| image_encoding | 使用される画像エンコードです。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| all() | すべてのオプションが有効化された最適化戦略を作成します。<br/>            有効化されるのは、ドキュメントの機能に影響を与えないオプションのみであることに注意してください。<br/>            つまり、画像圧縮やフォントの埋め込み解除は有効にならず（手動で埋め込むことは可能です）。 |

### 関連項目

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

