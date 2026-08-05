---
title: "Page"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF 文書のページを表すクラスです。"
type: docs
weight: 1080
url: /ja/python-net/aspose.pdf/page/
---

## Page class

PDF 文書のページを表すクラスです。

Page 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_add_paragraphs_after_last | ページの最後の段落の後に段落を追加するかどうかを取得または設定します |
| background_image | ページの背景画像を取得または設定します（ジェネレータ専用で、ドキュメントを読み取る際には設定されません）。 |
| toc_info | 目次情報を取得または設定します。 |
| ヘッダー | ページヘッダーを取得または設定します。 |
| レイヤー | レイヤーコレクションを取得または設定します。 |
| フッター | ページフッターを取得または設定します。 |
| paragraphs | 段落を取得します。 |
| page_info | ページ情報を取得または設定します（ジェネレータ専用で、ドキュメント読み取り時には設定されません）。 |
| rect | ページの矩形を取得または設定します。<br/>            取得時: 指定されている場合はページのクロップボックスが返され、指定がない場合はページのメディアボックスが返されます。<br/>            設定時: 常にページのメディアボックスが設定されます。<br/>            このプロパティはページの回転を考慮しません。回転を考慮したページ矩形を取得するには ActualRect を使用してください。 |
| color_type | ページの色タイプを、演算子 SetColor、画像、フォームから取得した情報に基づいて設定します。<br/>             |
| note_line_style | ノートの線スタイルを取得または設定します。（ジェネレータ専用で、ドキュメント読み取り時には設定されません） |
| tab_order | ページのタブ順序を取得または設定します。 <br/>            可能な値: Row, Column. デフォルト, Manual |
| duration | ページ表示時間を取得または設定します。これはプレゼンテーション中にページが表示される秒数です。<br/>            期間が定義されていない場合は -1 を返します。 |
| contents | ページのコンテンツストリーム内の演算子コレクションを取得します。<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| group | ページの page�s ページグループの属性を指定する group attributes クラスを取得または設定します。 |
| annotations | ページ注釈のコレクションを取得します。<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | ページリソースを取得します。Resources オブジェクトは画像、フォーム、フォントのコレクションを含みます。<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| rotate | ページの回転を取得または設定します。 |
| trim_box | ページのトリムボックスを取得または設定します。 |
| art_box | ページのアートボックスを取得または設定します。 |
| bleed_box | ページのブリードボックスを取得または設定します。 |
| crop_box | ページのクロップボックスを取得または設定します。 |
| media_box | ページのメディアボックスを取得または設定します。 |
| number | ページ番号を取得します。 |
| rotation_matrix | ページの変換行列を取得します。 |
| background | ページの背景色を取得または設定します。 |
| watermark | ページの透かしを取得または設定します。 |
| artifacts | ページ上のアーティファクトのコレクションを取得します。 |
| actions | ページプロパティのコレクションを取得します。 |
| fields_in_tab_order | このページのタブ順にある Field オブジェクトのリストを取得します。 |
| user_unit | UserUnit の値を取得または設定します。デフォルトのユーザースペース単位のサイズを示す正の数で、1 ⁄ 72 インチの倍数です。<br/>            デフォルト値は 1 です。このエントリをクリアするには、0 または負の値を設定してください。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| send_to(device, output) | 指定されたページデバイスでページを処理に送ります。 |
| send_to(device, output_file_name) | 指定されたページデバイスでページを処理に送ります。 |
| accept(visitor) | Accepts [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) ビジターオブジェクトを受け入れ、アノテーションの操作機能を提供します。 |
| accept(visitor) | Accepts [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) ビジターオブジェクトを受け入れ、テキストオブジェクトの操作機能を提供します。 |
| accept(visitor) | Accepts [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) ビジターオブジェクトを受け入れ、画像配置オブジェクトの操作機能を提供します。 |
| accept(visitor) | Accepts [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) ビジターオブジェクトを受け入れ、テキストオブジェクトの操作機能を提供します。 |
| add_image(image_stream, image_rect) | 画像をページに追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| add_image(hocr, image_stream, image_rect) | 検索可能な画像をページに追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | ページに画像を追加し、画像矩形の位置に従って配置します。 |
| add_image(image_path, rectangle) | 検索可能な画像をページに追加し、指定された矩形の中央に配置して画像の比率を保持します。 |
| is_blank(fill_threshold_factor) | ページが空白かどうかを示すフラグを取得します。 |
| get_page_rect(consider_rotation) | ページのCropBox（CropBoxがnullの場合はMediaBox）に従った矩形を返します。 |
| calculate_content_b_box() | 可視マージンなしでコンテンツを含む矩形（bbox）を計算します。 |
| rotation_to_int(rotation) | 回転列挙体のメンバーを整数値に変換します。 |
| int_to_rotation(rotation) | 整数値を対応する回転列挙体のメンバーに変換します。 |
| add_stamp(stamp) | ページにスタンプを配置します。スタンプはページ番号、画像、またはシンプルなテキスト（例：ロゴ）にできます。 |
| flatten() | ページ上にあるすべてのフィールドを削除し、代わりにその値を配置します。 |
| set_page_size(width, height) | ページのサイズを設定します。 |
| make_grayscale() | ページをグレースケールに変換します。 |
| free_memory() | キャッシュされたデータをクリアします |
| get_notifications() | ページコンテンツに対する内部操作に関する通知を返します。（現在、テキスト追加シナリオでの段落イベントに関する通知のみがサポートされています。） |
| as_byte_array(resolution) | 現在のページをビットマップに変換し、バイト配列として返します。 |
| as_xml() | 現在のページを UTF-8 エンコーディングの XML に変換します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

