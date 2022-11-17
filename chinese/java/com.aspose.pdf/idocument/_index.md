---
title: IDocument
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 PDF 文档的界面
type: docs
weight: 433
url: /zh/java/com.aspose.pdf/idocument/
---
**所有已实现的接口：**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IDocument extends System.IDisposable, Closeable
```

表示 PDF 文档的界面
## 方法

| 方法 | 描述 |
| --- | --- |
| [afterImport()](#afterImport--) | 枚举所有已注册的注释并为每个注释调用 AfterImport。 |
| [bindXml(InputStream stream)](#bindXml-java.io.InputStream-) | 将 xml 绑定到文档 |
| [bindXml(String file)](#bindXml-java.lang.String-) | 将 xml 绑定到文档 |
| [bindXml(String xmlFile, String xslFile)](#bindXml-java.lang.String-java.lang.String-) | 将 xml/xsl 绑定到文档 |
| [changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | 更改文档密码。 |
| [check(boolean doRepair)](#check-boolean-) | 验证文档。 |
| [close()](#close--) | 关闭此文档使用的所有资源。 |
| [convert(Document.CallBackGetHocr callback)](#convert-com.aspose.pdf.Document.CallBackGetHocr-) | 将文档转换为可搜索的文档。 |
| [convert(Document.CallBackGetHocr callback, boolean isTestVisible)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-) | 转换文档并将错误保存到指定文件中。 |
| [convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-) | 转换文档并将错误保存到指定文件中。 |
| [convert(PdfFormatConversionOptions options)](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | 使用指定的转换选项转换文档 |
| [convert(OutputStream outputLogStream, PdfFormat format, int action)](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) |  |
| [convert(String outputLogFileName, PdfFormat format, int action)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-) | 转换文档并将错误保存到指定文件中。 |
| [convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | 转换文档并将错误保存到指定文件中。 |
| [convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none)](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-) | 内部方法 |
| [convertWithSkippingErrors(Document.CallBackGetHocr callback)](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-) | 将文档转换为可搜索文档并跳过无法转换的 hochr 错误。 |
| [decrypt()](#decrypt--) | 解密文档。 |
| [dispose()](#dispose--) | 关闭此文档使用的所有资源。 |
| [encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-) | 加密文档。 |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | 加密文档。 |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-int-int-boolean-) | 加密文档。 |
| [exportAnnotationsToXfdf(String fileName)](#exportAnnotationsToXfdf-java.lang.String-) | 将所有文档注释导出到 XFDF 文件 |
| [flatten()](#flatten--) | 从文档中删除所有字段并改为放置它们的值。 |
| [flatten(Form.FlattenSettings flattenSettings)](#flatten-com.aspose.pdf.Form.FlattenSettings-) | 从文档中删除所有字段并改为放置它们的值。 |
| [freeMemory()](#freeMemory--) | 清除内存 |
| [getActions()](#getActions--) | 获取文档操作。 |
| [getBackground()](#getBackground--) | 获取文档的背景颜色。 |
| [getCatalogValue(String key)](#getCatalogValue-java.lang.String-) | 从目录字典返回项目值。 |
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
| [getForm()](#getForm--) | 获取文档的 Acro 形式。 |
| [getId()](#getId--) | 获取ID。 |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | 获取或设置忽略源文件中错误的标志。 |
| [getInfo()](#getInfo--) | 获取文档信息。 |
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
| [getPdfFormat()](#getPdfFormat--) |  |
| [getPermissions()](#getPermissions--) | 获取文档的权限。 |
| [getVersion()](#getVersion--) | 从 Pdf 文件头获取 Pdf 的版本。 |
| [getXmpMetadata(OutputStream stream)](#getXmpMetadata-java.io.OutputStream-) | 从文档中获取 XMP 元数据。 |
| [importAnnotationsFromXfdf(String fileName)](#importAnnotationsFromXfdf-java.lang.String-) | 将注释从 XFDF 文件导入文档。 |
| [isAbsentFontTryToSubstitute()](#isAbsentFontTryToSubstitute--) | 处理文档时有关丢失字体的通知 |
| [isCenterWindow()](#isCenterWindow--) | 获取指定文档窗口的位置是否将在屏幕上居中的标志。 |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | 如果该字体的许可证禁止这些操作，则无法执行该字体的许多操作。 |
| [isDisplayDocTitle()](#isDisplayDocTitle--) | 获取指定文档窗口标题栏是否应显示文档标题的标志。 |
| [isEncrypted()](#isEncrypted--) | 获取文档的加密状态。 |
| [isFitWindow()](#isFitWindow--) | 获取指定是否必须调整文档窗口大小以适合显示的第一个页面的标志。 |
| [isHideMenubar()](#isHideMenubar--) | 获取指定在文档处于活动状态时是否应隐藏菜单栏的标志。 |
| [isHideToolBar()](#isHideToolBar--) | 获取指定在文档处于活动状态时是否应隐藏工具栏的标志。 |
| [isHideWindowUI()](#isHideWindowUI--) | 获取或设置标志，该标志指定当文档处于活动状态时是否应隐藏用户界面元素。 |
| [isLinearized()](#isLinearized--) | 获取或设置一个值，该值指示文档是否线性化。 |
| [isManualDisposeEnabled()](#isManualDisposeEnabled--) | 默认方法保存关闭内部流并释放内存资源。 |
| [isPdfUaCompliant()](#isPdfUaCompliant--) | 获取符合 pdfua 标准的文档。 |
| [isPdfaCompliant()](#isPdfaCompliant--) |  |
| [isXrefGapsAllowed()](#isXrefGapsAllowed--) | 获取或设置文档 pdfa 兼容。 |
| [optimize()](#optimize--) | 线性化文档以便 - 尽快打开第一页； - 尽快显示下一页或通过链接进入下一页； - 当页面数据通过慢速通道传送时，在页面到达时逐步显示页面（首先显示最有用的数据）； - 允许甚至在接收和显示整个页面之前执行用户交互，例如跟随链接。 |
| [optimizeResources()](#optimizeResources--) | 优化文档中的资源： 1。 |
| [optimizeResources(OptimizationOptions strategy)](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | 根据定义的优化策略优化文档中的资源。 |
| [processParagraphs()](#processParagraphs--) | 将文档存储到流中。 |
| [removeMetadata()](#removeMetadata--) | 从文档中删除元数据。 |
| [removePdfUaCompliance()](#removePdfUaCompliance--) | 从文档中删除 pdfUa 合规性 |
| [removePdfaCompliance()](#removePdfaCompliance--) | 从文档中删除 pdfa 合规性 |
| [repair()](#repair--) | 修复损坏的文档。 |
| [恢复更新()](#resumeUpdate--) | resumeUpdate |
| [save()](#save--) | 增量保存文档（即使用增量更新技术）。 |
| [save(OutputStream output)](#save-java.io.OutputStream-) | 将文档存储到流中。 |
| [save(OutputStream outputStream, SaveFormat format)](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | 保存文件 |
| [save(OutputStream outputStream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 使用设置其保存选项的新名称保存文档。 |
| [save(String outputFileName)](#save-java.lang.String-) | 将文档保存到指定的文件中。 |
| [save(String outputFileName, SaveOptions options)](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | 使用设置其保存选项的新名称保存文档。 |
| [saveIncrementally(System.IO.Stream output)](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | 将 PDF 文档增量保存到指定的流。 |
| [saveIncrementally(OutputStream output)](#saveIncrementally-java.io.OutputStream-) | 将 PDF 文档增量保存到指定的流。 |
| [saveIncrementally(String outputFileName)](#saveIncrementally-java.lang.String-) | 将 PDF 文档增量保存到指定的流。 |
| [saveXml(String file)](#saveXml-java.lang.String-) | 将文档保存为 XML。 |
| [sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | 将文档的某些页面发送到文档设备进行处理。 |
| [sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | 将整个文档发送到文档设备进行处理。 |
| [sendTo(DocumentDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | 将整个文档发送到文档设备进行处理。 |
| [sendTo(DocumentDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | 将整个文档发送到文档设备进行处理。 |
| [setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)](#setAbsentFontTryToSubstitute-boolean-) | 在没有字体的情况下，设置程序确定字体的设置标志。 |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | 设置文档的背景颜色。 |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | 设置标志指定文档窗口的位置是否将在屏幕上居中。 |
| [setCollection(Collection value)](#setCollection-com.aspose.pdf.Collection-) | 设置文档集合。 |
| [setConvertMetadataAndCatalogOnly(boolean value)](#setConvertMetadataAndCatalogOnly-boolean-) | 获取 pdf/ua 转换器的转换参数（如果设置为 true，则仅转换元数据和文档目录） |
| [setDirection(int value)](#setDirection-int-) | 设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [setDisableFontLicenseVerifications(boolean value)](#setDisableFontLicenseVerifications-boolean-) | 如果该字体的许可证禁止这些操作，则无法执行该字体的许多操作。 |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | 设置标志指定文档的窗口标题栏是否应显示文档标题。 |
| [setDuplex(int value)](#setDuplex-int-) | 获取或设置从打印对话框打印文件时要使用的打印双面模式处理选项。 |
| [setEmbedStandardFonts(boolean value)](#setEmbedStandardFonts-boolean-) | 声明文档必须嵌入所有标准 Type1 字体的属性，该字体的标志 IsEmbedded 设置为 true。 |
| [setEnableSignatureSanitization(boolean value)](#setEnableSignatureSanitization-boolean-) | 获取或设置标志以管理签名字段清理。 |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | 设置标志，指定是否必须调整文档窗口的大小以适合显示的第一个页面。 |
| [setHideMenubar(boolean value)](#setHideMenubar-boolean-) | 设置标志，指定当文档处于活动状态时是否应隐藏菜单栏。 |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | 设置标志，指定在文档处于活动状态时工具栏是否应隐藏。 |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | 设置标志，指定在文档处于活动状态时是否应隐藏用户界面元素。 |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLayersAdded(boolean value)](#setLayersAdded-boolean-) | 设置 LayersAdded 值 |
| [setLinearized(boolean value)](#setLinearized-boolean-) | 设置一个值，指示文档是否线性化。 |
| [setManualDisposeEnabled(boolean manualDisposeEnabled)](#setManualDisposeEnabled-boolean-) | 默认方法 save 关闭内部流并释放内存资源。 |
| [setNonFullScreenPageMode(int value)](#setNonFullScreenPageMode-int-) | 设置页面模式，指定在退出全屏模式时如何显示文档。 |
| [setOpenAction(IAppointment value)](#setOpenAction-com.aspose.pdf.IAppointment-) | 设置在文档打开时执行的操作。 |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | 设置优化标志。 |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置页面信息。 |
| [setPageLayout(int value)](#setPageLayout-int-) | 设置打开文档时应使用的页面布局。 |
| [setPageMode(int value)](#setPageMode-int-) | 设置页面模式，指定打开文档时应如何显示。 |
| [setTitle(String title)](#setTitle-java.lang.String-) | 为 Pdf 文档设置标题 |
| [setXmpMetadata(InputStream stream)](#setXmpMetadata-java.io.InputStream-) | 设置文档的 XMP 元数据。 |
| [setXrefGapsAllowed(boolean value)](#setXrefGapsAllowed-boolean-) | 获取或设置文档 pdfa 兼容。 |
| [抑制更新()](#suppressUpdate--) | suppressUpdate |
| [更新页面()](#updatePages--) | updatePages |
| [validate(OutputStream outputLogStream, PdfFormat format)](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | 将文档验证到指定的文件中。 |
| [validate(String outputLogFileName, PdfFormat format)](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | 将文档验证到指定的文件中。 |
### afterImport() {#afterImport--}
```
public abstract void afterImport()
```


枚举所有已注册的注释并为每个注释调用 AfterImport。

### bindXml(InputStream stream) {#bindXml-java.io.InputStream-}
```
public abstract void bindXml(InputStream stream)
```


将 xml 绑定到文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 带有 xml 文件的流 |

### bindXml(String file) {#bindXml-java.lang.String-}
```
public abstract void bindXml(String file)
```


将 xml 绑定到文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | xml文件 |

### bindXml(String xmlFile, String xslFile) {#bindXml-java.lang.String-java.lang.String-}
```
public abstract void bindXml(String xmlFile, String xslFile)
```


将 xml/xsl 绑定到文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlFile | java.lang.String | xml 文件。 |
| xslFile | java.lang.String | 如果使用 XSLT，则为 xsl 文件。 |

### changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword) {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract void changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)
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
public abstract boolean check(boolean doRepair)
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
public abstract void close()
```


