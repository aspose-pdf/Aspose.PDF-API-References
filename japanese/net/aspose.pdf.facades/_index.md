---
title: "Aspose.Pdf.Facades"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades 名前空間は、元々 Aspose.Pdf.Kit から来たクラスを提供します。これらのクラスは、文書を操作し、結合、スタンプ、署名、注釈付けなどの処理を高レベルで実行するために使用されますが、文書の内部構造へのアクセスは行いません"
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/
---
**Aspose.Pdf.Facades** 名前空間は、もともと Aspose.Pdf.Kit から来たクラスを提供します。これらのクラスは、ドキュメントを結合、スタンプ付与、署名、注釈付与などの操作で操作するために使用されますが、ドキュメントの内部構造にアクセスせずに高レベルで行えます。

## クラス

| クラス | 説明 |
| --- | --- |
| [AutoFiller](./autofiller/) | データベースやその他のデータソースからデータを受け取り、テンプレート PDF の設計されたフィールドに入力し、最終的に新しい PDF ファイルまたはストリームを生成するクラスを表します。テンプレートファイルの入力モードは 2 つあり、ストリームとしての入力または PDF ファイルとしての入力があります。出力モードは 4 種類あり、1 つの結合ストリーム、1 つの結合ファイル、複数の小さなストリーム、複数の小さなファイルです。System.Data.DataTable に含まれるリテラルデータを受け取ることができます。 |
| [BDCProperties](./bdcproperties/) | BDC 演算子のプロパティ。 |
| [Bookmark](./bookmark/) | ブックマークを表します。 |
| [Bookmarks](./bookmarks/) | [`Bookmark`](../aspose.pdf.facades/bookmark/) オブジェクトのコレクションを表します。 |
| [DocumentPrivilege](./documentprivilege/) | Pdf ファイルへのアクセス権限を表します。[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/) を参照してください。このクラスの使用方法は 4 つあります：1. 事前定義された権限を直接使用する。2. 事前定義された権限に基づき、特定の権限を変更する。3. 事前定義された権限に基づき、特定の Adobe Professional 権限の組み合わせを変更する。4. 方法 2 と方法 3 を組み合わせる。 |
| [Facade](./facade/) | ベース ファサード クラスです。 |
| [FontColor](./fontcolor/) | テキストの色を表すクラスです。 |
| [Form](./form/) | Acro フォーム オブジェクトを表すクラスです。 |
| [FormattedText](./formattedtext/) | 書式設定されたテキストを表すクラスです。テキストとその色、サイズ、スタイルに関する情報を含みます。 |
| [FormDataConverter](./formdataconverter/) | データをある形式から別の形式へ変換するクラスを表します。fdf/xml/pdf/xfdf のデータを OLEDB/OdbcDB に変換できます。また、OLEDB/OdbcDB のデータを fdf/xml/xfdf に変換することも可能です。fdf を \"hard-named\" タグ付きの xml に変換することができます。 |
| [FormEditor](./formeditor/) | フォームの編集（フィールドの追加/削除など）を行うクラスです。 |
| [FormFieldFacade](./formfieldfacade/) | フィールド プロパティを表すクラスです。 |
| [LineInfo](./lineinfo/) | 線の情報を表します。 |
| [PdfAnnotationEditor](./pdfannotationeditor/) | PDF ドキュメントの注釈（コメント）を扱うクラスを表します。 |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | PDF ファイルのブックマーク（作成、変更、エクスポート、インポート、削除）を扱うクラスを表します。 |
| [PdfContentEditor](./pdfcontenteditor/) | PDF ファイルのコンテンツを編集するクラスを表します。 |
| [PdfConverter](./pdfconverter/) | PDF ファイルの各ページを画像に変換するクラスを表します。現在、BMP、JPEG、PNG、TIFF をサポートしています。PDF のサポート対象コンテンツ：画像、フォーム、コメント。 |
| [PdfExtractor](./pdfextractor/) | PDF ドキュメントから画像とテキストを抽出するクラスです。 |
| [PdfFileEditor](./pdffileeditor/) | PDF ファイルに対する操作（結合、分割、ページ抽出、ブックレット作成など）を実装します。 |
| [PdfFileInfo](./pdffileinfo/) | PDF ドキュメントのメタ情報にアクセスするクラスを表します。 |
| [PdfFileMend](./pdffilemend/) | 既存の PDF ドキュメントのページにテキストや画像を追加するクラスを表します。 |
| [PdfFileSanitization](./pdffilesanitization/) | サニタイズおよびリカバリ API を表します。他の方法でドキュメントを作成/開くことができない場合に使用してください。 |
| [PdfFileSecurity](./pdffilesecurity/) | 所有者またはユーザー パスワードで PDF ファイルを暗号化または復号し、セキュリティ設定やパスワードを変更することを表します。 |
| [PdfFileSignature](./pdffilesignature/) | 証明書で PDF ファイルに署名するクラスを表します。 |
| [PdfFileStamp](./pdffilestamp/) | PDF ファイルにスタンプ（透かしまたは背景）を追加するクラスです。 |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | すべての Java Script コードを削除するクラスです。 |
| [PdfPageEditor](./pdfpageeditor/) | PDF ファイルのページを編集するクラスを表します。ページの回転、ズーム、位置の移動、ページサイズの変更を含みます。 |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | 現在の印刷ページ情報を含むオブジェクトを表します。 |
| [PdfProducer](./pdfproducer/) | 他の形式から PDF を生成するクラスを表します。このサンプルは CGM ファイルから Pdf ファイルを生成する方法を示しています。 |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) イベントを処理するメソッドを表します。[`PdfViewer`](../aspose.pdf.facades/pdfviewer/) のメソッドです。 |
| [PdfViewer](./pdfviewer/) | pdf を表示または印刷するクラスを表します。 |
| [PdfXmpMetadata](./pdfxmpmetadata/) | XMP メタデータを操作するクラスです。 |
| [ReplaceTextStrategy](./replacetextstrategy/) | このクラスは ReplaceText 操作が実行されたときの PdfContentEditor の動作を定義するパラメータを含みます。 |
| [SaveableFacade](./saveablefacade/) | 保存可能なすべてのファサードの基底クラスです。 |
| [SignatureName](./signaturename/) | 署名名のクラスを表します。 |
| [Stamp](./stamp/) | スタンプを表すクラスです。 |
| [StampInfo](./stampinfo/) | スタンプ情報を表すクラスです。 |
| [TextProperties](./textproperties/) | テキストサイズ、色、スタイルなどのテキストプロパティを表します。 |
| [ViewerPreference](./viewerpreference/) | ビューアの設定 (ページモード、全画面でないページモード、ページレイアウト) を記述します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IFacade](./ifacade/) | 共通のファサードメソッドを定義する一般的なファサードインターフェイスです。 |
| [ISaveableFacade](./isaveablefacade/) | すべての保存可能なファサードに共通するメソッドを定義するファサードインターフェイスです。 |
## 列挙体

