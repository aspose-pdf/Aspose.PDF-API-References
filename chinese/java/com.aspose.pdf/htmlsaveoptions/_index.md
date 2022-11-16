---
title: HtmlSaveOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 导出为 Html 格式的保存选项
type: docs
weight: 161
url: /zh/java/com.aspose.pdf/htmlsaveoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)

**所有已实现的接口：**
[com.aspose.pdf.IPageSetOptions](../../com.aspose.pdf/ipagesetoptions), [com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions, IPipelineOptions
```

导出为 Html 格式的保存选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) | 初始化 HtmlSaveOptions 类的新实例。 |
| [HtmlSaveOptions(int documentType)](#HtmlSaveOptions-int-) | 初始化 HtmlSaveOptions 类的新实例。 |
| [HtmlSaveOptions(boolean fixedLayout)](#HtmlSaveOptions-boolean-) | 初始化 HtmlSaveOptions 类的新实例。 |
| [HtmlSaveOptions(int documentType, boolean fixedLayout)](#HtmlSaveOptions-int-boolean-) | 初始化 HtmlSaveOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdditionalMarginWidthInPoints()](#getAdditionalMarginWidthInPoints--) | 如果属性'SplitOnPages=false'，则代表所有输入PDF页面的整个HTML不会被拆分成不同的HTML页面，而是被放入一个大的结果HTML文件中。 |
| [getAntialiasingProcessing()](#getAntialiasingProcessing--) | 此参数定义在将复合背景图像从 PDF 转换为 HTML 期间所需的抗锯齿措施 |
| [getBatchSize()](#getBatchSize--) | 如果批量转换适用于源格式和目标格式对，则定义批量大小。 |
| [getClass()](#getClass--) |  |
| [getCompressSvgGraphicsIfAny()](#getCompressSvgGraphicsIfAny--) | 获取标志，该标志指示在保存期间是否将找到的 SVG 图形（如果有）压缩（zipped）为 SVGZ 格式 |
| [getConvertMarkedContentToLayers()](#getConvertMarkedContentToLayers--) | 如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（图层）内的所有元素将被放入 HTML div 中，“data-pdflayer”属性指定图层名称。 |
| [getCssClassNamesPrefix()](#getCssClassNamesPrefix--) | 当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（类似于“.stl\ _01\{\}" ... ".stl\ _NN\{\}) 生成并在结果 CSS 中使用。 |
| [getCustomCssSavingStrategy()](#getCustomCssSavingStrategy--) | 此字段可以包含在将 Pdf 转换为 Html 期间必须使用（如果存在）的保存策略，用于处理与创建的 HTML 文档整体或与其页面相关的 CSS 的保存（如果生成多个 HTML 页面）如果你想处理 CSS 文件以某种特定方式，请创建相关方法并将从中创建的委托分配给此属性。 |
| [getCustomHtmlSavingStrategy()](#getCustomHtmlSavingStrategy--) | 转换的结果可以包含一个或多个 HTML 页面您可以分配给此属性委托，该委托是从自定义方法创建的，该方法实现了一个 HTML 页面（准确地说是标记 HTML，没有外部链接文件，如果有的话）的处理过程中创建的转换。 |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | 此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是： |
| [getCustomResourceSavingStrategy()](#getCustomResourceSavingStrategy--) | 此字段可以包含在转换期间必须使用（如果存在）的保存策略，以自定义处理与已保存 HTML 的节点相关的已创建引用资源文件（如图像和字体）。 |
| [getCustomStrategyOfCssUrlCreation()](#getCustomStrategyOfCssUrlCreation--) | 该字段可以包含返回主题 CSS 的 URL（或 URL 模板，如果多页生成打开 - 请参阅下面的详细信息）的自定义方法，因为它应该放在生成的结果 HTML 中。 |
| [getDefaultFontName()](#getDefaultFontName--) | 指定已安装字体的名称，用于替换任何未嵌入且未安装在系统中的文档字体。 |
| [getDocumentType()](#getDocumentType--) | 获取 HtmlDocumentTypeInternal 。 |
| [getExcludeFontNameList()](#getExcludeFontNameList--) | 未嵌入 HTML 的 PDF 嵌入字体名称列表。 |
| [getExplicitListOfSavedPages()](#getExplicitListOfSavedPages--) | 使用此属性，您可以明确定义应转换文档的哪些页面。 |
| [getFixedLayout()](#getFixedLayout--) | 获取一个值，该值指示该 HTML 是否创建为固定布局。 |
| [getFontEncodingStrategy()](#getFontEncodingStrategy--) | 定义编码特殊规则以调整当前文档的 PDF 解码 |
| [getFontSavingMode()](#getFontSavingMode--) | 定义将 PDF 保存为所需格式时使用的字体保存模式 |
| [getFontSources()](#getFontSources--) | 预存字体的字体来源。 |
| [getHtmlMarkupGenerationMode()](#getHtmlMarkupGenerationMode--) | 有时存在生成 HTML 标记的特定要求。 |
| [getImageResolution()](#getImageResolution--) | 获取或设置图像渲染的分辨率。 |
| [getLettersPositioningMethod()](#getLettersPositioningMethod--) | 在结果 HTML 中设置单词中字母的定位模式 |
| [getMinimalLineWidth()](#getMinimalLineWidth--) | 此属性设置图形路径线的最小宽度。 |
| [getPageBorderIfAny()](#getPageBorderIfAny--) | 此属性表示用于在表示源 PDF 页面的区域周围的结果 HTML 文档中绘制边框（如果有）的设置集。 |
| [getPageMarginIfAny()](#getPageMarginIfAny--) | 此属性表示结果 HTML 文档中表示源 PDF 页面区域周围的一组额外页边距（如果有）。 |
| [getPartsEmbeddingMode()](#getPartsEmbeddingMode--) | 它定义了引用文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中还是作为单独的二进制实体生成 |
| [getPreventGlyphsGrouping()](#getPreventGlyphsGrouping--) | 当文本字形不会被分组为单词和字符串时，此属性会打开模式此模式允许在页面上定位字形时保持最大精度，它可用于转换文档与音符或字形应分别放置其他。 |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [getRasterImagesSavingMode()](#getRasterImagesSavingMode--) | 转换后的 PDF 可以包含光栅图像 此参数定义在将 PDF 转换为 HTML 期间应如何处理它们 |
| [getSaveFormat()](#getSaveFormat--) | 数据保存格式。 |
| [getSimpleTextboxModeGrouping()](#getSimpleTextboxModeGrouping--) | 此属性指定按顺序将字形和单词分组为字符串。例如，标签和单词在转换后的 HTML 中具有不同的顺序，您希望它们匹配。 |
| [getSpecialFolderForAllImages()](#getSpecialFolderForAllImages--) | 获取或设置目录的路径，如果在将文档保存为 HTML 期间遇到任何图像，则必须将这些图像保存到该目录。 |
| [getSpecialFolderForSvgImages()](#getSpecialFolderForSvgImages--) | 获取或设置目录的路径，如果在将文档保存为 HTML 期间遇到 SVG 图像，则必须将它们保存到该目录中。 |
| [getSplitCssIntoPages()](#getSplitCssIntoPages--) | When multipage-mode selected(ie 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. |
| [getSplitIntoPages()](#getSplitIntoPages--) | 获取指示源文档的每个页面是否将转换为它自己的目标 HTML 文档的标志，即结果 HTML 是否将拆分为多个 HTML 页面。 |
| [getUseZOrder()](#getUseZOrder--) | 如果属性 UseZORder 设置为 true，则图形和文本将根据原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | 获取布尔值，该值指示在文档保存到响应后将关闭响应对象。 |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [isPagesFlowTypeDependsOnViewersScreenSize()](#isPagesFlowTypeDependsOnViewersScreenSize--) | 如果属性“SplitOnPages=false”，那么代表所有输入 PDF 页面的整个 HTML 将被放入一个大的结果 HTML 文件中。 |
| [isRemoveEmptyAreasOnTopAndBottom()](#isRemoveEmptyAreasOnTopAndBottom--) | 定义是否在创建的 HTML 中删除没有任何内容（如果有）的顶部和底部空白区域。 |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | 如果属性 RenderTextAsImage 设置为 true，则源中的文本将变为 HTML 中的图像。 |
| [isSaveFullFont()](#isSaveFullFont--) | 表示将保存完整字体，仅支持 True Type 字体。 |
| [isSaveShadowedTextsAsTransparentTexts()](#isSaveShadowedTextsAsTransparentTexts--) | Pdf 可以包含被其他元素遮蔽的文本（fe 被图像遮盖），但可以在 Acrobat Reader 中选择到剪贴板（通常发生在文档包含图像和从中提取的 OCRed 文本时）。 |
| [isSaveTransparentTexts()](#isSaveTransparentTexts--) | Pdf 可以包含可以选择到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCRed 文本时）。 |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [isTrySaveTextUnderliningAndStrikeoutingInCss()](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF 本身不包含文本的下划线标记。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdditionalMarginWidthInPoints(int value)](#setAdditionalMarginWidthInPoints-int-) | 如果属性'SplitOnPages=false'，则代表所有输入PDF页面的整个HTML不会被拆分成不同的HTML页面，而是被放入一个大的结果HTML文件中。 |
| [setAntialiasingProcessing(int antialiasingProcessing)](#setAntialiasingProcessing-int-) | 此参数定义在将复合背景图像从 PDF 转换为 HTML 期间所需的抗锯齿措施 |
| [setBatchSize(int value)](#setBatchSize-int-) | 如果批量转换适用于源格式和目标格式对，则定义批量大小。 |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | 设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [setCompressSvgGraphicsIfAny(boolean value)](#setCompressSvgGraphicsIfAny-boolean-) | 设置标志，指示在保存期间是否将找到的 SVG 图形（如果有）压缩（zipped）为 SVGZ 格式 |
| [setConvertMarkedContentToLayers(boolean value)](#setConvertMarkedContentToLayers-boolean-) | 如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（图层）内的所有元素将被放入 HTML div 中，“data-pdflayer”属性指定图层名称。 |
| [setCssClassNamesPrefix(String cssClassNamesPrefix)](#setCssClassNamesPrefix-java.lang.String-) | 当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（类似于“.stl\ _01\{\}" ... ".stl\ _NN\{\}) 生成并在结果 CSS 中使用。 |
| [setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy)](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | 此字段可以包含在将 Pdf 转换为 Html 期间必须使用（如果存在）的保存策略，用于处理与创建的 HTML 文档整体或与其页面相关的 CSS 的保存（如果生成多个 HTML 页面）如果你想处理 CSS 文件以某种特定方式，请创建相关方法并将从中创建的委托分配给此属性。 |
| [setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy)](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | 转换的结果可以包含一个或多个 HTML 页面您可以分配给此属性委托，该委托是从自定义方法创建的，该方法实现了一个 HTML 页面（准确地说是标记 HTML，没有外部链接文件，如果有的话）的处理过程中创建的转换。 |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | 此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是： |
| [setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy)](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | 此字段可以包含在转换期间必须使用（如果存在）的保存策略，以自定义处理与已保存 HTML 的节点相关的已创建引用资源文件（如图像和字体）。 |
| [setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation)](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | 该字段可以包含返回主题 CSS 的 URL（或 URL 模板，如果多页生成打开 - 请参阅下面的详细信息）的自定义方法，因为它应该放在生成的结果 HTML 中。 |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | 指定已安装字体的名称，用于替换任何未嵌入且未安装在系统中的文档字体。 |
| [setDocumentType(int value)](#setDocumentType-int-) | 设置 HtmlDocumentType 。 |
| [setExcludeFontNameList(String[] excludeFontNameList)](#setExcludeFontNameList-java.lang.String---) | 未嵌入 HTML 的 PDF 嵌入字体名称列表。 |
| [setExplicitListOfSavedPages(int[] value)](#setExplicitListOfSavedPages-int---) | 使用此属性，您可以明确定义应转换文档的哪些页面。 |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [setFixedLayout(boolean value)](#setFixedLayout-boolean-) | 设置一个值，指示该 HTML 是否创建为固定布局。 |
| [setFontEncodingStrategy(byte fontEncodingStrategy)](#setFontEncodingStrategy-byte-) | 定义编码特殊规则以调整当前文档的 PDF 解码 |
| [setFontSavingMode(int fontSavingMode)](#setFontSavingMode-int-) | 定义将 PDF 保存为所需格式时使用的字体保存模式 |
| [setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)](#setHtmlMarkupGenerationMode-int-) | 有时存在生成 HTML 标记的特定要求。 |
| [setImageResolution(int value)](#setImageResolution-int-) | 获取或设置图像渲染的分辨率。 |
| [setLettersPositioningMethod(int lettersPositioningMethod)](#setLettersPositioningMethod-int-) | 在结果 HTML 中设置单词中字母的定位模式 |
| [setMinimalLineWidth(float value)](#setMinimalLineWidth-float-) | 此属性设置图形路径线的最小宽度。 |
| [setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny)](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | 此属性表示用于在表示源 PDF 页面的区域周围的结果 HTML 文档中绘制边框（如果有）的设置集。 |
| [setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny)](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | 此属性表示结果 HTML 文档中表示源 PDF 页面区域周围的一组额外页边距（如果有）。 |
| [setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | 如果属性“SplitOnPages=false”，那么代表所有输入 PDF 页面的整个 HTML 将被放入一个大的结果 HTML 文件中。 |
| [setPartsEmbeddingMode(int partsEmbeddingMode)](#setPartsEmbeddingMode-int-) | 它定义了引用文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中还是作为单独的二进制实体生成 |
| [setPreventGlyphsGrouping(boolean value)](#setPreventGlyphsGrouping-boolean-) | 当文本字形不会被分组为单词和字符串时，此属性会打开模式此模式允许在页面上定位字形时保持最大精度，它可用于转换文档与音符或字形应分别放置其他。 |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [setRasterImagesSavingMode(int rasterImagesSavingMode)](#setRasterImagesSavingMode-int-) | 转换后的 PDF 可以包含光栅图像 此参数定义在将 PDF 转换为 HTML 期间应如何处理它们 |
| [setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | 定义是否在创建的 HTML 中删除没有任何内容（如果有）的顶部和底部空白区域。 |
| [setRenderTextAsImage(boolean value)](#setRenderTextAsImage-boolean-) | 如果属性 RenderTextAsImage 设置为 true，则源中的文本将变为 HTML 中的图像。 |
| [setSaveFullFont(boolean saveFullFont)](#setSaveFullFont-boolean-) | 表示将保存完整字体，仅支持 True Type 字体。 |
| [setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Pdf 可以包含被其他元素遮蔽的文本（fe 被图像遮盖），但可以在 Acrobat Reader 中选择到剪贴板（通常发生在文档包含图像和从中提取的 OCRed 文本时）。 |
| [setSaveTransparentTexts(boolean saveTransparentTexts)](#setSaveTransparentTexts-boolean-) | Pdf 可以包含可以选择到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCRed 文本时）。 |
| [setSimpleTextboxModeGrouping(boolean value)](#setSimpleTextboxModeGrouping-boolean-) | 此属性指定按顺序将字形和单词分组为字符串。例如，标签和单词在转换后的 HTML 中具有不同的顺序，您希望它们匹配。 |
| [setSpecialFolderForAllImages(String specialFolderForAllImages)](#setSpecialFolderForAllImages-java.lang.String-) | 获取或设置目录的路径，如果在将文档保存为 HTML 期间遇到任何图像，则必须将这些图像保存到该目录。 |
| [setSpecialFolderForSvgImages(String specialFolderForSvgImages)](#setSpecialFolderForSvgImages-java.lang.String-) | 获取或设置目录的路径，如果在将文档保存为 HTML 期间遇到 SVG 图像，则必须将它们保存到该目录中。 |
| [setSplitCssIntoPages(boolean value)](#setSplitCssIntoPages-boolean-) | When multipage-mode selected(ie 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. |
| [setSplitIntoPages(boolean value)](#setSplitIntoPages-boolean-) | 设置标志，指示源文档的每一页是否将转换为它自己的目标 HTML 文档，即结果 HTML 是否将被拆分为多个 HTML 页面。 |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF 本身不包含文本的下划线标记。 |
| [setUseZOrder(boolean value)](#setUseZOrder-boolean-) | 如果属性 UseZORder 设置为 true，则图形和文本将根据原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


初始化 HtmlSaveOptions 类的新实例。

### HtmlSaveOptions(int documentType) {#HtmlSaveOptions-int-}
```
public HtmlSaveOptions(int documentType)
```


初始化 HtmlSaveOptions 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| documentType | int | HtmlDocumentTypeInternal 。 |

### HtmlSaveOptions(boolean fixedLayout) {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```


初始化 HtmlSaveOptions 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fixedLayout | boolean | 布尔值 |

### HtmlSaveOptions(int documentType, boolean fixedLayout) {#HtmlSaveOptions-int-boolean-}
```
public HtmlSaveOptions(int documentType, boolean fixedLayout)
```


初始化 HtmlSaveOptions 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| documentType | int | HtmlDocumentTypeInternal 。 |
| fixedLayout | boolean | 如果设置为 true，HTML 将创建为固定布局。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getAdditionalMarginWidthInPoints() {#getAdditionalMarginWidthInPoints--}
```
public int getAdditionalMarginWidthInPoints()
```


如果属性'SplitOnPages=false'，则代表所有输入PDF页面的整个HTML不会被拆分成不同的HTML页面，而是被放入一个大的结果HTML文件中。但是每个源 PDF 页面都将在 HTML 中用它自己的矩形区域表示（如果需要，可以用特殊属性“PageBorderIfAny”对区域进行边框显示页面纸张边缘。此参数定义将在输出 HTML 周围强制保留的页边距宽度-表示源 PDF 文档页面的区域。本质上，它定义了 PDF“纸质”页面的 HTML 表示之间的保证间隔，这种转换模式。

**退货：**
int - 整数值
### getAntialiasingProcessing() {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```


此参数定义在将复合背景图像从 PDF 转换为 HTML 期间所需的抗锯齿措施

**退货：**
int - AntialiasingProcessingType 元素
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


如果批量转换适用于源格式和目标格式对，则定义批量大小。

**退货：**
整数
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCompressSvgGraphicsIfAny() {#getCompressSvgGraphicsIfAny--}
```
public boolean getCompressSvgGraphicsIfAny()
```


获取标志，该标志指示在保存期间是否将找到的 SVG 图形（如果有）压缩（zipped）为 SVGZ 格式

值： HtmlDocumentType 。

**退货：**
boolean - 布尔值
### getConvertMarkedContentToLayers() {#getConvertMarkedContentToLayers--}
```
public boolean getConvertMarkedContentToLayers()
```


如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（图层）内的所有元素将被放入 HTML div 中，“data-pdflayer”属性指定图层名称。该图层名称将从 PDF 标记内容的可选属性中提取。如果此属性为 false（默认情况下），则不会从 PDF 标记内容创建任何图层。

**退货：**
boolean - 布尔值
### getCssClassNamesPrefix() {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```


当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（类似于“.stl\ _01\{\}" ... ".stl\ _NN\{\}) 生成并在结果 CSS 中使用。此属性允许强制设置类名前缀 例如，如果您希望所有类名都以 'my\_字首\_'（即类似于'我的\_字首\_1' ... '我的\_字首\_NNN' ) ，然后只需分配 'my\_字首\_' 在转换之前添加到此属性。如果此属性保持不变（即 null 将保留为 value ），则转换器将自行生成类名（类似于“.stl”\ _01\{\}" ... ".stl\ _NN\{\}")

**退货：**
java.lang.String - 字符串值
### getCustomCssSavingStrategy() {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```


此字段可以包含在将 Pdf 转换为 Html 期间必须使用（如果存在）的保存策略，用于处理与创建的 HTML 文档整体或与其页面相关的 CSS 的保存（如果生成多个 HTML 页面）如果你想处理 CSS 文件以某种特定方式，请创建相关方法并将从中创建的委托分配给此属性。

**退货：**
[CssSavingStrategy](../../com.aspose.pdf/csssavingstrategy) - CssSavingStrategy 实例
### getCustomHtmlSavingStrategy() {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```


转换的结果可以包含一个或多个 HTML 页面您可以分配给此属性委托，该委托是从自定义方法创建的，该方法实现了一个 HTML 页面（准确地说是标记 HTML，没有外部链接文件，如果有的话）的处理过程中创建的转换。在这种情况下，处理（如将页面的 HTML 保存在流或磁盘中）可以在该自定义代码中完成。在这种情况下，保存 HTML 页面的所有必要操作都必须在提供的方法代码中进行，因为在转换器代码中保存结果将不会被使用。如果出于某种原因必须由转换器代码本身而不是自定义代码来处理这种或那种情况，请在“htmlSavingInfo”参数变量的自定义代码标志“CustomProcessingCancelled”中进行设置：它会向转换器发出所有必要步骤的信号该资源的处理必须在转换器本身中完成，就像没有任何外部自定义代码进行处理一样。

**退货：**
[HtmlPageMarkupSavingStrategy](../../com.aspose.pdf/htmlpagemarkupsavingstrategy) HtmlPageMarkupSavingStrategy 实例
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是：

--------------------

```
public static void ConvertWithShowingProgress()
     {
         (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
         Document doc = new Document("Booklet.pdf");
         HtmlSaveOptions saveOptions = new HtmlSaveOptions();
         saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() {
        public void invoke(
    	    UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {
    	showProgressOnConsole(eventInfo);
        }
    };
         doc.save("Booklet.doc", saveOptions);
     }
     public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
     {
         switch (eventInfo.EventType)
         {
             case HtmlSaveOptions.ProgressEventType.TotalProgress:
                 System.out.println(String.format("%s  - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value));
                 break;
             case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
        	 System.out.println(String.format("%s  - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
        	 System.out.println(String.format("%s  - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
        	 System.out.println(String.format("%s  - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             default:
                 break;
         }
      }
```

**退货：**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) ConversionProgressEventHandler 实例
### getCustomResourceSavingStrategy() {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```


