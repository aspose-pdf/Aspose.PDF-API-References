---
title: HtmlSaveOptions
second_title: Aspose.PDF for .NET API 参考
description: 保存导出为 Html 格式的选项
type: docs
weight: 3430
url: /zh/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

保存导出为 Html 格式的选项

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions#constructor)() | 初始化[`HtmlSaveOptions`](../htmlsaveoptions)类的新实例。 |
| [HtmlSaveOptions](htmlsaveoptions#constructor_3)(bool) | 初始化[`HtmlSaveOptions`](../htmlsaveoptions)类的新实例。 |
| [HtmlSaveOptions](htmlsaveoptions#constructor_1)(HtmlDocumentType) | 初始化[`HtmlSaveOptions`](../htmlsaveoptions)类的新实例。 |
| [HtmlSaveOptions](htmlsaveoptions#constructor_2)(HtmlDocumentType, bool) | 初始化[`HtmlSaveOptions`](../htmlsaveoptions)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize) { get; set; } | 如果批量转换适用，则定义批量大小 到源和目标格式对。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | 获取或设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany) { get; set; } | 获取或设置指示 找到的 SVG 图形（如果有）是否将被压缩（压缩）的标志 保存期间转换为 SVGZ 格式 |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers) { get; set; } | 如果属性 ConvertMarkedContentToLayers 设置为 true，则标记为 内容（层）的 PDF 中的所有元素将被放入带有“数据”的 HTML div -pdflayer" 属性指定图层名称。 此图层名称将从 PDF 标记内容的可选属性中提取。 如果此属性为 false（默认情况下），则不会从 PDF 标记的内容创建任何图层。 |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname) { get; set; } | 指定已安装字体的名称，用于替换 任何未嵌入且未安装在系统中的文档字体。 如果为 null，则使用默认替换字体。 |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype) { get; set; } | 获取或设置[`HtmlDocumentType`](../htmldocumenttype)。 |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages) { get; set; } | 使用此属性您可以明确定义 应转换哪些文档页面。 此列表中的页面必须有从 1 开始的数字。即 有效页数必须取自范围 (1...[NumberOfPagesInConvertedDocument]) 此列表中页面出现的顺序不会影响它们的 结果 HTML 页面中的顺序 - 结果页面始终按照它们在源 PDF 中的 顺序排列。 如果此列表为空（默认情况下），所有页面都将被转换。 如果此列表的任何页码超出当前页面的范围(1-[amountOfPagesInDocument]) 将引发异常。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | 此属性开启了提取图像或文本的功能 用于具有 OCR 子层的 PDF 文档。 |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout) { get; set; } | 获取或设置一个值，该值指示该 HTML 是否创建为固定布局。 |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth) { get; set; } | 此属性指定 Flow 模式的全宽段落文本，FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources) { get; } | 预存字体的字体来源。 |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution) { get; set; } | 获取或设置图像渲染的分辨率。 |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth) { get; set; } | 此属性设置图形路径线的最小宽度。 如果线条粗细小于 1px Adobe Acrobat 会将其四舍五入为该值。所以这个属性可以 用于模拟 HTML 浏览器的这种行为。 |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping) { get; set; } | 当文本字形不会被分组为单词和字符串时，此属性打开模式 此模式允许在定位字形时保持最大精度在页面上，它可以是 用于转换带有音符或字形的文档，它们应该彼此分开放置。 只有当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage) { get; set; } | 如果属性 RenderTextAsImage 设置为 true，则来自源的文本将变为 HTML 中的图像。 可能有助于使文本无法选择 或 HTML 文本未正确呈现。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | 数据保存格式。 |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping) { get; set; } | 此属性指定字形和单词的顺序分组为字符串 例如标签和单词在转换的 HTML 中具有不同的顺序，您希望它们匹配。 只有当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages) { get; set; } | When multipage-mode selected(ie 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file 对于每个结果 HTML 页面。 默认情况下，此属性为 false，因此，将创建 一个用于所有已创建页面的大型通用 CSS。在此模式下生成的所有 CSS 的摘要大小（每页一个 CSS）通常 比一个大 CSS 文件的大小大得多，因为在前一种情况下 在这种情况下，CSS 类在每个页面的多个 CSS 文件中是重复的。 所以，这个设置只在你对以后独立处理每个 HTML 页面感兴趣时才使用这个设置更糟糕，因此 CSS 的大小 拆开的每一页都是最关键的问题。 |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages) { get; set; } | 获取或设置指示源 文档的每个页面是否将转换为它自己的目标 HTML 文档的标志, 即结果 HTML 是否会被拆分为多个 HTML 页面。 |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder) { get; set; } | 如果属性 UseZORder 设置为 true，则图形和文本将添加到生成的 HTML 文档 相应的原始 PDF 文档中的 Z 顺序。如果此属性为 false，则所有图形将 作为单层放置，这可能会对重叠对象造成一些不必要的影响。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | 回调以处理生成的任何警告。 WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。 Continue 是默认操作，Save 操作会继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing) | 此参数定义在将复合背景图像从 PDF 转换为 HTML 期间所需的抗锯齿措施 |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix) | 当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名 (类似于 ".stl_01 {}" ... ".stl_NN {})生成 并在结果 CSS 中使用。此属性允许强制设置类名前缀 例如，如果您希望所有类名都以 'my_prefix_' 开头(即类似于 'my_prefix_1' ... 'my_prefix_NNN' ) , 然后在转换之前将 'my_prefix_' 分配给此属性。 如果此属性保持不变（即 null 将保留为 value ），然后 转换器将自己生成类名 （它将类似于 ".stl_01 {}" ... ".stl_NN { }") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy) | 此字段可以包含保存策略 必须在转换过程中使用（如果存在） 的 Pdf 到 Html for处理与 CSS 相关的 保存到整个创建的 HTML 文档或其页面（如果生成了多个 HTML 页面） 如果您想以某种特定方式处理 CSS 文件，那只是请创建相关的方法和 将从它创建的委托分配给该属性。 |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy) | 转换结果可以包含一个或多个 HTML 页面 您可以分配给从实现处理的自定义方法创建的此属性委托一个 HTML 页面的 （准确地说是标记 HTML，没有外部链接文件，如果有的话） 在转换期间创建。 在这种情况下，可以在该自定义代码中进行处理（例如将页面的 HTML 保存在流或磁盘中）。 在这种情况下，必须在提供的方法代码中执行保存 HTML 页面的所有必要操作 ，因为将不使用转换器代码中的结果保存。 如果出于某种原因必须由转换器的代码本身来处理这种或那种情况， 不在自定义代码中，请在自定义代码中设置标志'CustomProcessingCancelled' of 'htmlSavingInfo' 参数的变量:它将向转换器发出信号，所有必要的 处理该资源的步骤必须在转换器本身中以相同的方式完成 好像没有任何用于处理的外部自定义代码。 |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler) | 此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前金额的消息 已处理页面，在控制台上显示进度的处理程序代码示例是: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy) | 此字段可以包含保存策略 在转换期间必须使用（如果存在） 用于自定义处理创建引用的资源 与保存的 HTML 节点相关的文件（如图像和字体）。 该策略必须处理资源 并返回字符串，该字符串表示生成的 HTML 中保存的资源 的所需 URL。 |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation) | 此字段可以包含返回 主题的自定义方法URL（或 URL 模板，如果多页生成开启 - 请参阅下面的详细信息） CSS，因为它应该放在生成的结果 HTML 中。 Fe 如果您想要转换器将一些特定的 URL 而不是标准 CSS 文件名放入生成的 CSS，那么您应该创建并放入此属性方法 生成所需的 URL。 如果设置了标志“SplitCssIntoPages”，则此自定义策略（如果有） 必须返回的不是 CSS 的确切 URL，而是 的模板字符串（之后使用 string.Format() function inside converter) 用页码替换占位符可以解析为这个或那个页面的 CSS URL 的 URL。 在这种情况下，预期返回字符串的示例是: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage ={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist) | 未嵌入 HTML 的 PDF 嵌入字体名称列表。 |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy) | 定义编码特殊规则以调整当前文档的 PDF 解码 |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode) | 定义将 PDF 保存为所需格式时使用的字体保存模式 |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode) | 有时会出现生成 HTML 标记的特定要求。 该参数定义了在将 PDF 转换为 HTML 时可以使用 的 HTML 准备模式，以匹配此类特定要求。 |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod) | 设置结果 HTML 中单词中字母的定位模式 |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany) | 此属性表示用于在表示源 PDF 页面的区域周围的结果 HTML 文档中绘制边框（如果有） 的设置集。 本质上它涉及显示页面的纸张边缘， 不是PDF页面本身引用的页面边框。 |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany) | 此属性表示一组额外的页边距（如果有） 在结果 HTML 文档中表示源 PDF 页面的区域周围。 |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize) | 如果属性“SplitOnPages=false”，则表示所有输入 PDF 页面的整个 HTML 将被 放入一个大的结果 HTML 文件中。 此标志定义结果 HTML 是否将以这样的方式生成 结果 HTML 中表示 PDF 页面的区域流将取决于 的屏幕分辨率观众。 假设查看器一侧的屏幕宽度足够大，可以在水平方向上将 2 个或更多页面放在 other 附近。如果这个标志设置为真，那么这个机会 将被使用（尽可能多的页面将在水平方向上显示在另一个 附近，然后下一个水平页面组将显示在第一个下）。 否则页面将以这种方式流动:下一页总是在前一页之下。 |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode) | 它定义了引用文件（HTML、字体、图像、CSSes） 是嵌入到主 HTML 文件中还是生成为单独的二进制文件实体 |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode) | 转换后的 PDF 可以包含光栅图像 此参数定义在将 PDF 转换为 HTML 期间应如何处理它们 |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom) | 定义是否在创建的 HTML 中删除顶部和底部的空白区域而没有任何内容（如果有）。 |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont) | 表示将保存完整字体，仅支持 True Type 字体。 默认情况下 SaveFullFont = false 并且转换器保存显示文档文本所需的初始字体 的子集。 |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts) | Pdf 可以包含被其他元素遮蔽的文本（fe by images）但 可以在 Acrobat Reader 中选择到剪贴板（通常会发生当文档包含从中提取的图像和 OCRed 文本时）。 此设置告诉转换器我们是否需要将此类文本保存为透明 结果 HTML 中的可选文本以模仿 Acrobat Reader 的行为（否则此类文本通常保存为隐藏，不可用用于复制到剪贴板） |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts) | Pdf 可以包含可以选择到剪贴板的透明文本（通常在文档包含从中提取的图像和 OCRed 文本时发生）。 此设置告诉转换器我们是否需要将此类文本保存为透明 结果 HTML 中的可选文本 |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages) | 如果在将文档保存为 HTML 期间遇到 ，则获取或设置任何图像必须保存到的目录路径。如果参数为空或 null 则图像文件（如果有）将与链接到 HTML 的其他文件一起保存 如果 CustomImageSavingStrategy 不会影响任何内容:属性已成功用于处理相关图像文件。 |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages) | 获取或设置目录的路径，如果在将文档保存为 HTML 的过程中遇到 ，则必须仅将 SVG 图像保存到该目录。如果参数为空或 null 则 SVG 文件（如果有）将与其他图像文件（靠近输出文件）一起保存 或图像的特殊文件夹中（如果它在 SpecialImagesFolderIfAny 选项中指定）。 如果 CustomImageSavingStrategy 属性成功用于处理相关图像文件，则不会影响任何内容。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | 有时 PDF 包含（页面或表格单元格的）背景图像 由多个相同的平铺背景图像构成，彼此相邻。 在这种情况下，目标格式的渲染器（对于 DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成 可见边界， 会导致它们的图像技术边缘平滑（抗锯齿）与 Acrobat Reader 不同。 如果导出的文档看起来在 相同背景图像的部分之间包含这样的可见边界，请尝试使用此设置来消除 这种不需要的效果. 注意！这种质量优化通常会减慢转换速度， 所以，请仅在真正需要时使用此选项。 |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss) | PDF 本身不包含文本的下划线标记。它模拟了位于文本下方的行。 此选项允许转换器尝试猜测这一行或那一行是文本的下划线 并将此信息放入 CSS 中，而不是以图形方式绘制下划线 |

### 也可以看看

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPageSetOptions](../ipagesetoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
