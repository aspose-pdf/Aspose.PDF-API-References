---
title: "クラス HtmlSaveOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlSaveOptions クラス。HTML 形式へのエクスポート用の保存オプションです"
type: docs
weight: 5690
url: /ja/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Html 形式へのエクスポート用保存オプション

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | `HtmlSaveOptions` クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | `HtmlSaveOptions` クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | `HtmlSaveOptions` クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | `HtmlSaveOptions` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | ソースと宛先のフォーマットペアに対してバッチ変換が適用可能な場合のバッチサイズを定義します。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | 見つかった SVG グラフィック（存在する場合）が保存時に SVGZ 形式に圧縮（ZIP）されるかどうかを示すフラグを取得または設定します。 |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | 属性 ConvertMarkedContentToLayers が true に設定されている場合、PDF のマークドコンテンツ（レイヤー）内のすべての要素が、レイヤー名を指定する "data-pdflayer" 属性を持つ HTML の div に配置されます。このレイヤー名は PDF のマークドコンテンツのオプションプロパティから抽出されます。この属性が false（デフォルト）の場合、PDF のマークドコンテンツからレイヤーは作成されません。 |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | 埋め込まれておらずシステムにもインストールされていないドキュメントフォントの代替として使用される、インストール済みフォントの名前を指定します。null の場合はデフォルトの代替フォントが使用されます。 |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | [`HtmlDocumentType`](../htmldocumenttype/) を取得または設定します。 |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | このプロパティを使用すると、変換すべきドキュメントのページを明示的に指定できます。このリスト内のページは 1 から始まる番号でなければなりません。つまり、有効なページ番号は範囲 (1...[NumberOfPagesInConvertedDocument]) から取得する必要があります。このリストにおけるページの出現順序は、結果の HTML ページの順序に影響しません。結果のページは常にソース PDF に存在する順序で表示されます。このリストが null（デフォルト）の場合、すべてのページが変換されます。このリスト内のページ番号が実際のページ数の範囲 (1-[amountOfPagesInDocument]) を超えると例外がスローされます。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを使用して PDF Document から画像またはテキストを抽出する機能を有効にします。 |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | HTML が固定レイアウトとして作成されるかどうかを示す値を取得または設定します。 |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | この属性はフローモード（FixedLayout = false）での全幅段落テキストを指定します。 |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | 事前に保存されたフォントのフォントソースです。 |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | 指定サイズ以下のテキストは変換時に無視されます。このテキストを削除するわけではなく、無視して出力ファイルに転送しません。 |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。 |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | 画像レンダリングの解像度を取得または設定します。 |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | この属性はグラフィックパスの線の最小幅を設定します。線の太さが 1px 未満の場合、Adobe Acrobat はこの値に丸めます。そのため、この属性は HTML ブラウザでこの動作をエミュレートするために使用できます。 |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | この属性は、テキストのグリフが単語や文字列にまとめられないモードを有効にします。このモードにより、ページ上でのグリフの配置精度を最大限に保つことができ、楽譜や個別に配置すべきグリフを含む文書の変換に使用できます。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。 |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | 属性 RenderTextAsImage が true に設定されている場合、ソースのテキストは HTML で画像として表示されます。テキストを選択不可にしたり、HTML のテキストが正しくレンダリングされない場合に役立ちます。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | 完全なフォントを保存することを示します。True Type フォントのみサポートします。デフォルトでは SaveFullFont = false で、変換ツールは文書のテキスト表示に必要なフォントのサブセットを保存します。 |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | この属性は、グリフと単語を文字列に順次グループ化することを指定します。たとえば、変換された HTML でタグと単語の順序が異なり、合わせたい場合に使用します。このパラメータは FixedLayout 属性の値が true の場合にのみ文書に適用されます。 |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | マルチページモードが選択されている場合（つまり 'SplitIntoPages' が true の場合）、この属性は各結果 HTML ページごとに個別の CSS ファイルを作成するかどうかを定義します。デフォルトではこの属性は false で、すべてのページに対して 1 つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS（ページごとに 1 つの CSS）の総サイズは、通常、1 つの大きな CSS ファイルのサイズよりもはるかに大きくなります。なぜなら、前者の場合、CSS クラスが各ページの複数の CSS ファイルに重複して存在するためです。そのため、この設定は、各 HTML ページを個別に処理したい場合にのみ使用すべきであり、各ページごとの CSS サイズが最も重要な課題となります。 |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | ソース文書の各ページを個別のターゲット HTML 文書に変換するかどうかを示すフラグを取得または設定します。つまり、結果の HTML が複数の HTML ページに分割されるかどうかを示します。 |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | HTML ページのタイトルを取得または設定します。 |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | 画像フラグメントを 1 つの画像に結合するフラグです。 |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | 属性 UseZORder が true に設定されている場合、元の PDF 文書の Z オーダーに従ってグラフィックとテキストが結果の HTML 文書に追加されます。この属性が false の場合、すべてのグラフィックが単一レイヤーとして配置され、重なったオブジェクトに不要な影響を与える可能性があります。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | このパラメータは、PDF から HTML への複合背景画像変換時に必要なアンチエイリアス処理を定義します。 |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | PDFtoHTML コンバータが結果の CSS を生成する際、CSS クラス名（例: \".stl_01 {}\" … \".stl_NN {}\"）が作成され、結果の CSS で使用されます。このプロパティを使用すると、クラス名のプレフィックスを強制的に設定できます。たとえば、すべてのクラス名を 'my_prefix_' で始めたい場合（例: 'my_prefix_1' … 'my_prefix_NNN' のように）、変換前にこのプロパティに 'my_prefix_' を割り当てます。このプロパティが未設定（null のまま）であれば、コンバータは自動的にクラス名を生成します（例: \".stl_01 {}\" … \".stl_NN {}\" のようになります）。 |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | このフィールドには、Pdf から Html への変換中に使用すべき（存在する場合）CSS の保存戦略を指定できます。作成された HTML 文書全体またはページ単位（複数の HTML ページが生成される場合）に関連する CSS の保存を処理します。CSS ファイルを特定の方法で処理したい場合は、該当するメソッドを作成し、そのデリゲートをこのプロパティに割り当ててください。 |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | 変換結果は 1 つまたは複数の HTML ページを含むことがあります。このプロパティには、変換中に作成された 1 つの HTML ページ（正確にはマークアップ HTML で、外部リンクファイルがある場合は除く）を処理するカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ページの HTML をストリームやディスクに保存するなどの処理はカスタムコードで行われます。したがって、HTML ページの保存に必要なすべての操作は、提供されたメソッドのコード内で実行する必要があります。変換ツールのコードで処理すべきケースがあり、カスタムコードで行わない場合は、カスタムコード内で 'htmlSavingInfo' パラメータの変数のフラグ 'CustomProcessingCancelled' を設定してください。これにより、外部カスタムコードが存在しないかのように、コンバータ自身がそのリソースの処理を行うことを示します。 |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | このハンドラは変換の進捗イベントを処理するために使用できます。たとえば、プログレスバーや現在処理中のページ数を示すメッセージの表示に利用できます。コンソールに進捗を表示するハンドラのコード例は以下の通りです： |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | このフィールドには、変換中に使用すべき（存在する場合）カスタマイズされたリソースファイル（画像やフォントなど）の保存戦略を指定できます。保存された HTML のノードに関連する参照リソースファイルを処理し、生成された HTML で使用する望ましい URL を表す文字列を返す必要があります。 |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | このフィールドには、生成された結果 HTML に配置すべき対象 CSS の URL（マルチページ生成が有効な場合は URL テンプレート）を返すカスタムメソッドを指定できます。たとえば、標準の CSS ファイル名の代わりに特定の URL を使用したい場合は、望ましい URL を生成するメソッドを作成し、このプロパティに設定してください。フラグ 'SplitCssIntoPages' が設定されている場合、このカスタム戦略（存在する場合）は CSS の正確な URL ではなく、プレースホルダーをページ番号で置換する（converter 内の string.Format() 関数を使用）ことで各ページの CSS URL に解決できるテンプレート文字列を返す必要があります。そのような場合に期待される返却文字列の例は、'SomeTargetLocation-page_{0}.css'、'../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}' です。 |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | HTML に埋め込まれない PDF 埋め込みフォント名の一覧。 |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | 現在のドキュメントの PDF デコードを調整するためのエンコーディング特別ルールを定義します |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | PDF を希望の形式で保存する際に使用されるフォント保存モードを定義します |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | HTML マークアップ生成に特定の要件がある場合があります。このパラメータは、PDF から HTML への変換時にそのような特定の要件に合わせて使用できる HTML 準備モードを定義します。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 数スレッドでページを処理します。 |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | 結果の HTML における単語内の文字の配置モードを設定します |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | この属性は、ソース PDF ページを表す領域の周囲に結果の HTML ドキュメントで境界線（存在する場合）を描画するために使用される設定の集合を表します。本質的には、PDF ページ自体で参照されるページ境界ではなく、ページの紙の端を表示することに関係しています。 |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | この属性は、ソース PDF ページを表す領域の周囲に結果の HTML ドキュメントで追加のページ余白（存在する場合）を設定するための設定集合を表します。 |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | 属性 'SplitOnPages=false' の場合、すべての入力 PDF ページを表す HTML が 1 つの大きな結果 HTML ファイルにまとめられます。このフラグは、結果の HTML が、ビューアの画面解像度に応じて PDF ページを表す領域の流れが変わるように生成されるかどうかを定義します。たとえば、ビューア側の画面幅が十分に広く、横方向に 2 ページ以上を隣接させて表示できる場合、このフラグが true に設定されていれば、その機能が利用されます（可能な限り横方向にページが隣り合って表示され、次の横方向のページ群は最初の下に表示されます）。フラグが false の場合、ページは常に前のページの下に順に配置されます。 |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | 参照されたファイル（HTML、フォント、画像、CSS）がメインの HTML ファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを定義します |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | 変換された PDF にはラスタ画像が含まれることがあります。このパラメータは、PDF から HTML への変換時にそれらをどのように処理するかを定義します |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | 作成された HTML から、コンテンツがない上部および下部の空白領域（存在する場合）を削除するかどうかを定義します |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF には、他の要素（例: 画像）に隠されているが、Acrobat Reader ではクリップボードに選択できるテキストが含まれることがあります（通常、文書に画像とそこから抽出された OCR テキストが含まれる場合に発生します）。この設定は、Acrobat Reader の動作を模倣するために、結果の HTML にこれらのテキストを透過的な選択可能テキストとして保存するかどうかをコンバータに指示します（そうしない場合、これらのテキストは通常、非表示として保存され、クリップボードへのコピーはできません）。 |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF には、クリップボードに選択できる透過テキストが含まれることがあります（通常、文書に画像とそこから抽出された OCR テキストが含まれる場合に発生します）。この設定は、結果の HTML にこれらのテキストを透過的な選択可能テキストとして保存するかどうかをコンバータに指示します |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | HTML としてドキュメントを保存する際に画像が見つかった場合に保存する必要があるディレクトリへのパスを取得または設定します。パラメータが空または null の場合、画像ファイル（存在する場合）は HTML にリンクされた他のファイルと共に保存されます。CustomImageSavingStrategy プロパティが正常に使用されて該当画像ファイルが処理された場合、この設定は影響しません。 |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | HTML としてドキュメントを保存する際に SVG 画像が見つかった場合にのみ保存するディレクトリへのパスを取得または設定します。パラメータが空または null の場合、SVG ファイル（存在する場合）は他の画像ファイルと同様に出力ファイルの近くに保存されるか、SpecialImagesFolderIfAny オプションで指定された画像用の特別フォルダーに保存されます。CustomImageSavingStrategy プロパティが正常に使用されて該当画像ファイルが処理された場合、この設定は影響しません。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | PDF には、ページや表セルの背景画像が、同じタイル背景画像を複数組み合わせて隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされた文書に同じ背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、実際に必要なときにのみこのオプションを使用してください。 |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF 自体にはテキストの下線マーカーが含まれていません。テキストの下に線を配置してエミュレートされています。このオプションは、コンバータがその線がテキストの下線であるかどうかを推測し、グラフィカルに下線を描画する代わりに CSS に情報を入れることを可能にします。 |

## 例

以下の例は、PDF ファイルを HTML ファイルに変換する方法を示しています

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF ファイルへのパスです。
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// 出力 HTML ファイルへのパスです。
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// HtmlSaveOptions を初期化します \t
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// HTML ファイルを保存します
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

### 関連項目

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


