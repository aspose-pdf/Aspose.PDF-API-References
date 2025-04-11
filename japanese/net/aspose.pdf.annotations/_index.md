---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations 名前空間は、ユーザーが文書と相互作用できる手段を提供するインタラクティブな機能として伝統的に呼ばれるさまざまな種類のアクション、宛先、およびその他の機能を操作するためのクラスを提供します。
type: docs
weight: 50
url: /ja/net/aspose.pdf.annotations/
---
**Aspose.Pdf.Annotations** 名前空間は、ユーザーが文書と相互作用できる手段を提供するインタラクティブな機能として伝統的に呼ばれるさまざまな種類のアクション、宛先、およびその他の機能を操作するためのクラスを提供します。

## クラス

| クラス | 説明 |
| --- | --- |
| [ActionCollection](./actioncollection/) | アクションのコレクション |
| [Annotation](./annotation/) | 注釈オブジェクトを表すクラス。 |
| [AnnotationActionCollection](./annotationactioncollection/) | 注釈アクションのコレクションを表します。 |
| [AnnotationCollection](./annotationcollection/) | 注釈コレクションを表すクラス。 |
| [AnnotationSelector](./annotationselector/) | このクラスは、Visitor テンプレートのアイデアを使用して注釈を選択するために使用されます。 |
| [AppearanceDictionary](./appearancedictionary/) | 注釈がページ上で視覚的にどのように表示されるかを指定する注釈外観辞書。 |
| [BleedMarkAnnotation](./bleedmarkannotation/) | ブリードマーク注釈を表します。 |
| [Border](./border/) | 注釈の境界の特性を表すクラス。 |
| [CaretAnnotation](./caretannotation/) | キャレット注釈を表すクラス。 |
| [Characteristics](./characteristics/) | 注釈の特性を表します |
| [CircleAnnotation](./circleannotation/) | 円注釈を表すクラス。 |
| [ColorBarAnnotation](./colorbarannotation/) | ColorBarAnnotation 注釈を表すクラス。プロパティ Color は無視され、代わりに ColorsOfCMYK 色が使用されます。作成時に、幅と高さの比率が注釈の向きを決定します - 水平または垂直。次に、注釈の矩形が TrimBox の外にあるかどうかを確認し、そうでない場合は、注釈の向きを考慮して TrimBox の外の最も近い位置に移動します。注釈が TrimBox の外に収まるように幅（高さ）を減らすことができます。レイアウトのためのスペースがない場合、幅/高さをゼロに設定できます（この場合、注釈はページに存在しますが表示されません）。 |
| [CommonFigureAnnotation](./commonfigureannotation/) | 共通の図形注釈を表す抽象クラス。 |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | 印刷されたページの隅に配置される注釈タイプを表します。 |
| [CustomExplicitDestination](./customexplicitdestination/) | カスタム明示的宛先を表します。 |
| [Dash](./dash/) | 線のダッシュパターンを表すクラス。 |
| [DefaultAppearance](./defaultappearance/) | フィールドのデフォルトの外観（フォント、テキストサイズ、色）を説明します。 |
| [DocumentActionCollection](./documentactioncollection/) | 文書に対して実行されるアクションを説明するクラス |
| [ExplicitDestination](./explicitdestination/) | PDF 文書内の明示的な宛先の基底クラスを表します。 |
| [FdfReader](./fdfreader/) | FDF 形式の読み取りを行うクラス。 |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | ファイル添付注釈を説明するクラス。 |
| [FitBExplicitDestination](./fitbexplicitdestination/) | ページの内容がウィンドウ内に完全に収まるように拡大表示される明示的な宛先を表します。必要な水平方向および垂直方向の拡大率が異なる場合は、2つのうち小さい方を使用し、他の次元でウィンドウ内にバウンディングボックスを中央に配置します。 |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | ページの垂直座標の上部がウィンドウの上端に位置し、ページの内容がウィンドウ内にバウンディングボックスの全幅を収めるのに十分な拡大率で拡大表示される明示的な宛先を表します。上部の null 値は、そのパラメータの現在の値を変更せずに保持することを指定します。 |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | ページの水平座標の左側がウィンドウの左端に位置し、ページの内容がウィンドウ内にバウンディングボックスの全高を収めるのに十分な拡大率で拡大表示される明示的な宛先を表します。左側の null 値は、そのパラメータの現在の値を変更せずに保持することを指定します。 |
| [FitExplicitDestination](./fitexplicitdestination/) | ページの内容がウィンドウ内に完全に収まるように拡大表示される明示的な宛先を表します。必要な水平方向および垂直方向の拡大率が異なる場合は、2つのうち小さい方を使用し、他の次元でページをウィンドウ内に中央に配置します。 |
| [FitHExplicitDestination](./fithexplicitdestination/) | ページの垂直座標の上部がウィンドウの上端に位置し、ページの内容がウィンドウ内にページの全幅を収めるのに十分な拡大率で拡大表示される明示的な宛先を表します。上部の null 値は、そのパラメータの現在の値を変更せずに保持することを指定します。 |
| [FitRExplicitDestination](./fitrexplicitdestination/) | ページの内容が指定された座標の左、下、右、上によって指定された矩形に完全に収まるように拡大表示される明示的な宛先を表します。必要な水平方向および垂直方向の拡大率が異なる場合は、2つのうち小さい方を使用し、他の次元で矩形をウィンドウ内に中央に配置します。パラメータのいずれかの null 値は予測不可能な動作を引き起こす可能性があります。 |
| [FitVExplicitDestination](./fitvexplicitdestination/) | ページの水平座標の左側がウィンドウの左端に位置し、ページの内容がウィンドウ内にページの全高を収めるのに十分な拡大率で拡大表示される明示的な宛先を表します。左側の null 値は、そのパラメータの現在の値を変更せずに保持することを指定します。 |
| [FixedPrint](./fixedprint/) | ウォーターマーク注釈の固定印刷データを表します。 |
| [FreeTextAnnotation](./freetextannotation/) | ページ上に直接テキストを表示する自由テキスト注釈を表します。通常のテキスト注釈とは異なり、自由テキスト注釈にはオープンまたはクローズ状態がなく、ポップアップウィンドウに表示されるのではなく、テキストは常に表示されます。 |
| [GoToAction](./gotoaction/) | 指定された宛先（ページ、位置、および拡大率）にビューを変更する移動アクションを表します。 |
| [GoToRemoteAction](./gotoremoteaction/) | 通常の移動アクションに似ていますが、現在のファイルではなく別の PDF ファイルの宛先にジャンプするリモート移動アクションを表します。 |
| [GoToURIAction](./gotouriaction/) | URI を解決する URI アクションを表します。 |
| [HideAction](./hideaction/) | Hidden フラグを設定またはクリアすることによって、画面上の 1 つまたは複数の注釈を隠したり表示したりする隠すアクションを表します。 |
| [HighlightAnnotation](./highlightannotation/) | 文書内のテキストの範囲をハイライトするハイライト注釈を表します。 |
| [ImportDataAction](./importdataaction/) | インポートデータアクションが呼び出されると、Forms Data Format (FDF) データが指定されたファイルから文書のインタラクティブフォームにインポートされます。 |
| [InkAnnotation](./inkannotation/) | 1 つ以上の離散パスで構成された自由形式の「落書き」を表します。 |
| [JavascriptAction](./javascriptaction/) | Javascript アクションを表すクラス。 |
| [LaunchAction](./launchaction/) | アプリケーションを起動したり、文書を開いたり印刷したりする起動アクションを表します。 |
| [LineAnnotation](./lineannotation/) | 線注釈を表すクラス。 |
| [LinkAnnotation](./linkannotation/) | 文書内の他の宛先へのハイパーテキストリンクまたは実行されるアクションを表します。 |
| [MarkupAnnotation](./markupannotation/) | マークアップ注釈を表す抽象クラス。 |
| [Measure](./measure/) | 測定座標系を説明するクラス。 |
| [MediaClip](./mediaclip/) | レンダリングのメディアクリップオブジェクトを説明するクラス。 |
| [MediaClipData](./mediaclipdata/) | メディアクリップデータを説明するクラス。 |
| [MediaClipSection](./mediaclipsection/) | このクラスはメディアクリップセクションを説明します。 |
| [MediaRendition](./mediarendition/) | メディアレンディションを説明するクラス。 |
| [MovieAnnotation](./movieannotation/) | コンピュータの画面とスピーカーで表示されるアニメーショングラフィックスと音声を含む映画注釈を表します。注釈がアクティブ化されると、映画が再生されます。 |
| [NamedAction](./namedaction/) | PDF ビューアアプリケーションがサポートすることが期待される名前付きアクションを表します。 |
| [NamedDestination](./nameddestination/) | 明示的な構文で直接定義されるのではなく、名前オブジェクトまたはバイト文字列によって間接的に参照される宛先。 |
| [PageInformationAnnotation](./pageinformationannotation/) | PDF 文書内のページ情報注釈を表します。この注釈には、ファイル名、ページ番号、および注釈作成の日付と時刻が含まれます。 |
| [PDF3DAnnotation](./pdf3dannotation/) | クラス PDF3DAnnotation。このクラスは継承できません。 |
| [PDF3DArtwork](./pdf3dartwork/) | クラス PDF3DArtwork。 |
| [PDF3DContent](./pdf3dcontent/) | クラス PDF3DContent。 |
| [PDF3DCrossSection](./pdf3dcrosssection/) | クラス PDF3DCrossSection。 |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | クラス PDF3DCrossSectionArray。 |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | クラス PDF3DCuttingPlaneOrientation。 |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | クラス PDF3DLightingScheme。 |
| [PDF3DRenderMode](./pdf3drendermode/) | クラス PDF3DRenderMode。 |
| [PDF3DStream](./pdf3dstream/) | クラス PDF3DStream。 |
| [PDF3DView](./pdf3dview/) | クラス PDF3DView。 |
| [PDF3DViewArray](./pdf3dviewarray/) | クラス PDF3DViewArray。 |
| [PdfAction](./pdfaction/) | PDF 文書内のアクションを表します |
| [PdfActionCollection](./pdfactioncollection/) | アクションのリストを説明するクラス。 |
| [PolyAnnotation](./polyannotation/) | ポリ注釈の抽象基底クラス。 |
| [PolygonAnnotation](./polygonannotation/) | 多角形注釈を表すクラス。 |
| [PolylineAnnotation](./polylineannotation/) | 最初と最後の頂点が暗黙的に接続されていない多線注釈を表します。 |
| [PopupAnnotation](./popupannotation/) | 入力と編集のためにポップアップウィンドウにテキストを表示するポップアップ注釈を表します。 |
| [PrinterMarkAnnotation](./printermarkannotation/) | プリンターマーク注釈を表す抽象クラス。 |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/) 列挙型の拡張メソッドを提供します。 |
| [RedactionAnnotation](./redactionannotation/) | レダクション注釈を表します。 |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | 登録マーク注釈を表します。 |
| [Rendition](./rendition/) | RendtionAnnotation のレンディションオブジェクトを説明するクラス。 |
| [RenditionAction](./renditionaction/) | マルチメディアコンテンツの再生を制御するレンディションアクション。 |
| [RichMediaAnnotation](./richmediaannotation/) | PDF 文書にビデオ/音声データを埋め込むことを可能にする RichMediaAnnotation を説明するクラス。 |
| [ScreenAnnotation](./screenannotation/) | メディアクリップが再生されるページの領域を指定する画面注釈。 |
| [SelectorRendition](./selectorrendition/) | セレクタレンディションを説明するクラス。 |
| [SoundAnnotation](./soundannotation/) | コンピュータのマイクから録音された音声またはファイルからインポートされた音声を含む音声注釈を表します。 |
| [SoundData](./sounddata/) | 注釈がアクティブ化されたときに再生される音声を定義する音声データを表します。 |
| [SoundSampleData](./soundsampledata/) | 音声オブジェクトに特有の追加エントリを表します（セクション 9.2 PDF1-7） |
| [SquareAnnotation](./squareannotation/) | 正方形注釈を表すクラス。 |
| [SquigglyAnnotation](./squigglyannotation/) | 文書のテキストに鋸歯状の下線として表示されるスキグリー注釈を表します。 |
| [StampAnnotation](./stampannotation/) | ゴム印注釈を表します。このタイプの注釈は、ページにゴム印で押されたように見えるテキストまたはグラフィックスを表示します。 |
| [StrikeOutAnnotation](./strikeoutannotation/) | 文書のテキストに打ち消し線として表示される打ち消し線注釈を表します。 |
| [SubmitFormAction](./submitformaction/) | フォーム送信アクションを説明するクラス。 |
| [TextAnnotation](./textannotation/) | PDF 文書のポイントに添付された「付箋」のテキスト注釈を表します。 |
| [TextMarkupAnnotation](./textmarkupannotation/) | テキストマークアップ注釈の抽象基底クラス。 |
| [TextStyle](./textstyle/) | 注釈内のテキストのスタイルを表すクラス |
| [TrimMarkAnnotation](./trimmarkannotation/) | トリムマーク注釈を表します。 |
| [UnderlineAnnotation](./underlineannotation/) | 文書のテキストに下線として表示される下線注釈を表します。 |
| [WatermarkAnnotation](./watermarkannotation/) | ウォーターマーク注釈オブジェクトを説明するクラス。 |
| [WidgetAnnotation](./widgetannotation/) | ウィジェット注釈を表すクラス。 |
| [XfdfReader](./xfdfreader/) | XFDF 形式の読み取りを行うクラス。 |
| [XYZExplicitDestination](./xyzexplicitdestination/) | ウィンドウの左上隅に位置する座標 (左、上) を持ち、ページの内容が拡大率 zoom で拡大表示される明示的な宛先を表します。左、上、または zoom のいずれかのパラメータの null 値は、そのパラメータの現在の値を変更せずに保持することを指定します。zoom の値が 0 の場合、null 値と同じ意味になります。 |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | 異なる文書注釈を訪問するための Visitor を定義します。 |
| [IAppointment](./iappointment/) | アクションと宛先の一般的なインターフェースを表します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | 注釈のさまざまな特性を指定するフラグのセット。 |
| [AnnotationState](./annotationstate/) | 元の注釈が設定できる状態の列挙。 |
| [AnnotationStateModel](./annotationstatemodel/) | 注釈の状態に対応する状態モデル。 |
| [AnnotationType](./annotationtype/) | 注釈タイプの列挙。 |
| [BorderEffect](./bordereffect/) | 注釈の境界に適用される効果を説明します。 |
| [BorderStyle](./borderstyle/) | 注釈の境界のスタイルを説明します。 |
| [CapStyle](./capstyle/) | インク注釈の線の終端のスタイル。 |
| [CaptionPosition](./captionposition/) | 注釈のキャプションの配置の列挙。 |
| [CaretSymbol](./caretsymbol/) | キャレットに関連付けられるシンボル。 |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK カラーモデルに含まれる色。 |
| [ExplicitDestinationType](./explicitdestinationtype/) | 明示的な宛先のタイプを列挙します。 |
| [FileIcon](./fileicon/) | 注釈を表示する際に使用されるアイコン。 |
| [FreeTextIntent](./freetextintent/) | 自由テキスト注釈の意図を列挙します。 |
| [HighlightingMode](./highlightingmode/) | 注釈のハイライトモードを列挙し、アクティブエリア内でマウスボタンが押されたり保持されたりしているときに使用される視覚効果。 |
| [Justification](./justification/) | 注釈のテキストを表示する際に使用されるクワディング（整列）の形式を列挙します。 |
| [LaunchActionOperation](./launchactionoperation/) | 起動アクションを実行する際に文書で実行する操作を列挙します。 |
| [LightingSchemeType](./lightingschemetype/) | 照明スキームタイプのセットを定義する列挙型。 |
| [LineEnding](./lineending/) | 線を描画する際に使用される線の終端スタイルを列挙します。 |
| [LineIntent](./lineintent/) | 線注釈の意図を列挙します。 |
| [PDF3DActivation](./pdf3dactivation/) | 3D 注釈のアクティベーションモードのセットを定義する列挙型。 |
| [PolyIntent](./polyintent/) | 多角形またはポリライン注釈の意図を列挙します。 |
| [PredefinedAction](./predefinedaction/) | PDF ファイルからトリガーされるさまざまなアクションを定義します。 |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | ページの隅におけるマークの位置を表します。 |
| [PrinterMarkSidePosition](./printermarksideposition/) | ページ上の登録マークの位置を表します。 |
| [PrinterMarksKind](./printermarkskind/) | 文書に追加されるプリンターマークの種類を指定します。 |
| [RenderModeType](./rendermodetype/) | レンダーモードタイプのセットを定義する列挙型 |
| [RenditionOperation](./renditionoperation/) | アクションがトリガーされたときに実行する操作。 |
| [RenditionType](./renditiontype/) | レンディションの可能なタイプを説明する列挙型。 |
| [ReplyType](./replytype/) | 注釈と InReplyTo で指定された注釈との関係の種類（「返信タイプ」）を列挙します。 |
| [SoundEncoding](./soundencoding/) | サンプルデータのエンコーディング形式。 |
| [SoundIcon](./soundicon/) | 注釈を表示する際に使用されるアイコンを列挙します。 |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | 音声サンプルデータのエンコーディング形式。 |
| [StampIcon](./stampicon/) | 注釈を表示する際に使用されるアイコンを列挙します。 |
| [TextIcon](./texticon/) | 注釈を表示する際に使用されるアイコンを列挙します。 |