关闭此文档使用的所有资源。

### convert(Document.CallBackGetHocr callback) {#convert-com.aspose.pdf.Document.CallBackGetHocr-}
```
public abstract boolean convert(Document.CallBackGetHocr callback)
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
public abstract boolean convert(Document.CallBackGetHocr callback, boolean isTestVisible)
```


转换文档并将错误保存到指定文件中。

这允许在页面上显示/隐藏可搜索文本。默认值为 FALSE。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | 无法转换的对象的操作 |
| isTestVisible | boolean | 布尔值 |

**退货：**
boolean - 运算结果
### convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-}
```
public abstract boolean convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage)
```


转换文档并将错误保存到指定文件中。

这允许在页面上显示/隐藏可搜索文本。默认值为 FALSE。这允许从 pdf 获取原始图像。默认值为 FALSE。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | 无法转换的对象的操作 |
| isTestVisible | boolean | 布尔值 |
| isOriginalImage | boolean | 布尔值 |

**退货：**
boolean - 运算结果
### convert(PdfFormatConversionOptions options) {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
```
public abstract boolean convert(PdfFormatConversionOptions options)
```


使用指定的转换选项转换文档

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | [PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) | 一组用于转换 PDF 文档的选项 |

**退货：**
boolean - 运算结果
### convert(OutputStream outputLogStream, PdfFormat format, int action) {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convert(OutputStream outputLogStream, PdfFormat format, int action)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream |  |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) |  |
| action | int |  |

