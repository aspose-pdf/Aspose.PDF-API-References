---
title: Document
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 PDF 文档的类
type: docs
weight: 91
url: /zh/java/com.aspose.pdf/document/
---
**遗产：**
java.lang.Object, com.aspose.pdf.IVentureLicenseTarget, com.aspose.pdf.ADocument

**所有已实现的接口：**
[com.aspose.pdf.IDocument](../../com.aspose.pdf/idocument)
```
public final class Document extends ADocument implements IDocument
```

表示 PDF 文档的类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Document()](#Document--) | 初始化空文档。 |
| [Document(byte[] input)](#Document-byte---) | 从输入字节数组初始化新的 Document 实例。 |
| [Document(InputStream input)](#Document-java.io.InputStream-) | 从输入流初始化新的 Document 实例。 |
| [Document(InputStream input, String password)](#Document-java.io.InputStream-java.lang.String-) | 从输入流初始化新的 Document 实例。 |
| [Document(System.IO.Stream input)](#Document-com.aspose.ms.System.IO.Stream-) | 从输入流初始化新的 Document 实例。 |
| [Document(InputStream input, String password, boolean isManagedStream)](#Document-java.io.InputStream-java.lang.String-boolean-) | 从输入流初始化新的 Document 实例。 |
| [Document(InputStream input, boolean isManagedStream)](#Document-java.io.InputStream-boolean-) | 从输入流初始化新的 Document 实例。 |
| [Document(InputStream input, LoadOptions options)](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | 从流中打开现有文档，提供必要的转换以获取 pdf 文档。 |
| [Document(String filename, LoadOptions options)](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | 从提供必要转换以获取 pdf 文档的文件中打开现有文档。 |
| [Document(System.IO.Stream input, String password)](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | 从流中打开现有文档。 |
| [Document(String filename)](#Document-java.lang.String-) | 只需使用 filename 初始化 Document 。 |
| [Document(String filename, String password)](#Document-java.lang.String-java.lang.String-) | 初始化 Document 类的新实例以处理加密文档。 |
| [Document(String filename, String password, boolean isManagedStream)](#Document-java.lang.String-java.lang.String-boolean-) | 初始化 Document 类的新实例以处理加密文档。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [FontSubstitution](#FontSubstitution) | 当字体替换文档中的另一种字体时会发生这种情况。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [afterImport()](#afterImport--) | 枚举所有已注册的注释并为每个注释调用 AfterImport。 |
| [bindXml(InputStream stream)](#bindXml-java.io.InputStream-) | 将 xml 绑定到文档 |
| [bindXml(InputStream xmlStream, InputStream xslStream)](#bindXml-java.io.InputStream-java.io.InputStream-) | 将 xml/xsl 绑定到文档 |
| [bindXml(InputStream xmlStream, InputStream xslStream, System.Xml.XmlReaderSettings settings)](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | 将 xml/xsl 绑定到文档 |
| [bindXml(String file)](#bindXml-java.lang.String-) | 将 xml 绑定到文档 |
| [bindXml(String xmlFile, String xslFile)](#bindXml-java.lang.String-java.lang.String-) | 将 xml/xsl 绑定到文档 |
| [changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | 更改文档密码。 |
| [check(boolean doRepair)](#check-boolean-) | 验证文档。 |
| [close()](#close--) | 关闭此文档使用的所有资源。 |
| [convert(Document.CallBackGetHocr callback)](#convert-com.aspose.pdf.Document.CallBackGetHocr-) | 将文档转换为可搜索的文档。 |
| [convert(Document.CallBackGetHocr callback, boolean isTestVisible)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-) | 转换文档并将错误保存到指定文件中。 |
| [convert(Document.CallBackGetHocr callback, boolean isTextVisible, boolean isOriginalImage)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-) | 转换文档并将错误保存到指定文件中。 |
| [convert(PdfFormatConversionOptions options)](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | 使用指定的转换选项转换文档 |
| [convert(int fixup, OutputStream outputLog)](#convert-int-java.io.OutputStream-) | 通过应用 Fixup 转换文档。 |
| [convert(int fixup, OutputStream outputLog, boolean onlyValidation, Object[] parameters)](#convert-int-java.io.OutputStream-boolean-java.lang.Object---) | 通过应用 Fixup 转换文档。 |
| [convert(int fixup, String outputLog)](#convert-int-java.lang.String-) | 通过应用 Fixup 转换文档。 |
| [convert(int fixup, String outputLog, boolean onlyValidation, Object[] parameters)](#convert-int-java.lang.String-boolean-java.lang.Object---) | 通过应用 Fixup 转换文档。 |
| [convert(InputStream srcStream, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions)](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 将源格式的流转换为目标格式的流。 |
| [convert(InputStream srcStream, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions)](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | 将源格式的流转换为目标格式的目标文件。 |
| [convert(OutputStream outputLogStream, PdfFormat format, int action)](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) | 转换文档并将错误保存到指定的流中。 |
| [convert(OutputStream outputLogStream, PdfFormat format, int action, int transparencyAction)](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-int-) | 转换文档并将错误保存到指定文件中。 |
| [convert(String srcFileName, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions)](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 将源格式的源文件转换为目标格式的流。 |
| [convert(String srcFileName, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions)](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | 将源格式的源文件转换为目标格式的目标文件。 |
| [convert(String outputLogFileName, PdfFormat format, int action)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-) | 转换文档并将错误保存到指定文件中。 |
| [convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | 转换文档并将错误保存到指定文件中。 |
| [convertInternal(System.IO.Stream outputLogStream, PdfFormat format, int action)](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-) | 转换文档并将错误保存到指定的流中。 |
| [convertPageToPNGMemoryStream(Page page)](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | 为 DSR、OMR、OCR 图像流将页面转换为 PNG。 |
| [convertWithSkippingErrors(Document.CallBackGetHocr callback)](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-) | 将文档转换为可搜索文档并跳过无法转换的 hochr 错误。 |
| [decrypt()](#decrypt--) | 解密文档。 |
| [dispose()](#dispose--) | 关闭此文档使用的所有资源。 |
| [encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-) | 加密文档。 |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | 加密文档。 |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-int-int-boolean-) | 加密文档。 |
| [endOperation()](#endOperation--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportAnnotationsToXfdf(OutputStream output)](#exportAnnotationsToXfdf-java.io.OutputStream-) | 将所有文档注释导出到流中。 |
| [exportAnnotationsToXfdf(String fileName)](#exportAnnotationsToXfdf-java.lang.String-) | 将所有文档注释导出到 XFDF 文件 |
| [flatten()](#flatten--) | 从文档中删除所有字段并改为放置它们的值。 |
| [flatten(Form.FlattenSettings flattenSettings)](#flatten-com.aspose.pdf.Form.FlattenSettings-) | 从文档中删除所有字段并改为放置它们的值。 |
| [freeMemory()](#freeMemory--) | 清除内存 |
| [getAbsentFontHandler()](#getAbsentFontHandler--) | 处理文档时有关丢失字体的通知。 |
| [getActions()](#getActions--) | 获取文档操作。 |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | 允许合并页面内容以优化文档大小。 |
| [getBackground()](#getBackground--) | 获取文档的背景颜色。 |
| [getCatalogValue(String key)](#getCatalogValue-java.lang.String-) | 从目录字典返回项目值。 |
| [getClass()](#getClass--) |  |
| [getCollection()](#getCollection--) | 获取文档集合。 |
| [getCryptoAlgorithm()](#getCryptoAlgorithm--) | 如果文档已加密，则获取安全设置。 |
| [getDefaultCopier()](#getDefaultCopier--) | 将用于复印页面的复印机返回到此文档。 |
| [getDestinations()](#getDestinations--) | 获取目的地的集合。 |
| [getDirection()](#getDirection--) | 获取文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [getDuplex()](#getDuplex--) | 获取或设置从打印对话框打印文件时要使用的打印双面模式处理选项。 |
| [getEmbedStandardFonts()](#getEmbedStandardFonts--) | 声明文档必须嵌入所有标准 Type1 字体的属性，该字体的标志 IsEmbedded 设置为 true。 |
| [getEmbeddedFiles()](#getEmbeddedFiles--) | 获取嵌入文档的文件集合。 |
| [getEnableSignatureSanitization()](#getEnableSignatureSanitization--) | 获取或设置标志以管理签名字段清理。 |
| [getEngineDoc()](#getEngineDoc--) | 用于访问内部文档结构的 IPdfDocument 实例。 |
| [getFileName()](#getFileName--) | 生成此文档的 PDF 文件的名称 |
| [getFontUtilities()](#getFontUtilities--) | IDocumentFontUtilities 实例 |
| [getForm()](#getForm--) | 获取文档的 Acro 形式。 |
| [getId()](#getId--) | 获取ID。 |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | 获取或设置忽略源文件中错误的标志。 |
| [getInfo()](#getInfo--) | 获取文档信息。 |
| [getJavaScript()](#getJavaScript--) | 文档级别的 JavaScript 集合。 |
| [getLogicalStructure()](#getLogicalStructure--) | 获取文档的逻辑结构。 |
| [getMetadata()](#getMetadata--) | 文档元数据。 |
| [getMetadataStream()](#getMetadataStream--) | 返回原始元数据流 |
| [getNamedDestinations()](#getNamedDestinations--) | 文档中命名目标的集合。 |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | 获取页面模式，指定在退出全屏模式时如何显示文档。 |
| [getObjectById(String id)](#getObjectById-java.lang.String-) | 获取文档中具有指定 ID 的对象。 |
| [getOpenAction()](#getOpenAction--) | 获取打开文档时执行的操作。 |
| [getOptimizeSize()](#getOptimizeSize--) | 获取优化标志。 |
| [getOutlines()](#getOutlines--) | 获取文档大纲。 |
| [getPageInfo()](#getPageInfo--) | 获取页面信息。 |
| [getPageLabels()](#getPageLabels--) | 获取文档中的页面标签。 |
| [getPageLayout()](#getPageLayout--) | 获取打开文档时应使用的页面布局。 |
| [getPageMode()](#getPageMode--) | 获取页面模式，指定打开文档时应如何显示。 |
| [getPages()](#getPages--) | 获取文档页面的集合。 |
| [getPdfFormat()](#getPdfFormat--) | 获取pdfa格式 |
| [getPermissions()](#getPermissions--) | 获取文档的权限。 |
| [getTaggedContent()](#getTaggedContent--) | 获取对 TaggedPdf 内容的访问权限。 |
| [getVersion()](#getVersion--) | 从 Pdf 文件头获取 Pdf 的版本。 |
| [getXmpMetadata(OutputStream output)](#getXmpMetadata-java.io.OutputStream-) | 从文档中获取 XMP 元数据。 |
| [hashCode()](#hashCode--) |  |
| [importAnnotationsFromXfdf(InputStream stream)](#importAnnotationsFromXfdf-java.io.InputStream-) | 将注释从流导入文档。 |
| [importAnnotationsFromXfdf(String fileName)](#importAnnotationsFromXfdf-java.lang.String-) | 将注释从 XFDF 文件导入文档。 |
| [isAbsentFontTryToSubstitute()](#isAbsentFontTryToSubstitute--) | 通知丢失字体替换的标志。 |
| [isCenterWindow()](#isCenterWindow--) | 获取指定文档窗口的位置是否将在屏幕上居中的标志。 |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | 如果该字体的许可证禁止这些操作，则无法执行该字体的许多操作。 |
| [isDisplayDocTitle()](#isDisplayDocTitle--) | 获取指定文档窗口标题栏是否应显示文档标题的标志。 |
| [isEnableObjectUnload()](#isEnableObjectUnload--) | 获取或设置使文档能够从内存中部分卸载的标志。 |
| [isEncrypted()](#isEncrypted--) | 获取文档的加密状态。 |
| [isFitWindow()](#isFitWindow--) | 获取指定是否必须调整文档窗口大小以适合显示的第一个页面的标志。 |
| [isHandleSignatureChange()](#isHandleSignatureChange--) | 如果文档将保存更改并具有签名，则抛出异常 |
| [isHideMenubar()](#isHideMenubar--) | 获取指定在文档处于活动状态时是否应隐藏菜单栏的标志。 |
| [isHideToolBar()](#isHideToolBar--) | 获取指定在文档处于活动状态时是否应隐藏工具栏的标志。 |
| [isHideWindowUI()](#isHideWindowUI--) | 获取指定在文档处于活动状态时是否应隐藏用户界面元素的标志。 |
| [isLicensed()](#isLicensed--) | 获取系统的许可状态。 |
| [isLinearized()](#isLinearized--) | 获取一个值，该值指示文档是否已线性化。 |
| [isManualDisposeEnabled()](#isManualDisposeEnabled--) | 默认方法保存关闭内部流并释放内存资源。 |
| [isPdfUaCompliant()](#isPdfUaCompliant--) | 获取符合 pdfua 标准的文档。 |
| [isPdfaCompliant()](#isPdfaCompliant--) | 获取符合 pdfa 标准的文档。 |
| [isSkippedPdfaCompliantValidationBeforeSave()](#isSkippedPdfaCompliantValidationBeforeSave--) | 默认情况下，如果某些规则被破坏，pdfa 验证过程是更新或删除 pdfa 兼容数据所必需的。 |
| [isXrefGapsAllowed()](#isXrefGapsAllowed--) | 获取或设置文档 pdfa 兼容。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize()](#optimize--) | 线性化文档以便 - 尽快打开第一页； - 尽快显示下一页或通过链接进入下一页； - 当页面数据通过慢速通道传送时，在页面到达时逐步显示页面（首先显示最有用的数据）； - 允许甚至在接收和显示整个页面之前执行用户交互，例如跟随链接。 |
| [optimizeResources()](#optimizeResources--) | 优化文档中的资源： 1。 |
| [optimizeResources(OptimizationOptions strategy)](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | 根据定义的优化策略优化文档中的资源。 |
| [preSave(PageCollection pages, SaveOptions saveOptions)](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | 内部方法 |
| [processParagraphs()](#processParagraphs--) | 将文档存储到流中。 |
| [removeMetadata()](#removeMetadata--) | 从文档中删除元数据。 |
| [removePdfUaCompliance()](#removePdfUaCompliance--) | 从文档中删除 pdfUa 合规性 |
| [removePdfaCompliance()](#removePdfaCompliance--) | 从文档中删除 pdfa 合规性 |
| [repair()](#repair--) | 修复损坏的文档。 |
| [resumeUpdate()](#resumeUpdate--) | 恢复文档更新 |
| [save()](#save--) | 增量保存文档（即使用增量更新技术）。 |
| [save(System.IO.Stream output)](#save-com.aspose.ms.System.IO.Stream-) | 将文档存储到流中。 |
| [save(SaveOptions options)](#save-com.aspose.pdf.SaveOptions-) | 使用保存选项保存文档。 |
| [save(OutputStream output)](#save-java.io.OutputStream-) | 将文档存储到流中。 |
| [save(OutputStream outputStream, SaveFormat format)](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | 使用新名称和文件格式保存文档。 |
| [save(OutputStream outputStream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 使用保存选项将文档保存到流中。 |
| [save(String outputFileName)](#save-java.lang.String-) | 将文档保存到指定的文件中。 |
| [save(String outputFileName, SaveFormat format)](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | 使用新名称和文件格式保存文档。 |
| [save(String outputFileName, SaveOptions options)](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | 使用设置其保存选项的新名称保存文档。 |
| [saveIncrementally(System.IO.Stream output)](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | 将 PDF 文档增量保存到指定的流。 |
| [saveIncrementally(OutputStream output)](#saveIncrementally-java.io.OutputStream-) | 将 PDF 文档增量保存到指定的流。 |
| [saveIncrementally(String outputFileName)](#saveIncrementally-java.lang.String-) | 将 PDF 文档增量保存到指定的流。 |
| [saveXml(String file)](#saveXml-java.lang.String-) | 将文档保存为 XML。 |
| [sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | 将文档的某些页面发送到文档设备进行处理。 |
| [sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | 将整个文档发送到文档设备进行处理。 |
| [sendTo(DocumentDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | 将整个文档发送到文档设备进行处理。 |
| [sendTo(DocumentDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | 将整个文档发送到文档设备进行处理。 |
| [setAbsentFontHandler(ADocument.AbsentFontHandler absentFontHandler)](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | 处理文档时有关丢失字体的通知。 |
| [setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)](#setAbsentFontTryToSubstitute-boolean-) | 在缺少字体的情况下，设置程序确定字体的设置标志。 |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | 允许合并页面内容以优化文档大小。 |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | 设置文档的背景颜色。 |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | 设置标志指定文档窗口的位置是否将在屏幕上居中。 |
| [setCollection(Collection value)](#setCollection-com.aspose.pdf.Collection-) | 设置文档集合。 |
| [setConvertMetadataAndCatalogOnly(boolean value)](#setConvertMetadataAndCatalogOnly-boolean-) | 获取 pdf/ua 转换器的转换参数（如果设置为 true，则仅转换元数据和文档目录） |
| [setDirection(int value)](#setDirection-int-) | 设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [setDisableFontLicenseVerifications(boolean value)](#setDisableFontLicenseVerifications-boolean-) | 如果该字体的许可证禁止这些操作，则无法执行该字体的许多操作。 |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | 设置标志指定文档的窗口标题栏是否应显示文档标题。 |
| [setDuplex(int value)](#setDuplex-int-) | 获取或设置从打印对话框打印文件时要使用的打印双面模式处理选项。 |
| [setEmbedStandardFonts(boolean value)](#setEmbedStandardFonts-boolean-) | 声明文档必须嵌入所有标准 Type1 字体的属性，该字体的标志 IsEmbedded 设置为 true。 |
| [setEnableObjectUnload(boolean value)](#setEnableObjectUnload-boolean-) | 获取或设置使文档能够从内存中部分卸载的标志。 |
| [setEnableSignatureSanitization(boolean value)](#setEnableSignatureSanitization-boolean-) | 获取或设置标志以管理签名字段清理。 |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | 设置标志，指定是否必须调整文档窗口的大小以适合显示的第一个页面。 |
| [setHandleSignatureChange(boolean value)](#setHandleSignatureChange-boolean-) | 如果文档将保存更改并具有签名，则抛出异常 |
| [setHideMenubar(boolean value)](#setHideMenubar-boolean-) | 设置标志，指定当文档处于活动状态时是否应隐藏菜单栏。 |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | 设置标志，指定在文档处于活动状态时工具栏是否应隐藏。 |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | 设置标志，指定在文档处于活动状态时是否应隐藏用户界面元素。 |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) | 获取或设置忽略源文件中错误的标志。 |
| [setLayersAdded(boolean value)](#setLayersAdded-boolean-) |  |
| [setLinearized(boolean value)](#setLinearized-boolean-) | 设置一个值，指示文档是否线性化。 |
| [setManualDisposeEnabled(boolean manualDisposeEnabled)](#setManualDisposeEnabled-boolean-) | 默认方法 save 关闭内部流并释放内存资源。 |
| [setNonFullScreenPageMode(int value)](#setNonFullScreenPageMode-int-) | 设置页面模式，指定在退出全屏模式时如何显示文档。 |
| [setOpenAction(IAppointment value)](#setOpenAction-com.aspose.pdf.IAppointment-) | 设置在文档打开时执行的操作。 |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | 设置优化标志。 |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置页面信息。 |
| [setPageLayout(int value)](#setPageLayout-int-) | 设置打开文档时应使用的页面布局。 |
| [setPageMode(int pageMode)](#setPageMode-int-) | 设置页面模式，指定打开文档时应如何显示。 |
| [setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | 默认情况下，如果某些规则被破坏，pdfa 验证过程是更新或删除 pdfa 所必需的。 |
| [setTitle(String title)](#setTitle-java.lang.String-) | 为 Pdf 文档设置标题 |
| [setXmpMetadata(InputStream stream)](#setXmpMetadata-java.io.InputStream-) | 设置文档的 XMP 元数据。 |
| [setXrefGapsAllowed(boolean value)](#setXrefGapsAllowed-boolean-) | 获取或设置文档 pdfa 兼容。 |
| [startOperation()](#startOperation--) |  |
| [suppressUpdate()](#suppressUpdate--) | 禁止更新所有页面的内容数据内容不会更新，直到调用 ResumeUpdate |
| [toString()](#toString--) |  |
| [updatePages()](#updatePages--) |  |
| [validate(PdfFormatConversionOptions options)](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | 将文档验证到指定的文件中。 |
| [validate(OutputStream outputLogStream, PdfFormat format)](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | 将文档验证到指定的文件中。 |
| [validate(String outputLogFileName, PdfFormat format)](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | 将文档验证到指定的文件中。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Document() {#Document--}
```
public Document()
```


初始化空文档。

### Document(byte[] input) {#Document-byte---}
```
public Document(byte[] input)
```


从输入字节数组初始化新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | byte[] | 带有pdf文档的字节数组。 |

### Document(InputStream input) {#Document-java.io.InputStream-}
```
public Document(InputStream input)
```


从输入流初始化新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 流式传输 pdf 文档。 |

### Document(InputStream input, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream input, String password)
```


从输入流初始化新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 输入流对象，对应的pdf受密码保护。 |
| password | java.lang.String | 用户或所有者密码。 |

### Document(System.IO.Stream input) {#Document-com.aspose.ms.System.IO.Stream-}
```
public Document(System.IO.Stream input)
```


从输入流初始化新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | com.aspose.ms.System.IO.Stream | 流式传输 pdf 文档。 |

### Document(InputStream input, String password, boolean isManagedStream) {#Document-java.io.InputStream-java.lang.String-boolean-}
```
public Document(InputStream input, String password, boolean isManagedStream)
```


从输入流初始化新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 流式传输 pdf 文档。 |
| password | java.lang.String | 用户或所有者密码。 |
| isManagedStream | boolean | 如果设置为 true 内部流在退出前关闭；否则，不是。 |

### Document(InputStream input, boolean isManagedStream) {#Document-java.io.InputStream-boolean-}
```
public Document(InputStream input, boolean isManagedStream)
```


从输入流初始化新的 Document 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 流式传输 pdf 文档。 |
| isManagedStream | boolean | 如果设置为 true 内部流在退出前关闭；否则，不是。 |

### Document(InputStream input, LoadOptions options) {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public Document(InputStream input, LoadOptions options)
```


从流中打开现有文档，提供必要的转换以获取 pdf 文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | java.io.InputStream | 要转换为 pdf 文档的输入流。 |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | 表示将输入转换为 pdf 文档的属性。 |

### Document(String filename, LoadOptions options) {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
```
public Document(String filename, LoadOptions options)
```


从提供必要转换以获取 pdf 文档的文件中打开现有文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 要转换为 pdf 文档的输入文件。 |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | 表示将文件名转换为 pdf 文档的属性。 |

### Document(System.IO.Stream input, String password) {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public Document(System.IO.Stream input, String password)
```


从流中打开现有文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| input | com.aspose.ms.System.IO.Stream | 要转换为 pdf 文档的输入文件。 |
| password | java.lang.String | 用户或所有者密码。 |

### Document(String filename) {#Document-java.lang.String-}
```
public Document(String filename)
```


只需使用 filename 初始化 Document 。与 Document(Stream) 相同。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | pdf 文档文件的名称。 |

### Document(String filename, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filename, String password)
```


初始化 Document 类的新实例以处理加密文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 文档文件名。 |
| password | java.lang.String | 用户或所有者密码。 |

### Document(String filename, String password, boolean isManagedStream) {#Document-java.lang.String-java.lang.String-boolean-}
```
public Document(String filename, String password, boolean isManagedStream)
```


初始化 Document 类的新实例以处理加密文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 文档文件名。 |
| password | java.lang.String | 用户或所有者密码。 |
| isManagedStream | boolean | 如果设置为 true 内部流在退出前关闭；否则，不是。 |

### FontSubstitution {#FontSubstitution}
```
public final PdfEvent<ADocument.FontSubstitutionHandler> FontSubstitution
```


当字体替换文档中的另一种字体时会发生这种情况。

### afterImport() {#afterImport--}
```
public void afterImport()
```


枚举所有已注册的注释并为每个注释调用 AfterImport。内部方法

### bindXml(InputStream stream) {#bindXml-java.io.InputStream-}
```
public void bindXml(InputStream stream)
```


将 xml 绑定到文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 带有 xml 文件的流 |

### bindXml(InputStream xmlStream, InputStream xslStream) {#bindXml-java.io.InputStream-java.io.InputStream-}
```
public void bindXml(InputStream xmlStream, InputStream xslStream)
```


将 xml/xsl 绑定到文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlStream | java.io.InputStream | xml 流。 |
| xslStream | java.io.InputStream | 如果使用 XSLT，则为 xsl 流。 |

### bindXml(InputStream xmlStream, InputStream xslStream, System.Xml.XmlReaderSettings settings) {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
```
public void bindXml(InputStream xmlStream, InputStream xslStream, System.Xml.XmlReaderSettings settings)
```


将 xml/xsl 绑定到文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlStream | java.io.InputStream | xml 流。 |
| xslStream | java.io.InputStream | 如果使用 XSLT，则为 xsl 流。 |
| settings | com.aspose.ms.System.Xml.XmlReaderSettings | xml 阅读器设置。 |

### bindXml(String file) {#bindXml-java.lang.String-}
```
public void bindXml(String file)
```


将 xml 绑定到文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | xml文件 |

### bindXml(String xmlFile, String xslFile) {#bindXml-java.lang.String-java.lang.String-}
```
public void bindXml(String xmlFile, String xslFile)
```


将 xml/xsl 绑定到文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlFile | java.lang.String | xml 文件。 |
| xslFile | java.lang.String | 如果使用 XSLT，则为 xsl 文件。 |

### changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword) {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
```
public void changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


更改文档密码。此操作只能使用所有者密码来完成。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 所有者密码。 |
| newUserPassword | java.lang.String | 新用户密码。 |
| newOwnerPassword | java.lang.String | 新所有者密码。 |

### check(boolean doRepair) {#check-boolean-}
```
public boolean check(boolean doRepair)
```


验证文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doRepair | boolean | 如果确实发现问题将被修复。 |

**退货：**
boolean - 布尔值
### close() {#close--}
```
public void close()
```


关闭此文档使用的所有资源。

### convert(Document.CallBackGetHocr callback) {#convert-com.aspose.pdf.Document.CallBackGetHocr-}
```
public boolean convert(Document.CallBackGetHocr callback)
```


将文档转换为可搜索的文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | hocr 识别的回调过程。 |

**退货：**
boolean - 布尔值
### convert(Document.CallBackGetHocr callback, boolean isTestVisible) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-}
```
public boolean convert(Document.CallBackGetHocr callback, boolean isTestVisible)
```


转换文档并将错误保存到指定文件中。

这允许显示/隐藏可搜索文本。默认值为 FALSE。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | 无法转换的对象的操作 |
| isTestVisible | boolean | 布尔值 |

**退货：**
boolean - 运算结果
### convert(Document.CallBackGetHocr callback, boolean isTextVisible, boolean isOriginalImage) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-}
```
public boolean convert(Document.CallBackGetHocr callback, boolean isTextVisible, boolean isOriginalImage)
```


转换文档并将错误保存到指定文件中。

这允许在页面上显示/隐藏可搜索文本。默认值为 FALSE。这允许从 pdf 获取原始图像。默认值为 FALSE。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | 无法转换的对象的操作 |
| isTextVisible | boolean | 布尔值 |
| isOriginalImage | boolean | 布尔值 |

**退货：**
boolean - 运算结果
### convert(PdfFormatConversionOptions options) {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
```
public boolean convert(PdfFormatConversionOptions options)
```


使用指定的转换选项转换文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | [PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) | 一组用于转换 PDF 文档的选项 |

**退货：**
boolean - 运算结果
### convert(int fixup, OutputStream outputLog) {#convert-int-java.io.OutputStream-}
```
public final boolean convert(int fixup, OutputStream outputLog)
```


通过应用 Fixup 转换文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fixup | int | 修正类型。 |
| outputLog | java.io.OutputStream | 过程日志。 |

**退货：**
boolean - 运算结果。
### convert(int fixup, OutputStream outputLog, boolean onlyValidation, Object[] parameters) {#convert-int-java.io.OutputStream-boolean-java.lang.Object---}
```
public final boolean convert(int fixup, OutputStream outputLog, boolean onlyValidation, Object[] parameters)
```


通过应用 Fixup 转换文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fixup | int | 修正类型。 |
| outputLog | java.io.OutputStream | 过程日志。 |
| onlyValidation | boolean | 仅文件验证。 |
| parameters | java.lang.Object[] | 无法设置的 Fixup 属性。 |

**退货：**
boolean - 运算结果。
### convert(int fixup, String outputLog) {#convert-int-java.lang.String-}
```
public boolean convert(int fixup, String outputLog)
```


通过应用 Fixup 转换文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fixup | int | 修正类型。 |
| outputLog | java.lang.String | 过程日志。 |

**退货：**
boolean - 运算结果。
### convert(int fixup, String outputLog, boolean onlyValidation, Object[] parameters) {#convert-int-java.lang.String-boolean-java.lang.Object---}
```
public boolean convert(int fixup, String outputLog, boolean onlyValidation, Object[] parameters)
```


通过应用 Fixup 转换文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fixup | int | 修正类型。 |
| outputLog | java.lang.String | 过程日志。 |
| onlyValidation | boolean | 仅文件验证。 |
| parameters | java.lang.Object[] | 无法设置的 Fixup 属性。 |

**退货：**
boolean - 运算结果。
### convert(InputStream srcStream, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions) {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public static void convert(InputStream srcStream, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions)
```


将源格式的流转换为目标格式的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | 源流。 |
| loadOptions | [LoadOptions](../../com.aspose.pdf/loadoptions) | 源流格式。 |
| dstStream | java.io.OutputStream | 目标流。 |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | 目标文件格式。 |

### convert(InputStream srcStream, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions) {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public static void convert(InputStream srcStream, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions)
```


将源格式的流转换为目标格式的目标文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | 源流。 |
| loadOptions | [LoadOptions](../../com.aspose.pdf/loadoptions) | 源流格式。 |
| dstFileName | java.lang.String | 目标文件名。 |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | 目标文件格式。 |

### convert(OutputStream outputLogStream, PdfFormat format, int action) {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-}
```
public boolean convert(OutputStream outputLogStream, PdfFormat format, int action)
```


转换文档并将错误保存到指定的流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | 将存储评论的流。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PDF 格式。 |
| action | int | 无法转换的对象的操作 |

**退货：**
boolean - 布尔值
### convert(OutputStream outputLogStream, PdfFormat format, int action, int transparencyAction) {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-int-}
```
public final boolean convert(OutputStream outputLogStream, PdfFormat format, int action, int transparencyAction)
```


转换文档并将错误保存到指定文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | 将存储评论的流。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | pdf 格式。 |
| action | int | 无法转换的对象的操作 |
| transparencyAction | int | 图像蒙版对象的操作 |

**退货：**
boolean - 运算结果
### convert(String srcFileName, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions) {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public static void convert(String srcFileName, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions)
```


将源格式的源文件转换为目标格式的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | java.lang.String | 源文件名。 |
| loadOptions | [LoadOptions](../../com.aspose.pdf/loadoptions) | 源文件格式。 |
| dstStream | java.io.OutputStream | 目标流。 |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | 目标流格式。 |

### convert(String srcFileName, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions) {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public static void convert(String srcFileName, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions)
```


将源格式的源文件转换为目标格式的目标文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | java.lang.String | 源文件名。 |
| loadOptions | [LoadOptions](../../com.aspose.pdf/loadoptions) | 源文件格式。 |
| dstFileName | java.lang.String | 目标文件名。 |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | 目标文件格式。 |

### convert(String outputLogFileName, PdfFormat format, int action) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-}
```
public boolean convert(String outputLogFileName, PdfFormat format, int action)
```


转换文档并将错误保存到指定文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | java.lang.String | 将存储评论的文件路径。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PDF 格式。 |
| action | int | 无法转换的对象的操作 |

**退货：**
boolean - 布尔值
### convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-}
```
public boolean convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)
```


转换文档并将错误保存到指定文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | java.lang.String | 将存储评论的文件路径。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | pdf 格式。 |
| action | int | 无法转换的对象的操作 |
| transparencyAction | int | 图像蒙版对象的操作 |

**退货：**
boolean - 运算结果
### convertInternal(System.IO.Stream outputLogStream, PdfFormat format, int action) {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-}
```
public boolean convertInternal(System.IO.Stream outputLogStream, PdfFormat format, int action)
```


转换文档并将错误保存到指定的流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | com.aspose.ms.System.IO.Stream | 将存储评论的流。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PDF 格式。 |
| action | int | hocr 识别的回调过程。 |

**退货：**
boolean - 布尔值
### convertPageToPNGMemoryStream(Page page) {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
```
public byte[] convertPageToPNGMemoryStream(Page page)
```


为 DSR、OMR、OCR 图像流将页面转换为 PNG。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要转换的页面对象。 |

**退货：**
字节[- 以字节为单位的图像流[大批。
### convertWithSkippingErrors(Document.CallBackGetHocr callback) {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-}
```
public boolean convertWithSkippingErrors(Document.CallBackGetHocr callback)
```


将文档转换为可搜索文档并跳过无法转换的 hochr 错误。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | hocr 识别的回调过程。 |

**退货：**
boolean - 布尔值
### decrypt() {#decrypt--}
```
public void decrypt()
```


解密文档。然后调用 Save 以获得文档的解密版本。

### dispose() {#dispose--}
```
public void dispose()
```


关闭此文档使用的所有资源。

此方法已过时，请改用 close() 。

### encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-}
```
public void encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)
```


加密文档。调用然后保存以获取文档的加密版本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | java.lang.String | 用户密码。 |
| ownerPassword | java.lang.String | 所有者密码。 |
| privileges | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 文档权限，详见权限。 |
| cryptoAlgorithm | int | 密码算法，详见 CryptoAlgorithm。 |
| usePdf20 | boolean | 支持修订版 6（扩展 8）。 |

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


加密文档。调用然后保存以获取文档的加密版本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | java.lang.String | 用户密码。 |
| ownerPassword | java.lang.String | 所有者密码。 |
| permissions | int | 文档权限，详见权限。 |
| cryptoAlgorithm | int | 密码算法，详见 CryptoAlgorithm。 |

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-int-int-boolean-}
```
public void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)
```


加密文档。调用然后保存以获取文档的加密版本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | java.lang.String | 用户密码。 |
| ownerPassword | java.lang.String | 所有者密码。 |
| permissions | int | 文档权限，详见权限。 |
| cryptoAlgorithm | int | 密码算法，详见 CryptoAlgorithm。 |
| usePdf20 | boolean | 支持修订版 6（扩展 8）。 |

### endOperation() {#endOperation--}
```
public static void endOperation()
```




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
### exportAnnotationsToXfdf(OutputStream output) {#exportAnnotationsToXfdf-java.io.OutputStream-}
```
public final void exportAnnotationsToXfdf(OutputStream output)
```


将所有文档注释导出到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | java.io.OutputStream | 存储 XFDF 的流。 |

### exportAnnotationsToXfdf(String fileName) {#exportAnnotationsToXfdf-java.lang.String-}
```
public void exportAnnotationsToXfdf(String fileName)
```


将所有文档注释导出到 XFDF 文件

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | XFDF 文件名 |

### flatten() {#flatten--}
```
public void flatten()
```


从文档中删除所有字段并改为放置它们的值。

### flatten(Form.FlattenSettings flattenSettings) {#flatten-com.aspose.pdf.Form.FlattenSettings-}
```
public void flatten(Form.FlattenSettings flattenSettings)
```


从文档中删除所有字段并改为放置它们的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| flattenSettings | [FlattenSettings](../../com.aspose.pdf/flattensettings) | 展平过程的设置。 |

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


清除内存

### getAbsentFontHandler() {#getAbsentFontHandler--}
```
public ADocument.AbsentFontHandler getAbsentFontHandler()
```


处理文档时有关丢失字体的通知。

**退货：**
com.aspose.pdf.ADocument.AbsentFontHandler - ADocument.AbsentFontHandler 实例
### getActions() {#getActions--}
```
public DocumentActionCollection getActions()
```


获取文档操作。此属性是 DocumentActions 类的实例，它允许获取/设置 BeforClosing、BeforSaving 等操作。

**退货：**
[DocumentActionCollection](../../com.aspose.pdf/documentactioncollection) - DocumentActionCollection 对象

--------------------

```
//本例演示了如何获取文件打开后的动作：

 Document document = new Document("PdfWithOpenAction.pdf");
 DocumentActionCollection actions = document.getActions();
 PdfAction afterSavingAction = actions.getAfterSaving();
```
### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```


允许合并页面内容以优化文档大小。如果使用，则不同但重复的页面可能引用相同的内容对象。请注意，此模式可能会导致其他页面更改时更改页面内容等副作用。

**退货：**
boolean - value 布尔值
### getBackground() {#getBackground--}
```
public Color getBackground()
```


获取文档的背景颜色。

**退货：**
[Color](../../java.awt/color) 颜色对象
### getCatalogValue(String key) {#getCatalogValue-java.lang.String-}
```
public Object getCatalogValue(String key)
```


从目录字典返回项目值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 项目的关键。 |

**退货：**
java.lang.Object - 项目值 - 如果成功找到键；否则为空。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCollection() {#getCollection--}
```
public Collection getCollection()
```


获取文档集合。

**退货：**
[Collection](../../com.aspose.pdf/collection) - 集合对象
### getCryptoAlgorithm() {#getCryptoAlgorithm--}
```
public int getCryptoAlgorithm()
```


如果文档已加密，则获取安全设置。如果文档未加密，则在 .net 1.1 中将引发相应的异常，或者对于其他 .net 版本，CryptoAlgorithm 将为 null。

**退货：**
int - CryptoAlgorithm 元素
### getDefaultCopier() {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```


将用于复印页面的复印机返回到此文档。

**退货：**
[Copier](../../com.aspose.pdf/copier) 复印机对象
### getDestinations() {#getDestinations--}
```
public DestinationCollection getDestinations()
```


获取目的地的集合。

**退货：**
[DestinationCollection](../../com.aspose.pdf/destinationcollection) DestinationCollection 元素
### getDirection() {#getDirection--}
```
public int getDirection()
```


获取文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。

**退货：**
int - 方向元素
### getDuplex() {#getDuplex--}
```
public int getDuplex()
```


获取或设置从打印对话框打印文件时要使用的打印双面模式处理选项。

**退货：**
int - PrintDuplex 元素
### getEmbedStandardFonts() {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```


声明文档必须嵌入所有标准 Type1 字体的属性，该字体的标志 IsEmbedded 设置为 true。所有 PDF 字体都可以简单地通过将标志 IsEmbedded 设置为 true 来嵌入到文档中，但 PDF 标准 Type1 字体是此规则的一个例外。标准 Type1 字体嵌入需要很多时间，因此要嵌入这些字体，不仅需要将指定字体的标志 IsEmbedded 设置为 true，还需要在文档级别设置一个附加标志 - EmbedStandardFonts = true;此属性只能为所有字体设置一次。默认为假。

**退货：**
布尔值
### getEmbeddedFiles() {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```


获取嵌入文档的文件集合。

**退货：**
[EmbeddedFileCollection](../../com.aspose.pdf/embeddedfilecollection) - EmbeddedFileCollection 对象
### getEnableSignatureSanitization() {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```


获取或设置标志以管理签名字段清理。默认启用。

**退货：**
boolean - 布尔值
### getEngineDoc() {#getEngineDoc--}
```
public IPdfDocument getEngineDoc()
```


用于访问内部文档结构的 IPdfDocument 实例。仅限内部

**退货：**
[IPdfDocument](../../com.aspose.pdf.engine/ipdfdocument) IPdfDocument 对象
### getFileName() {#getFileName--}
```
public String getFileName()
```


生成此文档的 PDF 文件的名称

**退货：**
java.lang.String - 字符串对象
### getFontUtilities() {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```


IDocumentFontUtilities 实例

**退货：**
[IDocumentFontUtilities](../../com.aspose.pdf/idocumentfontutilities) IDocumentFontUtilities 实例
### getForm() {#getForm--}
```
public Form getForm()
```


获取文档的 Acro 形式。

**退货：**
[Form](../../com.aspose.pdf/form) 表单对象
### getId() {#getId--}
```
public Id getId()
```


获取ID。

**退货：**
[Id](../../com.aspose.pdf/id) Id 对象
### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```


获取或设置忽略源文件中错误的标志。当源文档中的页面复制到目标文档中时，如果源文件中的某些对象已损坏，则复制过程将停止，但此标志为 false。例子： dest.Pages.Add(src.Pages);如果此标志设置为 true，则损坏的对象将被替换为空值。默认情况下：真。

**退货：**
boolean - 布尔值
### getInfo() {#getInfo--}
```
public DocumentInfo getInfo()
```


获取文档信息。

**退货：**
[DocumentInfo](../../com.aspose.pdf/documentinfo) - 文档信息对象
### getJavaScript() {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```


文档级别的 JavaScript 集合。

**退货：**
[JavaScriptCollection](../../com.aspose.pdf/javascriptcollection) JavaScriptCollection 对象
### getLogicalStructure() {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```


获取文档的逻辑结构。

**退货：**
[RootElement](../../com.aspose.pdf/rootelement) RootElement 对象
### getMetadata() {#getMetadata--}
```
public Metadata getMetadata()
```


文档元数据。 （PDF 文档可能包含一般信息，例如文档的标题、作者以及创建和修改日期。此类关于文档的全局信息（相对于其内容或结构）称为元数据，旨在帮助编目和搜索对于外部数据库中的文档。）

**退货：**
[Metadata](../../com.aspose.pdf/metadata) - 元数据对象
### getMetadataStream() {#getMetadataStream--}
```
public IPdfStreamAccessor getMetadataStream()
```


返回原始元数据流

**退货：**
[IPdfStreamAccessor](../../com.aspose.pdf.engine.data.types/ipdfstreamaccessor) IPdfStreamAccessor 对象
### getNamedDestinations() {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```


文档中命名目标的集合。

**退货：**
[NamedDestinationCollection](../../com.aspose.pdf.nameddestinations/nameddestinationcollection)
### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public int getNonFullScreenPageMode()
```


获取页面模式，指定在退出全屏模式时如何显示文档。

**退货：**
int - PageMode 元素
### getObjectById(String id) {#getObjectById-java.lang.String-}
```
public Object getObjectById(String id)
```


获取文档中具有指定 ID 的对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 对象标识。 |

**退货：**
java.lang.Object - 具有指定 id 的对象。如果未找到 id，则为空。
### getOpenAction() {#getOpenAction--}
```
public IAppointment getOpenAction()
```


获取打开文档时执行的操作。

--------------------

```
//示例演示如何获取 CenterWindow 标志：

 Document document = new Document("sample.pdf");
 IAppointment value = document.getOpenAction();
```

**退货：**
[IAppointment](../../com.aspose.pdf/iappointment)-IAppointment 对象
### getOptimizeSize() {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```


获取优化标志。将页面添加到文档时，如果设置了此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。这允许减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。默认值：假。

**退货：**
boolean - 布尔值
### getOutlines() {#getOutlines--}
```
public OutlineCollection getOutlines()
```


获取文档大纲。

**退货：**
[OutlineCollection](../../com.aspose.pdf/outlinecollection) - OutlineCollection 对象
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


获取页面信息。（仅适用于生成器）

**退货：**
[PageInfo](../../com.aspose.pdf/pageinfo) - 页面信息。
### getPageLabels() {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```


获取文档中的页面标签。

**退货：**
[PageLabelCollection](../../com.aspose.pdf/pagelabelcollection) - PageLabelCollection 对象
### getPageLayout() {#getPageLayout--}
```
public int getPageLayout()
```


获取打开文档时应使用的页面布局。

**退货：**
int - PageLayout 元素
### getPageMode() {#getPageMode--}
```
public int getPageMode()
```


获取页面模式，指定打开文档时应如何显示。

**退货：**
int - PageMode 元素
### getPages() {#getPages--}
```
public PageCollection getPages()
```


获取文档页面的集合。请注意，页面在集合中从 1 开始编号。

**退货：**
[PageCollection](../../com.aspose.pdf/pagecollection) - PageCollection 对象

--------------------

```
//下面的示例演示了如何使用文档页面进行操作：
//如何获取页数，如何获取文档起始页的矩形。

 Document document = new Document("sample.pdf");
 PageCollection  pages = document.getPages();
 System.out.println("Document contains " + pages.size());
 Page page = pages.get_Item(1);
 Rectangle rect = page.getRect();
```
### getPdfFormat() {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```


获取pdfa格式

**退货：**
[PdfFormat](../../com.aspose.pdf/pdfformat) - PdfFormat 元素
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


获取文档的权限。

**退货：**
int - 整数值
### getTaggedContent() {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```


获取对 TaggedPdf 内容的访问权限。

该示例演示了如何使用标记内容创建带有标题、段落和图像的新文档。

```
	//创建新文档
     Document document = new Document();

     //获取标记的内容
     ITaggedContent taggedContent = document.getTaggedContent();

     //设置文档语言
     taggedContent.setLanguage("en-US");

     //设置PDF文档的标题
     taggedContent.setTitle("Example document");

     //创建和添加部分
     SectElement sect = taggedContent.createSectElement();
     taggedContent.getRootElement().appendChild(sect);

     //创建标题
     HeaderElement h1 = taggedContent.createHeaderElement(1);
     h1.setText("The Header");
     sect.appendChild(h1);

     //创建段落
     ParagraphElement p = taggedContent.createParagraphElement();
     p.setTag("Paragraph");
     p.setText("The text of paragraph.");
     sect.appendChild(p);
     //创建插图
     IllustrationElement figure1 = taggedContent.createFigureElement();
     sect.appendChild(figure1);
     figure1.setAlternativeText("Figure 1");
     figure1.setTitle("Image 1");
     figure1.setTag("Fig");
     figure1.setImage("path/of/image.jpg");
     //保存文件
     document.save("example.pdf");
```

**退货：**
[ITaggedContent](../../com.aspose.pdf.tagged/itaggedcontent) ITaggedContent 实例
### getVersion() {#getVersion--}
```
public String getVersion()
```


从 Pdf 文件头获取 Pdf 的版本。

**退货：**
java.lang.String - 字符串值
### getXmpMetadata(OutputStream output) {#getXmpMetadata-java.io.OutputStream-}
```
public void getXmpMetadata(OutputStream output)
```


从文档中获取 XMP 元数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | java.io.OutputStream | 将存储元数据的流。 |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### importAnnotationsFromXfdf(InputStream stream) {#importAnnotationsFromXfdf-java.io.InputStream-}
```
public final void importAnnotationsFromXfdf(InputStream stream)
```


将注释从流导入文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 流包含 XFDF 数据。 |

### importAnnotationsFromXfdf(String fileName) {#importAnnotationsFromXfdf-java.lang.String-}
```
public void importAnnotationsFromXfdf(String fileName)
```


将注释从 XFDF 文件导入文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | XFDF 文件名 |

### isAbsentFontTryToSubstitute() {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```


通知丢失字体替换的标志。

**退货：**
布尔值
### isCenterWindow() {#isCenterWindow--}
```
public boolean isCenterWindow()
```


获取指定文档窗口的位置是否将在屏幕上居中的标志。

**退货：**
boolean - 布尔值

--------------------

```
//示例演示如何获取 CenterWindow 标志：

 Document document = new Document("sample.pdf");
 boolean value = document.isCenterWindow();
```
### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```


如果该字体的许可证禁止这些操作，则无法执行该字体的许多操作。例如，如果许可规则禁止嵌入某些字体，则无法将其嵌入到 PDF 文档中。此标志用于禁用当前 PDF 文档中所有字体的任何许可限制。使用此标志时要小心。当它被设置时，意味着设置这个标志的人，对自己可能违反许可/法律的行为承担全部责任。所以他自己承担风险。强烈建议仅当您完全确信自己没有违反版权法时才使用此标志。默认为假。

**退货：**
boolean - 布尔值默认为 false。
### isDisplayDocTitle() {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```


获取指定文档窗口标题栏是否应显示文档标题的标志。

**退货：**
boolean - 布尔值

--------------------

```
//示例演示如何获取 DisplayDocTitle 标志：

 Document document = new Document("sample.pdf");
 boolean value = document.isDisplayDocTitle();
```
### isEnableObjectUnload() {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```


获取或设置使文档能够从内存中部分卸载的标志。这允许减少内存使用，但可能会对性能产生负面影响。

**退货：**
boolean - 布尔值
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


获取文档的加密状态。如果文档已加密，则为真。

**退货：**
boolean - 布尔值
### isFitWindow() {#isFitWindow--}
```
public boolean isFitWindow()
```


获取指定是否必须调整文档窗口大小以适合显示的第一个页面的标志。

**退货：**
boolean - 布尔值

--------------------

```
Example demonstrates how to get FitWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isFitWindow();
```
### isHandleSignatureChange() {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```


如果文档将保存更改并具有签名，则抛出异常

**退货：**
boolean - 布尔值
### isHideMenubar() {#isHideMenubar--}
```
public boolean isHideMenubar()
```


获取指定在文档处于活动状态时是否应隐藏菜单栏的标志。

**退货：**
boolean - 布尔值

--------------------

```
//示例演示如何获取 HideMenubar 标志：

 Document document = new Document("sample.pdf");
 boolean value = document.isHideMenubar();
```
### isHideToolBar() {#isHideToolBar--}
```
public boolean isHideToolBar()
```


获取指定在文档处于活动状态时是否应隐藏工具栏的标志。

**退货：**
boolean - 布尔值

--------------------

```
//示例演示如何获取 HideToolBar 标志：

 Document document = new Document("sample.pdf");
 boolean value = document.isHideToolBar();
```
### isHideWindowUI() {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```


获取指定在文档处于活动状态时是否应隐藏用户界面元素的标志。

**退货：**
boolean - 布尔值

--------------------

```
//示例演示如何获取 HideWindowUI 标志：

 Document document = new Document("sample.pdf");
 boolean value = document.isHideWindowUI();
```
### isLicensed() {#isLicensed--}
```
public static boolean isLicensed()
```


获取系统的许可状态。如果系统在许可模式下工作，则返回 true，否则返回 false。

**退货：**
boolean - 布尔值
### isLinearized() {#isLinearized--}
```
public boolean isLinearized()
```


获取一个值，该值指示文档是否已线性化。

**退货：**
boolean - 布尔值
### isManualDisposeEnabled() {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```


默认方法保存关闭内部流并释放内存资源。如果启用此 ManualDispose 参数，我们可以在方法保存后执行一些操作并继续处理文档。

**退货：**
boolean - 布尔值。 （默认值 == 假）
### isPdfUaCompliant() {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```


获取符合 pdfua 标准的文档。

**退货：**
boolean - 布尔值
### isPdfaCompliant() {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```


获取符合 pdfa 标准的文档。

**退货：**
boolean - 布尔值
### isSkippedPdfaCompliantValidationBeforeSave() {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```


默认情况下，如果某些规则被破坏，pdfa 验证过程是更新或删除 pdfa 兼容数据所必需的。但是为了快速保存过程是可以跳过的。

**退货：**
boolean - 布尔值
### isXrefGapsAllowed() {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```


获取或设置文档 pdfa 兼容。

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




### optimize() {#optimize--}
```
public void optimize()
```


线性化文档以便 - 尽快打开第一页； - 尽快显示下一页或通过链接进入下一页； - 当页面数据通过慢速通道传送时，在页面到达时逐步显示页面（首先显示最有用的数据）； - 允许甚至在接收和显示整个页面之前执行用户交互，例如跟随链接。调用此方法实际上并不保存文档。反之只准备有优化结构的文档，调用Save 即可得到优化后的文档。

### optimizeResources() {#optimizeResources--}
```
public void optimizeResources()
```


优化文档中的资源： 1. 去除文档页面中不用的资源； 2. 等量资源合并为一个对象； 3. 删除未使用的对象。

### optimizeResources(OptimizationOptions strategy) {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
```
public void optimizeResources(OptimizationOptions strategy)
```


根据定义的优化策略优化文档中的资源。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| strategy | [OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions) | 优化策略。 |

### preSave(PageCollection pages, SaveOptions saveOptions) {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
```
public static void preSave(PageCollection pages, SaveOptions saveOptions)
```


内部方法

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pages | [PageCollection](../../com.aspose.pdf/pagecollection) | PageCollection 实例 |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项实例 |

### processParagraphs() {#processParagraphs--}
```
public void processParagraphs()
```


将文档存储到流中。

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


从文档中删除元数据。

### removePdfUaCompliance() {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```


从文档中删除 pdfUa 合规性

### removePdfaCompliance() {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```


从文档中删除 pdfa 合规性

### repair() {#repair--}
```
public void repair()
```


修复损坏的文档。

### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


恢复文档更新

### save() {#save--}
```
public void save()
```


增量保存文档（即使用增量更新技术）。

--------------------

为了增量保存文档，我们应该打开文档文件进行写入。因此，Document 不得使用 InputStream 进行初始化，而必须使用文件路径进行初始化，如下一个代码片段所示： 

```
Document doc = new Document("document.pdf"); 
//进行一些更改并逐步保存文档
doc.save();
```

如果文档是用 InputStream 初始化的，写入 InputStream 是不可能的，所以我们建议使用单独的方法“save”来保存文档或“saveIncrementally”来增量保存文档。

### save(System.IO.Stream output) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream output)
```


将文档存储到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | 存储文档外壳的流。 |

### save(SaveOptions options) {#save-com.aspose.pdf.SaveOptions-}
```
public final void save(SaveOptions options)
```


使用保存选项保存文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项。 |

### save(OutputStream output) {#save-java.io.OutputStream-}
```
public void save(OutputStream output)
```


将文档存储到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | java.io.OutputStream | 存储文档外壳的流。 |

### save(OutputStream outputStream, SaveFormat format) {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
```
public void save(OutputStream outputStream, SaveFormat format)
```


使用新名称和文件格式保存文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 将存储文档的流。 |
| format | [SaveFormat](../../com.aspose.pdf/saveformat) | 格式选项。 |

### save(OutputStream outputStream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public void save(OutputStream outputStream, SaveOptions options)
```


使用保存选项将文档保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 将存储文档的流。 |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项。 |

### save(String outputFileName) {#save-java.lang.String-}
```
public void save(String outputFileName)
```


将文档保存到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | java.lang.String | 将存储文档的文件路径。 |

### save(String outputFileName, SaveFormat format) {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
```
public void save(String outputFileName, SaveFormat format)
```


使用新名称和文件格式保存文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | java.lang.String | 将存储文档的文件路径。 |
| format | [SaveFormat](../../com.aspose.pdf/saveformat) | 格式选项。 |

### save(String outputFileName, SaveOptions options) {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public void save(String outputFileName, SaveOptions options)
```


使用设置其保存选项的新名称保存文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | java.lang.String | 将存储文档的文件路径。 |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项。 |

### saveIncrementally(System.IO.Stream output) {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
```
public void saveIncrementally(System.IO.Stream output)
```


将 PDF 文档增量保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | 输出流对象 |

### saveIncrementally(OutputStream output) {#saveIncrementally-java.io.OutputStream-}
```
public void saveIncrementally(OutputStream output)
```


将 PDF 文档增量保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | java.io.OutputStream | 输出流对象 |

### saveIncrementally(String outputFileName) {#saveIncrementally-java.lang.String-}
```
public void saveIncrementally(String outputFileName)
```


将 PDF 文档增量保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | java.lang.String | 输出流对象 |

### saveXml(String file) {#saveXml-java.lang.String-}
```
public void saveXml(String file)
```


将文档保存为 XML。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 文档模型xml文件 |

### sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
```
public void sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)
```


将文档的某些页面发送到文档设备进行处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | 用于处理文档的文档设备。 |
| fromPage | int | 处理的第一页。 |
| toPage | int | 处理的最后一页。 |
| output | java.io.OutputStream | 输出流包含给定设备处理文档页面的结果。 |

### sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
```
public void sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)
```


将整个文档发送到文档设备进行处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | 用于处理文档的文档设备。 |
| fromPage | int | 处理的第一页。 |
| toPage | int | 处理的最后一页。 |
| outputFileName | java.lang.String | 带有处理结果的输出文件名。 |

### sendTo(DocumentDevice device, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
```
public void sendTo(DocumentDevice device, OutputStream output)
```


将整个文档发送到文档设备进行处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | 用于处理文档的文档设备。 |
| output | java.io.OutputStream | 输出流包含给定设备的文档处理结果。 |

### sendTo(DocumentDevice device, String outputFileName) {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
```
public void sendTo(DocumentDevice device, String outputFileName)
```


将整个文档发送到文档设备进行处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | 用于处理文档的文档设备。 |
| outputFileName | java.lang.String | 带有处理结果的输出文件名。 |

### setAbsentFontHandler(ADocument.AbsentFontHandler absentFontHandler) {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
```
public void setAbsentFontHandler(ADocument.AbsentFontHandler absentFontHandler)
```


处理文档时有关丢失字体的通知。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| absentFontHandler | com.aspose.pdf.ADocument.AbsentFontHandler | ADocument.AbsentFontHandler 实例 |

### setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute) {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```


在缺少字体的情况下，设置程序确定字体的设置标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| setAbsentFontTryToSubstitute | boolean |  |

### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```


允许合并页面内容以优化文档大小。如果使用，则不同但重复的页面可能引用相同的内容对象。请注意，此模式可能会导致其他页面更改时更改页面内容等副作用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public void setBackground(Color value)
```


设置文档的背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color | 颜色对象 |

### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```


设置标志指定文档窗口的位置是否将在屏幕上居中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCollection(Collection value) {#setCollection-com.aspose.pdf.Collection-}
```
public void setCollection(Collection value)
```


设置文档集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Collection](../../com.aspose.pdf/collection) | 集合对象 |

### setConvertMetadataAndCatalogOnly(boolean value) {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```


获取 pdf/ua 转换器的转换参数（如果设置为 true，则仅转换元数据和文档目录）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setDirection(int value) {#setDirection-int-}
```
public void setDirection(int value)
```


设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setDisableFontLicenseVerifications(boolean value) {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```


如果该字体的许可证禁止这些操作，则无法执行该字体的许多操作。例如，如果许可规则禁止嵌入某些字体，则无法将其嵌入到 PDF 文档中。此标志用于禁用当前 PDF 文档中所有字体的任何许可限制。使用此标志时要小心。当它被设置时，意味着设置这个标志的人，对自己可能违反许可/法律的行为承担全部责任。所以他自己承担风险。强烈建议仅当您完全确信自己没有违反版权法时才使用此标志。默认为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 默认为 false。 |

### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```


设置标志指定文档的窗口标题栏是否应显示文档标题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setDuplex(int value) {#setDuplex-int-}
```
public void setDuplex(int value)
```


获取或设置从打印对话框打印文件时要使用的打印双面模式处理选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PrintDuplex 元素 |

### setEmbedStandardFonts(boolean value) {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```


声明文档必须嵌入所有标准 Type1 字体的属性，该字体的标志 IsEmbedded 设置为 true。所有 PDF 字体都可以简单地通过将标志 IsEmbedded 设置为 true 来嵌入到文档中，但 PDF 标准 Type1 字体是此规则的一个例外。标准 Type1 字体嵌入需要很多时间，因此要嵌入这些字体，不仅需要将指定字体的标志 IsEmbedded 设置为 true，还需要在文档级别设置一个附加标志 - EmbedStandardFonts = true;此属性只能为所有字体设置一次。默认为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setEnableObjectUnload(boolean value) {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```


获取或设置使文档能够从内存中部分卸载的标志。这允许减少内存使用，但可能会对性能产生负面影响。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setEnableSignatureSanitization(boolean value) {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```


获取或设置标志以管理签名字段清理。默认启用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```


设置标志，指定是否必须调整文档窗口的大小以适合显示的第一个页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHandleSignatureChange(boolean value) {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```


如果文档将保存更改并具有签名，则抛出异常

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHideMenubar(boolean value) {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```


设置标志，指定当文档处于活动状态时是否应隐藏菜单栏。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```


设置标志，指定在文档处于活动状态时工具栏是否应隐藏。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```


设置标志，指定在文档处于活动状态时是否应隐藏用户界面元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```


获取或设置忽略源文件中错误的标志。当源文档中的页面复制到目标文档中时，如果源文件中的某些对象已损坏，则复制过程将停止，但此标志为 false。例子： dest.Pages.Add(src.Pages);如果此标志设置为 true，则损坏的对象将被替换为空值。默认情况下：真。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLayersAdded(boolean value) {#setLayersAdded-boolean-}
```
public void setLayersAdded(boolean value)
```


设置 LayersAdded 值

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setLinearized(boolean value) {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```


设置一个值，指示文档是否线性化。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setManualDisposeEnabled(boolean manualDisposeEnabled) {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```


默认方法 save 关闭内部流并释放内存资源。如果启用此 ManualDispose 参数，我们可以在调用方法保存后执行一些操作并继续处理文档。但强烈建议在不再需要 Document 实例时调用 dispose 方法。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| manualDisposeEnabled | boolean | 布尔值。 （默认值 == 假） |

### setNonFullScreenPageMode(int value) {#setNonFullScreenPageMode-int-}
```
public void setNonFullScreenPageMode(int value)
```


设置页面模式，指定在退出全屏模式时如何显示文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setOpenAction(IAppointment value) {#setOpenAction-com.aspose.pdf.IAppointment-}
```
public void setOpenAction(IAppointment value)
```


设置在文档打开时执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | 预约值 |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```


设置优化标志。将页面添加到文档时，如果设置了此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。这允许减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。默认值：假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


设置页面信息。（仅适用于生成器）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | PageInfo 对象 |

### setPageLayout(int value) {#setPageLayout-int-}
```
public void setPageLayout(int value)
```


设置打开文档时应使用的页面布局。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPageMode(int pageMode) {#setPageMode-int-}
```
public void setPageMode(int pageMode)
```


设置页面模式，指定打开文档时应如何显示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageMode | int | 整数值 |

### setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave) {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```


默认情况下，如果某些规则被破坏，pdfa 验证过程是更新或删除 pdfa 所必需的。但是为了快速保存过程是可以跳过的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave | boolean | 布尔值 |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public final void setTitle(String title)
```


为 Pdf 文档设置标题

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| title | java.lang.String | 文档的标题 |

### setXmpMetadata(InputStream stream) {#setXmpMetadata-java.io.InputStream-}
```
public void setXmpMetadata(InputStream stream)
```


设置文档的 XMP 元数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 XMP 元数据的流。 |

### setXrefGapsAllowed(boolean value) {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```


获取或设置文档 pdfa 兼容。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### startOperation() {#startOperation--}
```
public static void startOperation()
```




### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


禁止更新所有页面的内容数据内容不会更新，直到调用 ResumeUpdate

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### updatePages() {#updatePages--}
```
public void updatePages()
```


更新页面

### validate(PdfFormatConversionOptions options) {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
```
public boolean validate(PdfFormatConversionOptions options)
```


将文档验证到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | [PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) | 一组用于转换 PDF 文档的选项 |

**退货：**
boolean - 运算结果
### validate(OutputStream outputLogStream, PdfFormat format) {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
```
public boolean validate(OutputStream outputLogStream, PdfFormat format)
```


将文档验证到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | 将存储评论的流。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PDF 格式。 |

**退货：**
boolean - 布尔值
### validate(String outputLogFileName, PdfFormat format) {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
```
public boolean validate(String outputLogFileName, PdfFormat format)
```


将文档验证到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | java.lang.String | 将存储评论的文件路径。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat 元素。 |

**退货：**
布尔值
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
