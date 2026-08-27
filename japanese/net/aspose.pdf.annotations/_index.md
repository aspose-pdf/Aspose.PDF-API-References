---
title: "Aspose.Pdf.Annotations"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations 名前空間は、さまざまなタイプのアクション先や、従来インタラクティブと呼ばれるドキュメントのその他の機能を操作するためのクラスを提供し、ユーザーが相互にやり取りできる手段を提供します。"
type: docs
weight: 50
url: /ja/net/aspose.pdf.annotations/
---
**Aspose.Pdf.Annotations** 名前空間は、さまざまな種類のアクション、宛先、その他のドキュメント機能（従来はインタラクティブと呼ばれ、ユーザーが相互作用できる手段）を扱うためのクラスを提供します。

## クラス

| クラス | 説明 |
| --- | --- |
| [ActionCollection](./actioncollection/) | アクションのコレクション |
| [Annotation](./annotation/) | 注釈オブジェクトを表すクラスです。 |
| [AnnotationActionCollection](./annotationactioncollection/) | 注釈アクションのコレクションを表します。 |
| [AnnotationCollection](./annotationcollection/) | 注釈コレクションを表すクラスです。 |
| [AnnotationSelector](./annotationselector/) | このクラスは、Visitor パターンの考え方を使用して注釈を選択するために使用されます。 |
| [AppearanceDictionary](./appearancedictionary/) | ページ上で注釈が視覚的にどのように表示されるかを指定する注釈外観ディクショナリです。 |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Bleed Mark 注釈を表します。 |
| [Border](./border/) | 注釈ボーダーの特性を表すクラスです。 |
| [CaretAnnotation](./caretannotation/) | Caret 注釈を表すクラスです。 |
| [Characteristics](./characteristics/) | 注釈の特性を表します |
| [CircleAnnotation](./circleannotation/) | Circle 注釈を表すクラスです。 |
| [ColorBarAnnotation](./colorbarannotation/) | ColorBarAnnotation 注釈を表すクラスです。プロパティ Color は無視され、代わりに ColorsOfCMYK の色が使用されます。作成時に幅と高さの比率が注釈の向き（横または縦）を決定します。次に、注釈の矩形が TrimBox の外にあるか確認し、外にない場合は注釈の向きを考慮して最も近い TrimBox の外側の位置へシフトされます。幅（高さ）を縮小して注釈を TrimBox の外に収めることが可能です。レイアウトのためのスペースがない場合、幅/高さをゼロに設定できます（この場合、注釈はページに存在しますが表示されません）。 |
| [CommonFigureAnnotation](./commonfigureannotation/) | 共通の図形注釈を表す抽象クラスです。 |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | 印刷ページの角に配置される注釈タイプを表します。 |
| [CustomExplicitDestination](./customexplicitdestination/) | カスタムの明示的なデスティネーションを表します。 |
| [Dash](./dash/) | 線の破線パターンを表すクラスです。 |
| [DefaultAppearance](./defaultappearance/) | フィールドのデフォルト外観（フォント、テキストサイズ、カラー）を記述します。 |
| [DocumentActionCollection](./documentactioncollection/) | document に対して実行されるアクションを記述するクラスです。 |
| [ExplicitDestination](./explicitdestination/) | PDF document 内の明示的なデスティネーションの基底クラスを表します。 |
| [FdfReader](./fdfreader/) | FDF形式の読み取りを行うクラスです。 |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | ファイル添付 annotation を記述するクラスです。 |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Page の内容を、bounding box がウィンドウ内に水平・垂直の両方で完全に収まるように拡大表示する明示的なデスティネーションを表します。必要な水平拡大率と垂直拡大率が異なる場合は、両者の小さい方を使用し、もう一方の次元で bounding box をウィンドウの中央に配置します。 |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Page の垂直座標 top をウィンドウの上端に配置し、Page の内容を bounding box の幅全体がウィンドウ内に収まるように拡大表示する明示的なデスティネーションを表します。top が null の場合は、そのパラメータの現在の値を変更せずに保持します。 |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Page の水平座標 left をウィンドウの左端に配置し、Page の内容を bounding box の高さ全体がウィンドウ内に収まるように拡大表示する明示的なデスティネーションを表します。left が null の場合は、そのパラメータの現在の値を変更せずに保持します。 |
| [FitExplicitDestination](./fitexplicitdestination/) | Page 全体がウィンドウ内に水平・垂直の両方で完全に収まるように内容を拡大表示する明示的なデスティネーションを表します。必要な水平拡大率と垂直拡大率が異なる場合は、両者の小さい方を使用し、もう一方の次元で Page をウィンドウの中央に配置します。 |
| [FitHExplicitDestination](./fithexplicitdestination/) | Page の垂直座標 top をウィンドウの上端に配置し、Page の内容を Page 全体の幅がウィンドウ内に収まるように拡大表示する明示的なデスティネーションを表します。top が null の場合は、そのパラメータの現在の値を変更せずに保持します。 |
| [FitRExplicitDestination](./fitrexplicitdestination/) | 左、下、右、上の座標で指定された矩形がウィンドウ内に水平・垂直の両方で完全に収まるように内容を拡大表示する明示的なデスティネーションを表します。必要な水平拡大率と垂直拡大率が異なる場合は、両者の小さい方を使用し、もう一方の次元で矩形をウィンドウの中央に配置します。任意のパラメータが null の場合、予測できない動作になる可能性があります。 |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Page の水平座標 left をウィンドウの左端に配置し、Page の内容を Page 全体の高さがウィンドウ内に収まるように拡大表示する明示的なデスティネーションを表します。left が null の場合は、そのパラメータの現在の値を変更せずに保持します。 |
| [FixedPrint](./fixedprint/) | Watermark Annotation の固定印刷データを表します。 |
| [FreeTextAnnotation](./freetextannotation/) | ページ上に直接テキストを表示する free text annotation を表します。通常のテキスト annotation とは異なり、free text annotation は開閉状態がなく、ポップアップウィンドウで表示される代わりにテキストが常に可視です。 |
| [GoToAction](./gotoaction/) | 指定されたデスティネーション（ページ、位置、拡大率）にビューを変更する go-to アクションを表します。 |
| [GoToRemoteAction](./gotoremoteaction/) | 通常の go-to アクションと似ていますが、現在のファイルではなく別の PDF ファイル内のデスティネーションへジャンプする remote go-to アクションを表します。 |
| [GoToURIAction](./gotouriaction/) | URI を解決する URI アクションを表します。 |
| [HideAction](./hideaction/) | Hidden フラグを設定またはクリアすることで、画面上の1つ以上の annotation を非表示または表示する hide アクションを表します。 |
| [HighlightAnnotation](./highlightannotation/) | document 内のテキスト範囲をハイライトする highlight annotation を表します。 |
| [ImportDataAction](./importdataaction/) | インポートデータアクションが呼び出された際、Forms Data Format（FDF）データは指定されたファイルから document のインタラクティブフォームにインポートされます。 |
| [InkAnnotation](./inkannotation/) | 1つ以上の切れ目のあるパスで構成されるフリーハンドの「落書き」を表します。 |
| [JavascriptAction](./javascriptaction/) | JavaScript アクションを表すクラスです。 |
| [LaunchAction](./launchaction/) | アプリケーションを起動する、または document を開く・印刷する launch アクションを表します。 |
| [LineAnnotation](./lineannotation/) | 線 annotation を表すクラスです。 |
| [LinkAnnotation](./linkannotation/) | 文書内の別の場所へのハイパーテキストリンク、または実行されるアクションのいずれかを表します。 |
| [MarkupAnnotation](./markupannotation/) | マークアップ注釈を表す抽象クラスです。 |
| [Measure](./measure/) | 測定座標系を記述するクラスです。 |
| [MediaClip](./mediaclip/) | レンダリングのメディアクリップオブジェクトを記述するクラスです。 |
| [MediaClipData](./mediaclipdata/) | メディアクリップデータを記述するクラスです。 |
| [MediaClipSection](./mediaclipsection/) | このクラスはメディアクリップセクションを記述します。 |
| [MediaRendition](./mediarendition/) | メディアレンダリングを記述するクラスです。 |
| [MovieAnnotation](./movieannotation/) | コンピュータ画面とスピーカーを通じて表示されるアニメーション画像と音声を含むムービーannotationを表します。annotationがアクティブになると、ムービーが再生されます。 |
| [NamedAction](./namedaction/) | PDFビューアアプリケーションがサポートすると想定される名前付きアクションを表します。 |
| [NamedDestination](./nameddestination/) | 明示的な構文で直接定義する代わりに、宛先は名前オブジェクトまたはバイト文字列を使用して間接的に参照されることがあります。 |
| [PageInformationAnnotation](./pageinformationannotation/) | PDF document内のPage Information annotationを表します。このannotationにはファイル名、Page number、そして annotation creation の日時が含まれます。 |
| [PDF3DAnnotation](./pdf3dannotation/) | クラス PDF3DAnnotation。 このクラスは継承できません。 |
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
| [PdfAction](./pdfaction/) | PDF document内のActionを表します |
| [PdfActionCollection](./pdfactioncollection/) | アクションのリストを記述するクラスです。 |
| [PolyAnnotation](./polyannotation/) | ポリannotationのための抽象基底クラスです。 |
| [PolygonAnnotation](./polygonannotation/) | ポリゴン注釈を表すクラス。 |
| [PolylineAnnotation](./polylineannotation/) | ポリライン注釈はポリゴンに似ていますが、最初と最後の頂点は暗黙的に接続されません。 |
| [PopupAnnotation](./popupannotation/) | テキストの入力と編集のためにポップアップウィンドウにテキストを表示するポップアップ注釈を表します。 |
| [PrinterMarkAnnotation](./printermarkannotation/) | プリンターマーク注釈を表す抽象クラス。 |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/) 列挙体に対する拡張メソッドを提供します。 |
| [RedactionAnnotation](./redactionannotation/) | Redact 注釈を表します。 |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | 登録マーク注釈を表します。 |
| [Rendition](./rendition/) | RendtionAnnotation のレンダリングオブジェクトを記述するクラス。 |
| [RenditionAction](./renditionaction/) | マルチメディアコンテンツの再生を制御するレンディションアクション。 |
| [RichMediaAnnotation](./richmediaannotation/) | PDF ドキュメントにビデオ/オーディオ データを埋め込むことを可能にする RichMediaAnnotation を記述するクラス。 |
| [ScreenAnnotation](./screenannotation/) | メディアクリップを再生できるページ上の領域を指定するスクリーン注釈。 |
| [SelectorRendition](./selectorrendition/) | セレクターレンディションを記述するクラス。 |
| [SoundAnnotation](./soundannotation/) | コンピュータのマイクから録音した音声、またはファイルからインポートした音声を含むサウンド注釈を表します。 |
| [SoundData](./sounddata/) | 注釈がアクティブになったときに再生される音声を定義するサウンドデータを表します。 |
| [SoundSampleData](./soundsampledata/) | サウンドオブジェクトに固有の追加エントリを表します（セクション 9.2 PDF1-7）。 |
| [SquareAnnotation](./squareannotation/) | 四角形注釈を表すクラス。 |
| [SquigglyAnnotation](./squigglyannotation/) | 文書のテキストに波状の下線として表示されるスキギィ注釈を表します。 |
| [StampAnnotation](./stampannotation/) | ゴムスタンプ注釈を表します。このタイプの注釈は、ページにゴムスタンプで押されたかのように見えるテキストまたはグラフィックを表示します。 |
| [StrikeOutAnnotation](./strikeoutannotation/) | 文書のテキストに取り消し線として表示される取り消し線注釈を表します。 |
| [SubmitFormAction](./submitformaction/) | submit-form アクションを記述するクラス。 |
| [TextAnnotation](./textannotation/) | PDF ドキュメントのポイントに添付された「付箋」テキスト注釈を表します。 |
| [TextMarkupAnnotation](./textmarkupannotation/) | テキストマークアップ注釈の抽象基底クラス。 |
| [TextStyle](./textstyle/) | 注釈内のテキストのスタイルを表すクラス。 |
| [TrimMarkAnnotation](./trimmarkannotation/) | トリムマーク注釈を表します。 |
| [UnderlineAnnotation](./underlineannotation/) | 文書のテキストに下線として表示される下線注釈を表します。 |
| [WatermarkAnnotation](./watermarkannotation/) | クラスはウォーターマーク注釈オブジェクトを説明します。 |
| [WidgetAnnotation](./widgetannotation/) | ウィジェット注釈を表すクラスです。 |
| [XfdfReader](./xfdfreader/) | XFDF 形式の読み取りを行うクラスです。 |
| [XYZExplicitDestination](./xyzexplicitdestination/) | ウィンドウの左上隅に (left, top) の座標でページを表示し、ページの内容を zoom 倍率で拡大する明示的なデスティネーションを表します。left、top、または zoom のいずれかのパラメータが null の場合、そのパラメータの現在の値は変更されずに保持されます。zoom 値が 0 の場合は null と同じ意味です。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | さまざまなドキュメント注釈を訪問するための Visitor を定義します。 |
| [IAppointment](./iappointment/) | アクションとデスティネーションの一般的なインターフェイスを表します。 |
## 列挙体