**退货：**
布尔值
### convert(String outputLogFileName, PdfFormat format, int action) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convert(String outputLogFileName, PdfFormat format, int action)
```


转换文档并将错误保存到指定文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | java.lang.String | 将存储评论的文件路径。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PDF 格式。 |
| action | int | 无法转换的对象的操作 |

**退货：**
boolean - 运算结果
### convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-}
```
public abstract boolean convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)
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
### convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none) {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none)
```


内部方法

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| log | com.aspose.ms.System.IO.Stream | 内部对象 |
| _convertTo | [PdfFormat](../../com.aspose.pdf/pdfformat) | 内部对象 |
| none | int | 内部对象 |

**退货：**
布尔值 - 内部值
### convertWithSkippingErrors(Document.CallBackGetHocr callback) {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-}
```
public abstract boolean convertWithSkippingErrors(Document.CallBackGetHocr callback)
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
public abstract void decrypt()
```


解密文档。然后调用 Save 以获得文档的解密版本。

### dispose() {#dispose--}
```
public abstract void dispose()
```


关闭此文档使用的所有资源。

此方法已过时，请改用 close() 。

### encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-}
```
public abstract void encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)
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
public abstract void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
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
public abstract void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)
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

### exportAnnotationsToXfdf(String fileName) {#exportAnnotationsToXfdf-java.lang.String-}
```
public abstract void exportAnnotationsToXfdf(String fileName)
```


