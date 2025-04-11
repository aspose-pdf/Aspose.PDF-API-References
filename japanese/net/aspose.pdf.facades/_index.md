---
title: Aspose.Pdf.Facades
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades 名前空間は、元々 Aspose.Pdf.Kit から来たクラスを提供します。これらのクラスは、文書を操作するために使用され、結合、スタンプ、署名、注釈などの操作を高レベルで実行しますが、文書の内部構造にはアクセスしません。
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/
---
**Aspose.Pdf.Facades** 名前空間は、元々 Aspose.Pdf.Kit から来たクラスを提供します。これらのクラスは、文書を操作するために使用され、結合、スタンプ、署名、注釈などの操作を高レベルで実行しますが、文書の内部構造にはアクセスしません。

## クラス

| クラス | 説明 |
| --- | --- |
| [AutoFiller](./autofiller/) | データベースまたは他のデータソースからデータを受け取り、テンプレート PDF の設計されたフィールドに埋め込み、最終的に新しい PDF ファイルまたはストリームを生成するクラスを表します。入力モードはストリームまたは PDF ファイルとしての2つのテンプレートファイル入力モードがあります。出力モードは、1つのマージストリーム、1つのマージファイル、多くの小さなストリーム、多くの小さなファイルの4種類があります。System.Data.DataTable に含まれるリテラルデータを受け取ることができます。 |
| [BDCProperties](./bdcproperties/) | BDC オペレーターのプロパティ。 |
| [Bookmark](./bookmark/) | ブックマークを表します。 |
| [Bookmarks](./bookmarks/) | [`Bookmark`](../aspose.pdf.facades/bookmark/) オブジェクトのコレクションを表します。 |
| [DocumentPrivilege](./documentprivilege/) | PDF ファイルへのアクセス権を表します。[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/) を参照してください。このクラスの使用方法は4つあります: 1. 定義済みの権限を直接使用する。 2. 定義済みの権限に基づいて特定の権限を変更する。 3. 定義済みの権限に基づいて特定の Adobe Professional 権限の組み合わせを変更する。 4. 方法2と方法3を混合する。 |
| [Facade](./facade/) | 基本ファサードクラス。 |
| [FontColor](./fontcolor/) | テキストの色を表すクラス。 |
| [Form](./form/) | Acro フォームオブジェクトを表すクラス。 |
| [FormattedText](./formattedtext/) | フォーマットされたテキストを表すクラス。テキストとその色、サイズ、スタイルに関する情報を含みます。 |
| [FormDataConverter](./formdataconverter/) | ある形式から別の形式にデータを変換するクラスを表します。fdf/xml/pdf/xfdf のデータを OLEDB/OdbcDB に変換できます。また、OLEDB/OdbcDB のデータを fdf/xml/xfdf のデータに変換することもできます。fdf を "ハードネーム" タグを持つ xml に変換できます。 |
| [FormEditor](./formeditor/) | フォームを編集するためのクラス（フィールドの追加/削除など）。 |
| [FormFieldFacade](./formfieldfacade/) | フィールドプロパティを表すクラス。 |
| [LineInfo](./lineinfo/) | 行の情報を表します。 |
| [PdfAnnotationEditor](./pdfannotationeditor/) | PDF ドキュメントの注釈（コメント）を操作するためのクラスを表します。 |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | PDF ファイルのブックマークを作成、変更、エクスポート、インポート、削除するためのクラスを表します。 |
| [PdfContentEditor](./pdfcontenteditor/) | PDF ファイルのコンテンツを編集するためのクラスを表します。 |
| [PdfConverter](./pdfconverter/) | PDF ファイルの各ページを画像に変換するためのクラスを表します。現在、BMP、JPEG、PNG、TIFF をサポートしています。PDF 内のサポートされているコンテンツ: 画像、フォーム、コメント。 |
| [PdfExtractor](./pdfextractor/) | PDF ドキュメントから画像とテキストを抽出するためのクラス。 |
| [PdfFileEditor](./pdffileeditor/) | PDF ファイルに対する操作を実装します: 結合、分割、ページの抽出、ブックレットの作成など。 |
| [PdfFileInfo](./pdffileinfo/) | PDF ドキュメントのメタ情報にアクセスするためのクラスを表します。 |
| [PdfFileMend](./pdffilemend/) | 既存の PDF ドキュメントのページにテキストや画像を追加するためのクラスを表します。 |
| [PdfFileSanitization](./pdffilesanitization/) | サニタイズおよび回復 API を表します。他の方法で文書を作成/開くことができない場合に使用します。 |
| [PdfFileSecurity](./pdffilesecurity/) | 所有者またはユーザーパスワードで PDF ファイルを暗号化または復号化し、セキュリティ設定とパスワードを変更するためのクラスを表します。 |
| [PdfFileSignature](./pdffilesignature/) | 証明書を使用して PDF ファイルに署名するためのクラスを表します。 |
| [PdfFileStamp](./pdffilestamp/) | PDF ファイルにスタンプ（透かしまたは背景）を追加するためのクラス。 |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | すべての JavaScript コードを削除するためのクラス。 |
| [PdfPageEditor](./pdfpageeditor/) | PDF ファイルのページを編集するためのクラスを表し、ページの回転、ズーム、位置の移動、ページサイズの変更を含みます。 |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | 現在の印刷ページ情報を含むオブジェクトを表します。 |
| [PdfProducer](./pdfproducer/) | 他の形式から PDF を生成するためのクラスを表します。このサンプルは、CGM ファイルから PDF ファイルを生成する方法を示しています。 |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | [`PdfViewer`](../aspose.pdf.facades/pdfviewer/) の [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) イベントを処理するメソッドを表します。 |
| [PdfViewer](./pdfviewer/) | PDF を表示または印刷するためのクラスを表します。 |
| [PdfXmpMetadata](./pdfxmpmetadata/) | XMP メタデータを操作するためのクラス。 |
| [ReplaceTextStrategy](./replacetextstrategy/) | このクラスは、ReplaceText 操作が実行されるときの PdfContentEditor の動作を定義するパラメータを含みます。 |
| [SaveableFacade](./saveablefacade/) | すべての保存可能なファサードの基本クラス。 |
| [SignatureName](./signaturename/) | 署名名を表すクラス。 |
| [Stamp](./stamp/) | スタンプを表すクラス。 |
| [StampInfo](./stampinfo/) | スタンプ情報を表すクラス。 |
| [TextProperties](./textproperties/) | テキストのプロパティ（テキストサイズ、色、スタイルなど）を表します。 |
| [ViewerPreference](./viewerpreference/) | ビューアの設定（ページモード、フルスクリーンでないページモード、ページレイアウト）を説明します。 |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [IFacade](./ifacade/) | 一般的なファサードインターフェースで、共通のファサードメソッドを定義します。 |
| [ISaveableFacade](./isaveablefacade/) | すべての保存可能なファサードに共通のメソッドを定義するファサードインターフェース。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [Algorithm](./algorithm/) | PDF ドキュメントを暗号化するために使用できるアルゴリズムを表します。 |
| [AutoRotateMode](./autorotatemode/) | ドキュメントが印刷されるときの回転の方向。 |
| [BlendingColorSpace](./blendingcolorspace/) | ブレンディングカラースペースを表すクラス。 |
| [DataType](./datatype/) | フィールドタイプの定義を列挙します。 |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | 標準 XMP プロパティの列挙。 |
| [EncodingType](./encodingtype/) | テキストの使用におけるエンコーディングタイプを列挙します。 |
| [FieldType](./fieldtype/) | 可能なフィールドタイプの列挙。 |
| [FontStyle](./fontstyle/) | 14 種類のフォントを列挙します。 |
| [ImageMergeMode](./imagemergemode/) | 画像をマージするためのモードを表します。 |
| [KeySize](./keysize/) | PDF ドキュメントを暗号化するために使用できる異なるキーサイズを定義します。 |
| [PositioningMode](./positioningmode/) | 位置決めモードを定義します。可能な値には、レガシー（後方互換性）と現在（更新されたテキスト位置計算方法）が含まれます。 |
| [PropertyFlag](./propertyflag/) | 可能なフィールドフラグの列挙。 |
| [StampType](./stamptype/) | スタンプの種類を説明します。 |
| [SubmitFormFlag](./submitformflag/) | 可能な送信フォームフラグの列挙。 |
| [WordWrapMode](./wordwrapmode/) | ワードラッピング戦略を定義します。 |