此字段可以包含在转换期间必须使用（如果存在）的保存策略，以自定义处理与已保存 HTML 的节点相关的已创建引用资源文件（如图像和字体）。该策略必须处理资源并返回表示生成的 HTML 中已保存资源的所需 URL 的字符串。

**退货：**
[ResourceSavingStrategy](../../com.aspose.pdf/resourcesavingstrategy) - ResourceSavingStrategy 实例
### getCustomStrategyOfCssUrlCreation() {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```


该字段可以包含返回主题 CSS 的 URL（或 URL 模板，如果多页生成打开 - 请参阅下面的详细信息）的自定义方法，因为它应该放在生成的结果 HTML 中。如果您希望转换器将一些特定的 URL 而不是标准的 CSS 文件名放入生成的 CSS，那么您应该只创建并放入此生成所需 URL 的属性方法。如果设置了“SplitCssIntoPages”标志，则此自定义策略（如果有）必须返回的不是 CSS 的确切 URL，而是模板字符串（在用转换器中的 String.Format() 函数用页码替换占位符之后）可以解析为 URL对于这个或那个页面的 CSS URL。在这种情况下预期返回字符串的例子是：'SomeTargetLocation-page\_\{0\}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage=\ {0\} ')

**退货：**
[CssUrlMakingStrategy](../../com.aspose.pdf/cssurlmakingstrategy) - CssUrlMakingStrategy 实例
### getDefaultFontName() {#getDefaultFontName--}
```
public String getDefaultFontName()
```


