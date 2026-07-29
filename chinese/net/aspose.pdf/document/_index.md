---
title: "类 Document"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Document 类。表示 PDF 文档的类。"
type: docs
weight: 3900
url: /zh/net/aspose.pdf/document/
---
## Document class

表示 PDF 文档的类。

```csharp
public sealed class Document : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Document](document/#constructor)() | 初始化空文档。 |
| [Document](document/#constructor_1)(PdfVersion) | 按版本初始化空文档。 |
| [Document](document/#constructor_2)(Stream) | 从 *input* 流初始化新的 Document 实例。 |
| [Document](document/#constructor_11)(string) | 仅使用 *filename* 初始化 Document。与 [`Document`](./document/) 相同。 |
| [Document](document/#constructor_6)(Stream, bool) | 从 *input* 流初始化新的 Document 实例。 |
| [Document](document/#constructor_4)(Stream, CertificateEncryptionOptions) | 从 *input* 流初始化新的 Document 实例。 |
| [Document](document/#constructor_3)(Stream, LoadOptions) | 从流中打开现有文档，并提供必要的转换以获取 pdf 文档。 |
| [Document](document/#constructor_7)(Stream, string) | 从 *input* 流初始化新的 Document 实例。 |
| [Document](document/#constructor_15)(string, bool) | 仅使用 *filename* 初始化 Document。与 [`Document`](./document/) 相同。 |
| [Document](document/#constructor_13)(string, CertificateEncryptionOptions) | 初始化 `Document` 类的新实例，以处理加密文档。 |
| [Document](document/#constructor_12)(string, LoadOptions) | 从文件中打开现有文档，并提供必要的转换选项以获取 pdf 文档。 |
| [Document](document/#constructor_16)(string, string) | 初始化 `Document` 类的新实例，以处理加密文档。 |
| [Document](document/#constructor_5)(Stream, CertificateEncryptionOptions, bool) | 从 *input* 流初始化新的 Document 实例。 |
| [Document](document/#constructor_9)(Stream, string, bool) | 从 *input* 流初始化新的 Document 实例。 |
| [Document](document/#constructor_8)(Stream, string, ICustomSecurityHandler) | 从 *input* 流初始化新的 Document 实例。 |
| [Document](document/#constructor_14)(string, CertificateEncryptionOptions, bool) | 初始化 `Document` 类的新实例，以处理加密文档。 |
| [Document](document/#constructor_18)(string, string, bool) | 初始化 `Document` 类的新实例，以处理加密文档。 |
| [Document](document/#constructor_17)(string, string, ICustomSecurityHandler) | 初始化 `Document` 类的新实例，以处理加密文档。 |
| [Document](document/#constructor_10)(Stream, string, bool, ICustomSecurityHandler) | 从 *input* 流初始化新的 Document 实例。 |
| [Document](document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | 初始化 `Document` 类的新实例，以处理加密文档。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | 获取文档操作。此属性是 DocumentActions 类的实例，允许获取/设置 BeforClosing、BeforSaving 等操作。 |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | 允许合并页面内容以优化文档大小。如果使用，则不同但重复的页面可能引用相同的内容对象。请注意，此模式可能导致副作用，例如在更改其他页面时更改页面内容。 |
| [Background](../../aspose.pdf/document/background/) { get; set; } | 获取或设置文档的背景颜色。 |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | 获取或设置标志，指定文档窗口的位置是否居中显示在屏幕上。 |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | 获取文档的集合。 |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | 获取文档加密时的安全设置。如果文档未加密，则在 .net 1.1 中会抛出相应的异常，或在其他 .net 版本中 CryptoAlgorithm 为 null。 |
| [CustomSecurityHandler](../../aspose.pdf/document/customsecurityhandler/) { get; } | 获取自定义安全处理程序。 |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | 获取目标集合。已过时。请使用 NamedDestinations。 |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | 获取或设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | 如果字体许可证禁止某些操作，则许多与字体相关的操作无法执行。例如，如果许可证规则禁用嵌入，则某些字体无法嵌入到 PDF 文档中。此标志用于在当前 PDF 文档中禁用所有字体的任何许可证限制。使用此标志时请谨慎。设置后表示设置此标志的人自行承担可能的许可证/法律违规责任，即自行承担风险。强烈建议仅在完全确信不会侵犯版权法时才使用此标志。默认值为 false。 |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | 获取或设置标志，指定文档窗口标题栏是否应显示文档标题。 |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | 获取或设置在打印对话框中打印文件时使用的双面打印模式处理选项。 |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | 获取嵌入到文档中的文件集合。 |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | 声明文档必须嵌入所有标准 Type1 字体的属性，该属性将标志 IsEmbedded 设置为 true。所有 PDF 字体都可以通过将 IsEmbedded 标志设为 true 来嵌入文档，但 PDF 标准 Type1 字体是例外。嵌入标准 Type1 字体需要较长时间，因此除了为指定字体将 IsEmbedded 标志设为 true 外，还必须在文档级别设置额外的标志 - EmbedStandardFonts = true；此属性只能对所有字体设置一次。默认值为 false。 |
| [EnableNotificationLogging](../../aspose.pdf/document/enablenotificationlogging/) { get; set; } | 获取或设置一个值，指示是否启用通知日志记录。 |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | 获取或设置标志，以允许文档部分从内存中卸载。这可以降低内存使用，但可能对性能产生负面影响。 |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | 获取或设置标志，以管理签名字段的清理。默认启用。 |
| [FileName](../../aspose.pdf/document/filename/) { get; } | 导致此文档的 PDF 文件名称 |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | 获取或设置标志，指定文档窗口是否必须调整大小以适应首次显示的页面。 |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | IDocumentFontUtilities 实例 |
| [Form](../../aspose.pdf/document/form/) { get; } | 获取文档的 Acro 表单。 |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | 如果文档在保存更改后仍包含签名，则抛出异常。 |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | 获取或设置标志，指定文档激活时是否隐藏菜单栏。 |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | 获取或设置标志，指定文档激活时是否隐藏工具栏。 |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | 获取或设置标志，指定文档激活时是否隐藏用户界面元素。 |
| [Id](../../aspose.pdf/document/id/) { get; } | 获取 ID。 |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | 获取或设置在源文件中忽略错误的标志。当将源文档的页面复制到目标文档时，如果源文件中的某些对象损坏且此标志为 false，则复制过程会因异常而停止。例如：dest.Pages.Add(src.Pages); 如果此标志设置为 true，则损坏的对象将被替换为空值。默认值：true。 |
| [Info](../../aspose.pdf/document/info/) { get; } | 获取文档信息。 |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | 获取文档的加密状态。如果文档已加密，则为 true。 |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | 获取或设置指示文档是否已线性化的值。 |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | 获取文档是否符合 PDF/A 标准。 |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | 获取文档是否符合 PDF/UA 标准。 |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | 获取或设置文档是否符合 PDF/A 标准。 |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | 文档级别的 JavaScript 集合。 |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | 获取文档的逻辑结构。 |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | 文档元数据。（PDF 文档可能包含一般信息，例如文档的标题、作者以及创建和修改日期。这类关于文档的全局信息（区别于其内容或结构）称为元数据，旨在帮助在外部数据库中对文档进行编目和搜索。） |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | 文档中命名目标的集合。 |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | 获取或设置页面模式，指定在退出全屏模式时如何显示文档。 |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | 获取或设置文档打开时执行的操作。 |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | 获取或设置优化标志。如果设置此标志，当向文档添加页面时，结果文件中相同的资源流将合并为一个 PDF 对象。这可以减小生成文件的大小，但可能导致执行速度变慢和内存需求增大。默认值：false。 |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | 获取文档大纲。 |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | 获取文档中 Output intents 的集合。 |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | 获取或设置页面信息。（仅用于生成器，读取文档时不填充） |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | 获取文档中的页面标签。 |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | 获取或设置打开文档时使用的页面布局。 |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | 获取或设置页面模式，指定打开文档时应如何显示。 |
| [Pages](../../aspose.pdf/document/pages/) { get; } | 获取或设置文档页面的集合。请注意，集合中的页面编号从 1 开始。 |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | 获取 PDF 格式 |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | 获取文档的权限。 |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | 获取或设置标志，指定是否使用 PDF 页面尺寸来选择输入纸盘。 |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | 获取或设置在为此文档显示打印对话框时应选择的页面缩放选项。 |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | 获取对 TaggedPdf 内容的访问。 |
| [Version](../../aspose.pdf/document/version/) { get; } | 获取 Pdf 文件头中的 Pdf 版本。 |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | 获取并设置将整个文件加载到内存中的文件大小限制。该值以兆字节为单位。默认值为 210 Mb。 |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | 获取系统的授权状态。如果系统在授权模式下工作则返回 true，否则返回 false。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | 合并文档。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | 合并 pdf 文件。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | 合并文档。 |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | 合并文档。 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | 将 xml 绑定到文档 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | 将 xml 绑定到文档 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | 将 xml/xsl 绑定到文档 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | 将 xml/xsl 绑定到文档 |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | 将 xml/xsl 绑定到文档 |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | 更改文档密码。此操作只能使用所有者密码完成。 |
| [Check](../../aspose.pdf/document/check/)(bool) | 验证文档。 |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | 使用指定的转换选项转换文档 |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | 识别文档中的图像并在其上添加 hocr 字符串。 |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | 识别文档中的图像并在其上添加 hocr 字符串。 |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | 转换文档并将错误保存到指定的流中。 |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | 转换文档并将错误保存到指定的文件中。 |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | 通过应用 Fixup 转换文档。 |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | 通过应用 Fixup 转换文档。 |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 转换文档并将错误保存到指定的文件中。 |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 转换文档并将错误保存到指定的文件中。 |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | 将页面转换为 PNG，以用于 DSR、OMR、OCR 图像流。 |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | 解密文档。调用 Save 以获取文档的解密版本。 |
| [Dispose](../../aspose.pdf/document/dispose/)() | 关闭此文档使用的所有资源。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) | 加密文档。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, DocumentPrivilege, ICustomSecurityHandler) | 加密文档。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_3)(string, string, Permissions, CryptoAlgorithm) | 加密文档。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_5)(string, string, Permissions, ICustomSecurityHandler) | 加密文档。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | 加密文档。 |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_4)(string, string, Permissions, CryptoAlgorithm, bool) | 加密文档。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | 将所有文档注释导出到流中。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | 将所有文档注释导出到 XFDF 文件。 |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | 从文档中移除所有字段并用其值替代。 |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | 从文档中移除所有字段（以及注释），并用其值替代。 |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | 将透明内容替换为非透明的光栅和矢量图形。 |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | 清除内存 |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | 从目录字典返回项的值。 |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | 获取文档中具有指定 ID 的对象。 |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | 从文档获取 XMP 元数据。 |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | 检查当前 PDF 文档是否已使用增量更新方式保存。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | 从流导入批注到文档。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | 从 XFDF 文件导入批注到文档。 |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | 检查文档是否需要调用 Repair 方法。 |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | 加载文件并将其转换为 PDF。 |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | 合并文档。 |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | 合并 pdf 文件。 |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | 合并文档。 |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | 合并文档。 |
| [Optimize](../../aspose.pdf/document/optimize/)() | 线性化文档，以实现以下目标：- 尽快打开首页；- 尽快显示下一页或通过链接跳转到下一页；- 当页面数据通过慢速通道分段传输时，逐步显示页面（优先显示最有用的数据）；- 允许用户交互（如点击链接）在整个页面接收并显示之前就可以进行。调用此方法并不会实际保存文档。相反，文档仅被准备为优化结构，随后调用 Save 以获取优化后的文档。 |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | 优化文档中的资源：1. 删除文档页面未使用的资源；2. 将相同的资源合并为一个对象；3. 删除未使用的对象。 |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | 根据定义的优化策略优化文档中的资源。 |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | 将文档中的页面树节点组织为平衡树。仅当文档的页面对象数量超过 nodesNumInSubtrees 时才执行，否则不做任何操作。遍历 Pages 元素时请勿调用此方法，否则可能产生不可预期的结果。 |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | 为生成器处理段落。 |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | 从文档中移除元数据。 |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | 从文档中移除 pdfa 合规性 |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | 从文档中移除 pdfUa 合规性 |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | 修复损坏的文档。 |
| [Save](../../aspose.pdf/document/save/#save)() | 增量保存文档（即使用增量更新技术）。 |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | 使用保存选项保存文档。 |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | 将文档存储到流中。 |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | 将文档保存到指定文件中。 |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | 以新名称和文件格式保存文档。 |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | 使用保存选项将文档保存到流中。 |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | 以新名称和文件格式保存文档。 |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | 以新名称并设置保存选项保存文档。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | 增量保存文档（即使用增量更新技术）。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | 使用保存选项保存文档。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | 将文档存储到流中。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | 将文档保存到指定文件中。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | 以新名称和文件格式保存文档。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | 使用保存选项将文档保存到流中。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | 以新名称和文件格式保存文档。 |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | 以新名称并设置保存选项保存文档。 |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | 将文档保存为 XML。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | 将整个文档发送到文档设备进行处理。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | 将整个文档发送到文档设备进行处理。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | 将特定页面的文档发送到文档设备进行处理。 |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | 将整个文档发送到文档设备进行处理。 |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | 设置 PDF 文档的标题。 |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | 设置文档的 XMP 元数据。 |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | 将文档验证到指定文件。 |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | 将文档验证到指定文件。 |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | 将文档验证到指定文件。 |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | 将源格式的流转换为目标格式的流。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | 将源格式的流转换为目标格式的文件。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | 将源格式的源文件转换为目标格式的流。 |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | 将源格式的源文件转换为目标格式的目标文件。 |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | 将加载整个文件到内存的文件大小限制设置为默认值 210 Mb。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | 当字体在文档中替换另一个字体时发生。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | 表示将处理 FontSubstitution 事件的方法。 |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | 提供调优字体的功能。 |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | 表示 Merge 方法的选项。 |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | 表示用于修复 PDF 文档的选项。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


