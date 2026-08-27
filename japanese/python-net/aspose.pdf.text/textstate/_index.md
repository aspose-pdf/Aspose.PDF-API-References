---
title: "TextState"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "テキストの状態を表します"
type: docs
weight: 490
url: /ja/python-net/aspose.pdf.text/textstate/
---

## TextState class

テキストの状態を表します

TextState 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| TextState() | テキスト状態オブジェクトを作成します。 |
| TextState(font_size) | TextState クラスの新しいインスタンスを初期化します |
| TextState(foreground_color) | TextState クラスの新しいインスタンスを初期化します |
| TextState(foreground_color, font_size) | TextState クラスの新しいインスタンスを初期化します |
| TextState(font_family) | TextState クラスの新しいインスタンスを初期化します |
| TextState(font_family, bold, italic) | TextState クラスの新しいインスタンスを初期化します |
| TextState(font_family, font_size) | TextState クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| character_spacing | テキストの文字間隔を取得または設定します。 |
| line_spacing | テキストの行間隔を取得または設定します。 |
| horizontal_scaling | テキストの横方向スケーリングを取得または設定します。 |
| subscript | テキストの下付き文字を取得または設定します。 |
| superscript | テキストの上付き文字を取得または設定します。 |
| word_spacing | テキストの単語間隔を取得または設定します。 |
| invisible | テキストの不可視性を取得または設定します。これは基本的に [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/) の状態を反映しますが、特定のケース（クリッピングなど）を除きます。 |
| rendering_mode | テキストのレンダリングモードを取得または設定します。 |
| font_size | テキストのフォントサイズを取得または設定します。 |
| font | テキストのフォントを取得または設定します。 |
| foreground_color | テキストの前景色を取得または設定します。 |
| stroking_color | テキストの前景色を取得または設定します。 |
| underline | テキストの下線を取得または設定します。これは [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) オブジェクトで表されます。 |
| strike_out | テキストの取り消し線を設定します。これは [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) オブジェクトで表されます。 |
| background_color | テキストの背景色を設定します。 |
| font_style | テキストのフォントスタイルを設定します。 |
| horizontal_alignment | テキストの水平揃えを取得または設定します。 |
| TAB_TAG | テキスト内にこのタグを配置してタブ設定を宣言できます。 |
| TABSTOP_DEFAULT_VALUE | デフォルトフォントのスペース文字幅におけるタブ設定のデフォルト値です。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| apply_changes_from(text_state) | 別の textState から設定を適用します。 |
| measure_string(str) | 文字列を測定します。 |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

