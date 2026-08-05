---
title: "PDF3DAnnotation"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "クラス PDF3DAnnotation。 このクラスは継承できません。"
type: docs
weight: 510
url: /ja/python-net/aspose.pdf.annotations/pdf3dannotation/
---

## PDF3DAnnotation class

クラス PDF3DAnnotation。 このクラスは継承できません。

PDF3DAnnotation 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PDF3DAnnotation(page, rect, pdf_3d_artwork) | PDF3DAnnotation クラスの新しいインスタンスを初期化します |
| PDF3DAnnotation(page, rect, pdf_3d_artwork, activation) | PDF3DAnnotation クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| vertical_alignment | 段落の垂直方向の配置を取得または設定します |
| horizontal_alignment | 注釈のテキスト配置を取得または設定します。 |
| margin | 段落の外側余白を取得または設定します（PDF 生成用） |
| is_first_paragraph_in_column | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_kept_with_next | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_in_new_page | この段落が新しいページで生成されるように強制するかどうかを示す bool 値を取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| is_in_line_paragraph | 段落がインラインかどうかを取得または設定します。<br/>            デフォルトは false です。（PDF 生成用） |
| hyperlink | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| z_index | グラフの Z 順序を示す int 値を取得または設定します。ZIndex が大きいグラフは<br/>            ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフは<br/>            ページ内のテキストの背後に配置されます。 |
| update_appearance_on_convert | true の場合、PF ドキュメントを画像に変換する前に注釈の外観が更新されます。これによりフィールドが正しく変換されますが、時間がかかる可能性があります。 |
| use_font_subset | このプロパティが true に設定されている場合、フォントはサブセットとしてドキュメントに追加されます。デフォルト値は true です。 |
| flags | 注釈のフラグ。 |
| annotation_type | 注釈のタイプを取得します。 |
| width | 注釈の幅を取得または設定します。 |
| actions | 注釈アクションのリストを取得します。 |
| height | 注釈の高さを取得または設定します。 |
| rect | 注釈矩形を取得または設定します。 |
| contents | 注釈のテキストを取得または設定します。 |
| name | ページ上の注釈名を取得または設定します。 |
| modified | 注釈が最近変更された日時を取得または設定します。 |
| color | 注釈の色を取得または設定します。 |
| border | 注釈の境界特性を取得または設定します。 [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| active_state | 現在の注釈外観状態を取得または設定します。 |
| characteristics | 注釈の特性を取得します。 |
| states | 注釈の外観ディクショナリを取得します。 |
| alignment | 注釈の配置。 このプロパティは廃止予定です。代わりに HorizontalAligment を使用してください。 |
| text_horizontal_alignment | 注釈のテキスト配置を取得または設定します。 |
| full_name | 注釈の完全修飾名を取得します。 |
| appearance | 注釈の外観ディクショナリを取得します。 |
| page_index | 注釈が含まれるページのインデックスを取得します。 |
| pdf_3d_artwork | 3D アートワークを取得します |
| lighting_scheme | 照明スキームを取得します |
| content | コンテンツを取得または設定します。 |
| render_mode | レンダーモードを取得します。 |
| view_array | ビュー配列を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| set_image_preview(filename) | 画像プレビューを設定します。 |
| set_image_preview(image) | 画像プレビューを設定します。 |
| clone() | このインスタンスをクローンします。<br/>            仮想メソッドです。常に null を返します。 |
| get_rectangle(consider_rotation) | ページの回転を考慮した注釈の矩形を返します。 |
| accept(visitor) | 注釈処理のためにビジターを受け入れます。 |
| flatten() | 注釈内容をページに直接配置します、<br/>            注釈オブジェクトは削除されます。 |
| change_after_resize(transform) | 行列変換に従ってパラメータと外観を更新します。 |
| set_default_view_index(index) | デフォルトビューのインデックスを設定します。 |
| clear_image_preview() | 画像プレビューをクリアします。 |
| get_image_preview() | 画像プレビューを取得します。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

