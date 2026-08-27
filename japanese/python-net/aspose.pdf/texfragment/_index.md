---
title: "TeXFragment"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "TeX フラグメントを表します。"
type: docs
weight: 1510
url: /ja/python-net/aspose.pdf/texfragment/
---

## TeXFragment class

TeX フラグメントを表します。

TeXFragment 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| TeXFragment(text) | TeXFragment クラスの新しいインスタンスを初期化します |
| TeXFragment(text, remove_indents) | TeXFragment クラスの新しいインスタンスを初期化します |
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
| te_x_load_options_of_instance | このクラスのインスタンスに LaTeX をロード（およびレンダリング）するために使用される TeXLoadOptions を取得または設定します。<br/>            特定のインスタンスに対して LaTeX のインポート設定を個別に使用する必要がある場合に使用してください<br/>            （例：このインスタンスまたは別のインスタンスがインポートされた LaTeX 用に特定の BasePath を使用する、または外部リソースのローダーを指定する必要がある場合）<br/>            パラメータがデフォルト（null）の場合、標準の LaTeX ロードオプションが使用されます。 |
| latex_load_options_of_instance | このクラスのインスタンスに LaTeX をロード（およびレンダリング）するために使用される TeXLoadOptions を取得または設定します。<br/>            特定のインスタンスに対して LaTeX のインポート設定を個別に使用する必要がある場合に使用してください<br/>            （例：このインスタンスまたは別のインスタンスがインポートされた LaTeX 用に特定の BasePath を使用する、または外部リソースのローダーを指定する必要がある場合）<br/>            パラメータがデフォルト（null）の場合、標準の LaTeX ロードオプションが使用されます。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | フラグメントをクローンします。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

