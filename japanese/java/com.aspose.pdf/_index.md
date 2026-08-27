---
title: "com.aspose.pdf"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "com.aspose.pdf は、Aspose.PDF for Java ライブラリのすべてのクラスのルートパッケージであり、Document のように直接含まれるクラスや、いくつかのサブパッケージを介して間接的に含まれるクラスが含まれます。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf/
---
com.aspose.pdf は、Aspose.PDF for Java ライブラリのすべてのクラスのルートパッケージであり、Document のように直接含まれるクラスや、いくつかのサブパッケージを介して間接的に含まれるクラスが含まれます。

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | hocr 認識のコールバック手順。 |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | hocr 認識のコールバック手順。 |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | hocr 認識のコールバック手順。 |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | フォントを調整する機能を保持します |
| [IAnnotationVisitor](./iannotationvisitor/) | さまざまなドキュメント注釈を訪問する Visitor を定義します。 |
| [IAppointment](./iappointment/) | アクションとデスティネーションの一般的なインターフェイスを表します。 |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | カラースペース変換戦略のインターフェイス。 |
| [IDocument](./idocument/) | PDF ドキュメントを表すインターフェイス |
| [IFontOptions](./ifontoptions/) | フォントの動作を調整するための便利なプロパティ |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | このインターフェイスは量子化のカスタマイズアルゴリズム用に宣言されています。ユーザーはこのアルゴリズムの独自実装（例としてアンマネージドコードに基づくアルゴリズム）を実装できます。 |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | このインターフェイスは量子化のカスタマイズアルゴリズム用に宣言されています。ユーザーはこのアルゴリズムの独自実装（例としてアンマネージドコードに基づくアルゴリズム）を実装できます。 |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | さまざまな pdf 演算子を訪問する Visitor を定義します。 |
| [IPageSetOptions](./ipagesetoptions/) | 変換対象ページのセットに関連する変換オプションを定義します。 |
| [IPipelineOptions](./ipipelineoptions/) | パイプライン構成に関連する変換オプションを定義します。 |
| [ITableElement](./itableelement/) | このインターフェイスは TableAbsorber によって抽出された既存テーブルの要素を表します。 |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | 場合によっては、外部リソース（画像や CSS など）の内部ローダーの使用を回避し、要求されたリソースを取得するカスタムメソッドを提供する必要があります。たとえば、クラウド上で Aspose.PDf を使用する際には参照ファイルへの直接アクセスが不可能であり、特別なメソッドにカスタムコードを入れて使用する必要があります。このデリゲートはそのようなカスタムメソッドのシグネチャを定義します。 |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * 一時フォルダーを一時フォントデータのホストに使用するかどうかのフラグを設定します。 / * デフォルトは true です。 / * value = false の場合はヒープメモリを使用します。 / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | この種のプロパティには、PDF から生成された SVG から抽出され、PDF から HTML への変換時に外部リソースとして保存される画像の外部保存処理を実装したカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの独自保存などの処理はカスタムコードで行い、カスタムコードはパス（または引用符なしの任意の文字列）を返す必要があります。そのパスは、元の画像リソースへの想定パスの代わりに生成された SVG に組み込まれます。この場合、画像の保存に必要なすべての操作は提供されたメソッドのコード内で実行しなければなりません。なぜかコンバータのコード自体で処理する必要がある場合は、カスタムコード内で 'CustomProcessingCancelled' フラグを 'imageSavingInfo' パラメータの変数に設定してください。これにより、外部カスタムコードがないかのように、リソースの処理に必要なすべての手順がコンバータ側で実行されることをコンバータに通知します。 |
## クラス

