---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsクラス。Html形式へのエクスポートのための保存オプション
type: docs
weight: 5560
url: /ja/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptionsクラス

Html形式へのエクスポートのための保存オプション

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | `HtmlSaveOptions`クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | `HtmlSaveOptions`クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | `HtmlSaveOptions`クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | `HtmlSaveOptions`クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | ソースと宛先フォーマットのペアにバッチ変換が適用可能な場合のバッチサイズを定義します。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | アップページを準備する際にフォントグリフがキャッシュされるかどうかを示すブール値を取得または設定します。PDFから他の形式への変換のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Responseオブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | 保存中に見つかったSVGグラフィックス（ある場合）がSVGZ形式に圧縮されるかどうかを示すフラグを取得または設定します。 |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | ConvertMarkedContentToLayers属性がtrueに設定されている場合、PDFのマークされたコンテンツ（レイヤー）のすべての要素が、レイヤー名を指定する"data-pdflayer"属性を持つHTML divに配置されます。このレイヤー名はPDFのマークされたコンテンツのオプションプロパティから抽出されます。この属性がfalse（デフォルト）である場合、PDFのマークされたコンテンツからレイヤーは作成されません。 |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | 埋め込まれておらず、システムにインストールされていないドキュメントフォントを置き換えるために使用されるインストールされたフォントの名前を指定します。nullの場合、デフォルトの置き換えフォントが使用されます。 |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | [`HtmlDocumentType`](../htmldocumenttype/)を取得または設定します。 |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | このプロパティを使用すると、変換するドキュメントのページを明示的に定義できます。このリストのページは1ベースの番号でなければなりません。すなわち、有効なページ番号は範囲(1...[NumberOfPagesInConvertedDocument])から取得する必要があります。このリストにおけるページの出現順序は、結果のHTMLページにおける順序に影響を与えません - 結果のページは常にソースPDFに存在する順序で表示されます。このリストがnullの場合（デフォルトでは）、すべてのページが変換されます。このリストのページ番号が存在するページの範囲（1-[amountOfPagesInDocument]）を超える場合、例外がスローされます。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCRサブレイヤーを持つPDFドキュメントから画像またはテキストを抽出する機能をオンにします。 |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | HTMLが固定レイアウトとして作成されるかどうかを示す値を取得または設定します。 |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | この属性は、フローモードのための全幅段落テキストを指定します。FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | 事前に保存されたフォントのフォントソース。 |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | 指定されたサイズ以下のテキストは変換中に無視されます。このテキストは削除されず、無視されて出力ファイルに転送されません。 |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | フォントの欠如に関連するエラーが無視されるかどうかを示す値を取得または設定します。trueは、フォントの欠如に関するエラーが無視されることを意味します。無効なリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトではfalseです。 |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | 画像レンダリングの解像度を取得または設定します。 |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | この属性は、グラフィックパスの線の最小幅を設定します。線の太さが1px未満の場合、Adobe Acrobatはこの値に丸めます。この属性は、HTMLブラウザでこの動作をエミュレートするために使用できます。 |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | この属性は、テキストグリフが単語や文字列にグループ化されないモードをオンにします。このモードは、ページ上のグリフの位置決め中に最大の精度を保持することを可能にし、音符や互いに別々に配置されるべきグリフを持つドキュメントの変換に使用できます。このパラメータは、FixedLayout属性の値がtrueのときのみドキュメントに適用されます。 |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | RenderTextAsImage属性がtrueに設定されている場合、ソースのテキストはHTML内の画像になります。テキストを選択できなくするか、HTMLテキストが正しくレンダリングされない場合に便利です。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | フルフォントが保存されることを示します。True Type Fontsのみをサポートします。デフォルトではSaveFullFont = falseで、コンバータはドキュメントのテキストを表示するために必要な初期フォントのサブセットを保存します。 |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | この属性は、グリフと単語を文字列に順次グループ化することを指定します。たとえば、タグと単語が変換されたHTMLで異なる順序を持ち、それらを一致させたい場合に使用します。このパラメータは、FixedLayout属性の値がtrueのときのみドキュメントに適用されます。 |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | マルチページモードが選択されている場合（すなわち、'SplitIntoPages'が'true'の場合）、この属性は、各結果HTMLページのために別々のCSSファイルを作成するかどうかを定義します。デフォルトではこの属性はfalseであるため、すべての作成されたページのために1つの大きな共通CSSが作成されます。このモードで生成されたすべてのCSSの合計サイズ（1ページあたり1つのCSS）は、通常1つの大きなCSSファイルのサイズよりもはるかに大きくなります。なぜなら、前者の場合、CSSクラスが複数のCSSファイルに重複して存在するからです。この設定は、各HTMLページを独立して将来的に処理することに関心がある場合にのみ使用するのが望ましいです。したがって、各ページのCSSのサイズが最も重要な問題となります。 |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | ソースドキュメントの各ページがそれぞれのターゲットHTMLドキュメントに変換されるかどうかを示すフラグを取得または設定します。すなわち、結果のHTMLが複数のHTMLページに分割されるかどうかを示します。 |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | HTMLページのタイトルを取得または設定します。 |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | 画像フラグメントを1つの画像に結合するためのフラグ。 |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | UseZOrder属性がtrueに設定されている場合、グラフィックスとテキストは元のPDFドキュメントのZ順序に従って結果のHTMLドキュメントに追加されます。この属性がfalseの場合、すべてのグラフィックスは単一のレイヤーとして配置され、重なったオブジェクトに対して不必要な効果を引き起こす可能性があります。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandlerは、ContinueまたはAbortを指定するReturnAction列挙型のアイテムを返します。Continueはデフォルトのアクションであり、保存操作は続行されますが、ユーザーはAbortを返すこともでき、その場合保存操作は中止されるべきです。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | このパラメータは、PDFからHTMLへの変換中に必要なアンチエイリアス処理を定義します。 |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | PDFtoHTMLコンバータが結果CSSを生成する際、CSSクラス名（".stl_01 {}" ... ".stl_NN {}"のような）が生成され、結果CSSで使用されます。このプロパティは、クラス名のプレフィックスを強制的に設定することを可能にします。たとえば、すべてのクラス名が'my_prefix_'で始まるようにしたい場合（すなわち、'my_prefix_1' ... 'my_prefix_NNN'のような）、変換前にこのプロパティに'my_prefix_'を割り当てるだけです。このプロパティが変更されない場合（すなわち、nullが値として残される場合）、コンバータはクラス名を自動的に生成します（".stl_01 {}" ... ".stl_NN {}"のような）。 |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | このフィールドには、PDFからHTMLへの変換中に、作成されたHTMLドキュメント全体またはそのページ（複数のHTMLページが生成される場合）のCSSの保存に関連する保存戦略が含まれる場合があります。CSSファイルを特定の方法で処理したい場合は、関連するメソッドを作成し、そのメソッドから作成されたデリゲートをこのプロパティに割り当ててください。 |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | 変換の結果には1つまたは複数のHTMLページが含まれる場合があります。このプロパティには、変換中に作成された1つのHTMLページ（正確には、外部リンクされたファイルがないマークアップHTML）を処理するカスタムメソッドから作成されたデリゲートを割り当てることができます。この場合、HTMLページの保存などの処理は、そのカスタムコードで行うことができます。この場合、HTMLページの保存に必要なすべてのアクションは、提供されたメソッドのコード内で行う必要があります。なぜなら、コンバータのコード内で結果を保存することは使用されないからです。この場合、何らかの理由でこの処理がコンバータのコード自体によって行われる必要がある場合は、カスタムコード内で'htmlSavingInfo'パラメータの変数の'CustomProcessingCancelled'フラグを設定してください。これにより、コンバータはそのリソースの処理に必要なすべてのステップがコンバータ自体で行われるべきであることを示します。 |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | このハンドラは、変換進行状況イベントを処理するために使用できます。たとえば、進行状況バーや処理されたページの現在の量に関するメッセージを表示するために使用できます。ハンドラのコードの例は次のとおりです。 |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | このフィールドには、カスタマイズされたHTMLのノードに関連する作成された参照リソースファイル（画像やフォントなど）の保存に関連する保存戦略が含まれる場合があります。その戦略はリソースを処理し、生成されたHTML内で保存されたリソースの望ましいURLを表す文字列を返す必要があります。 |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | このフィールドには、生成された結果HTMLに配置されるべきCSSのURL（またはマルチページ生成がオンの場合はURLテンプレート）を返すカスタムメソッドが含まれる場合があります。たとえば、コンバータが生成されたCSS内で標準のCSSファイル名の代わりに特定のURLを配置するようにしたい場合は、望ましいURLを生成するメソッドを作成し、このプロパティに配置するだけです。'SplitCssIntoPages'フラグが設定されている場合、このカスタム戦略（存在する場合）は、CSSの正確なURLではなく、プレースホルダーをページ番号で置き換えた後に解決できるテンプレート文字列を返す必要があります。この場合の期待される返り値の例は次のとおりです：'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}' |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | HTMLに埋め込まれないPDF埋め込みフォント名のリスト。 |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | 現在のドキュメントのPDFデコーディングを調整するための特別なルールを定義します。 |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | PDFを望ましい形式に保存する際に使用されるフォント保存モードを定義します。 |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | 時にはHTMLマークアップ生成に特定の要件が存在します。このパラメータは、PDFからHTMLへの変換中に使用できるHTML準備モードを定義します。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 複数のスレッドでページを処理します。 |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | 結果HTML内の単語内の文字の位置決めモードを設定します。 |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | この属性は、ソースPDFページを表す領域の周囲に結果HTMLドキュメント内で境界線（ある場合）を描画するために使用される設定のセットを表します。本質的には、PDFページ自体に参照されるページの境界ではなく、ページの紙の端を表示することに関係しています。 |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | この属性は、ソースPDFページを表す領域の周囲に結果HTMLドキュメント内で追加のページマージン（ある場合）を表します。 |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | 'SplitOnPages=false'属性の場合、すべての入力PDFページを表すHTMLが1つの大きな結果HTMLファイルに配置されます。このフラグは、結果HTMLが生成される方法を定義します。すなわち、結果HTML内のPDFページを表す領域のフローがビューアの画面解像度に依存するかどうかを示します。ビューア側の画面の幅が十分に大きく、2ページ以上を横方向に並べて表示できる場合、このフラグがtrueに設定されていると、その機会が利用されます（可能な限り多くのページが横方向に並べて表示され、次の横方向のページグループが最初の下に表示されます）。そうでない場合、ページは次のようにフローします：次のページは常に前のページの下に配置されます。 |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | 参照ファイル（HTML、フォント、画像、CSS）がメインHTMLファイルに埋め込まれるか、別のバイナリエンティティとして生成されるかを定義します。 |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | 変換されたPDFにはラスタ画像が含まれる場合があります。このパラメータは、PDFからHTMLへの変換中にそれらがどのように処理されるべきかを定義します。 |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | 作成されたHTML内で、コンテンツのない上部および下部の空白領域が削除されるかどうかを定義します（ある場合）。 |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDFには、他の要素（例えば画像）によって影が付けられたテキストが含まれる場合がありますが、Acrobat Readerではクリップボードに選択できることがあります（通常、ドキュメントに画像とOCRされたテキストが含まれている場合に発生します）。この設定は、結果HTML内でそのようなテキストを透明な選択可能なテキストとして保存する必要があるかどうかをコンバータに指示します（そうでない場合、そのようなテキストは通常、隠された状態で保存され、クリップボードにコピーできません）。 |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDFには、クリップボードに選択できる透明なテキストが含まれる場合があります（通常、ドキュメントに画像とOCRされたテキストが含まれている場合に発生します）。この設定は、結果HTML内でそのようなテキストを透明な選択可能なテキストとして保存する必要があるかどうかをコンバータに指示します。 |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | ドキュメントをHTMLとして保存する際に遭遇したすべての画像が保存されるディレクトリへのパスを取得または設定します。このパラメータが空またはnullの場合、画像ファイル（ある場合）はHTMLにリンクされた他のファイルと一緒に保存されます。CustomImageSavingStrategyプロパティが関連する画像ファイルを処理するために正常に使用された場合、何も影響しません。 |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | ドキュメントをHTMLとして保存する際に遭遇したSVG画像のみが保存されるディレクトリへのパスを取得または設定します。このパラメータが空またはnullの場合、SVGファイル（ある場合）は他の画像ファイル（出力ファイルの近く）または画像用の特別なフォルダに保存されます（SpecialImagesFolderIfAnyオプションで指定されている場合）。CustomImageSavingStrategyプロパティが関連する画像ファイルを処理するために正常に使用された場合、何も影響しません。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 時にはPDFには、ページやテーブルセルの背景画像が含まれ、同じタイル状の背景画像が隣接して配置されている場合があります。この場合、ターゲット形式のレンダラー（例えば、DOCS形式のMsWord）は、背景画像の部分間に目に見える境界を生成することがあります。なぜなら、画像のエッジスムージング（アンチエイリアス）の技術がAcrobat Readerとは異なるからです。エクスポートされたドキュメントに同じ背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用してその不要な効果を取り除くことを試みてください。注意！この品質の最適化は通常、変換を大幅に遅くするため、本当に必要な場合にのみこのオプションを使用してください。 |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF自体にはテキストの下線マーカーが含まれていません。これは、テキストの下に配置された線でエミュレートされます。このオプションは、コンバータがこの線がテキストの下線であると推測し、この情報をグラフィックで下線を描画する代わりにCSSに入れることを許可します。 |

## 例

次の例は、PDFファイルをHTMLファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### 参照

* クラス [UnifiedSaveOptions](../unifiedsaveoptions/)
* インターフェース [IPageSetOptions](../ipagesetoptions/)
* インターフェース [IPipelineOptions](../ipipelineoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)