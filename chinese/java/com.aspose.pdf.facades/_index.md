---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Aspose.PDF for Java API 参考"
description: "com.aspose.pdf.facades 包提供最初来自 Aspose.Pdf.Kit 的类。"
type: docs
weight: 180
url: /zh/java/com.aspose.pdf.facades/
---
com.aspose.pdf.facades 包提供最初来自 Aspose.Pdf.Kit 的类。

## 接口

| 接口 | 描述 |
| --- | --- |
| [IFacade](./ifacade/) | 定义通用外观方法的通用外观接口。 |
| [IForm](./iform/) | 表示 Acro 表单对象的类。 |
| [IFormEditor](./iformeditor/) | 用于编辑表单（添加/删除字段等）的类。 |
| [IPdfFileEditor](./ipdffileeditor/) | 实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。 |
| [IPdfFileStamp](./ipdffilestamp/) | 用于向 PDF 文件添加印章（水印或背景）的接口。 |
| [ISaveableFacade](./isaveablefacade/) | 为所有可保存的外观定义通用方法的外观接口。 |
## 类

| 类 | 描述 |
| --- | --- |
| [AlignmentType](./alignmenttype/) | 类可能包含对齐类型。请改用 HorizontalAlignment。 |
| [AutoRotateMode](./autorotatemode/) | 文档打印时的旋转方向。 |
| [BDCProperties](./bdcproperties/) | BDC 操作符属性。 |
| [Bookmark](./bookmark/) | 表示一个书签。 |
| [Bookmarks](./bookmarks/) | 表示 {@code Bookmark} 对象的集合。 |
| [CgmPdfProducer](./cgmpdfproducer/) | 表示一个将计算机图形元文件（CGM）格式转换为 PDF 的类。 |
| [DataType](./datatype/) | 枚举字段类型定义。 |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | 标准 XMP 属性的枚举。 |
| [DocumentPrivilege](./documentprivilege/) | 表示访问 Pdf 文件的权限。参见 {@code PdfFileSecurity}。使用此类有 4 种方式：1.直接使用预定义的权限。2.基于预定义的权限并更改某些特定权限。3.基于预定义的权限并更改某些特定的 Adobe Professional 权限组合。4.混合方式 2 和方式 3。 //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | 枚举文本使用的编码类型。 |
| [Facade](./facade/) | 基础外观类。 |
| [FontColor](./fontcolor/) | 表示文本颜色的类。 |
| [Form](./form/) | 表示 Acro 表单对象的类。 |
| [Form.ImportStatus](./form.importstatus/) | 导入字段的状态 |
| [FormattedText](./formattedtext/) | 表示格式化文本的类。包含关于文本及其颜色、大小、样式的信息。 |
| [FormEditor](./formeditor/) | 用于编辑表单（添加/删除字段等）的类。 |
| [FormEditorWeb](./formeditorweb/) | 用于编辑表单（添加/删除字段等）的类。 |
| [FormFieldFacade](./formfieldfacade/) | 表示字段属性的类。 |
| [FormWeb](./formweb/) | 表示 Acro 表单接口。 |
| [InternalHelper](./internalhelper/) | 帮助类 |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | 用于指定页面调整参数的类。允许设置以下参数：结果页面的尺寸（宽度、高度），使用默认空间单位或初始页面尺寸的百分比；左、上、下、右边距，使用默认空间单位或初始页面尺寸的百分比；某些值可以为 null，以便自动计算。这些值将在显式指定的值计算后，根据剩余页面尺寸进行计算。例如：如果页面宽度 = 100，且新页面宽度指定为 60 单位，则左、右边距会自动计算为：(100 - 60) / 2 = 15。此类在 ResizeContents 方法中使用。 |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | 以默认空间单位的百分比指定的边距或内容尺寸值。此类在 ContentsResizeParameters 中使用。 |
| [LineInfo](./lineinfo/) | 表示线条的信息。 |
| [PdfAnnotationEditor](./pdfannotationeditor/) | 表示用于处理 PDF 文档批注（注释）的类。 |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | 表示用于处理 PDF 文件书签（包括创建、修改、导出、导入和删除）的类。 |
| [PdfContentEditor](./pdfcontenteditor/) | 表示用于编辑 PDF 文件内容的类。 |
| [PdfConverter](./pdfconverter/) | 表示用于将 PDF 文件的每页转换为图像的类，现已支持 BMP、JPEG、PNG 和 TIFF。支持的 PDF 内容包括：图片、表单、注释。 |
| [PdfExtractor](./pdfextractor/) | 用于从 PDF 文档中提取图像和文本的类。 |
| [PdfFileEditor](./pdffileeditor/) | 实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。 |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | 在合并过程中遇到损坏文件时执行的操作。 |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | 表示具有抽象方法的类，该方法通常由调用方提供并处理来自合并的进度事件。通常此类提供的客户处理程序可用于在控制台或进度条上显示总体合并进度。表示已发生的进度事件信息。 |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | 在合并期间提供损坏文件信息的类。 |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | 分页符位置的数据。 |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | 此类表示可在外部应用程序中使用的合并进度信息。 |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | 此枚举描述合并过程中可能出现的进度事件类型。 |
| [PdfFileEditorWeb](./pdffileeditorweb/) | 表示 PdfFileEditorWeb 类，实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。 |
| [PdfFileInfo](./pdffileinfo/) | 表示用于访问 PDF 文档元信息的类。 |
| [PdfFileMend](./pdffilemend/) | 表示用于在现有 PDF 文档页面上添加文本和图像的类。 |
| [PdfFileSanitization](./pdffilesanitization/) | 表示清理和恢复 API。如果无法以其他方式创建/打开文档，请使用它。 |
| [PdfFileSecurity](./pdffilesecurity/) | 表示使用所有者或用户密码对 PDF 文件进行加密或解密、修改安全设置和密码的功能。 |
| [PdfFileSignature](./pdffilesignature/) | 表示使用证书对 PDF 文件进行签名的类。 |
| [PdfFileStamp](./pdffilestamp/) | 用于向 PDF 文件添加印章（水印或背景）的类。 |
| [PdfFileStampWeb](./pdffilestampweb/) | 用于向 PDF 文件添加印章（水印或背景）的类。支持与 HttpServletResponse 配合使用。 |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | 用于移除所有 JavaScript 代码的类。 |
| [PdfPageEditor](./pdfpageeditor/) | 表示用于编辑 PDF 文件页面的类，包括旋转页面、缩放页面、移动位置和更改页面尺寸。 |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | 表示包含当前打印页面信息的对象。 |
| [PdfProducer](./pdfproducer/) | <p> 表示用于从其他格式生成 PDF 的类。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | 表示处理 PrintDocument 的 QueryPageSettings 事件的方法。 |
| [PdfViewer](./pdfviewer/) | 表示用于查看或打印 PDF 的类。 |
| [PdfXmpMetadata](./pdfxmpmetadata/) | 用于操作 XMP 元数据的类。 |
| [PositioningMode](./positioningmode/) | 定义定位模式。可能的取值包括 Legacy（向后兼容）和 Current（更新的文本位置计算方法）。 |
| [PropertyFlag](./propertyflag/) | 可能的字段标志枚举。 |
| [ReplaceTextStrategy](./replacetextstrategy/) | 此类包含定义 PdfContentEditor 在执行 ReplaceText 操作时行为的参数。 |
| [SaveableFacade](./saveablefacade/) | <p> 所有可保存外观的基类。 |
| [SignatureName](./signaturename/) | 表示签名名称的类。表示更精确的签名名称。用于替代字符串名称。允许您使用相同的字符串名称呈现签名。 |
| [Stamp](./stamp/) | 表示印章的类。 |
| [StampInfo](./stampinfo/) | 表示印章信息的类。 |
| [TextProperties](./textproperties/) | 表示文本属性，例如：文本大小、颜色、样式等。 |
| [VerticalAlignmentType](./verticalalignmenttype/) | 表示可能的垂直对齐值的类。请改用 VerticalAlignment。 |
| [ViewerPreference](./viewerpreference/) | 描述查看器首选项（页面模式、非全屏页面模式、页面布局）。 |
| [WordWrapMode](./wordwrapmode/) | 定义换行策略 |
## Enums

| 枚举 | 描述 |
| --- | --- |
| [Algorithm](./algorithm/) | 表示可用于加密 pdf 文档的算法。 |
| [BlendingColorSpace](./blendingcolorspace/) | 表示混合颜色空间的类。 |
| [FieldType](./fieldtype/) | 可能的字段类型枚举。 |
| [FontStyle](./fontstyle/) | 枚举 14 种字体类型。 |
| [ImageMergeMode](./imagemergemode/) | 表示合并图像的模式。 |
| [KeySize](./keysize/) | 定义可用于加密 pdf 文档的不同密钥大小。 |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | 当字体不包含所需字符时要执行的操作 |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | 默认情况下，替换文本操作应用的范围为 REPLACE_FIRST。 |
| [StampType](./stamptype/) | 描述印章类型。 |
| [SubmitFormFlag](./submitformflag/) | 可能的提交表单标志枚举。 |
