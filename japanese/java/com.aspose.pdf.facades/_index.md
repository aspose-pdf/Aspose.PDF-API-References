---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "com.aspose.pdf.facades パッケージは、もともと Aspose.Pdf.Kit から来たクラスを提供します。"
type: docs
weight: 180
url: /ja/java/com.aspose.pdf.facades/
---
com.aspose.pdf.facades パッケージは、もともと Aspose.Pdf.Kit から来たクラスを提供します。

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IFacade](./ifacade/) | 共通ファサードメソッドを定義する一般的なファサードインターフェイス。 |
| [IForm](./iform/) | Acro フォームオブジェクトを表すクラス。 |
| [IFormEditor](./iformeditor/) | フォームの編集（フィールドの追加/削除など）を行うクラス。 |
| [IPdfFileEditor](./ipdffileeditor/) | PDF ファイルに対する操作（結合、分割、ページ抽出、ブックレット作成など）を実装します。 |
| [IPdfFileStamp](./ipdffilestamp/) | PDF ファイルにスタンプ（透かしまたは背景）を追加するためのインターフェイス。 |
| [ISaveableFacade](./isaveablefacade/) | すべての保存可能なファサードで共通のメソッドを定義するファサードインターフェイス。 |
## クラス

| クラス | 説明 |
| --- | --- |
| [AlignmentType](./alignmenttype/) | クラスにはさまざまな配置タイプが含まれています。代わりに HorizontalAlignment を使用してください。 |
| [AutoRotateMode](./autorotatemode/) | ドキュメントが印刷される際の回転方向。 |
| [BDCProperties](./bdcproperties/) | BDC 演算子のプロパティ。 |
| [Bookmark](./bookmark/) | ブックマークを表します。 |
| [Bookmarks](./bookmarks/) |  {@code Bookmark} オブジェクトのコレクションを表します。 |
| [CgmPdfProducer](./cgmpdfproducer/) | Computer Graphics Metafile（CGM）形式から PDF を生成するクラスを表します。 |
| [DataType](./datatype/) | フィールドタイプ定義を列挙します。 |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | 標準 XMP プロパティの列挙です。 |
| [DocumentPrivilege](./documentprivilege/) | Pdf ファイルへのアクセス権限を表します。 {@code PdfFileSecurity} を参照してください。このクラスの使用方法は 4 つあります: 1. 事前定義された権限を直接使用する。 2. 事前定義された権限を基にして特定の権限を変更する。 3. 事前定義された権限を基にして特定の Adobe Professional 権限の組み合わせを変更する。 4. 方法 2 と方法 3 を組み合わせる。 //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | 使用されるテキストのエンコーディングタイプを列挙します。 |
| [Facade](./facade/) | 基本ファサードクラス。 |
| [FontColor](./fontcolor/) | テキストの色を表すクラス。 |
| [Form](./form/) | Acro フォームオブジェクトを表すクラス。 |
| [Form.ImportStatus](./form.importstatus/) | インポートされたフィールドのステータス |
| [FormattedText](./formattedtext/) | 書式設定されたテキストを表すクラス。テキストとその色、サイズ、スタイルに関する情報を含みます。 |
| [FormEditor](./formeditor/) | フォームの編集（フィールドの追加/削除など）を行うクラス。 |
| [FormEditorWeb](./formeditorweb/) | フォーム（フィールドの追加/削除など）を編集するためのクラス。 |
| [FormFieldFacade](./formfieldfacade/) | フィールドプロパティを表すクラス。 |
| [FormWeb](./formweb/) | Acro フォームインターフェイスを表します。 |
| [InternalHelper](./internalhelper/) | ヘルプクラス |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | ページリサイズパラメータを指定するクラス。次のパラメータを設定できます: 結果ページのサイズ（幅、高さ）をデフォルトの空間単位または元ページサイズのパーセンテージで指定; 左、上、下、右の余白をデフォルトの空間単位または元ページサイズのパーセンテージで指定; 一部の値は自動計算のために null のままにできます。これらの値は、明示的に指定された値を除いた残りのページサイズから計算されます。例: ページ幅 = 100、 新しいページ幅を 60 単位と指定した場合、左と右の余白は自動的に計算されます: (100 - 60) / 2 = 15。このクラスは ResizeContents メソッドで使用されます。 |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | 余白またはコンテンツサイズの値をデフォルトの空間単位のパーセンテージで指定します。このクラスは ContentsResizeParameters で使用されます。 |
| [LineInfo](./lineinfo/) | 行の情報を表します。 |
| [PdfAnnotationEditor](./pdfannotationeditor/) | PDF ドキュメントの注釈（コメント）を扱うクラスを表します。 |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | PDF ファイルのブックマーク（作成、変更、エクスポート、インポート、削除を含む）を扱うクラスを表します。 |
| [PdfContentEditor](./pdfcontenteditor/) | PDF ファイルの内容を編集するクラスを表します。 |
| [PdfConverter](./pdfconverter/) | PDF ファイルの各ページを画像に変換するクラスを表します。現在、BMP、JPEG、PNG、TIFF をサポートしています。PDF のサポート対象コンテンツ: 画像、フォーム、コメント。 |
| [PdfExtractor](./pdfextractor/) | PDF ドキュメントから画像とテキストを抽出するクラスです。 |
| [PdfFileEditor](./pdffileeditor/) | PDF ファイルに対する操作（結合、分割、ページ抽出、ブックレット作成など）を実装します。 |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | 結合処理中に破損したファイルに遭遇したときに実行されるアクションです。 |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | 結合から発生する進捗イベントを処理し、通常は呼び出し側が提供する抽象メソッドを持つクラスを表します。通常、この提供された顧客側ハンドラはコンソールやプログレスバーに全体の結合進捗を表示するために使用できます。発生した進捗イベントに関する情報を表します。 |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | 結合時に破損したファイルに関する情報を提供するクラスです。 |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | 改ページ位置のデータです。 |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | このクラスは、外部アプリケーションで使用できる結合進捗に関する情報を表します。 |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | この列挙型は、結合中に発生し得る可能な進捗イベントの種類を説明します。 |
| [PdfFileEditorWeb](./pdffileeditorweb/) | PDF ファイルに対する結合、分割、ページ抽出、ブックレット作成などの操作を実装する PdfFileEditorWeb クラスを表します。 |
| [PdfFileInfo](./pdffileinfo/) | PDF ドキュメントのメタ情報にアクセスするクラスを表します。 |
| [PdfFileMend](./pdffilemend/) | 既存の PDF ドキュメントのページにテキストや画像を追加するクラスを表します。 |
| [PdfFileSanitization](./pdffilesanitization/) | サニタイズおよびリカバリ API を表します。他の方法でドキュメントを作成/開くことができない場合に使用してください。 |
| [PdfFileSecurity](./pdffilesecurity/) | 所有者またはユーザーパスワードで PDF ファイルを暗号化または復号し、セキュリティ設定やパスワードを変更する機能を表します。 |
| [PdfFileSignature](./pdffilesignature/) | 証明書で PDF ファイルに署名するクラスを表します。 |
| [PdfFileStamp](./pdffilestamp/) | PDF ファイルにスタンプ（透かしまたは背景）を追加するクラスです。 |
| [PdfFileStampWeb](./pdffilestampweb/) | PDF ファイルにスタンプ（透かしまたは背景）を追加するクラスです。HttpServletResponse と連携できるようにします。 |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | すべての JavaScript コードを除去するクラスです。 |
| [PdfPageEditor](./pdfpageeditor/) | ページの回転、ズーム、位置移動、ページサイズ変更など、PDF ファイルのページを編集するクラスを表します。 |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | 現在の印刷ページ情報を含むオブジェクトを表します。 |
| [PdfProducer](./pdfproducer/) | <p> 他の形式から PDF を生成するクラスを表します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | PrintDocument の QueryPageSettings イベントを処理するメソッドを表します。 |
| [PdfViewer](./pdfviewer/) | PDF を表示または印刷するクラスを表します。 |
| [PdfXmpMetadata](./pdfxmpmetadata/) | XMP メタデータを操作するクラスです。 |
| [PositioningMode](./positioningmode/) | 配置モードを定義します。可能な値は Legacy（下位互換性）と Current（更新されたテキスト位置計算方法）です。 |
| [PropertyFlag](./propertyflag/) | 可能なフィールドフラグの列挙。 |
| [ReplaceTextStrategy](./replacetextstrategy/) | このクラスは、ReplaceText 操作が実行されるときの PdfContentEditor の動作を定義するパラメータを含みます。 |
| [SaveableFacade](./saveablefacade/) | <p> すべての保存可能なファサードの基底クラスです。 |
| [SignatureName](./signaturename/) | 署名名のクラスを表します。より正確な署名名を表します。文字列名の代わりに使用されます。同じ文字列名で署名を提示することができます。 |
| [Stamp](./stamp/) | スタンプを表すクラスです。 |
| [StampInfo](./stampinfo/) | スタンプ情報を表すクラスです。 |
| [TextProperties](./textproperties/) | テキストサイズ、色、スタイルなどのテキストプロパティを表します。 |
| [VerticalAlignmentType](./verticalalignmenttype/) | 可能な垂直位置合わせ値を表すクラスです。代わりに VerticalAlignment を使用してください。 |
| [ViewerPreference](./viewerpreference/) | ビューアの設定（ページモード、全画面以外のページモード、ページレイアウト）を説明します。 |
| [WordWrapMode](./wordwrapmode/) | 単語折り返し戦略を定義します |
## Enums

| 列挙型 | 説明 |
| --- | --- |
| [Algorithm](./algorithm/) | PDF ドキュメントの暗号化に使用できるアルゴリズムを表します。 |
| [BlendingColorSpace](./blendingcolorspace/) | ブレンドカラー空間を表すクラスです。 |
| [FieldType](./fieldtype/) | 可能なフィールドタイプの列挙です。 |
| [FontStyle](./fontstyle/) | 14 種類のフォントを列挙します。 |
| [ImageMergeMode](./imagemergemode/) | 画像の結合モードを表します。 |
| [KeySize](./keysize/) | PDF ドキュメントの暗号化に使用できるさまざまな鍵サイズを定義します。 |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | フォントに必要な文字が含まれていない場合に実行するアクション |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | テキスト置換操作が適用される範囲（デフォルトは REPLACE_FIRST）です。 |
| [StampType](./stamptype/) | スタンプタイプを説明します。 |
| [SubmitFormFlag](./submitformflag/) | 可能な送信フォームフラグの列挙です。 |
