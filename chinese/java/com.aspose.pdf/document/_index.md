---
title: "文档"
linktitle: "文档"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档的类。"
type: docs
weight: 1060
url: /zh/java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Document

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class Document extends Object implements IDocument
```

表示 PDF 文档的类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | 当文档中的字体被另一个字体替换时会发生此情况。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Document](#Document--) | 初始化空文档。 |
| [Document](#Document-byte:A-) | 从 {@code input} 字节数组初始化新的 Document 实例。 |
| [Document](#Document-java.io.InputStream-) | 初始化空文档。 |
| [Document](#Document-java.io.InputStream-boolean-) | 初始化空文档。 |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | 初始化空文档。 |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | 初始化空文档。 |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | 初始化空文档。 |
| [Document](#Document-java.io.InputStream-java.lang.String-) | 初始化空文档。 |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-) | 初始化空文档。 |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 初始化空文档。 |
| [Document](#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 初始化空文档。 |
| [Document](#Document-com.aspose.pdf.PdfVersion-) | 初始化空文档。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-) | 初始化空文档。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-) | 初始化空文档。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | 初始化空文档。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 初始化空文档。 |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-boolean-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-java.lang.String-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-java.lang.String-boolean-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 初始化空文档。 |
| [Document](#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 初始化空文档。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [afterImport](#afterImport--) | 枚举所有已注册的注释并为每个调用 AfterImport。 |
| [bindXml](#bindXml-java.io.InputStream-) | 将 xml 绑定到文档 |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | 将 xml/xsl 绑定到文档 |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | 将 xml/xsl 绑定到文档 |
| [bindXml](#bindXml-java.lang.String-) | 将 xml 绑定到文档 |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | 将 xml/xsl 绑定到文档 |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | 更改文档密码。此操作只能使用所有者密码完成。 |
| [check](#check-boolean-) | 验证文档。 |
| [close](#close--) | 关闭此文档使用的所有资源。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | 识别文档中的图像并在其上添加 hocr 字符串。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | 通过应用 Fixup 转换文档。 |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | 通过应用 Fixup 转换文档。 |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | 通过应用 Fixup 转换文档。 |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | 通过应用 Fixup 转换文档。 |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 将源格式的流转换为目标格式的流。 |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | 将源格式的流转换为目标格式的目标文件。 |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 转换文档并将错误保存到指定的流中。 |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | 使用指定的转换选项转换文档 |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | 将源格式的源文件转换为目标格式的流。 |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | 将源格式的源文件转换为目标格式的目标文件。 |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 将文档转换并将错误保存到指定文件。 |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | 将文档转换并将错误保存到指定文件。 |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 转换文档并将错误保存到指定的流中。 |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | 将页面转换为 PNG，以用于 DSR、OMR、OCR 图像流。 |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | 将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。 |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | 将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。 |
| [decrypt](#decrypt--) | 解密文档。随后调用 Save 以获取文档的解密版本。 |
| [dispose](#dispose--) | 关闭此文档使用的所有资源。此方法已过时，请改用 close()。 |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | 加密文档。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | 加密文档。随后调用 Save 以获取文档的加密版本。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 加密文档。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | 加密文档。随后调用 Save 以获取文档的加密版本。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | 加密文档。随后调用 Save 以获取文档的加密版本。 |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | 加密文档。 |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | 将所有文档注释导出到流中。 |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | 将所有文档注释导出为 XFDF 文件 |
| [flatten](#flatten--) | 从文档中移除所有字段（以及注释），并用它们的值替代。 |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | 从文档中移除所有字段（以及注释），并用它们的值替代。 |
| [flattenTransparency](#flattenTransparency--) | 将透明内容替换为非透明的光栅和矢量图形。 |
| [freeMemory](#freeMemory--) | 清除内存 |
| [getAbsentFontHandler](#getAbsentFontHandler--) | 处理文档时缺少字体的通知。 |
| [getActions](#getActions--) | <p> 获取文档操作。此属性是 DocumentActions 类的实例，允许获取/设置 BeforClosing、BeforSaving 等操作。 </p> |
| [getAllowReusePageContent](#getAllowReusePageContent--) | 允许合并页面内容以优化文档大小。 |
| [getBackground](#getBackground--) | 获取文档的背景颜色。 |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | 返回目录字典中的项目值。 |
| [getCollection](#getCollection--) | 获取文档集合。 |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | 获取文档加密时的安全设置。如果文档未加密，则在 .net 1.1 中会抛出相应异常，其他 .net 版本中 CryptoAlgorithm 将为 null。 |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | 获取自定义安全处理程序。 |
| [getDefaultCopier](#getDefaultCopier--) | 返回用于将页面复制到此文档的复制器。 |
| [getDestinations](#getDestinations--) | 获取目标集合。 |
| [getDirection](#getDirection--) | 获取文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [getDuplex](#getDuplex--) | 获取或设置在打印对话框中打印文件时使用的打印双面模式处理选项。 |
| [getEmbeddedFiles](#getEmbeddedFiles--) | 获取嵌入文档的文件集合。 |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | 声明文档必须嵌入所有标准 Type1 字体的属性，该属性的 IsEmbedded 标志设置为 true。 |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | 获取或设置用于管理签名字段清理的标志。 |
| [getEngineDoc](#getEngineDoc--) | 用于访问内部文档结构的 IPdfDocument 实例。仅限内部使用。 |
| [getFileName](#getFileName--) | 导致此文档的 PDF 文件名称 |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | 获取和设置将整个文件加载到内存中的文件大小限制。 |
| [getFontUtilities](#getFontUtilities--) | IDocumentFontUtilities 实例 |
| [getForm](#getForm--) | 获取文档的 Acro Form。 |
| [getId](#getId--) | 获取 ID。 |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | 获取或设置在源文件中忽略错误的标志。当从源文档复制页面到目标文档时，如果该标志为 false 且源文件中的某些对象损坏，复制过程将因异常而停止。例如：dest.Pages.Add(src.Pages); 如果将此标志设为 true，则损坏的对象将被替换为空值。默认值：true。 |
| [getInfo](#getInfo--) | 获取文档信息。 |
| [getJavaScript](#getJavaScript--) | 文档级别的 JavaScript 集合。 |
| [getLogicalStructure](#getLogicalStructure--) | 获取文档的逻辑结构。 |
| [getMetadata](#getMetadata--) | 文档元数据。（PDF 文档可能包含一般信息，例如文档的标题、作者以及创建和修改日期。这类关于文档的全局信息（区别于其内容或结构）称为元数据，旨在帮助在外部数据库中对文档进行编目和检索。） |
| [getMetadataStream](#getMetadataStream--) | 返回原始元数据流 |
| [getNamedDestinations](#getNamedDestinations--) | 文档中命名目标的集合。 |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | 获取页面模式，指定退出全屏模式时文档的显示方式。 |
| [getObjectById](#getObjectById-java.lang.String-) | 获取文档中具有指定 ID 的对象。 |
| [getOpenAction](#getOpenAction--) | <p> 获取文档打开时执行的操作。 </p> <hr> <pre> 示例演示如何获取 CenterWindow 标志：Document document = new Document(\"sample.pdf\"); IAppointment value = document.getOpenAction(); </pre> |
| [getOptimizeSize](#getOptimizeSize--) | 获取优化标志。当向文档添加页面时，如果设置了此标志，结果文件中相同的资源流将合并为一个 PDF 对象。这可以减小结果文件的大小，但可能导致执行变慢和内存需求增大。默认值：false。 |
| [getOutlines](#getOutlines--) | 获取文档大纲。 |
| [getOutputIntents](#getOutputIntents--) | 获取文档中 Output intents 的集合。 |
| [getPageInfo](#getPageInfo--) | 获取页面信息。（仅用于生成器，读取文档时不填充） |
| [getPageLabels](#getPageLabels--) | 获取文档中的页面标签。 |
| [getPageLayout](#getPageLayout--) | 获取文档打开时应使用的页面布局。 |
| [getPageMode](#getPageMode--) | 获取页面模式，指定文档打开时的显示方式。 |
| [getPages](#getPages--) | <p> 获取文档页面的集合。请注意，集合中的页面编号从 1 开始。 </p> |
| [getPdfFormat](#getPdfFormat--) | 获取 PDF/A 格式 |
| [getPermissions](#getPermissions--) | 获取文档的权限。 |
| [getPrintScaling](#getPrintScaling--) | 获取在打印对话框中打印文件时使用的打印缩放处理选项。 |
| [getTaggedContent](#getTaggedContent--) | 获取对 TaggedPdf 内容的访问。示例演示如何使用标记内容创建包含标题、段落和图像的新文档。 // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage(\"en-US\"); // Set title for PDF document taggedContent.setTitle(\"Example document\"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText(\"The Header\"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag(\"Paragraph\"); p.setText(\"The text of paragraph.\"); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText(\"Figure 1\"); figure1.setTitle(\"Image 1\"); figure1.setTag(\"Fig\"); figure1.setImage(\"path/of/image.jpg\"); // Save document document.save(\"example.pdf\"); |
| [getVersion](#getVersion--) | 获取 PDF 文件头中的 PDF 版本。 |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | 获取文档的 XMP 元数据。 |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | 检查当前 PDF 文档是否已使用增量更新保存。 |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | 从流导入注释到文档。 |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | 从 XFDF 文件导入注释到文档。 |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | 指示缺失字体替换的标志。 |
| [isCenterWindow](#isCenterWindow--) | <p> 获取指定文档窗口位置是否居中显示在屏幕上的标志。 </p> |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | 如果这些操作被该字体的许可证禁止，则许多字体操作无法执行。 |
| [isDisplayDocTitle](#isDisplayDocTitle--) | <p> 获取标志，指定文档窗口标题栏是否应显示文档标题。 </p> |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | 获取或设置一个值，指示是否启用通知日志记录。 |
| [isEnableObjectUnload](#isEnableObjectUnload--) | 获取或设置标志，以启用文档在内存中部分卸载。 |
| [isEncrypted](#isEncrypted--) | 获取文档的加密状态。如果文档已加密则为 true。 |
| [isFitWindow](#isFitWindow--) | <p> 获取标志，指定文档窗口是否必须调整大小以适应首次显示的页面。 </p> |
| [isHandleSignatureChange](#isHandleSignatureChange--) | 如果文档在保存时包含更改且具有签名，则抛出异常。 |
| [isHideMenubar](#isHideMenubar--) | <p> 获取标志，指定文档激活时是否应隐藏菜单栏。 </p> |
| [isHideToolBar](#isHideToolBar--) | <p> 获取标志，指定文档激活时是否应隐藏工具栏。 </p> |
| [isHideWindowUI](#isHideWindowUI--) | <p> 获取标志，指定文档激活时是否应隐藏用户界面元素。 </p> |
| [isLicensed](#isLicensed--) | 获取系统的授权状态。 |
| [isLinearized](#isLinearized--) | 获取一个值，指示文档是否已线性化。 |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | 默认情况下，save 方法会关闭内部流并释放内存资源。如果启用了此 ManualDispose 参数，则可以在调用 save 方法后执行一些操作并继续使用文档。 |
| [isPdfaCompliant](#isPdfaCompliant--) | 获取文档是否符合 PDF/A 标准。 |
| [isPdfUaCompliant](#isPdfUaCompliant--) | 获取文档是否符合 PDF/UA 标准。 |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | 获取指定是否使用 PDF 页面尺寸来选择输入纸盘的标志。 |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | 检查文档是否需要调用 Repair 方法。 |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | 默认情况下，PDF/A 验证过程是必要的，以在某些规则被破坏时更新或移除 PDF/A 合规数据。 |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | 获取或设置文档是否符合 PDF/A 标准。 |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | 加载文件并将其转换为 PDF。 |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | 合并文档。 |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | 合并文档。 |
| [merge](#merge-com.aspose.pdf.Document...-) | 合并文档。 |
| [merge](#merge-java.lang.String...-) | 合并 PDF 文件。 |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | 合并文档。 |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | 合并文档。 |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | 合并文档。 |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | 合并 PDF 文件。 |
| [optimize](#optimize--) | 线性化文档，以实现以下目标：- 尽快打开首页；- 尽快显示下一页或通过链接跳转到下一页；- 当页面数据通过慢速通道分段传输时，逐步增量显示页面（优先显示最有用的数据）；- 允许用户交互，例如点击链接，即使在整个页面尚未完全接收和显示之前也能进行。调用此方法并不会实际保存文档。相反，文档仅被准备为优化的结构，随后调用 Save 以获取优化后的文档。 |
| [optimizeResources](#optimizeResources--) | 优化文档中的资源：1. 删除文档页面未使用的资源；2. 将相同的资源合并为一个对象；3. 删除未使用的对象。 |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | 优化文档中的资源：1. 删除文档页面未使用的资源；2. 将相同的资源合并为一个对象；3. 删除未使用的对象。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | 将文档中的页面树节点组织为平衡树。仅当文档的页面对象数量超过 nodesNumInSubtrees 时才执行，否则不进行任何操作。 |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | 将文档中的页面树节点组织为平衡树。仅当文档的页面对象数量超过 nodesNumInSubtrees 时才执行，否则不进行任何操作。 |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | 内部方法 |
| [processParagraphs](#processParagraphs--) | 将文档存储到流中。 |
| [removeMetadata](#removeMetadata--) | 从文档中移除元数据。 |
| [removePdfaCompliance](#removePdfaCompliance--) | 从文档中移除 pdfa 合规性 |
| [removePdfUaCompliance](#removePdfUaCompliance--) | 从文档中移除 pdfUa 合规性 |
| [repair](#repair--) | 修复损坏的文档。 |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | 修复损坏的文档。 |
| [resumeUpdate](#resumeUpdate--) | 恢复文档更新 |
| [save](#save--) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [save](#save-java.io.OutputStream-) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [save](#save-com.aspose.pdf.SaveOptions-) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [save](#save-com.aspose.ms.System.IO.Stream-) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [save](#save-java.lang.String-) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | <p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。 |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | 将 PDF 文档增量保存到指定流中。 |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | 将 PDF 文档增量保存到指定流中。 |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | 将 PDF 文档增量保存到指定流中。 |
| [saveXml](#saveXml-java.lang.String-) | 将文档保存为 XML。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | 将文档的特定页面发送到文档设备进行处理。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | 将整个文档发送到文档设备进行处理。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | 将整个文档发送到文档设备进行处理。 |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | 将整个文档发送到文档设备进行处理。 |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | 处理文档时缺少字体的通知。 |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | 设置标志，以在缺少字体时使用程序确定的字体。 |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | 允许合并页面内容以优化文档大小。 |
| [setBackground](#setBackground-java.awt.Color-) | 设置文档的背景颜色。 |
| [setCenterWindow](#setCenterWindow-boolean-) | 设置标志，指定文档窗口的位置是否在屏幕上居中。 |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | 设置文档的集合。 |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | 获取 pdf/ua 转换器的转换参数（如果设置为 true，则仅转换元数据和文档目录） |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | 将加载整个文件到内存的文件大小限制设置为默认值 210 Mb。 |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | 设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | 如果这些操作被该字体的许可证禁止，则许多字体操作无法执行。 |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | 设置标志，指定文档窗口标题栏是否应显示文档标题。 |
| [setDuplex](#setDuplex-int-) | 获取或设置在打印对话框中打印文件时使用的打印双面模式处理选项。 |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | 声明文档必须嵌入所有标准 Type1 字体的属性，该属性的 IsEmbedded 标志设置为 true。 |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | 获取或设置一个值，指示是否启用通知日志记录。 |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | 获取或设置标志，以启用文档在内存中部分卸载。 |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | 获取或设置用于管理签名字段清理的标志。 |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | 获取和设置将整个文件加载到内存中的文件大小限制。 |
| [setFitWindow](#setFitWindow-boolean-) | 设置标志，指定文档窗口是否必须调整大小以适应首次显示的页面。 |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | 如果文档在保存时包含更改且具有签名，则抛出异常。 |
| [setHideMenubar](#setHideMenubar-boolean-) | 设置标志，指定文档激活时是否隐藏菜单栏。 |
| [setHideToolBar](#setHideToolBar-boolean-) | 设置标志，指定文档激活时是否隐藏工具栏。 |
| [setHideWindowUI](#setHideWindowUI-boolean-) | 设置标志，指定文档激活时是否隐藏用户界面元素。 |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | 获取或设置在源文件中忽略错误的标志。当从源文档复制页面到目标文档时，如果该标志为 false 且源文件中的某些对象损坏，复制过程将因异常而停止。例如：dest.Pages.Add(src.Pages); 如果将此标志设为 true，则损坏的对象将被替换为空值。默认值：true。 |
| [setLinearized](#setLinearized-boolean-) | 设置一个值，指示文档是否已线性化。 |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | 默认情况下，method save 关闭内部流并释放内存资源。如果启用了 ManualDispose 参数，我们可以在调用 method save 后执行一些操作并继续使用文档。但强烈建议在不再需要 Document 实例时调用 dispose 方法。 |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | 设置页面模式，指定在退出全屏模式时如何显示文档。 |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | <p> 设置在文档打开时执行的操作。 <p> |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 设置优化标志。当页面添加到文档时，如果设置了此标志，结果文件中相等的资源流将合并为一个 PDF 对象。这可以减小结果文件大小，但可能导致执行速度变慢且需要更多内存。默认值：false。 |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置页面信息。（仅用于生成器，在读取文档时不填充） |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | 设置在打开文档时应使用的页面布局。 |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | 设置页面模式，指定打开时文档应如何显示。 |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | 设置标志，指定是否应使用 PDF 页面大小来选择输入纸盘。 |
| [setPrintScaling](#setPrintScaling-int-) | 设置在打印对话框中打印文件时使用的打印缩放处理选项。 |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | 默认情况下，如果违反某些规则，需要进行 pdfa 验证过程来更新或移除 pdfa。 |
| [setTitle](#setTitle-java.lang.String-) | 设置 Pdf 文档的标题 |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | 设置文档的 XMP 元数据。 |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | 获取或设置文档是否符合 PDF/A 标准。 |
| [suppressUpdate](#suppressUpdate--) | 抑制所有页面的内容数据更新。内容将在调用 ResumeUpdate 之前不会更新。 |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | 将文档验证到指定的文件中。 |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | 将文档验证到指定的文件中。 |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | 将文档验证到指定的文件中。 |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

当文档中的字体被另一个字体替换时会发生此情况。

### Document {#Document--}
```
public Document()
```

初始化空文档。

### Document {#Document-byte:A-}
```
public Document(byte[] input)
```

从 {@code input} 字节数组初始化新的 Document 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 |  | 包含 pdf 文档的字节数组。 |

### Document {#Document-java.io.InputStream-}
初始化空文档。

### Document {#Document-java.io.InputStream-boolean-}
初始化空文档。

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
初始化空文档。

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
初始化空文档。

### Document {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
初始化空文档。

### Document {#Document-java.io.InputStream-java.lang.String-}
初始化空文档。

### Document {#Document-java.io.InputStream-java.lang.String-boolean-}
初始化空文档。

### Document {#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
初始化空文档。

### Document {#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
初始化空文档。

### Document {#Document-com.aspose.pdf.PdfVersion-}
初始化空文档。

### Document {#Document-com.aspose.ms.System.IO.Stream-}
初始化空文档。

### Document {#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-}
初始化空文档。

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
初始化空文档。

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
初始化空文档。

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
初始化空文档。

### Document {#Document-java.lang.String-}
初始化空文档。

### Document {#Document-java.lang.String-boolean-}
初始化空文档。

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
初始化空文档。

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
初始化空文档。

### Document {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
初始化空文档。

### Document {#Document-java.lang.String-java.lang.String-}
初始化空文档。

### Document {#Document-java.lang.String-java.lang.String-boolean-}
初始化空文档。

### Document {#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
初始化空文档。

### Document {#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
初始化空文档。

### afterImport {#afterImport--}
```
public void afterImport()
```

枚举所有已注册的注释并为每个调用 AfterImport。

### bindXml {#bindXml-java.io.InputStream-}
将 xml 绑定到文档

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
将 xml/xsl 绑定到文档

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
将 xml/xsl 绑定到文档

### bindXml {#bindXml-java.lang.String-}
将 xml 绑定到文档

### bindXml {#bindXml-java.lang.String-java.lang.String-}
将 xml/xsl 绑定到文档

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
更改文档密码。此操作只能使用所有者密码完成。

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
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
public void close()
```

