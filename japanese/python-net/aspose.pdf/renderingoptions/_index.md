---
title: "RenderingOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "レンダリングオプションを表します。"
type: docs
weight: 1330
url: /ja/python-net/aspose.pdf/renderingoptions/
---

## RenderingOptions class

レンダリングオプションを表します。

RenderingOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| RenderingOptions() | RenderingOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| barcode_optimization | バーコード最適化モードを取得または設定します。 |
| optimize_dimensions | サイズ最適化モードを取得または設定します。 |
| system_fonts_native_rendering | システムフォントがネイティブにレンダリングされるモードを取得または設定します。 |
| use_new_imaging_engine | 新しいイメージングエンジンが使用されるかどうかを決定するフラグを取得または設定します。 |
| width_extra_units | AppendRectangle 演算子の矩形の幅を増減させるために使用される値を取得または設定します。 |
| height_extra_units | AppendRectangle 演算子の矩形の幅を増減させるために使用される値を取得または設定します。 |
| convert_fonts_to_unicode_ttf | すべてのフォントが TTF Unicode バージョンに変換されることを示します。これは互換性 <br/>             の理由やフォント使用量の最適化に役立ちます。新しい TTF フォントは元のフォントのすべてのシンボルを持つのではなく、<br/>             テキストで使用されるシンボルのみを持ちます。 |
| use_font_hinting | このフラグを使用するとフォントヒンティング機構が有効になります。フォントヒンティングとは、アウトラインフォントの表示を調整するための数学的指示を使用することです。<br/>            このフラグをオンにすることで、テキストの可読性に関する問題が解決する場合があります。<br/>            現時点では、このフラグの使用は TTF フォントに対してのみ効果があり、これらのフォントがソース文書で使用されている場合に限られます。 |
| scale_images_to_fit_page_width | ページ上のすべての画像をページ幅に合わせてスケーリングするために使用される値を取得または設定します。 |
| interpolation_high_quality | 補間の高品質モードを取得または設定します。 |
| max_fonts_cache_size | フォントキャッシュ内のフォントの最大数です。デフォルト値は 10 です。 |
| max_symbols_cache_size | シンボルキャッシュ内のシンボルの最大数です。デフォルト値は 100 です。 |
| default_font_name | 欠落しているフォントの代替として使用されるフォントのデフォルト名を取得/設定します。 |
| ignore_resource_font_errors | フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。<br/>            true - フォントが存在しないエラーを無視することを意味します。処理中に不正なリソースを参照するテキストセグメントはスキップされます。<br/>            デフォルトは false |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