指定已安装字体的名称，用于替换任何未嵌入且未安装在系统中的文档字体。如果为空，则使用默认替换字体。

**退货：**
java.lang.String - 字符串值：字体名称
### getDocumentType() {#getDocumentType--}
```
public int getDocumentType()
```


获取 HtmlDocumentTypeInternal 。

**退货：**
int - HtmlDocumentTypeInternal 。
### getExcludeFontNameList() {#getExcludeFontNameList--}
```
public String[] getExcludeFontNameList()
```


未嵌入 HTML 的 PDF 嵌入字体名称列表。

**退货：**
java.lang.字符串[] - 字符串元素数组
### getExplicitListOfSavedPages() {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```


使用此属性，您可以明确定义应转换文档的哪些页面。此列表中的页面必须具有从 1 开始的数字。即有效页数必须取自范围（1 ...[NumberOfPagesInConvertedDocument]) 此列表中页面的出现顺序不会影响它们在结果 HTML 页面中的顺序 - 结果页面始终按照它们在源 PDF 中的顺序排列。如果此列表为空（默认情况下为空），则将转换所有页面。如果此列表的任何页码超出当前页面的范围（1-[amountOfPagesInDocument]) 异常将被抛出。

**退货：**
整数[]
### getFixedLayout() {#getFixedLayout--}
```
public boolean getFixedLayout()
```


