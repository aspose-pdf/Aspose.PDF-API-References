---
title: Document
second_title: Aspose.PDF for .NET API 参考
description: 代表 PDF 文档的类
type: docs
weight: 1870
url: /zh/net/aspose.pdf/document/
---
## Document class

代表 PDF 文档的类

```csharp
public sealed class Document : IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Document](document#constructor)() | 初始化空文档。 |
| [Document](document#constructor_1)(Stream) | 从*input*流. |
| [Document](document#constructor_6)(string) | 只需使用初始化文件*filename*.一样[`Document`](./document). |
| [Document](document#constructor_3)(Stream, bool) | 从*input*流. |
| [Document](document#constructor_2)(Stream, LoadOptions) | 从流中打开现有文档，提供必要的转换以获取 pdf 文档。 |
| [Document](document#constructor_4)(Stream, string) | 从*input*流. |
| [Document](document#constructor_7)(string, LoadOptions) | 从文件中打开现有文档，提供必要的转换选项以获取 pdf 文档。 |
| [Document](document#constructor_8)(string, string) | 初始化[`Document`](../document)用于处理加密文档的类。 |
| [Document](document#constructor_5)(Stream, string, bool) | 从*input*流. |
| [Document](document#constructor_9)(string, string, bool) | 初始化[`Document`](../document)用于处理加密文档的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | 获取文档操作。此属性是 DocumentActions 类的实例，它允许获取/设置 BeforClosing、BeforSaving 等操作。 |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | 允许合并页面内容以优化文档大小。如果使用，则不同但重复的页面可能会引用 相同的内容对象。请注意，此模式可能会导致在更改其他页面时更改页面内容等副作用。 |
| [Background](../../aspose.pdf/document/background) { get; set; } | 获取或设置文档的背景颜色。 |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | 获取或设置标志，指定文档窗口的位置是否将在屏幕上居中。 |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | 获取文档集合。 |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | 如果文档已加密，则获取安全设置。 如果文档未加密，则在 .net 1.1 中将引发相应的异常，否则其他 .net 版本的 CryptoAlgorithm 将为空。 |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | 获取目的地的集合。 已过时。请使用 NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | 获取或设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | 如果该字体的许可禁止这些操作，则无法执行该字体的许多操作。 例如，如果许可规则禁用该字体的嵌入，则某些字体无法嵌入到 PDF 文档中。 此标志用于禁用当前 PDF 文档中所有字体的任何许可限制。 使用此标志时要小心。当它被设置时，它意味着设置这个标志的人， 对自己可能违反许可/法律的行为承担全部责任。 所以他自己承担风险。 强烈建议仅在您完全确信自己没有违反 版权法时才使用此标志。 默认为假。 |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | 获取或设置标志，指定文档的窗口标题栏是否应显示文档标题。 |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | 获取或设置从打印对话框打印文件时使用的打印双面模式处理选项。 |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | 获取嵌入到文档的文件集合。 |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | 声明该文档必须嵌入所有标准 Type1 字体的属性 将标志 IsEmbedded 设置为 true。所有 PDF 字体都可以通过将标志 IsEmbedded 设置为 true 来嵌入 到文档中，但 PDF 标准 Type1 字体是此规则的一个例外。 标准 Type1 字体嵌入需要很多时间，因此要嵌入这些字体 不仅需要设置标志IsEmbedded 为指定字体设置为 true，但还在文档级别设置 一个附加标志 - EmbedStandardFonts = true; 对于所有字体，此属性只能设置一次。 默认为 false。 |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | 获取或设置使文档部分从内存中卸载的标志。 这可以减少内存使用，但可能对性能产生负面影响。 |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | 获取或设置标志以管理签名字段清理。默认启用。 |
| [FileName](../../aspose.pdf/document/filename) { get; } | 产生此文档的 PDF 文件的名称 |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | 获取或设置标志，指定是否必须调整文档窗口的大小以适合显示的第一个页面。 |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | IDocumentFontUtilities 实例 |
| [Form](../../aspose.pdf/document/form) { get; } | 获取文档的 Acro 格式。 |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | 如果文档将保存更改并具有签名，则抛出异常 |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | 获取或设置标志，指定当文档处于活动状态时是否应隐藏菜单栏。 |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | 获取或设置标志，指定当文档处于活动状态时是否应隐藏工具栏。 |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | 获取或设置标志，指定当文档处于活动状态时是否应隐藏用户界面元素。 |
| [Id](../../aspose.pdf/document/id) { get; } | 获取 ID。 |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | 获取或设置忽略源文件中错误的标志。 当源文档中的页面复制到目标文档中时，如果源文件中的某些对象在此标志为假时损坏，则复制过程将停止，异常 。 示例：dest.Pages.Add(src.Pages); 如果此标志设置为 true，则损坏的对象将被替换为空值。 默认情况下：true. |
| [Info](../../aspose.pdf/document/info) { get; } | 获取文档信息。 |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | 获取文档的加密状态。如果文档已加密，则为真。 |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | 获取或设置一个值，该值指示文档是否被线性化。 |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | 获取符合 pdfa 的 is 文档。 |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | 获取符合 pdfua 的文档。 |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | 获取或设置 is document pdfa compliant. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | 文档级别的 JavaScript 集合。 |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | 获取文档的逻辑结构。 |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | 文档元数据。 （PDF 文档可能包括一般信息， ，例如文档的标题、作者以及创建和修改日期。 关于文档（与其内容或结构相反）的此类全局信息称为元数据 ，并且是旨在帮助编目和搜索外部数据库中的文档。） |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | 文档中命名目的地的集合。 |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | 获取或设置页面模式，指定在退出全屏模式时如何显示文档。 |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | 获取或设置文档打开时执行的操作。 |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | 获取或设置优化标志。将页面添加到文档时，如果设置了此标志，则结果文件中的相等资源流 are 合并到一个 PDF 对象中。 这可以减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。 默认值：false。 |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | 获取文档大纲。 |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | 获取或设置页面信息。（仅用于生成器） |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | 获取文档中的页面标签。 |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | 获取或设置打开文档时应使用的页面布局。 |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | 获取或设置页面模式，指定文档在打开时应如何显示。 |
| [Pages](../../aspose.pdf/document/pages) { get; } | 获取或设置文档页面的集合。 请注意，页面从集合中的 1 开始编号。 |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | 获取 PDF 格式 |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | 获取文档的权限。 |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | 获取对 TaggedPdf 内容的访问权限。 |
| [Version](../../aspose.pdf/document/version) { get; } | 从 Pdf 文件头获取一个版本的 Pdf。 |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | 获取系统的许可状态。如果系统在许可模式下工作，则返回 true，否则返回 false。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | 将 xml 绑定到文档 |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | 将 xml 绑定到文档 |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | 将 xml/xsl 绑定到文档 |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | 将 xml/xsl 绑定到文档 |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | 将 xml/xsl 绑定到文档 |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | 更改文档密码。此操作只能使用所有者密码来完成。 |
| [Check](../../aspose.pdf/document/check)(bool) | 验证文档。 |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | 转换文档并将错误保存到指定文件中。 |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | 使用指定的转换选项转换文档 |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | 转换文档并将错误保存到指定的流中。 |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | 转换文档并将错误保存到指定文件中。 |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | 通过应用 Fixup 转换文档。 |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | 通过应用 Fixup 转换文档。 |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 转换文档并将错误保存到指定文件中。 |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 转换文档并将错误保存到指定文件中。 |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | 将页面转换为 DSR、OMR、OCR 图像流的 PNG。 |
| [Decrypt](../../aspose.pdf/document/decrypt)() | 解密文档。调用然后保存以获取文档的解密版本。 |
| [Dispose](../../aspose.pdf/document/dispose)() | 关闭此文档使用的所有资源。 |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | 加密文档。调用然后保存以获取文档的加密版本。 |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | 加密文档。调用然后保存以获取文档的加密版本。 |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | 加密文档。调用然后保存以获取文档的加密版本。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | 将所有文档注释导出到流中。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | 将所有文档注释导出到 XFDF 文件 |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | 从文档中删除所有字段并放置它们的值。 |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | 从文档中删除所有字段并放置它们的值。 |
| [FreeMemory](../../aspose.pdf/document/freememory)() | 清除内存 |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | 从目录字典中返回项目值。 |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | 获取文档中具有指定 ID 的对象。 |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | 从文档中获取 XMP 元数据。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | 将注释从流导入到文档。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | 将注释从 XFDF 文件导入到文档。 |
| [Optimize](../../aspose.pdf/document/optimize)() | 线性化文档，以便 - 尽快打开第一页； - 尽快显示下一页或链接到下一页； - 当页面的数据被传递时，页面到达时递增显示通过慢速通道（首先显示最有用的数据）； - 允许用户交互，例如跟踪链接，甚至在整个页面被接收和显示之前执行。 调用此方法实际上不会保存文档.反之文档只准备有优化的结构， 调用然后保存得到优化的文档。 |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | 优化文档中的资源： 1.文档页面上没有使用的资源被移除； 2.相等的资源合并为一个对象； 3. 未使用的对象被删除。 |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | 根据定义的优化策略优化文档中的资源。 |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | 为生成器处理段落。 |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | 从文档中删除元数据。 |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | 从文档中删除 pdfa 合规性 |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | 从文档中删除 pdfUa 合规性 |
| [Repair](../../aspose.pdf/document/repair)() | 修复损坏的文档。 |
| [Save](../../aspose.pdf/document/save#save)() | 增量保存文档（即使用增量更新技术）。 |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | 使用保存选项保存文档。 |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | 将文档存储到流中。 |
| [Save](../../aspose.pdf/document/save#save_5)(string) | 将文档保存到指定文件中。 |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | 使用新名称和文件格式保存文档。 |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | 使用保存选项将文档保存到流中。 |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | 使用新名称和文件格式保存文档。 |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | 使用设置其保存选项的新名称保存文档。 |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | 使用保存选项将文档保存到响应流中。 |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | 将文档保存到 XML. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | 将整个文档发送到文档设备进行处理。 |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | 将整个文档发送到文档设备进行处理。 |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | 将文档的某些页面发送到文档设备进行处理。 |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | 将整个文档发送到文档设备进行处理。 |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | 为 Pdf 文档设置标题 |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | 设置文档的 XMP 元数据。 |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | 验证文档到指定文件中。 |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | 验证文档到指定文件中。 |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | 验证文档到指定文件中。 |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | 将源格式的流转换为目标格式的流。 |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | 将源格式的流转换为目标格式的目标文件。 |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | 将源格式的源文件转换为目标格式的流。 |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | 将源格式的源文件转换为目标格式的目标文件。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | hocr 识别的回调过程。 |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | 表示将处理 FontSubstitution 事件的方法。 |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | 拥有调整字体的功能 |

### 也可以看看

* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
