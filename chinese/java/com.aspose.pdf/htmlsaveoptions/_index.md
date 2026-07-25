---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "导出为 Html 格式的保存选项"
type: docs
weight: 1990
url: /zh/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

导出为 Html 格式的保存选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | 初始化 HtmlSaveOptions 类的新实例。 |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | 初始化 {@code HtmlSaveOptions} 类的新实例。 |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | 初始化 HtmlSaveOptions 类的新实例。 |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | 初始化 HtmlSaveOptions 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | 如果属性 'SplitOnPages=false'，则整个表示所有输入 PDF 页面 的 HTML 不会被拆分为不同的 HTML 页面，而是放入一个大的结果 HTML 文件中。但每个源 PDF 页面将在 HTML 中以其自己的矩形区域表示（如有必要，这些区域可以使用特殊属性 'PageBorderIfAny' 加边框以显示页面纸张边缘）。此参数定义在输出的 HTML 区域（代表源 PDF 文档的页面）周围强制保留的边距宽度。本质上，它定义了 PDF \"paper\" 页面的 HTML 表示之间的保证间隔，以此方式进行转换。 |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | 此参数定义在将复合背景图像从 PDF 转换为 HTML 过程中所需的抗锯齿措施。 |
| [getBatchSize](#getBatchSize--) | 如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。 |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | 当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（例如 \".stl_01 {}\" … \".stl_NN {}\"）会被生成并用于结果 CSS。此属性允许强制设置类名前缀。例如，如果您希望所有类名都以 'my_prefix_' 开头（即类似 'my_prefix_1' … 'my_prefix_NNN'），只需在转换前将 'my_prefix_' 赋给此属性。如果此属性保持未修改（即值为 null），则转换器将自行生成类名（如 \".stl_01 {}\" … \".stl_NN {}\"）。 |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | 此字段可以包含在 PDF 转换为 Html 期间用于处理整个创建的 HTML 文档或其页面（如果生成多个 HTML 页面）相关 CSS 保存的策略（如果提供）。如果您想以特定方式处理 CSS 文件，请创建相应的方法并将由其创建的委托分配给此属性。 |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | 转换结果可能包含一个或多个 HTML 页面。您可以将自定义方法创建的委托分配给此属性，以实现对在转换期间生成的单个 HTML 页面（准确地说是标记 HTML，且不包含任何外部链接文件）的处理。在这种情况下，诸如将页面的 HTML 保存到流或磁盘的处理可以在自定义代码中完成。所有保存 HTML 页面的必要操作必须在提供的方法代码中完成，因为转换器内部的保存代码将不再使用。如果出于某种原因必须由转换器自身的代码而非自定义代码来完成处理，请在自定义代码中设置 'htmlSavingInfo' 参数变量的标志 'CustomProcessingCancelled'：这将向转换器指示所有必要的资源处理步骤应由转换器本身完成，就像没有任何外部自定义代码进行处理一样。 |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> 此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | 此字段可以包含在转换期间用于自定义处理已创建的引用资源文件（如图像和字体）——这些文件与已保存 HTML 的节点相关——的保存策略（如果提供）。该策略必须处理资源并返回表示生成的 HTML 中已保存资源的期望 URL 的字符串。 |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | 此字段可以包含返回 URL（如果启用多页生成则返回 URL 模板——详见下文）的自定义方法，该 URL 用于在生成的结果 HTML 中放置主题 CSS。例如，如果您希望转换器在生成的 CSS 中使用特定的 URL 替代标准 CSS 文件名，则只需在此属性中创建并放入生成所需 URL 的方法。如果设置了标志 'SplitCssIntoPages'，则此自定义策略（如果有）必须返回不是 CSS 的确切 URL，而是模板字符串（在转换器内部使用 String.Format() 函数将占位符替换为页码后），可以解析为相应页的 CSS URL。此类情况下预期返回的字符串示例有：'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' |
| [getDefaultFontName](#getDefaultFontName--) | 指定已安装字体的名称，该字体用于替代文档中未嵌入且系统中未安装的任何字体。如果为 null，则使用默认替代字体。 |
| [getDocumentType](#getDocumentType--) | 获取 {@code HtmlDocumentTypeInternal}。 |
| [getExcludeFontNameList](#getExcludeFontNameList--) | PDF 嵌入字体名称列表，这些字体不会嵌入到 HTML 中。 |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | 通过此属性，您可以明确指定应转换文档的哪些页。列表中的页码采用 1 基编号。例如，页码必须取自范围 (1...[NumberOfPagesInConvertedDocument])。列表中页码的出现顺序不影响它们在结果 HTML 页面中的顺序——结果页面始终按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（默认情况），则会转换所有页。如果列表中的任何页码超出当前文档页数范围 (1-[amountOfPagesInDocument])，将抛出异常。 |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | 此属性指定流式模式下的全宽段落文本，FixedLayout = false。 |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | 定义编码特殊规则，以调优当前文档的 PDF 解码。 |
| [getFontSavingMode](#getFontSavingMode--) | 定义在将 PDF 保存为所需格式时使用的字体保存模式。 |
| [getFontSources](#getFontSources--) | <p> 预保存字体的字体来源。 </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | 有时会出现对生成 HTML 标记的特定需求。此参数定义在 PDF 转换为 HTML 时可使用的 HTML 准备模式，以满足此类特定需求。 |
| [getImageResolution](#getImageResolution--) | 获取或设置图像渲染的分辨率。 |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | 设置结果 HTML 中单词中字母的定位模式。 |
| [getMinimalLineWidth](#getMinimalLineWidth--) | 此属性设置图形路径线的最小宽度。如果线宽小于 1px，Adobe Acrobat 会将其四舍五入为该值。因此，可使用此属性在 HTML 浏览器中模拟此行为。 |
| [getPageBorderIfAny](#getPageBorderIfAny--) | 此属性表示用于在结果 HTML 文档中围绕表示源 PDF 页面的区域绘制边框（如果有）的设置集合。实质上，它涉及显示页面的纸张边缘，而不是 PDF 页面本身引用的页面边框。 |
| [getPageMarginIfAny](#getPageMarginIfAny--) | 此属性表示在结果 HTML 文档中围绕表示源 PDF 页面的区域的额外页面边距（如果有）的设置集合。 |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | 它定义了引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是作为独立的二进制实体生成。 |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | 转换后的 PDF 可能包含光栅图像。此参数定义在 PDF 转换为 HTML 时应如何处理这些图像。 |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | 获取或设置在将文档保存为 HTML 时必须保存的图像目录路径。如果参数为空或为 null，则图像文件（如果有）将与链接到 HTML 的其他文件一起保存。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。 |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | 获取或设置在将文档保存为 HTML 时必须保存的仅 SVG 图像的目录路径。如果参数为空或为 null，则 SVG 文件（如果有）将与其他图像文件（位于输出文件附近）一起保存，或保存到特殊图像文件夹（如果在 SpecialImagesFolderIfAny 选项中指定）。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。 |
| [getTitle](#getTitle--) | 获取或设置 HTML 页面标题。 |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | 获取指示在保存期间是否将发现的 SVG 图形（如果有）压缩（打包）为 SVGZ 格式的标志。值：{@code HtmlDocumentType}。 |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | 如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（层）中的所有元素将放入带有 \"data-pdflayer\" 属性并指定层名称的 HTML div 中。该层名称将从 PDF 标记内容的可选属性中提取。如果此属性为 false（默认），则不会从 PDF 标记内容创建任何层。 |
| [isFixedLayout](#isFixedLayout--) | 获取一个值，指示该 HTML 是否以固定布局创建。 |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | 获取或设置是否忽略与缺少字体相关的错误的指示。true 表示将忽略缺少字体的错误，处理时会跳过引用错误资源的文本段落。默认值为 false。 |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | 如果属性 'SplitOnPages=false'，则表示所有输入 PDF 页面的完整 HTML 将放入一个大的结果 HTML 文件中。此标志定义结果 HTML 是否以一种方式生成，即结果 HTML 中表示 PDF 页面的区域流动取决于查看器的屏幕分辨率。假设查看器端的屏幕宽度足以在水平方向上并排放置两页或更多页。如果此标志设为 true，则会利用此机会（尽可能在水平方向上并排显示多页，然后下一组水平页面显示在第一组下方）。否则页面将以如下方式流动：下一页始终位于前一页下方。 |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | 此属性在文本字形不会被分组为单词和字符串的模式下开启。此模式可在页面上定位字形时保持最高精度，可用于转换包含音乐符号或应彼此分开放置的字形的文档。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | 定义在生成的 HTML 中是否会移除顶部和底部没有任何内容的空白区域（如果存在）。 |
| [isRenderTextAsImage](#isRenderTextAsImage--) | 如果属性 RenderTextAsImage 设置为 true，来源文本将在 HTML 中变为图像。此方式可用于使文本不可选中或在 HTML 文本未正确渲染的情况下。 |
| [isSaveFullFont](#isSaveFullFont--) | 指示将保存完整字体，仅支持 True Type 字体。默认情况下 SaveFullFont = false，转换器仅保存文档显示文本所需的初始字体子集。 |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | PDF 可能包含被其他元素（例如图像）遮挡的文本，但在 Acrobat Reader 中仍可复制到剪贴板（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告知转换器是否需要在结果 HTML 中将此类文本保存为透明可选文本，以模拟 Acrobat Reader 的行为（否则此类文本通常会被保存为隐藏，无法复制）。 |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | PDF 可能包含可复制到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告知转换器是否需要在结果 HTML 中将此类文本保存为透明可选文本。 |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | 此属性指定字形和单词按顺序分组为字符串。例如，标签和单词在转换后的 HTML 中顺序不同，而您希望它们匹配。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | 当选择多页模式（即 'SplitIntoPages' 为 true）时，此属性决定是否为每个生成的 HTML 页面创建单独的 CSS 文件。默认情况下此属性为 false，所有页面共用一个大型公共 CSS。该模式下生成的所有 CSS（每页一个 CSS）的总体大小通常远大于单个大型 CSS 文件，因为前者会在每个页面的多个 CSS 文件中出现重复的 CSS 类。因此，仅在您需要对每个 HTML 页面独立进行后续处理时才建议使用此设置，因为此时每个页面单独的 CSS 大小是最关键的问题。 |
| [isSplitIntoPages](#isSplitIntoPages--) | 获取指示是否将源文档的每一页转换为其各自的目标 HTML 文档的标志，即结果 HTML 是否会被拆分为多个 HTML 页面。 |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF 本身不包含文本下划线标记，而是通过位于文本下方的线条来模拟。此选项允许转换器尝试判断某条线是否为文本下划线，并将此信息写入 CSS，而不是以图形方式绘制下划线。 |
| [isUseZOrder](#isUseZOrder--) | 如果属性 UseZORder 设置为 true，图形和文本将按照原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。如果此属性为 false，所有图形将放置在单一层上，可能导致重叠对象出现不必要的效果。 |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | 如果属性 'SplitOnPages=false'，则整个表示所有输入 PDF 页面 的 HTML 不会被拆分为不同的 HTML 页面，而是放入一个大的结果 HTML 文件中。但每个源 PDF 页面将在 HTML 中以其自己的矩形区域表示（如有必要，这些区域可以使用特殊属性 'PageBorderIfAny' 加边框以显示页面纸张边缘）。此参数定义在输出的 HTML 区域（代表源 PDF 文档的页面）周围强制保留的边距宽度。本质上，它定义了 PDF \"paper\" 页面的 HTML 表示之间的保证间隔，以此方式进行转换。 |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | 此参数定义在将复合背景图像从 PDF 转换为 HTML 过程中所需的抗锯齿措施。 |
| [setBatchSize](#setBatchSize-int-) | 如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。 |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | 设置指示在保存期间是否将找到的 SVG 图形（如果有）压缩（ZIP）为 SVGZ 格式的标志。值：{@code HtmlDocumentType}。 |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | 如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（层）中的所有元素将放入带有 \"data-pdflayer\" 属性并指定层名称的 HTML div 中。该层名称将从 PDF 标记内容的可选属性中提取。如果此属性为 false（默认），则不会从 PDF 标记内容创建任何层。 |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | 当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（例如 \".stl_01 {}\" … \".stl_NN {}\"）会被生成并用于结果 CSS。此属性允许强制设置类名前缀。例如，如果您希望所有类名都以 'my_prefix_' 开头（即类似 'my_prefix_1' … 'my_prefix_NNN'），只需在转换前将 'my_prefix_' 赋给此属性。如果此属性保持未修改（即值为 null），则转换器将自行生成类名（如 \".stl_01 {}\" … \".stl_NN {}\"）。 |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | 此字段可以包含在 PDF 转换为 Html 期间用于处理整个创建的 HTML 文档或其页面（如果生成多个 HTML 页面）相关 CSS 保存的策略（如果提供）。如果您想以特定方式处理 CSS 文件，请创建相应的方法并将由其创建的委托分配给此属性。 |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | 转换结果可以包含一个或多个 HTML 页面。您可以为此属性分配由自定义方法创建的委托，该方法实现对在转换期间生成的单个 HTML 页面（准确来说是标记 HTML，不含任何外部链接文件）的处理。 |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | 此处理程序可用于处理转换进度事件，例如。 |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | 此字段可以包含在转换期间必须使用的保存策略（如果提供），用于自定义处理与已保存 HTML 节点相关的创建的引用资源文件（如图像和字体）。 |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | 此字段可以包含自定义方法，该方法返回主题 CSS 的 URL（如果启用了多页生成，则返回 URL 模板——详见下文），以便将其放入生成的结果 HTML 中。 |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | 指定已安装字体的名称，该字体用于替代文档中未嵌入且系统中未安装的任何字体。如果为 null，则使用默认替代字体。 |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | 设置 {@code HtmlDocumentType}。 |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | PDF 嵌入字体名称列表，这些字体不会嵌入到 HTML 中。 |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | 通过此属性，您可以明确指定应转换文档的哪些页。列表中的页码采用 1 基编号。例如，页码必须取自范围 (1...[NumberOfPagesInConvertedDocument])。列表中页码的出现顺序不影响它们在结果 HTML 页面中的顺序——结果页面始终按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（默认情况），则会转换所有页。如果列表中的任何页码超出当前文档页数范围 (1-[amountOfPagesInDocument])，将抛出异常。 |
| [setFixedLayout](#setFixedLayout-boolean-) | 设置一个值，指示该 HTML 是否以固定布局方式创建。 |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | 此属性指定流式模式下的全宽段落文本，FixedLayout = false。 |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | 定义编码特殊规则，以调优当前文档的 PDF 解码。 |
| [setFontSavingMode](#setFontSavingMode-int-) | 定义在将 PDF 保存为所需格式时使用的字体保存模式。 |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | 有时会出现对生成 HTML 标记的特定需求。此参数定义在 PDF 转换为 HTML 时可使用的 HTML 准备模式，以满足此类特定需求。 |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | 获取或设置是否忽略与缺少字体相关的错误的指示。true 表示将忽略缺少字体的错误，处理时会跳过引用错误资源的文本段落。默认值为 false。 |
| [setImageResolution](#setImageResolution-int-) | 获取或设置图像渲染的分辨率。 |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | 设置结果 HTML 中单词中字母的定位模式。 |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | 此属性设置图形路径线的最小宽度。如果线宽小于 1px，Adobe Acrobat 会将其四舍五入为该值。因此，可使用此属性在 HTML 浏览器中模拟此行为。 |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | 此属性表示用于在结果 HTML 文档中围绕代表源 PDF 页面区域绘制边框（如果有）的设置集合。 |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | 此属性表示在结果 HTML 文档中围绕表示源 PDF 页面的区域的额外页面边距（如果有）的设置集合。 |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | 如果属性 'SplitOnPages=false'，则表示所有输入 PDF 页面的完整 HTML 将放入一个大的结果 HTML 文件中。此标志定义结果 HTML 是否以一种方式生成，即结果 HTML 中表示 PDF 页面的区域流动取决于查看器的屏幕分辨率。假设查看器端的屏幕宽度足以在水平方向上并排放置两页或更多页。如果此标志设为 true，则会利用此机会（尽可能在水平方向上并排显示多页，然后下一组水平页面显示在第一组下方）。否则页面将以如下方式流动：下一页始终位于前一页下方。 |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | 它定义了引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是作为独立的二进制实体生成。 |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | 此属性在文本字形不会被分组为单词和字符串的模式下开启。此模式可在页面上定位字形时保持最高精度，可用于转换包含音乐符号或应彼此分开放置的字形的文档。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | 转换后的 PDF 可能包含光栅图像。此参数定义在 PDF 转换为 HTML 时应如何处理这些图像。 |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | 定义在生成的 HTML 中是否会移除顶部和底部没有任何内容的空白区域（如果存在）。 |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | 如果属性 RenderTextAsImage 设置为 true，来源文本将在 HTML 中变为图像。此方式可用于使文本不可选中或在 HTML 文本未正确渲染的情况下。 |
| [setSaveFullFont](#setSaveFullFont-boolean-) | 指示将保存完整字体，仅支持 True Type 字体。默认情况下 SaveFullFont = false，转换器仅保存文档显示文本所需的初始字体子集。 |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | PDF 可能包含被其他元素（例如图像）遮挡的文本，但在 Acrobat Reader 中仍可复制到剪贴板（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告知转换器是否需要在结果 HTML 中将此类文本保存为透明可选文本，以模拟 Acrobat Reader 的行为（否则此类文本通常会被保存为隐藏，无法复制）。 |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | PDF 可能包含可复制到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告知转换器是否需要在结果 HTML 中将此类文本保存为透明可选文本。 |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | 此属性指定字形和单词按顺序分组为字符串。例如，标签和单词在转换后的 HTML 中顺序不同，而您希望它们匹配。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。 |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | 获取或设置在将文档保存为 HTML 时必须保存的图像目录路径。如果参数为空或为 null，则图像文件（如果有）将与链接到 HTML 的其他文件一起保存。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。 |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | 获取或设置在将文档保存为 HTML 时必须保存的仅 SVG 图像的目录路径。如果参数为空或为 null，则 SVG 文件（如果有）将与其他图像文件（位于输出文件附近）一起保存，或保存到特殊图像文件夹（如果在 SpecialImagesFolderIfAny 选项中指定）。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。 |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | 当选择多页模式（即 'SplitIntoPages' 为 true）时，此属性决定是否为每个生成的 HTML 页面创建单独的 CSS 文件。默认情况下此属性为 false，所有页面共用一个大型公共 CSS。该模式下生成的所有 CSS（每页一个 CSS）的总体大小通常远大于单个大型 CSS 文件，因为前者会在每个页面的多个 CSS 文件中出现重复的 CSS 类。因此，仅在您需要对每个 HTML 页面独立进行后续处理时才建议使用此设置，因为此时每个页面单独的 CSS 大小是最关键的问题。 |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | 设置指示是否将源文档的每一页转换为其各自的目标 HTML 文档的标志，即结果 HTML 是否会被拆分为多个 HTML 页面。 |
| [setTitle](#setTitle-java.lang.String-) | 获取或设置 HTML 页面标题。 |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF 本身不包含文本下划线标记，而是通过位于文本下方的线条来模拟。此选项允许转换器尝试判断某条线是否为文本下划线，并将此信息写入 CSS，而不是以图形方式绘制下划线。 |
| [setUseZOrder](#setUseZOrder-boolean-) | 如果属性 UseZORder 设置为 true，图形和文本将按照原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。如果此属性为 false，所有图形将放置在单一层上，可能导致重叠对象出现不必要的效果。 |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

初始化 HtmlSaveOptions 类的新实例。

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

初始化 {@code HtmlSaveOptions} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fixedLayout |  | 布尔值 |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
初始化 HtmlSaveOptions 类的新实例。

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
初始化 HtmlSaveOptions 类的新实例。

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

如果属性 'SplitOnPages=false'，则整个表示所有输入 PDF 页面 的 HTML 不会被拆分为不同的 HTML 页面，而是放入一个大的结果 HTML 文件中。但每个源 PDF 页面将在 HTML 中以其自己的矩形区域表示（如有必要，这些区域可以使用特殊属性 'PageBorderIfAny' 加边框以显示页面纸张边缘）。此参数定义在输出的 HTML 区域（代表源 PDF 文档的页面）周围强制保留的边距宽度。本质上，它定义了 PDF \"paper\" 页面的 HTML 表示之间的保证间隔，以此方式进行转换。

**Returns:**
int 值 @deprecated AdditionalMarginWidthInPoints 已弃用，请改用 PageMarginIfAny。

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

此参数定义在将复合背景图像从 PDF 转换为 HTML 过程中所需的抗锯齿措施。

**Returns:**
AntialiasingProcessingType 元素 @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。

**Returns:**
int 值

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（例如 \".stl_01 {}\" … \".stl_NN {}\"）会被生成并用于结果 CSS。此属性允许强制设置类名前缀。例如，如果您希望所有类名都以 'my_prefix_' 开头（即类似 'my_prefix_1' … 'my_prefix_NNN'），只需在转换前将 'my_prefix_' 赋给此属性。如果此属性保持未修改（即值为 null），则转换器将自行生成类名（如 \".stl_01 {}\" … \".stl_NN {}\"）。

**Returns:**
字符串值

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

此字段可以包含在 PDF 转换为 Html 期间用于处理整个创建的 HTML 文档或其页面（如果生成多个 HTML 页面）相关 CSS 保存的策略（如果提供）。如果您想以特定方式处理 CSS 文件，请创建相应的方法并将由其创建的委托分配给此属性。

**Returns:**
CssSavingStrategy 实例

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

转换结果可能包含一个或多个 HTML 页面。您可以将自定义方法创建的委托分配给此属性，以实现对在转换期间生成的单个 HTML 页面（准确地说是标记 HTML，且不包含任何外部链接文件）的处理。在这种情况下，诸如将页面的 HTML 保存到流或磁盘的处理可以在自定义代码中完成。所有保存 HTML 页面的必要操作必须在提供的方法代码中完成，因为转换器内部的保存代码将不再使用。如果出于某种原因必须由转换器自身的代码而非自定义代码来完成处理，请在自定义代码中设置 'htmlSavingInfo' 参数变量的标志 'CustomProcessingCancelled'：这将向转换器指示所有必要的资源处理步骤应由转换器本身完成，就像没有任何外部自定义代码进行处理一样。

**Returns:**
HtmlPageMarkupSavingStrategy 实例

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> 此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler 实例

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

此字段可以包含在转换期间用于自定义处理已创建的引用资源文件（如图像和字体）——这些文件与已保存 HTML 的节点相关——的保存策略（如果提供）。该策略必须处理资源并返回表示生成的 HTML 中已保存资源的期望 URL 的字符串。

**Returns:**
ResourceSavingStrategy 实例

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

此字段可以包含返回 URL（如果启用多页生成则返回 URL 模板——详见下文）的自定义方法，该 URL 用于在生成的结果 HTML 中放置主题 CSS。例如，如果您希望转换器在生成的 CSS 中使用特定的 URL 替代标准 CSS 文件名，则只需在此属性中创建并放入生成所需 URL 的方法。如果设置了标志 'SplitCssIntoPages'，则此自定义策略（如果有）必须返回不是 CSS 的确切 URL，而是模板字符串（在转换器内部使用 String.Format() 函数将占位符替换为页码后），可以解析为相应页的 CSS URL。此类情况下预期返回的字符串示例有：'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }'

**Returns:**
CssUrlMakingStrategy 实例

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

指定已安装字体的名称，该字体用于替代文档中未嵌入且系统中未安装的任何字体。如果为 null，则使用默认替代字体。

**Returns:**
String 值：字体名称

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

获取 {@code HtmlDocumentTypeInternal}。

**Returns:**
该 {@code HtmlDocumentTypeInternal}。

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

PDF 嵌入字体名称列表，这些字体不会嵌入到 HTML 中。

**Returns:**
String 元素数组

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

通过此属性，您可以明确指定应转换文档的哪些页。列表中的页码采用 1 基编号。例如，页码必须取自范围 (1...[NumberOfPagesInConvertedDocument])。列表中页码的出现顺序不影响它们在结果 HTML 页面中的顺序——结果页面始终按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（默认情况），则会转换所有页。如果列表中的任何页码超出当前文档页数范围 (1-[amountOfPagesInDocument])，将抛出异常。

**Returns:**
int 数组

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

此属性指定流式模式下的全宽段落文本，FixedLayout = false。

**Returns:**
布尔值

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

定义编码特殊规则，以调优当前文档的 PDF 解码。

**Returns:**
FontEncodingRules 元素 @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

定义在将 PDF 保存为所需格式时使用的字体保存模式。

**Returns:**
FontSavingModes 元素 @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> 预保存字体的字体来源。 </p>

**Returns:**
FontSourceCollection 对象 <hr> <p> 字体可能会预先保存以用于缓存，然后传递到 Html 转换过程。比如在文档拆分场景以及在多个线程中使用单一字体集处理文档页面时，这可能会很有用。 </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

有时会出现对生成 HTML 标记的特定需求。此参数定义在 PDF 转换为 HTML 时可使用的 HTML 准备模式，以满足此类特定需求。

**Returns:**
HtmlMarkupGenerationModes 元素 @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

获取或设置图像渲染的分辨率。

**Returns:**
值：分辨率

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

设置结果 HTML 中单词中字母的定位模式。

**Returns:**
LettersPositioningMethods 元素 @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

此属性设置图形路径线的最小宽度。如果线宽小于 1px，Adobe Acrobat 会将其四舍五入为该值。因此，可使用此属性在 HTML 浏览器中模拟此行为。

**Returns:**
float 值

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

此属性表示用于在结果 HTML 文档中围绕表示源 PDF 页面的区域绘制边框（如果有）的设置集合。实质上，它涉及显示页面的纸张边缘，而不是 PDF 页面本身引用的页面边框。

**Returns:**
BorderInfo 实例

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

此属性表示在结果 HTML 文档中围绕表示源 PDF 页面的区域的额外页面边距（如果有）的设置集合。

**Returns:**
MarginInfo 实例

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

它定义了引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是作为独立的二进制实体生成。

**Returns:**
PartsEmbeddingModes 元素 @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

转换后的 PDF 可能包含光栅图像。此参数定义在 PDF 转换为 HTML 时应如何处理这些图像。

**Returns:**
RasterImagesSavingModes 元素 @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

获取或设置在将文档保存为 HTML 时必须保存的图像目录路径。如果参数为空或为 null，则图像文件（如果有）将与链接到 HTML 的其他文件一起保存。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。

**Returns:**
字符串值

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

获取或设置在将文档保存为 HTML 时必须保存的仅 SVG 图像的目录路径。如果参数为空或为 null，则 SVG 文件（如果有）将与其他图像文件（位于输出文件附近）一起保存，或保存到特殊图像文件夹（如果在 SpecialImagesFolderIfAny 选项中指定）。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。

**Returns:**
字符串值

### getTitle {#getTitle--}
```
public final String getTitle()
```

获取或设置 HTML 页面标题。

**Returns:**
字符串值

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

获取指示在保存期间是否将发现的 SVG 图形（如果有）压缩（打包）为 SVGZ 格式的标志。值：{@code HtmlDocumentType}。

**Returns:**
布尔值

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（层）中的所有元素将放入带有 \"data-pdflayer\" 属性并指定层名称的 HTML div 中。该层名称将从 PDF 标记内容的可选属性中提取。如果此属性为 false（默认），则不会从 PDF 标记内容创建任何层。

**Returns:**
布尔值

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

获取一个值，指示该 HTML 是否以固定布局创建。

**Returns:**
值：{@code true} 如果 [fixed layout]；否则，{@code false}。

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

获取或设置是否忽略与缺少字体相关的错误的指示。true 表示将忽略缺少字体的错误，处理时会跳过引用错误资源的文本段落。默认值为 false。

**Returns:**
布尔值

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

如果属性 'SplitOnPages=false'，则表示所有输入 PDF 页面的完整 HTML 将放入一个大的结果 HTML 文件中。此标志定义结果 HTML 是否以一种方式生成，即结果 HTML 中表示 PDF 页面的区域流动取决于查看器的屏幕分辨率。假设查看器端的屏幕宽度足以在水平方向上并排放置两页或更多页。如果此标志设为 true，则会利用此机会（尽可能在水平方向上并排显示多页，然后下一组水平页面显示在第一组下方）。否则页面将以如下方式流动：下一页始终位于前一页下方。

**Returns:**
布尔值

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

此属性在文本字形不会被分组为单词和字符串的模式下开启。此模式可在页面上定位字形时保持最高精度，可用于转换包含音乐符号或应彼此分开放置的字形的文档。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。

**Returns:**
布尔值

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

定义在生成的 HTML 中是否会移除顶部和底部没有任何内容的空白区域（如果存在）。

**Returns:**
布尔值

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

如果属性 RenderTextAsImage 设置为 true，来源文本将在 HTML 中变为图像。此方式可用于使文本不可选中或在 HTML 文本未正确渲染的情况下。

**Returns:**
布尔值

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

指示将保存完整字体，仅支持 True Type 字体。默认情况下 SaveFullFont = false，转换器仅保存文档显示文本所需的初始字体子集。

**Returns:**
布尔值

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

PDF 可能包含被其他元素（例如图像）遮挡的文本，但在 Acrobat Reader 中仍可复制到剪贴板（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告知转换器是否需要在结果 HTML 中将此类文本保存为透明可选文本，以模拟 Acrobat Reader 的行为（否则此类文本通常会被保存为隐藏，无法复制）。

**Returns:**
布尔值

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

PDF 可能包含可复制到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告知转换器是否需要在结果 HTML 中将此类文本保存为透明可选文本。

**Returns:**
布尔值

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

此属性指定字形和单词按顺序分组为字符串。例如，标签和单词在转换后的 HTML 中顺序不同，而您希望它们匹配。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。

**Returns:**
布尔值

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

当选择多页模式（即 'SplitIntoPages' 为 true）时，此属性决定是否为每个生成的 HTML 页面创建单独的 CSS 文件。默认情况下此属性为 false，所有页面共用一个大型公共 CSS。该模式下生成的所有 CSS（每页一个 CSS）的总体大小通常远大于单个大型 CSS 文件，因为前者会在每个页面的多个 CSS 文件中出现重复的 CSS 类。因此，仅在您需要对每个 HTML 页面独立进行后续处理时才建议使用此设置，因为此时每个页面单独的 CSS 大小是最关键的问题。

**Returns:**
布尔值

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

获取指示是否将源文档的每一页转换为其各自的目标 HTML 文档的标志，即结果 HTML 是否会被拆分为多个 HTML 页面。

**Returns:**
布尔值

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

PDF 本身不包含文本下划线标记，而是通过位于文本下方的线条来模拟。此选项允许转换器尝试判断某条线是否为文本下划线，并将此信息写入 CSS，而不是以图形方式绘制下划线。

**Returns:**
布尔值

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

如果属性 UseZORder 设置为 true，图形和文本将按照原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。如果此属性为 false，所有图形将放置在单一层上，可能导致重叠对象出现不必要的效果。

**Returns:**
布尔值

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

如果属性 'SplitOnPages=false'，则整个表示所有输入 PDF 页面 的 HTML 不会被拆分为不同的 HTML 页面，而是放入一个大的结果 HTML 文件中。但每个源 PDF 页面将在 HTML 中以其自己的矩形区域表示（如有必要，这些区域可以使用特殊属性 'PageBorderIfAny' 加边框以显示页面纸张边缘）。此参数定义在输出的 HTML 区域（代表源 PDF 文档的页面）周围强制保留的边距宽度。本质上，它定义了 PDF \"paper\" 页面的 HTML 表示之间的保证间隔，以此方式进行转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 @deprecated AdditionalMarginWidthInPoints 已弃用，请改用 PageMarginIfAny。 |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

此参数定义在将复合背景图像从 PDF 转换为 HTML 过程中所需的抗锯齿措施。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 抗锯齿处理 |  | AntialiasingProcessingType 元素 @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

设置指示在保存期间是否将找到的 SVG 图形（如果有）压缩（ZIP）为 SVGZ 格式的标志。值：{@code HtmlDocumentType}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（层）中的所有元素将放入带有 \"data-pdflayer\" 属性并指定层名称的 HTML div 中。该层名称将从 PDF 标记内容的可选属性中提取。如果此属性为 false（默认），则不会从 PDF 标记内容创建任何层。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（例如 \".stl_01 {}\" … \".stl_NN {}\"）会被生成并用于结果 CSS。此属性允许强制设置类名前缀。例如，如果您希望所有类名都以 'my_prefix_' 开头（即类似 'my_prefix_1' … 'my_prefix_NNN'），只需在转换前将 'my_prefix_' 赋给此属性。如果此属性保持未修改（即值为 null），则转换器将自行生成类名（如 \".stl_01 {}\" … \".stl_NN {}\"）。

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
此字段可以包含在 PDF 转换为 Html 期间用于处理整个创建的 HTML 文档或其页面（如果生成多个 HTML 页面）相关 CSS 保存的策略（如果提供）。如果您想以特定方式处理 CSS 文件，请创建相应的方法并将由其创建的委托分配给此属性。

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
转换结果可以包含一个或多个 HTML 页面。您可以为此属性分配由自定义方法创建的委托，该方法实现对在转换期间生成的单个 HTML 页面（准确来说是标记 HTML，不含任何外部链接文件）的处理。

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
此处理程序可用于处理转换进度事件，例如。

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
此字段可以包含在转换期间必须使用的保存策略（如果提供），用于自定义处理与已保存 HTML 节点相关的创建的引用资源文件（如图像和字体）。

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
此字段可以包含自定义方法，该方法返回主题 CSS 的 URL（如果启用了多页生成，则返回 URL 模板——详见下文），以便将其放入生成的结果 HTML 中。

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
指定已安装字体的名称，该字体用于替代文档中未嵌入且系统中未安装的任何字体。如果为 null，则使用默认替代字体。

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
设置 {@code HtmlDocumentType}。

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
PDF 嵌入字体名称列表，这些字体不会嵌入到 HTML 中。

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

通过此属性，您可以明确指定应转换文档的哪些页。列表中的页码采用 1 基编号。例如，页码必须取自范围 (1...[NumberOfPagesInConvertedDocument])。列表中页码的出现顺序不影响它们在结果 HTML 页面中的顺序——结果页面始终按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（默认情况），则会转换所有页。如果列表中的任何页码超出当前文档页数范围 (1-[amountOfPagesInDocument])，将抛出异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

设置一个值，指示该 HTML 是否以固定布局方式创建。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | : {@code true} 如果 [fixed layout]；否则，{@code false}。 |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

此属性指定流式模式下的全宽段落文本，FixedLayout = false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

定义编码特殊规则，以调优当前文档的 PDF 解码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字体编码策略 |  | FontEncodingRules 元素 @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

定义在将 PDF 保存为所需格式时使用的字体保存模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字体保存模式 |  | FontSavingModes 元素 @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

有时会出现对生成 HTML 标记的特定需求。此参数定义在 PDF 转换为 HTML 时可使用的 HTML 准备模式，以满足此类特定需求。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| HTML 标记生成模式 |  | HtmlMarkupGenerationModes 元素 @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

获取或设置是否忽略与缺少字体相关的错误的指示。true 表示将忽略缺少字体的错误，处理时会跳过引用错误资源的文本段落。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

获取或设置图像渲染的分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 值：分辨率 |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
设置结果 HTML 中单词中字母的定位模式。

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

此属性设置图形路径线的最小宽度。如果线宽小于 1px，Adobe Acrobat 会将其四舍五入为该值。因此，可使用此属性在 HTML 浏览器中模拟此行为。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
此属性表示用于在结果 HTML 文档中围绕代表源 PDF 页面区域绘制边框（如果有）的设置集合。

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
此属性表示在结果 HTML 文档中围绕表示源 PDF 页面的区域的额外页面边距（如果有）的设置集合。

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

如果属性 'SplitOnPages=false'，则表示所有输入 PDF 页面的完整 HTML 将放入一个大的结果 HTML 文件中。此标志定义结果 HTML 是否以一种方式生成，即结果 HTML 中表示 PDF 页面的区域流动取决于查看器的屏幕分辨率。假设查看器端的屏幕宽度足以在水平方向上并排放置两页或更多页。如果此标志设为 true，则会利用此机会（尽可能在水平方向上并排显示多页，然后下一组水平页面显示在第一组下方）。否则页面将以如下方式流动：下一页始终位于前一页下方。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面流类型取决于查看器屏幕大小 |  | 布尔值 |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

它定义了引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是作为独立的二进制实体生成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 部件嵌入模式 |  | PartsEmbeddingModes 元素 @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

此属性在文本字形不会被分组为单词和字符串的模式下开启。此模式可在页面上定位字形时保持最高精度，可用于转换包含音乐符号或应彼此分开放置的字形的文档。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

转换后的 PDF 可能包含光栅图像。此参数定义在 PDF 转换为 HTML 时应如何处理这些图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImagesSavingMode |  | RasterImagesSavingModes 元素 @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

定义在生成的 HTML 中是否会移除顶部和底部没有任何内容的空白区域（如果存在）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | 布尔值 |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

如果属性 RenderTextAsImage 设置为 true，来源文本将在 HTML 中变为图像。此方式可用于使文本不可选中或在 HTML 文本未正确渲染的情况下。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

指示将保存完整字体，仅支持 True Type 字体。默认情况下 SaveFullFont = false，转换器仅保存文档显示文本所需的初始字体子集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

PDF 可能包含被其他元素（例如图像）遮挡的文本，但在 Acrobat Reader 中仍可复制到剪贴板（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告知转换器是否需要在结果 HTML 中将此类文本保存为透明可选文本，以模拟 Acrobat Reader 的行为（否则此类文本通常会被保存为隐藏，无法复制）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | 布尔值 |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

PDF 可能包含可复制到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCR 文本时）。此设置告知转换器是否需要在结果 HTML 中将此类文本保存为透明可选文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| saveTransparentTexts |  | 布尔值 |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

此属性指定字形和单词按顺序分组为字符串。例如，标签和单词在转换后的 HTML 中顺序不同，而您希望它们匹配。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
获取或设置在将文档保存为 HTML 时必须保存的图像目录路径。如果参数为空或为 null，则图像文件（如果有）将与链接到 HTML 的其他文件一起保存。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
获取或设置在将文档保存为 HTML 时必须保存的仅 SVG 图像的目录路径。如果参数为空或为 null，则 SVG 文件（如果有）将与其他图像文件（位于输出文件附近）一起保存，或保存到特殊图像文件夹（如果在 SpecialImagesFolderIfAny 选项中指定）。如果已成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则此设置不产生任何影响。

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

当选择多页模式（即 'SplitIntoPages' 为 true）时，此属性决定是否为每个生成的 HTML 页面创建单独的 CSS 文件。默认情况下此属性为 false，所有页面共用一个大型公共 CSS。该模式下生成的所有 CSS（每页一个 CSS）的总体大小通常远大于单个大型 CSS 文件，因为前者会在每个页面的多个 CSS 文件中出现重复的 CSS 类。因此，仅在您需要对每个 HTML 页面独立进行后续处理时才建议使用此设置，因为此时每个页面单独的 CSS 大小是最关键的问题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

设置指示是否将源文档的每一页转换为其各自的目标 HTML 文档的标志，即结果 HTML 是否会被拆分为多个 HTML 页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTitle {#setTitle-java.lang.String-}
获取或设置 HTML 页面标题。

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

PDF 本身不包含文本下划线标记，而是通过位于文本下方的线条来模拟。此选项允许转换器尝试判断某条线是否为文本下划线，并将此信息写入 CSS，而不是以图形方式绘制下划线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | 布尔值 |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

如果属性 UseZORder 设置为 true，图形和文本将按照原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。如果此属性为 false，所有图形将放置在单一层上，可能导致重叠对象出现不必要的效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