获取一个值，该值指示该 HTML 是否创建为固定布局。

**退货：**
布尔值 - 值：如果为真[固定布局];否则，假的。
### getFontEncodingStrategy() {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```


定义编码特殊规则以调整当前文档的 PDF 解码

**退货：**
byte - FontEncodingRules 元素
### getFontSavingMode() {#getFontSavingMode--}
```
public int getFontSavingMode()
```


定义将 PDF 保存为所需格式时使用的字体保存模式

**退货：**
int - FontSavingModes 元素
### getFontSources() {#getFontSources--}
```
public FontSourceCollection getFontSources()
```


预存字体的字体来源。

**退货：**
[FontSourceCollection](../../com.aspose.pdf.text/fontsourcecollection) FontSourceCollection 对象

--------------------

字体可以预先保存用于缓存目的，然后传递到 Html 转换过程。例如，它可能在文档拆分场景和使用单组字体在多个线程中处理文档页面时很有用。
### getHtmlMarkupGenerationMode() {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```


有时存在生成 HTML 标记的特定要求。此参数定义 HTML 准备模式，可在将 PDF 转换为 HTML 期间使用这些模式以匹配此类特定要求。

**退货：**
int - HtmlMarkupGenerationModes 元素
### getImageResolution() {#getImageResolution--}
```
public int getImageResolution()
```


