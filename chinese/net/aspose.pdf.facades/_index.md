---
title: "Aspose.Pdf.Facades"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades 命名空间提供最初来自 Aspose.Pdf.Kit 的类。这些类用于在不访问文档内部结构的情况下，对文档进行拼接、加盖印章、签名、注释等高级操作。"
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/
---
**Aspose.Pdf.Facades** 命名空间提供最初来自 Aspose.Pdf.Kit 的类。这些类用于在不访问文档内部结构的情况下，对文档执行合并、加盖印章、签名、注释等高级操作。

## 类

| 类 | 描述 |
| --- | --- |
| [AutoFiller](./autofiller/) | 表示一个类，用于从数据库或其他数据源接收数据，将其填充到模板 PDF 的设计字段中，最终生成新的 PDF 文件或流。它有两种模板文件输入模式：作为流或 PDF 文件。它有四种输出模式：一个合并流、一个合并文件、多个小流、多个小文件。它可以接收包含在 System.Data.DataTable 中的文字数据。 |
| [BDCProperties](./bdcproperties/) | BDC 操作符属性。 |
| [Bookmark](./bookmark/) | 表示书签。 |
| [Bookmarks](./bookmarks/) | 表示一组 [`Bookmark`](../aspose.pdf.facades/bookmark/) 对象。 |
| [DocumentPrivilege](./documentprivilege/) | 表示访问 Pdf 文件的权限。参见[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/)。使用此类有 4 种方式：1.直接使用预定义的权限。2.基于预定义的权限并更改某些特定权限。3.基于预定义的权限并更改某些特定的 Adobe Professional 权限组合。4.混合方式 2 和方式 3。 |
| [Facade](./facade/) | 基础外观类。 |
| [FontColor](./fontcolor/) | 表示文本颜色的类。 |
| [Form](./form/) | 表示 Acro 表单对象的类。 |
| [FormattedText](./formattedtext/) | 表示格式化文本的类。包含有关文本及其颜色、大小、样式的信息。 |
| [FormDataConverter](./formdataconverter/) | 表示一个将数据从一种格式转换为另一种格式的类。它可以将 fdf/xml/pdf/xfdf 中的数据转换为 OLEDB/OdbcDB。它也可以将 OLEDB/OdbcDB 中的数据转换为 fdf/xml/xfdf。它可以将 fdf 转换为带有 "hard-named" 标记的 xml。 |
| [FormEditor](./formeditor/) | 用于编辑表单（添加/删除字段等）的类。 |
| [FormFieldFacade](./formfieldfacade/) | 表示字段属性的类。 |
| [LineInfo](./lineinfo/) | 表示线条的信息。 |
| [PdfAnnotationEditor](./pdfannotationeditor/) | 表示用于处理 PDF 文档批注（注释）的类。 |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | 表示用于处理 PDF 文件书签的类，包括创建、修改、导出、导入和删除。 |
| [PdfContentEditor](./pdfcontenteditor/) | 表示用于编辑 PDF 文件内容的类。 |
| [PdfConverter](./pdfconverter/) | 表示将 pdf 文件的每页转换为图像的类，目前支持 BMP、JPEG、PNG 和 TIFF。pdf 中支持的内容：图片、表单、注释。 |
| [PdfExtractor](./pdfextractor/) | 用于从 PDF 文档中提取图像和文本的类。 |
| [PdfFileEditor](./pdffileeditor/) | 实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。 |
| [PdfFileInfo](./pdffileinfo/) | 表示用于访问 PDF 文档元信息的类。 |
| [PdfFileMend](./pdffilemend/) | 表示用于在现有 PDF 文档页面上添加文本和图像的类。 |
| [PdfFileSanitization](./pdffilesanitization/) | 表示清理和恢复 API。如果无法以其他方式创建/打开文档，请使用它。 |
| [PdfFileSecurity](./pdffilesecurity/) | 表示使用所有者或用户密码对 Pdf 文件进行加密或解密，修改安全设置和密码。 |
| [PdfFileSignature](./pdffilesignature/) | 表示使用证书对 pdf 文件进行签名的类。 |
| [PdfFileStamp](./pdffilestamp/) | 用于向 PDF 文件添加印章（水印或背景）的类。 |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | 用于移除所有 Java Script 代码的类。 |
| [PdfPageEditor](./pdfpageeditor/) | 表示用于编辑 PDF 文件页面的类，包括旋转页面、缩放页面、移动位置和更改页面大小。 |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | 表示包含当前打印页面信息的对象。 |
| [PdfProducer](./pdfproducer/) | 表示一个用于从其他格式生成 PDF 的类。此示例展示了如何从 CGM 文件生成 Pdf 文件。 |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | 表示处理 [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) 事件的 [`PdfViewer`](../aspose.pdf.facades/pdfviewer/) 方法。 |
| [PdfViewer](./pdfviewer/) | 表示用于查看或打印 pdf 的类。 |
| [PdfXmpMetadata](./pdfxmpmetadata/) | 用于操作 XMP 元数据的类。 |
| [ReplaceTextStrategy](./replacetextstrategy/) | 此类包含在执行 ReplaceText 操作时定义 PdfContentEditor 行为的参数。 |
| [SaveableFacade](./saveablefacade/) | 所有可保存外观的基类。 |
| [SignatureName](./signaturename/) | 表示签名名称的类。 |
| [Stamp](./stamp/) | 表示印章的类。 |
| [StampInfo](./stampinfo/) | 表示印章信息的类。 |
| [TextProperties](./textproperties/) | 表示文本属性，例如：文本大小、颜色、样式等。 |
| [ViewerPreference](./viewerpreference/) | 描述查看器首选项（页面模式、非全屏页面模式、页面布局）。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IFacade](./ifacade/) | 定义通用外观方法的通用外观接口。 |
| [ISaveableFacade](./isaveablefacade/) | 定义所有可保存外观通用方法的外观接口。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [Algorithm](./algorithm/) | 表示可用于加密 pdf 文档的算法。 |
| [AutoRotateMode](./autorotatemode/) | 文档打印时的旋转方向。 |
| [BlendingColorSpace](./blendingcolorspace/) | 表示混合颜色空间的类。 |
| [DataType](./datatype/) | 枚举字段类型定义。 |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | 标准 XMP 属性的枚举。 |
| [EncodingType](./encodingtype/) | 枚举文本使用的编码类型。 |
| [FieldType](./fieldtype/) | 可能字段类型的枚举。 |
| [FontStyle](./fontstyle/) | 枚举 14 种字体类型。 |
| [ImageMergeMode](./imagemergemode/) | 表示合并图像的模式。 |
| [KeySize](./keysize/) | 定义可用于加密 pdf 文档的不同密钥大小。 |
| [PositioningMode](./positioningmode/) | 定义定位模式。可能的值包括 Legacy（向后兼容）和 Current（更新的文本位置计算方法）。 |
| [PropertyFlag](./propertyflag/) | 可能字段标志的枚举。 |
| [StampType](./stamptype/) | 描述印章类型。 |
| [SubmitFormFlag](./submitformflag/) | 可能的提交表单标志的枚举。 |
| [WordWrapMode](./wordwrapmode/) | 定义换行策略 |


