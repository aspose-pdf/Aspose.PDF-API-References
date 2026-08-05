---
title: "HtmlSaveOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "HTML 形式へのエクスポート用の保存オプション"
type: docs
weight: 490
url: /ja/python-net/aspose.pdf/htmlsaveoptions/
---

## HtmlSaveOptions class

HTML 形式へのエクスポート用の保存オプション

HtmlSaveOptions 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| HtmlSaveOptions() | [HtmlSaveOptions](/pdf/python-net/aspose.pdf/htmlsaveoptions/) クラスの新しいインスタンスを初期化します。 |
| HtmlSaveOptions(document_type) | HtmlSaveOptions クラスの新しいインスタンスを初期化します。 |
| HtmlSaveOptions(fixed_layout) | HtmlSaveOptions クラスの新しいインスタンスを初期化します。 |
| HtmlSaveOptions(document_type, fixed_layout) | HtmlSaveOptions クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバックです。 <br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。 <br/>            Continue はデフォルトのアクションで、保存操作は継続しますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |
| save_format | データ保存の形式です。 |
| close_response | ドキュメントがレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| extract_ocr_sublayer_only | None |
| try_merge_adjacent_same_background_images | None |
| document_type | 取得または設定します [HtmlDocumentType](/pdf/python-net/aspose.pdf/htmldocumenttype/)。 |
| compress_svg_graphics_if_any | 取得または設定しますこのフラグは、<br/>            見つかった SVG グラフィック（存在する場合）が圧縮（ZIP）され、<br/>            保存時に SVGZ 形式になるかどうかを示します。 |
| split_css_into_pages | マルチページモードが選択された場合（例：'SplitIntoPages' が 'true'）、<br/>            この属性は各結果 HTML ページごとに別々の CSS ファイルを作成するかどうかを定義します。<br/>            デフォルトではこの属性は false で、すべての作成されたページに対して 1 つの大きな共通 CSS が作成されます。<br/>            このモードで生成されるすべての CSS（ページごとに 1 つの CSS）の合計サイズは、通常、1 つの大きな CSS ファイルのサイズよりもはるかに大きくなります。<br/>            以前のケースでは、CSS クラスが各ページの複数の CSS ファイルに重複して存在するためです。<br/>            したがって、この設定は、各 HTML ページを個別に将来処理したい場合にのみ使用すべきであり、その場合、ページごとに分離された CSS のサイズが最も重要な問題となります。 |
| split_into_pages | 取得または設定しますこのフラグは、ソース <br/>            文書の各ページがそれぞれのターゲット HTML 文書に変換されるかどうか、<br/>            すなわち結果の HTML が複数の HTML ページに分割されるかどうかを示します。 |
| explicit_list_of_saved_pages | このプロパティを使用すると、変換すべき文書のページを明示的に定義できます。<br/>            このリストのページは 1 から始まる番号でなければなりません。つまり、ページ番号は (1...[NumberOfPagesInConvertedDocument]) の範囲から取得する必要があります。<br/>            リスト内のページの出現順序は、結果の HTML ページの順序に影響しません。結果のページは常にソース PDF に存在する順序で表示されます。<br/>            このリストが null（デフォルト）の場合、すべてのページが変換されます。<br/>            リスト内のページ番号が存在するページの範囲 (1-[amountOfPagesInDocument]) を超えると、例外がスローされます。 |
| fixed_layout | 取得または設定します。この値は、HTML が固定レイアウトとして作成されるかどうかを示します。 |
| image_resolution | 取得または設定します。画像レンダリングの解像度を設定します。 |
| default_font_name | インストールされているフォントの名前を指定します。このフォントは、埋め込まれておらずシステムにインストールされていない文書フォントの代替として使用されます。<br/>            null の場合、デフォルトの代替フォントが使用されます。 |
| batch_size | バッチ変換がソースおよび宛先フォーマットの組み合わせに適用可能な場合、バッチサイズを定義します。<br/>             |
| font_sources | 事前に保存されたフォントのフォントソースです。 |
| additional_margin_width_in_points | 属性 'SplitOnPages=false' の場合、すべての入力 PDF ページを表す HTML 全体が異なる HTML ページに分割されず、1 つの大きな結果 HTML ファイルにまとめられます。<br/>            ただし、各ソース PDF ページは HTML 内でそれぞれの矩形領域として表現されます（必要に応じて、'PageBorderIfAny' 属性でページの紙の端を示す枠線を付けることができます）。<br/>            このパラメータは、ソース PDF 文書のページを表す出力 HTML 領域の周囲に強制的に設定される余白幅を定義します。本質的に、PDF の "paper" ページの HTML 表現間の保証された間隔を定義するものです。 |
| use_z_order | 属性 UseZORder が true に設定されている場合、グラフィックとテキストは元の PDF 文書の Z オーダーに従って結果の HTML 文書に追加されます。<br/>            この属性が false の場合、すべてのグラフィックは単一のレイヤーとして配置され、重なり合うオブジェクトに対して不要な効果が生じる可能性があります。 |
| convert_marked_content_to_layers | 属性 ConvertMarkedContentToLayers が true に設定されている場合、PDF のマーク付きコンテンツ（レイヤー）内のすべての要素は、レイヤー名を指定する "data-pdflayer" 属性を持つ HTML の div に配置されます。<br/>            このレイヤー名は、PDF のマーク付きコンテンツのオプションプロパティから抽出されます。<br/>            この属性が false（デフォルト）の場合、PDF のマーク付きコンテンツからレイヤーは作成されません。 |
| minimal_line_width | この属性はグラフィックパスラインの最小幅を設定します。<br/>ラインの太さが1px未満の場合、Adobe Acrobatはこの値に丸めます。<br/>そのため、この属性はHTMLブラウザでこの動作をエミュレートするために使用できます。 |
| prevent_glyphs_grouping | この属性は、テキストグリフが単語や文字列にグループ化されないモードをオンにします。<br/>このモードにより、ページ上でのグリフの位置決め精度を最大限に保つことができ、楽譜や互いに別々に配置すべきグリフを含む文書の変換に使用できます。<br/>このパラメータは、FixedLayout属性の値がtrueの場合にのみ文書に適用されます。 |
| simple_textbox_mode_grouping | この属性は、グリフと単語を文字列に順次グループ化することを指定します。<br/>例えば、変換されたHTMLでタグと単語の順序が異なり、これらを一致させたい場合です。<br/>このパラメータは、FixedLayout属性の値がtrueの場合にのみ文書に適用されます。 |
| flow_layout_paragraph_full_width | この属性は、Flowモード（FixedLayout = false）における全幅段落テキストを指定します。 |
| render_text_as_image | RenderTextAsImage属性がtrueに設定されている場合、ソースのテキストはHTML内で画像になります。<br/>テキストを選択不可にしたい場合に役立ちます<br/>またはHTMLテキストが正しくレンダリングされない場合です。 |
| save_full_font | フルフォントが保存されることを示し、True Typeフォントのみをサポートします。<br/>デフォルトでは SaveFullFont = false で、コンバータは文書のテキスト表示に必要な元フォントのサブセットを保存します。 |
| antialiasing_processing | このパラメータは、PDFからHTMLへの複合背景画像変換時に必要なアンチエイリアス処理を定義します。 |
| save_transparent_texts | PDFには、クリップボードに選択できる透明テキストが含まれることがあります（通常、文書に画像があり、そこから抽出されたOCRテキストがある場合に発生します）。<br/>この設定は、コンバータに対して、これらのテキストを結果のHTMLで透明かつ選択可能なテキストとして保存するかどうかを指示します。 |
| save_shadowed_texts_as_transparent_texts | PDFには、他の要素（例: 画像）に影付けされたテキストが含まれることがありますが、<br/>Acrobat Readerではクリップボードに選択できます（通常、文書に画像があり、そこから抽出されたOCRテキストがある場合に発生します）。<br/>この設定は、コンバータに対して、Acrobat Readerの動作を模倣するために、これらのテキストを結果のHTMLで透明かつ選択可能なテキストとして保存するかどうかを指示します（そうしない場合、これらのテキストは通常、非表示として保存され、クリップボードへのコピーはできません）。 |
| font_saving_mode | PDFを目的の形式に保存する際に使用されるフォント保存モードを定義します。 |
| page_border_if_any | この属性は、境界線（存在する場合）を描画するために使用される設定の集合を表します。<br/>結果のHTMLドキュメントで、ソースPDFページを表す領域の周囲に適用されます。<br/>本質的には、ページの紙の端を表示することに関係します。<br/>PDFページ自体で参照されるページ境界ではありません。 |
| page_margin_if_any | この属性は、追加のページ余白（存在する場合）の設定集合を表します。<br/>結果のHTMLドキュメントで、ソースPDFページを表す領域の周囲に適用されます。 |
| letters_positioning_method | 結果のHTMLにおける単語内の文字の配置モードを設定します |
| exclude_font_name_list | HTMLに埋め込まれないPDF埋め込みフォント名のリスト |
| special_folder_for_svg_images | HTMLとしてドキュメントを保存する際に SVG 画像が検出された場合にのみ保存するディレクトリのパスを取得または設定します。<br/>            パラメータが空または null の場合、SVG ファイル（存在すれば）は他の画像ファイルと同じ場所（出力ファイルの近く）に保存されるか、<br/>            SpecialImagesFolderIfAny オプションで指定された場合は画像用の特別フォルダーに保存されます。<br/>            CustomImageSavingStrategy プロパティが正常に使用されて画像ファイルの処理が行われた場合、これには影響しません。 |
| special_folder_for_all_images | HTMLとしてドキュメントを保存する際に画像が検出された場合に保存するディレクトリのパスを取得または設定します。<br/>            パラメータが空または null の場合、画像ファイル（存在すれば）はHTMLにリンクされた他のファイルと一緒に保存されます。<br/>            CustomImageSavingStrategy プロパティが正常に使用されて画像ファイルの処理が行われた場合、これには影響しません。 |
| css_class_names_prefix | PDFtoHTML コンバータが結果の CSS を生成する際、CSS クラス名<br/>            （例: \".stl_01 {}\" ... \".stl_NN {}\" のようなもの）が生成され、結果の CSS で使用されます。このプロパティを使用すると、クラス名のプレフィックスを強制的に設定できます。<br/>            例えば、すべてのクラス名を 'my_prefix_' で始めたい場合（例: 'my_prefix_1' ... 'my_prefix_NNN' のように）、変換前にこのプロパティに 'my_prefix_' を割り当てるだけです。<br/>            このプロパティを変更しないまま（つまり null のまま）にすると、コンバータは自動的にクラス名を生成します<br/>            （例: \".stl_01 {}\" ... \".stl_NN {}\" のようになります）。 |
| parts_embedding_mode | 参照されるファイル（HTML、フォント、画像、CSS）がメイン HTML ファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを定義します。<br/>             |
| html_markup_generation_mode | HTML マークアップの生成に特定の要件がある場合があります。<br/>            このパラメータは、PDF から HTML への変換時にそのような特定の要件に合わせて使用できる HTML 準備モードを定義します。 |
| raster_images_saving_mode | 変換された PDF にはラスタ画像が含まれることがあります。<br/>            このパラメータは、PDF から HTML への変換時にそれらの画像をどのように処理するかを定義します。 |
| remove_empty_areas_on_top_and_bottom | 作成された HTML から、コンテンツがない上部および下部の空白領域（存在する場合）を削除するかどうかを定義します。 |
| font_encoding_strategy | 現在のドキュメントの PDF デコードを調整するためのエンコーディングに関する特別な規則を定義します。 |
| pages_flow_type_depends_on_viewers_screen_size | 属性 'SplitOnPages=false' の場合、すべての入力 PDF ページを表す HTML 全体が <br/>            1つの大きな結果 HTML ファイルにまとめられます。 <br/>            このフラグは、結果 HTML が生成される際に、PDF ページを表す領域の流れがビューアの画面解像度に依存するかどうかを定義します。<br/>            ビューア側の画面幅が十分に広く、横方向に 2 ページ以上を隣り合わせに配置できると想定します。 <br/>            このフラグが true の場合、その機会が利用され、可能な限り多くのページが横方向に隣り合わせに表示され、次の横方向のページグループは最初のグループの下に表示されます。<br/>            それ以外の場合、ページは常に前のページの下に続く形で流れます。 |
| try_save_text_underlining_and_strikeouting_in_css | PDF 自体にはテキストの下線マーカーが含まれていません。テキストの下に線を配置してエミュレートしています。<br/>            このオプションにより、コンバータはその線がテキストの下線であるかどうかを推測し、下線をグラフィカルに描画する代わりにその情報を CSS に入れることができます。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