关闭此文档使用的所有资源。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
识别文档中的图像并在其上添加 hocr 字符串。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
将文档转换并将错误保存到指定文件。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
将文档转换并将错误保存到指定文件。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
将文档转换并将错误保存到指定文件。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
将文档转换并将错误保存到指定文件。

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
将文档转换并将错误保存到指定文件。

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
通过应用 Fixup 转换文档。

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
通过应用 Fixup 转换文档。

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
通过应用 Fixup 转换文档。

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
通过应用 Fixup 转换文档。

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
将源格式的流转换为目标格式的流。

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
将源格式的流转换为目标格式的目标文件。

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
转换文档并将错误保存到指定的流中。

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
将文档转换并将错误保存到指定文件。

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
使用指定的转换选项转换文档

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
将源格式的源文件转换为目标格式的流。

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
将源格式的源文件转换为目标格式的目标文件。

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
将文档转换并将错误保存到指定文件。

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
将文档转换并将错误保存到指定文件。

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
转换文档并将错误保存到指定的流中。

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
将页面转换为 PNG，以用于 DSR、OMR、OCR 图像流。

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
将文档转换为可搜索文档，并跳过无法转换的 hochr 错误。

### decrypt {#decrypt--}
```
public void decrypt()
```

解密文档。随后调用 Save 以获取文档的解密版本。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