获取或设置图像渲染的分辨率。

**退货：**
int - 值：分辨率
### getLettersPositioningMethod() {#getLettersPositioningMethod--}
```
public int getLettersPositioningMethod()
```


在结果 HTML 中设置单词中字母的定位模式

**退货：**
int - LettersPositioningMethods 元素
### getMinimalLineWidth() {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```


此属性设置图形路径线的最小宽度。如果线条粗细小于 1 像素，Adobe Acrobat 会将其四舍五入到该值。因此，此属性可用于为 HTML 浏览器模拟此行为。

**退货：**
float - 浮点值
### getPageBorderIfAny() {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```


此属性表示用于在表示源 PDF 页面的区域周围的结果 HTML 文档中绘制边框（如果有）的设置集。本质上它涉及显示页面的纸张边缘，而不是 PDF 页面本身引用的页面边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo 实例
### getPageMarginIfAny() {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```


此属性表示结果 HTML 文档中表示源 PDF 页面区域周围的一组额外页边距（如果有）。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 实例
### getPartsEmbeddingMode() {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```


它定义了引用文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中还是作为单独的二进制实体生成

**退货：**
int - PartsEmbeddingModes 元素
### getPreventGlyphsGrouping() {#getPreventGlyphsGrouping--}
```
public boolean getPreventGlyphsGrouping()
```


当文本字形不会被分组为单词和字符串时，此属性会打开模式此模式允许在页面上定位字形时保持最大精度，它可用于转换文档与音符或字形应分别放置其他。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。

**退货：**
boolean - 布尔值
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分

**退货：**
com.aspose.pdf.ConversionProgressEventsTranslator - ConversionProgressEventsTranslator 实例
### getRasterImagesSavingMode() {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```


转换后的 PDF 可以包含光栅图像 此参数定义在将 PDF 转换为 HTML 期间应如何处理它们

**退货：**
int - RasterImagesSavingModes 元素
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


数据保存格式。

**退货：**
[SaveFormat](../../com.aspose.pdf/saveformat) 保存格式值
### getSimpleTextboxModeGrouping() {#getSimpleTextboxModeGrouping--}
```
public final boolean getSimpleTextboxModeGrouping()
```


此属性指定按顺序将字形和单词分组为字符串。例如，标签和单词在转换后的 HTML 中具有不同的顺序，您希望它们匹配。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。

**退货：**
boolean - 布尔值
### getSpecialFolderForAllImages() {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```


获取或设置目录的路径，如果在将文档保存为 HTML 期间遇到任何图像，则必须将这些图像保存到该目录。如果参数为空或 null，则图像文件（如果有）将与链接到 HTML 的其他文件一起保存如果 CustomImageSavingStrategy 属性已成功用于处理相关图像文件，则不会有任何影响。

**退货：**
java.lang.String - 字符串值
### getSpecialFolderForSvgImages() {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```


获取或设置目录的路径，如果在将文档保存为 HTML 期间遇到 SVG 图像，则必须将它们保存到该目录中。如果参数为空或 null，则 SVG 文件（如果有）将与其他图像文件（靠近输出文件）一起保存或保存在图像的特殊文件夹中（如果它在 SpecialImagesFolderIfAny 选项中指定）。如果成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则不会有任何影响。

**退货：**
java.lang.String - 字符串值
### getSplitCssIntoPages() {#getSplitCssIntoPages--}
```
public boolean getSplitCssIntoPages()
```


