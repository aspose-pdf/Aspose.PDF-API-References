---
title: "RichMediaAnnotation"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ドキュメントにビデオ/オーディオデータを埋め込むことを可能にする RichMediaAnnotation を記述するクラスです。"
type: docs
weight: 710
url: /ja/python-net/aspose.pdf.annotations/richmediaannotation/
---

## RichMediaAnnotation class

PDF ドキュメントにビデオ/オーディオデータを埋め込むことを可能にする RichMediaAnnotation を記述するクラスです。

RichMediaAnnotation型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| RichMediaAnnotation(page, rect) | RichMediaAnnotationクラスの新しいインスタンスを初期化します |
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
| custom_player | ビデオ/オーディオデータを再生するためのカスタムFlashプレーヤーを設定または取得します。 |
| custom_flash_variables | プレーヤーに渡されるFlash変数を設定または取得します。 |
| content | リッチメディアコンテンツのデータです。 |
| type | コンテンツのタイプを取得または設定します。可能な値: Audio, Video。 |
| activate_on | アプリケーションを起動するイベント。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | このインスタンスをクローンします。<br/>            仮想メソッドです。常に null を返します。 |
| get_rectangle(consider_rotation) | ページの回転を考慮した注釈の矩形を返します。 |
| accept(visitor) | このアノテーションのビジターを受け入れます。 |
| flatten() | 注釈内容をページに直接配置します、<br/>            注釈オブジェクトは削除されます。 |
| change_after_resize(transform) | 行列変換に従ってパラメータと外観を更新します。 |
| add_custom_data(name, data) | カスタム名データを追加します（例: フラッシュスクリプトに必要な場合）。 |
| set_content(file_name, audio) | コンテンツストリームを設定します。 |
| set_poster(image_stream) | アノテーションのポスターを設定します。 |
| update() | 指定されたパラメータでデータを更新します。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