| クラス | 説明 |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | ページ上に存在するテーブルのセルを表します |
| [AbsorbedRow](./absorbedrow/) | ページ上に存在するテーブルの行を表します |
| [AbsorbedTable](./absorbedtable/) | ページ上に存在するテーブルを表します |
| [ActionCollection](./actioncollection/) | アクションのコレクション |
| [Annotation](./annotation/) | アノテーションオブジェクトを表すクラスです。 |
| [AnnotationActionCollection](./annotationactioncollection/) | アノテーションアクションのコレクションを表します。 |
| [AnnotationCollection](./annotationcollection/) | アノテーションコレクションを表すクラスです。 |
| [AnnotationFlags](./annotationflags/) | フラグ アノテーションのさまざまな特性を指定するバイナリフラグのセットです。 |
| [AnnotationSelector](./annotationselector/) | このクラスは Visitor テンプレートの考え方を使用してアノテーションを選択するために使用されます。 |
| [AnnotationTextRenderer](./annotationtextrenderer/) | 通常テキストとリッチテキストをレンダリングするクラスです。 |
| [AppearanceDictionary](./appearancedictionary/) | ページ上でアノテーションが視覚的にどのように表示されるかを指定するアノテーション外観辞書です。 |
| [ApsLoadOptions](./apsloadoptions/) | APS のロードオプションを記述するクラスです。APS XML 形式からのインポートオプションです。 |
| [ApsSaveOptions](./apssaveoptions/) | APS XML 形式へのエクスポート用の保存オプションです。 |
| [ApsToFlowConverter](./apstoflowconverter/) | APS から Flow への変換 |
| [Artifact](./artifact/) | PDF アーティファクトオブジェクトを表すクラスです。 |
| [ArtifactCollection](./artifactcollection/) | アーティファクトコレクションを表すクラスです。 |
| [AutoTaggingSettings](./autotaggingsettings/) | PDF ドキュメントにおける自動タグ付け機能の設定を提供します。{@link AutoTaggingSettings} クラスは PDF コンテンツの自動タグ付けオプションを構成できるようにします。自動タグ付けの有効化/無効化、見出し認識の戦略の指定、フォントサイズに基づく見出しレベルの定義などのプロパティを含みます。 |
| [BackgroundArtifact](./backgroundartifact/) | 背景アーティファクトを記述するクラスです。このアーティファクトはページの背景を設定できるようにします。 |
| [BarcodeField](./barcodefield/) | バーコードフィールドを表すクラスです。 |
| [BaseActionCollection](./baseactioncollection/) | ページ/アノテーション/フィールドのインタラクティブアクションに関する基本的な操作をカプセル化するクラスです。 |
| [BaseOperatorCollection](./baseoperatorcollection/) | オペレーターコレクションの基底クラスを表します。 |
| [BaseParagraph](./baseparagraph/) | ページに追加できる抽象基底オブジェクト（doc.Paragraphs.Add()）を表します。 |
| [BatesNArtifact](./batesnartifact/) | クラスはBates番号付けアーティファクトを説明します。 |
| [BitmapInfo](./bitmapinfo/) | ピクセルの配列とビットマップ情報を含むオブジェクト。 |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | ビットマップのピクセル形式。 |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Bleed Markアノテーションを表します。Bleedマークは印刷ページの角に配置され、ページのトリミング位置とトリムマークからどれだけずれてよいかを示します。 |
| [Border](./border/) | アノテーション境界の特性を表すクラス。 |
| [BorderInfo](./borderinfo/) | このクラスはグラフィック要素の境界を表します。 |
| [BorderSide](./borderside/) | フラグは境界側をバイナリで列挙します。 |
| [BorderStyleConverter](./borderstyleconverter/) | BorderStyleConverterクラスを表します |
| [Brush](./brush/) | このクラスは抽象ブラシを表します |
| [BuildVersionInfo](./buildversioninfo/) | このクラスは現在の製品ビルドに関する情報を提供します。 |
| [ButtonField](./buttonfield/) | クラスはプッシュボタンフィールドを表します。 |
| [CaretAnnotation](./caretannotation/) | Caretアノテーションを表すクラス。 |
| [CaretSymbolConverter](./caretsymbolconverter/) | CaretSymbolConverterクラスを表します |
| [CdrLoadOptions](./cdrloadoptions/) | クラスはCDRロードオプションを説明します。 |
| [Cell](./cell/) | テーブル行のセルを表します。 |
| [Cells](./cells/) | 行のセルコレクションを表します。 |
| [CgmImportOptions](./cgmimportoptions/) | Computer Graphics Metafile（CGM）形式からのインポートオプション。 |
| [CgmLoadOptions](./cgmloadoptions/) | CGMファイルをPDFドキュメントにロード/インポートするためのオプションを含みます。 |
| [Characteristics](./characteristics/) | アノテーションの特性を表します |
| [CharInfo](./charinfo/) | 文字情報オブジェクトを表します。文字の位置情報を提供します。 |
| [CharInfoCollection](./charinfocollection/) | <p> CharInfoオブジェクトのコレクションを表します。 </p> <hr> <pre> この例は、すべての文字を反復処理し、文字を取得する方法を示します //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> テキストセグメント文字の位置情報へのアクセスを提供します。 </p> |
| [CheckboxField](./checkboxfield/) | チェックボックスフィールドを表すクラス |
| [ChoiceField](./choicefield/) | 選択フィールドの基底クラスを表します。 |
| [CircleAnnotation](./circleannotation/) | 円アノテーションを表すクラス。 |
| [Collection](./collection/) | Collection（12.3.5 Collections）用のクラスを表します。 |
| [CollectionField](./collectionfield/) | ドキュメントコレクションスキーマフィールドクラスを表します。 |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | スキーマコレクション内のフィールドのサブタイプパラメータを表します。 |
| [CollectionItem](./collectionitem/) | コレクションアイテムクラスを表します。コレクションアイテムはコレクションスキーマで記述されたデータを含みます。 |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | コレクションアイテムの値を表すクラスです。 |
| [CollectionSchema](./collectionschema/) | ドキュメントコレクションの「Schema」を記述するクラスを表します。 |
| [Color](./color/) | さまざまなカラースペースで表現できるカラー値のクラスを表します。 |
| [ColorBarAnnotation](./colorbarannotation/) | ColorBarAnnotation アノテーションを表すクラスです。プロパティ Color は無視され、代わりに ColorsOfCMYK カラーが使用されます。作成時に幅と高さの比率でアノテーションの向き（水平または垂直）が決定されます。次に、アノテーション矩形が TrimBox の外にあるか確認し、外にない場合は、アノテーションの向きを考慮して最も近い TrimBox 外側の位置へシフトされます。幅（高さ）を縮小してアノテーションを TrimBox の外に収めることが可能です。レイアウト用の空間がない場合、幅/高さを 0 に設定できます（この場合、アノテーションはページに存在しますが表示されません）。 |
| [ColumnInfo](./columninfo/) | このクラスは列の情報を表します。 |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | イベントを表すクラスです。 |
| [ComboBoxField](./comboboxfield/) | フォームのコンボボックスフィールドを表すクラスです。 |
| [ComHelper](./comhelper/) | <p> COM クライアントがドキュメントを Aspose.PDF にロードするためのメソッドを提供します。 </p> <hr> <p> COM アプリケーションでファイルまたはストリームからドキュメントを Document オブジェクトにロードするには ComHelper クラスを使用します。Document クラスは新しいドキュメントを作成するデフォルトコンストラクタを提供し、ファイルまたはストリームからロードするためのオーバーロードされたコンストラクタも提供します。.NET アプリケーションで Aspose.Words を使用している場合は、すべての Document コンストラクタを直接使用できますが、COM アプリケーションで Aspose.PDF を使用している場合は、デフォルトの Document コンストラクタのみが利用可能です。 </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | 共通の図形アノテーションを表す抽象クラスです。 |
| [CompositingParameters](./compositingparameters/) | 現在のグラフィックス状態の合成パラメータを含むオブジェクトを表します。 |
| [ContentsAppender](./contentsappender/) | 内容の変更は APPEND モードのみで実行します。このモードにより、内容に変更を加える前の不要で重いパース処理を回避できます。新しいオペレーターは内容の末尾または先頭に追加されるだけです。 |
| [Copier](./copier/) | オブジェクトをコピーするためのクラスです。 |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | 印刷ページの角に配置されるアノテーションタイプを表します。 |
| [CustomExplicitDestination](./customexplicitdestination/) | カスタムの明示的なデスティネーションを表します。 |
| [CustomSign](./customsign/) | ドキュメントにカスタム署名を行うデリゲート（ベータ版）です。 |
| [Dash](./dash/) | 線の破線パターンを表すクラスです。 |
| [DateField](./datefield/) | カレンダー表示付きの日付フィールドです。DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | フィールドのデフォルト外観（フォント、テキストサイズ、カラー）を記述します。 |
| [DefaultDirectory](./defaultdirectory/) | 特定の目的のためのデフォルトパスを指定します。 |
| [DestinationCollection](./destinationcollection/) | PDF ドキュメント内のすべてのデスティネーション（名前文字列をデスティネーションにマッピングする名前ツリー（12.3.2.3「Named Destinations」参照）および（7.7.4「Name Dictionary」参照））のコレクションを表すクラスです。 |
| [DestinationFactory](./destinationfactory/) | DestinationFactory クラスを表します。 |
| [DjvuLoadOptions](./djvuloadoptions/) | DJVU のロードオプションを記述するクラスです。 |
| [DocMDPSignature](./docmdpsignature/) | 文書 MDP（変更検出と防止）署名タイプのクラスを表します。 |
| [DocSaveOptions](./docsaveoptions/) | Doc 形式へのエクスポート用保存オプション |
| [Document](./document/) | PDF 文書を表すクラス。 |
| [Document.OptimizationOptions](./document.optimizationoptions/) | 文書最適化アルゴリズムを記述するクラス。このクラスのインスタンスは OptimizeResources() メソッドのパラメータとして使用できます。@deprecated このクラスは廃止されました。代わりに com.aspose.pdf.optimization.OptimizationOptions を使用してください。 |
| [Document.RepairOptions](./document.repairoptions/) | PDF 文書の修復オプションを表します。このクラスは PDF 文書の修復プロセスをカスタマイズする方法を提供します。 |
| [DocumentActionCollection](./documentactioncollection/) | 文書に対して実行されるいくつかのアクションを記述するクラス |
| [DocumentExtensions](./documentextensions/) | Document クラスに追加機能を提供します。 |
| [DocumentFactory](./documentfactory/) | さまざまなタイプの文書を作成/ロードできるクラス。 |
| [DocumentInfo](./documentinfo/) | PDF 文書のメタ情報を表します。 |
| [DocumentWeb](./documentweb/) | DocumentWeb クラスを表します。 |
| [Element](./element/) | 論理構造の基本要素を表すクラス。 |
| [ElementCollection](./elementcollection/) | 基本的な論理構造要素のコレクション。 |
| [EmbeddedFileCollection](./embeddedfilecollection/) | 埋め込みファイルコレクションを表すクラス。 |
| [EncryptedPayload](./encryptedpayload/) | ファイル仕様内の暗号化されたペイロードを表します。 |
| [EpubLoadOptions](./epubloadoptions/) | EPUB ファイルを PDF 文書にロード/インポートするためのオプションを含みます。 |
| [EpubSaveOptions](./epubsaveoptions/) | EPUB 形式へのエクスポート用保存オプション |
| [ExcelSaveOptions](./excelsaveoptions/) | Excel 形式へのエクスポート用保存オプション |
| [ExplicitDestination](./explicitdestination/) | PDF 文書の明示的なデスティネーションの基底クラスを表します。 |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | ExplicitDestinationTypeConverter クラスを表します。 |
| [ExportFieldsOptions](./exportfieldsoptions/) | フォームフィールドのエクスポートオプションの基底クラスを表します。 |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | フォームフィールドを Json 形式でエクスポートするためのオプションを表します。{@link ExportFieldsOptions} から継承し、Json エクスポート用の特定オプションを追加します。 |
| [ExportImportMessages](./exportimportmessages/) | フォームフィールドのエクスポートおよびインポート操作に関するさまざまなエラーメッセージを含みます。 |
| [ExternalSignature](./externalsignature/) | X509Certificate2 を使用して分離型 PKCS#7Detached 署名を作成します。USB スマートカードや、エクスポート可能なプライベートキーを持たないトークンをサポートします。 |
| [FdfReader](./fdfreader/) | FDF 形式の読み取りを実行するクラス。 Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf"); |
| [Field](./field/) | Acro フォームフィールドの基底クラス。 |
| [FieldSerializationResult](./fieldserializationresult/) | フォームフィールドのシリアライズ処理の結果を表します。 |
| [FieldSerializationStatus](./fieldserializationstatus/) | フォームフィールドのシリアライズのステータスを表します。 |
| [FieldValueType](./fieldvaluetype/) | スキーマコレクション内のフィールド値の型を表します。 |
| [FigureElement](./figureelement/) | 論理構造図を表すクラスです。 |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | ファイル添付アノテーションを記述するクラスです。 |
| [FileFontSource](./filefontsource/) | 単一フォントファイルのソースを表します。 |
| [FileHyperlink](./filehyperlink/) | ファイルハイパーリンクオブジェクトを表します。 |
| [FileIconConverter](./fileiconconverter/) | FileIconConverter クラスを表します。 |
| [FileParams](./fileparams/) | 埋め込みファイルパラメータ辞書を定義し、追加のファイル固有情報を含めます。 |
| [FileSelectBoxField](./fileselectboxfield/) | ファイル選択ボックス要素のフィールドです。 |
| [FileSpecification](./filespecification/) | 埋め込みファイルを表すクラスです。 |
| [FitBExplicitDestination](./fitbexplicitdestination/) | ページの内容が水平・垂直の両方向でウィンドウ内にバウンディングボックス全体が収まるように拡大された、明示的な表示先を表します。必要な水平および垂直の拡大率が異なる場合は、両者のうち小さい方を使用し、もう一方の方向でバウンディングボックスをウィンドウの中央に配置します。 |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | ページの垂直座標 top がウィンドウの上端に位置し、ページの内容がバウンディングボックスの幅全体がウィンドウ内に収まるように拡大された、明示的な表示先を表します。top が null の場合は、そのパラメータの現在値を変更せずに保持することを意味します。 |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | ページの水平座標 left がウィンドウの左端に位置し、ページの内容がバウンディングボックスの高さ全体がウィンドウ内に収まるように拡大された、明示的な表示先を表します。left が null の場合は、そのパラメータの現在値を変更せずに保持することを意味します。 |
| [FitExplicitDestination](./fitexplicitdestination/) | ページ全体がウィンドウ内に水平・垂直の両方向で収まるように内容が拡大された、明示的な表示先を表します。必要な水平および垂直の拡大率が異なる場合は、両者のうち小さい方を使用し、もう一方の方向でページをウィンドウの中央に配置します。 |
| [FitHExplicitDestination](./fithexplicitdestination/) | ページの垂直座標 top がウィンドウの上端に位置し、ページの内容がページ全体の幅がウィンドウ内に収まるように拡大された、明示的な表示先を表します。top が null の場合は、そのパラメータの現在値を変更せずに保持することを意味します。 |
| [FitRExplicitDestination](./fitrexplicitdestination/) | ページの内容が left、bottom、right、top の座標で指定された矩形がウィンドウ内に水平・垂直の両方向で完全に収まるように拡大された、明示的な表示先を表します。必要な水平および垂直の拡大率が異なる場合は、両者のうち小さい方を使用し、もう一方の方向で矩形をウィンドウの中央に配置します。任意のパラメータが null の場合、予測できない動作になる可能性があります。 |
| [FitVExplicitDestination](./fitvexplicitdestination/) | ページの水平座標 left がウィンドウの左端に位置し、ページの内容がページ全体の高さがウィンドウ内に収まるように拡大された、明示的な表示先を表します。left が null の場合は、そのパラメータの現在値を変更せずに保持することを意味します。 |
| [FixedPrint](./fixedprint/) | 透かしアノテーションの固定印刷データを表します。 |
| [FloatingBox](./floatingbox/) | PDF ドキュメント内の FloatingBox を表します。FloatingBox はカスタム位置に配置されます。 |
| [FlowConverter](./flowconverter/) | PDF ドキュメントを Flow 形式（XLSX、ODS、XMLSpreedSheet2003、CSV）や EnchanedFlow モードの DOCX、FlowEngine モードの TableAbsorber に変換します。 |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Flow ライブラリから TableAbsorber へデータを渡す |
| [FolderFontSource](./folderfontsource/) | フォントファイルを含むフォルダーを表します。 |
| [Font](./font/) | <p> フォントオブジェクトを表します。 </p> <hr> <pre> The example demonstrates how to search text on first page and change font of a first search occurrence. // Open document Document doc = new Document(\"input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | フォントの吸収オブジェクトを表します。フォントの検索を実行し、検索結果へ {@code FontAbsorber.Fonts} コレクションを介してアクセスできるようにします。 |
| [FontCollection](./fontcollection/) | <p> フォントコレクションを表します。 </p> <hr> <pre> この例は、ページで宣言されたすべてのフォントを埋め込みにする方法を示しています。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\\\Tests\\\\input.pdf"); </pre> <hr> <p> {@code FontCollection} クラスで表されるフォントコレクションは、さまざまなシナリオで使用されます。たとえば、{@code Resources.Fonts} プロパティを持つリソースで使用されます。 </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | PDF/A 標準では、すべてのフォントを文書に埋め込むことが要求されています。このクラスには、フォントが宛先 PC に存在せず埋め込めない場合のフラグが含まれています。 |
| [FontRepository](./fontrepository/) | <p> フォント検索を実行します。システムにインストールされたフォントと標準の PDF フォントを検索します。また、カスタムフォントを開く機能も提供します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置換する方法を示しています。 // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | フォントソースの基底クラスを表します。 |
| [FontStyles](./fontstyles/) | Binary Flag <p> テキストに適用されるスタイル情報を指定します。 </p> <hr> <p> この列挙体には、メンバー値の組み合わせを可能にする {@code FlagsAttribute} 属性があります。 </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag はフォントのサブセット化戦略を列挙します。 |
| [FooterArtifact](./footerartifact/) | フッターアーティファクトを記述します。ページのフッターを設定するために使用できます。 |
| [Form](./form/) | フォームオブジェクトを表すクラスです。 |
| [Form.FlattenSettings](./form.flattensettings/) | フォーム平坦化手順の設定を記述するクラスです。 |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | フォームは署名情報を含むことができ、署名済みまたは未署名です。ビューアでのフォームの表示は、フォームが署名されているかどうかに依存する必要がある場合があります。この列挙体は、署名に関してフォームタイプの変換中に使用できる可能なレンダリングモードを列挙します。 |
| [FormattedFragment](./formattedfragment/) | 抽象的な書式化フラグメントを表します。 |
| [FreeTextAnnotation](./freetextannotation/) | ページ上に直接テキストを表示するフリーテキスト注釈を表します。通常のテキスト注釈とは異なり、フリーテキスト注釈には開閉状態がなく、ポップアップウィンドウで表示される代わりにテキストは常に表示されます。 |
| [GoToAction](./gotoaction/) | 指定された宛先（ページ、位置、拡大率）にビューを変更する GoTo アクションを表します。 |
| [GoToRemoteAction](./gotoremoteaction/) | 通常の GoTo アクションと似ていますが、現在のファイルではなく別の PDF ファイルの宛先へジャンプするリモート GoTo アクションを表します。 |
| [GoToURIAction](./gotouriaction/) | URI を解決する URI アクションを表します。 |
| [GraphInfo](./graphinfo/) | グラフィック情報を表します。 |
| [Group](./group/) | 透過イメージングモデルで使用するページのページグループの属性を指定するグループ属性クラスです。 |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | ヘッダーアーティファクトを記述するクラスです。このアーティファクトはページの見出しを設定するために使用できます。 |
| [HeaderFooter](./headerfooter/) | ヘッダーまたはフッターの PDF ページを表すクラスです。 |
| [Heading](./heading/) | 見出しを表します。 |
| [HideAction](./hideaction/) | Hidden フラグを設定またはクリアすることで、画面上の1つ以上の注釈を非表示または表示する Hide アクションを表します。 |
| [HighlightAnnotation](./highlightannotation/) | 文書内のテキスト範囲をハイライトするハイライト注釈を表します。 |
| [HtmlFragment](./htmlfragment/) | HTML フラグメントを表します。 |
| [HtmlLoadOptions](./htmlloadoptions/) | HTML ファイルを PDF 文書に読み込み/インポートするためのオプションを表します。 |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Binary Flag は、他のオプションと組み合わせてページのサイズとレイアウトを決定するフラグを指定します。 |
| [HtmlSaveOptions](./htmlsaveoptions/) | HTML形式へのエクスポート用の保存オプション |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | この列挙体は変換中の可能なアンチエイリアス手法を説明します |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | このクラスは、PDFからHTML形式への変換中にCSSをカスタム保存するために関連するデータの集合を表します |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | このプロパティには、PDFからHTMLへの変換中に作成されたCSSの一部の処理や保存を実装するカスタム戦略を割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコード内で行う必要があります |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | このプロパティには、生成されたHTMLドキュメントで参照されるCSSのURL作成を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。たとえば、HTMLで参照されるCSSを "otherPage.ASPX?CssID=zjjkklj" のようにしたい場合、そのようなカスタム戦略は "otherPage.ASPX?CssID=zjjkklj" を返す必要があります |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | 変換ツールからカスタムコードへのリクエストに関連し、対象CSSの望ましいURL（またはURLテンプレート）を取得することを目的としたデータの集合を表します |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | この列挙体はエンコーディングロジックを調整する規則を定義します |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | 保存されたPDFで参照されるフォントの保存に使用できるモードを列挙します |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | このクラスは、PDFからHTMLへの変換中に外部リソース画像ファイルの保存に関連するデータの集合を表します |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | PDFからHTMLへの変換中に外部リソースとして保存できる画像ファイルの可能なタイプを列挙します |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | 作成されたHTMLに特定の要件がある場合があります。この列挙体は、PDFからHTMLへの変換中にそのような特定の要件に合わせるために使用できるHTML準備モードを定義します |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | HtmlSaveOptions の SplitToPages プロパティが有効な場合、PDFからHTMLへの変換中に複数のHTMLファイル（変換されたページごとに1つのHTMLファイル）が作成されます。このクラスは、PDFからHTMLへの変換中に1つのHTMLページのマークアップをカスタム保存することに関連するデータの集合を表します |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | 変換結果には1つまたは複数のHTMLページ（画像やフォントなどの外部ファイルを参照できる場合もあります）が含まれる可能性があります。このプロパティには、変換中に作成されたHTMLページ（HTML自体）の処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコードで行うことができます。この場合、HTMLページのマークアップの保存に必要なすべての操作は提供されたメソッドのコード内で実行する必要があります。なぜかコンバータのコード自体で処理を行う必要がある場合は、カスタムコード内で 'CustomProcessingCancelled' フラグを 'htmlSavingInfo' パラメータの変数に設定してください。このフラグは、外部のカスタム保存コードがないかのように、コンバータ自身でそのリソースの処理に必要なすべての手順を実行するようコンバータに指示します。 |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | 画像が属する可能性のある親（HTMLページまたはSVG親画像）のタイプを列挙します |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | この列挙体はHTMLで参照されるファイルの埋め込みモードの可能な種類を列挙します。これにより、参照されたファイル（HTML、フォント、画像、CSS）がメインHTMLファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを制御できます |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | 変換されたPDFにはラスタ画像（.png、.jpeg など）が含まれることがあります。この列挙体は、PDFからHTMLへの変換中にラスタ画像をどのように処理できるかの方法を定義します |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | このプロパティには、PDFからHTMLへの変換中に抽出され外部リソース（フォントまたは画像）として保存する必要があるリソースの処理を実装するカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ストリームやディスクへの保存などの処理はカスタムコードで行うことができ、カスタムコードはパス（引用符なしの任意の文字列）を返す必要があります。そのパスは、生成されたHTMLに元の画像リソースのパスの代わりに組み込まれます。この場合、画像の保存に必要なすべての操作は提供されたメソッドのコード内で実行する必要があります。なぜかコンバータのコード自体で処理を行う必要がある場合は、カスタムコード内で 'CustomProcessingCancelled' フラグを 'resourceSavingInfo' パラメータの変数に設定してください。このフラグは、外部のカスタムコードがないかのように、コンバータ自身でそのリソースの処理に必要なすべての手順を実行するようコンバータに指示します |
| [Hyperlink](./hyperlink/) | 抽象的なハイパーリンクを表します |
| [IconFit](./iconfit/) | ウィジェット注釈のアイコンが注釈矩形内でどのように表示されるかを説明します |
| [Id](./id/) | <p> ファイル識別子構造を表します。 </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | 画像を表します |
| [ImageDeleteAction](./imagedeleteaction/) | 画像オブジェクトがコレクションから削除されたときに実行されるアクションです。画像オブジェクトが削除された場合 |
| [ImagePlacement](./imageplacement/) | <p> PDF ドキュメントページに配置された画像の特性を表します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページ上の画像を検索し、可視サイズのビットマップとして画像を取得する方法を示しています。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> 画像がページに配置されると、{@code Resources} で定義された物理的な寸法とは異なる寸法を持つことがあります。オブジェクト {@code ImagePlacement} は、寸法や解像度などの情報を提供することを目的としています。 </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> 画像配置オブジェクトの吸収器オブジェクトを表します。画像の使用状況を検索し、{@code ImagePlacementAbsorber.ImagePlacements} コレクションを介して検索結果へのアクセスを提供します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページ上の画像を検索し、画像配置プロパティを取得する方法を示しています。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> {@code ImagePlacementAbsorber} オブジェクトは、画像検索シナリオで基本的に使用されます。検索が完了すると、出現箇所は {@code ImagePlacement} オブジェクトとして表され、これらは {@code ImagePlacementAbsorber.ImagePlacements} コレクションに含まれます。{@code ImagePlacement} オブジェクトは、画像配置プロパティ（寸法、解像度など）へのアクセスを提供します。 </p> 画像の正の回転は反時計回りで、ページに対しては時計回りです。ここでは、画像の回転角度を表す必要があるため、ページの角度を画像の角度から差し引きます。 |
| [ImagePlacementCollection](./imageplacementcollection/) | 画像配置コレクションを表します |
| [ImageStamp](./imagestamp/) | グラフィックスタンプを表します。 |
| [ImageType](./imagetype/) | 画像フォーマットタイプを表します。 |
| [ImportDataAction](./importdataaction/) | import-data アクションが呼び出されると、Forms Data Format (FDF) データが指定されたファイルからドキュメントのインタラクティブフォームにインポートされます。 |
| [ImportFieldsOptions](./importfieldsoptions/) | フォームフィールドのインポートオプションの基底クラスを表します。 |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | フォームフィールドを Json 形式にインポートするためのオプションを表します。{@code ImportFieldsOptions} から継承し、Json インポート用の特定オプションを追加します。 |
| [ImportOptions](./importoptions/) | ImportOptions 型は、個々のインポートオプションに対する抽象化レベルを保持します。 |
| [InkAnnotation](./inkannotation/) | 1 本以上の切れ目のあるパスで構成されたフリーハンドの「落書き」を表します。 |
| [InternalHelper](./internalhelper/) | 内部クラス |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | フォームタイプに対する操作が無効な場合にスローされる例外です。 |
| [JavascriptAction](./javascriptaction/) | JavaScript アクションを表すクラスです。 |
| [JavaScriptCollection](./javascriptcollection/) | このクラスは JavaScript のコレクションを表します。 |
| [LatexFragment](./latexfragment/) | TeX フラグメントを表します。@deprecated 代わりに TeXFragment を使用してください |
| [LatexLoadOptions](./latexloadoptions/) | PDF ドキュメントへの TeX ファイルのロード/インポートオプションを表します。@deprecated 代わりに TeXLoadOptions を使用してください。 |
| [LaTeXSaveOptions](./latexsaveoptions/) | TeX 形式へのエクスポート用保存オプションです。@deprecated 代わりに TeXSaveOptions を使用してください |
| [LaunchAction](./launchaction/) | アプリケーションを起動する、またはドキュメントを開く・印刷するランチアクションを表します。 |
| [Layer](./layer/) | PDF ページ内のレイヤーを表します。 |
| [LevelFormat](./levelformat/) | 目次のフォーマットを表します。 |
| [License](./license/) | コンポーネントのライセンス付与メソッドを提供します。この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。 License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | ライセンス情報を表します。 |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | 軽量オペレーターコレクションです。基になるコンテンツストリームが添付されていないシナリオで、結果としてオペレーターコレクションだけが必要な場合に使用することを意図しています。 |
| [LineAnnotation](./lineannotation/) | ライン注釈を表すクラスです。 |
| [LineEndingConverter](./lineendingconverter/) | LineEndingConverter クラスを表します。 |
| [LineEndingsDrawer](./lineendingsdrawer/) | 注釈のラインエンドを描画します。内部使用のみを目的とした内部クラスです。 |
| [LinkAnnotation](./linkannotation/) | 文書内の別の場所へのハイパーリンク、または実行されるアクションのいずれかを表します。 |
| [ListBoxField](./listboxfield/) | クラスは ListBox フィールドを表します。 |
| [LoadOptions](./loadoptions/) | LoadOptions 型は個々のロードオプションに対する抽象化レベルを保持します。 |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | 変換時（HTML、EPUB など）の余白領域の使用モードを表し、インポートされたフォーマットの余白使用に関する指示の処理方法を定義します。 |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | 注意！この機能は実装済みですが、サンプルドキュメントで OSHARED 層のブロッカー問題が判明したため、まだパブリック API に公開されていません。変換時のページサイズ使用モードを表します。HTML、EPUB などのフォーマットは通常フロート設計で、必要なページサイズに合わせることができます。しかし、コンテンツが水平位置やサイズを指定していて、必要なページサイズに収められない場合があります。そのような場合、（たとえばコンテンツのサイズが結果 PDF 文書の初期ページサイズに合わないとき）何をすべきかを定義できます。 |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | リソースのカスタムロードの結果 |
| [LocaleOptions](./localeoptions/) | LocaleOptions 型は Aspose.PDF のロケール設定を指定します。 |
| [LocalHyperlink](./localhyperlink/) | ローカルハイパーリンクオブジェクトを表します。 |
| [MarginInfo](./margininfo/) | このクラスはさまざまなオブジェクトの余白を表します。 |
| [MarkupAnnotation](./markupannotation/) | マークアップ注釈を表す抽象クラスです。 |
| [MarkupParagraph](./markupparagraph/) | 段落を表します。 |
| [MarkupSection](./markupsection/) | マークアップセクションを表します。これはテキストを含み、別のテキストブロックと視覚的に区切ることができるページ上の長方形領域です。 |
| [Matrix](./matrix/) | クラスは変換行列を表します。 |
| [Matrix3D](./matrix3d/) | クラスは変換行列を表します。 |
| [MdLoadOptions](./mdloadoptions/) | Markdown 形式変換のロードオプションです。 |
| [Measure](./measure/) | 測定座標系を記述するクラスです。 |
| [Measure.NumberFormat](./measure.numberformat/) | 測定の数値形式です。 |
| [Measure.NumberFormatList](./measure.numberformatlist/) | 数値形式のリストを表します。 |
| [MediaClip](./mediaclip/) | レンダリングのメディアクリップオブジェクトを記述するクラスです。 |
| [MediaClipData](./mediaclipdata/) | メディアクリップデータを記述するクラスです。 |
| [MediaClipSection](./mediaclipsection/) | このクラスはメディアクリップセクションを記述します。 |
| [MediaRendition](./mediarendition/) | メディアレンダリングを記述するクラスです。 |
| [MemoryCleaner](./memorycleaner/) | MemoryCleaner クラスを表します |
| [MemoryExtender](./memoryextender/) | MemoryExtender クラスを表します。ヒープメモリが制限されたシステムで大きなファイルを使用する場合、ディスク領域を一時的なスワップメモリとして使用できるように有効にできます。 |
| [MemoryFontSource](./memoryfontsource/) | 単一フォントファイルのソースを表します。 |
| [Metadata](./metadata/) | XMP メタデータストリームへのアクセスを提供します。 |
| [Metered](./metered/) | <p> メーターキーを設定するメソッドを提供します。 </p> <hr> この例では、メーターの公開キーと秘密キーを設定しようとします <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | .mht ファイルを PDF ドキュメントにロード/インポートするオプションを表します。 |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | XML 形式へのエクスポート用の保存オプション |
| [MovieAnnotation](./movieannotation/) | コンピュータ画面とスピーカーで表示されるアニメーション画像と音声を含むムービーアノテーションを表します。アノテーションがアクティブになると、ムービーが再生されます。 |
| [NamedAction](./namedaction/) | PDF ビューアアプリケーションがサポートすることが期待される名前付きアクションを表します。 |
| [NamedDestination](./nameddestination/) | 明示的な構文で直接定義する代わりに、宛先は名前オブジェクトまたはバイト文字列によって間接的に参照されることがあります。 |
| [Note](./note/) | このクラスはジェネレータ段落ノートを表します。 |
| [NumberField](./numberfield/) | 指定された有効文字を持つテキストフィールド @see TextBoxField |
| [NumberTree](./numbertree/) | PDF ファイルのナンバーツリー構造を表すクラス。7.9.7 Number Trees |
| [OcspSettings](./ocspsettings/) | 署名プロセス中に使用される OCSP 設定を表します。 |
| [OfdLoadOptions](./ofdloadoptions/) | OFD 形式のロードオプション。 |
| [Operator](./operator/) | 演算子を表す抽象クラス。 |
| [OperatorCollection](./operatorcollection/) | 演算子のコレクションを表すクラス |
| [OperatorSelector](./operatorselector/) | このクラスは Visitor テンプレートの考え方を用いて演算子を選択するために使用されます。 |
| [Opi](./opi/) | Open Prepress Interface (OPI) は、高解像度画像のための低解像度プレースホルダーまたはプロキシを作成するメカニズムであることを表します。 |
| [OptimizedMemoryStream](./optimizedmemorystream/) | より標準的な容量を含むことができる MemoryStream を定義します。 |
| [Option](./option/) | 選択フィールドのオプションを表すクラス。 |
| [OptionCollection](./optioncollection/) | 選択フィールドのオプションのコレクションを表すクラス。 |
| [OutlineCollection](./outlinecollection/) | ドキュメントアウトライン階層を表します。 |
| [OutlineItemCollection](./outlineitemcollection/) | PDF ドキュメントのアウトライン階層内のアウトラインエントリを表します。 |
| [Outlines](./outlines/) | アウトラインのコレクションを記述するクラス。 |
| [OutputIntent](./outputintent/) | PDF ドキュメントの色特性を、印刷される対象出力デバイスまたは製造環境の特性と一致させる出力インテントを表します。 |
| [OutputIntents](./outputintents/) | {@link OutputIntent} のコレクションを表します。 |
| [Page](./page/) | PDF ドキュメントのページを表すクラス。 |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | ヘッダーとフッターをカスタマイズする手順。 |
| [PageActionCollection](./pageactioncollection/) | このクラスはページアクションを記述します。 |
| [PageCollection](./pagecollection/) | PDF文書ページのコレクション。 |
| [PageExtensions](./pageextensions/) | Pageクラスに追加機能を提供します。 |
| [PageInfo](./pageinfo/) | pdfジェネレータ用のページ情報を表します。 |
| [PageInformationAnnotation](./pageinformationannotation/) | PDF文書内のページ情報アノテーションを表します。このアノテーションにはファイル名、ページ番号、アノテーション作成日時が含まれます。このクラスは主にPDF文書の特定ページにメタデータを追加するために使用され、追跡や参照の目的に役立ちます。例えば、印刷プロセス中にページにマークを付けたり、文書閲覧時にページに関する追加情報を提供したりすることができます。 |
| [PageLabel](./pagelabel/) | Pageラベル範囲を表すクラス。 |
| [PageLabelCollection](./pagelabelcollection/) | ページラベルコレクションを表すクラス。 |
| [PageMarkup](./pagemarkup/) | ページマークアップは {@code MarkupSection} と {@code MarkupParagraph} のコレクションで表されます。 |
| [PageNumberStamp](./pagenumberstamp/) | ページ番号スタンプを表し、ページ番号付けに使用されます。 |
| [PageSize](./pagesize/) | PDF文書内のページサイズを表すクラス。 |
| [PaginationArtifact](./paginationartifact/) | 文書内のページ付けアーティファクトの抽象基底クラスを表します。 |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> セクションや段落などのページ構造オブジェクトの吸収オブジェクトを表します。テキストのセクションと段落を検索し、テキスト座標空間でそれを記述する矩形や多角形へのアクセスを提供します。また、テキストセグメントの検索を行い、構造要素でグループ化された {@code TextFragments} コレクションを介して検索結果へのアクセスを提供します。 </p> この例は、最初の PDF 文書ページ上の各段落の最初のテキストセグメントを見つけてハイライトする方法を示しています。 <p> // Open document Document doc = new Document(\"input.pdf\"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath(\"output.pdf\")); </p> <hr> 検索が完了すると {@code ParagraphAbsorber.PageMarkups} コレクションには {@code MarkupSection} と {@code MarkupParagraph} のコレクションでページ構造を表す {@code PageMarkup} オブジェクトが含まれます。 {@code TextFragment} オブジェクトは検索対象テキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更が可能です。 |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) |  {@link ParagraphAbsorber} のオプションを表します。 |
| [Paragraphs](./paragraphs/) | このクラスは段落コレクションを表します。 |
| [PasswordBoxField](./passwordboxfield/) | パスワード入力用テキストフィールドを記述するクラスです。 |
| [PclLoadOptions](./pclloadoptions/) | PCLファイルをPDF文書にロード（インポート）するためのオプションを表します。 |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | 変換に使用できるコンバージョンエンジンを列挙します。 |
| [PDF3DAnnotation](./pdf3dannotation/) | PDF3DAnnotation クラス。このクラスは継承できません。 @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | PDF3DArtwork クラス。 |
| [PDF3DContent](./pdf3dcontent/) | PDF3DContent クラス。 |
| [PDF3DCrossSection](./pdf3dcrosssection/) | PDF3DCrossSection クラス。 |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | PDF3DCrossSectionArray クラス。 |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | PDF3DCuttingPlaneOrientation クラス。 |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | PDF3DLightingScheme クラス。 |
| [PDF3DRenderMode](./pdf3drendermode/) | PDF3DRenderMode クラス。 |
| [PDF3DStream](./pdf3dstream/) | PDF3DStream クラス。 |
| [PDF3DView](./pdf3dview/) | クラス PDF3DView。 |
| [PDF3DViewArray](./pdf3dviewarray/) | クラス PDF3DViewArray。 |
| [PdfAction](./pdfaction/) | PDF ドキュメント内のアクションを表します |
| [PdfActionCollection](./pdfactioncollection/) | クラスはアクションのリストを記述します。 |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | このクラスは、TrueType シンボリックフォントに複数のエンコーディングがある場合のエンコーディングデータコピー処理を調整するために使用できるルールを記述します。PDF/A 形式に変換した後、一部の PDF ドキュメントで「シンボリック TrueType フォントの cmap に複数のエンコーディングが存在します」というエラーが発生することがあります。このエラーの原因は何でしょうか？すべての TrueType シンボリックフォントは、内部データに特別なテーブル「cmap」を持っています。このテーブルは文字コードをグリフインデックスにマッピングします。このテーブルには、使用されるエンコーディングを記述した異なるエンコーディングサブテーブルが含まれることがあります。cmap テーブルに関する詳細情報は https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html を参照してください。通常、cmap テーブルには複数のエンコーディングサブテーブルが含まれますが、PDF/A 標準では、このフォントに対して PDF/A ドキュメント内で残すエンコーディングサブテーブルは 1 つだけであるか、フォントのサブテーブルの中に (3,0) エンコーディングサブテーブルが存在することが要求されます。ここでの重要な質問は、別のサブテーブルからどのデータを取得して宛先エンコーディングテーブル (3,0) にコピーすべきか、ということです。大多数のフォントは「整形式」の cmap テーブルを持ち、すべてのエンコーディングサブテーブルが他のサブテーブルと完全に一致しています。しかし、一部のフォントでは衝突が発生する cmap テーブルがあり、例えばあるサブテーブルが Unicode 100 に対してグリフインデックス 100 を持ち、別のサブテーブルが同じ Unicode 100 に対してグリフインデックス 200 を持つ場合があります。この問題を解決するには特別な戦略が必要です。デフォルトでは以下の戦略が使用されます：mac サブテーブル (1,0) が検索されます。このテーブルが見つかった場合、宛先テーブル (3,0) を埋めるためにこのデータのみが使用されます。mac サブテーブルが見つからない場合、(3,0) を除くすべてのサブテーブルが順に走査され、宛先 (3,0) サブテーブルにデータをコピーするために使用されます。また、各 Unicode（Unicode, グリフインデックス）のマッピングは、宛先テーブルに現在その Unicode が存在しない場合にのみコピーされます。したがって、例えば最初のサブテーブルが Unicode 100 に対してグリフインデックス 100 を持ち、次のサブテーブルが同じ Unicode 100 に対してグリフインデックス 200 を持つ場合、最初のサブテーブル（unicode=100、glyph index=100）のデータのみがコピーされます。このように、前のサブテーブルが次のサブテーブルよりも優先されます。このクラス { PdfASymbolicFontEncodingStrategy } のプロパティは、デフォルトの動作を調整するのに役立ちます。型が { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType } のプロパティ {PreferredCmapEncodingTable}（{ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable } / { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable }）が設定されている場合、mac サブテーブル (1,0) よりも優先して該当サブテーブルが使用されます。列挙型 {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} の値 'MacTable' は、この場合意味がなく、デフォルトで使用される mac サブテーブル (1,0) と同じものを指しています。プロパティ {CmapEncodingTablesPriorityQueue}（{ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue } / { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue }）は、すべてのサブテーブルに対する優先順位を破棄します。このプロパティが設定されている場合、宣言されたキューに含まれるサブテーブルのみが指定された順序で使用されます。指定されたサブテーブルが見つからない場合、上記で説明したデフォルトのすべてのサブテーブルの走査とコピー戦略が使用されます。オブジェクト { PdfASymbolicFontEncodingStrategy.QueueItem } は使用されるエンコーディングサブテーブルを指定します。このサブテーブルは、メンバー (PlatformID, PlatformSpecificId) の組み合わせまたは { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType } 列挙型を使用して設定できます。フォントに (3,0) サブテーブルがない場合、PDF/A 互換性を保つために別のサブテーブルが使用されます。使用するサブテーブルの選択は前述のルールに従って行われ、{@code PreferredCmapEncodingTable}（{ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable } / {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}）および {@code CmapEncodingTablesPriorityQueue}（{ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue } / { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}）プロパティが結果のサブテーブルを決定するために使用されます。フォントが要求されたサブテーブルを持たない場合は、存在する任意のサブテーブルが使用されます。 |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | エンコーディングサブテーブルを指定します。各エンコーディングサブテーブルはパラメータ (PlatformID, PlatformSpecificID) のユニークな組み合わせを持ちます。列挙型 {@code CMapEncodingTableType} とプロパティ {@code CMapEncodingTable} は、必要なエンコーディングサブテーブルの設定を容易にするために実装されました。 |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | 既知のエンコーディングサブテーブルのセットを宣言します |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | PDF ドキュメントの変換オプションのセットを表します |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | このクラスは、ソース PDF ドキュメントが PDF 仕様に準拠していない場合の PDF/A 変換を制御するフラグを保持します。これらのフラグを使用するとパフォーマンスが低下しますが、通常の方法でソース PDF ドキュメントを PDF/A 形式に変換できない場合に必要です。デフォルトではすべてのフラグが false に設定されています。 |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | 一部の PDF ドキュメントには、プライベートユース領域 (PUA) に属する特殊な Unicode シンボルが含まれます。詳細は https://en.wikipedia.org/wiki/Private_Use_Areas を参照してください。これらのシンボルは "Text is mapped to Unicode Private Use Area but no ActualText entry is present" という PDF/A 準拠エラーを引き起こします。この列挙型は、PUA シンボルを処理するために使用できる戦略を宣言します。 |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | 一部の文書は PDF/A 形式に変換した後、サイズが大きくなります。これらの文書のファイルサイズを削減するには、フォント削除の戦略を定義する必要があります。この列挙型は、フォント使用を最適化するために使用できる戦略を宣言します。この列挙型の各戦略は、フラグ {@code OptimizeFileSize} が設定されている場合にのみ意味があります。 |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | 文書テキストセグメントを整列させるために使用される戦略を記述します。現在は、セグメントを元の境界に復元する戦略のみがサポートされています。将来的に他の戦略が追加される可能性があります。 |
| [PdfPageStamp](./pdfpagestamp/) | クラスは、PDF ページをスタンプとして使用するスタンプを表します。 |
| [PdfSaveOptions](./pdfsaveoptions/) | PDF 形式へのエクスポート用の保存オプション |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | PdfXml 形式のロードオプション。 |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | PdfXml 形式の保存オプション。 |
| [Permissions](./permissions/) | Binary Flag この列挙体は PDF のユーザー権限を表します。 |
| [PKCS1](./pkcs1/) | PKCS#1 標準に関する署名オブジェクトを表します。署名には RSA 暗号アルゴリズムと SHA-1 ダイジェスト方式が使用されます。 |
| [PKCS7](./pkcs7/) | PKCS#7 仕様（Internet RFC 2315、PKCS #7: Cryptographic Message Syntax、バージョン 1.5）に準拠した PKCS#7 オブジェクトを表します。文書のバイト範囲の SHA1 ダイジェストが PKCS#7 SignedData フィールドにカプセル化されます。 |
| [PKCS7Detached](./pkcs7detached/) | PKCS#7 仕様（Internet RFC 2315、PKCS #7: Cryptographic Message Syntax、バージョン 1.5）に準拠した PKCS#7 オブジェクトを表します。文書のバイト範囲に対する元の署名メッセージダイジェストが通常の PKCS#7 SignedData フィールドとして組み込まれます。データは PKCS#7 SignedData フィールドにカプセル化されません。 |
| [Point](./point/) | 小数座標を持つ点を表します。 |
| [Point3D](./point3d/) | 小数座標を持つ点を表します。 |
| [PolyAnnotation](./polyannotation/) | ポリ注釈用の抽象基底クラスです。 |
| [PolygonAnnotation](./polygonannotation/) | 多角形注釈を表すクラスです。 |
| [PolylineAnnotation](./polylineannotation/) | ポリゴンに似ていますが、最初と最後の頂点が暗黙的に接続されないポリライン注釈を表します。 |
| [PopupAnnotation](./popupannotation/) | テキストを入力・編集するためのポップアップウィンドウに表示するポップアップ注釈を表します。 |
| [Position](./position/) | 位置オブジェクトを表します。 |
| [PptxSaveOptions](./pptxsaveoptions/) | SVG 形式へのエクスポート用保存オプションです。 |
| [PrintController](./printcontroller/) | 印刷コントローラを表します。 |
| [PrintDuplex](./printduplex/) | 印刷ダイアログからファイルを印刷する際に使用する用紙処理オプションです。 |
| [PrinterMarkAnnotation](./printermarkannotation/) | プリンターマーク注釈を表す抽象クラスです。 |
| [PrinterMarksKind](./printermarkskind/) | 文書に追加されるプリンターのマークの種類を指定します。この列挙体には {@link FlagsAttribute} 属性があり、メンバー値をビット単位で組み合わせることができます。 |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | {@link PrinterMarksKind} 列挙体の拡張メソッドを提供します。 |
| [PrintScaling](./printscaling/) | この文書の印刷ダイアログが表示される際に選択されるページ拡大縮小オプションです。 |
| [ProgressEventType](./progresseventtype/) | この列挙体は変換中に発生し得る可能な進行状況イベントタイプを説明します。 |
| [PsLoadOptions](./psloadoptions/) | .mht ファイルを PDF ドキュメントにロード/インポートするオプションを表します。 |
| [PsSaveOptions](./pssaveoptions/) | PS（PostScript）または EPS 形式へのエクスポート用保存オプションです。 |
| [RadioButtonField](./radiobuttonfield/) | ラジオボタン フィールドを表すクラスです。 |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | RadioButton フィールドの項目を表すクラスです。 |
| [Rectangle](./rectangle/) | 矩形を表すクラスです。 |
| [Redaction](./redaction/) | 内部使用のみです @author User |
| [RedactionAnnotation](./redactionannotation/) | Redact 注釈を表します。 |
| [RegexManager](./regexmanager/) | 構成可能なタイムアウト設定を備えた正規表現操作用ラッパーを提供します。 |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | 登録マーク注釈を表します。登録マークは、印刷プロセス中に色の正確な位置合わせを保証するために印刷版やスクリーンに追加されるシンボルです。 |
| [RenderingOptions](./renderingoptions/) | レンダリングオプションを表します |
| [RenderModeType](./rendermodetype/) | 列挙体 RenderModeType: レンダーモードの種類の集合 |
| [Rendition](./rendition/) | RendtionAnnotation のレンディションオブジェクトを記述するクラスです。 |
| [RenditionAction](./renditionaction/) | マルチメディアコンテンツの再生を制御するレンディションアクションです。 |
| [RenditionOperation](./renditionoperation/) | アクションがトリガーされたときに実行される操作です。 |
| [RenditionType](./renditiontype/) | Rendition の可能なタイプを記述する列挙体です。 |
| [Resources](./resources/) | ページリソースを表すクラスです。 |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | いくつかの値を持つ ExtGStates を表します。 |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | RGB からデバイスグレイカラースペースへの変換戦略を表します。 |
| [RichMediaAnnotation](./richmediaannotation/) | PDF ドキュメントにビデオ/オーディオデータを埋め込むことを可能にする RichMediaAnnotation を記述するクラスです。 |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | 注釈を有効化するイベントです。 |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | マルチメディアのタイプです。 |
| [RichTextBoxField](./richtextboxfield/) | リッチテキストエディタコンポーネントを記述するクラスです。 |
| [RichTextFontStyles](./richtextfontstyles/) | RichText 内のテキストフラグメントのスタイリングオプションです。 |
| [RootElement](./rootelement/) | ルート構造要素です。 |
| [Row](./row/) | テーブルの行を表します。 |
| [Rows](./rows/) | テーブルの行コレクションを表します。 |
| [RtfLoadOptions](./rtfloadoptions/) | RTF 形式のロードオプションです。 |
| [SaveOptions](./saveoptions/) | SaveOptions 型は個々の保存オプションに対する抽象化レベルを保持します。 |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | このクラスのインスタンスは、結果ドキュメント上に描画できる境界に関する情報を表します。 |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | 境界の一部（上、下、左側または右側）に関する情報を表します。 |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | このクラスのインスタンスは、結果ドキュメント上に描画できるページ余白に関する情報を表します。 |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | 余白の一部（上、下、左側または右側）に関する情報を表します。 |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | このクラスは、PDF を他の形式（例：HTML）に変換する際に発生する外部リソースファイルの保存に関連するデータの集合を表します。 |
| [ScalingMode](./scalingmode/) | 使用すべきスケーリングのタイプ。 |
| [ScalingReason](./scalingreason/) | アイコンが注釈矩形内でスケーリングされる条件。 |
| [ScreenAnnotation](./screenannotation/) | メディアクリップを再生できるページ上の領域を指定するスクリーン注釈。 |
| [SelectorRendition](./selectorrendition/) | セレクタのレンダリングを記述するクラス。 |
| [Signature](./signature/) | PDF 文書内の署名オブジェクトを表す抽象クラスです。署名は署名オブジェクトの値を持つフィールドであり、後者は文書の有効性を検証するために使用されるデータを含みます。 |
| [SignatureCustomAppearance](./signaturecustomappearance/) | 署名のカスタム外観オブジェクトを表す抽象クラスです。 |
| [SignatureField](./signaturefield/) | 署名フォームフィールドを表します。 |
| [SignHash](./signhash/) | ドキュメントハッシュにカスタム署名を行うためのデリゲート (ベータ)。 |
| [SoundAnnotation](./soundannotation/) | コンピュータのマイクで録音された音声またはファイルからインポートされた音声を含むサウンド注釈を表します。 |
| [SoundData](./sounddata/) | 注釈がアクティブになったときに再生される音声を定義するサウンドデータを表します。 |
| [SoundEncoding](./soundencoding/) | サンプルデータのエンコーディング形式。 |
| [SoundIcon](./soundicon/) | 注釈の表示に使用されるアイコンを列挙します。 |
| [SoundIconConverter](./soundiconconverter/) | SoundIconConverter クラスを表します。 |
| [SoundSampleData](./soundsampledata/) | サウンドオブジェクトに固有の追加エントリを表します（セクション 9.2 PDF1-7）。 |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | サウンドサンプルデータのエンコーディング形式。 |
| [SquareAnnotation](./squareannotation/) | 四角形注釈を表すクラスです。 |
| [SquigglyAnnotation](./squigglyannotation/) | 文書のテキストにジグザグの下線として表示されるスキギィ注釈を表します。 |
| [Stamp](./stamp/) | さまざまな種類のスタンプを表す抽象クラスです。 |
| [StampAnnotation](./stampannotation/) | <p> ゴムスタンプ注釈を表します。このタイプの注釈は、ページにゴムスタンプで押されたかのように見えるテキストまたはグラフィックを表示します。 </p> <hr> <pre> 次のコードスニペットは、最初の PDF 文書ページに 2 つのスタンプを追加する方法を示しています。入力文書は inFile から取得され、変更は outFile に保存されます。最初のスタンプはアイコン NotForPublicRelease を使用し、2 番目のスタンプは rubber.jpg の画像を使用します。 Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream(\"rubber.jpg\", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | StampIconConverter クラスを表します。 |
| [StrikeOutAnnotation](./strikeoutannotation/) | 文書のテキストに取り消し線として表示される取り消し線注釈を表します。 |
| [StructElement](./structelement/) | 一般的な構造要素です。 |
| [SubjectNameElements](./subjectnameelements/) | 署名サブジェクト文字列の要素を記述する列挙です。 |
| [SubmitFormAction](./submitformaction/) | submit-form アクションを記述するクラスです。 |
| [SvgLoadOptions](./svgloadoptions/) | PDF 文書に SVG ファイルをロード/インポートするためのオプションを表します。 |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | 変換に使用できるコンバージョンエンジンを列挙します。 |
| [SvgSaveOptions](./svgsaveoptions/) | SVG 形式へのエクスポート用保存オプションです。 |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | このクラスは、PDFからHTMLへの変換中に外部リソース画像ファイルの保存に関連するデータの集合を表します |
| [Symbology](./symbology/) | A (Barcode) シンボロジーは、特定のタイプのバーコードの技術的詳細を定義します：バーの幅、文字セット、エンコード方法、チェックサムの仕様など。 |
| [SystemFontSource](./systemfontsource/) | システムにインストールされているすべてのフォントを表します。 |
| [TabAlignmentType](./tabalignmenttype/) | タブの配置タイプを列挙します。 |
| [Table](./table/) | ページに追加できるテーブルを表します。 |
| [TableAbsorber](./tableabsorber/) | <p> テーブル要素の吸収オブジェクトを表します。検索を実行し、{@code TableAbsorber.TableList} コレクションを介して検索結果へのアクセスを提供します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテーブルを見つけ、テーブルセル内のテキストを置換する方法を示しています。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | タブリーダータイプを列挙します。 |
| [TableBroken](./tablebroken/) | テーブルの破損を列挙します。 |
| [TabOrder](./taborder/) | ページ上のタブ順序 |
| [TabStop](./tabstop/) | 段落内のカスタムタブストップ位置を表します。 |
| [TabStops](./tabstops/) | {@code TabStop} オブジェクトのコレクションを表します。 |
| [TeXFragment](./texfragment/) | LaTeX フラグメントを表します。 |
| [TeXLoadOptions](./texloadoptions/) | PDF ドキュメントに TeX ファイルをロード/インポートするためのオプションを表します。 |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | メモリから出力ストリームを取得する機能を実装します。たとえば、付随する出力（ログファイルなど）をディスクに書き込まず、後でメモリから読み取りたい場合に使用できます。 |
| [TeXSaveOptions](./texsaveoptions/) | TeX 形式へのエクスポート用保存オプション |
| [TextAbsorber](./textabsorber/) | <p> テキストの吸収オブジェクトを表します。テキスト抽出を実行し、{@code TextAbsorber.Text} オブジェクトを介して結果へのアクセスを提供します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> {@code TextAbsorber} オブジェクトは、Pdf ドキュメントまたはそのページからテキストを抽出するために使用されます。 </p> |
| [TextAnnotation](./textannotation/) | PDF ドキュメントのポイントに添付された「付箋」テキスト注釈を表します。 |
| [TextBoxField](./textboxfield/) | テキストボックスフィールドを表すクラスです。 |
| [TextBuilder](./textbuilder/) | テキストオブジェクトを Pdf ページに追加します。 |
| [TextDefaults](./textdefaults/) | テキストサブシステムのデフォルトを定義します |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | テキストサブシステムのデフォルトのタイプを指定します |
| [TextEditOptions](./texteditoptions/) | テキスト編集操作のオプションを記述します。 |
| [TextElement](./textelement/) | ドキュメント論理構造の一般的なテキスト要素です。 |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | PDF ドキュメントにテキスト抽出エラーが発生したことを説明します。 |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | テキスト抽出エラーが発生した PDF ドキュメント内の位置を表します。 |
| [TextExtractionOptions](./textextractionoptions/) | テキスト抽出オプションを表します |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | PDF ドキュメントをテキストに変換する際に使用できるさまざまなモードを定義します。 {@code TextDevice} クラスを参照してください。 |
| [TextFormattingOptions](./textformattingoptions/) | テキスト書式設定オプションを表します |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | 行間の詳細を定義します |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | 単語折り返し戦略を定義します |
| [TextFragment](./textfragment/) | <p> PDF テキストのフラグメントを表します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストとフォントを置換する方法を示します。 // Open document Document doc = new Document("input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("output.pdf"); </pre> <hr> <pre> 簡潔に言うと、{@code TextFragment} オブジェクトは {@code TextSegment} オブジェクトのリストを保持します。 詳細は次のとおりです。 {@code com.aspose.pdf} の PDF ドキュメントのテキストは、{@code TextFragment} と {@code TextSegment} の 2 つの基本オブジェクトで表現されます。 それらの違いは主にコンテキストに依存します。 以下のシナリオを考えてみましょう。 ユーザーはテキスト "hello world" を検索し、操作やプロパティ変更、参照などを行います。 Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> PDF テキストの物理的な表現は非常に複雑です。テキスト "hello world" は、いくつかの物理的に独立したテキストセグメントで構成される場合があります。Aspose.Pdf のテキストモデルは基本的に、{@code TextFragment} オブジェクトがユーザーのクエリを表す物理的 {@code TextSegment} オブジェクトの集合に対して単一の論理操作セットを提供することを示しています。テキスト検索シナリオでは、{@code TextFragment} は論理的な "hello world" テキスト表現であり、{@code TextSegment} オブジェクトのコレクションは "hello world" テキストオブジェクトを構成するすべての物理的セグメントを表します。したがって、{@code TextFragment} は論理テキスト表現に近く、{@code TextSegment} は物理テキスト表現に近いです。明らかに各 {@code TextSegment} オブジェクトはそれぞれ独自のフォント、色、位置プロパティを持つことができます。{@code TextFragment} はフォントの設定、フォントサイズの設定、フォントカラーの設定など、テキストのプロパティを簡単に変更する方法を提供します。一方、{@code TextSegment} オブジェクトは個別にアクセス可能で、ユーザーは {@code TextSegment} オブジェクトを独立して操作できます。 <p> TextFragment のプロパティを変更すると、TextFragment が集約オブジェクトであり、内部セグメントを再配置したり単一のセグメントに結合したりするため、内部 {@code Segments} コレクションが変更される可能性があることに注意してください。{@code Segments} コレクションを変更せずに保持する必要がある場合は、内部セグメントを個別に変更してください。 </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> テキストフラグメントの吸収オブジェクトを表します。テキスト検索を実行し、{@code TextFragmentAbsorber.TextFragments} コレクションを介して検索結果へのアクセスを提供します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストとフォントを置換する方法を示します。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> {@code TextFragmentAbsorber} オブジェクトは主にテキスト検索シナリオで使用されます。検索が完了すると、出現箇所は {@code TextFragmentAbsorber.TextFragments} コレクションが保持する {@code TextFragment} オブジェクトとして表現されます。{@code TextFragment} オブジェクトは検索結果のテキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。 </p> |
| [TextFragmentCollection](./textfragmentcollection/) | テキストフラグメントのコレクションを表します |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> テキストフラグメントのテキスト状態を表します。 </p> <hr> <pre> この例は、{@code TextState} オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示します。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> テキストの以下のプロパティを変更する方法を提供します：フォント（{@code TextFragmentState.Font} プロパティ）、フォントサイズ（{@code TextFragmentState.FontSize} プロパティ）、フォントスタイル（ {@code TextFragmentState.FontStyle} プロパティ）、前景色（ {@code TextFragmentState.ForegroundColor} プロパティ）、背景色（ {@code TextFragmentState.BackgroundColor} プロパティ） </p> <p> {@code TextFragmentState} プロパティを変更すると、TextFragment が集約オブジェクトであり、内部セグメントを再配置したり単一のセグメントに結合したりするため、内部 {@code TextFragment.Segments} コレクションが変更される可能性があることに注意してください。{@code TextFragment.Segments} コレクションを変更せずに保持する必要がある場合は、内部セグメントを個別に変更してください。 </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | 注釈の表示に使用されるアイコンを列挙します。 |
| [TextIconConverter](./texticonconverter/) | TextIconConverter クラスを表します |
| [TextMarkupAnnotation](./textmarkupannotation/) | テキストマークアップ注釈の抽象基底クラスです。 |
| [TextOptions](./textoptions/) | テキスト処理オプションを表します |
| [TextParagraph](./textparagraph/) | <p> テキスト段落を複数行テキストオブジェクトとして表します。 </p> <hr> <pre> この例は、テキスト段落オブジェクトを作成し、Pdf ページに追加する方法を示しています。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // テキスト段落を作成 TextParagraph paragraph = new TextParagraph(); // 段落の矩形を設定 paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // 単語折り返しオプションを設定 paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // 文字列行を追加 paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // TextBuilder を使用して段落を Pdf ページに追加 TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // Pdf ドキュメントを保存 doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | TextParagraph の背景モード |
| [TextParagraphAbsorber](./textparagraphabsorber/) | テキスト段落の吸収オブジェクトを表します。テキスト検索を実行し、検索結果へは {@code TextParagraphAbsorber.TextParagraphs} コレクションを介してアクセスできます。 |
| [TextParagraphCollection](./textparagraphcollection/) | テキスト段落コレクションを表します |
| [TextReplaceOptions](./textreplaceoptions/) | テキスト置換オプションを表します |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | テキストフラグメントを短く置換した後に実行されるアクションを決定します。None - アクションなし、置換されたテキストが行の残りと重なる可能性があります。AdjustSpaceWidth - 行長を保つために単語間のスペース幅を調整しようとします。WholeWordsHyphenation - 段落行間で単語を分配して段落の右端を保とうとします。ShiftRestOfLine - テキストの長さ変化に応じて行の残り部分をシフトし、行の長さが変わることがあります。デフォルト値は ShiftRestOfLine です。 |
| [TextSearchOptions](./textsearchoptions/) | テキスト検索オプションを表します |
| [TextSegment](./textsegment/) | <p> Pdf テキストのセグメントを表します。 </p> <hr> <pre> この例は、{@code TextSegment} オブジェクトの {@code TextState} オブジェクトを使用してテキストの色とフォントサイズを変更する方法を示しています。 // ドキュメントを開く Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // "hello world" テキストの出現をすべて検索するための TextFragmentAbsorber オブジェクトを作成 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 最初のページで吸収器を受け入れる doc.getPages().get(1).accept(absorber); // 最初のテキスト出現の最初のテキストセグメントの前景色を変更 absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // 最初のテキスト出現の最初のテキストセグメントのフォントサイズを変更 absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // ドキュメントを保存 doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> 簡単に言うと、{@code TextSegment} オブジェクトは {@code TextFragment} オブジェクトの子です。詳細: {@code Aspose.Pdf} の PDF ドキュメントのテキストは、{@code TextFragment} と {@code TextSegment} の 2 つの基本オブジェクトで表されます。両者の違いは主にコンテキストに依存します。次のシナリオを考えてみましょう。ユーザーは "hello world" テキストを検索し、プロパティを変更したり、表示したりします。 Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> 物理的に PDF テキストの表現は非常に複雑です。テキスト "hello world" はいくつかの物理的に独立したテキストセグメントで構成されることがあります。Aspose.PDF のテキストモデルは基本的に、{@code TextFragment} オブジェクトがユーザーのクエリを表す物理的 {@code TextSegment} オブジェクト集合に対して単一の論理操作セットを提供すると定義しています。テキスト検索シナリオでは、{@code TextFragment} は論理的な "hello world" テキスト表現であり、{@code TextSegment} オブジェクトコレクションは "hello world" テキストオブジェクトを構成するすべての物理セグメントを表します。したがって、{@code TextFragment} は論理テキスト表現に近く、{@code TextSegment} は物理テキスト表現に近いです。明らかに各 {@code TextSegment} オブジェクトは独自のフォント、色付け、位置プロパティを持つ可能性があります。{@code TextFragment} はフォント設定、フォントサイズ設定、フォントカラー設定など、テキストとそのプロパティを変更する簡単な方法を提供します。一方、{@code TextSegment} オブジェクトはアクセス可能で、ユーザーは {@code TextSegment} オブジェクトを個別に操作できます。 </p> |
| [TextSegmentCollection](./textsegmentcollection/) | テキストセグメントコレクションを表します |
| [TextStamp](./textstamp/) | テキストスタンプを表します。 |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | フォントに必要な文字が含まれていない場合に実行するアクション。 |
| [TextState](./textstate/) | テキストのテキスト状態を表します |
| [TextStyle](./textstyle/) | チェックボックスフィールドを表すクラス |
| [TimestampSettings](./timestampsettings/) | 署名プロセス中に使用される OCSP 設定を表します。 |
| [TocInfo](./tocinfo/) | 目次情報を表します。 |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | このクラスは、Adobe Preflight エラー "Text cannot be mapped to Unicode" を解決するために使用できる規則を記述します。 |
| [TrimMarkAnnotation](./trimmarkannotation/) | Trim Mark 注釈を表します。Trim Mark は印刷されたページの角に配置され、ページをトリミングすべき位置を示します。 |
| [TxtLoadOptions](./txtloadoptions/) | TXT から PDF への変換用ロードオプション。 |
| [UnderlineAnnotation](./underlineannotation/) | 文書のテキストに下線として表示される下線注釈を表します。 |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | このクラスは、統一された変換方式（統一内部ドキュメントモデルを使用）で保存するための保存オプションを表します。 |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | 呼び出し側が通常提供し、コンバータからの進行イベントを処理する抽象メソッドを持つクラスを表します。通常、このように提供された顧客側ハンドラは、コンソールやプログレスバーに総合的な変換進行状況を表示するために使用できます。 |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | このクラスは、外部アプリケーションで変換進行状況をエンドユーザーに表示するために使用できる変換進捗情報を表します。 |
| [WarningCallback](./warningcallback/) | ユーザーのコールバック機構サポート用インターフェイス。 |
| [WarningInfo](./warninginfo/) | 警告情報をカプセル化するための不変オブジェクト。 |
| [WarningType](./warningtype/) | / * Enum 表示された警告タイプ。 / * / |
| [Watermark](./watermark/) | ページの透かしを表します。 |
| [WatermarkAnnotation](./watermarkannotation/) | クラスは Watermark アノテーションオブジェクトを記述します。 |
| [WatermarkArtifact](./watermarkartifact/) | クラスは透かしアーティファクトを記述します。これは次のために使用できる場合があります |
| [WebHyperlink](./webhyperlink/) | ウェブハイパーリンクオブジェクトを表します。 |
| [WidgetAnnotation](./widgetannotation/) | ウィジェットアノテーションを表すクラスです。 |
| [XFA](./xfa/) | XML Forms Architecture (XFA) に関する XML フォームを表します。 |
| [XfaParserOptions](./xfaparseroptions/) | class 関連データのカプセル化を処理する |
| [XfdfReader](./xfdfreader/) | <p> XFDF フォーマットの読み取りを実行するクラスです。 </p> <hr> <p> <code> Document doc = new Document(\"example.pdf\"); InputStream xfdfStream = new FileInputStream(\"filename\"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save(\"example_out.pdf\"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | XFDF ファイル形式へのアノテーションとフィールドの書き込みメソッドを集約します |
| [XForm](./xform/) | XForm を表すクラス |
| [XFormCollection](./xformcollection/) | XFormCollection のコレクションを表すクラスです。 |
| [XImage](./ximage/) | 画像 X-Object を表すクラスです。 |
| [XImage.RawParameters](./ximage.rawparameters/) | 画像の生の XImage パラメータを表すクラスです。 |
| [XImageCollection](./ximagecollection/) | XImage コレクションを表すクラスです。 |
| [XmlLoadOptions](./xmlloadoptions/) | XML ファイルを PDF ドキュメントにロード/インポートするオプションを表します。 |
| [XmlSaveOptions](./xmlsaveoptions/) | XML 形式へのエクスポート用の保存オプション |
| [XmpField](./xmpfield/) | XMP フィールドを表します。 |
| [XmpFieldType](./xmpfieldtype/) | この列挙型は XMP フィールドのタイプを表します。 |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | プロパティカテゴリ: 内部または外部。 |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | このスキーマは構造化タイプのフィールドを記述します。PDF/A プロパティ値タイプスキーマと非常に似ていますが、プロパティの代わりに構造内のフィールドを定義します。スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/field# 必要なスキーマ名前空間プレフィックス: pdfaField。 |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | フィールド、プロパティ、値タイプインスタンスの基底クラスを表します。 |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | 単一のプロパティを記述します。スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/property# 必要なスキーマ名前空間プレフィックス: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | PDF/A-1 が提供する XMP 拡張スキーマを記述します。 |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | PDF/A-1 が提供する XMP 拡張スキーマの説明を表します。 |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | PDF/A ValueType スキーマは、XMP 2004 仕様で定義されていないすべてのプロパティ値タイプに必要です。つまり、以下のリストに含まれない値タイプです: - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/type# 必要なスキーマ名前空間プレフィックス: pdfaType |
| [XmpValue](./xmpvalue/) | XMP 値を表します |
| [XpsLoadOptions](./xpsloadoptions/) | XPS ファイルを PDF ドキュメントに読み込む/インポートするためのオプションを表します。 |
| [XpsSaveOptions](./xpssaveoptions/) | XPS 形式へのエクスポート用保存オプション |
| [XslFoLoadOptions](./xslfoloadoptions/) | XSL-FO ファイルを PDF ドキュメントに読み込む/インポートするためのオプションを表します。 |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙型は、そのような書式エラーの処理方法として可能な戦略を列挙します。 |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> 明示的なデスティネーションを表します。このデスティネーションは、座標 (left, top) がウィンドウの左上隅に位置し、ページの内容がズーム係数で拡大表示されます。left、top、または zoom のいずれかのパラメータが null の場合、そのパラメータの現在の値が変更されずに保持されます。ズーム値が 0 の場合も null と同じ意味です。 </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| 列挙型 | 説明 |
| --- | --- |
| [AFRelationship](./afrelationship/) | 列挙は関連ファイルの関係を記述します。 |
| [AnnotationState](./annotationstate/) | 元の注釈が設定できる状態の列挙です。 |
| [AnnotationStateModel](./annotationstatemodel/) | 注釈の状態に対応するステートモデルです。 |
| [AnnotationType](./annotationtype/) | 注釈タイプの列挙です。 |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | 可能なアーティファクトサブタイプの列挙です。 |
| [Artifact.ArtifactType](./artifact.artifacttype/) | 可能なアーティファクトタイプの列挙です。 |
| [BlendMode](./blendmode/) | ブレンドモードの列挙です。 |
| [BorderCornerStyle](./bordercornerstyle/) | ボーダーのコーナースタイルを列挙します。 |
| [BorderEffect](./bordereffect/) | 注釈のボーダーに適用すべき効果を記述します。 |
| [BorderStyle](./borderstyle/) | 注釈ボーダーのスタイルを記述します。 |
| [BoxStyle](./boxstyle/) | チェックボックス内のチェック描画スタイルを表します。 |
| [CapStyle](./capstyle/) | インク注釈ラインの線端スタイルです。 |
| [CaptionPosition](./captionposition/) | 注釈のキャプション位置の列挙です。 |
| [CaretSymbol](./caretsymbol/) | キャレットに関連付けられるシンボルです。 |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK カラーモデルに含まれる色です。 |
| [ColorSpace](./colorspace/) | カラースペースの列挙です。 |
| [ColorType](./colortype/) | ページ上の要素のカラータイプを指定します。 |
| [ColumnAdjustment](./columnadjustment/) | 列の調整タイプを列挙します。 |
| [ContentDisposition](./contentdisposition/) | MIME プロトコルの Content-Disposition ヘッダー。 |
| [ConvertErrorAction](./converterroraction/) | このクラスは変換エラーのアクションを表します。 |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | このアクションはソフトマスク付き画像の変換アクションを表します。 |
| [ConvertTransparencyAction](./converttransparencyaction/) | このクラスは透過変換のアクションを表します。 |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | 暗号化/復号化ルーチンで使用される暗号アルゴリズムのタイプを表します。 |
| [CryptographicStandard](./cryptographicstandard/) | / * / * この {@code Aspose.Pdf.Security } 名前空間には暗号化とデジタル署名に使用されるクラスが含まれています。 / * / |
| [DefaultState](./defaultstate/) | PDF レイヤーのデフォルト状態を表します。 |
| [DigestHashAlgorithm](./digesthashalgorithm/) | データを "hash" にマッピングするアルゴリズムのタイプを表します |
| [Direction](./direction/) | テキストの方向。 |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | この文書に付与されたアクセス許可です。有効な値は次のとおりです: 1 - 文書への変更は一切許可されず、変更があると署名が無効になります。 2 - 許可される変更はフォームへの入力、ページテンプレートのインスタンス化、署名であり、その他の変更は署名を無効にします。 3 - 許可される変更は 2 と同じに加えて、注釈の作成、削除、修正が可能で、その他の変更は署名を無効にします。 |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | .doc または .docx ファイル形式を指定できます。 |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | PDF 文書がワードプロセッシング文書に変換される方法を制御できます。結果の文書を大幅に編集する予定がない場合は RecognitionMode.Textbox モードを使用してください。テキストボックスは少量の編集であれば簡単に修正できます。出力文書のさらなる編集が必要な場合は RecognitionMode.Flow モードを使用してください。フローモードの段落やテキストラインはテキストの修正が容易ですが、サポートされていない書式設定オブジェクトは RecognitionMode.Textbox モードよりも見栄えが悪くなります。 |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | 通常は固定レイアウトの PDF ファイルが変換される際、変換エンジンはグルーピングと多層解析を実行して元の文書作者の意図を復元し、フロー レイアウトで結果を生成しようとします。このプロパティは、コンテンツ認識の望ましい方法に合わせてその変換を調整します。 |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | 明示的なデスティネーションのタイプを列挙します。 |
| [ExtendedBoolean](./extendedboolean/) | Undefined 値をサポートするブール型を表します。 |
| [ExtractImageMode](./extractimagemode/) | 文書から画像を抽出する際に使用できるさまざまなモードを定義します。 |
| [FileEncoding](./fileencoding/) | 添付ファイルのエンコーディングです。可能な値: Zip - ファイルが ZIP で圧縮されます、None - ファイルは圧縮されません。 |
| [FileIcon](./fileicon/) | 注釈の表示に使用されるアイコンです。 |
| [Fixup](./fixup/) | この列挙型は Fixup のタイプを表します。 |
| [FormType](./formtype/) | Acro Form の可能なタイプの列挙です。 |
| [FreeTextIntent](./freetextintent/) | フリーテキスト注釈の意図を列挙します。 |
| [HighlightingMode](./highlightingmode/) | 注釈のハイライトモードを列挙します。マウスボタンがアクティブ領域内で押されたり保持されたりしたときに使用される視覚効果です。 |
| [HorizontalAlignment](./horizontalalignment/) | 水平揃えを記述します。 |
| [HtmlDocumentType](./htmldocumenttype/) | HTML 文書タイプの列挙を表します。 |
| [HtmlMediaType](./htmlmediatype/) | レンダリング中に使用される可能なメディアタイプを指定します。 |
| [IconCaptionPosition](./iconcaptionposition/) | アイコンの位置を説明します。 |
| [ImageFileType](./imagefiletype/) | 画像ファイルタイプを列挙します。 |
| [ImageFilterType](./imagefiltertype/) | 画像フィルタータイプを表す列挙型です。 |
| [ImageFormat](./imageformat/) | この列挙型は画像フォーマットを表します。 |
| [ImportFormat](./importformat/) | インポート形式を指定します。 |
| [Justification](./justification/) | 注釈テキストの表示に使用される配置（揃え）形式を列挙します。 |
| [LaunchActionOperation](./launchactionoperation/) | 起動アクション実行時にドキュメントに対して実行する操作を列挙します。 |
| [LettersPositioningMethods](./letterspositioningmethods/) | 結果のHTMLで単語内の文字配置の可能なモードを列挙します。 |
| [LightingSchemeType](./lightingschemetype/) | 列挙体 LightingSchemeType: ライティングスキームタイプの集合です。 |
| [LineEnding](./lineending/) | 線を描画する際に使用されるラインエンドスタイルを列挙します。 |
| [LineIntent](./lineintent/) | ライン注釈の意図を列挙します。 |
| [LoadFormat](./loadformat/) | ロード形式を指定します。 |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | 分数値がどのように表示されるかを示す値です。 |
| [NumberingStyle](./numberingstyle/) | PageLabel クラスでサポートされるページ番号付けスタイルの列挙です。 |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | シークに使用するストリーム内の位置を指定します。 |
| [PageCoordinateType](./pagecoordinatetype/) | ページ座標タイプを説明します。MediaBox = 0、CropBox = 1 |
| [PageLayout](./pagelayout/) | ページレイアウトを説明します。 |
| [PageMode](./pagemode/) | クラスはドキュメントページで使用されるコンポーネントを説明します。 |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | ページ上の要素の位置を決定するバリアントを指定します。 |
| [PasswordType](./passwordtype/) | この列挙型はパスワードで保護された PDF ドキュメントで使用される既知のパスワードタイプを表します。 |
| [PDF3DActivation](./pdf3dactivation/) | 列挙体 PDF3DActivation: 3D 注釈のアクティベーションモードの集合です。 |
| [PdfFormat](./pdfformat/) | このクラスは PDF フォーマットを表します。 |
| [PdfVersion](./pdfversion/) | この列挙型は PDF ファイルのバージョンを表します。 |
| [PolyIntent](./polyintent/) | ポリゴンまたはポリライン注釈の意図を列挙します。 |
| [PredefinedAction](./predefinedaction/) | PDF ファイルからトリガー可能なさまざまなアクションを定義します。 |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | ページの隅にあるマークの位置を表します。 |
| [PrinterMarkSidePosition](./printermarksideposition/) | ページ上のレジストレーションマークの位置を表します。 |
| [ReplyType](./replytype/) | アノテーションと InReplyTo で指定されたものとの間の関係（"reply type"）の種類を列挙します。 |
| [ReturnAction](./returnaction/) | この列挙は {@code IWarningCallback.Warning(WarningInfo)} メソッドを呼び出す場合のプログラムワークフローアクションを表します。 |
| [Rotation](./rotation/) | 可能な回転値の列挙です。 |
| [SaveFormat](./saveformat/) | 形式を指定します |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | 結果ドキュメントで境界線やその他の線を描画するために使用できる線種を表します。 |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | 保存された外部リソースの可能なタイプを列挙します。 |
| [StampIcon](./stampicon/) | 注釈の表示に使用されるアイコンを列挙します。 |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | PDF から SVG への変換中に外部リソースとして保存できる画像ファイルの可能なタイプを列挙します。 |
| [TextAlignment](./textalignment/) | アノテーション内のテキストの配置です。 |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | クリッピングパスの処理モード |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | フォント置換の動作です。 |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | 言語変換モード |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | フォントに必要な文字が含まれていない場合に実行するアクション |
| [TextRenderingMode](./textrenderingmode/) | テキストレンダリングモード（Tmode）は、テキストを表示する際にグリフのアウトラインをストローク、塗りつぶし、クリッピング境界として使用するか、またはその3つの組み合わせのいずれかになるかを決定します。 |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | テキストのフォントサイズを、包含領域内に収まるように調整するポリシーを指定します。 |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | テキスト置換操作が適用される範囲です。デフォルトは REPLACE_FIRST です。この廃止されたオプションは互換性のために残されています。PdfContentEditor に影響し、TextFragmentAbsorber には影響しません。 |
| [VerticalAlignment](./verticalalignment/) | 可能な垂直配置値の列挙です。 |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