将所有文档注释导出到 XFDF 文件

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | XFDF 文件名 |

### flatten() {#flatten--}
```
public abstract void flatten()
```


从文档中删除所有字段并改为放置它们的值。

### flatten(Form.FlattenSettings flattenSettings) {#flatten-com.aspose.pdf.Form.FlattenSettings-}
```
public abstract void flatten(Form.FlattenSettings flattenSettings)
```


从文档中删除所有字段并改为放置它们的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| flattenSettings | [FlattenSettings](../../com.aspose.pdf/flattensettings) | 展平过程的设置。 |

### freeMemory() {#freeMemory--}
```
public abstract void freeMemory()
```


清除内存

### getActions() {#getActions--}
```
public abstract DocumentActionCollection getActions()
```


获取文档操作。此属性是 DocumentActions 类的实例，它允许获取/设置 BeforClosing、BeforSaving 等操作。

--------------------

```
This example demonstrates how to obtain after open action of the document:

 Document document = new Document("PdfWithOpenAction.pdf");
 DocumentActions actions = document.getActions();
 com.aspose.pdf.Action afterSavingAction = actions.getAfterSaving();
```

**退货：**
[DocumentActionCollection](../../com.aspose.pdf/documentactioncollection) - DocumentActionCollection 对象
### getBackground() {#getBackground--}
```
public abstract Color getBackground()
```


获取文档的背景颜色。

**退货：**
[Color](../../java.awt/color) - java.awt.Color 对象
### getCatalogValue(String key) {#getCatalogValue-java.lang.String-}
```
public abstract Object getCatalogValue(String key)
```


从目录字典返回项目值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 项目的关键。 |

**退货：**
java.lang.Object - 项目值 - 如果成功找到键；否则为空。
### getCollection() {#getCollection--}
```
public abstract Collection getCollection()
```


获取文档集合。

**退货：**
[Collection](../../com.aspose.pdf/collection) - 集合对象
### getCryptoAlgorithm() {#getCryptoAlgorithm--}
```
public abstract int getCryptoAlgorithm()
```


如果文档已加密，则获取安全设置。如果文档未加密，则在 .net 1.1 中将引发相应的异常，或者对于其他 .net 版本，CryptoAlgorithm 将为 null。

**退货：**
int - 整数值
### getDefaultCopier() {#getDefaultCopier--}
```
public abstract Copier getDefaultCopier()
```


将用于复印页面的复印机返回到此文档。

**退货：**
[Copier](../../com.aspose.pdf/copier) 复印机对象
### getDestinations() {#getDestinations--}
```
public abstract DestinationCollection getDestinations()
```


获取目的地的集合。

**退货：**
[DestinationCollection](../../com.aspose.pdf/destinationcollection) DestinationCollection 对象
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


获取文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。

**退货：**
int - 方向元素
### getDuplex() {#getDuplex--}
```
public abstract int getDuplex()
```


获取或设置从打印对话框打印文件时要使用的打印双面模式处理选项。

**退货：**
int - PrintDuplex 元素
### getEmbedStandardFonts() {#getEmbedStandardFonts--}
```
public abstract boolean getEmbedStandardFonts()
```


声明文档必须嵌入所有标准 Type1 字体的属性，该字体的标志 IsEmbedded 设置为 true。所有 PDF 字体都可以简单地通过将标志 IsEmbedded 设置为 true 来嵌入到文档中，但 PDF 标准 Type1 字体是此规则的一个例外。标准 Type1 字体嵌入需要很多时间，因此要嵌入这些字体，不仅需要将指定字体的标志 IsEmbedded 设置为 true，还需要在文档级别设置一个附加标志 - EmbedStandardFonts = true;此属性只能为所有字体设置一次。默认为假。

**退货：**
boolean - 布尔值
### getEmbeddedFiles() {#getEmbeddedFiles--}
```
public abstract EmbeddedFileCollection getEmbeddedFiles()
```


获取嵌入文档的文件集合。

**退货：**
[EmbeddedFileCollection](../../com.aspose.pdf/embeddedfilecollection) - EmbeddedFileCollection 对象
### getEnableSignatureSanitization() {#getEnableSignatureSanitization--}
```
public abstract boolean getEnableSignatureSanitization()
```


获取或设置标志以管理签名字段清理。默认启用。

**退货：**
boolean - 布尔值
### getEngineDoc() {#getEngineDoc--}
```
public abstract IPdfDocument getEngineDoc()
```


用于访问内部文档结构的 IPdfDocument 实例。仅限内部

**退货：**
[IPdfDocument](../../com.aspose.pdf.engine/ipdfdocument) IPdfDocument 对象
### getFileName() {#getFileName--}
```
public abstract String getFileName()
```


生成此文档的 PDF 文件的名称

**退货：**
java.lang.String - 字符串对象
### getForm() {#getForm--}
```
public abstract Form getForm()
```


获取文档的 Acro 形式。

**退货：**
[Form](../../com.aspose.pdf/form) 表单对象
### getId() {#getId--}
```
public abstract Id getId()
```


获取ID。