When multipage-mode selected(ie 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page.默认情况下，此属性为 false，因此将为所有创建的页面创建一个大的通用 CSS。在这种模式下生成的所有 CSS 的总大小（每页一个 CSS）通常比一个大 CSS 文件的大小大得多，因为在前一种情况下，CSS 类在这种情况下在每个页面的几个 CSS 文件中是重复的。因此，仅当您对每个 HTML 页面的未来处理感兴趣时才使用此设置更糟糕，因此拆分的每个页面的 CSS 大小是最关键的问题。

**退货：**
boolean - 布尔值
### getSplitIntoPages() {#getSplitIntoPages--}
```
public boolean getSplitIntoPages()
```


获取指示源文档的每个页面是否将转换为它自己的目标 HTML 文档的标志，即结果 HTML 是否将拆分为多个 HTML 页面。

**退货：**
boolean - 布尔值
### getUseZOrder() {#getUseZOrder--}
```
public boolean getUseZOrder()
```


如果属性 UseZORder 设置为 true，则图形和文本将根据原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。如果此属性为 false，则所有图形都作为单层放置，这可能会对重叠对象造成一些不必要的影响。

**退货：**
boolean - 布尔值
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Save 操作继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。

**退货：**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback 值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


获取布尔值，该值指示在文档保存到响应后将关闭响应对象。

**退货：**
boolean - 布尔值
### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。

Value：结果文档中将提取真实的文本；否则，假的。

**退货：**
boolean - 布尔值
### isPagesFlowTypeDependsOnViewersScreenSize() {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```


如果属性“SplitOnPages=false”，那么代表所有输入 PDF 页面的整个 HTML 将被放入一个大的结果 HTML 文件中。此标志定义结果 HTML 是否将以这样的方式生成，即结果 HTML 中表示 PDF 页面的区域流将取决于查看器的屏幕分辨率。假设观看者一侧的屏幕宽度足够大，可以将 2 个或更多页面在水平方向上并排放置。如果此标志设置为真，则将使用此机会（尽可能多的页面将在水平方向上一个接一个地显示，然后下一组水平页面将显示在第一个页面下方）。否则页面将以这种方式流动：下一页总是在上一页下面。

**退货：**
boolean - 布尔值
### isRemoveEmptyAreasOnTopAndBottom() {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```


定义是否在创建的 HTML 中删除没有任何内容（如果有）的顶部和底部空白区域。

**退货：**
boolean - 布尔值
### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


如果属性 RenderTextAsImage 设置为 true，则源中的文本将变为 HTML 中的图像。使文本不可选择或 HTML 文本未正确呈现可能很有用。

**退货：**
boolean - 布尔值
### isSaveFullFont() {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```


表示将保存完整字体，仅支持 True Type 字体。默认情况下 SaveFullFont = false 并且转换器保存显示文档文本所需的初始字体的子集。

**退货：**
boolean - 布尔值
### isSaveShadowedTextsAsTransparentTexts() {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```


Pdf 可以包含被其他元素遮蔽的文本（fe 被图像遮盖），但可以在 Acrobat Reader 中选择到剪贴板（通常发生在文档包含图像和从中提取的 OCRed 文本时）。此设置告诉转换器我们是否需要将此类文本保存为结果 HTML 中的透明可选文本以模仿 Acrobat Reader 的行为（否则此类文本通常保存为隐藏，不可用于复制到剪贴板）

**退货：**
boolean - 布尔值
### isSaveTransparentTexts() {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```


Pdf 可以包含可以选择到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCRed 文本时）。此设置告诉转换器我们是否需要将此类文本保存为结果 HTML 中的透明可选文本

**退货：**
boolean - 布尔值
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。在这种情况下，目标格式的渲染器（DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果看起来导出的文档包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不需要的效果。注意力！这种质量优化通常会减慢转换速度，因此请仅在确实需要时才使用此选项。

**退货：**
boolean - 布尔值
### isTrySaveTextUnderliningAndStrikeoutingInCss() {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```


PDF 本身不包含文本的下划线标记。它模拟了位于文本下方的线。此选项允许转换器尝试猜测此行或那行是文本的下划线并将此信息放入 CSS 而不是以图形方式绘制下划线

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdditionalMarginWidthInPoints(int value) {#setAdditionalMarginWidthInPoints-int-}
```
public void setAdditionalMarginWidthInPoints(int value)
```


如果属性'SplitOnPages=false'，则代表所有输入PDF页面的整个HTML不会被拆分成不同的HTML页面，而是被放入一个大的结果HTML文件中。但是每个源 PDF 页面都将在 HTML 中用它自己的矩形区域表示（如果需要，可以用特殊属性“PageBorderIfAny”对区域进行边框显示页面纸张边缘。此参数定义将在输出 HTML 周围强制保留的页边距宽度-表示源 PDF 文档页面的区域。本质上，它定义了 PDF“纸质”页面的 HTML 表示之间的保证间隔，这种转换模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setAntialiasingProcessing(int antialiasingProcessing) {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```


此参数定义在将复合背景图像从 PDF 转换为 HTML 期间所需的抗锯齿措施

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| antialiasingProcessing | int | AntialiasingProcessingType 元素 |

### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


如果批量转换适用于源格式和目标格式对，则定义批量大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


设置布尔值，指示在文档保存到响应后将关闭响应对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCompressSvgGraphicsIfAny(boolean value) {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```


设置标志，指示在保存期间是否将找到的 SVG 图形（如果有）压缩（zipped）为 SVGZ 格式

值： HtmlDocumentType 。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setConvertMarkedContentToLayers(boolean value) {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```


如果属性 ConvertMarkedContentToLayers 设置为 true，则 PDF 标记内容（图层）内的所有元素将被放入 HTML div 中，“data-pdflayer”属性指定图层名称。该图层名称将从 PDF 标记内容的可选属性中提取。如果此属性为 false（默认情况下），则不会从 PDF 标记内容创建任何图层。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCssClassNamesPrefix(String cssClassNamesPrefix) {#setCssClassNamesPrefix-java.lang.String-}
```
public void setCssClassNamesPrefix(String cssClassNamesPrefix)
```


当 PDFtoHTML 转换器生成结果 CSS 时，CSS 类名（类似于“.stl\ _01\{\}" ... ".stl\ _NN\{\}) 生成并在结果 CSS 中使用。此属性允许强制设置类名前缀 例如，如果您希望所有类名都以 'my\_字首\_'（即类似于'我的\_字首\_1' ... '我的\_字首\_NNN' ) ，然后只需分配 'my\_字首\_' 在转换之前添加到此属性。如果此属性保持不变（即 null 将保留为 value ），则转换器将自行生成类名（类似于“.stl”\ _01\{\}" ... ".stl\ _NN\{\}")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cssClassNamesPrefix | java.lang.String | 字符串值 |

### setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy) {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
```
public void setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy)
```


此字段可以包含在将 Pdf 转换为 Html 期间必须使用（如果存在）的保存策略，用于处理与创建的 HTML 文档整体或与其页面相关的 CSS 的保存（如果生成多个 HTML 页面）如果你想处理 CSS 文件以某种特定方式，请创建相关方法并将从中创建的委托分配给此属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customCssSavingStrategy | [CssSavingStrategy](../../com.aspose.pdf/csssavingstrategy) | CssSavingStrategy 实例 |

### setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy) {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
```
public void setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy)
```


转换的结果可以包含一个或多个 HTML 页面您可以分配给此属性委托，该委托是从自定义方法创建的，该方法实现了一个 HTML 页面（准确地说是标记 HTML，没有外部链接文件，如果有的话）的处理过程中创建的转换。在这种情况下，处理（如将页面的 HTML 保存在流或磁盘中）可以在该自定义代码中完成。在这种情况下，保存 HTML 页面的所有必要操作都必须在提供的方法代码中进行，因为在转换器代码中保存结果将不会被使用。如果出于某种原因必须由转换器代码本身而不是自定义代码来处理这种或那种情况，请在“htmlSavingInfo”参数变量的自定义代码标志“CustomProcessingCancelled”中进行设置：它会向转换器发出所有必要步骤的信号该资源的处理必须在转换器本身中完成，就像没有任何外部自定义代码进行处理一样。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customHtmlSavingStrategy | [HtmlPageMarkupSavingStrategy](../../com.aspose.pdf/htmlpagemarkupsavingstrategy) | HtmlPageMarkupSavingStrategy 实例 |

### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)
```


此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是：

--------------------

```
public static void ConvertWithShowingProgress()
     {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() {
     public void invoke(
     UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {
     showProgressOnConsole(eventInfo);
     }
     };
     doc.save("Booklet.doc", saveOptions);
     }
     public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
     {
     switch (eventInfo.EventType)
     {
     case HtmlSaveOptions.ProgressEventType.TotalProgress:
     System.out.println(String.format("%s  - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value));
     break;
     case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
     System.out.println(String.format("%s  - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
     System.out.println(String.format("%s  - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
     System.out.println(String.format("%s  - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     default:
     break;
     }
     }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customProgressHandler | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | ConversionProgressEventHandler 实例 |

### setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy) {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
```
public void setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy)
```


此字段可以包含在转换期间必须使用（如果存在）的保存策略，以自定义处理与已保存 HTML 的节点相关的已创建引用资源文件（如图像和字体）。该策略必须处理资源并返回表示生成的 HTML 中已保存资源的所需 URL 的字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customResourceSavingStrategy | [ResourceSavingStrategy](../../com.aspose.pdf/resourcesavingstrategy) | ResourceSavingStrategy 实例 |

### setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation) {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
```
public void setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation)
```


该字段可以包含返回主题 CSS 的 URL（或 URL 模板，如果多页生成打开 - 请参阅下面的详细信息）的自定义方法，因为它应该放在生成的结果 HTML 中。如果您希望转换器将一些特定的 URL 而不是标准的 CSS 文件名放入生成的 CSS，那么您应该只创建并放入此生成所需 URL 的属性方法。如果设置了“SplitCssIntoPages”标志，则此自定义策略（如果有）必须返回的不是 CSS 的确切 URL，而是模板字符串（在用转换器中的 String.Format() 函数用页码替换占位符之后）可以解析为 URL对于这个或那个页面的 CSS URL。在这种情况下预期返回字符串的例子是：'SomeTargetLocation-page\_\{0\}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage=\ {0\} ')

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customStrategyOfCssUrlCreation | [CssUrlMakingStrategy](../../com.aspose.pdf/cssurlmakingstrategy) | CssUrlMakingStrategy 实例 |

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public void setDefaultFontName(String value)
```