| 列挙体 | 説明 |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | 注釈のさまざまな特性を指定するフラグの集合です。 |
| [AnnotationState](./annotationstate/) | 元の注釈が設定可能な状態の列挙です。 |
| [AnnotationStateModel](./annotationstatemodel/) | 注釈の状態に対応するステートモデルです。 |
| [AnnotationType](./annotationtype/) | 注釈タイプの列挙です。 |
| [BorderEffect](./bordereffect/) | 注釈の境界線に適用すべき効果を説明します。 |
| [BorderStyle](./borderstyle/) | 注釈境界線のスタイルを説明します。 |
| [CapStyle](./capstyle/) | インク注釈線の線端のスタイルです。 |
| [CaptionPosition](./captionposition/) | 注釈のキャプション位置の列挙です。 |
| [CaretSymbol](./caretsymbol/) | キャレットに関連付けられるシンボルです。 |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK カラーモデルに含まれる色です。 |
| [ExplicitDestinationType](./explicitdestinationtype/) | 明示的なデスティネーションのタイプを列挙します。 |
| [FileIcon](./fileicon/) | 注釈の表示に使用されるアイコンです。 |
| [FreeTextIntent](./freetextintent/) | フリーテキスト注釈の意図を列挙します。 |
| [HighlightingMode](./highlightingmode/) | 注釈のハイライトモードを列挙します。これは、マウスボタンがアクティブ領域内で押されたり保持されたりしたときに使用される視覚効果です。 |
| [Justification](./justification/) | 注釈テキストの表示に使用される配置（整列）の形態を列挙します。 |
| [LaunchActionOperation](./launchactionoperation/) | 起動アクション実行中にドキュメントに対して実行される操作を列挙します。 |
| [LightingSchemeType](./lightingschemetype/) | 列挙体 LightingSchemeType: ライティングスキームタイプの集合です。 |
| [LineEnding](./lineending/) | 線を描画する際に使用される線端スタイルを列挙します。 |
| [LineIntent](./lineintent/) | ライン注釈の意図を列挙します。 |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: 3D アノテーション有効化モードのセット。 |
| [PolyIntent](./polyintent/) | ポリゴンまたはポリライン アノテーションの意図を列挙します。 |
| [PredefinedAction](./predefinedaction/) | PDF ファイルからトリガーできるさまざまなアクションを定義します。 |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | ページの隅にあるマークの位置を表します。 |
| [PrinterMarkSidePosition](./printermarksideposition/) | ページ上のレジストレーション マークの位置を表します。 |
| [PrinterMarksKind](./printermarkskind/) | ドキュメントに追加されるプリンター マークのタイプを指定します。 |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: レンダーモードタイプのセット |
| [RenditionOperation](./renditionoperation/) | アクションがトリガーされたときに実行する操作です。 |
| [RenditionType](./renditiontype/) | Rendition の可能なタイプを列挙します。 |
| [ReplyType](./replytype/) | アノテーションと InReplyTo で指定されたものとの間の関係（「返信タイプ」）の種類を列挙します。 |
| [RichTextFontStyles](./richtextfontstyles/) | RichText のテキスト フラグメントのスタイル設定オプションです。 |
| [SoundEncoding](./soundencoding/) | サンプル データのエンコーディング形式です。 |
| [SoundIcon](./soundicon/) | アノテーションの表示に使用されるアイコンを列挙します。 |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | サウンド サンプル データのエンコーディング形式です。 |
| [StampIcon](./stampicon/) | アノテーションの表示に使用されるアイコンを列挙します。 |
| [TextIcon](./texticon/) | アノテーションの表示に使用されるアイコンを列挙します。 |