**退货：**
[Id](../../com.aspose.pdf/id) Id 对象
### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public abstract boolean getIgnoreCorruptedObjects()
```


获取或设置忽略源文件中错误的标志。当源文档中的页面复制到目标文档中时，如果源文件中的某些对象已损坏，则复制过程将停止，但此标志为 false。例子： dest.Pages.Add(src.Pages);如果此标志设置为 true，则损坏的对象将被替换为空值。默认情况下：真。

**退货：**
boolean - 布尔值
### getInfo() {#getInfo--}
```
public abstract DocumentInfo getInfo()
```


获取文档信息。

**退货：**
[DocumentInfo](../../com.aspose.pdf/documentinfo) - 文档信息对象
### getLogicalStructure() {#getLogicalStructure--}
```
public abstract RootElement getLogicalStructure()
```


获取文档的逻辑结构。

**退货：**
[RootElement](../../com.aspose.pdf/rootelement) RootElement 对象
### getMetadata() {#getMetadata--}
```
public abstract Metadata getMetadata()
```


文档元数据。 （PDF 文档可能包含一般信息，例如文档的标题、作者以及创建和修改日期。此类关于文档的全局信息（相对于其内容或结构）称为元数据，旨在帮助编目和搜索对于外部数据库中的文档。）

**退货：**
[Metadata](../../com.aspose.pdf/metadata) - 元数据对象
### getMetadataStream() {#getMetadataStream--}
```
public abstract IPdfStreamAccessor getMetadataStream()
```


返回原始元数据流

**退货：**
[IPdfStreamAccessor](../../com.aspose.pdf.engine.data.types/ipdfstreamaccessor) IPdfStreamAccessor 对象
### getNamedDestinations() {#getNamedDestinations--}
```
public abstract NamedDestinationCollection getNamedDestinations()
```


文档中命名目标的集合。

**退货：**
[NamedDestinationCollection](../../com.aspose.pdf.nameddestinations/nameddestinationcollection) NamedDestinationCollection 实例
### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public abstract int getNonFullScreenPageMode()
```


获取页面模式，指定在退出全屏模式时如何显示文档。

**退货：**
int - PageMode 元素
### getObjectById(String id) {#getObjectById-java.lang.String-}
```
public abstract Object getObjectById(String id)
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
public abstract IAppointment getOpenAction()
```


获取打开文档时执行的操作。

--------------------

```
Example demonstrates how to get CenterWindow flag:
 Document document = new Document("sample.pdf");
 IAppointment value = document.getOpenAction();
```

**退货：**
[IAppointment](../../com.aspose.pdf/iappointment)-IAppointment 对象
### getOptimizeSize() {#getOptimizeSize--}
```
public abstract boolean getOptimizeSize()
```


获取优化标志。将页面添加到文档时，如果设置了此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。这允许减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。默认值：假。

**退货：**
boolean - 布尔值
### getOutlines() {#getOutlines--}
```
public abstract OutlineCollection getOutlines()
```


获取文档大纲。

**退货：**
[OutlineCollection](../../com.aspose.pdf/outlinecollection) - OutlineCollection 对象
### getPageInfo() {#getPageInfo--}
```
public abstract PageInfo getPageInfo()
```


获取页面信息。（仅适用于生成器）

**退货：**
[PageInfo](../../com.aspose.pdf/pageinfo) - 页面信息。
### getPageLabels() {#getPageLabels--}
```
public abstract PageLabelCollection getPageLabels()
```


获取文档中的页面标签。

**退货：**
[PageLabelCollection](../../com.aspose.pdf/pagelabelcollection) - PageLabelCollection 对象
### getPageLayout() {#getPageLayout--}
```
public abstract int getPageLayout()
```


获取打开文档时应使用的页面布局。

**退货：**
int - PageLayout 元素
### getPageMode() {#getPageMode--}
```
public abstract int getPageMode()
```


获取页面模式，指定打开文档时应如何显示。

**退货：**
int - PageMode 元素
### getPages() {#getPages--}
```
public abstract PageCollection getPages()
```


获取文档页面的集合。请注意，页面在集合中从 1 开始编号。

--------------------

```
Example below demonstrates how to operate with the document pages:
 How to obtain number of pages and how to obtain rectangle of starting page of the document.

 Document document = new Document("sample.pdf");
 Pages pages = document.getPages();
 System.out.println("Document contains " + pages.size());
 Page page = pages.get_Item(1);
 Rectangle rect = page.getRect();
```

**退货：**
[PageCollection](../../com.aspose.pdf/pagecollection) 布尔值
### getPdfFormat() {#getPdfFormat--}
```
public abstract PdfFormat getPdfFormat()
```




**退货：**
[PdfFormat](../../com.aspose.pdf/pdfformat) - PdfFormat 元素
### getPermissions() {#getPermissions--}
```
public abstract int getPermissions()
```


获取文档的权限。

**退货：**
int - 整数值
### getVersion() {#getVersion--}
```
public abstract String getVersion()
```


从 Pdf 文件头获取 Pdf 的版本。

**退货：**
java.lang.String - 字符串对象
### getXmpMetadata(OutputStream stream) {#getXmpMetadata-java.io.OutputStream-}
```
public abstract void getXmpMetadata(OutputStream stream)
```


从文档中获取 XMP 元数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 将存储元数据的流。 |

