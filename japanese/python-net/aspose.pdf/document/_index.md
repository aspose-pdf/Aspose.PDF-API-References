---
title: "Document"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ドキュメントを表すクラス"
type: docs
weight: 230
url: /ja/python-net/aspose.pdf/document/
---

## Document class

PDF ドキュメントを表すクラス

Document 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Document(input) | Document クラスの新しいインスタンスを初期化します |
| Document(input, password, is_managed_stream) | Document クラスの新しいインスタンスを初期化します |
| Document(input, is_managed_stream) | Document クラスの新しいインスタンスを初期化します |
| Document(filename) | Document クラスの新しいインスタンスを初期化します |
| Document(input, password) | Document クラスの新しいインスタンスを初期化します |
| Document() | 空のドキュメントを初期化します。 |
| Document(filename, options) | Document クラスの新しいインスタンスを初期化します |
| Document(input, options) | Document クラスの新しいインスタンスを初期化します |
| Document(filename, password) | Document クラスの新しいインスタンスを初期化します |
| Document(filename, password, is_managed_stream) | Document クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| java_script | ドキュメントレベルの JavaScript コレクションです。 |
| is_licensed | システムのライセンス状態を取得します。システムがライセンスモードで動作している場合は true、そうでない場合は false を返します。 |
| page_info | ページ情報を取得または設定します。（ジェネレータ用のみで、ドキュメントを読み込む際には設定されません） |
| enable_signature_sanitization | 署名フィールドのサニタイズを管理するフラグを取得または設定します。デフォルトで有効です。 |
| is_pdfa_compliant | ドキュメントが PDF/A に準拠しているかを取得します。 |
| is_pdf_ua_compliant | ドキュメントが PDF/UA に準拠しているかを取得します。 |
| is_xref_gaps_allowed | ドキュメントが PDF/A に準拠しているかを取得または設定します。 |
| named_destinations | ドキュメント内の Named Destination のコレクション。 |
| デスティネーション | デスティネーションのコレクションを取得します。<br/>            廃止予定です。NamedDestinations を使用してください。 |
| pdf_format | PDF フォーマットを取得します |
| embed_standard_fonts | ドキュメントがすべての標準 Type1 フォントを埋め込む必要があることを宣言するプロパティ <br/>            フラグ IsEmbedded が true に設定されているもの。すべての PDF フォントは<br/>            フラグ IsEmbedded を true に設定するだけでドキュメントに埋め込むことができますが、PDF の標準 Type1 フォントはこの規則の例外です。<br/>            標準 Type1 フォントの埋め込みには多くの時間がかかるため、これらのフォントを埋め込むには<br/>            指定されたフォントのフラグ IsEmbedded を true に設定するだけでなく、<br/>            ドキュメントレベルで追加のフラグ - EmbedStandardFonts = true; を設定する必要があります。<br/>            このプロパティはすべてのフォントに対して一度だけ設定できます。<br/>            デフォルトは falseです。 |
| disable_font_license_verifications | フォントに関する多くの操作は、そのフォントのライセンスで禁止されている場合は実行できません。<br/>            例えば、ライセンス規則により埋め込みが禁止されているフォントは PDF ドキュメントに埋め込むことができません。<br/>            このフラグは、現在の PDF ドキュメント内のすべてのフォントに対するライセンス制限を無効にするために使用されます。<br/>            このフラグを使用する際は注意が必要です。設定された場合、そのフラグを設定した人が、<br/>            可能なライセンス／法的違反に対する全責任を自ら負うことを意味します。<br/>            したがって、自己のリスクで使用することになります。<br/>            著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。<br/>            デフォルトは falseです。 |
| font_utilities | IDocumentFontUtilities インスタンス |
| コレクション | ドキュメントのコレクションを取得します。 |
| version | PDF ファイルヘッダーから PDF のバージョンを取得します。 |
| open_action | ドキュメントが開かれたときに実行されるアクションを取得または設定します。 |
| hide_tool_bar | ドキュメントがアクティブなときにツールバーを非表示にするかどうかを指定するフラグを取得または設定します。 |
| hide_menubar | ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを指定するフラグを取得または設定します。 |
| hide_window_ui | ドキュメントがアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを指定するフラグを取得または設定します。 |
| fit_window | ドキュメントウィンドウを最初に表示されるページに合わせてサイズ変更する必要があるかどうかを指定するフラグを取得または設定します。 |
| center_window | ドキュメントのウィンドウの位置が画面の中央に配置されるかどうかを指定するフラグを取得または設定します。 |
| display_doc_title | ドキュメントのウィンドウタイトルバーにドキュメントタイトルを表示するかどうかを指定するフラグを取得または設定します。 |
| pages | ドキュメントページのコレクションを取得または設定します。<br/>            コレクション内のページは 1 から番号付けされていることに注意してください。 |
| outlines | ドキュメントのアウトラインを取得します。 |
| actions | ドキュメントのアクションを取得します。このプロパティは DocumentActions クラスのインスタンスで、BeforClosing、BeforSaving などのアクションを取得/設定できるようにします。 |
| form | ドキュメントの Acro Form を取得します。 |
| embedded_files | ドキュメントに埋め込まれたファイルのコレクションを取得します。 |
| direction | テキストの読み順（L2R（左から右）または R2L（右から左））を取得または設定します。 |
| page_mode | ドキュメントが開かれたときの表示方法を指定するページモードを取得または設定します。 |
| non_full_screen_page_mode | 全画面モードを終了したときにドキュメントを表示する方法を指定するページモードを取得または設定します。 |
| page_layout | ドキュメントが開かれたときに使用されるページレイアウトを取得または設定します。 |
| duplex | 印刷ダイアログからファイルを印刷する際に使用する印刷両面モードの処理オプションを取得または設定します。 |
| file_name | このドキュメントを生成した PDF ファイルの名前 |
| info | ドキュメント情報を取得します。 |
| メタデータ | ドキュメントのメタデータ。<br/>            (PDF ドキュメントには、タイトル、作者、作成日および変更日などの一般情報が含まれる場合があります。<br/>             ドキュメントの内容や構造とは対照的に、ドキュメント全体に関するこのような情報はメタデータと呼ばれ、<br/>             外部データベースでのカタログ作成や検索を支援することを目的としています。) |
| 論理構造 | ドキュメントの論理構造を取得します。 |
| 署名変更の処理 | ドキュメントが変更された状態で保存され、かつ署名がある場合は例外をスローします。 |
| 暗号アルゴリズム | ドキュメントが暗号化されている場合のセキュリティ設定を取得します。<br/>            ドキュメントが暗号化されていない場合、.net 1.1 では対応する例外がスローされ、<br/>            他の .net バージョンでは CryptoAlgorithm が null になります。 |
| 線形化されているか | ドキュメントが線形化されているかどうかを示す値を取得または設定します。 |
| 権限 | ドキュメントの権限を取得します。 |
| is_encrypted | ドキュメントの暗号化状態を取得します。暗号化されている場合は true です。 |
| id | ID を取得します。 |
| background | ドキュメントの背景色を取得または設定します。 |
| optimize_size | 最適化フラグを取得または設定します。このフラグが設定されている場合、ページがドキュメントに追加されると、結果ファイル内の同等のリソースストリームが<br/>            1つの PDF オブジェクトにマージされます。<br/>            これにより結果ファイルのサイズを減少させることができますが、実行が遅くなりメモリ使用量が増加する可能性があります。<br/>            デフォルト値: false. |
| allow_reuse_page_content | ページ内容をマージしてドキュメントサイズを最適化できるようにします。使用すると、異なるが重複したページが同じコンテンツオブジェクトを参照する場合があります。<br/>            このモードは、あるページが変更されたときに別のページの内容が変わるといった副作用を引き起こす可能性があることに注意してください。 |
| 破損オブジェクトを無視する | ソースファイルのエラーを無視するフラグを取得または設定します。<br/>            ソースドキュメントからページが宛先ドキュメントにコピーされる際、フラグが false の場合、ソースファイル内のオブジェクトが破損していると例外でコピー処理が停止します。<br/>            例: dest.Pages.Add(src.Pages);<br/>            フラグが true に設定されていると、破損したオブジェクトは空の値で置き換えられます。<br/>            デフォルト: true. |
| ページラベル | ドキュメント内のページラベルを取得します。 |
| オブジェクトのアンロードを有効化 | ドキュメントをメモリから部分的にアンロードできるようにするフラグを取得または設定します。<br/>            これによりメモリ使用量を減少させることができますが、パフォーマンスに悪影響を及ぼす可能性があります。 |
| タグ付けコンテンツ | TaggedPdf コンテンツへのアクセスを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| save(output) | ドキュメントをストリームに保存します。 |
| save(output_file_name) | 指定されたファイルにドキュメントを保存します。 |
| save() | ドキュメントをストリームに保存します。 |
| save(options) | 保存オプションでドキュメントを保存します。 |
| save(output_file_name, format) | 新しい名前とファイル形式でドキュメントを保存します。 |
| save(output_stream, format) | 新しい名前とファイル形式でドキュメントを保存します。 |
| save(output_file_name, options) | 新しい名前で保存し、保存オプションを設定してドキュメントを保存します。 |
| save(output_stream, options) | 保存オプションを使用してストリームにドキュメントを保存します。 |
| export_annotations_to_xfdf(file_name) | すべてのドキュメント注釈をXFDFファイルにエクスポートします。 |
| export_annotations_to_xfdf(stream) | すべてのドキュメント注釈をストリームにエクスポートします。 |
| send_to(device, output) | ドキュメント全体を処理用にデバイスへ送信します。 |
| send_to(device, from_page, to_page, output) | ドキュメントの特定ページを処理用にデバイスへ送信します。 |
| send_to(device, output_file_name) | ドキュメント全体を処理用にデバイスへ送信します。 |
| send_to(device, from_page, to_page, output_file_name) | ドキュメント全体を処理用にデバイスへ送信します。 |
| import_annotations_from_xfdf(file_name) | XFDFファイルから注釈をドキュメントにインポートします。 |
| import_annotations_from_xfdf(stream) | ストリームからドキュメントへ注釈をインポートします。 |
| validate(output_log_file_name, format) | ドキュメントを指定されたファイルに検証します。 |
| validate(output_log_stream, format) | ドキュメントを指定されたファイルに検証します。 |
| validate(options) | ドキュメントを指定されたファイルに検証します。 |
| convert(output_log_file_name, format, action, transparency_action) | ドキュメントを変換し、エラーを指定されたファイルに保存します。 |
| convert(output_log_stream, format, action, transparency_action) | ドキュメントを変換し、エラーを指定されたファイルに保存します。 |
| convert(output_log_file_name, format, action) | ドキュメントを変換し、エラーを指定されたファイルに保存します。 |
| convert(options) | 指定された変換オプションを使用してドキュメントを変換します |
| convert(output_log_stream, format, action) | ドキュメントを変換し、エラーを指定されたファイルに保存します。 |
| convert(fixup, output_log, only_validation, parameters) | Fixup を適用してドキュメントを変換します。 |
| convert(fixup, output_log, only_validation, parameters) | Fixup を適用してドキュメントを変換します。 |
| convert(src_file_name, load_options, dst_file_name, save_options) | ソース形式のソースファイルを、宛先形式の宛先ファイルに変換します。 |
| convert(src_stream, load_options, dst_file_name, save_options) | ソース形式のストリームを、宛先形式の宛先ファイルに変換します。 |
| convert(src_file_name, load_options, dst_stream, save_options) | ソース形式のストリームを、宛先形式の宛先ファイルに変換します。 |
| convert(src_stream, load_options, dst_stream, save_options) | ソース形式のストリームを、宛先形式の宛先ファイルに変換します。 |
| flatten() | ドキュメントからすべてのフィールドを削除し、その代わりに値を配置します。 |
| flatten(flatten_settings) | ドキュメントからすべてのフィールドを削除し、その代わりに値を配置します。 |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | ドキュメントを暗号化します。暗号化されたバージョンを取得するには、Save を呼び出してください。 |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | ドキュメントを暗号化します。暗号化されたバージョンを取得するには、Save を呼び出してください。 |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | ドキュメントを暗号化します。暗号化されたバージョンを取得するには、Save を呼び出してください。 |
| optimize_resources() | ドキュメント内のリソースを最適化します:<br/>            1. ドキュメントページで使用されていないリソースは削除されます;<br/>            2. 同一のリソースは1つのオブジェクトに結合されます; <br/>            3. 未使用のオブジェクトが削除されます. |
| optimize_resources(strategy) | 定義された最適化戦略に従ってドキュメント内のリソースを最適化します。 |
| bind_xml(file) | XML をドキュメントにバインドします |
| bind_xml(xml_file, xsl_file) | XML をドキュメントにバインドします |
| bind_xml(xml_stream, xsl_stream) | XML/XSL をドキュメントにバインドします |
| bind_xml(stream) | XML/XSL をドキュメントにバインドします |
| remove_pdfa_compliance() | ドキュメントから PDF/A 準拠を削除します |
| remove_pdf_ua_compliance() | ドキュメントから PDF/UA 準拠を削除します |
| set_title(title) | PDF ドキュメントのタイトルを設定します |
| process_paragraphs() | ジェネレーター用に段落を処理します。 |
| remove_metadata() | ドキュメントからメタデータを削除します。 |
| change_passwords(owner_password, new_user_password, new_owner_password) | ドキュメントのパスワードを変更します。この操作は所有者パスワードを使用してのみ実行できます。 |
| decrypt() | ドキュメントを復号化します。その後 Save を呼び出して復号化されたバージョンを取得してください。 |
| optimize() | Linearize document in order to<br/>            - open the first page as quickly as possible;<br/>            - display next page or follow by link to the next page as quickly as possible;<br/>            - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first);<br/>            - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed.<br/>            Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure,<br/>            call then Save to get optimized document. |
| get_catalog_value(key) | カタログ辞書から項目の値を返します。 |
| free_memory() | メモリをクリアします。 |
| save_xml(file) | ドキュメントを XML に保存します。 |
| get_object_by_id(id) | ドキュメント内で指定された ID を持つオブジェクトを取得します。 |
| repair() | 破損したドキュメントを修復します。 |
| get_xmp_metadata(stream) | ドキュメントから XMP メタデータを取得します。 |
| set_xmp_metadata(stream) | ドキュメントの XMP メタデータを設定します。 |
| check(do_repair) | ドキュメントを検証します。 |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。<br/>            ドキュメントに nodesNumInSubtrees 以上のページオブジェクトがある場合にのみ実行され、そうでなければ何もしません。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