指定已安装字体的名称，用于替换任何未嵌入且未安装在系统中的文档字体。如果为空，则使用默认替换字体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字体名称 |

### setDocumentType(int value) {#setDocumentType-int-}
```
public void setDocumentType(int value)
```


设置 HtmlDocumentType 。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HtmlDocumentType 。 |

### setExcludeFontNameList(String[] excludeFontNameList) {#setExcludeFontNameList-java.lang.String---}
```
public void setExcludeFontNameList(String[] excludeFontNameList)
```


未嵌入 HTML 的 PDF 嵌入字体名称列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| excludeFontNameList | java.lang.String[] | 字符串元素数组 |

### setExplicitListOfSavedPages(int[] value) {#setExplicitListOfSavedPages-int---}
```
public final void setExplicitListOfSavedPages(int[] value)
```


使用此属性，您可以明确定义应转换文档的哪些页面。此列表中的页面必须具有从 1 开始的数字。即有效页数必须取自范围（1 ...[NumberOfPagesInConvertedDocument]) 此列表中页面的出现顺序不会影响它们在结果 HTML 页面中的顺序 - 结果页面始终按照它们在源 PDF 中的顺序排列。如果此列表为空（默认情况下为空），则将转换所有页面。如果此列表的任何页码超出当前页面的范围（1-[amountOfPagesInDocument]) 异常将被抛出。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### setExtractOcrSublayerOnly(boolean value) {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```


此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。

Value：结果文档中将提取真实的文本；否则，假的。

--------------------

默认值 == 假

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFixedLayout(boolean value) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```


设置一个值，指示该 HTML 是否创建为固定布局。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  真如果[固定布局];否则，假的。 |

### setFontEncodingStrategy(byte fontEncodingStrategy) {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```


定义编码特殊规则以调整当前文档的 PDF 解码

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontEncodingStrategy | byte | FontEncodingRules 元素 |

### setFontSavingMode(int fontSavingMode) {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```


定义将 PDF 保存为所需格式时使用的字体保存模式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontSavingMode | int | FontSavingModes 元素 |

### setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode) {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```


有时存在生成 HTML 标记的特定要求。此参数定义 HTML 准备模式，可在将 PDF 转换为 HTML 期间使用这些模式以匹配此类特定要求。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| htmlMarkupGenerationMode | int | HtmlMarkupGenerationModes 元素 |

### setImageResolution(int value) {#setImageResolution-int-}
```
public void setImageResolution(int value)
```


获取或设置图像渲染的分辨率。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 值：分辨率 |

### setLettersPositioningMethod(int lettersPositioningMethod) {#setLettersPositioningMethod-int-}
```
public void setLettersPositioningMethod(int lettersPositioningMethod)
```


在结果 HTML 中设置单词中字母的定位模式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| lettersPositioningMethod | int | LettersPositioningMethods 元素 |

### setMinimalLineWidth(float value) {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```