关闭此文档使用的所有资源。此方法已过时，请改用 close()。

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
加密文档。

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
加密文档。随后调用 Save 以获取文档的加密版本。

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
加密文档。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
加密文档。随后调用 Save 以获取文档的加密版本。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
加密文档。随后调用 Save 以获取文档的加密版本。

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
加密文档。

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
将所有文档注释导出到流中。

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
将所有文档注释导出为 XFDF 文件

### flatten {#flatten--}
```
public void flatten()
```

从文档中移除所有字段（以及注释），并用它们的值替代。

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
从文档中移除所有字段（以及注释），并用它们的值替代。

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

将透明内容替换为非透明的光栅和矢量图形。

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

清除内存

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

处理文档时缺少字体的通知。

**Returns:**
ADocument.AbsentFontHandler 实例

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

<p> 获取文档操作。此属性是 DocumentActions 类的实例，允许获取/设置 BeforClosing、BeforSaving 等操作。 </p>

**Returns:**
DocumentActionCollection object <hr> <pre> 此示例演示如何获取文档的打开后操作： Document document = new Document(\"PdfWithOpenAction.pdf\"); DocumentActionCollection actions = document.getActions(); PdfAction afterSavingAction = actions.getAfterSaving(); </pre>

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

允许合并页面内容以优化文档大小。

**Returns:**
value 布尔值

### getBackground {#getBackground--}
```
public Color getBackground()
```

获取文档的背景颜色。

**Returns:**
Color 对象

### getCatalogValue {#getCatalogValue-java.lang.String-}
返回目录字典中的项目值。

### getCollection {#getCollection--}
```
public Collection getCollection()
```

获取文档集合。

**Returns:**
Collection 对象

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

获取文档加密时的安全设置。如果文档未加密，则在 .net 1.1 中会抛出相应异常，其他 .net 版本中 CryptoAlgorithm 将为 null。

**Returns:**
CryptoAlgorithm 元素 @see CryptoAlgorithm

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public final com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

获取自定义安全处理程序。

**Returns:**
ICustomSecurityHandler 实例

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

返回用于将页面复制到此文档的复制器。

**Returns:**
Copier 对象

### getDestinations {#getDestinations--}
```
public DestinationCollection getDestinations()
```

获取目标集合。

**Returns:**
DestinationCollection 元素

### getDirection {#getDirection--}
```
public Direction getDirection()
```

获取文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。

**Returns:**
Direction 元素 @see Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

获取或设置在打印对话框中打印文件时使用的打印双面模式处理选项。

**Returns:**
PrintDuplex 元素

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

获取嵌入文档的文件集合。

**Returns:**
EmbeddedFileCollection 对象

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

声明文档必须嵌入所有标准 Type1 字体的属性，该属性的 IsEmbedded 标志设置为 true。

**Returns:**
布尔值

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

获取或设置用于管理签名字段清理的标志。

**Returns:**
布尔值

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

用于访问内部文档结构的 IPdfDocument 实例。仅限内部使用。

**Returns:**
IPdfDocument 对象

### getFileName {#getFileName--}
```
public String getFileName()
```

导致此文档的 PDF 文件名称

**Returns:**
字符串对象

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

获取和设置将整个文件加载到内存中的文件大小限制。

**Returns:**
int 值

### getFontUtilities {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```

IDocumentFontUtilities 实例

**Returns:**
IDocumentFontUtilities 实例

### getForm {#getForm--}
```
public Form getForm()
```

获取文档的 Acro Form。

**Returns:**
Form 对象

### getId {#getId--}
```
public Id getId()
```

获取 ID。

**Returns:**
Id 对象

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

获取或设置在源文件中忽略错误的标志。当从源文档复制页面到目标文档时，如果该标志为 false 且源文件中的某些对象损坏，复制过程将因异常而停止。例如：dest.Pages.Add(src.Pages); 如果将此标志设为 true，则损坏的对象将被替换为空值。默认值：true。

**Returns:**
布尔值

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

获取文档信息。

**Returns:**
DocumentInfo 对象

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

文档级别的 JavaScript 集合。

**Returns:**
JavaScriptCollection 对象

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

获取文档的逻辑结构。

**Returns:**
RootElement 对象

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

文档元数据。（PDF 文档可能包含一般信息，例如文档的标题、作者以及创建和修改日期。这类关于文档的全局信息（区别于其内容或结构）称为元数据，旨在帮助在外部数据库中对文档进行编目和检索。）

**Returns:**
Metadata 对象

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

返回原始元数据流

**Returns:**
IPdfStreamAccessor 对象

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

文档中命名目标的集合。

**Returns:**
NamedDestinationCollection 实例

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

获取页面模式，指定退出全屏模式时文档的显示方式。

**Returns:**
PageMode 元素 @see PageMode

### getObjectById {#getObjectById-java.lang.String-}
获取文档中具有指定 ID 的对象。

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

<p> 获取文档打开时执行的操作。 </p> <hr> <pre> 示例演示如何获取 CenterWindow 标志：Document document = new Document(\"sample.pdf\"); IAppointment value = document.getOpenAction(); </pre>

**Returns:**
IAppointment 对象

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

获取优化标志。当向文档添加页面时，如果设置了此标志，结果文件中相同的资源流将合并为一个 PDF 对象。这可以减小结果文件的大小，但可能导致执行变慢和内存需求增大。默认值：false。

**Returns:**
布尔值

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

获取文档大纲。

**Returns:**
OutlineCollection 对象

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

获取文档中 Output intents 的集合。

**Returns:**
OutputIntents 实例

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

获取页面信息。（仅用于生成器，读取文档时不填充）

**Returns:**
页面信息。

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

获取文档中的页面标签。

**Returns:**
PageLabelCollection 对象

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

获取文档打开时应使用的页面布局。

**Returns:**
PageLayout 元素 @see PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

获取页面模式，指定文档打开时的显示方式。

**Returns:**
PageMode 元素 @see PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

<p> 获取文档页面的集合。请注意，集合中的页面编号从 1 开始。 </p>

**Returns:**
PageCollection object <hr> <pre> 以下示例演示如何操作文档页面：如何获取页面数量以及如何获取文档起始页的矩形。 Document document = new Document(\"sample.pdf\"); PageCollection pages = document.getPages(); System.out.println(\"Document contains \" + pages.size()); Page page = pages.get_Item(1); Rectangle rect = page.getRect(); </pre>

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

获取 PDF/A 格式

**Returns:**
PdfFormat 元素 @see PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

获取文档的权限。

**Returns:**
int 值

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

获取在打印对话框中打印文件时使用的打印缩放处理选项。

**Returns:**
PrintScaling 元素

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```

获取对 TaggedPdf 内容的访问。示例演示如何使用标记内容创建包含标题、段落和图像的新文档。 // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage(\"en-US\"); // Set title for PDF document taggedContent.setTitle(\"Example document\"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText(\"The Header\"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag(\"Paragraph\"); p.setText(\"The text of paragraph.\"); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText(\"Figure 1\"); figure1.setTitle(\"Image 1\"); figure1.setTag(\"Fig\"); figure1.setImage(\"path/of/image.jpg\"); // Save document document.save(\"example.pdf\");

**Returns:**
ITaggedContent 实例

### getVersion {#getVersion--}
```
public String getVersion()
```

获取 PDF 文件头中的 PDF 版本。

**Returns:**
字符串值

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
获取文档的 XMP 元数据。

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

检查当前 PDF 文档是否已使用增量更新保存。

**Returns:**
如果 PDF 文档具有增量更新则为 true；否则为 false。

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
从流导入注释到文档。

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
从 XFDF 文件导入注释到文档。

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

指示缺失字体替换的标志。

**Returns:**
布尔值

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

<p> 获取指定文档窗口位置是否居中显示在屏幕上的标志。 </p>

**Returns:**
boolean value <hr> <pre> 示例演示如何获取 CenterWindow 标志： Document document = new Document(\"sample.pdf\"); boolean value = document.isCenterWindow(); </pre>

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

如果这些操作被该字体的许可证禁止，则许多字体操作无法执行。

**Returns:**
布尔值，默认 false。

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

<p> 获取标志，指定文档窗口标题栏是否应显示文档标题。 </p>

**Returns:**
boolean value <hr> <pre> 示例演示如何获取 DisplayDocTitle 标志： Document document = new Document(\"sample.pdf\"); boolean value = document.isDisplayDocTitle(); </pre>

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

获取或设置一个值，指示是否启用通知日志记录。

**Returns:**
布尔值

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

获取或设置标志，以启用文档在内存中部分卸载。

**Returns:**
布尔值

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

获取文档的加密状态。如果文档已加密则为 true。

**Returns:**
布尔值

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

<p> 获取标志，指定文档窗口是否必须调整大小以适应首次显示的页面。 </p>

**Returns:**
boolean value <hr> <pre> 示例演示如何获取 FitWindow 标志： Document document = new Document(\"sample.pdf\"); boolean value = document.isFitWindow(); </pre>

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

如果文档在保存时包含更改且具有签名，则抛出异常。

**Returns:**
布尔值

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

<p> 获取标志，指定文档激活时是否应隐藏菜单栏。 </p>

**Returns:**
boolean value <hr> <pre> 示例演示如何获取 HideMenubar 标志： Document document = new Document(\"sample.pdf\"); boolean value = document.isHideMenubar(); </pre>

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

<p> 获取标志，指定文档激活时是否应隐藏工具栏。 </p>

**Returns:**
布尔值 <hr> <pre> 示例演示如何获取 HideToolBar 标志: Document document = new Document("sample.pdf"); boolean value = document.isHideToolBar(); </pre>

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

<p> 获取标志，指定文档激活时是否应隐藏用户界面元素。 </p>

**Returns:**
布尔值 <hr> <pre> 示例演示如何获取 HideWindowUI 标志: Document document = new Document("sample.pdf"); boolean value = document.isHideWindowUI(); </pre>

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

获取系统的授权状态。

**Returns:**
布尔值

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

获取一个值，指示文档是否已线性化。

**Returns:**
布尔值

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

默认情况下，save 方法会关闭内部流并释放内存资源。如果启用了此 ManualDispose 参数，则可以在调用 save 方法后执行一些操作并继续使用文档。

**Returns:**
布尔值。（默认值 == false）

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

获取文档是否符合 PDF/A 标准。

**Returns:**
布尔值

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

获取文档是否符合 PDF/UA 标准。

**Returns:**
布尔值

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

获取指定是否使用 PDF 页面尺寸来选择输入纸盘的标志。

**Returns:**
布尔值

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
检查文档是否需要调用 Repair 方法。

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

默认情况下，PDF/A 验证过程是必要的，以在某些规则被破坏时更新或移除 PDF/A 合规数据。

**Returns:**
布尔值

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

获取或设置文档是否符合 PDF/A 标准。

**Returns:**
布尔值

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
加载文件并将其转换为 PDF。

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
合并文档。

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
合并文档。

### merge {#merge-com.aspose.pdf.Document...-}
合并文档。

### merge {#merge-java.lang.String...-}
合并 PDF 文件。

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
合并文档。

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
合并文档。

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
合并文档。

### mergeDocuments {#mergeDocuments-java.lang.String...-}
合并 PDF 文件。

### optimize {#optimize--}
```
public void optimize()
```

线性化文档，以实现以下目标：- 尽快打开首页；- 尽快显示下一页或通过链接跳转到下一页；- 当页面数据通过慢速通道分段传输时，逐步增量显示页面（优先显示最有用的数据）；- 允许用户交互，例如点击链接，即使在整个页面尚未完全接收和显示之前也能进行。调用此方法并不会实际保存文档。相反，文档仅被准备为优化的结构，随后调用 Save 以获取优化后的文档。

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

优化文档中的资源：1. 删除文档页面未使用的资源；2. 将相同的资源合并为一个对象；3. 删除未使用的对象。

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
优化文档中的资源：1. 删除文档页面未使用的资源；2. 将相同的资源合并为一个对象；3. 删除未使用的对象。

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

将文档中的页面树节点组织为平衡树。仅当文档的页面对象数量超过 nodesNumInSubtrees 时才执行，否则不进行任何操作。

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

将文档中的页面树节点组织为平衡树。仅当文档的页面对象数量超过 nodesNumInSubtrees 时才执行，否则不进行任何操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodesNumInSubtrees |  | 所需的子节点数量。 |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
内部方法

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

将文档存储到流中。

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

从文档中移除元数据。

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

从文档中移除 pdfa 合规性

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

从文档中移除 pdfUa 合规性

### repair {#repair--}
```
public void repair()
```

修复损坏的文档。

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
修复损坏的文档。

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

恢复文档更新

### save {#save--}
```
public void save()
```

<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

### save {#save-java.io.OutputStream-}
<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

### save {#save-com.aspose.pdf.SaveOptions-}
<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

### save {#save-com.aspose.ms.System.IO.Stream-}
<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

### save {#save-java.lang.String-}
<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
<p> 增量保存文档（即使用增量更新技术）。 </p> <hr> <p> 为了增量保存文档，我们应以写入模式打开文档文件。因此 Document 不应使用 InputStream 初始化，而应使用文件路径，如下代码片段所示：Document doc = new Document(\"document.pdf\"); // 做一些更改并增量保存文档 doc.save(); </p> 如果文档是使用 InputStream 初始化的，则无法向 InputStream 写入，因此我们建议使用单独的方法 \"save\" 来保存文档，或使用 \"saveIncrementally\" 来增量保存文档。

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

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
处理文档时缺少字体的通知。

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

设置标志，以在缺少字体时使用程序确定的字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  |  |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

允许合并页面内容以优化文档大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBackground {#setBackground-java.awt.Color-}
设置文档的背景颜色。

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

设置标志，指定文档窗口的位置是否在屏幕上居中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
设置文档的集合。

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

获取 pdf/ua 转换器的转换参数（如果设置为 true，则仅转换元数据和文档目录）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

将加载整个文件到内存的文件大小限制设置为默认值 210 Mb。

### setDirection {#setDirection-com.aspose.pdf.Direction-}
设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

如果这些操作被该字体的许可证禁止，则许多字体操作无法执行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值，默认 false。 |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

设置标志，指定文档窗口标题栏是否应显示文档标题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

获取或设置在打印对话框中打印文件时使用的打印双面模式处理选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | PrintDuplex 元素 |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

声明文档必须嵌入所有标准 Type1 字体的属性，该属性的 IsEmbedded 标志设置为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

获取或设置一个值，指示是否启用通知日志记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

获取或设置标志，以启用文档在内存中部分卸载。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

获取或设置用于管理签名字段清理的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

获取和设置将整个文件加载到内存中的文件大小限制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

设置标志，指定文档窗口是否必须调整大小以适应首次显示的页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

如果文档在保存时包含更改且具有签名，则抛出异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

设置标志，指定文档激活时是否隐藏菜单栏。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

设置标志，指定文档激活时是否隐藏工具栏。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

设置标志，指定文档激活时是否隐藏用户界面元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

获取或设置在源文件中忽略错误的标志。当从源文档复制页面到目标文档时，如果该标志为 false 且源文件中的某些对象损坏，复制过程将因异常而停止。例如：dest.Pages.Add(src.Pages); 如果将此标志设为 true，则损坏的对象将被替换为空值。默认值：true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

设置一个值，指示文档是否已线性化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

默认情况下，method save 关闭内部流并释放内存资源。如果启用了 ManualDispose 参数，我们可以在调用 method save 后执行一些操作并继续使用文档。但强烈建议在不再需要 Document 实例时调用 dispose 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| manualDisposeEnabled |  | 布尔值。（默认值 == false） |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
设置页面模式，指定在退出全屏模式时如何显示文档。

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
<p> 设置在文档打开时执行的操作。 <p>

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

设置优化标志。当页面添加到文档时，如果设置了此标志，结果文件中相等的资源流将合并为一个 PDF 对象。这可以减小结果文件大小，但可能导致执行速度变慢且需要更多内存。默认值：false。

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
public final void setPickTrayByPdfSize(boolean value)
```

设置标志，指定是否应使用 PDF 页面大小来选择输入纸盘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

设置在打印对话框中打印文件时使用的打印缩放处理选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | PrintDuplex 元素 |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

默认情况下，如果违反某些规则，需要进行 pdfa 验证过程来更新或移除 pdfa。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | 布尔值 |

### setTitle {#setTitle-java.lang.String-}
设置 Pdf 文档的标题

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
设置文档的 XMP 元数据。

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

获取或设置文档是否符合 PDF/A 标准。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

抑制所有页面的内容数据更新。内容将在调用 ResumeUpdate 之前不会更新。

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
将文档验证到指定的文件中。

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
将文档验证到指定的文件中。

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
将文档验证到指定的文件中。
