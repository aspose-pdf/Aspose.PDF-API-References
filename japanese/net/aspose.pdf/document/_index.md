---
title: "クラス Document"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Document クラス。PDF Document を表すクラスです。"
type: docs
weight: 3900
url: /ja/net/aspose.pdf/document/
---
## Document class

PDF ドキュメントを表すクラス。

```csharp
public sealed class Document : IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Document](document/#constructor)() | 空の Document を初期化します。 |
| [Document](document/#constructor_1)(PdfVersion) | バージョン指定で空の Document を初期化します。 |
| [Document](document/#constructor_2)(Stream) | *input* ストリームから新しい Document インスタンスを初期化します。 |
| [Document](document/#constructor_11)(string) | *filename* を使用して Document を初期化するだけです。[`Document`](./document/) と同じです。 |
| [Document](document/#constructor_6)(Stream, bool) | *input* ストリームから新しい Document インスタンスを初期化します。 |
| [Document](document/#constructor_4)(Stream, CertificateEncryptionOptions) | *input* ストリームから新しい Document インスタンスを初期化します。 |
| [Document](document/#constructor_3)(Stream, LoadOptions) | ストリームから既存の Document を開き、PDF Document を取得するために必要な変換を提供します。 |
| [Document](document/#constructor_7)(Stream, string) | *input* ストリームから新しい Document インスタンスを初期化します。 |
| [Document](document/#constructor_15)(string, bool) | *filename* を使用して Document を初期化するだけです。[`Document`](./document/) と同じです。 |
| [Document](document/#constructor_13)(string, CertificateEncryptionOptions) | 暗号化された Document を扱うために `Document` クラスの新しいインスタンスを初期化します。 |
| [Document](document/#constructor_12)(string, LoadOptions) | ファイルから既存の Document を開き、PDF Document を取得するために必要な変換オプションを提供します。 |
| [Document](document/#constructor_16)(string, string) | 暗号化された Document を扱うために `Document` クラスの新しいインスタンスを初期化します。 |
| [Document](document/#constructor_5)(Stream, CertificateEncryptionOptions, bool) | *input* ストリームから新しい Document インスタンスを初期化します。 |
| [Document](document/#constructor_9)(Stream, string, bool) | *input* ストリームから新しい Document インスタンスを初期化します。 |
| [Document](document/#constructor_8)(Stream, string, ICustomSecurityHandler) | *input* ストリームから新しい Document インスタンスを初期化します。 |
| [Document](document/#constructor_14)(string, CertificateEncryptionOptions, bool) | 暗号化された Document を扱うために `Document` クラスの新しいインスタンスを初期化します。 |
| [Document](document/#constructor_18)(string, string, bool) | 暗号化された Document を扱うために `Document` クラスの新しいインスタンスを初期化します。 |
| [Document](document/#constructor_17)(string, string, ICustomSecurityHandler) | 暗号化された Document を扱うために `Document` クラスの新しいインスタンスを初期化します。 |
| [Document](document/#constructor_10)(Stream, string, bool, ICustomSecurityHandler) | *input* ストリームから新しい Document インスタンスを初期化します。 |
| [Document](document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | 暗号化された Document を扱うために `Document` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Document のアクションを取得します。このプロパティは DocumentActions クラスのインスタンスで、BeforClosing、BeforSaving などのアクションを取得/設定できます。 |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | ページコンテンツをマージして Document サイズを最適化できます。使用すると、異なるが重複したページが同じコンテンツオブジェクトを参照する可能性があります。このモードは、別のページが変更されたときにページコンテンツが変わるなどの副作用を引き起こすことがある点に注意してください。 |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Document の背景色を取得または設定します。 |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Document のウィンドウの位置を画面の中央に配置するかどうかを示すフラグを取得または設定します。 |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Document のコレクションを取得します。 |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Document が暗号化されている場合にセキュリティ設定を取得します。Document が暗号化されていない場合、.NET 1.1 では対応する例外がスローされ、他の .NET バージョンでは CryptoAlgorithm が null になります。 |
| [CustomSecurityHandler](../../aspose.pdf/document/customsecurityhandler/) { get; } | カスタム セキュリティ ハンドラを取得します。 |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | 宛先のコレクションを取得します。廃止予定です。NamedDestinations を使用してください。 |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | テキストの読み順（L2R（左から右）または R2L（右から左））を取得または設定します。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | フォントに対する多くの操作は、そのフォントのライセンスで禁止されている場合は実行できません。たとえば、ライセンス規則により埋め込みが無効化されているフォントは PDF Document に埋め込めません。このフラグは現在の PDF Document 内のすべてのフォントに対するライセンス制限を無効にするために使用されます。このフラグを使用する際は注意が必要です。フラグが設定されると、設定した人物が可能なライセンス／法的違反に対する全責任を自ら負うことを意味します。したがって、自己責任で使用することになります。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。既定は false です。 |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Document のウィンドウタイトルバーに Document タイトルを表示するかどうかを示すフラグを取得または設定します。 |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | 印刷ダイアログからファイルを印刷する際に使用する、印刷の両面モード処理オプションを取得または設定します。 |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Document に埋め込まれたファイルのコレクションを取得します。 |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | このプロパティは、フラグ IsEmbedded が true に設定されたすべての標準 Type1 フォントを Document に埋め込む必要があることを宣言します。すべての PDF フォントはフラグ IsEmbedded を true に設定するだけで Document に埋め込むことができますが、PDF の標準 Type1 フォントはこの規則の例外です。標準 Type1 フォントの埋め込みには多くの時間がかかるため、これらのフォントを埋め込むには、指定したフォントのフラグ IsEmbedded を true に設定するだけでなく、Document レベルで追加のフラグ EmbedStandardFonts = true を設定する必要があります。このプロパティはすべてのフォントに対して一度だけ設定可能です。既定は false です。 |
| [EnableNotificationLogging](../../aspose.pdf/document/enablenotificationlogging/) { get; set; } | 通知のロギングを有効にするかどうかを示す値を取得または設定します。 |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | ドキュメントをメモリから部分的にアンロードできるようにするフラグを取得または設定します。これによりメモリ使用量を減らすことができますが、パフォーマンスに悪影響を及ぼす可能性があります。 |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | 署名フィールドのサニタイズを管理するフラグを取得または設定します。既定で有効です。 |
| [FileName](../../aspose.pdf/document/filename/) { get; } | この Document を引き起こした PDF ファイルの名前 |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Document ウィンドウを最初に表示される Page に合わせてサイズ変更するかどうかを示すフラグを取得または設定します。 |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | IDocumentFontUtilities インスタンス |
| [Form](../../aspose.pdf/document/form/) { get; } | Document の Acro Form を取得します。 |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Document が変更された状態で保存され、かつ署名がある場合に例外をスローします。 |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Document がアクティブなときにメニューバーを非表示にするかどうかを示すフラグを取得または設定します。 |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Document がアクティブなときにツールバーを非表示にするかどうかを示すフラグを取得または設定します。 |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Document がアクティブなときにユーザーインターフェイス要素を非表示にするかどうかを示すフラグを取得または設定します。 |
| [Id](../../aspose.pdf/document/id/) { get; } | ID を取得します。 |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | ソースファイルのエラーを無視するかどうかを示すフラグを取得または設定します。ソース Document から Page を宛先 Document にコピーする際、フラグが false の場合、ソースファイル内のオブジェクトが破損していると例外でコピー処理が中止されます。例: dest.Pages.Add(src.Pages); フラグが true に設定されていると、破損したオブジェクトは空の値で置き換えられます。既定は true です。 |
| [Info](../../aspose.pdf/document/info/) { get; } | document の情報を取得します。 |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | document の暗号化ステータスを取得します。document が暗号化されている場合は True です。 |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | document がリニアライズされているかどうかを示す値を取得または設定します。 |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | document が pdfa に準拠しているかどうかを取得します。 |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | document が pdfua に準拠しているかどうかを取得します。 |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | document が pdfa に準拠しているかどうかを取得または設定します。 |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | document レベルの JavaScript のコレクション。 |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | document の論理構造を取得します。 |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Document メタデータ。(PDF document には、タイトル、作者、作成日および変更日などの一般情報が含まれる場合があります。このような document のコンテンツや構造とは別のグローバル情報はメタデータと呼ばれ、外部データベースでのカタログ化や検索を支援することを目的としています。) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | document の Named Destination のコレクション。 |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | ページモードを取得または設定し、フルスクリーンモードを終了したときに document をどのように表示するかを指定します。 |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | document のオープン時に実行されるアクションを取得または設定します。 |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | 最適化フラグを取得または設定します。このフラグが設定されていると、pages が document に追加される際、結果ファイル内の同等のリソースストリームが 1 つの PDF オブジェクトにマージされます。これにより結果ファイルのサイズを減少させることができますが、実行が遅くなりメモリ要件が増加する可能性があります。デフォルト値: false。 |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | document のアウトラインを取得します。 |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | document の Output intents のコレクションを取得します。 |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | ページ情報を取得または設定します。(generator 用のみで、document を読み取る際には設定されません) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | document のページラベルを取得します。 |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | document が開かれたときに使用されるページレイアウトを取得または設定します。 |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | document が開かれたときにどのように表示されるかを指定するページモードを取得または設定します。 |
| [Pages](../../aspose.pdf/document/pages/) { get; } | document のページコレクションを取得または設定します。コレクション内の pages は 1 から番号付けされていることに注意してください。 |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | PDF フォーマットを取得します |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | document の権限を取得します。 |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | PDF ページサイズを入力用紙トレイの選択に使用するかどうかを指定するフラグを取得または設定します。 |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | この document の印刷ダイアログが表示されるときに選択されるページスケーリングオプションを取得または設定します。 |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | TaggedPdf コンテンツへのアクセスを取得します。 |
| [Version](../../aspose.pdf/document/version/) { get; } | Pdf のファイルヘッダーからバージョンを取得します。 |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | ファイル全体をメモリに読み込む際のファイルサイズ上限を取得および設定します。値はメガバイトで設定されます。デフォルト値は 210 MB です。 |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | システムのライセンス状態を取得します。システムがライセンスモードで動作している場合は true、そうでない場合は false を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Document を結合します。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Pdf ファイルを結合します。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Document を結合します。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Document を結合します。 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | xml を Document にバインドします |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | xml を Document にバインドします |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | xml/xsl を Document にバインドします |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | xml/xsl を Document にバインドします |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | xml/xsl を Document にバインドします |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Document のパスワードを変更します。この操作は所有者パスワードを使用した場合にのみ実行できます。 |
| [Check](../../aspose.pdf/document/check/)(bool) | Document を検証します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | 指定された変換オプションを使用して Document を変換します |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Document 内の画像を認識し、hocr 文字列を上に追加します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Document 内の画像を認識し、hocr 文字列を上に追加します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Document を変換し、エラーを指定されたストリームに保存します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Document を変換し、エラーを指定されたファイルに保存します。 |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Fixup を適用して Document を変換します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Fixup を適用して Document を変換します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Document を変換し、エラーを指定されたファイルに保存します。 |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Document を変換し、エラーを指定されたファイルに保存します。 |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | DSR、OMR、OCR 画像ストリーム用に Page を PNG に変換します。 |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Document を復号化します。その後 Save を呼び出して復号化されたバージョンを取得します。 |
| [Dispose](../../aspose.pdf/document/dispose/)() | この Document が使用するすべてのリソースを閉じます。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) | Document を暗号化します。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, DocumentPrivilege, ICustomSecurityHandler) | Document を暗号化します。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_3)(string, string, Permissions, CryptoAlgorithm) | Document を暗号化します。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_5)(string, string, Permissions, ICustomSecurityHandler) | Document を暗号化します。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Document を暗号化します。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_4)(string, string, Permissions, CryptoAlgorithm, bool) | Document を暗号化します。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | すべての Document 注釈をストリームにエクスポートします。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | すべての Document 注釈を XFDF ファイルにエクスポートします |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Document からすべてのフィールドを削除し、その代わりに値を配置します。 |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Document からすべてのフィールド（および注釈）を削除し、その代わりに値を配置します。 |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | 透明なコンテンツを非透明のラスタおよびベクターグラフィックに置き換えます。 |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | メモリをクリアします |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | カタログ辞書から項目の値を返します。 |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | 指定された ID を持つオブジェクトを document から取得します。 |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | document から XMP メタデータを取得します。 |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | 現在の PDF document がインクリメンタル更新で保存されているか確認します。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | ストリームから document へアノテーションをインポートします。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | XFDF ファイルから document へアノテーションをインポートします。 |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | document が Repair メソッドの呼び出しを必要としているか確認します。 |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | ファイルを読み込み、PDF に変換します。 |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Document を結合します。 |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Pdf ファイルを結合します。 |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Document を結合します。 |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Document を結合します。 |
| [Optimize](../../aspose.pdf/document/optimize/)() | document をリニアライズして、- 最初のページをできるだけ速く開くため、- 次のページを表示するか、次のページへのリンクをできるだけ速くたどるため、- ページデータが遅いチャネルで送信される際に、ページが到着したら段階的に表示する（最も有用なデータを先に表示する）ため、- ユーザー操作（リンクのクリックなど）を、ページ全体が受信・表示される前に実行できるようにするためです。このメソッドを呼び出しても実際には document は保存されません。むしろ、document は最適化された構造になるように準備されるだけで、最適化された document を取得するには Save を呼び出してください。 |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | document のリソースを最適化します：1. document のページで使用されていないリソースは削除されます；2. 同一のリソースは 1 つのオブジェクトに結合されます；3. 未使用のオブジェクトは削除されます。 |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | 定義された最適化戦略に従って document のリソースを最適化します。 |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | document のページツリーノードをバランスツリーに整理します。document に nodesNumInSubtrees 以上のページオブジェクトがある場合のみ実行され、そうでなければ何もしません。Pages 要素を反復処理している間はこのメソッドを呼び出さないでください。予測できない結果になる可能性があります。 |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | ジェネレータ用に段落を処理します。 |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | document からメタデータを削除します。 |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | document から pdfa 準拠を削除します。 |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | document から pdfUa 準拠を削除します。 |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | 破損した document を修復します。 |
| [Save](../../aspose.pdf/document/save/#save)() | document をインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | save options を使用して document を保存します。 |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | document をストリームに保存します。 |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | document を指定されたファイルに保存します。 |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | document を新しい名前とファイル形式で保存します。 |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | save options を使用して document をストリームに保存します。 |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | document を新しい名前とファイル形式で保存します。 |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | 新しい名前を設定し、save options を指定して document を保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | document をインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | save options を使用して document を保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | document をストリームに保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | document を指定されたファイルに保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | document を新しい名前とファイル形式で保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | save options を使用して document をストリームに保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | document を新しい名前とファイル形式で保存します。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | 新しい名前を設定し、save options を指定して document を保存します。 |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | document を XML に保存します。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | document 全体を document device に送信して処理します。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | document 全体を document device に送信して処理します。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | ドキュメントの特定のページを処理のためにドキュメントデバイスへ送信します。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | document 全体を document device に送信して処理します。 |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Pdf ドキュメントのタイトルを設定します。 |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | ドキュメントの XMP メタデータを設定します。 |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | ドキュメントを指定されたファイルに検証します。 |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | ドキュメントを指定されたファイルに検証します。 |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | ドキュメントを指定されたファイルに検証します。 |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | ストリームをソース形式からデスティネーション形式のストリームに変換します。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | ストリームをソース形式からデスティネーション形式のデスティネーションファイルに変換します。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | ソース形式のソースファイルをデスティネーション形式のストリームに変換します。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | ソース形式のソースファイルをデスティネーション形式のデスティネーションファイルに変換します。 |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | メモリにファイル全体をロードする際のファイルサイズ上限をデフォルト値の 210 MB に設定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | フォントがドキュメント内で別のフォントに置き換えられたときに発生します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | FontSubstitution イベントを処理するメソッドを表します。 |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | フォントを調整する機能を保持します。 |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Merge メソッドのオプションを表します。 |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | PDF Document の修復オプションを表します。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