### importAnnotationsFromXfdf(String fileName) {#importAnnotationsFromXfdf-java.lang.String-}
```
public abstract void importAnnotationsFromXfdf(String fileName)
```


将注释从 XFDF 文件导入文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | XFDF 文件名 |

### isAbsentFontTryToSubstitute() {#isAbsentFontTryToSubstitute--}
```
public abstract boolean isAbsentFontTryToSubstitute()
```


处理文档时有关丢失字体的通知

**退货：**
boolean - 布尔值
### isCenterWindow() {#isCenterWindow--}
```
public abstract boolean isCenterWindow()
```


获取指定文档窗口的位置是否将在屏幕上居中的标志。

--------------------

```
Example demonstrates how to get CenterWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isCenterWindow();
```

**退货：**
boolean - 布尔值
### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public abstract boolean isDisableFontLicenseVerifications()
```


如果该字体的许可证禁止这些操作，则无法执行该字体的许多操作。例如，如果许可规则禁止嵌入某些字体，则无法将其嵌入到 PDF 文档中。此标志用于禁用当前 PDF 文档中所有字体的任何许可限制。使用此标志时要小心。当它被设置时，意味着设置这个标志的人，对自己可能违反许可/法律的行为承担全部责任。所以他自己承担风险。强烈建议仅当您完全确信自己没有违反版权法时才使用此标志。

**退货：**
boolean - 布尔值默认为 false。
### isDisplayDocTitle() {#isDisplayDocTitle--}
```
public abstract boolean isDisplayDocTitle()
```


获取指定文档窗口标题栏是否应显示文档标题的标志。

--------------------

```
Example demonstrates how to get DisplayDocTitle flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isDisplayDocTitle();
```

**退货：**
boolean - 布尔值
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


获取文档的加密状态。如果文档已加密，则为真。

**退货：**
boolean - 布尔值
### isFitWindow() {#isFitWindow--}
```
public abstract boolean isFitWindow()
```


获取指定是否必须调整文档窗口大小以适合显示的第一个页面的标志。

--------------------

```
Example demonstrates how to get FitWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isFitWindow();
```

**退货：**
boolean - 布尔值
### isHideMenubar() {#isHideMenubar--}
```
public abstract boolean isHideMenubar()
```


获取指定在文档处于活动状态时是否应隐藏菜单栏的标志。

--------------------

```
Example demonstrates how to get HideMenubar flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideMenubar();
```

**退货：**
boolean - 布尔值
### isHideToolBar() {#isHideToolBar--}
```
public abstract boolean isHideToolBar()
```


获取指定在文档处于活动状态时是否应隐藏工具栏的标志。

--------------------

```
Example demonstrates how to get HideToolBar flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideToolBar();
```

**退货：**
boolean - 布尔值
### isHideWindowUI() {#isHideWindowUI--}
```
public abstract boolean isHideWindowUI()
```


获取或设置标志，该标志指定当文档处于活动状态时是否应隐藏用户界面元素。

--------------------

```
Example demonstrates how to get HideWindowUI flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideWindowUI();
```

**退货：**
boolean - 布尔值
### isLinearized() {#isLinearized--}
```
public abstract boolean isLinearized()
```


获取或设置一个值，该值指示文档是否线性化。

**退货：**
boolean - 布尔值
### isManualDisposeEnabled() {#isManualDisposeEnabled--}
```
public abstract boolean isManualDisposeEnabled()
```


默认方法保存关闭内部流并释放内存资源。如果启用此 ManualDispose 参数，我们可以在方法保存后执行一些操作并继续处理文档。

**退货：**
boolean - 布尔值。 （默认值 == 假）
### isPdfUaCompliant() {#isPdfUaCompliant--}
```
public abstract boolean isPdfUaCompliant()
```


获取符合 pdfua 标准的文档。

**退货：**
boolean - 布尔值
### isPdfaCompliant() {#isPdfaCompliant--}
```
public abstract boolean isPdfaCompliant()
```




**退货：**
布尔值
### isXrefGapsAllowed() {#isXrefGapsAllowed--}
```
public abstract boolean isXrefGapsAllowed()
```


获取或设置文档 pdfa 兼容。

**退货：**
boolean - 布尔值
### optimize() {#optimize--}
```
public abstract void optimize()
```


线性化文档以便 - 尽快打开第一页； - 尽快显示下一页或通过链接进入下一页； - 当页面数据通过慢速通道传送时，在页面到达时逐步显示页面（首先显示最有用的数据）； - 允许甚至在接收和显示整个页面之前执行用户交互，例如跟随链接。调用此方法实际上并不保存文档。反之只准备有优化结构的文档，调用Save 即可得到优化后的文档。

### optimizeResources() {#optimizeResources--}
```
public abstract void optimizeResources()
```


优化文档中的资源： 1. 去除文档页面中不用的资源； 2. 等量资源合并为一个对象； 3. 删除未使用的对象。

### optimizeResources(OptimizationOptions strategy) {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
```
public abstract void optimizeResources(OptimizationOptions strategy)
```


根据定义的优化策略优化文档中的资源。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| strategy | [OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions) | 优化策略。 |

### processParagraphs() {#processParagraphs--}
```
public abstract void processParagraphs()
```


将文档存储到流中。

### removeMetadata() {#removeMetadata--}
```
public abstract void removeMetadata()
```


从文档中删除元数据。

### removePdfUaCompliance() {#removePdfUaCompliance--}
```
public abstract void removePdfUaCompliance()
```


从文档中删除 pdfUa 合规性

### removePdfaCompliance() {#removePdfaCompliance--}
```
public abstract void removePdfaCompliance()
```


从文档中删除 pdfa 合规性

### repair() {#repair--}
```
public abstract void repair()
```


修复损坏的文档。

### resumeUpdate() {#resumeUpdate--}
```
public abstract void resumeUpdate()
```


恢复更新

### save() {#save--}
```
public abstract void save()
```


增量保存文档（即使用增量更新技术）。

--------------------

为了增量保存文档，我们应该打开文档文件进行写入。因此，Document 不能使用 InputStream 进行初始化，而必须使用文件路径进行初始化，如下一个代码片段所示：Document doc = new Document("document.pdf"); // 进行一些更改并增量保存文档 doc.save();

如果文档是用 InputStream 初始化的，写入 InputStream 是不可能的，所以我们建议使用单独的方法“save”来保存文档或“saveIncrementally”来增量保存文档。

### save(OutputStream output) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream output)
```


