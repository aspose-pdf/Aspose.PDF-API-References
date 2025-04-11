---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptions 类。导出到 Html 格式的保存选项
type: docs
weight: 5560
url: /zh/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions 类

导出到 Html 格式的保存选项

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | 初始化 `HtmlSaveOptions` 类的新实例。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | 初始化 `HtmlSaveOptions` 类的新实例。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | 初始化 `HtmlSaveOptions` 类的新实例。 |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | 初始化 `HtmlSaveOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | 定义批处理大小，如果批处理转换适用于源和目标格式对。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，指示在准备 aps 页面时是否将字体字形缓存。提高从 pdf 转换到其他格式的性能，但增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，指示在文档保存到响应后，响应对象是否将被关闭。 |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | 获取或设置标志，指示在保存期间是否将找到的 SVG 图形（如果有）压缩（压缩）为 SVGZ 格式 |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | 如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（图层）中的所有元素将放入带有 "data-pdflayer" 属性的 HTML div 中，指定图层名称。此图层名称将从 PDF 标记内容的可选属性中提取。如果此属性为 false（默认值），则不会从 PDF 标记内容创建任何图层。 |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | 指定用于替代任何未嵌入且未安装在系统中的文档字体的已安装字体的名称。如果为 null，则使用默认替代字体。 |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | 获取或设置 [`HtmlDocumentType`](../htmldocumenttype/)。 |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | 使用此属性，您可以明确指定应转换文档的哪些页面。此列表中的页面必须具有基于 1 的编号。即有效的页面编号必须取自范围 (1...[NumberOfPagesInConvertedDocument])。此列表中页面的出现顺序不会影响结果 HTML 页面中的顺序 - 在结果页面中，页面始终按其在源 PDF 中出现的顺序排列。如果此列表为 null（默认值），则将转换所有页面。如果此列表中的任何页面编号超出现有页面的范围（1-[amountOfPagesInDocument]），将抛出异常。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用从具有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | 获取或设置一个值，指示 HTML 是否作为固定布局创建。 |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | 此属性指定流模式下的全宽段落文本，FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | 预保存字体的字体源。 |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | 在转换过程中，将忽略指定大小或更小的文本。我们不会删除此文本，而是忽略它并不将其传输到输出文件 |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | 获取或设置指示将忽略与缺少字体相关的错误的值。 true - 表示将忽略缺少字体的错误。引用不正确资源的文本段在处理过程中将被跳过。默认值为 false |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | 获取或设置图像渲染的分辨率。 |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | 此属性设置图形路径线的最小宽度。如果线的厚度小于 1px，Adobe Acrobat 会将其四舍五入到此值。因此，此属性可用于模拟 HTML 浏览器的此行为。 |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | 此属性启用文本字形不被分组为单词和字符串的模式。此模式允许在页面上保持字形定位的最大精度，并且可以用于转换包含音乐符号或应彼此分开的字形的文档。此参数仅在 FixedLayout 属性的值为 true 时应用于文档。 |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | 如果属性 RenderTextAsImage 设置为 true，则源中的文本在 HTML 中变为图像。可能有助于使文本不可选择或 HTML 文本未正确呈现。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | 指示将保存完整字体，仅支持 True Type 字体。默认情况下 SaveFullFont = false，转换器保存显示文档文本所需的初始字体的子集。 |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | 此属性指定字形和单词的顺序分组为字符串。例如，标签和单词在转换后的 HTML 中的顺序不同，您希望它们匹配。此参数仅在 FixedLayout 属性的值为 true 时应用于文档。 |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | 当选择多页模式（即 'SplitIntoPages' 为 'true'）时，此属性定义是否应为每个结果 HTML 页面创建单独的 CSS 文件。默认情况下，此属性为 false，因此将为所有创建的页面创建一个大的公共 CSS。在这种模式下生成的所有 CSS 的总大小（每页一个 CSS）通常比一个大 CSS 文件的大小大得多，因为在前一种情况下，CSS 类在每个页面的多个 CSS 文件中重复。因此，此设置最好仅在您对将来独立处理每个 HTML 页面感兴趣时使用，因此每个页面的 CSS 的大小是最关键的问题。 |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | 获取或设置标志，指示源文档的每个页面是否将转换为其自己的目标 HTML 文档，即结果 HTML 是否将拆分为多个 HTML 页面。 |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | 获取或设置 HTML 页面标题。 |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | 将图像片段合并为一张图片的标志。 |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | 如果属性 UseZOrder 设置为 true，则图形和文本将根据原始 PDF 文档中的 Z 顺序添加到结果 HTML 文档中。如果此属性为 false，则所有图形将作为单个图层放置，这可能会导致重叠对象的一些不必要效果。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。 WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，保存操作继续，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | 此参数定义在将复合背景图像从 PDF 转换为 HTML 时所需的抗锯齿措施 |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | 当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（类似 ".stl_01 {}" ... ".stl_NN {}"）在结果 CSS 中生成并使用。此属性允许强制设置类名前缀。例如，如果您希望所有类名以 'my_prefix_' 开头（即类似 'my_prefix_1' ... 'my_prefix_NNN'），则只需在转换之前将 'my_prefix_' 分配给此属性。如果此属性保持不变（即 null 将作为值），则转换器将自行生成类名（将是类似 ".stl_01 {}" ... ".stl_NN {}"） |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | 此字段可以包含在转换 PDF 到 HTML 期间必须使用的保存策略（如果存在），用于处理与创建的 HTML 文档整体或其页面（如果生成多个 HTML 页面）相关的 CSS 的保存。如果您希望以某种特定方式处理 CSS 文件，请创建相关方法并将从中创建的委托分配给此属性。 |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | 转换结果可以包含一个或多个 HTML 页面。您可以将此属性分配给从自定义方法创建的委托，该方法实现对在转换过程中创建的一个 HTML 页面（准确地说是标记 HTML，没有任何外部链接文件）的处理。在这种情况下，处理（例如将页面的 HTML 保存到流或磁盘）可以在该自定义代码中完成。在这种情况下，必须在提供的方法代码中采取保存 HTML 页面的所有必要操作，因为转换器中的结果保存代码将不再使用。如果出于某种原因必须由转换器的代码本身而不是自定义代码进行处理，请在自定义代码中设置 'htmlSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志：这将向转换器发出信号，指示必须以与没有任何外部自定义代码进行处理的方式相同，在转换器中完成该资源的所有必要处理步骤。 |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | 此处理程序可用于处理转换进度事件，例如，它可以用于显示进度条或有关当前处理页面数量的消息，处理程序代码的示例在控制台上显示进度： |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | 此字段可以包含在转换期间必须使用的保存策略（如果存在），用于自定义处理与保存的 HTML 节点相关的创建引用资源文件（如图像和字体）。该策略必须处理资源并返回表示生成的 HTML 中保存资源的期望 URL 的字符串。 |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | 此字段可以包含返回 URL（或 URL 模板，如果启用多页生成 - 见下文）的方法，该方法应放入生成的结果 HTML 中的主题 CSS 中。例如，如果您希望转换器在生成的 CSS 中放入某个特定 URL，而不是标准 CSS 文件名，则只需创建并放入此属性的方法，该方法生成期望的 URL。如果标志 'SplitCssIntoPages' 设置，则此自定义策略（如果有）必须返回的不是 CSS 的确切 URL，而是模板字符串，该字符串（在转换器内部使用 string.Format() 函数替换占位符的页面编号后）可以解析为该页面的 CSS 的 URL。此情况下预期返回字符串的示例包括：'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | 不会嵌入到 HTML 中的 PDF 嵌入字体名称列表。 |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | 定义编码特殊规则以调整当前文档的 PDF 解码 |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | 定义在保存 PDF 到所需格式期间将使用的字体保存模式 |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | 有时对 HTML 标记生成有特定要求。此参数定义在将 PDF 转换为 HTML 期间可以使用的 HTML 准备模式，以满足这些特定要求。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | 设置结果 HTML 中单词中字母的定位模式 |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | 此属性表示用于在结果 HTML 文档中绘制边框（如果有）的设置集，围绕表示源 PDF 页面区域。实质上，它涉及到显示页面的纸张边缘，而不是 PDF 页面本身引用的页面边框。 |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | 此属性表示在结果 HTML 文档中围绕表示源 PDF 页面区域的额外页面边距（如果有）的设置集。 |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | 如果属性 'SplitOnPages=false'，则表示所有输入 PDF 页面将放入一个大的结果 HTML 文件中。此标志定义结果 HTML 是否将以这样的方式生成，即表示 PDF 页面区域在结果 HTML 中的流动将取决于查看者的屏幕分辨率。假设查看者侧的屏幕宽度足够大，可以将 2 页或更多页面并排放置在水平方向上。如果此标志设置为 true，则将利用此机会（尽可能多的页面将并排显示在水平方向上，然后下一组水平页面将显示在第一组下方）。否则，页面将以这样的方式流动：下一页始终在上一页下方。 |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | 它定义引用文件（HTML、字体、图像、CSS）是否将嵌入到主 HTML 文件中，还是作为单独的二进制实体生成 |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | 转换后的 PDF 可能包含光栅图像。此参数定义在将 PDF 转换为 HTML 期间应如何处理它们 |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | 定义在创建的 HTML 中是否将删除顶部和底部没有任何内容的空区域（如果有）。 |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF 可能包含被其他元素（例如图像）阴影处理的文本，但可以在 Acrobat Reader 中选择（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告诉转换器是否需要将这些文本保存为结果 HTML 中的透明可选择文本，以模仿 Acrobat Reader 的行为（否则这些文本通常会被保存为隐藏的，不可复制到剪贴板）。 |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF 可能包含可以选择到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告诉转换器是否需要将这些文本保存为结果 HTML 中的透明可选择文本 |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | 获取或设置必须保存任何图像的目录路径，如果在将文档保存为 HTML 时遇到它们。如果参数为空或 null，则图像文件（如果有）将与链接到 HTML 的其他文件一起保存。如果成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则不会影响任何内容。 |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | 获取或设置必须仅保存 SVG 图像的目录路径，如果在将文档保存为 HTML 时遇到它们。如果参数为空或 null，则 SVG 文件（如果有）将与其他图像文件（靠近输出文件）一起保存，或在图像的特殊文件夹中（如果在 SpecialImagesFolderIfAny 选项中指定）。如果成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则不会影响任何内容。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由几个相同的平铺背景图像构成的背景图像（页面或表格单元格）。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来包含这些相同背景图像部分之间的可见边界，请尝试使用此设置消除这种不必要的效果。注意！此质量优化通常会显著减慢转换速度，因此，请仅在确实必要时使用此选项。 |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF 本身不包含文本的下划线标记。它通过位于文本下方的线条进行模拟。此选项允许转换器尝试猜测这条线是否是文本的下划线，并将此信息放入 CSS 中，而不是以图形方式绘制下划线 |

## 示例

以下示例演示如何将 PDF 文件转换为 HTML 文件

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

### 另请参阅

* 类 [UnifiedSaveOptions](../unifiedsaveoptions/)
* 接口 [IPageSetOptions](../ipagesetoptions/)
* 接口 [IPipelineOptions](../ipipelineoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)