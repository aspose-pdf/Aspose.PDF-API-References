---
title: "HtmlLoadOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "HTML ファイルを PDF ドキュメントに読み込み/インポートするためのオプションを表します。"
type: docs
weight: 480
url: /ja/python-net/aspose.pdf/htmlloadoptions/
---

## HtmlLoadOptions class

HTML ファイルを PDF ドキュメントに読み込み/インポートするためのオプションを表します。

HtmlLoadOptions 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| HtmlLoadOptions() | 空のベースパスで HTML を PDF ドキュメントに変換するためのロードオプションを作成します。 |
| HtmlLoadOptions(base_path) | HtmlLoadOptions クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバック。<br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。<br/>            Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。 |
| load_format | ファイル形式を表します。この形式は[LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)で記述されています。 |
| is_render_to_single_page | ドキュメント全体を単一ページにレンダリングするかどうかを取得または設定します。 |
| is_embed_fonts | 結果ドキュメントへのフォント埋め込みを取得または設定します。 |
| page_layout_option | レイアウトオプションを取得または設定します。 |
| html_media_type | レンダリング中に使用される可能なメディアタイプを取得または設定します。 |
| input_encoding | 解析時にこのドキュメントで使用されるエンコーディングを指定する属性を取得または設定します。この属性が null の場合、エンコーディングはドキュメントの文字セット属性から決定されます。 |
| base_path | HTML ファイルのベースパス/URL。 |
| page_info | ドキュメントのページ情報を取得または設定します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

