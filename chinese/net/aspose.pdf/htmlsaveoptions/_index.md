---
title: "类 HtmlSaveOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlSaveOptions 类。导出为 Html 格式的保存选项"
type: docs
weight: 5690
url: /zh/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

导出为 HTML 格式的保存选项

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
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | 如果批量转换适用于源和目标格式对，则定义批处理大小。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。可提升 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | 获取或设置指示在保存期间是否将找到的 SVG 图形（如果有）压缩（打包）为 SVGZ 格式的标志。 |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | 如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（图层）中的所有元素将放入具有 \"data-pdflayer\" 属性并指定图层名称的 HTML div 中。该图层名称将从 PDF 标记内容的可选属性中提取。如果此属性为 false（默认），则不会从 PDF 标记内容创建任何图层。 |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | 指定已安装字体的名称，用于替代系统中未嵌入且未安装的文档字体。如果为 null，则使用默认替代字体。 |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | 获取或设置 [`HtmlDocumentType`](../htmldocumenttype/)。 |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | 使用此属性，您可以明确指定文档的哪些页面应被转换。此列表中的页面必须使用从 1 开始的编号。即，页面编号必须取自范围 (1...[NumberOfPagesInConvertedDocument])。列表中页面出现的顺序不影响结果 HTML 页面中的顺序——结果页面始终按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（默认情况下），则会转换所有页面。如果此列表中的任何页面编号超出现有页面的范围 (1-[amountOfPagesInDocument])，将抛出异常。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用了从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | 获取或设置指示 HTML 是否以固定布局创建的值。 |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | 此属性指定流模式下的全宽段落文本，FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | 预保存字体的字体来源。 |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | 在转换过程中，指定大小或更小的文本将被忽略。我们不会删除这些文本，只是忽略它们，并且不将其传输到输出文件。 |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | 获取或设置指示是否忽略与缺少字体相关错误的标志。true - 表示将忽略缺少字体的错误。处理期间将跳过引用不正确资源的文本段。默认值为 false。 |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | 获取或设置图像渲染的分辨率。 |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | 此属性设置图形路径线的最小宽度。如果线的粗细小于 1px，Adobe Acrobat 会将其四舍五入为此值。因此可以使用此属性在 HTML 浏览器中模拟此行为。 |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | 此属性开启一种模式，在该模式下文本字形不会被分组为单词和字符串。此模式允许在页面上定位字形时保持最高精度，可用于转换包含音乐符号或需要相互独立放置的字形的文档。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | 如果将属性 RenderTextAsImage 设置为 true，来源文本将在 HTML 中变为图像。这在需要使文本不可选中或 HTML 文本渲染不正确时可能有用。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | 指示将保存完整字体，仅支持 True Type 字体。默认情况下 SaveFullFont = false，转换器仅保存文档文本显示所需的初始字体子集。 |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | 此属性指定字形和单词的顺序分组为字符串。例如，标签和单词在转换后的 HTML 中顺序不同，而您希望它们匹配。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | 当选择多页模式（即 'SplitIntoPages' 为 true）时，此属性决定是否为每个生成的 HTML 页面创建单独的 CSS 文件。默认情况下此属性为 false，所有页面共用一个大的公共 CSS。以此模式生成的所有 CSS（每页一个 CSS）的总体大小通常远大于单个大 CSS 文件的大小，因为前者会在每个页面的多个 CSS 文件中出现重复的 CSS 类。因此，仅在您需要对每个 HTML 页面独立进行后续处理时才建议使用此设置，因为此时每个页面单独的 CSS 大小是最关键的问题。 |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | 获取或设置标志，以指示是否将源文档的每页转换为其自己的目标 HTML 文档，即结果 HTML 是否会被拆分为多个 HTML 页面。 |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | 获取或设置 HTML 页面标题。 |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | 用于将图像碎片合并为一张图片的标志。 |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | 如果将属性 UseZORder 设置为 true，图形和文本将按照原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。如果此属性为 false，所有图形将放置在单一层上，可能会导致重叠对象出现不必要的效果。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue（继续）或 Abort（中止）。Continue 为默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | 此参数定义在将复合背景图像从 PDF 转换为 HTML 过程中所需的抗锯齿措施。 |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | 当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（例如 ".stl_01 {}" … ".stl_NN {}"）会被生成并用于结果 CSS。此属性允许强制设置类名前缀。例如，如果您希望所有类名以 'my_prefix_' 开头（即类似 'my_prefix_1' … 'my_prefix_NNN'），只需在转换前将 'my_prefix_' 赋给此属性。如果此属性保持未设置（即值为 null），转换器将自行生成类名（如 ".stl_01 {}" … ".stl_NN {}"）。 |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | 此字段可以包含在 Pdf 转换为 Html 期间用于处理整个创建的 HTML 文档或其页面（如果生成多个 HTML 页面）相关 CSS 保存的策略（如果提供）。如果您想以特定方式处理 CSS 文件，请创建相应的方法并将其委托分配给此属性。 |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | 转换结果可能包含一个或多个 HTML 页面。您可以将自定义方法生成的委托分配给此属性，以实现对在转换期间创建的单个 HTML 页面（准确来说是标记 HTML，不包含任何外部链接文件）的处理。在这种情况下，诸如将页面的 HTML 保存到流或磁盘的处理可以在自定义代码中完成。所有保存 HTML 页面所需的操作必须在提供的方法代码中执行，因为转换器内部的保存代码将不再使用。如果出于某种原因必须由转换器自身的代码而非自定义代码完成处理，请在自定义代码中设置 'htmlSavingInfo' 参数变量的标志 'CustomProcessingCancelled'：这将通知转换器应自行完成该资源的所有必要处理步骤，就像没有任何外部自定义代码一样。 |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | 此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | 此字段可以包含在转换期间用于自定义处理已创建的引用资源文件（如图像和字体）——这些文件与已保存的 HTML 节点相关的保存策略（如果提供）。该策略必须处理资源并返回表示生成的 HTML 中已保存资源的期望 URL 的字符串。 |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | 此字段可以包含自定义方法，该方法返回应放入生成的结果 HTML 中的 CSS URL（如果启用多页生成，则返回 URL 模板——详见下文）。例如，如果您希望转换器在生成的 CSS 中使用特定的 URL 而不是标准的 CSS 文件名，只需创建并将生成所需 URL 的方法放入此属性。如果设置了标志 'SplitCssIntoPages'，则此自定义策略（若存在）必须返回不是 CSS 的确切 URL，而是模板字符串，转换器内部使用 string.Format() 将占位符替换为页码后即可解析为相应页面的 CSS URL。此类情况下的返回字符串示例包括：'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}'。 |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | PDF 嵌入字体名称列表，这些字体不会嵌入到 HTML 中。 |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | 定义编码特殊规则，以调优当前文档的 PDF 解码 |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | 定义在将 PDF 保存为所需格式时使用的字体保存模式 |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | 有时会出现对生成 HTML 标记的特定需求。此参数定义在 PDF 转换为 HTML 时可用于满足此类特定需求的 HTML 准备模式。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | 设置结果 HTML 中单词中字母的定位模式 |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | 此属性表示用于在结果 HTML 文档中围绕表示源 PDF 页面区域绘制边框（如果有）的设置集合。实质上它涉及显示页面的纸张边缘，而不是 PDF 页面本身引用的页面边框。 |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | 此属性表示在结果 HTML 文档中围绕表示源 PDF 页面区域的额外页面边距（如果有）的设置集合。 |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | 如果属性 'SplitOnPages=false'，则表示所有输入 PDF 页面 的完整 HTML 将放入一个大的结果 HTML 文件中。此标志定义是否以使结果 HTML 中表示 PDF 页面的区域流动取决于查看器屏幕分辨率的方式生成结果 HTML。假设查看器侧的屏幕宽度足够大，可以在水平方向上并排放置 2 页或更多页面。如果此标志设置为 true，则会使用此功能（尽可能多的页面将在水平方向并排显示，随后下一组水平页面显示在第一组下方）。否则，页面将以如下方式流动：下一页始终位于前一页下方。 |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | 它定义是否将引用的文件（HTML、字体、图像、CSS）嵌入到主 HTML 文件中，还是生成独立的二进制实体 |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | 转换后的 PDF 可能包含光栅图像，此参数定义在 PDF 转换为 HTML 过程中应如何处理这些图像 |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | 定义在生成的 HTML 中是否会移除顶部和底部没有任何内容的空白区域（如果存在）。 |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF 可能包含被其他元素（例如图像）遮挡的文本，但在 Acrobat Reader 中仍可复制到剪贴板（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告诉转换器是否需要将此类文本保存为结果 HTML 中的透明可选文本，以模拟 Acrobat Reader 的行为（否则此类文本通常会被保存为隐藏，无法复制到剪贴板）。 |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF 可能包含可复制到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告诉转换器是否需要将此类文本保存为结果 HTML 中的透明可选文本。 |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | 获取或设置在将文档保存为 HTML 时必须保存任何遇到的图像的目录路径。如果参数为空或 null，则图像文件（如果有）将与链接到 HTML 的其他文件一起保存。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。 |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | 获取或设置在将文档保存为 HTML 时必须保存仅 SVG 图像的目录路径。如果参数为空或 null，则 SVG 文件（如果有）将与其他图像文件（位于输出文件附近）一起保存，或保存到特殊图像文件夹（如果在 SpecialImagesFolderIfAny 选项中指定）。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了此类可见边界，请尝试使用此设置以消除该不良效果。注意！此质量优化通常会显著降低转换速度，因此请仅在确实必要时使用此选项。 |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF 本身不包含文本的下划线标记，而是通过位于文本下方的线条来模拟。此选项允许转换器尝试猜测某条线是否为文本的下划线，并将此信息写入 CSS，而不是以图形方式绘制下划线。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 HTML 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF 文件的路径。
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// 输出 HTML 文件的路径。
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// 初始化 HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// 保存 HTML 文件
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

### 另请参见

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


