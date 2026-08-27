---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "HTML形式へのエクスポート用の保存オプション"
type: docs
weight: 1990
url: /ja/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

HTML形式へのエクスポート用の保存オプション

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | HtmlSaveOptions クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | {@code HtmlSaveOptions} クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | HtmlSaveOptions クラスの新しいインスタンスを初期化します。 |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | HtmlSaveOptions クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | 属性 'SplitOnPages=false' が設定されている場合、すべての入力 PDF ページを表す HTML 全体は別々の HTML ページに分割されず、1 つの大きな結果 HTML ファイルにまとめられます。ただし、各ソース PDF ページは HTML 内でそれぞれの矩形領域として表現されます（必要に応じて、特別な属性 'PageBorderIfAny' を使用してページの紙の端を示す境界線を付けることができます）。このパラメータは、ソース PDF ドキュメントのページを表す出力 HTML 領域の周囲に強制的に残す余白の幅を定義します。本質的に、PDF の \"paper\" ページの HTML 表現間の保証された間隔を定義する変換モードです。 |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | このパラメータは、PDF から HTML への複合背景画像の変換中に必要なアンチエイリアス処理を定義します。 |
| [getBatchSize](#getBatchSize--) | バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。 |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | PDFtoHTML コンバータが結果の CSS を生成する際、CSS クラス名（例: \".stl_01 {}\" … \".stl_NN {}\"）が生成され、結果の CSS で使用されます。このプロパティを使用すると、クラス名のプレフィックスを強制的に設定できます。例えば、すべてのクラス名を 'my_prefix_' で始めたい場合（つまり 'my_prefix_1' … 'my_prefix_NNN' のようになる）、変換前にこのプロパティに 'my_prefix_' を割り当てるだけです。このプロパティを変更しないまま（すなわち null のまま）にすると、コンバータが自動的にクラス名を生成します（例: \".stl_01 {}\" … \".stl_NN {}\"）。 |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | このフィールドには、Pdf から Html への変換中に、作成された HTML ドキュメント全体またはそのページ（複数の HTML ページが生成される場合）に関連する CSS の保存処理に使用すべき保存戦略を指定できます（存在する場合）。CSS ファイルを特定の方法で処理したい場合は、該当するメソッドを作成し、そのデリゲートをこのプロパティに割り当ててください。 |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | 変換結果は 1 つまたは複数の HTML ページを含む場合があります。このプロパティに、変換中に作成された 1 つの HTML ページ（正確には外部リンクファイルがないマークアップ HTML）を処理するカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ページの HTML をストリームやディスクに保存するなどの処理はカスタムコードで実行できます。この場合、HTML ページの保存に必要なすべての操作は提供されたメソッド内で行う必要があります。なぜかコンバータ側のコードで処理すべき場合は、カスタムコードのフラグ 'CustomProcessingCancelled' を 'htmlSavingInfo' パラメータの変数に設定してください。これにより、コンバータは外部カスタムコードが存在しないかのように、リソースの処理をコンバータ自身で実行するよう指示されます。 |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> このハンドラは、変換の進捗イベントを処理するために使用できます。例えば、プログレスバーや現在処理中のページ数に関するメッセージを表示するために利用できます。コンソールに進捗を表示するハンドラのコード例は次のとおりです: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | このフィールドには、変換中に作成された参照リソースファイル（画像やフォントなど）をカスタマイズして処理するために使用すべき保存戦略を指定できます（存在する場合）。この戦略はリソースを処理し、生成された HTML で保存されたリソースの望ましい URL を表す文字列を返す必要があります。 |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | このフィールドには、生成された結果HTMLに配置される対象CSSのURL（マルチページ生成が有効な場合はURLテンプレート - 詳細は下記参照）を返すカスタムメソッドを設定できます。例えば、変換時に標準のCSSファイル名の代わりに特定のURLを生成CSSに使用したい場合は、目的のURLを生成するメソッドを作成し、このプロパティに設定すればよいです。フラグ 'SplitCssIntoPages' が設定されている場合、このカスタム戦略（存在する場合）はCSSの正確なURLではなく、プレースホルダーをページ番号に置換する String.Format() 関数を使用して変換器内で解決できるテンプレート文字列を返す必要があります。このような場合に期待される戻り文字列の例は、'SomeTargetLocation-page_{0}.css'、'../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' です。 |
| [getDefaultFontName](#getDefaultFontName--) | システムに埋め込まれておらずインストールされていない文書フォントの代替として使用される、インストール済みフォントの名前を指定します。null の場合はデフォルトの代替フォントが使用されます。 |
| [getDocumentType](#getDocumentType--) | {@code HtmlDocumentTypeInternal} を取得します。 |
| [getExcludeFontNameList](#getExcludeFontNameList--) | HTML に埋め込まれない PDF 埋め込みフォント名の一覧です。 |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | このプロパティを使用すると、変換対象となる文書のページを明示的に指定できます。このリスト内のページ番号は 1 から始まる番号でなければなりません。つまり、有効なページ番号は範囲 (1...[NumberOfPagesInConvertedDocument]) から取得する必要があります。このリストにおけるページの出現順序は、結果となる HTML ページの順序に影響しません。結果ページは常に元の PDF に存在する順序で表示されます。このリストが null（デフォルト） の場合、すべてのページが変換されます。このリスト内のページ番号が実際のページ範囲 (1-[amountOfPagesInDocument]) を超えると例外がスローされます。 |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | この属性は、Flow モード（FixedLayout = false）用の全幅段落テキストを指定します。 |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | 現在の文書の PDF デコードを調整するためのエンコーディング特別ルールを定義します。 |
| [getFontSavingMode](#getFontSavingMode--) | PDF を目的の形式で保存する際に使用されるフォント保存モードを定義します。 |
| [getFontSources](#getFontSources--) | <p> 事前保存されたフォントのソースです。 </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | HTML マークアップ生成に特定の要件がある場合があります。このパラメータは、PDF から HTML への変換時にそのような特定の要件に合わせて使用できる HTML 準備モードを定義します。 |
| [getImageResolution](#getImageResolution--) | 画像レンダリングの解像度を取得または設定します。 |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | 結果 HTML における単語内の文字配置モードを設定します。 |
| [getMinimalLineWidth](#getMinimalLineWidth--) | この属性はグラフィックパス線の最小幅を設定します。線の太さが 1px 未満の場合、Adobe Acrobat はこの値に丸めます。そのため、この属性は HTML ブラウザで同様の動作をエミュレートするために使用できます。 |
| [getPageBorderIfAny](#getPageBorderIfAny--) | この属性は、ソース PDF ページを表す領域の周囲に結果 HTML ドキュメントで境界線（存在する場合）を描画するために使用される設定の集合を表します。本質的には、PDF ページ自体に参照されているページ境界ではなく、ページの紙の端を表示することに関係します。 |
| [getPageMarginIfAny](#getPageMarginIfAny--) | この属性は、ソース PDF ページを表す領域の周囲に結果 HTML ドキュメントで追加のページ余白（存在する場合）を設定するための設定集合を表します。 |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | 参照されるファイル（HTML、フォント、画像、CSS）がメインの HTML ファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを定義します。 |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | 変換された PDF にはラスタ画像が含まれることがあります。このパラメータは、PDF から HTML への変換時にそれらをどのように処理するかを定義します。 |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | HTML として文書を保存する際に画像が検出された場合に保存する必要があるディレクトリへのパスを取得または設定します。パラメータが空または null の場合、画像ファイル（存在する場合）は HTML にリンクされた他のファイルと共に保存されます。CustomImageSavingStrategy プロパティが該当画像ファイルの処理に正常に使用された場合、これには影響しません。 |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | HTML として文書を保存する際に SVG 画像が検出された場合にのみ保存するディレクトリへのパスを取得または設定します。パラメータが空または null の場合、SVG ファイル（存在する場合）は他の画像ファイルと同じ場所（出力ファイルの近く）または SpecialImagesFolderIfAny オプションで指定された画像用の特別フォルダーに保存されます。CustomImageSavingStrategy プロパティが該当画像ファイルの処理に正常に使用された場合、これには影響しません。 |
| [getTitle](#getTitle--) | HTML ページのタイトルを取得または設定します。 |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | 見つかった SVG グラフィック（存在する場合）が保存時に SVGZ 形式（圧縮）に変換されるかどうかを示すフラグを取得します。値: {@code HtmlDocumentType}。 |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | 属性 ConvertMarkedContentToLayers が true に設定されている場合、PDF のマークドコンテンツ（レイヤー）内のすべての要素が、レイヤー名を指定する \"data-pdflayer\" 属性を持つ HTML div に配置されます。このレイヤー名は PDF のマークドコンテンツのオプションプロパティから抽出されます。この属性が false（デフォルト）の場合、PDF のマークドコンテンツからレイヤーは作成されません。 |
| [isFixedLayout](#isFixedLayout--) | HTML が固定レイアウトとして作成されているかどうかを示す値を取得します。 |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。 |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | 属性 'SplitOnPages=false' の場合、すべての入力 PDF ページを表す HTML が 1 つの大きな結果 HTML ファイルにまとめられます。このフラグは、結果 HTML が PDF ページを表す領域の流れがビューアの画面解像度に依存する形で生成されるかどうかを定義します。ビューア側の画面幅が十分に広く、横方向に 2 ページ以上を隣接させて表示できると仮定します。このフラグが true に設定されている場合、その機能が使用され、可能な限り多くのページが横方向に並んで表示され、次の横方向のページグループは最初のグループの下に表示されます。フラグが false の場合、ページは常に前のページの下に順次配置されます。 |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | この属性は、テキストのグリフが単語や文字列にグループ化されないモードをオンにします。このモードは、ページ上のグリフの位置決め精度を最大限に保つことを可能にし、楽譜や個別に配置すべきグリフを含む文書の変換に使用できます。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。 |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | 作成された HTML から、コンテンツが全くない上下の空白領域を削除するかどうかを定義します（該当する場合）。 |
| [isRenderTextAsImage](#isRenderTextAsImage--) | 属性 RenderTextAsImage が true に設定されている場合、ソースのテキストは HTML で画像になります。テキストを選択不可にしたり、HTML のテキストが正しくレンダリングされない場合に有用です。 |
| [isSaveFullFont](#isSaveFullFont--) | フルフォントが保存されることを示します。True Type フォントのみサポートします。デフォルトでは SaveFullFont = false で、変換器は文書のテキスト表示に必要な元フォントのサブセットのみを保存します。 |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | Pdf は他の要素（例：画像）に影で隠されたテキストを含むことがありますが、Acrobat Reader ではクリップボードにコピーできることがあります（通常、文書に画像と OCR されたテキストが含まれる場合に起こります）。この設定は、変換器に対し、結果の HTML でそのようなテキストを透明な選択可能テキストとして保存し、Acrobat Reader の動作を模倣するかどうかを指示します（そうでない場合、通常は非表示でコピーできない形で保存されます）。 |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Pdf は透明なテキストを含むことがあり、クリップボードにコピーできることがあります（通常、文書に画像と OCR されたテキストが含まれる場合に起こります）。この設定は、変換器に対し、結果の HTML でそのようなテキストを透明な選択可能テキストとして保存するかどうかを指示します。 |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | この属性は、グリフと単語を文字列に順次グループ化することを指定します。例えば、タグと単語の順序が変換された HTML で異なり、同じ順序にしたい場合です。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。 |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | マルチページモードが選択されている場合（例：'SplitIntoPages' が 'true'）、この属性は各結果 HTML ページごとに別々の CSS ファイルを作成するかどうかを定義します。デフォルトではこの属性は false で、すべてのページに対して1つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS（ページごとに1つの CSS）の合計サイズは、1つの大きな CSS ファイルのサイズより通常ははるかに大きくなります。なぜなら、前者の場合、CSS クラスが各ページの複数の CSS ファイルに重複して存在するためです。したがって、この設定は、各 HTML ページを個別に将来的に処理したい場合にのみ使用する方が適しています。その場合、各ページごとの CSS サイズが最も重要な課題となります。 |
| [isSplitIntoPages](#isSplitIntoPages--) | ソース文書の各ページがそれぞれのターゲット HTML 文書に変換されるかどうかを示すフラグを取得します。つまり、結果の HTML が複数の HTML ページに分割されるかどうかです。 |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF 自体はテキストの下線マーカーを含みません。下線はテキストの下に配置された線でエミュレートされます。このオプションは、変換器がその線がテキストの下線であると推測し、下線をグラフィックで描画する代わりに CSS に情報を入れることを許可します。 |
| [isUseZOrder](#isUseZOrder--) | 属性 UseZORder が true に設定されている場合、グラフィックとテキストは元の PDF 文書の Z 順序に従って結果の HTML 文書に追加されます。この属性が false の場合、すべてのグラフィックが単一レイヤーとして配置され、重なったオブジェクトで不要な効果が生じる可能性があります。 |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | 属性 'SplitOnPages=false' が設定されている場合、すべての入力 PDF ページを表す HTML 全体は別々の HTML ページに分割されず、1 つの大きな結果 HTML ファイルにまとめられます。ただし、各ソース PDF ページは HTML 内でそれぞれの矩形領域として表現されます（必要に応じて、特別な属性 'PageBorderIfAny' を使用してページの紙の端を示す境界線を付けることができます）。このパラメータは、ソース PDF ドキュメントのページを表す出力 HTML 領域の周囲に強制的に残す余白の幅を定義します。本質的に、PDF の \"paper\" ページの HTML 表現間の保証された間隔を定義する変換モードです。 |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | このパラメータは、PDF から HTML への複合背景画像の変換中に必要なアンチエイリアス処理を定義します。 |
| [setBatchSize](#setBatchSize-int-) | バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。 |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | SVG グラフィック（存在する場合）が保存時に SVGZ 形式に圧縮（zip）されるかどうかを示すフラグを設定します。値: {@code HtmlDocumentType}。 |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | 属性 ConvertMarkedContentToLayers が true に設定されている場合、PDF のマークドコンテンツ（レイヤー）内のすべての要素が、レイヤー名を指定する \"data-pdflayer\" 属性を持つ HTML div に配置されます。このレイヤー名は PDF のマークドコンテンツのオプションプロパティから抽出されます。この属性が false（デフォルト）の場合、PDF のマークドコンテンツからレイヤーは作成されません。 |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | PDFtoHTML コンバータが結果の CSS を生成する際、CSS クラス名（例: \".stl_01 {}\" … \".stl_NN {}\"）が生成され、結果の CSS で使用されます。このプロパティを使用すると、クラス名のプレフィックスを強制的に設定できます。例えば、すべてのクラス名を 'my_prefix_' で始めたい場合（つまり 'my_prefix_1' … 'my_prefix_NNN' のようになる）、変換前にこのプロパティに 'my_prefix_' を割り当てるだけです。このプロパティを変更しないまま（すなわち null のまま）にすると、コンバータが自動的にクラス名を生成します（例: \".stl_01 {}\" … \".stl_NN {}\"）。 |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | このフィールドには、Pdf から Html への変換中に、作成された HTML ドキュメント全体またはそのページ（複数の HTML ページが生成される場合）に関連する CSS の保存処理に使用すべき保存戦略を指定できます（存在する場合）。CSS ファイルを特定の方法で処理したい場合は、該当するメソッドを作成し、そのデリゲートをこのプロパティに割り当ててください。 |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | 変換結果は1つまたは複数の HTML ページを含む可能性があります。このプロパティには、変換中に作成された1つの HTML ページ（正確には外部リンクファイルのないマークアップ HTML）を処理するカスタムメソッドから作成されたデリゲートを割り当てることができます。 |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | このハンドラは、変換進行イベントを処理するために使用できます（例）。 |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | このフィールドには、変換中に使用すべき保存戦略（存在する場合）を指定できます。これは、作成された参照リソースファイル（画像やフォントなど）をカスタマイズして処理するためのものです。 |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | このフィールドには、生成された結果 HTML に配置すべき対象 CSS の URL（またはマルチページ生成が有効な場合の URL テンプレート）を返すカスタムメソッドを含めることができます。 |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | システムに埋め込まれておらずインストールされていない文書フォントの代替として使用される、インストール済みフォントの名前を指定します。null の場合はデフォルトの代替フォントが使用されます。 |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | {@code HtmlDocumentType} を設定します。 |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | HTML に埋め込まれない PDF 埋め込みフォント名の一覧です。 |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | このプロパティを使用すると、変換対象となる文書のページを明示的に指定できます。このリスト内のページ番号は 1 から始まる番号でなければなりません。つまり、有効なページ番号は範囲 (1...[NumberOfPagesInConvertedDocument]) から取得する必要があります。このリストにおけるページの出現順序は、結果となる HTML ページの順序に影響しません。結果ページは常に元の PDF に存在する順序で表示されます。このリストが null（デフォルト） の場合、すべてのページが変換されます。このリスト内のページ番号が実際のページ範囲 (1-[amountOfPagesInDocument]) を超えると例外がスローされます。 |
| [setFixedLayout](#setFixedLayout-boolean-) | HTML が固定レイアウトとして作成されるかどうかを示す値を設定します。 |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | この属性は、Flow モード（FixedLayout = false）用の全幅段落テキストを指定します。 |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | 現在の文書の PDF デコードを調整するためのエンコーディング特別ルールを定義します。 |
| [setFontSavingMode](#setFontSavingMode-int-) | PDF を目的の形式で保存する際に使用されるフォント保存モードを定義します。 |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | HTML マークアップ生成に特定の要件がある場合があります。このパラメータは、PDF から HTML への変換時にそのような特定の要件に合わせて使用できる HTML 準備モードを定義します。 |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。 |
| [setImageResolution](#setImageResolution-int-) | 画像レンダリングの解像度を取得または設定します。 |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | 結果 HTML における単語内の文字配置モードを設定します。 |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | この属性はグラフィックパス線の最小幅を設定します。線の太さが 1px 未満の場合、Adobe Acrobat はこの値に丸めます。そのため、この属性は HTML ブラウザで同様の動作をエミュレートするために使用できます。 |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | この属性は、結果の HTML 文書でソース PDF ページを表す領域の周囲に境界線（存在する場合）を描画するために使用される設定の集合を表します。 |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | この属性は、ソース PDF ページを表す領域の周囲に結果 HTML ドキュメントで追加のページ余白（存在する場合）を設定するための設定集合を表します。 |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | 属性 'SplitOnPages=false' の場合、すべての入力 PDF ページを表す HTML が 1 つの大きな結果 HTML ファイルにまとめられます。このフラグは、結果 HTML が PDF ページを表す領域の流れがビューアの画面解像度に依存する形で生成されるかどうかを定義します。ビューア側の画面幅が十分に広く、横方向に 2 ページ以上を隣接させて表示できると仮定します。このフラグが true に設定されている場合、その機能が使用され、可能な限り多くのページが横方向に並んで表示され、次の横方向のページグループは最初のグループの下に表示されます。フラグが false の場合、ページは常に前のページの下に順次配置されます。 |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | 参照されるファイル（HTML、フォント、画像、CSS）がメインの HTML ファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを定義します。 |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | この属性は、テキストのグリフが単語や文字列にグループ化されないモードをオンにします。このモードは、ページ上のグリフの位置決め精度を最大限に保つことを可能にし、楽譜や個別に配置すべきグリフを含む文書の変換に使用できます。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。 |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | 変換された PDF にはラスタ画像が含まれることがあります。このパラメータは、PDF から HTML への変換時にそれらをどのように処理するかを定義します。 |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | 作成された HTML から、コンテンツが全くない上下の空白領域を削除するかどうかを定義します（該当する場合）。 |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | 属性 RenderTextAsImage が true に設定されている場合、ソースのテキストは HTML で画像になります。テキストを選択不可にしたり、HTML のテキストが正しくレンダリングされない場合に有用です。 |
| [setSaveFullFont](#setSaveFullFont-boolean-) | フルフォントが保存されることを示します。True Type フォントのみサポートします。デフォルトでは SaveFullFont = false で、変換器は文書のテキスト表示に必要な元フォントのサブセットのみを保存します。 |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Pdf は他の要素（例：画像）に影で隠されたテキストを含むことがありますが、Acrobat Reader ではクリップボードにコピーできることがあります（通常、文書に画像と OCR されたテキストが含まれる場合に起こります）。この設定は、変換器に対し、結果の HTML でそのようなテキストを透明な選択可能テキストとして保存し、Acrobat Reader の動作を模倣するかどうかを指示します（そうでない場合、通常は非表示でコピーできない形で保存されます）。 |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Pdf は透明なテキストを含むことがあり、クリップボードにコピーできることがあります（通常、文書に画像と OCR されたテキストが含まれる場合に起こります）。この設定は、変換器に対し、結果の HTML でそのようなテキストを透明な選択可能テキストとして保存するかどうかを指示します。 |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | この属性は、グリフと単語を文字列に順次グループ化することを指定します。例えば、タグと単語の順序が変換された HTML で異なり、同じ順序にしたい場合です。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。 |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | HTML として文書を保存する際に画像が検出された場合に保存する必要があるディレクトリへのパスを取得または設定します。パラメータが空または null の場合、画像ファイル（存在する場合）は HTML にリンクされた他のファイルと共に保存されます。CustomImageSavingStrategy プロパティが該当画像ファイルの処理に正常に使用された場合、これには影響しません。 |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | HTML として文書を保存する際に SVG 画像が検出された場合にのみ保存するディレクトリへのパスを取得または設定します。パラメータが空または null の場合、SVG ファイル（存在する場合）は他の画像ファイルと同じ場所（出力ファイルの近く）または SpecialImagesFolderIfAny オプションで指定された画像用の特別フォルダーに保存されます。CustomImageSavingStrategy プロパティが該当画像ファイルの処理に正常に使用された場合、これには影響しません。 |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | マルチページモードが選択されている場合（例：'SplitIntoPages' が 'true'）、この属性は各結果 HTML ページごとに別々の CSS ファイルを作成するかどうかを定義します。デフォルトではこの属性は false で、すべてのページに対して1つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS（ページごとに1つの CSS）の合計サイズは、1つの大きな CSS ファイルのサイズより通常ははるかに大きくなります。なぜなら、前者の場合、CSS クラスが各ページの複数の CSS ファイルに重複して存在するためです。したがって、この設定は、各 HTML ページを個別に将来的に処理したい場合にのみ使用する方が適しています。その場合、各ページごとの CSS サイズが最も重要な課題となります。 |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | ソース文書の各ページがそれぞれのターゲット HTML 文書に変換されるかどうかを示すフラグを設定します。つまり、結果の HTML が複数の HTML ページに分割されるかどうかです。 |
| [setTitle](#setTitle-java.lang.String-) | HTML ページのタイトルを取得または設定します。 |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF 自体はテキストの下線マーカーを含みません。下線はテキストの下に配置された線でエミュレートされます。このオプションは、変換器がその線がテキストの下線であると推測し、下線をグラフィックで描画する代わりに CSS に情報を入れることを許可します。 |
| [setUseZOrder](#setUseZOrder-boolean-) | 属性 UseZORder が true に設定されている場合、グラフィックとテキストは元の PDF 文書の Z 順序に従って結果の HTML 文書に追加されます。この属性が false の場合、すべてのグラフィックが単一レイヤーとして配置され、重なったオブジェクトで不要な効果が生じる可能性があります。 |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

HtmlSaveOptions クラスの新しいインスタンスを初期化します。

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

{@code HtmlSaveOptions} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fixedLayout |  | ブール値 |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
HtmlSaveOptions クラスの新しいインスタンスを初期化します。

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
HtmlSaveOptions クラスの新しいインスタンスを初期化します。

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

属性 'SplitOnPages=false' が設定されている場合、すべての入力 PDF ページを表す HTML 全体は別々の HTML ページに分割されず、1 つの大きな結果 HTML ファイルにまとめられます。ただし、各ソース PDF ページは HTML 内でそれぞれの矩形領域として表現されます（必要に応じて、特別な属性 'PageBorderIfAny' を使用してページの紙の端を示す境界線を付けることができます）。このパラメータは、ソース PDF ドキュメントのページを表す出力 HTML 領域の周囲に強制的に残す余白の幅を定義します。本質的に、PDF の \"paper\" ページの HTML 表現間の保証された間隔を定義する変換モードです。

**Returns:**
int value @deprecated AdditionalMarginWidthInPoints は非推奨です。代わりに PageMarginIfAny を使用してください。

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

このパラメータは、PDF から HTML への複合背景画像の変換中に必要なアンチエイリアス処理を定義します。

**Returns:**
AntialiasingProcessingType 要素 @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。

**Returns:**
int 値です。

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

PDFtoHTML コンバータが結果の CSS を生成する際、CSS クラス名（例: \".stl_01 {}\" … \".stl_NN {}\"）が生成され、結果の CSS で使用されます。このプロパティを使用すると、クラス名のプレフィックスを強制的に設定できます。例えば、すべてのクラス名を 'my_prefix_' で始めたい場合（つまり 'my_prefix_1' … 'my_prefix_NNN' のようになる）、変換前にこのプロパティに 'my_prefix_' を割り当てるだけです。このプロパティを変更しないまま（すなわち null のまま）にすると、コンバータが自動的にクラス名を生成します（例: \".stl_01 {}\" … \".stl_NN {}\"）。

**Returns:**
文字列値

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

このフィールドには、Pdf から Html への変換中に、作成された HTML ドキュメント全体またはそのページ（複数の HTML ページが生成される場合）に関連する CSS の保存処理に使用すべき保存戦略を指定できます（存在する場合）。CSS ファイルを特定の方法で処理したい場合は、該当するメソッドを作成し、そのデリゲートをこのプロパティに割り当ててください。

**Returns:**
CssSavingStrategy インスタンス

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

変換結果は 1 つまたは複数の HTML ページを含む場合があります。このプロパティに、変換中に作成された 1 つの HTML ページ（正確には外部リンクファイルがないマークアップ HTML）を処理するカスタムメソッドから作成されたデリゲートを割り当てることができます。その場合、ページの HTML をストリームやディスクに保存するなどの処理はカスタムコードで実行できます。この場合、HTML ページの保存に必要なすべての操作は提供されたメソッド内で行う必要があります。なぜかコンバータ側のコードで処理すべき場合は、カスタムコードのフラグ 'CustomProcessingCancelled' を 'htmlSavingInfo' パラメータの変数に設定してください。これにより、コンバータは外部カスタムコードが存在しないかのように、リソースの処理をコンバータ自身で実行するよう指示されます。

**Returns:**
HtmlPageMarkupSavingStrategy インスタンス

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> このハンドラは、変換の進捗イベントを処理するために使用できます。例えば、プログレスバーや現在処理中のページ数に関するメッセージを表示するために利用できます。コンソールに進捗を表示するハンドラのコード例は次のとおりです: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler インスタンス

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

このフィールドには、変換中に作成された参照リソースファイル（画像やフォントなど）をカスタマイズして処理するために使用すべき保存戦略を指定できます（存在する場合）。この戦略はリソースを処理し、生成された HTML で保存されたリソースの望ましい URL を表す文字列を返す必要があります。

**Returns:**
ResourceSavingStrategy インスタンス

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

このフィールドには、生成された結果HTMLに配置される対象CSSのURL（マルチページ生成が有効な場合はURLテンプレート - 詳細は下記参照）を返すカスタムメソッドを設定できます。例えば、変換時に標準のCSSファイル名の代わりに特定のURLを生成CSSに使用したい場合は、目的のURLを生成するメソッドを作成し、このプロパティに設定すればよいです。フラグ 'SplitCssIntoPages' が設定されている場合、このカスタム戦略（存在する場合）はCSSの正確なURLではなく、プレースホルダーをページ番号に置換する String.Format() 関数を使用して変換器内で解決できるテンプレート文字列を返す必要があります。このような場合に期待される戻り文字列の例は、'SomeTargetLocation-page_{0}.css'、'../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' です。

**Returns:**
CssUrlMakingStrategy インスタンス

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

システムに埋め込まれておらずインストールされていない文書フォントの代替として使用される、インストール済みフォントの名前を指定します。null の場合はデフォルトの代替フォントが使用されます。

**Returns:**
文字列値: フォント名

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

{@code HtmlDocumentTypeInternal} を取得します。

**Returns:**
この {@code HtmlDocumentTypeInternal}。

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

HTML に埋め込まれない PDF 埋め込みフォント名の一覧です。

**Returns:**
String 要素の配列

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

このプロパティを使用すると、変換対象となる文書のページを明示的に指定できます。このリスト内のページ番号は 1 から始まる番号でなければなりません。つまり、有効なページ番号は範囲 (1...[NumberOfPagesInConvertedDocument]) から取得する必要があります。このリストにおけるページの出現順序は、結果となる HTML ページの順序に影響しません。結果ページは常に元の PDF に存在する順序で表示されます。このリストが null（デフォルト） の場合、すべてのページが変換されます。このリスト内のページ番号が実際のページ範囲 (1-[amountOfPagesInDocument]) を超えると例外がスローされます。

**Returns:**
int 配列

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

この属性は、Flow モード（FixedLayout = false）用の全幅段落テキストを指定します。

**Returns:**
ブール値

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

現在の文書の PDF デコードを調整するためのエンコーディング特別ルールを定義します。

**Returns:**
FontEncodingRules 要素 @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

PDF を目的の形式で保存する際に使用されるフォント保存モードを定義します。

**Returns:**
FontSavingModes 要素 @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> 事前保存されたフォントのソースです。 </p>

**Returns:**
FontSourceCollection オブジェクト <hr> <p> フォントはキャッシュ目的で事前に保存され、その後 HTML 変換プロセスに渡される可能性があります。たとえば、ドキュメント分割シナリオや、単一のフォントセットで複数スレッドでドキュメントページを処理する場合に便利です。 </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

HTML マークアップ生成に特定の要件がある場合があります。このパラメータは、PDF から HTML への変換時にそのような特定の要件に合わせて使用できる HTML 準備モードを定義します。

**Returns:**
HtmlMarkupGenerationModes 要素 @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

画像レンダリングの解像度を取得または設定します。

**Returns:**
値: 解像度

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

結果 HTML における単語内の文字配置モードを設定します。

**Returns:**
LettersPositioningMethods 要素 @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

この属性はグラフィックパス線の最小幅を設定します。線の太さが 1px 未満の場合、Adobe Acrobat はこの値に丸めます。そのため、この属性は HTML ブラウザで同様の動作をエミュレートするために使用できます。

**Returns:**
float 値

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

この属性は、ソース PDF ページを表す領域の周囲に結果 HTML ドキュメントで境界線（存在する場合）を描画するために使用される設定の集合を表します。本質的には、PDF ページ自体に参照されているページ境界ではなく、ページの紙の端を表示することに関係します。

**Returns:**
BorderInfo インスタンス

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

この属性は、ソース PDF ページを表す領域の周囲に結果 HTML ドキュメントで追加のページ余白（存在する場合）を設定するための設定集合を表します。

**Returns:**
MarginInfo インスタンス

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

参照されるファイル（HTML、フォント、画像、CSS）がメインの HTML ファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを定義します。

**Returns:**
PartsEmbeddingModes 要素 @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

変換された PDF にはラスタ画像が含まれることがあります。このパラメータは、PDF から HTML への変換時にそれらをどのように処理するかを定義します。

**Returns:**
RasterImagesSavingModes 要素 @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

HTML として文書を保存する際に画像が検出された場合に保存する必要があるディレクトリへのパスを取得または設定します。パラメータが空または null の場合、画像ファイル（存在する場合）は HTML にリンクされた他のファイルと共に保存されます。CustomImageSavingStrategy プロパティが該当画像ファイルの処理に正常に使用された場合、これには影響しません。

**Returns:**
文字列値

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

HTML として文書を保存する際に SVG 画像が検出された場合にのみ保存するディレクトリへのパスを取得または設定します。パラメータが空または null の場合、SVG ファイル（存在する場合）は他の画像ファイルと同じ場所（出力ファイルの近く）または SpecialImagesFolderIfAny オプションで指定された画像用の特別フォルダーに保存されます。CustomImageSavingStrategy プロパティが該当画像ファイルの処理に正常に使用された場合、これには影響しません。

**Returns:**
文字列値

### getTitle {#getTitle--}
```
public final String getTitle()
```

HTML ページのタイトルを取得または設定します。

**Returns:**
文字列値

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

見つかった SVG グラフィック（存在する場合）が保存時に SVGZ 形式（圧縮）に変換されるかどうかを示すフラグを取得します。値: {@code HtmlDocumentType}。

**Returns:**
ブール値

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

属性 ConvertMarkedContentToLayers が true に設定されている場合、PDF のマークドコンテンツ（レイヤー）内のすべての要素が、レイヤー名を指定する \"data-pdflayer\" 属性を持つ HTML div に配置されます。このレイヤー名は PDF のマークドコンテンツのオプションプロパティから抽出されます。この属性が false（デフォルト）の場合、PDF のマークドコンテンツからレイヤーは作成されません。

**Returns:**
ブール値

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

HTML が固定レイアウトとして作成されているかどうかを示す値を取得します。

**Returns:**
値: {@code true} は [fixed layout] の場合; それ以外は {@code false}。

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。

**Returns:**
ブール値

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

属性 'SplitOnPages=false' の場合、すべての入力 PDF ページを表す HTML が 1 つの大きな結果 HTML ファイルにまとめられます。このフラグは、結果 HTML が PDF ページを表す領域の流れがビューアの画面解像度に依存する形で生成されるかどうかを定義します。ビューア側の画面幅が十分に広く、横方向に 2 ページ以上を隣接させて表示できると仮定します。このフラグが true に設定されている場合、その機能が使用され、可能な限り多くのページが横方向に並んで表示され、次の横方向のページグループは最初のグループの下に表示されます。フラグが false の場合、ページは常に前のページの下に順次配置されます。

**Returns:**
ブール値

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

この属性は、テキストのグリフが単語や文字列にグループ化されないモードをオンにします。このモードは、ページ上のグリフの位置決め精度を最大限に保つことを可能にし、楽譜や個別に配置すべきグリフを含む文書の変換に使用できます。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。

**Returns:**
ブール値

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

作成された HTML から、コンテンツが全くない上下の空白領域を削除するかどうかを定義します（該当する場合）。

**Returns:**
ブール値

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

属性 RenderTextAsImage が true に設定されている場合、ソースのテキストは HTML で画像になります。テキストを選択不可にしたり、HTML のテキストが正しくレンダリングされない場合に有用です。

**Returns:**
ブール値

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

フルフォントが保存されることを示します。True Type フォントのみサポートします。デフォルトでは SaveFullFont = false で、変換器は文書のテキスト表示に必要な元フォントのサブセットのみを保存します。

**Returns:**
ブール値

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

Pdf は他の要素（例：画像）に影で隠されたテキストを含むことがありますが、Acrobat Reader ではクリップボードにコピーできることがあります（通常、文書に画像と OCR されたテキストが含まれる場合に起こります）。この設定は、変換器に対し、結果の HTML でそのようなテキストを透明な選択可能テキストとして保存し、Acrobat Reader の動作を模倣するかどうかを指示します（そうでない場合、通常は非表示でコピーできない形で保存されます）。

**Returns:**
ブール値

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Pdf は透明なテキストを含むことがあり、クリップボードにコピーできることがあります（通常、文書に画像と OCR されたテキストが含まれる場合に起こります）。この設定は、変換器に対し、結果の HTML でそのようなテキストを透明な選択可能テキストとして保存するかどうかを指示します。

**Returns:**
ブール値

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

この属性は、グリフと単語を文字列に順次グループ化することを指定します。例えば、タグと単語の順序が変換された HTML で異なり、同じ順序にしたい場合です。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。

**Returns:**
ブール値

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

マルチページモードが選択されている場合（例：'SplitIntoPages' が 'true'）、この属性は各結果 HTML ページごとに別々の CSS ファイルを作成するかどうかを定義します。デフォルトではこの属性は false で、すべてのページに対して1つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS（ページごとに1つの CSS）の合計サイズは、1つの大きな CSS ファイルのサイズより通常ははるかに大きくなります。なぜなら、前者の場合、CSS クラスが各ページの複数の CSS ファイルに重複して存在するためです。したがって、この設定は、各 HTML ページを個別に将来的に処理したい場合にのみ使用する方が適しています。その場合、各ページごとの CSS サイズが最も重要な課題となります。

**Returns:**
ブール値

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

ソース文書の各ページがそれぞれのターゲット HTML 文書に変換されるかどうかを示すフラグを取得します。つまり、結果の HTML が複数の HTML ページに分割されるかどうかです。

**Returns:**
ブール値

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

PDF 自体はテキストの下線マーカーを含みません。下線はテキストの下に配置された線でエミュレートされます。このオプションは、変換器がその線がテキストの下線であると推測し、下線をグラフィックで描画する代わりに CSS に情報を入れることを許可します。

**Returns:**
ブール値

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

属性 UseZORder が true に設定されている場合、グラフィックとテキストは元の PDF 文書の Z 順序に従って結果の HTML 文書に追加されます。この属性が false の場合、すべてのグラフィックが単一レイヤーとして配置され、重なったオブジェクトで不要な効果が生じる可能性があります。

**Returns:**
ブール値

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

属性 'SplitOnPages=false' が設定されている場合、すべての入力 PDF ページを表す HTML 全体は別々の HTML ページに分割されず、1 つの大きな結果 HTML ファイルにまとめられます。ただし、各ソース PDF ページは HTML 内でそれぞれの矩形領域として表現されます（必要に応じて、特別な属性 'PageBorderIfAny' を使用してページの紙の端を示す境界線を付けることができます）。このパラメータは、ソース PDF ドキュメントのページを表す出力 HTML 領域の周囲に強制的に残す余白の幅を定義します。本質的に、PDF の \"paper\" ページの HTML 表現間の保証された間隔を定義する変換モードです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int value @deprecated AdditionalMarginWidthInPoints は非推奨です。代わりに PageMarginIfAny を使用してください。 |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

このパラメータは、PDF から HTML への複合背景画像の変換中に必要なアンチエイリアス処理を定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| antialiasingProcessing |  | AntialiasingProcessingType 要素 @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

バッチ変換がソースと宛先のフォーマットペアに適用可能な場合のバッチサイズを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

SVG グラフィック（存在する場合）が保存時に SVGZ 形式に圧縮（zip）されるかどうかを示すフラグを設定します。値: {@code HtmlDocumentType}。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

属性 ConvertMarkedContentToLayers が true に設定されている場合、PDF のマークドコンテンツ（レイヤー）内のすべての要素が、レイヤー名を指定する \"data-pdflayer\" 属性を持つ HTML div に配置されます。このレイヤー名は PDF のマークドコンテンツのオプションプロパティから抽出されます。この属性が false（デフォルト）の場合、PDF のマークドコンテンツからレイヤーは作成されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
PDFtoHTML コンバータが結果の CSS を生成する際、CSS クラス名（例: \".stl_01 {}\" … \".stl_NN {}\"）が生成され、結果の CSS で使用されます。このプロパティを使用すると、クラス名のプレフィックスを強制的に設定できます。例えば、すべてのクラス名を 'my_prefix_' で始めたい場合（つまり 'my_prefix_1' … 'my_prefix_NNN' のようになる）、変換前にこのプロパティに 'my_prefix_' を割り当てるだけです。このプロパティを変更しないまま（すなわち null のまま）にすると、コンバータが自動的にクラス名を生成します（例: \".stl_01 {}\" … \".stl_NN {}\"）。

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
このフィールドには、Pdf から Html への変換中に、作成された HTML ドキュメント全体またはそのページ（複数の HTML ページが生成される場合）に関連する CSS の保存処理に使用すべき保存戦略を指定できます（存在する場合）。CSS ファイルを特定の方法で処理したい場合は、該当するメソッドを作成し、そのデリゲートをこのプロパティに割り当ててください。

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
変換結果は1つまたは複数の HTML ページを含む可能性があります。このプロパティには、変換中に作成された1つの HTML ページ（正確には外部リンクファイルのないマークアップ HTML）を処理するカスタムメソッドから作成されたデリゲートを割り当てることができます。

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
このハンドラは、変換進行イベントを処理するために使用できます（例）。

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
このフィールドには、変換中に使用すべき保存戦略（存在する場合）を指定できます。これは、作成された参照リソースファイル（画像やフォントなど）をカスタマイズして処理するためのものです。

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
このフィールドには、生成された結果 HTML に配置すべき対象 CSS の URL（またはマルチページ生成が有効な場合の URL テンプレート）を返すカスタムメソッドを含めることができます。

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
システムに埋め込まれておらずインストールされていない文書フォントの代替として使用される、インストール済みフォントの名前を指定します。null の場合はデフォルトの代替フォントが使用されます。

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
{@code HtmlDocumentType} を設定します。

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
HTML に埋め込まれない PDF 埋め込みフォント名の一覧です。

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

このプロパティを使用すると、変換対象となる文書のページを明示的に指定できます。このリスト内のページ番号は 1 から始まる番号でなければなりません。つまり、有効なページ番号は範囲 (1...[NumberOfPagesInConvertedDocument]) から取得する必要があります。このリストにおけるページの出現順序は、結果となる HTML ページの順序に影響しません。結果ページは常に元の PDF に存在する順序で表示されます。このリストが null（デフォルト） の場合、すべてのページが変換されます。このリスト内のページ番号が実際のページ範囲 (1-[amountOfPagesInDocument]) を超えると例外がスローされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

HTML が固定レイアウトとして作成されるかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | : {@code true} は [fixed layout] の場合; それ以外は {@code false}。 |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

この属性は、Flow モード（FixedLayout = false）用の全幅段落テキストを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

現在の文書の PDF デコードを調整するためのエンコーディング特別ルールを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontEncodingStrategy |  | FontEncodingRules 要素 @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

PDF を目的の形式で保存する際に使用されるフォント保存モードを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontSavingMode |  | FontSavingModes 要素 @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

HTML マークアップ生成に特定の要件がある場合があります。このパラメータは、PDF から HTML への変換時にそのような特定の要件に合わせて使用できる HTML 準備モードを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | HtmlMarkupGenerationModes 要素 @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

画像レンダリングの解像度を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 値: 解像度 |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
結果 HTML における単語内の文字配置モードを設定します。

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

この属性はグラフィックパス線の最小幅を設定します。線の太さが 1px 未満の場合、Adobe Acrobat はこの値に丸めます。そのため、この属性は HTML ブラウザで同様の動作をエミュレートするために使用できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
この属性は、結果の HTML 文書でソース PDF ページを表す領域の周囲に境界線（存在する場合）を描画するために使用される設定の集合を表します。

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
この属性は、ソース PDF ページを表す領域の周囲に結果 HTML ドキュメントで追加のページ余白（存在する場合）を設定するための設定集合を表します。

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

属性 'SplitOnPages=false' の場合、すべての入力 PDF ページを表す HTML が 1 つの大きな結果 HTML ファイルにまとめられます。このフラグは、結果 HTML が PDF ページを表す領域の流れがビューアの画面解像度に依存する形で生成されるかどうかを定義します。ビューア側の画面幅が十分に広く、横方向に 2 ページ以上を隣接させて表示できると仮定します。このフラグが true に設定されている場合、その機能が使用され、可能な限り多くのページが横方向に並んで表示され、次の横方向のページグループは最初のグループの下に表示されます。フラグが false の場合、ページは常に前のページの下に順次配置されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | ブール値 |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

参照されるファイル（HTML、フォント、画像、CSS）がメインの HTML ファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| partsEmbeddingMode |  | PartsEmbeddingModes 要素 @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

この属性は、テキストのグリフが単語や文字列にグループ化されないモードをオンにします。このモードは、ページ上のグリフの位置決め精度を最大限に保つことを可能にし、楽譜や個別に配置すべきグリフを含む文書の変換に使用できます。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

変換された PDF にはラスタ画像が含まれることがあります。このパラメータは、PDF から HTML への変換時にそれらをどのように処理するかを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rasterImagesSavingMode |  | RasterImagesSavingModes 要素 @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

作成された HTML から、コンテンツが全くない上下の空白領域を削除するかどうかを定義します（該当する場合）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | ブール値 |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

属性 RenderTextAsImage が true に設定されている場合、ソースのテキストは HTML で画像になります。テキストを選択不可にしたり、HTML のテキストが正しくレンダリングされない場合に有用です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

フルフォントが保存されることを示します。True Type フォントのみサポートします。デフォルトでは SaveFullFont = false で、変換器は文書のテキスト表示に必要な元フォントのサブセットのみを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

Pdf は他の要素（例：画像）に影で隠されたテキストを含むことがありますが、Acrobat Reader ではクリップボードにコピーできることがあります（通常、文書に画像と OCR されたテキストが含まれる場合に起こります）。この設定は、変換器に対し、結果の HTML でそのようなテキストを透明な選択可能テキストとして保存し、Acrobat Reader の動作を模倣するかどうかを指示します（そうでない場合、通常は非表示でコピーできない形で保存されます）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | ブール値 |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Pdf は透明なテキストを含むことがあり、クリップボードにコピーできることがあります（通常、文書に画像と OCR されたテキストが含まれる場合に起こります）。この設定は、変換器に対し、結果の HTML でそのようなテキストを透明な選択可能テキストとして保存するかどうかを指示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| saveTransparentTexts |  | ブール値 |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

この属性は、グリフと単語を文字列に順次グループ化することを指定します。例えば、タグと単語の順序が変換された HTML で異なり、同じ順序にしたい場合です。このパラメータは、FixedLayout 属性の値が true の場合にのみ文書に適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
HTML として文書を保存する際に画像が検出された場合に保存する必要があるディレクトリへのパスを取得または設定します。パラメータが空または null の場合、画像ファイル（存在する場合）は HTML にリンクされた他のファイルと共に保存されます。CustomImageSavingStrategy プロパティが該当画像ファイルの処理に正常に使用された場合、これには影響しません。

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
HTML として文書を保存する際に SVG 画像が検出された場合にのみ保存するディレクトリへのパスを取得または設定します。パラメータが空または null の場合、SVG ファイル（存在する場合）は他の画像ファイルと同じ場所（出力ファイルの近く）または SpecialImagesFolderIfAny オプションで指定された画像用の特別フォルダーに保存されます。CustomImageSavingStrategy プロパティが該当画像ファイルの処理に正常に使用された場合、これには影響しません。

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

マルチページモードが選択されている場合（例：'SplitIntoPages' が 'true'）、この属性は各結果 HTML ページごとに別々の CSS ファイルを作成するかどうかを定義します。デフォルトではこの属性は false で、すべてのページに対して1つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS（ページごとに1つの CSS）の合計サイズは、1つの大きな CSS ファイルのサイズより通常ははるかに大きくなります。なぜなら、前者の場合、CSS クラスが各ページの複数の CSS ファイルに重複して存在するためです。したがって、この設定は、各 HTML ページを個別に将来的に処理したい場合にのみ使用する方が適しています。その場合、各ページごとの CSS サイズが最も重要な課題となります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

ソース文書の各ページがそれぞれのターゲット HTML 文書に変換されるかどうかを示すフラグを設定します。つまり、結果の HTML が複数の HTML ページに分割されるかどうかです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTitle {#setTitle-java.lang.String-}
HTML ページのタイトルを取得または設定します。

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

PDF 自体はテキストの下線マーカーを含みません。下線はテキストの下に配置された線でエミュレートされます。このオプションは、変換器がその線がテキストの下線であると推測し、下線をグラフィックで描画する代わりに CSS に情報を入れることを許可します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | ブール値 |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

属性 UseZORder が true に設定されている場合、グラフィックとテキストは元の PDF 文書の Z 順序に従って結果の HTML 文書に追加されます。この属性が false の場合、すべてのグラフィックが単一レイヤーとして配置され、重なったオブジェクトで不要な効果が生じる可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
