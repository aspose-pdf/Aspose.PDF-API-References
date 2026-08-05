---
title: "FloatingBox"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: 
type: docs
weight: 370
url: /ja/python-net/aspose.pdf/floatingbox/
---

## FloatingBox class



FloatingBox 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| FloatingBox(width, height) | FloatingBox クラスの新しいインスタンスを初期化します |
| FloatingBox() | [FloatingBox](/pdf/python-net/aspose.pdf/floatingbox/) クラスの新しいインスタンスを初期化します。 |
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
| column_info | 列情報を取得または設定します |
| width | 浮動ボックスの幅を示す float 値を取得または設定します。 |
| height | 浮動ボックスの高さを示す float 値を取得または設定します。 |
| is_need_repeating | 段落が次のページで繰り返す必要があるかどうかを示す bool 値を取得または設定します。<br/>            デフォルト値は false です。この属性は、段落自体とその ReferenceParagraphID が参照するオブジェクトの両方が RepeatingRows に含まれている場合にのみ有効です。 |
| paragraphs | セル内のすべての段落を示す [paragraphs](/pdf/python-net/aspose.pdf/floatingbox/) コレクションを取得または設定します。 |
| border | 浮動ボックスの境界情報を示す [BorderInfo](/pdf/python-net/aspose.pdf/borderinfo/) オブジェクトを取得または設定します。 |
| background_color | 浮動ボックスの背景色を示す [Color](/pdf/python-net/aspose.pdf/color/) オブジェクトを取得または設定します。 |
| background_image | ページの背景画像を取得または設定します（ジェネレータ専用で、ドキュメントを読み取る際には設定されません）。 |
| padding | 浮動ボックスのパディングを示す [MarginInfo](/pdf/python-net/aspose.pdf/margininfo/) オブジェクトを取得または設定します。 |
| left | テーブルの左座標を取得または設定します。 |
| 上 | テーブルの上座標を取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| clone() | 新しい [FloatingBox](/pdf/python-net/aspose.pdf/floatingbox/) オブジェクトをクローンします。浮動ボックス内の段落はクローンされません。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