此属性设置图形路径线的最小宽度。如果线条粗细小于 1 像素，Adobe Acrobat 会将其四舍五入到该值。因此，此属性可用于为 HTML 浏览器模拟此行为。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny) {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
```
public void setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny)
```


此属性表示用于在表示源 PDF 页面的区域周围的结果 HTML 文档中绘制边框（如果有）的设置集。本质上它涉及显示页面的纸张边缘，而不是 PDF 页面本身引用的页面边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageBorderIfAny | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 实例 |

### setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny) {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
```
public void setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny)
```


此属性表示结果 HTML 文档中表示源 PDF 页面区域周围的一组额外页边距（如果有）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageMarginIfAny | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 实例 |

### setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize) {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```


如果属性“SplitOnPages=false”，那么代表所有输入 PDF 页面的整个 HTML 将被放入一个大的结果 HTML 文件中。此标志定义结果 HTML 是否将以这样的方式生成，即结果 HTML 中表示 PDF 页面的区域流将取决于查看器的屏幕分辨率。假设观看者一侧的屏幕宽度足够大，可以将 2 个或更多页面在水平方向上并排放置。如果此标志设置为真，则将使用此机会（尽可能多的页面将在水平方向上一个接一个地显示，然后下一组水平页面将显示在第一个页面下方）。否则页面将以这种方式流动：下一页总是在上一页下面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize | boolean | 布尔值 |

### setPartsEmbeddingMode(int partsEmbeddingMode) {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```


它定义了引用文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中还是作为单独的二进制实体生成

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| partsEmbeddingMode | int | PartsEmbeddingModes 元素 |

### setPreventGlyphsGrouping(boolean value) {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```


当文本字形不会被分组为单词和字符串时，此属性会打开模式此模式允许在页面上定位字形时保持最大精度，它可用于转换文档与音符或字形应分别放置其他。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | ConversionProgressEventsTranslator 实例 |

### setRasterImagesSavingMode(int rasterImagesSavingMode) {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```


转换后的 PDF 可以包含光栅图像 此参数定义在将 PDF 转换为 HTML 期间应如何处理它们

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImagesSavingMode | int | RasterImagesSavingModes 元素 |

### setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom) {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```


定义是否在创建的 HTML 中删除没有任何内容（如果有）的顶部和底部空白区域。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom | boolean | 布尔值 |

### setRenderTextAsImage(boolean value) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```


如果属性 RenderTextAsImage 设置为 true，则源中的文本将变为 HTML 中的图像。使文本不可选择或 HTML 文本未正确呈现可能很有用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSaveFullFont(boolean saveFullFont) {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean saveFullFont)
```


表示将保存完整字体，仅支持 True Type 字体。默认情况下 SaveFullFont = false 并且转换器保存显示文档文本所需的初始字体的子集。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| saveFullFont | boolean | 布尔值 |

### setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts) {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```


Pdf 可以包含被其他元素遮蔽的文本（fe 被图像遮盖），但可以在 Acrobat Reader 中选择到剪贴板（通常发生在文档包含图像和从中提取的 OCRed 文本时）。此设置告诉转换器我们是否需要将此类文本保存为结果 HTML 中的透明可选文本以模仿 Acrobat Reader 的行为（否则此类文本通常保存为隐藏，不可用于复制到剪贴板）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts | boolean | 布尔值 |

### setSaveTransparentTexts(boolean saveTransparentTexts) {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```


Pdf 可以包含可以选择到剪贴板的透明文本（通常发生在文档包含图像和从中提取的 OCRed 文本时）。此设置告诉转换器我们是否需要将此类文本保存为结果 HTML 中的透明可选文本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| saveTransparentTexts | boolean | 布尔值 |

### setSimpleTextboxModeGrouping(boolean value) {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```


此属性指定按顺序将字形和单词分组为字符串。例如，标签和单词在转换后的 HTML 中具有不同的顺序，您希望它们匹配。仅当 FixedLayout 属性的值为 true 时，此参数才会应用于文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSpecialFolderForAllImages(String specialFolderForAllImages) {#setSpecialFolderForAllImages-java.lang.String-}
```
public void setSpecialFolderForAllImages(String specialFolderForAllImages)
```


获取或设置目录的路径，如果在将文档保存为 HTML 期间遇到任何图像，则必须将这些图像保存到该目录。如果参数为空或 null，则图像文件（如果有）将与链接到 HTML 的其他文件一起保存如果 CustomImageSavingStrategy 属性已成功用于处理相关图像文件，则不会有任何影响。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| specialFolderForAllImages | java.lang.String | 字符串值 |

### setSpecialFolderForSvgImages(String specialFolderForSvgImages) {#setSpecialFolderForSvgImages-java.lang.String-}
```
public void setSpecialFolderForSvgImages(String specialFolderForSvgImages)
```


获取或设置目录的路径，如果在将文档保存为 HTML 期间遇到 SVG 图像，则必须将它们保存到该目录中。如果参数为空或 null，则 SVG 文件（如果有）将与其他图像文件（靠近输出文件）一起保存或保存在图像的特殊文件夹中（如果它在 SpecialImagesFolderIfAny 选项中指定）。如果成功使用 CustomImageSavingStrategy 属性处理相关图像文件，则不会有任何影响。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| specialFolderForSvgImages | java.lang.String | 字符串值 |

### setSplitCssIntoPages(boolean value) {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```


When multipage-mode selected(ie 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page.默认情况下，此属性为 false，因此将为所有创建的页面创建一个大的通用 CSS。在这种模式下生成的所有 CSS 的总大小（每页一个 CSS）通常比一个大 CSS 文件的大小大得多，因为在前一种情况下，CSS 类在这种情况下在每个页面的几个 CSS 文件中是重复的。因此，仅当您对每个 HTML 页面的未来处理感兴趣时才使用此设置更糟糕，因此拆分的每个页面的 CSS 大小是最关键的问题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSplitIntoPages(boolean value) {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```


设置标志，指示源文档的每一页是否将转换为它自己的目标 HTML 文档，即结果 HTML 是否将被拆分为多个 HTML 页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。在这种情况下，目标格式的渲染器（DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果看起来导出的文档包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不需要的效果。注意力！这种质量优化通常会减慢转换速度，因此请仅在确实需要时才使用此选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | 布尔值 |

### setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss) {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```


PDF 本身不包含文本的下划线标记。它模拟了位于文本下方的线。此选项允许转换器尝试猜测此行或那行是文本的下划线并将此信息放入 CSS 而不是以图形方式绘制下划线

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss | boolean | 布尔值 |

### setUseZOrder(boolean value) {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```


如果属性 UseZORder 设置为 true，则图形和文本将根据原始 PDF 文档中的 Z 顺序添加到生成的 HTML 文档中。如果此属性为 false，则所有图形都作为单层放置，这可能会对重叠对象造成一些不必要的影响。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Save 操作继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback 值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
