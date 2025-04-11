---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Documentクラス。PDFドキュメントを表すクラス
type: docs
weight: 3780
url: /ja/net/aspose.pdf/document/
---
## Documentクラス

PDFドキュメントを表すクラス。

```csharp
public sealed class Document : IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Document](document/#constructor)() | 空のドキュメントを初期化します。 |
| [Document](document/#constructor_1)(PdfVersion) | バージョンによって空のドキュメントを初期化します。 |
| [Document](document/#constructor_2)(Stream) | *input*ストリームから新しいDocumentインスタンスを初期化します。 |
| [Document](document/#constructor_7)(string) | *filename*を使用してDocumentを初期化します。 [`Document`](./document/)と同じです。 |
| [Document](document/#constructor_4)(Stream, bool) | *input*ストリームから新しいDocumentインスタンスを初期化します。 |
| [Document](document/#constructor_3)(Stream, LoadOptions) | 必要な変換を提供してストリームから既存のドキュメントを開きます。 |
| [Document](document/#constructor_5)(Stream, string) | *input*ストリームから新しいDocumentインスタンスを初期化します。 |
| [Document](document/#constructor_9)(string, bool) | *filename*を使用してDocumentを初期化します。 [`Document`](./document/)と同じです。 |
| [Document](document/#constructor_8)(string, LoadOptions) | 必要な変換オプションを提供してファイルから既存のドキュメントを開きます。 |
| [Document](document/#constructor_10)(string, string) | 暗号化されたドキュメントで作業するための`Document`クラスの新しいインスタンスを初期化します。 |
| [Document](document/#constructor_6)(Stream, string, bool) | *input*ストリームから新しいDocumentインスタンスを初期化します。 |
| [Document](document/#constructor_11)(string, string, bool) | 暗号化されたドキュメントで作業するための`Document`クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | ドキュメントアクションを取得します。このプロパティはDocumentActionsクラスのインスタンスで、BeforClosing、BeforSavingなどのアクションを取得/設定できます。 |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | ドキュメントサイズを最適化するためにページコンテンツをマージすることを許可します。使用すると、異なるが重複したページが同じコンテンツオブジェクトを参照する場合があります。このモードは、他のページが変更されたときにページコンテンツが変更されるなどの副作用を引き起こす可能性があることに注意してください。 |
| [Background](../../aspose.pdf/document/background/) { get; set; } | ドキュメントの背景色を取得または設定します。 |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | ドキュメントのウィンドウの位置が画面の中央に配置されるかどうかを指定するフラグを取得または設定します。 |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | ドキュメントのコレクションを取得します。 |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | ドキュメントが暗号化されている場合のセキュリティ設定を取得します。ドキュメントが暗号化されていない場合、.net 1.1では対応する例外が発生し、他の.netバージョンではCryptoAlgorithmがnullになります。 |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | 目的地のコレクションを取得します。廃止予定です。NamedDestinationsを使用してください。 |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | テキストの読み取り順序を取得または設定します：L2R（左から右）またはR2L（右から左）。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | フォントに対してライセンスによって禁止されている場合、フォントに関する多くの操作を実行できません。たとえば、ライセンスルールがこのフォントの埋め込みを無効にしている場合、一部のフォントはPDFドキュメントに埋め込むことができません。このフラグは、現在のPDFドキュメント内のすべてのフォントに対するライセンス制限を無効にするために使用されます。このフラグを使用する際は注意が必要です。このフラグが設定されている場合、それを設定した人は、可能なライセンス/法律違反のすべての責任を負うことになります。したがって、彼は自己責任でそれを引き受けます。著作権法を破っていないと完全に自信がある場合にのみ、このフラグを使用することを強くお勧めします。デフォルトはfalseです。 |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | ドキュメントのウィンドウタイトルバーにドキュメントタイトルを表示するかどうかを指定するフラグを取得または設定します。 |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | 印刷ダイアログからファイルを印刷する際に使用する印刷両面モードの処理オプションを取得または設定します。 |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | ドキュメントに埋め込まれたファイルのコレクションを取得します。 |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | ドキュメントがIsEmbeddedフラグがtrueに設定されたすべての標準Type1フォントを埋め込む必要があることを宣言するプロパティです。すべてのPDFフォントは、IsEmbeddedフラグをtrueに設定することでドキュメントに埋め込むことができますが、PDF標準Type1フォントはこのルールの例外です。標準Type1フォントの埋め込みには多くの時間がかかるため、これらのフォントを埋め込むには、指定されたフォントのIsEmbeddedフラグをtrueに設定するだけでなく、ドキュメントレベルで追加のフラグ-EmbedStandardFonts = true;を設定する必要があります。このプロパティは、すべてのフォントに対して1回だけ設定できます。デフォルトはfalseです。 |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | ドキュメントが部分的にメモリからアンロードされることを可能にするフラグを取得または設定します。これによりメモリ使用量を減らすことができますが、パフォーマンスに悪影響を及ぼす可能性があります。 |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | 署名フィールドのサニタイズを管理するフラグを取得または設定します。デフォルトで有効です。 |
| [FileName](../../aspose.pdf/document/filename/) { get; } | このドキュメントを引き起こしたPDFファイルの名前 |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | ドキュメントウィンドウが最初に表示されるページに合わせてサイズ変更されるかどうかを指定するフラグを取得または設定します。 |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | IDocumentFontUtilitiesインスタンス |
| [Form](../../aspose.pdf/document/form/) { get; } | ドキュメントのAcroフォームを取得します。 |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | ドキュメントが変更を加えて保存される場合に例外をスローします。 |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | ドキュメントがアクティブなときにメニューバーを非表示にするかどうかを指定するフラグを取得または設定します。 |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | ドキュメントがアクティブなときにツールバーを非表示にするかどうかを指定するフラグを取得または設定します。 |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | ドキュメントがアクティブなときにユーザーインターフェース要素を非表示にするかどうかを指定するフラグを取得または設定します。 |
| [Id](../../aspose.pdf/document/id/) { get; } | IDを取得します。 |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | ソースファイルのエラーを無視するフラグを取得または設定します。ソースドキュメントからページが宛先ドキュメントにコピーされるとき、このフラグがfalseの場合、ソースファイル内のオブジェクトが破損しているとコピー処理は例外で停止します。例：dest.Pages.Add(src.Pages);このフラグがtrueに設定されている場合、破損したオブジェクトは空の値に置き換えられます。デフォルト：true。 |
| [Info](../../aspose.pdf/document/info/) { get; } | ドキュメント情報を取得します。 |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | ドキュメントの暗号化状態を取得します。ドキュメントが暗号化されている場合はtrueです。 |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | ドキュメントが線形化されているかどうかを示す値を取得または設定します。 |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | ドキュメントがpdfa準拠であるかどうかを取得します。 |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | ドキュメントがpdfua準拠であるかどうかを取得します。 |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | ドキュメントがpdfa準拠であるかどうかを取得または設定します。 |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | ドキュメントレベルのJavaScriptのコレクション。 |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | ドキュメントの論理構造を取得します。 |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | ドキュメントメタデータ。（PDFドキュメントには、ドキュメントのタイトル、著者、作成日、変更日などの一般情報が含まれる場合があります。このようなドキュメントに関するグローバル情報（その内容や構造とは対照的に）はメタデータと呼ばれ、外部データベースでのドキュメントのカタログ化や検索を支援することを目的としています。） |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | ドキュメント内の名前付き目的地のコレクション。 |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | フルスクリーンモードを終了したときにドキュメントを表示する方法を指定するページモードを取得または設定します。 |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | ドキュメントを開くときに実行されるアクションを取得または設定します。 |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | 最適化フラグを取得または設定します。ページがドキュメントに追加されると、結果ファイル内の同等のリソースストリームが1つのPDFオブジェクトにマージされます。このフラグが設定されていると、結果ファイルサイズを減少させることができますが、実行が遅くなり、メモリ要件が大きくなる可能性があります。デフォルト値：false。 |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | ドキュメントのアウトラインを取得します。 |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | ドキュメント内の出力意図のコレクションを取得します。 |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | ページ情報を取得または設定します。（生成者のみ、ドキュメントを読み取るときは入力されません） |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | ドキュメント内のページラベルを取得します。 |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | ドキュメントが開かれたときに使用されるページレイアウトを取得または設定します。 |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | ドキュメントが開かれたときに表示される方法を指定するページモードを取得または設定します。 |
| [Pages](../../aspose.pdf/document/pages/) { get; } | ドキュメントページのコレクションを取得または設定します。コレクション内のページは1から番号が付けられています。 |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | PDFフォーマットを取得します。 |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | ドキュメントの権限を取得します。 |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | PDFページサイズを使用して入力用紙トレイを選択するかどうかを指定するフラグを取得または設定します。 |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | このドキュメントの印刷ダイアログが表示されたときに選択されるページスケーリングオプションを取得または設定します。 |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | TaggedPdfコンテンツへのアクセスを取得します。 |
| [Version](../../aspose.pdf/document/version/) { get; } | PDFファイルヘッダーからPDFのバージョンを取得します。 |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | ファイル全体をメモリに読み込むためのファイルサイズ制限を取得および設定します。値はメガバイトで設定されます。デフォルト値は210 Mbです。 |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | システムのライセンス状態を取得します。システムがライセンスモードで動作している場合はtrue、それ以外の場合はfalseを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | ドキュメントをマージします。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | PDFファイルをマージします。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | ドキュメントをマージします。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | ドキュメントをマージします。 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | XMLをドキュメントにバインドします。 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | XMLをドキュメントにバインドします。 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | XML/XSLをドキュメントにバインドします。 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | XML/XSLをドキュメントにバインドします。 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | XML/XSLをドキュメントにバインドします。 |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | ドキュメントのパスワードを変更します。このアクションは所有者パスワードを使用してのみ実行できます。 |
| [Check](../../aspose.pdf/document/check/)(bool) | ドキュメントを検証します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | 指定された変換オプションを使用してドキュメントを変換します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | ドキュメント内の画像を認識し、その上にhocr文字列を追加します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | ドキュメント内の画像を認識し、その上にhocr文字列を追加します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | ドキュメントを変換し、エラーを指定されたストリームに保存します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | ドキュメントを変換し、エラーを指定されたファイルに保存します。 |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Fixupを適用してドキュメントを変換します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Fixupを適用してドキュメントを変換します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | ドキュメントを変換し、エラーを指定されたファイルに保存します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | ドキュメントを変換し、エラーを指定されたファイルに保存します。 |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | ページをPNGに変換します（DSR、OMR、OCR画像ストリーム用）。 |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | ドキュメントを復号化します。その後、保存して復号化されたバージョンを取得します。 |
| [Dispose](../../aspose.pdf/document/dispose/)() | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | ドキュメントを暗号化します。その後、保存して暗号化されたバージョンを取得します。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | ドキュメントを暗号化します。その後、保存して暗号化されたバージョンを取得します。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | ドキュメントを暗号化します。その後、保存して暗号化されたバージョンを取得します。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | すべてのドキュメント注釈をストリームにエクスポートします。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | すべてのドキュメント注釈をXFDFファイルにエクスポートします。 |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | ドキュメントからすべてのフィールドを削除し、その値を代わりに配置します。 |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | ドキュメントからすべてのフィールド（および注釈）を削除し、その値を代わりに配置します。 |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | 透明なコンテンツを不透明なラスタおよびベクターグラフィックスに置き換えます。 |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | メモリをクリアします。 |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | カタログ辞書からアイテムの値を返します。 |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | ドキュメント内の指定されたIDを持つオブジェクトを取得します。 |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | ドキュメントからXMPメタデータを取得します。 |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | 現在のPDFドキュメントが増分更新で保存されているかどうかを確認します。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | ストリームからドキュメントに注釈をインポートします。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | XFDFファイルからドキュメントに注釈をインポートします。 |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | ドキュメントがRepairメソッド呼び出しを必要とするかどうかを確認します。 |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | ファイルを読み込み、PDFに変換します。 |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | ドキュメントをマージします。 |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | PDFファイルをマージします。 |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | ドキュメントをマージします。 |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | ドキュメントをマージします。 |
| [Optimize](../../aspose.pdf/document/optimize/)() | ドキュメントを線形化して、- 最初のページをできるだけ早く開く; - 次のページをできるだけ早く表示するか、次のページへのリンクをたどる; - データが遅いチャネルを介して配信されるときにページをインクリメンタルに表示する（最も有用なデータを最初に表示する）; - ユーザーの操作（リンクをたどるなど）を、ページ全体が受信されて表示される前に実行できるようにします。このメソッドを呼び出すことは、実際にはドキュメントを保存しません。逆に、ドキュメントは最適化された構造を持つように準備されるだけで、最適化されたドキュメントを取得するには保存を呼び出す必要があります。 |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | ドキュメント内のリソースを最適化します：1. ドキュメントページで使用されていないリソースが削除されます。2. 同等のリソースが1つのオブジェクトに結合されます。3. 使用されていないオブジェクトが削除されます。 |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | 定義された最適化戦略に従ってドキュメント内のリソースを最適化します。 |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | ドキュメント内のページツリーノードをバランスの取れたツリーに整理します。ドキュメントにnodesNumInSubtreesページオブジェクトがある場合のみ、そうでない場合は何もしません。Pages要素を反復処理している間にこのメソッドを呼び出さないでください。予測不可能な結果をもたらす可能性があります。 |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | 生成者のために段落を処理します。 |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | ドキュメントからメタデータを削除します。 |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | ドキュメントからpdfa準拠を削除します。 |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | ドキュメントからpdfUa準拠を削除します。 |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | 壊れたドキュメントを修復します。 |
| [Save](../../aspose.pdf/document/save/#save)() | ドキュメントを増分的に保存します（すなわち、増分更新技術を使用して）。 |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | 保存オプションを使用してドキュメントを保存します。 |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | ドキュメントをストリームに保存します。 |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | 指定されたファイルにドキュメントを保存します。 |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | 新しい名前とファイル形式でドキュメントを保存します。 |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | 保存オプションを使用してストリームにドキュメントを保存します。 |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | 新しい名前とファイル形式でドキュメントを保存します。 |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | 新しい名前を設定してドキュメントを保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | ドキュメントを増分的に保存します（すなわち、増分更新技術を使用して）。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | 保存オプションを使用してドキュメントを保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | ドキュメントをストリームに保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | 指定されたファイルにドキュメントを保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | 新しい名前とファイル形式でドキュメントを保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | 保存オプションを使用してストリームにドキュメントを保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | 新しい名前とファイル形式でドキュメントを保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | 新しい名前を設定してドキュメントを保存します。 |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | ドキュメントをXMLに保存します。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | ドキュメントデバイスに処理のためにドキュメント全体を送信します。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | ドキュメントデバイスに処理のためにドキュメント全体を送信します。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | ドキュメントの特定のページをドキュメントデバイスに処理のために送信します。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | ドキュメントデバイスに処理のためにドキュメント全体を送信します。 |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | PDFドキュメントのタイトルを設定します。 |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | ドキュメントのXMPメタデータを設定します。 |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | 指定されたファイルにドキュメントを検証します。 |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | 指定されたファイルにドキュメントを検証します。 |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | 指定されたファイルにドキュメントを検証します。 |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | ソース形式のストリームを宛先形式のストリームに変換します。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | ソース形式のストリームを宛先形式の宛先ファイルに変換します。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | ソース形式のソースファイルを宛先形式のストリームに変換します。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | ソース形式のソースファイルを宛先形式の宛先ファイルに変換します。 |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | ファイル全体をメモリに読み込むためのファイルサイズ制限をデフォルト値210 Mbに設定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | ドキュメント内でフォントが別のフォントに置き換えられるときに発生します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | FontSubstitutionイベントを処理するメソッドを表します。 |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | フォントを調整する機能を保持します。 |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | マージメソッドのオプションを表します。 |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | PDFドキュメントを修復するためのオプションを表します。 |

### 参照

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)