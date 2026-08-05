---
title: "PageNumberStamp"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ページ番号スタンプを表し、ページに番号付けするために使用されます。"
type: docs
weight: 1140
url: /ja/python-net/aspose.pdf/pagenumberstamp/
---

## PageNumberStamp class

ページ番号スタンプを表し、ページに番号付けするために使用されます。

PageNumberStamp 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PageNumberStamp(format) | PageNumberStamp クラスの新しいインスタンスを初期化します |
| PageNumberStamp() | [PageNumberStamp](/pdf/python-net/aspose.pdf/pagenumberstamp/) クラスの新しいインスタンスを初期化します。Format は "#" に設定されます。 |
| PageNumberStamp(formatted_text) | PageNumberStamp クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| background | コンテンツが背景としてスタンプされていることを示す bool 値を設定または取得します。<br/>            値が true の場合、スタンプ コンテンツは下部に配置されます。<br/>            デフォルトでは、値は false で、スタンプ コンテンツは上部に配置されます。 |
| opacity | スタンプの不透明度を示す値を取得または設定します。値は 0.0 から 1.0 です。<br/>            デフォルトでは、値は 1.0 です。 |
| outline_opacity | スタンプのアウトライン不透明度を示す値を取得または設定します。値は 0.0 から 1.0 です。<br/>            デフォルトでは、値は 1.0 です。 |
| outline_width | スタンプのアウトライン幅の値を取得または設定します。<br/>            デフォルトでは、値は 1.0 です。 |
| rotate | スタンプ コンテンツの回転を [Rotation](/pdf/python-net/aspose.pdf/rotation/) の値に従って設定または取得します。<br/>            注: このプロパティは 90 度の倍数 (0, 90, 180, 270 度) の角度を設定するためのものです。<br/>            任意の角度を設定するには RotateAngle プロパティを使用します。 <br/>            ArbitraryAngle で設定された角度が 90 の倍数でない場合、Rotate プロパティは Rotation.None を返します。 |
| x_indent | 左端から開始する水平スタンプ座標です。 |
| y_indent | 下端から開始する垂直スタンプ座標です。 |
| horizontal_alignment | ページ上のスタンプの水平配置を取得または設定します。 |
| vertical_alignment | ページ上のスタンプの垂直配置を取得または設定します。 |
| left_margin | スタンプの左余白を取得または設定します。 |
| right_margin | スタンプの右余白を取得または設定します。 |
| bottom_margin | スタンプの下余白を取得または設定します。 |
| top_margin | スタンプの上余白を取得または設定します。 |
| zoom_x | スタンプの水平ズーム係数です。スタンプを水平に拡大縮小できます。 |
| width | ページ上のスタンプの希望幅です。 |
| height | ページ上のスタンプの希望高さです。 |
| zoom_y | スタンプの垂直ズーム係数です。スタンプを垂直に拡大縮小できます。 |
| zoom | スタンプのズーム係数です。スタンプを拡大縮小できます。<br/>            ZoomX と ZoomY プロパティのペアは、各軸ごとにズーム係数を個別に設定できることに注意してください。 <br/>            このプロパティを設定すると、ZoomX と ZoomY の両方のプロパティが変更されます。 <br/>            ZoomX と ZoomY が異なる場合、Zoom プロパティは ZoomX の値を返します。 |
| rotate_angle | スタンプの回転角度（度単位）を取得または設定します。<br/>            このプロパティでは任意の回転角度を設定できます。 |
| draw | このプロパティはページ上でスタンプがどのように描画されるかを決定します。Draw = true の場合、スタンプはグラフィック演算子として描画され、draw = false の場合、スタンプはテキストとして描画されます。 |
| treat_y_indent_as_base_line | テキスト配置の座標原点を定義します。<br/>            TreatYIndentAsBaseLine = true の場合（Draw = true のデフォルト）、YIndent の値はテキストのベースラインとして扱われます。<br/>            TreatYIndentAsBaseLine = false の場合（Draw = false のデフォルト）、YIndent の値はテキストの底部（ディセントライン）として扱われます。 |
| word_wrap | 単語の折り返しを定義します。このプロパティが true に設定され、Width の値が指定されている場合、テキストは指定された幅に合わせて複数行に分割されます。デフォルト値: false。 |
| justify | テキストの両端揃えを定義します。このプロパティが true に設定されると、テキストの左端と右端が揃えられます。デフォルト値: false。 |
| scale | テキストのスケーリングを定義します。このプロパティが true に設定され、Width 値が指定されている場合、テキストは指定された幅に合わせてスケーリングされます。 |
| value | ページ上のスタンプとして使用される文字列値を取得または設定します。 |
| text_state | スタンプのテキストプロパティを取得します。詳細は [text_state](/pdf/python-net/aspose.pdf/textstamp/) を参照してください。 |
| text_alignment | スタンプ内のテキストの配置。 |
| max_row_width | WordWrap オプションの最大行高さ。 |
| format | ページ番号をスタンプするための文字列値。<br/>            値には文字 '#' を含める必要があり、スタンプ処理中にページ番号に置き換えられます。 |
| starting_number | 開始ページ番号の値を取得または設定します。この値から他のページが番号付けされます。 |
| numbering_style | このスタンプで使用される番号付けスタイル。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| put(page) | ページ番号を追加します。 |
| set_stamp_id(value) | スタンプ ID を設定します。 |
| get_stamp_id() | スタンプ ID を返します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