将文档存储到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | java.io.OutputStream | 存储文档外壳的流。 |

### save(OutputStream outputStream, SaveFormat format) {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
```
public abstract void save(OutputStream outputStream, SaveFormat format)
```


保存文件

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 输出流对象 |
| format | [SaveFormat](../../com.aspose.pdf/saveformat) | 保存格式值 |

### save(OutputStream outputStream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public abstract void save(OutputStream outputStream, SaveOptions options)
```


使用设置其保存选项的新名称保存文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 将存储文档的 OutputStream。 |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项。 |

### save(String outputFileName) {#save-java.lang.String-}
```
public abstract void save(String outputFileName)
```


将文档保存到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | java.lang.String | 将存储文档的文件路径。 |

### save(String outputFileName, SaveOptions options) {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public abstract void save(String outputFileName, SaveOptions options)
```


使用设置其保存选项的新名称保存文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | java.lang.String | 将存储文档的文件路径。 |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项。 |

### saveIncrementally(System.IO.Stream output) {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
```
public abstract void saveIncrementally(System.IO.Stream output)
```


将 PDF 文档增量保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | 输出流对象 |

### saveIncrementally(OutputStream output) {#saveIncrementally-java.io.OutputStream-}
```
public abstract void saveIncrementally(OutputStream output)
```


将 PDF 文档增量保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | java.io.OutputStream | 输出流对象 |

### saveIncrementally(String outputFileName) {#saveIncrementally-java.lang.String-}
```
public abstract void saveIncrementally(String outputFileName)
```


将 PDF 文档增量保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | java.lang.String | 字符串值 |

### saveXml(String file) {#saveXml-java.lang.String-}
```
public abstract void saveXml(String file)
```


将文档保存为 XML。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 文档模型xml文件 |

### sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
```
public abstract void sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)
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
public abstract void sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)
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
public abstract void sendTo(DocumentDevice device, OutputStream output)
```


将整个文档发送到文档设备进行处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | 文档设备对象 |
| output | java.io.OutputStream | 输出流对象 |

### sendTo(DocumentDevice device, String outputFileName) {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
```
public abstract void sendTo(DocumentDevice device, String outputFileName)
```


将整个文档发送到文档设备进行处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | 用于处理文档的文档设备。 |
| outputFileName | java.lang.String | 带有处理结果的输出文件名。 |

### setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute) {#setAbsentFontTryToSubstitute-boolean-}
```
public abstract void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```


在没有字体的情况下，设置程序确定字体的设置标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| setAbsentFontTryToSubstitute | boolean | 布尔值 |

### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public abstract void setBackground(Color value)
```


设置文档的背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color | java.awt.Color 对象 |

### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public abstract void setCenterWindow(boolean value)
```


设置标志指定文档窗口的位置是否将在屏幕上居中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCollection(Collection value) {#setCollection-com.aspose.pdf.Collection-}
```
public abstract void setCollection(Collection value)
```


设置文档集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Collection](../../com.aspose.pdf/collection) | 集合对象 |

### setConvertMetadataAndCatalogOnly(boolean value) {#setConvertMetadataAndCatalogOnly-boolean-}
```
public abstract void setConvertMetadataAndCatalogOnly(boolean value)
```


获取 pdf/ua 转换器的转换参数（如果设置为 true，则仅转换元数据和文档目录）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 方向元素 |

### setDisableFontLicenseVerifications(boolean value) {#setDisableFontLicenseVerifications-boolean-}
```
public abstract void setDisableFontLicenseVerifications(boolean value)
```


如果该字体的许可证禁止这些操作，则无法执行该字体的许多操作。例如，如果许可规则禁止嵌入某些字体，则无法将其嵌入到 PDF 文档中。此标志用于禁用当前 PDF 文档中所有字体的任何许可限制。使用此标志时要小心。当它被设置时，意味着设置这个标志的人，对自己可能违反许可/法律的行为承担全部责任。所以他自己承担风险。强烈建议仅当您完全确信自己没有违反版权法时才使用此标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 默认为 false。 |

### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public abstract void setDisplayDocTitle(boolean value)
```


设置标志指定文档的窗口标题栏是否应显示文档标题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setDuplex(int value) {#setDuplex-int-}
```
public abstract void setDuplex(int value)
```


获取或设置从打印对话框打印文件时要使用的打印双面模式处理选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PrintDuplex 元素 |

### setEmbedStandardFonts(boolean value) {#setEmbedStandardFonts-boolean-}
```
public abstract void setEmbedStandardFonts(boolean value)
```


声明文档必须嵌入所有标准 Type1 字体的属性，该字体的标志 IsEmbedded 设置为 true。所有 PDF 字体都可以简单地通过将标志 IsEmbedded 设置为 true 来嵌入到文档中，但 PDF 标准 Type1 字体是此规则的一个例外。标准 Type1 字体嵌入需要很多时间，因此要嵌入这些字体，不仅需要将指定字体的标志 IsEmbedded 设置为 true，还需要在文档级别设置一个附加标志 - EmbedStandardFonts = true;此属性只能为所有字体设置一次。默认为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setEnableSignatureSanitization(boolean value) {#setEnableSignatureSanitization-boolean-}
```
public abstract void setEnableSignatureSanitization(boolean value)
```


获取或设置标志以管理签名字段清理。默认启用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public abstract void setFitWindow(boolean value)
```


设置标志，指定是否必须调整文档窗口的大小以适合显示的第一个页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHideMenubar(boolean value) {#setHideMenubar-boolean-}
```
public abstract void setHideMenubar(boolean value)
```


设置标志，指定当文档处于活动状态时是否应隐藏菜单栏。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public abstract void setHideToolBar(boolean value)
```


设置标志，指定在文档处于活动状态时工具栏是否应隐藏。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public abstract void setHideWindowUI(boolean value)
```


设置标志，指定在文档处于活动状态时是否应隐藏用户界面元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public abstract void setIgnoreCorruptedObjects(boolean value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setLayersAdded(boolean value) {#setLayersAdded-boolean-}
```
public abstract void setLayersAdded(boolean value)
```


设置 LayersAdded 值

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLinearized(boolean value) {#setLinearized-boolean-}
```
public abstract void setLinearized(boolean value)
```


设置一个值，指示文档是否线性化。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setManualDisposeEnabled(boolean manualDisposeEnabled) {#setManualDisposeEnabled-boolean-}
```
public abstract void setManualDisposeEnabled(boolean manualDisposeEnabled)
```


默认方法 save 关闭内部流并释放内存资源。如果启用此 ManualDispose 参数，我们可以在调用方法保存后执行一些操作并继续处理文档。但强烈建议在不再需要 Document 实例时调用 dispose 方法。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| manualDisposeEnabled | boolean | 布尔值。 （默认值 == 假） |

### setNonFullScreenPageMode(int value) {#setNonFullScreenPageMode-int-}
```
public abstract void setNonFullScreenPageMode(int value)
```


设置页面模式，指定在退出全屏模式时如何显示文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PageMode 元素 |

### setOpenAction(IAppointment value) {#setOpenAction-com.aspose.pdf.IAppointment-}
```
public abstract void setOpenAction(IAppointment value)
```


设置在文档打开时执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | 约会对象 |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public abstract void setOptimizeSize(boolean value)
```


设置优化标志。将页面添加到文档时，如果设置了此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。这允许减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。默认值：假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public abstract void setPageInfo(PageInfo value)
```


设置页面信息。（仅适用于生成器）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | PageInfo 对象 |

### setPageLayout(int value) {#setPageLayout-int-}
```
public abstract void setPageLayout(int value)
```


设置打开文档时应使用的页面布局。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 页面布局元素 |

### setPageMode(int value) {#setPageMode-int-}
```
public abstract void setPageMode(int value)
```


设置页面模式，指定打开文档时应如何显示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PageMode 元素 |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String title)
```


为 Pdf 文档设置标题

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| title | java.lang.String | 文档的标题 |

### setXmpMetadata(InputStream stream) {#setXmpMetadata-java.io.InputStream-}
```
public abstract void setXmpMetadata(InputStream stream)
```


设置文档的 XMP 元数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 XMP 元数据的流。 |

### setXrefGapsAllowed(boolean value) {#setXrefGapsAllowed-boolean-}
```
public abstract void setXrefGapsAllowed(boolean value)
```


获取或设置文档 pdfa 兼容。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### suppressUpdate() {#suppressUpdate--}
```
public abstract void suppressUpdate()
```


抑制更新

### updatePages() {#updatePages--}
```
public abstract void updatePages()
```


更新页面

### validate(OutputStream outputLogStream, PdfFormat format) {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
```
public abstract boolean validate(OutputStream outputLogStream, PdfFormat format)
```


将文档验证到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | 将存储评论的流。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PDF 格式。 |

**退货：**
boolean - 运算结果
### validate(String outputLogFileName, PdfFormat format) {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
```
public abstract boolean validate(String outputLogFileName, PdfFormat format)
```


将文档验证到指定的文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | java.lang.String | 将存储评论的文件路径。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PDF 格式。 |

**退货：**
boolean - 布尔值