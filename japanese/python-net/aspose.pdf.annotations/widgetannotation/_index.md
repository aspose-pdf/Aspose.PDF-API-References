---
title: "WidgetAnnotation"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ウィジェットアノテーションを表すクラスです。"
type: docs
weight: 870
url: /ja/python-net/aspose.pdf.annotations/widgetannotation/
---

## WidgetAnnotation class

ウィジェットアノテーションを表すクラスです。

WidgetAnnotation 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| WidgetAnnotation(doc) | WidgetAnnotation クラスの新しいインスタンスを初期化します |
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
| actions | 注釈のアクションを取得します。 |
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
| on_activated | 注釈がアクティブ化されたときに実行されるアクションです。 |
| highlighting | 注釈のハイライトモード。 |
| parent | 注釈の親を取得します。 |
| default_appearance | フィールドのデフォルト外観を取得または設定します。 |
| read_only | フィールドの読み取り専用ステータスを取得または設定します。 |
| 必須 | フィールドの必須ステータスを取得または設定します。 |
| エクスポート可能 | フィールドのエクスポート可能フラグを取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | このインスタンスをクローンします。<br/>            仮想メソッドです。常に null を返します。 |
| get_rectangle(consider_rotation) | ページの回転を考慮した注釈の矩形を返します。 |
| accept(visitor) | ビジターを受け入れます。 |
| flatten() | 注釈内容をページに直接配置します、<br/>            注釈オブジェクトは削除されます。 |
| change_after_resize(transform) | 行列変換に従ってパラメータと外観を更新します。 |

### 関連項目

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

