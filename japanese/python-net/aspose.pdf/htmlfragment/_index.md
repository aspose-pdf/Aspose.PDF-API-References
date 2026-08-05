---
title: "HtmlFragment"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "HTML フラグメントを表します。"
type: docs
weight: 470
url: /ja/python-net/aspose.pdf/htmlfragment/
---

## HtmlFragment class

HTML フラグメントを表します。

HtmlFragment 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| HtmlFragment(text) | HtmlFragment クラスの新しいインスタンスを初期化します。 |
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
| rectangle | HtmlFragment の矩形を取得します。 |
| is_paragraph_has_margin | 段落がデフォルトの余白を持つかどうかを取得または設定します。余白がない場合は 0 です。 |
| is_break_words | 単語の改行を取得または設定します。 |
| text_state | フォントを取得または設定します。 |
| html_load_options | このクラスのインスタンスに HTML をロード（およびレンダリング）するために使用される HtmlLoadOptions を取得または設定します。<br/>            必要に応じて、このインスタンスまたは別のインスタンスの HTML インポートに特定の設定を使用する場合に使用してください。<br/>            （例: このインスタンスまたは別のインスタンスがインポートされた HTML の特定の BasePath を使用する必要がある場合や、外部リソースの特定のローダーを使用する必要がある場合）<br/>            パラメーターがデフォルト（null）の場合、標準の HTML ローディングオプションが使用されます。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | HTML フラグメントをクローンします。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

