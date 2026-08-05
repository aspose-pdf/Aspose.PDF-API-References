---
title: "PdfPageStamp"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ページをスタンプとして使用するスタンプを表すクラスです。"
type: docs
weight: 1230
url: /ja/python-net/aspose.pdf/pdfpagestamp/
---

## PdfPageStamp class

PDF ページをスタンプとして使用するスタンプを表すクラスです。

PdfPageStamp 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfPageStamp(pdf_page) | PdfPageStamp クラスの新しいインスタンスを初期化します |
| PdfPageStamp(file_name, page_index) | PdfPageStamp クラスの新しいインスタンスを初期化します |
| PdfPageStamp(stream, page_index) | PdfPageStamp クラスの新しいインスタンスを初期化します |
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
| pdf_page | スタンプとして使用されるページを取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| put(page) | 指定されたページにスタンプを配置します。 |
| set_stamp_id(value) | スタンプ ID を設定します。 |
| get_stamp_id() | スタンプ ID を返します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