| 列挙体 | 説明 |
| --- | --- |
| [Algorithm](./algorithm/) | pdf document を暗号化するために使用できるアルゴリズムを表します。 |
| [AutoRotateMode](./autorotatemode/) | document が印刷される際の回転方向です。 |
| [BlendingColorSpace](./blendingcolorspace/) | ブレンドカラー空間を表すクラスです。 |
| [DataType](./datatype/) | フィールドタイプの定義を列挙します。 |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | 標準 XMP プロパティの列挙です。 |
| [EncodingType](./encodingtype/) | テキストで使用されるエンコーディングタイプを列挙します。 |
| [FieldType](./fieldtype/) | 可能なフィールドタイプの列挙です。 |
| [FontStyle](./fontstyle/) | フォントの 14 種類を列挙します。 |
| [ImageMergeMode](./imagemergemode/) | 画像の結合モードを表します。 |
| [KeySize](./keysize/) | pdf documents を暗号化するために使用できるさまざまな鍵サイズを定義します。 |
| [PositioningMode](./positioningmode/) | 配置モードを定義します。可能な値には Legacy（下位互換性）と Current（更新されたテキスト位置計算方法）が含まれます。 |
| [PropertyFlag](./propertyflag/) | 可能なフィールドフラグの列挙です。 |
| [StampType](./stamptype/) | スタンプの種類を説明します。 |
| [SubmitFormFlag](./submitformflag/) | 可能な送信フォームフラグの列挙です。 |
| [WordWrapMode](./wordwrapmode/) | 単語折り返し戦略を定義します |


