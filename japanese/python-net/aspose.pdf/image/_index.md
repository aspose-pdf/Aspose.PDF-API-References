---
title: "画像"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "画像を表します。"
type: docs
weight: 650
url: /ja/python-net/aspose.pdf/image/
---

## Image class

画像を表します。

Image 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Image() | Image クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| vertical_alignment | 段落の垂直方向の配置を取得または設定します |
| horizontal_alignment | 段落の水平方向の配置を取得または設定します |
| margin | 段落の外側余白を取得または設定します（PDF 生成用） |
| is_first_paragraph_in_column | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_kept_with_next | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_in_new_page | この段落が新しいページで生成されるように強制するかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_in_line_paragraph | 段落がインラインかどうかを取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| hyperlink | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| z_index | グラフの Z 順序を示す int 値を取得または設定します。ZIndex が大きいグラフは<br/>            ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフは<br/>            ページ内のテキストの背後に配置されます。 |
| file | 画像ファイルを取得または設定します。 |
| fix_width | 画像の幅を取得または設定します。 |
| fix_height | 画像の高さを取得または設定します。 |
| file_type | 画像ファイルのタイプを取得または設定します。 |
| image_scale | 画像のスケールを取得または設定します。 |
| image_stream | 画像ストリームを取得または設定します。 |
| is_apply_resolution | 生成時に画像が解像度を使用するかどうかを示すブール値を取得または設定します |
| is_black_white | 画像が白黒に強制されるかどうかを示すブール値を取得または設定します。TIFF <br/>            CCITT サブフォーマットの画像が使用される場合、このプロパティは true に設定する必要があります。 |
| タイトル | 画像のタイトルを示す文字列値を取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | 画像をクローンします。 |
| get_mime_type(i) | 画像の MIME タイプを返します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

