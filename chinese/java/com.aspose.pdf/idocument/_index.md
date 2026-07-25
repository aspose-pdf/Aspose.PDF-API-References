---
title: "IDocument"
linktitle: "IDocument"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档的接口"
type: docs
weight: 2230
url: /zh/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

表示 PDF 文档的接口

## 方法

| 方法 | 描述 |
| --- | --- |
| [afterImport](#afterImport--) | 枚举所有已注册的注释并为每个调用 AfterImport。 |
| [bindXml](#bindXml-java.io.InputStream-) | 将 xml 绑定到文档 |
| [bindXml](#bindXml-java.lang.String-) | 将 xml 绑定到文档 |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | 将 xml/xsl 绑定到文档 |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | 更改文档密码。 |
| [check](#check-boolean-) | 验证文档。 |
| [close](#close--) | 关闭此文档使用的所有资源。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | 将文档转换为可搜索文档。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | 将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | 将文档转换并将错误保存到指定文件。 <p> 这允许在页面上显示/隐藏可搜索文本。默认值为 FALSE。 这允许从 pdf 获取原始图像。默认值为 FALSE。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | 将文档转换并将错误保存到指定文件。 <p> 这允许在页面上显示/隐藏可搜索文本。默认值为 FALSE。 这允许从 pdf 获取原始图像。默认值为 FALSE。 |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | 使用指定的转换选项转换文档 |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | 将文档转换并将错误保存到指定文件。 |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 内部方法 |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | 将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。 |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | 将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。 |
| [decrypt](#decrypt--) | 解密文档。 |
| [dispose](#dispose--) | 已弃用。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | 加密文档。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | 加密文档。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | 加密文档。 |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | 将所有文档注释导出为 XFDF 文件 |
| [flatten](#flatten--) | 从文档中移除所有字段（以及注释），并用它们的值替代。 |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | 从文档中移除所有字段，并用它们的值替代。 |
| [flattenTransparency](#flattenTransparency--) | 将透明内容替换为非透明的光栅和矢量图形。 |
| [freeMemory](#freeMemory--) | 清除内存 |
| [getActions](#getActions--) | 获取文档操作。 |
| [getBackground](#getBackground--) | 获取文档的背景颜色。 |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | 返回目录字典中的项目值。 |
| [getCollection](#getCollection--) | 获取文档集合。 |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | 如果文档已加密，则获取安全设置。 |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | 获取自定义安全处理程序。 |
| [getDefaultCopier](#getDefaultCopier--) | 返回用于将页面复制到此文档的复制器。 |
| [getDestinations](#getDestinations--) | 获取目标集合。 |
| [getDirection](#getDirection--) | 获取文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [getDuplex](#getDuplex--) | 获取或设置在打印对话框中打印文件时使用的打印双面模式处理选项。 |
| [getEmbeddedFiles](#getEmbeddedFiles--) | 获取嵌入文档的文件集合。 |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | 声明文档必须嵌入所有标准 Type1 字体的属性，该属性的 IsEmbedded 标志设置为 true。 |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | 获取或设置用于管理签名字段清理的标志。 |
| [getEngineDoc](#getEngineDoc--) | 用于访问内部文档结构的 IPdfDocument 实例。 |
| [getFileName](#getFileName--) | 导致此文档的 PDF 文件名称 |
| [getForm](#getForm--) | 获取文档的 Acro Form。 |
| [getId](#getId--) | 获取 ID。 |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | 获取或设置忽略源文件错误的标志。 |
| [getInfo](#getInfo--) | 获取文档信息。 |
| [getLogicalStructure](#getLogicalStructure--) | 获取文档的逻辑结构。 |
| [getMetadata](#getMetadata--) | 文档元数据。 |
| [getMetadataStream](#getMetadataStream--) | 返回原始元数据流 |
| [getNamedDestinations](#getNamedDestinations--) | 文档中命名目标的集合。 |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | 获取页面模式，指定退出全屏模式时文档的显示方式。 |
| [getObjectById](#getObjectById-java.lang.String-) | 获取文档中具有指定 ID 的对象。 |
| [getOpenAction](#getOpenAction--) | 获取文档打开时执行的操作。 |
| [getOptimizeSize](#getOptimizeSize--) | 获取优化标志。 |
| [getOutlines](#getOutlines--) | 获取文档大纲。 |
| [getPageInfo](#getPageInfo--) | 获取页面信息。（仅用于生成器，读取文档时不填充） |
| [getPageLabels](#getPageLabels--) | 获取文档中的页面标签。 |
| [getPageLayout](#getPageLayout--) | 获取文档打开时应使用的页面布局。 |
| [getPageMode](#getPageMode--) | 获取页面模式，指定文档打开时的显示方式。 |
| [getPages](#getPages--) | 获取文档页面的集合。 |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | 获取文档的权限。 |
| [getPrintScaling](#getPrintScaling--) | 获取在打印对话框中打印文件时使用的打印缩放处理选项。 |
| [getTaggedContent](#getTaggedContent--) | 获取对 TaggedPdf 内容的访问。 |
| [getVersion](#getVersion--) | 获取 PDF 文件头中的 PDF 版本。 |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | 获取文档的 XMP 元数据。 |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | 从 XFDF 文件导入注释到文档。 |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | 处理文档时缺少字体的通知 |
| [isCenterWindow](#isCenterWindow--) | 获取指定文档窗口位置是否居中于屏幕的标志。 |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | 如果这些操作被该字体的许可证禁止，则许多字体操作无法执行。 |
| [isDisplayDocTitle](#isDisplayDocTitle--) | 获取指定文档窗口标题栏是否应显示文档标题的标志。 |
| [isEncrypted](#isEncrypted--) | 获取文档的加密状态。 |
| [isFitWindow](#isFitWindow--) | 获取指定文档窗口是否必须调整大小以适应首次显示页面的标志。 |
| [isHideMenubar](#isHideMenubar--) | 获取指定文档激活时是否应隐藏菜单栏的标志。 |
| [isHideToolBar](#isHideToolBar--) | 获取指定文档激活时是否应隐藏工具栏的标志。 |
| [isHideWindowUI](#isHideWindowUI--) | 获取或设置指定文档激活时是否应隐藏用户界面元素的标志。 |
| [isLinearized](#isLinearized--) | 获取或设置指示文档是否已线性化的值。 |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | 默认情况下，save 方法会关闭内部流并释放内存资源。如果启用此 ManualDispose 参数，则可以在保存方法后执行一些操作并继续使用文档。 |
| [isPdfaCompliant](#isPdfaCompliant--) | 获取文档是否符合 PDF/A 标准。 |
| [isPdfUaCompliant](#isPdfUaCompliant--) | 获取文档是否符合 PDF/UA 标准。 |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | 获取指定是否使用 PDF 页面尺寸来选择输入纸盘的标志。 |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | 获取或设置文档是否符合 PDF/A 标准。 |
| [optimize](#optimize--) | 线性化文档，以便 - 尽快打开首页； - 尽快显示下一页或通过链接跳转到下一页； - 当页面数据通过慢速通道传输时，逐步显示页面（优先显示最有用的数据）； - 允许用户交互，例如点击链接，即使在整个页面尚未接收并显示完毕时也能进行。 |
| [optimizeResources](#optimizeResources--) | 优化文档中的资源：1。 |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | 根据定义的优化策略优化文档中的资源。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | 将文档中的页面树节点组织为平衡树。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | 将文档中的页面树节点组织为平衡树。 |
| [processParagraphs](#processParagraphs--) | 将文档存储到流中。 |
| [removeMetadata](#removeMetadata--) | 从文档中移除元数据。 |
| [removePdfaCompliance](#removePdfaCompliance--) | 从文档中移除 pdfa 合规性 |
| [removePdfUaCompliance](#removePdfUaCompliance--) | 从文档中移除 pdfUa 合规性 |
| [repair](#repair--) | 修复损坏的文档。 |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | 增量保存文档（即 |
| [save](#save-java.io.OutputStream-) | 将文档存储到流中。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | 保存文档 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 使用新名称保存文档并设置其保存选项。 |
| [save](#save-java.lang.String-) | 将文档保存到指定文件中。 |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | 使用新名称保存文档并设置其保存选项。 |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | 将 PDF 文档增量保存到指定流中。 |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | 将 PDF 文档增量保存到指定流中。 |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | 将 PDF 文档增量保存到指定流中。 |
| [saveXml](#saveXml-java.lang.String-) | 将文档保存为 XML。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | 将文档的特定页面发送到文档设备进行处理。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | 将整个文档发送到文档设备进行处理。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | 将整个文档发送到文档设备进行处理。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | 将整个文档发送到文档设备进行处理。 |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | 设置标志，以在缺少字体时使用程序确定的字体。 |
| [setBackground](#setBackground-java.awt.Color-) | 设置文档的背景颜色。 |
| [setCenterWindow](#setCenterWindow-boolean-) | 设置标志，指定文档窗口的位置是否居中显示在屏幕上。 |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | 设置文档的集合。 |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | 获取 pdf/ua 转换器的转换参数（如果设置为 true，则仅转换元数据和文档目录） |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | 设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | 如果这些操作被该字体的许可证禁止，则许多字体操作无法执行。 |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | 设置标志，指定文档窗口标题栏是否应显示文档标题。 |
| [setDuplex](#setDuplex-int-) | 获取或设置在打印对话框中打印文件时使用的打印双面模式处理选项。 |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | 声明文档必须嵌入所有标准 Type1 字体的属性，该属性的 IsEmbedded 标志设置为 true。 |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | 获取或设置用于管理签名字段清理的标志。 |
| [setFitWindow](#setFitWindow-boolean-) | 设置标志，指定文档窗口是否必须调整大小以适应首次显示的页面。 |
| [setHideMenubar](#setHideMenubar-boolean-) | 设置标志，指定文档激活时是否隐藏菜单栏。 |
| [setHideToolBar](#setHideToolBar-boolean-) | 设置标志，指定文档激活时是否隐藏工具栏。 |
| [setHideWindowUI](#setHideWindowUI-boolean-) | 设置标志，指定文档激活时是否隐藏用户界面元素。 |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | 设置一个值，指示文档是否已线性化。 |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | 默认情况下，save 方法会关闭内部流并释放内存资源。如果启用了 ManualDispose 参数，我们仍然可以在调用 save 方法后执行一些操作并继续使用文档。但强烈建议在不再需要 Document 实例时调用 dispose 方法。 |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | 设置页面模式，指定在退出全屏模式时如何显示文档。 |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | 设置文档打开时执行的操作。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 设置优化标志。 |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置页面信息。（仅用于生成器，在读取文档时不填充） |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | 设置在打开文档时应使用的页面布局。 |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | 设置页面模式，指定打开时文档应如何显示。 |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | 设置标志，指定是否应使用 PDF 页面大小来选择输入纸盘。 |
| [setPrintScaling](#setPrintScaling-int-) | 设置在打印对话框中打印文件时使用的打印缩放处理选项。 |
| [setTitle](#setTitle-java.lang.String-) | 设置 Pdf 文档的标题 |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | 设置文档的 XMP 元数据。 |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | 获取或设置文档是否符合 PDF/A 标准。 |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | 将文档验证到指定的文件中。 |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | 将文档验证到指定的文件中。 |

### afterImport {#afterImport--}
```
void afterImport()
```

枚举所有已注册的注释并为每个调用 AfterImport。

### bindXml {#bindXml-java.io.InputStream-}
将 xml 绑定到文档

### bindXml {#bindXml-java.lang.String-}
将 xml 绑定到文档

### bindXml {#bindXml-java.lang.String-java.lang.String-}
将 xml/xsl 绑定到文档

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
更改文档密码。

### check {#check-boolean-}
```
boolean check(boolean doRepair)
```

验证文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| doRepair |  | 如果为 true，将修复发现的问题。 |

**Returns:**
布尔值

### close {#close--}
```
void close()
```

关闭此文档使用的所有资源。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
将文档转换为可搜索文档。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
将文档转换并将错误保存到指定文件。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
将文档转换并将错误保存到指定文件。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
将文档转换并将错误保存到指定文件。 <p> 这允许在页面上显示/隐藏可搜索文本。默认值为 FALSE。 这允许从 pdf 获取原始图像。默认值为 FALSE。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
将文档转换并将错误保存到指定文件。 <p> 这允许在页面上显示/隐藏可搜索文本。默认值为 FALSE。 这允许从 pdf 获取原始图像。默认值为 FALSE。

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
使用指定的转换选项转换文档

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
将文档转换并将错误保存到指定文件。

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
将文档转换并将错误保存到指定文件。

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
内部方法

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。

### decrypt {#decrypt--}
```
void decrypt()
```

解密文档。

### dispose {#dispose--}
```
@Deprecated void dispose()
```

已弃用。

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
加密文档。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
加密文档。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
加密文档。

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
将所有文档注释导出为 XFDF 文件

### flatten {#flatten--}
```
void flatten()
```

从文档中移除所有字段（以及注释），并用它们的值替代。

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
从文档中移除所有字段，并用它们的值替代。

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

将透明内容替换为非透明的光栅和矢量图形。

### freeMemory {#freeMemory--}
```
void freeMemory()
```

清除内存

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

获取文档操作。

**Returns:**
DocumentActionCollection 对象

### getBackground {#getBackground--}
```
Color getBackground()
```

获取文档的背景颜色。

**Returns:**
java.awt.Color 对象

### getCatalogValue {#getCatalogValue-java.lang.String-}
返回目录字典中的项目值。

### getCollection {#getCollection--}
```
Collection getCollection()
```

获取文档集合。

**Returns:**
Collection 对象

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

如果文档已加密，则获取安全设置。

**Returns:**
CryptoAlgorithm 元素或 null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

获取自定义安全处理程序。

**Returns:**
ICustomSecurityHandler 实例

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

返回用于将页面复制到此文档的复制器。

**Returns:**
Copier 对象

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

获取目标集合。

**Returns:**
DestinationCollection 对象

### getDirection {#getDirection--}
```
Direction getDirection()
```

获取文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。

**Returns:**
Direction 元素

### getDuplex {#getDuplex--}
```
int getDuplex()
```

获取或设置在打印对话框中打印文件时使用的打印双面模式处理选项。

**Returns:**
PrintDuplex 元素

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

获取嵌入文档的文件集合。

**Returns:**
EmbeddedFileCollection 对象

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

声明文档必须嵌入所有标准 Type1 字体的属性，该属性的 IsEmbedded 标志设置为 true。

**Returns:**
布尔值

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

获取或设置用于管理签名字段清理的标志。

**Returns:**
布尔值

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

用于访问内部文档结构的 IPdfDocument 实例。

**Returns:**
IPdfDocument 对象

### getFileName {#getFileName--}
```
String getFileName()
```

导致此文档的 PDF 文件名称

**Returns:**
字符串对象

### getForm {#getForm--}
```
Form getForm()
```

获取文档的 Acro Form。

**Returns:**
Form 对象

### getId {#getId--}
```
Id getId()
```

获取 ID。

**Returns:**
Id 对象

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

获取或设置忽略源文件错误的标志。

**Returns:**
布尔值

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

获取文档信息。

**Returns:**
DocumentInfo 对象

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

获取文档的逻辑结构。

**Returns:**
RootElement 对象

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

文档元数据。

**Returns:**
Metadata 对象

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

返回原始元数据流

**Returns:**
IPdfStreamAccessor 对象

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

文档中命名目标的集合。

**Returns:**
NamedDestinationCollection 实例

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

获取页面模式，指定退出全屏模式时文档的显示方式。

**Returns:**
PageMode 元素

### getObjectById {#getObjectById-java.lang.String-}
获取文档中具有指定 ID 的对象。

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

获取文档打开时执行的操作。

**Returns:**
IAppointment 对象

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

获取优化标志。

**Returns:**
布尔值

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

获取文档大纲。

**Returns:**
OutlineCollection 对象

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

获取页面信息。（仅用于生成器，读取文档时不填充）

**Returns:**
页面信息。

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

获取文档中的页面标签。

**Returns:**
PageLabelCollection 对象

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

获取文档打开时应使用的页面布局。

**Returns:**
PageLayout 元素

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

获取页面模式，指定文档打开时的显示方式。

**Returns:**
PageMode 元素

### getPages {#getPages--}
```
PageCollection getPages()
```

获取文档页面的集合。

**Returns:**
布尔值

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
PdfFormat 元素

### getPermissions {#getPermissions--}
```
int getPermissions()
```

获取文档的权限。

**Returns:**
int 值

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

获取在打印对话框中打印文件时使用的打印缩放处理选项。

**Returns:**
PrintScaling 元素

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

获取对 TaggedPdf 内容的访问。

**Returns:**
ITaggedContent 实例

### getVersion {#getVersion--}
```
String getVersion()
```

获取 PDF 文件头中的 PDF 版本。

**Returns:**
字符串对象

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
获取文档的 XMP 元数据。

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
从 XFDF 文件导入注释到文档。

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

处理文档时缺少字体的通知

**Returns:**
布尔值

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

获取指定文档窗口位置是否居中于屏幕的标志。

**Returns:**
布尔值

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

如果这些操作被该字体的许可证禁止，则许多字体操作无法执行。

**Returns:**
布尔值，默认 false。

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

获取指定文档窗口标题栏是否应显示文档标题的标志。

**Returns:**
布尔值

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

获取文档的加密状态。

**Returns:**
布尔值

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

获取指定文档窗口是否必须调整大小以适应首次显示页面的标志。

**Returns:**
布尔值

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

获取指定文档激活时是否应隐藏菜单栏的标志。

**Returns:**
布尔值

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

获取指定文档激活时是否应隐藏工具栏的标志。

**Returns:**
布尔值

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

获取或设置指定文档激活时是否应隐藏用户界面元素的标志。

**Returns:**
布尔值

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

获取或设置指示文档是否已线性化的值。

**Returns:**
布尔值

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

默认情况下，save 方法会关闭内部流并释放内存资源。如果启用此 ManualDispose 参数，则可以在保存方法后执行一些操作并继续使用文档。

**Returns:**
布尔值。（默认值 == false）

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

获取文档是否符合 PDF/A 标准。

**Returns:**
布尔值

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

获取文档是否符合 PDF/UA 标准。

**Returns:**
布尔值

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

获取指定是否使用 PDF 页面尺寸来选择输入纸盘的标志。

**Returns:**
布尔值

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

获取或设置文档是否符合 PDF/A 标准。

**Returns:**
布尔值

### optimize {#optimize--}
```
void optimize()
```

线性化文档，以便 - 尽快打开首页； - 尽快显示下一页或通过链接跳转到下一页； - 当页面数据通过慢速通道传输时，逐步显示页面（优先显示最有用的数据）； - 允许用户交互，例如点击链接，即使在整个页面尚未接收并显示完毕时也能进行。

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

优化文档中的资源：1。

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
根据定义的优化策略优化文档中的资源。

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

将文档中的页面树节点组织为平衡树。

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

将文档中的页面树节点组织为平衡树。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodesNumInSubtrees |  | 子节点的期望数量。默认值为十。 |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

将文档存储到流中。

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

从文档中移除元数据。

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

从文档中移除 pdfa 合规性

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

从文档中移除 pdfUa 合规性

### repair {#repair--}
```
void repair()
```

修复损坏的文档。

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

增量保存文档（即

### save {#save-java.io.OutputStream-}
将文档存储到流中。

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
保存文档

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
使用新名称保存文档并设置其保存选项。

### save {#save-java.lang.String-}
将文档保存到指定文件中。

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
使用新名称保存文档并设置其保存选项。

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
将 PDF 文档增量保存到指定流中。

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
将 PDF 文档增量保存到指定流中。

### saveIncrementally {#saveIncrementally-java.lang.String-}
将 PDF 文档增量保存到指定流中。

### saveXml {#saveXml-java.lang.String-}
将文档保存为 XML。

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
将文档的特定页面发送到文档设备进行处理。

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
将整个文档发送到文档设备进行处理。

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
将整个文档发送到文档设备进行处理。

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
将整个文档发送到文档设备进行处理。

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

设置标志，以在缺少字体时使用程序确定的字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | 布尔值 |

### setBackground {#setBackground-java.awt.Color-}
设置文档的背景颜色。

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

设置标志，指定文档窗口的位置是否居中显示在屏幕上。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
设置文档的集合。

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

获取 pdf/ua 转换器的转换参数（如果设置为 true，则仅转换元数据和文档目录）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

如果这些操作被该字体的许可证禁止，则许多字体操作无法执行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值，默认 false。 |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

设置标志，指定文档窗口标题栏是否应显示文档标题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

获取或设置在打印对话框中打印文件时使用的打印双面模式处理选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | PrintDuplex 元素 |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

声明文档必须嵌入所有标准 Type1 字体的属性，该属性的 IsEmbedded 标志设置为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

获取或设置用于管理签名字段清理的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

设置标志，指定文档窗口是否必须调整大小以适应首次显示的页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

设置标志，指定文档激活时是否隐藏菜单栏。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

设置标志，指定文档激活时是否隐藏工具栏。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

设置标志，指定文档激活时是否隐藏用户界面元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

设置一个值，指示文档是否已线性化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

默认情况下，save 方法会关闭内部流并释放内存资源。如果启用了 ManualDispose 参数，我们仍然可以在调用 save 方法后执行一些操作并继续使用文档。但强烈建议在不再需要 Document 实例时调用 dispose 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| manualDisposeEnabled |  | 布尔值。（默认值 == false） |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
设置页面模式，指定在退出全屏模式时如何显示文档。

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
设置文档打开时执行的操作。

### setOptimizeSize {#setOptimizeSize-boolean-}
```
void setOptimizeSize(boolean value)
```

设置优化标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
设置页面信息。（仅用于生成器，在读取文档时不填充）

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
设置在打开文档时应使用的页面布局。

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
设置页面模式，指定打开时文档应如何显示。

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
void setPickTrayByPdfSize(boolean value)
```

设置标志，指定是否应使用 PDF 页面大小来选择输入纸盘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

设置在打印对话框中打印文件时使用的打印缩放处理选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | PrintDuplex 元素 |

### setTitle {#setTitle-java.lang.String-}
设置 Pdf 文档的标题

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
设置文档的 XMP 元数据。

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

获取或设置文档是否符合 PDF/A 标准。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
将文档验证到指定的文件中。

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
将文档验证到指定的文件中。
