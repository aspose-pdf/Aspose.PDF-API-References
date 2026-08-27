---
title: "com.aspose.pdf"
second_title: "Aspose.PDF for Java API 参考"
description: "com.aspose.pdf 是 Aspose.PDF for Java 库中所有类的根包，这些类要么直接位于其中，如 Document，要么通过多个子包间接包含。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf/
---
com.aspose.pdf 是 Aspose.PDF for Java 库中所有类的根包，这些类要么直接位于其中，如 Document，要么通过多个子包间接包含。

## 接口

| 接口 | 描述 |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | hocr 识别的回调过程。 |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | hocr 识别的回调过程。 |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | hocr 识别的回调过程。 |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | 包含调节字体的功能 |
| [IAnnotationVisitor](./iannotationvisitor/) | 定义用于访问不同文档注释的 Visitor。 |
| [IAppointment](./iappointment/) | 表示用于操作和目标的通用接口。 |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | 颜色空间转换策略的接口。 |
| [IDocument](./idocument/) | 表示 PDF 文档的接口 |
| [IFontOptions](./ifontoptions/) | 用于调节字体行为的有用属性 |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | 此接口用于声明量化自定义算法。用户可以实现自己的该算法实现（例如基于非托管代码的算法）。 |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | 此接口用于声明量化自定义算法。用户可以实现自己的该算法实现（例如基于非托管代码的算法）。 |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | 定义用于访问不同 PDF 操作符的 Visitor。 |
| [IPageSetOptions](./ipagesetoptions/) | 定义与要转换的页面集合相关的转换选项。 |
| [IPipelineOptions](./ipipelineoptions/) | 定义与管道配置相关的转换选项。 |
| [ITableElement](./itableelement/) | 此接口表示由 TableAbsorber 提取的现有表格的元素。 |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | 有时需要避免使用内部加载器来加载外部资源（如图像或 CSS），并提供自定义方法，以从某处获取请求的资源。例如，在云端使用 Aspose.PDf 时无法直接访问引用的文件，需要将一些自定义代码放入专用方法中使用。此委托定义了此类自定义方法的签名。 |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * 设置标志，指示是否使用临时文件夹来存放临时字体数据。 / * 默认值为 true。 / * 如果值为 false，则使用堆内存； / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | 要为此类属性分配委托，可使用自定义方法创建的委托，该方法实现对从 PDF 创建的 SVG 中提取的图像的外部保存处理，并在 PDF 转 HTML 的转换过程中将其保存为外部资源。在这种情况下，处理（例如自行保存到流或磁盘）可以在该自定义代码中完成，并且该自定义代码必须返回路径（或任何不带引号的字符串），该路径随后会被合并到生成的 SVG 中，替代原本应指向该图像资源的路径。在这种情况下，所有保存图像的必要操作必须在提供的方法代码中完成，因为转换器代码中的结果保存将不再使用。如果出于某种原因必须由转换器的代码本身（而不是自定义代码）处理此文件或那个文件，请在自定义代码中设置 'CustomProcessingCancelled' 标志，针对 'imageSavingInfo' 参数的变量。它向转换器指示，所有对该资源的必要处理步骤应由转换器自行完成，就像没有任何外部自定义代码一样。 |
## 类

| 类 | 描述 |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | 表示页面上存在的表格单元格 |
| [AbsorbedRow](./absorbedrow/) | 表示页面上存在的表格行 |
| [AbsorbedTable](./absorbedtable/) | 表示页面上存在的表格 |
| [ActionCollection](./actioncollection/) | 操作集合 |
| [Annotation](./annotation/) | 表示注释对象的类。 |
| [AnnotationActionCollection](./annotationactioncollection/) | 表示注释操作的集合。 |
| [AnnotationCollection](./annotationcollection/) | 表示注释集合的类。 |
| [AnnotationFlags](./annotationflags/) | 标志 一组二进制标志，用于指定注释的各种特性。 |
| [AnnotationSelector](./annotationselector/) | 此类用于使用 Visitor 模板思想选择注释。 |
| [AnnotationTextRenderer](./annotationtextrenderer/) | 用于渲染普通文本和富文本的类。 |
| [AppearanceDictionary](./appearancedictionary/) | 注释外观字典，指定注释在页面上的视觉呈现方式。 |
| [ApsLoadOptions](./apsloadoptions/) | 描述 APS 加载选项的类。用于从 APS XML 格式导入的选项。 |
| [ApsSaveOptions](./apssaveoptions/) | 导出为 APS XML 格式的保存选项。 |
| [ApsToFlowConverter](./apstoflowconverter/) | APS 到 Flow 的转换 |
| [Artifact](./artifact/) | 表示 PDF Artifact 对象的类。 |
| [ArtifactCollection](./artifactcollection/) | 表示 Artifact 集合的类。 |
| [AutoTaggingSettings](./autotaggingsettings/) | 提供 PDF 文档自动标记功能的设置。{@link AutoTaggingSettings} 类允许配置 PDF 内容自动标记的选项。它包括用于启用或禁用自动标记、指定标题识别策略以及基于字体大小定义标题级别的属性。 |
| [BackgroundArtifact](./backgroundartifact/) | 描述背景 Artifact 的类。此 Artifact 允许设置页面的背景。 |
| [BarcodeField](./barcodefield/) | 表示条形码字段的类。 |
| [BaseActionCollection](./baseactioncollection/) | 封装页面、注释、字段交互操作的基本动作的类。 |
| [BaseOperatorCollection](./baseoperatorcollection/) | 表示运算符集合的基类。 |
| [BaseParagraph](./baseparagraph/) | 表示可以添加到页面的抽象基对象（doc.Paragraphs.Add()）。 |
| [BatesNArtifact](./batesnartifact/) | 类描述 Bates 编号工件。 |
| [BitmapInfo](./bitmapinfo/) | 对象包含像素数组和位图信息。 |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | 位图像素格式。 |
| [BleedMarkAnnotation](./bleedmarkannotation/) | 表示出血标记注释。出血标记放置在打印页面的角落，以指示页面应裁剪的位置以及允许偏离裁剪标记的距离。 |
| [Border](./border/) | 类表示注释边框的特征。 |
| [BorderInfo](./borderinfo/) | 此类表示图形元素的边框。 |
| [BorderSide](./borderside/) | 标志枚举边框各侧的二进制值。 |
| [BorderStyleConverter](./borderstyleconverter/) | 表示 BorderStyleConverter 类 |
| [Brush](./brush/) | 此类表示抽象画刷 |
| [BuildVersionInfo](./buildversioninfo/) | 此类提供有关当前产品构建的信息。 |
| [ButtonField](./buttonfield/) | 类表示按钮字段。 |
| [CaretAnnotation](./caretannotation/) | 类表示插入符号注释。 |
| [CaretSymbolConverter](./caretsymbolconverter/) | 表示 CaretSymbolConverter 类 |
| [CdrLoadOptions](./cdrloadoptions/) | 类描述 CDR 加载选项。 |
| [Cell](./cell/) | 表示表格行的单元格。 |
| [Cells](./cells/) | 表示行的单元格集合。 |
| [CgmImportOptions](./cgmimportoptions/) | 用于从计算机图形元文件（CGM）格式导入的选项。 |
| [CgmLoadOptions](./cgmloadoptions/) | 包含将 CGM 文件加载/导入到 PDF 文档的选项。 |
| [Characteristics](./characteristics/) | 表示注释特征。 |
| [CharInfo](./charinfo/) | 表示字符信息对象。提供字符定位信息。 |
| [CharInfoCollection](./charinfocollection/) | <p> 表示 CharInfo 对象集合。 </p> <hr> <pre> The example demonstrates how to iterate thought all the characters and retrieve the character //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> 提供对文本段字符定位信息的访问。 </p> |
| [CheckboxField](./checkboxfield/) | 类表示复选框字段。 |
| [ChoiceField](./choicefield/) | 表示选择字段的基类。 |
| [CircleAnnotation](./circleannotation/) | 类表示圆形注释。 |
| [Collection](./collection/) | 表示 Collection（12.3.5 Collections） 类。 |
| [CollectionField](./collectionfield/) | 表示文档集合模式字段类。 |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | 表示模式集合中字段的子类型参数。 |
| [CollectionItem](./collectionitem/) | 表示集合项类。集合项包含由集合模式描述的数据。 |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | 表示集合项值的类。 |
| [CollectionSchema](./collectionschema/) | 表示描述文档集合“Schema”的类。 |
| [Color](./color/) | 表示可以在不同颜色空间中表达的颜色值类。 |
| [ColorBarAnnotation](./colorbarannotation/) | 表示 ColorBarAnnotation 注释的类。属性 Color 被忽略，改用 ColorsOfCMYK 颜色。创建时，宽高比例决定注释的方向——水平或垂直。随后检查注释矩形是否位于 TrimBox 之外，如果不在，则根据注释方向将其移动到 TrimBox 最近的外部位置。可以缩小宽度（高度），使注释位于 TrimBox 之外。如果布局没有空间，宽度/高度可以设为零（此时注释仍在页面上，但不显示）。 |
| [ColumnInfo](./columninfo/) | 此类表示列的信息。 |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | 表示事件的类 |
| [ComboBoxField](./comboboxfield/) | 表示表单中 Combobox 字段的类。 |
| [ComHelper](./comhelper/) | <p> 为 COM 客户端提供将文档加载到 Aspose.PDF 的方法。 </p> <hr> <p> 使用 ComHelper 类将文档从文件或流加载到 COM 应用程序中的 Document 对象。Document 类提供默认构造函数来创建新文档，并且还提供重载构造函数以从文件或流加载文档。如果您在 .NET 应用程序中使用 Aspose.Words，可以直接使用所有 Document 构造函数，但如果在 COM 应用程序中使用 Aspose.PDF，则仅提供默认的 Document 构造函数。 </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | 表示通用图形注释的抽象类。 |
| [CompositingParameters](./compositingparameters/) | 表示包含当前图形状态的图形合成参数的对象。 |
| [ContentsAppender](./contentsappender/) | 仅在 APPEND 模式下执行内容修改。此模式可避免在对内容进行更改之前进行不必要且繁重的内容解析。它仅将新操作符追加到内容的末尾或开头。 |
| [Copier](./copier/) | 用于复制对象的类。 |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | 表示放置在打印页面角落的注释类型。 |
| [CustomExplicitDestination](./customexplicitdestination/) | 表示自定义显式目标。 |
| [CustomSign](./customsign/) | 用于自定义签署文档的委托（Beta）。 |
| [Dash](./dash/) | 表示线段虚线模式的类。 |
| [DateField](./datefield/) | 带日历视图的日期字段。DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | 描述字段的默认外观（字体、文字大小和颜色）。 |
| [DefaultDirectory](./defaultdirectory/) | 指定某些用途的默认路径 |
| [DestinationCollection](./destinationcollection/) | 表示 PDF 文档中所有目标集合的类（一个名称树，将名称字符串映射到目标（参见 12.3.2.3，“Named Destinations”）以及（参见 7.7.4，“Name Dictionary”）））。 |
| [DestinationFactory](./destinationfactory/) | 表示 DestinationFactory 类 |
| [DjvuLoadOptions](./djvuloadoptions/) | 描述 DJVU 加载选项的类。 |
| [DocMDPSignature](./docmdpsignature/) | 表示文档 MDP（修改检测和防止）签名类型的类。 |
| [DocSaveOptions](./docsaveoptions/) | 导出为 Doc 格式的保存选项 |
| [Document](./document/) | 表示 PDF 文档的类。 |
| [Document.OptimizationOptions](./document.optimizationoptions/) | 描述文档优化算法的类。此类的实例可用作 OptimizeResources() 方法的参数。@deprecated 此类已过时。请改用 com.aspose.pdf.optimization.OptimizationOptions。 |
| [Document.RepairOptions](./document.repairoptions/) | 表示修复 PDF 文档的选项。此类提供自定义 PDF 文档修复过程的方法。 |
| [DocumentActionCollection](./documentactioncollection/) | 描述对文档执行的某些操作的类 |
| [DocumentExtensions](./documentextensions/) | 为 Document 类提供额外功能。 |
| [DocumentFactory](./documentfactory/) | 允许创建/加载不同类型文档的类。 |
| [DocumentInfo](./documentinfo/) | 表示 PDF 文档的元信息。 |
| [DocumentWeb](./documentweb/) | 表示 DocumentWeb 类 |
| [Element](./element/) | 表示逻辑结构基础元素的类。 |
| [ElementCollection](./elementcollection/) | 基础逻辑结构元素的集合。 |
| [EmbeddedFileCollection](./embeddedfilecollection/) | 表示嵌入文件集合的类。 |
| [EncryptedPayload](./encryptedpayload/) | 表示文件规范中的加密负载。 |
| [EpubLoadOptions](./epubloadoptions/) | 包含将 EPUB 文件加载/导入到 pdf 文档的选项。 |
| [EpubSaveOptions](./epubsaveoptions/) | 导出为 EPUB 格式的保存选项 |
| [ExcelSaveOptions](./excelsaveoptions/) | 导出为 Excel 格式的保存选项 |
| [ExplicitDestination](./explicitdestination/) | 表示 PDF 文档中显式目标的基类。 |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | 表示 ExplicitDestinationTypeConverter 类 |
| [ExportFieldsOptions](./exportfieldsoptions/) | 表示导出表单字段选项的基类。 |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | 表示导出表单字段为 Json 格式的选项。继承自 {@link ExportFieldsOptions} 并添加了 Json 导出的特定选项。 |
| [ExportImportMessages](./exportimportmessages/) | 包含表单字段导出和导入操作的各种错误消息。 |
| [ExternalSignature](./externalsignature/) | 使用 X509Certificate2 创建分离的 PKCS#7Detached 签名。它支持 USB 智能卡、没有可导出私钥的令牌。 |
| [FdfReader](./fdfreader/) | 执行 FDF 格式读取的类。Document doc = new Document(\"example.pdf\"); InputStream fdfStream = FileInputStream(\"file.fdf\"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save(\"example_out.pdf\"); |
| [Field](./field/) | Acro 表单字段的基类。 |
| [FieldSerializationResult](./fieldserializationresult/) | 表示表单字段序列化过程的结果。 |
| [FieldSerializationStatus](./fieldserializationstatus/) | 表示表单字段序列化的状态。 |
| [FieldValueType](./fieldvaluetype/) | 表示模式集合中字段值的类型。 |
| [FigureElement](./figureelement/) | 表示逻辑结构图的类。 |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | 描述文件附件注释的类。 |
| [FileFontSource](./filefontsource/) | 表示单个字体文件来源。 |
| [FileHyperlink](./filehyperlink/) | 表示文件超链接对象。 |
| [FileIconConverter](./fileiconconverter/) | 表示 FileIconConverter 类 |
| [FileParams](./fileparams/) | 定义一个嵌入文件参数字典，其中应包含额外的特定文件信息。 |
| [FileSelectBoxField](./fileselectboxfield/) | 文件选择框元素的字段。 |
| [FileSpecification](./filespecification/) | 表示嵌入文件的类。 |
| [FitBExplicitDestination](./fitbexplicitdestination/) | 表示显式目标，该目标显示页面并将其内容放大到恰好使其边界框完全适合窗口的水平和垂直方向。如果所需的水平和垂直放大因子不同，则使用较小的那个，并在另一个方向上将边界框居中于窗口。 |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | 表示显式目标，该目标显示页面，并将垂直坐标 top 定位在窗口的顶部边缘，页面内容放大到恰好使其边界框的整个宽度适合窗口。top 为 null 时表示保留该参数的当前值不变。 |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | 表示显式目标，该目标显示页面，并将水平坐标 left 定位在窗口的左侧边缘，页面内容放大到恰好使其边界框的整个高度适合窗口。left 为 null 时表示保留该参数的当前值不变。 |
| [FitExplicitDestination](./fitexplicitdestination/) | 表示显式目标，该目标显示页面并将其内容放大到恰好使整个页面在窗口中水平和垂直方向都完全适合。如果所需的水平和垂直放大因子不同，则使用较小的那个，并在另一个方向上将页面居中于窗口。 |
| [FitHExplicitDestination](./fithexplicitdestination/) | 表示显式目标，该目标显示页面，并将垂直坐标 top 定位在窗口的顶部边缘，页面内容放大到恰好使页面的整个宽度适合窗口。top 为 null 时表示保留该参数的当前值不变。 |
| [FitRExplicitDestination](./fitrexplicitdestination/) | 表示显式目标，该目标显示页面并将其内容放大到恰好使由坐标 left、bottom、right 和 top 指定的矩形在窗口中水平和垂直方向都完全适合。如果所需的水平和垂直放大因子不同，则使用较小的那个，并在另一个方向上将矩形居中于窗口。任何参数为 null 可能导致不可预测的行为。 |
| [FitVExplicitDestination](./fitvexplicitdestination/) | 表示显式目标，该目标显示页面，并将水平坐标 left 定位在窗口的左侧边缘，页面内容放大到恰好使页面的整个高度适合窗口。left 为 null 时表示保留该参数的当前值不变。 |
| [FixedPrint](./fixedprint/) | 表示水印注释的固定打印数据。 |
| [FloatingBox](./floatingbox/) | 表示 PDF 文档中的 FloatingBox。FloatingBox 是自定义定位的。 |
| [FlowConverter](./flowconverter/) | 将 PDF 文档转换为 Flow 格式（XLSX、ODS、XMLSpreedSheet2003、CSV）以及 EnchanedFlow 模式下的 DOCX，FlowEngine 模式下的 TableAbsorber。 |
| [FlowToTableAbsorber](./flowtotableabsorber/) | 将数据从 Flow 库传递给 TableAbsorber。 |
| [FolderFontSource](./folderfontsource/) | 表示包含字体文件的文件夹。 |
| [Font](./font/) | <p> 表示字体对象。 </p> <hr> <pre> 示例演示如何在首页搜索文本并更改首次搜索出现的字体。 // Open document Document doc = new Document(\"input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | 表示字体吸收器对象。执行字体搜索并通过 {@code FontAbsorber.Fonts} 集合提供对搜索结果的访问。 |
| [FontCollection](./fontcollection/) | <p> 表示字体集合。 </p> <hr> <pre> 此示例演示如何将页面上声明的所有字体设为嵌入。 // 打开文档 Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // 确保页面资源中声明的所有字体均已嵌入 // 注意，如果字体声明在表单资源中，则无法从页面资源访问 for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\\\Tests\\\\input.pdf"); </pre> <hr> <p> 由 {@code FontCollection} 类表示的字体集合在多种场景中使用。例如，在具有 {@code Resources.Fonts} 属性的资源中。 </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | PDF/A 标准要求所有字体必须嵌入文档中。此类包含在某些字体因目标电脑上缺失而无法嵌入的情况下使用的标志。 |
| [FontRepository](./fontrepository/) | <p> 执行字体搜索。搜索系统已安装的字体和标准 Pdf 字体。还提供打开自定义字体的功能。 </p> <hr> <pre> 此示例演示如何查找字体并替换第一页文本的字体。 // 查找字体 Font font = FontRepository.findFont("Arial"); // 打开文档 Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 接受第一页的吸收器 doc.getPages().get_Item(1).accept(absorber); // 更改首次文本出现的字体 absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // 保存文档 doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | 表示字体源的基类。 |
| [FontStyles](./fontstyles/) | Binary Flag <p> 指定应用于文本的样式信息。 </p> <hr> <p> 此枚举具有 {@code FlagsAttribute} 属性，允许组合其成员值。 </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag 枚举字体子集化的策略 |
| [FooterArtifact](./footerartifact/) | 描述页脚构件。可用于设置页面的页脚。 |
| [Form](./form/) | 表示表单对象的类。 |
| [Form.FlattenSettings](./form.flattensettings/) | 描述表单扁平化过程设置的类。 |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | 表单可以包含签名信息，并且可以是已签名或未签名的。有时在查看器中显示表单的方式必须取决于表单是否已签名。此枚举列举了在表单类型转换时针对签名的可能渲染模式。 |
| [FormattedFragment](./formattedfragment/) | 表示抽象的格式化片段。 |
| [FreeTextAnnotation](./freetextannotation/) | 表示一种自由文本注释，可直接在页面上显示文本。与普通文本注释不同，自由文本注释没有打开或关闭状态；文本始终可见，而不是显示在弹出窗口中。 |
| [GoToAction](./gotoaction/) | 表示一种转到操作，可将视图更改为指定的目标（页面、位置和放大比例）。 |
| [GoToRemoteAction](./gotoremoteaction/) | 表示一种远程转到操作，类似于普通的转到操作，但跳转到另一个 PDF 文件中的目标，而不是当前文件。 |
| [GoToURIAction](./gotouriaction/) | 表示一种 URI 操作，会解析 URI。 |
| [GraphInfo](./graphinfo/) | 表示图形信息。 |
| [Group](./group/) | 一个组属性类，指定页面组的属性，以在透明成像模型中使用。 |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | 描述页眉构件的类。此构件可用于设置页面的标题。 |
| [HeaderFooter](./headerfooter/) | 表示页眉或页脚 pdf 页面 的类。 |
| [Heading](./heading/) | 表示标题。 |
| [HideAction](./hideaction/) | 表示一种隐藏操作，可通过设置或清除其 Hidden 标志来隐藏或显示屏幕上的一个或多个注释。 |
| [HighlightAnnotation](./highlightannotation/) | 表示一种突出显示注释，可突出显示文档中的一段文本。 |
| [HtmlFragment](./htmlfragment/) | 表示 html 片段。 |
| [HtmlLoadOptions](./htmlloadoptions/) | 表示将 html 文件加载/导入到 pdf 文档的选项。 |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Binary Flag 指定一组标志，这些标志与其他选项共同决定页面的尺寸和布局。 |
| [HtmlSaveOptions](./htmlsaveoptions/) | 导出为 Html 格式的保存选项 |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | 此枚举描述了转换过程中可能的抗锯齿措施 |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | 此类表示与 PDF 转换为 HTML 格式时自定义 CSS 保存相关的一组数据 |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | 您可以将自定义策略分配给此属性，该策略实现对在 PDF 转换为 HTML 期间创建的某个 CSS 部分的处理和/或保存。在这种情况下，处理（例如保存到流或磁盘）必须在该自定义代码中完成 |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | 您可以将由自定义方法创建的委托分配给此属性，该方法实现生成 HTML 文档中引用的 CSS 的 URL。例如，如果您希望在 HTML 中引用的 CSS 为 \"otherPage.ASPX?CssID=zjjkklj\"，则此自定义策略必须返回 \"otherPage.ASPX?CssID=zjjkklj\" |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | 表示与转换器向自定义代码请求以获取目标 CSS 的期望 URL（或 URL 模板）相关的一组数据 |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | 此枚举定义了调优编码逻辑的规则 |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | 枚举可用于保存已保存 PDF 中引用的字体的模式。 |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | 此类表示在 PDF 转换为 HTML 期间与外部资源图像文件保存相关的一组数据。 |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | 枚举在 Pdf 转换为 Html 期间可以保存为外部资源的图像文件的可能类型 |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | 有时会出现对生成的 HTML 的特定需求。此枚举定义了在 PDF 转换为 HTML 期间可用于满足此类特定需求的 HTML 准备模式。 |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | 如果 HtmlSaveOptions 的 SplitToPages 属性为 true，则在 PDF 转换为 HTML 期间会创建多个 HTML 文件（每个转换的页面一个 HTML 文件）。此类表示在 PDF 转换为 HTML 期间与自定义保存单个 HTML 页面标记相关的一组数据 |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | 转换结果可能包含一个或多个 HTML 页面（这些页面也可能引用图像或字体等外部文件）。您可以将由自定义方法创建的委托分配给此属性，该方法实现对在转换期间生成的 HTML 页面（HTML 本身）的处理。在这种情况下，处理（例如保存到流或磁盘）可以在该自定义代码中完成。此时，保存 HTML 页面标记的所有必要操作必须在提供的方法代码中完成，因为转换器代码中的保存将不再使用。如果由于某种原因必须由转换器自身的代码而非自定义代码进行处理，请在自定义代码中设置 'htmlSavingInfo' 参数变量的标志 'CustomProcessingCancelled'：它向转换器指示，所有对该资源的必要处理步骤应由转换器本身完成，就像没有任何外部自定义保存代码一样。 |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | 枚举图像可能所属的父级类型，图像可以属于 HTML 页面或 SVG 父图像 |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | 此枚举列举了在 HTML 中嵌入引用文件的可能模式。它允许控制引用的文件（HTML、字体、图像、CSS）是嵌入到主 HTML 文件中，还是作为独立的二进制实体生成 |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | 转换后的 PDF 可能包含光栅图像（.png、.jpeg 等）。此枚举定义了在 PDF 转换为 HTML 期间如何处理光栅图像的方法 |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | 您可以将由自定义方法创建的委托分配给此属性，该方法实现对从 PDF 中提取并在 PDF 转换为 HTML 期间必须保存为外部资源的外部资源（字体或图像）的处理。在这种情况下，处理（例如保存到流或磁盘）可以在该自定义代码中完成，并且该自定义代码必须返回路径（或任何不带引号的字符串），该路径随后会被合并到生成的 HTML 中，以替代原本假定的图像资源路径。此时，保存图像的所有必要操作必须在提供的方法代码中完成，因为转换器代码中的保存将不再使用。如果由于某种原因必须由转换器自身的代码而非自定义代码进行处理，请在自定义代码中设置 'resourceSavingInfo' 参数变量的标志 'CustomProcessingCancelled'：它向转换器指示，所有对该资源的必要处理步骤应由转换器本身完成，就像没有任何外部自定义代码一样。 |
| [Hyperlink](./hyperlink/) | 表示抽象超链接。 |
| [IconFit](./iconfit/) | 描述小部件注释的图标应如何显示在其注释矩形内。 |
| [Id](./id/) | <p> 表示文件标识符结构。 </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | 表示图像。 |
| [ImageDeleteAction](./imagedeleteaction/) | 当图像对象从集合中移除时执行的操作。如果图像对象被移除 |
| [ImagePlacement](./imageplacement/) | <p> 表示放置在 Pdf 文档页面上的图像的特性。 </p> <hr> <pre> 示例演示如何在第一页 PDF 文档页面上查找图像并获取具有可见尺寸的位图图像。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> 当图像放置到页面时，其尺寸可能不同于 {@code Resources} 中定义的物理尺寸。对象 {@code ImagePlacement} 用于提供此类信息，如尺寸、分辨率等。 </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> 表示图像放置对象的吸收器。执行图像使用搜索，并通过 {@code ImagePlacementAbsorber.ImagePlacements} 集合提供对搜索结果的访问。 </p> <hr> <pre> 示例演示如何在第一页 PDF 文档中查找图像并获取图像放置属性。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> {@code ImagePlacementAbsorber} 对象基本用于图像搜索场景。搜索完成后，出现的实例由 {@code ImagePlacement} 对象表示，这些对象包含在 {@code ImagePlacementAbsorber.ImagePlacements} 集合中。{@code ImagePlacement} 对象提供对图像放置属性的访问：尺寸、分辨率等。 </p> 图像的正向旋转是逆时针方向，而页面的正向旋转是顺时针方向。在此，我们需要表示图像的旋转角度，因此需要从图像角度中减去页面角度。 |
| [ImagePlacementCollection](./imageplacementcollection/) | 表示图像放置集合 |
| [ImageStamp](./imagestamp/) | 表示图形印章。 |
| [ImageType](./imagetype/) | 表示图像格式类型。 |
| [ImportDataAction](./importdataaction/) | 在调用 import-data 操作时，表单数据格式（FDF）数据应从指定文件导入到文档的交互式表单中。 |
| [ImportFieldsOptions](./importfieldsoptions/) | 表示导入表单字段选项的基类。 |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | 表示导入表单字段到 Json 格式的选项。继承自 {@code ImportFieldsOptions} 并添加了针对 Json 导入的特定选项。 |
| [ImportOptions](./importoptions/) | ImportOptions 类型在各个导入选项上保持抽象层级。 |
| [InkAnnotation](./inkannotation/) | 表示由一个或多个不相连路径组成的手绘“涂鸦”。 |
| [InternalHelper](./internalhelper/) | 内部类 |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | 当对表单类型的操作无效时抛出的异常。 |
| [JavascriptAction](./javascriptaction/) | 表示 JavaScript 操作的类。 |
| [JavaScriptCollection](./javascriptcollection/) | 此类表示 JavaScript 的集合。 |
| [LatexFragment](./latexfragment/) | 表示 TeX 片段。@deprecated 请使用 TeXFragment 替代 |
| [LatexLoadOptions](./latexloadoptions/) | 表示将 TeX 文件加载/导入到 PDF 文档的选项。@deprecated 请使用 TeXLoadOptions 替代。 |
| [LaTeXSaveOptions](./latexsaveoptions/) | 导出为 TeX 格式的保存选项。@deprecated 请使用 TeXSaveOptions 替代 |
| [LaunchAction](./launchaction/) | 表示启动操作，可启动应用程序或打开或打印文档。 |
| [Layer](./layer/) | 表示 PDF 页面中的图层。 |
| [LevelFormat](./levelformat/) | 表示目录的格式。 |
| [License](./license/) | 提供对组件进行授权的方法。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。 License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | 表示许可证信息。 |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | 轻量级操作符集合。旨在在底层内容流未附加的情况下使用，此时仅需要操作符集合作为结果。 |
| [LineAnnotation](./lineannotation/) | 表示线注释的类。 |
| [LineEndingConverter](./lineendingconverter/) | 表示 LineEndingConverter 类 |
| [LineEndingsDrawer](./lineendingsdrawer/) | 为注释绘制线端点。仅供内部使用的内部类。 |
| [LinkAnnotation](./linkannotation/) | 表示文档中指向其他位置的超文本链接或要执行的操作。 |
| [ListBoxField](./listboxfield/) | 类表示 ListBox 字段。 |
| [LoadOptions](./loadoptions/) | LoadOptions 类型保存对各个加载选项的抽象层级。 |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | 表示转换过程中页边距区域的使用模式（如 HTML、EPUB 等），定义对导入格式中与页边距使用相关指令的处理。 |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | 注意！该功能已实现，但由于在 OSHARED 层发现的阻塞问题尚未公开到 API。表示转换过程中页面尺寸的使用模式。诸如 HTML、EPUB 等格式通常采用浮动布局，因此可以适配所需的页面尺寸。但有时内容指定了水平位置或尺寸，导致无法放入所需的页面尺寸。在这种情况下，我们可以定义应如何处理（即当内容尺寸不符合结果 PDF 文档的初始页面尺寸时）。 |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | 自定义加载资源的结果 |
| [LocaleOptions](./localeoptions/) | LocaleOptions 类型指定 Aspose.PDF 的区域设置配置。 |
| [LocalHyperlink](./localhyperlink/) | 表示本地超链接对象。 |
| [MarginInfo](./margininfo/) | 此类表示不同对象的边距。 |
| [MarkupAnnotation](./markupannotation/) | 表示标记注释的抽象类。 |
| [MarkupParagraph](./markupparagraph/) | 表示一个段落。 |
| [MarkupSection](./markupsection/) | 表示标记章节——页面上包含文本的矩形区域，可在视觉上与其他文本块区分开来。 |
| [Matrix](./matrix/) | 类表示变换矩阵。 |
| [Matrix3D](./matrix3d/) | 类表示变换矩阵。 |
| [MdLoadOptions](./mdloadoptions/) | Markdown 格式转换的加载选项。 |
| [Measure](./measure/) | 描述 Measure 坐标系的类。 |
| [Measure.NumberFormat](./measure.numberformat/) | 度量的数字格式。 |
| [Measure.NumberFormatList](./measure.numberformatlist/) | 表示数字格式列表。 |
| [MediaClip](./mediaclip/) | 描述呈现的媒体剪辑对象的类。 |
| [MediaClipData](./mediaclipdata/) | 描述媒体剪辑数据的类。 |
| [MediaClipSection](./mediaclipsection/) | 此类描述媒体剪辑章节。 |
| [MediaRendition](./mediarendition/) | 描述媒体呈现的类。 |
| [MemoryCleaner](./memorycleaner/) | 表示 MemoryCleaner 类 |
| [MemoryExtender](./memoryextender/) | 表示 MemoryExtender 类。在堆内存受限的系统上使用大文件时，可以启用它使用磁盘空间作为临时交换内存。 |
| [MemoryFontSource](./memoryfontsource/) | 表示单个字体文件来源。 |
| [Metadata](./metadata/) | 提供对 XMP 元数据流的访问。 |
| [Metered](./metered/) | <p> 提供设置计量密钥的方法。 </p> <hr> 在此示例中，将尝试设置计量的公钥和私钥 <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | 表示加载/导入 .mht 文件到 pdf 文档的选项。 |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | 导出为 Xml 格式的保存选项。 |
| [MovieAnnotation](./movieannotation/) | 表示包含动画图形和声音的电影注释，可在计算机屏幕上和扬声器中呈现。当注释被激活时，电影将播放。 |
| [NamedAction](./namedaction/) | 表示 PDF 查看器应用程序应支持的命名操作。 |
| [NamedDestination](./nameddestination/) | 目的地可以不使用显式语法直接定义，而是通过名称对象或字节串间接引用。 |
| [Note](./note/) | 此类表示 generator paragraph note。 |
| [NumberField](./numberfield/) | 带有指定有效字符的文本字段 @see TextBoxField |
| [NumberTree](./numbertree/) | 表示 PDF 文件的 Number 树结构的类。7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | 表示签名过程使用的 ocsp 设置。 |
| [OfdLoadOptions](./ofdloadoptions/) | OFD 格式的加载选项。 |
| [Operator](./operator/) | 表示运算符的抽象类。 |
| [OperatorCollection](./operatorcollection/) | 类表示运算符的集合。 |
| [OperatorSelector](./operatorselector/) | 此类用于使用 Visitor 模板思想选择运算符。 |
| [Opi](./opi/) | 表示 Open Prepress Interface (OPI) 是一种为高分辨率图像创建低分辨率占位符或代理的机制。 |
| [OptimizedMemoryStream](./optimizedmemorystream/) | 定义一个可以容纳更大标准容量的 MemoryStream。 |
| [Option](./option/) | 类表示选择字段的选项。 |
| [OptionCollection](./optioncollection/) | 表示选择字段选项集合的类。 |
| [OutlineCollection](./outlinecollection/) | 表示文档大纲层次结构。 |
| [OutlineItemCollection](./outlineitemcollection/) | 表示 PDF 文档大纲层次结构中的大纲条目。 |
| [Outlines](./outlines/) | 类描述大纲的集合。 |
| [OutputIntent](./outputintent/) | 表示一种输出意图，使 PDF 文档的颜色特性与目标输出设备或文档将被打印的生产环境的颜色特性相匹配。 |
| [OutputIntents](./outputintents/) | 表示 {@link OutputIntent} 的集合。 |
| [Page](./page/) | 表示 PDF 文档页面的类。 |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | 自定义页眉和页脚的过程。 |
| [PageActionCollection](./pageactioncollection/) | 此类描述页面操作。 |
| [PageCollection](./pagecollection/) | PDF 文档页面的集合。 |
| [PageExtensions](./pageextensions/) | 为 Page 类提供额外功能。 |
| [PageInfo](./pageinfo/) | 表示 pdf 生成器的页面信息。 |
| [PageInformationAnnotation](./pageinformationannotation/) | 表示 PDF 文档中的 Page Information 注释。此注释包含文件名、页码以及注释创建的日期和时间。此类主要用于向 PDF 文档的特定页面添加元数据，这对于跟踪和引用非常有用。例如，可在打印过程中标记页面，或在查看文档时提供关于页面的额外信息。 |
| [PageLabel](./pagelabel/) | 表示 Page Label 范围的类。 |
| [PageLabelCollection](./pagelabelcollection/) | 表示页面标签集合的类。 |
| [PageMarkup](./pagemarkup/) | 页面标记由 {@code MarkupSection} 和 {@code MarkupParagraph} 的集合表示。 |
| [PageNumberStamp](./pagenumberstamp/) | 表示页码戳记，用于给页面编号。 |
| [PageSize](./pagesize/) | 表示 PDF 文档中页面尺寸的类。 |
| [PaginationArtifact](./paginationartifact/) | 表示文档中分页工件的抽象基类。 |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> 表示页面结构对象（如章节和段落）的吸收器对象。执行对章节和段落文本的搜索，并提供对描述文本坐标空间的矩形和多边形的访问。还执行文本片段搜索，并通过按结构元素分组的 {@code TextFragments} 集合提供对搜索结果的访问。 </p> 示例演示如何在第一个 PDF 文档页面上找到每个段落的第一个文本片段并高亮显示它。 <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> 当搜索完成后，{@code ParagraphAbsorber.PageMarkups} 集合将包含表示页面结构的 {@code PageMarkup} 对象，这些对象由 {@code MarkupSection} 和 {@code MarkupParagraph} 的集合组成。{@code TextFragment} 对象提供对搜索到的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。 |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | 表示 {@link ParagraphAbsorber} 的选项。 |
| [Paragraphs](./paragraphs/) | 此类表示段落集合。 |
| [PasswordBoxField](./passwordboxfield/) | 描述用于输入密码的文本字段的类。 |
| [PclLoadOptions](./pclloadoptions/) | 表示将 PCL 文件加载（导入）到 pdf 文档的选项。 |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | 枚举可用于转换的转换引擎。 |
| [PDF3DAnnotation](./pdf3dannotation/) | 类 PDF3DAnnotation。此类不可继承。@see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | 类 PDF3DArtwork。 |
| [PDF3DContent](./pdf3dcontent/) | 类 PDF3DContent。 |
| [PDF3DCrossSection](./pdf3dcrosssection/) | 类 PDF3DCrossSection。 |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | 类 PDF3DCrossSectionArray。 |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | 类 PDF3DCuttingPlaneOrientation。 |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | 类 PDF3DLightingScheme。 |
| [PDF3DRenderMode](./pdf3drendermode/) | 类 PDF3DRenderMode。 |
| [PDF3DStream](./pdf3dstream/) | 类 PDF3DStream。 |
| [PDF3DView](./pdf3dview/) | 类 PDF3DView。 |
| [PDF3DViewArray](./pdf3dviewarray/) | 类 PDF3DViewArray。 |
| [PdfAction](./pdfaction/) | 表示 PDF 文档中的操作 |
| [PdfActionCollection](./pdfactioncollection/) | 类描述操作列表。 |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | 此类描述可用于调节在 TrueType 符号字体拥有多个编码时复制编码数据过程的规则。某些 PDF 文档在转换为 PDF/A 格式后可能会出现错误 "More than one encoding in symbolic TrueType font's cmap"。导致此错误的原因是什么？所有 TrueType 符号字体在其内部数据中都有特殊的 "cmap" 表。该表将字符代码映射到字形索引。该表还可能包含描述所使用编码的不同编码子表。有关 cmap 表的高级信息，请参阅 https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html。通常 cmap 表包含多个编码子表，但 PDF/A 标准要求在 PDF/A 文档中该字体只能保留一个编码子表，或者在该字体的子表中必须包含一个 (3,0) 编码子表。关键问题是——必须从其他子表中获取哪些数据复制到目标编码表 (3,0)？大多数字体拥有“良好构造”的 cmap 表，其中每个编码子表都与其他子表完全一致。但有些字体的 cmap 表存在冲突——例如，一个子表为 Unicode 100 提供字形索引 100，而另一个子表为相同的 Unicode 100 提供字形索引 200。为解决此问题需要特殊策略。默认使用以下策略：查找 mac 子表 (1,0)。如果找到该表，则仅使用此数据填充目标表 (3,0)。如果未找到 mac 子表，则遍历除 (3,0) 之外的所有子表，并将数据复制到目标 (3,0) 子表。此外，仅当目标表当前不包含某个 unicode 时，才会将每个 unicode（unicode，字形索引）的映射复制到目标表中。因此，例如如果第一个子表为 Unicode 100 提供字形索引 100，而下一个子表为相同的 Unicode 100 提供字形索引 200，则仅会复制第一个子表（unicode=100，字形索引=100）的数据。因此，每个前面的子表优先于后面的子表。此类的属性 { PdfASymbolicFontEncodingStrategy} 有助于调节默认行为。如果设置了类型为 { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} 的属性 {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable})，则相关子表将在优先级上高于 mac 子表 (1,0)。枚举 {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} 中的值 'MacTable' 在此情况下没有意义，因为它指向同一个默认使用的 mac 子表 (1,0)。属性 {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) 会丢弃所有子表的优先级。如果设置了此属性，则仅按指定顺序使用声明队列中的子表。如果未找到指定的子表，则会使用所有子表的默认遍历以及上述复制策略。对象 { PdfASymbolicFontEncodingStrategy.QueueItem} 指定使用的编码子表。可以通过成员组合（PlatformID、PlatformSpecificId）或通过枚举 { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} 来设置此子表。如果字体没有 (3,0) 子表，则会使用其他子表以保持 PDF/A 兼容性。所使用的子表选择遵循前述相同规则，即使用 {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) 和 {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) 属性来确定最终子表；如果字体也没有请求的子表，则会使用任何现有的子表。 |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | 指定编码子表。每个编码子表都有唯一的参数组合 (PlatformID, PlatformSpecificID)。实现了枚举 {@code CMapEncodingTableType} 和属性 {@code CMapEncodingTable}，以便更容易设置所需的编码子表。 |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | 声明一组已知的编码子表。 |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | 表示用于转换 PDF 文档的选项集合。 |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | 此类持有标志，用于在源 PDF 文档不符合 PDF 规范的情况下控制 PDF/A 转换。如果使用此类的标志会降低性能，但在源 PDF 文档无法通过常规方式转换为 PDF/A 格式时是必要的。默认情况下，所有标志均设置为 false。 |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | 某些 PDF 文档包含属于私用区 (PUA) 的特殊 Unicode 符号，详见 https://en.wikipedia.org/wiki/Private_Use_Areas。此类符号会导致 PDF/A 合规错误，例如 "Text is mapped to Unicode Private Use Area but no ActualText entry is present"。此枚举声明了可用于处理 PUA 符号的策略。 |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | 某些文档在转换为 PDF/A 格式后体积较大。为减小这些文档的文件大小，需要定义字体移除策略。此枚举声明了可用于优化字体使用的策略。此枚举中的每个策略仅在设置了标志 {@code OptimizeFileSize} 时才有意义。 |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | 描述用于对齐文档文本段落的策略。目前仅支持将段落恢复到原始边界的策略。未来可能会添加其他策略。 |
| [PdfPageStamp](./pdfpagestamp/) | 类表示使用 PDF 页面作为印章的印章。 |
| [PdfSaveOptions](./pdfsaveoptions/) | 导出为 Pdf 格式的保存选项。 |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | PdfXml 格式的加载选项。 |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | PdfXml 格式的保存选项。 |
| [Permissions](./permissions/) | 二进制标志 此枚举表示用户对 PDF 的权限。 |
| [PKCS1](./pkcs1/) | 表示关于 PKCS#1 标准的签名对象。签名使用 RSA 加密算法和 SHA-1 摘要方法。 |
| [PKCS7](./pkcs7/) | 表示符合互联网 RFC 2315 中 PKCS#7 规范（PKCS #7：加密消息语法，版本 1.5）的 PKCS#7 对象。文档字节范围的 SHA1 摘要被封装在 PKCS#7 SignedData 字段中。 |
| [PKCS7Detached](./pkcs7detached/) | 表示符合互联网 RFC 2315 中 PKCS#7 规范（PKCS #7：加密消息语法，版本 1.5）的 PKCS#7 对象。文档字节范围的原始签名消息摘要被作为普通的 PKCS#7 SignedData 字段加入。PKCS#7 SignedData 字段中不应封装任何数据。 |
| [Point](./point/) | 表示具有分数坐标的点。 |
| [Point3D](./point3d/) | 表示具有分数坐标的点。 |
| [PolyAnnotation](./polyannotation/) | 多注释的抽象基类。 |
| [PolygonAnnotation](./polygonannotation/) | 表示多边形注释的类。 |
| [PolylineAnnotation](./polylineannotation/) | 表示折线注释，其类似于多边形，但首尾顶点不隐式相连。 |
| [PopupAnnotation](./popupannotation/) | 表示弹出注释，可在弹出窗口中显示文本以进行输入和编辑。 |
| [Position](./position/) | 表示位置对象 |
| [PptxSaveOptions](./pptxsaveoptions/) | 导出为 SVG 格式的保存选项 |
| [PrintController](./printcontroller/) | 表示打印控制器。 |
| [PrintDuplex](./printduplex/) | 从打印对话框打印文件时使用的纸张处理选项。 |
| [PrinterMarkAnnotation](./printermarkannotation/) | 表示打印机标记注释的抽象类。 |
| [PrinterMarksKind](./printermarkskind/) | 指定要添加到文档中的打印机标记类型。此枚举具有 {@link FlagsAttribute} 属性，允许对其成员值进行按位组合。 |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | 为 {@link PrinterMarksKind} 枚举提供扩展方法。 |
| [PrintScaling](./printscaling/) | 在为此文档显示打印对话框时应选择的页面缩放选项。 |
| [ProgressEventType](./progresseventtype/) | 此枚举描述转换过程中可能出现的进度事件类型。 |
| [PsLoadOptions](./psloadoptions/) | 表示加载/导入 .mht 文件到 pdf 文档的选项。 |
| [PsSaveOptions](./pssaveoptions/) | 导出为 PS（PostScript）或 EPS 格式的保存选项。 |
| [RadioButtonField](./radiobuttonfield/) | 表示单选按钮字段的类。 |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | 表示 RadioButton 字段项的类。 |
| [Rectangle](./rectangle/) | 表示矩形的类。 |
| [Redaction](./redaction/) | 仅供内部使用 @author User |
| [RedactionAnnotation](./redactionannotation/) | 表示遮蔽注释。 |
| [RegexManager](./regexmanager/) | 提供正则表达式操作的包装器，可配置超时设置。 |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | 表示一个注册标记注释。注册标记是添加到印版或屏幕上的符号，用于确保印刷过程中颜色的正确对齐。 |
| [RenderingOptions](./renderingoptions/) | 表示渲染选项 |
| [RenderModeType](./rendermodetype/) | 枚举 RenderModeType：一组渲染模式类型 |
| [Rendition](./rendition/) | 描述 RendtionAnnotation 的呈现对象的类。 |
| [RenditionAction](./renditionaction/) | 控制多媒体内容播放的呈现操作。 |
| [RenditionOperation](./renditionoperation/) | 当操作被触发时要执行的操作。 |
| [RenditionType](./renditiontype/) | 枚举描述了可能的呈现类型。 |
| [Resources](./resources/) | 表示页面资源的类。 |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | 表示带有某些值的 ExtGStates。 |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | 表示 RGB 到设备灰度颜色空间的转换策略。 |
| [RichMediaAnnotation](./richmediaannotation/) | 描述 RichMediaAnnotation 的类，该类允许将视频/音频数据嵌入 PDF 文档。 |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | 激活注释的事件。 |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | 多媒体的类型。 |
| [RichTextBoxField](./richtextboxfield/) | 描述富文本编辑器组件的类。 |
| [RichTextFontStyles](./richtextfontstyles/) | RichText 中文本片段样式的选项。 |
| [RootElement](./rootelement/) | 根结构元素。 |
| [Row](./row/) | 表示表格的一行。 |
| [Rows](./rows/) | 表示表格的行集合。 |
| [RtfLoadOptions](./rtfloadoptions/) | RTF 格式的加载选项。 |
| [SaveOptions](./saveoptions/) | SaveOptions 类型在各个保存选项上保持抽象层级。 |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | 此类的实例表示可以在某些结果文档上绘制的边框信息。 |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | 表示边框（上、下、左侧或右侧）某一部分的信息。 |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | 此类的实例表示可以在某些结果文档上绘制的页面边距信息。 |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | 表示边距（上、下、左侧或右侧）某一部分的信息。 |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | 此类表示在将 PDF 转换为其他格式（例如 HTML）期间涉及外部资源文件保存的一组数据。 |
| [ScalingMode](./scalingmode/) | 应使用的缩放类型。 |
| [ScalingReason](./scalingreason/) | 在注释矩形内对图标进行缩放的情况。 |
| [ScreenAnnotation](./screenannotation/) | 屏幕注释，指定页面上可播放媒体剪辑的区域。 |
| [SelectorRendition](./selectorrendition/) | 类描述选择器呈现。 |
| [Signature](./signature/) | 抽象类，表示 PDF 文档中的签名对象。签名是包含签名对象值的字段，后者包含用于验证文档有效性的数据。 |
| [SignatureCustomAppearance](./signaturecustomappearance/) | 抽象类，表示签名自定义外观对象。 |
| [SignatureField](./signaturefield/) | 表示签名表单字段。 |
| [SignHash](./signhash/) | 用于自定义签署文档哈希的委托（Beta）。 |
| [SoundAnnotation](./soundannotation/) | 表示包含从计算机麦克风录制或从文件导入的声音的声音注释。 |
| [SoundData](./sounddata/) | 表示定义在激活注释时播放的声音的数据。 |
| [SoundEncoding](./soundencoding/) | 样本数据的编码格式。 |
| [SoundIcon](./soundicon/) | 枚举用于显示注释的图标。 |
| [SoundIconConverter](./soundiconconverter/) | 表示 SoundIconConverter 类 |
| [SoundSampleData](./soundsampledata/) | 表示特定于声音对象的附加条目（第 9.2 节 PDF1-7） |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | 声音样本数据的编码格式。 |
| [SquareAnnotation](./squareannotation/) | 表示方形注释的类。 |
| [SquigglyAnnotation](./squigglyannotation/) | 表示在文档文本中出现锯齿下划线的波浪形注释。 |
| [Stamp](./stamp/) | 用于各种作为子类出现的印章的抽象类。 |
| [StampAnnotation](./stampannotation/) | <p> 表示橡胶印章注释。此类注释显示旨在看起来像用橡胶印章盖在页面上的文本或图形。 </p> <hr> <pre> 以下代码片段演示如何在第一个 PDF 文档页中添加 2 个印章。输入文档来自 inFile，修改后保存到 outFile。第一个印章使用图标 NotForPublicRelease，第二个使用来自 rubber.jpg 的图像。 Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream(\"rubber.jpg\", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | 表示 StampIconConverter 类 |
| [StrikeOutAnnotation](./strikeoutannotation/) | 表示在文档文本中出现删除线的删除线注释。 |
| [StructElement](./structelement/) | 通用结构元素。 |
| [SubjectNameElements](./subjectnameelements/) | 枚举描述签名主题字符串中的元素。 |
| [SubmitFormAction](./submitformaction/) | 描述 submit-form 操作的类。 |
| [SvgLoadOptions](./svgloadoptions/) | 表示将 SVG 文件加载/导入到 PDF 文档的选项。 |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | 枚举可用于转换的转换引擎。 |
| [SvgSaveOptions](./svgsaveoptions/) | 导出为 SVG 格式的保存选项 |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | 此类表示在 PDF 转换为 HTML 期间与外部资源图像文件保存相关的一组数据。 |
| [Symbology](./symbology/) | A (Barcode) Symbology 定义特定类型条形码的技术细节：条的宽度、字符集、编码方法、校验和规范等。 |
| [SystemFontSource](./systemfontsource/) | 表示系统中已安装的所有字体。 |
| [TabAlignmentType](./tabalignmenttype/) | 枚举制表符对齐类型。 |
| [Table](./table/) | 表示可以添加到页面的表格。 |
| [TableAbsorber](./tableabsorber/) | <p> 表示表元素的吸收器对象。执行搜索并通过 {@code TableAbsorber.TableList} 集合提供对搜索结果的访问。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上查找表格并替换表格单元格中的文本。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | 枚举制表符前导字符类型。 |
| [TableBroken](./tablebroken/) | 枚举表格中断情况。 |
| [TabOrder](./taborder/) | 页面上的制表顺序 |
| [TabStop](./tabstop/) | 表示段落中自定义的制表位位置。 |
| [TabStops](./tabstops/) | 表示 {@code TabStop} 对象的集合。 |
| [TeXFragment](./texfragment/) | 表示 LaTeX 片段。 |
| [TeXLoadOptions](./texloadoptions/) | 表示将 TeX 文件加载/导入到 PDF 文档的选项。 |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | 实现从内存获取输出流。例如，当您不希望伴随的输出（如日志文件）写入磁盘，而希望随后从内存中读取时，可使用它。 |
| [TeXSaveOptions](./texsaveoptions/) | 导出为 TeX 格式的保存选项 |
| [TextAbsorber](./textabsorber/) | <p> 表示文本的吸收器对象。执行文本提取并通过 {@code TextAbsorber.Text} 对象提供对结果的访问。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上提取文本。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> {@code TextAbsorber} 对象用于从 Pdf 文档或文档的页面中提取文本。 </p> |
| [TextAnnotation](./textannotation/) | 表示附加在 PDF 文档某一点的 \"sticky note\" 文本注释。 |
| [TextBoxField](./textboxfield/) | 表示文本框字段的类。 |
| [TextBuilder](./textbuilder/) | 将文本对象追加到 Pdf 页面。 |
| [TextDefaults](./textdefaults/) | 定义文本子系统默认值 |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | 指定文本子系统默认值的类型 |
| [TextEditOptions](./texteditoptions/) | 描述文本编辑操作的选项。 |
| [TextElement](./textelement/) | 文档逻辑结构的一般文本元素。 |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | 描述 PDF 文档中出现的文本提取错误。 |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | 表示 PDF 文档中出现文本提取错误的位置。 |
| [TextExtractionOptions](./textextractionoptions/) | 表示文本提取选项 |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | 定义在将 PDF 文档转换为文本时可使用的不同模式。参见 {@code TextDevice} 类。 |
| [TextFormattingOptions](./textformattingoptions/) | 表示文本格式化选项 |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | 定义行间距细节 |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | 定义换行策略 |
| [TextFragment](./textfragment/) | <p> 表示 PDF 文本的片段。 </p> <hr> <pre> 示例演示如何在 PDF 文档的第一页查找文本并替换该文本及其字体。 // Open document Document doc = new Document("input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("output.pdf"); </pre> <hr> <pre> 简而言之，{@code TextFragment} 对象包含 {@code TextSegment} 对象的列表。详细说明：{@code com.aspose.pdf} 中的 PDF 文本由两种基本对象表示：{@code TextFragment} 和 {@code TextSegment}。它们之间的差异主要取决于上下文。我们考虑以下场景。用户搜索文本 "hello world" 以进行操作、修改其属性等。 Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> PDF 文本的物理表示非常复杂。文本 "hello world" 可能由多个物理上独立的文本段组成。Aspose.Pdf 文本模型基本上规定 {@code TextFragment} 对象在表示用户查询的物理 {@code TextSegment} 对象集合之上提供单一的逻辑操作集。在文本搜索场景中，{@code TextFragment} 是逻辑上的 "hello world" 文本表示，而 {@code TextSegment} 对象集合则表示构成 "hello world" 文本对象的所有物理段。因此，{@code TextFragment} 接近逻辑文本表示，{@code TextSegment} 接近物理文本表示。显然，每个 {@code TextSegment} 对象可能拥有自己的字体、颜色、定位属性。{@code TextFragment} 提供了一种简便的方法来更改文本及其属性：设置字体、设置字体大小、设置字体颜色等。同时，{@code TextSegment} 对象是可访问的，用户能够独立操作 {@code TextSegment} 对象。 <p> 请注意，修改 TextFragment 属性可能会更改内部 {@code Segments} 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部段或将它们合并为单个段。如果您的需求是保持 {@code Segments} 集合不变，请单独修改内部段。 </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> 表示文本片段的吸收器对象。执行文本搜索并通过 {@code TextFragmentAbsorber.TextFragments} 集合提供对搜索结果的访问。 </p> <hr> <pre> 示例演示如何在 PDF 文档的第一页查找文本并替换该文本及其字体。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> {@code TextFragmentAbsorber} 对象基本上用于文本搜索场景。搜索完成后，出现的匹配项以 {@code TextFragment} 对象的形式表示，这些对象包含在 {@code TextFragmentAbsorber.TextFragments} 集合中。{@code TextFragment} 对象提供对搜索匹配文本、文本属性的访问，并允许编辑文本以及更改文本状态（字体、字体大小、颜色等）。 </p> |
| [TextFragmentCollection](./textfragmentcollection/) | 表示文本片段集合 |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> 表示文本片段的文本状态。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象更改文本的颜色和字体大小。 // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> 提供了一种更改文本以下属性的方法：字体（{@code TextFragmentState.Font} 属性） 字体大小（{@code TextFragmentState.FontSize} 属性） 字体样式（{@code TextFragmentState.FontStyle} 属性） 前景色（{@code TextFragmentState.ForegroundColor} 属性） 背景色（{@code TextFragmentState.BackgroundColor} 属性） <p> 请注意，修改 {@code TextFragmentState} 属性可能会更改内部 {@code TextFragment.Segments} 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部段或将它们合并为单个段。如果您的需求是保持 {@code TextFragment.Segments} 集合不变，请单独修改内部段。 </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | 枚举用于显示注释的图标。 |
| [TextIconConverter](./texticonconverter/) | 表示 TextIconConverter 类 |
| [TextMarkupAnnotation](./textmarkupannotation/) | 文本标记注释的抽象基类。 |
| [TextOptions](./textoptions/) | 表示文本处理选项 |
| [TextParagraph](./textparagraph/) | <p> 表示文本段落为多行文本对象。 </p> <hr> <pre> 示例演示如何创建文本段落对象并将其追加到 PDF 页面。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // 创建文本段落 TextParagraph paragraph = new TextParagraph(); // 设置段落矩形 paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // 设置换行选项 paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // 追加字符串行 paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // 使用 TextBuilder 将段落追加到 PDF 页面 TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // 保存 PDF 文档 doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | TextParagraph 的背景模式 |
| [TextParagraphAbsorber](./textparagraphabsorber/) | 表示文本段落的吸收器对象。执行文本搜索并通过 {@code TextParagraphAbsorber.TextParagraphs} 集合提供对搜索结果的访问。 |
| [TextParagraphCollection](./textparagraphcollection/) | 表示文本段落集合 |
| [TextReplaceOptions](./textreplaceoptions/) | 表示文本替换选项 |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | 确定在将文本片段替换为更短后将执行的操作。None - 不执行任何操作，替换后的文本可能会覆盖行的其余部分；AdjustSpaceWidth - 尝试调整单词之间的空格以保持行长度；WholeWordsHyphenation - 尝试在段落行之间分配单词以保持段落的右侧对齐；ShiftRestOfLine - 根据文本长度的变化移动行的其余部分，行的长度可能会被改变；默认值为 ShiftRestOfLine。 |
| [TextSearchOptions](./textsearchoptions/) | 表示文本搜索选项 |
| [TextSegment](./textsegment/) | <p> 表示 PDF 文本的片段。 </p> <hr> <pre> 示例演示如何使用 {@code TextSegment} 对象的 {@code TextState} 对象更改文本的颜色和字体大小。 // 打开文档 Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 为第一页接受吸收器 doc.getPages().get(1).accept(absorber); // 更改首次文本出现的第一个文本片段的前景色 absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // 更改首次文本出现的第一个文本片段的字体大小 absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // 保存文档 doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> 简而言之，{@code TextSegment} 对象是 {@code TextFragment} 对象的子对象。 详细说明：{@code Aspose.Pdf} 中 PDF 文档的文本由两个基本对象表示：{@code TextFragment} 和 {@code TextSegment}。 它们之间的差异主要取决于上下文。 让我们考虑以下场景。 用户搜索文本 "hello world" 以对其进行操作、更改其属性、查看等。 Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> PDF 文本的物理表示非常复杂。文本 "hello world" 可能由多个物理独立的文本片段组成。Aspose.PDF 文本模型基本上规定 {@code TextFragment} 对象在表示用户查询的物理 {@code TextSegment} 对象集合之上提供单一的逻辑操作集合。在文本搜索场景中，{@code TextFragment} 是逻辑上的 "hello world" 文本表示，而 {@code TextSegment} 对象集合则表示构成 "hello world" 文本对象的所有物理片段。因此，{@code TextFragment} 接近逻辑文本表示，{@code TextSegment} 接近物理文本表示。显然，每个 {@code TextSegment} 对象可能拥有其自己的字体、颜色、定位属性。{@code TextFragment} 提供了一种简单的方法来更改文本及其属性：设置字体、设置字体大小、设置字体颜色等。与此同时，{@code TextSegment} 对象是可访问的，用户能够独立地操作 {@code TextSegment} 对象。 </p> |
| [TextSegmentCollection](./textsegmentcollection/) | 表示文本片段集合 |
| [TextStamp](./textstamp/) | 表示文本印章。 |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | 当字体不包含所需字符时要执行的操作。 |
| [TextState](./textstate/) | 表示文本的文本状态 |
| [TextStyle](./textstyle/) | 类表示复选框字段。 |
| [TimestampSettings](./timestampsettings/) | 表示签名过程使用的 ocsp 设置。 |
| [TocInfo](./tocinfo/) | 表示目录信息。 |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | 此类描述可用于解决 Adobe Preflight 错误 "Text cannot be mapped to Unicode" 的规则。 |
| [TrimMarkAnnotation](./trimmarkannotation/) | 表示裁切标记注释。裁切标记放置在打印页面的角落，以指示页面的裁切位置。 |
| [TxtLoadOptions](./txtloadoptions/) | TXT 转 PDF 转换的加载选项。 |
| [UnderlineAnnotation](./underlineannotation/) | 表示在文档文本中显示为下划线的下划线注释。 |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | 此类表示使用统一转换方式（具有统一内部文档模型）的保存选项。 |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | 表示具有抽象方法的类，该方法通常由调用方提供，并处理来自转换器的进度事件。通常，这种由客户提供的处理程序可用于在控制台或进度条上显示整体转换进度。 |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | 此类表示可在外部应用程序中使用的转换进度信息，以向最终用户显示转换进度。 |
| [WarningCallback](./warningcallback/) | 用于用户回调机制支持的接口。 |
| [WarningInfo](./warninginfo/) | 用于封装警告信息的不可变对象。 |
| [WarningType](./warningtype/) | / * 枚举表示警告类型。 / * / |
| [Watermark](./watermark/) | 表示页面的水印。 |
| [WatermarkAnnotation](./watermarkannotation/) | 类描述 Watermark 注释对象。 |
| [WatermarkArtifact](./watermarkartifact/) | 类描述水印工件。此可用于 |
| [WebHyperlink](./webhyperlink/) | 表示网页超链接对象。 |
| [WidgetAnnotation](./widgetannotation/) | 表示小部件注释的类。 |
| [XFA](./xfa/) | 表示与 XML Forms Architecture (XFA) 相关的 XML 表单。 |
| [XfaParserOptions](./xfaparseroptions/) | 处理相关数据封装的类 |
| [XfdfReader](./xfdfreader/) | <p> 执行读取 XFDF 格式的类。 </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | 聚合将注释和字段写入 XFDF 文件格式的方法 |
| [XForm](./xform/) | 表示 XForm 的类 |
| [XFormCollection](./xformcollection/) | 表示 XFormCollection 集合的类。 |
| [XImage](./ximage/) | 表示图像 X-Object 的类。 |
| [XImage.RawParameters](./ximage.rawparameters/) | 表示图像原始 XImage 参数的类。 |
| [XImageCollection](./ximagecollection/) | 表示 XImage 集合的类。 |
| [XmlLoadOptions](./xmlloadoptions/) | 表示加载/导入 XML 文件到 PDF 文档的选项。 |
| [XmlSaveOptions](./xmlsaveoptions/) | 导出为 Xml 格式的保存选项。 |
| [XmpField](./xmpfield/) | 表示 XMP 字段。 |
| [XmpFieldType](./xmpfieldtype/) | 此枚举表示 XMP 字段的类型。 |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | 属性类别：内部或外部。 |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | 此模式描述结构化类型中的字段。它与 PDF/A Property Value Type 模式非常相似，但在结构中定义字段而不是属性。模式命名空间 URI: http://www.aiim.org/pdfa/ns/field# 必需的模式命名空间前缀: pdfaField。 |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | 表示字段、属性、值类型实例的基类。 |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | 描述单个属性。模式命名空间 URI: http://www.aiim.org/pdfa/ns/property# 必需的模式命名空间前缀: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | 描述 PDF/A-1 提供的 XMP 扩展模式。 |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | 表示 PDF/A-1 提供的 XMP 扩展模式的描述。 |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | PDF/A ValueType 模式是所有未在 XMP 2004 规范中定义的属性值类型所必需的，即以下列表之外的值类型：- 数组类型（这些是可以包含一个或多个字段的容器类型）：Alt、Bag、Seq - 基本值类型：Boolean、（开放和闭合）Choice、Date、Dimensions、Integer、Lang Alt、Locale、MIMEType、ProperName、Real、Text、Thumbnail、URI、URL、XPath - 媒体管理值类型：AgentName、RenditionClass、ResourceEvent、ResourceRef、Version - 基本作业/工作流值类型：Job - EXIF 模式值类型：Flash、CFAPattern、DeviceSettings、GPSCoordinate、OECF/SFR、Rational 模式命名空间 URI: http://www.aiim.org/pdfa/ns/type# 必需的模式命名空间前缀: pdfaType |
| [XmpValue](./xmpvalue/) | 表示 XMP 值 |
| [XpsLoadOptions](./xpsloadoptions/) | 表示将 xps 文件加载/导入到 pdf 文档的选项。 |
| [XpsSaveOptions](./xpssaveoptions/) | 导出为 Xps 格式的保存选项 |
| [XslFoLoadOptions](./xslfoloadoptions/) | 表示将 XSL-FO 文件加载/导入到 pdf 文档的选项。 |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | 源 XSLFO 文档可能包含格式错误。此枚举列举了处理此类格式错误的可能策略。 |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> 表示显式目标，该目标在窗口左上角显示页面，坐标 (left, top) 位于窗口左上角，页面内容按 zoom 因子放大。对于参数 left、top 或 zoom 的任意一个为 null 值，表示该参数的当前值保持不变。zoom 为 0 的含义与 null 值相同。 </p> <hr> <p> Document doc = new Document(\"example.pdf\"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| 枚举 | 描述 |
| --- | --- |
| [AFRelationship](./afrelationship/) | 枚举描述关联文件的关系。 |
| [AnnotationState](./annotationstate/) | 原始注释可以设置的状态枚举。 |
| [AnnotationStateModel](./annotationstatemodel/) | 对应注释状态的状态模型。 |
| [AnnotationType](./annotationtype/) | 注释类型的枚举。 |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | 可能的工件子类型枚举。 |
| [Artifact.ArtifactType](./artifact.artifacttype/) | 可能的工件类型枚举。 |
| [BlendMode](./blendmode/) | 混合模式枚举。 |
| [BorderCornerStyle](./bordercornerstyle/) | 枚举边框的角落样式。 |
| [BorderEffect](./bordereffect/) | 描述应应用于注释边框的效果。 |
| [BorderStyle](./borderstyle/) | 描述注释边框的样式。 |
| [BoxStyle](./boxstyle/) | 表示复选框中勾选的绘制样式。 |
| [CapStyle](./capstyle/) | 墨迹注释线的线端样式。 |
| [CaptionPosition](./captionposition/) | 注释标题定位的枚举。 |
| [CaretSymbol](./caretsymbol/) | 与插入符号关联的符号。 |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK 颜色模型中包含的颜色。 |
| [ColorSpace](./colorspace/) | 颜色空间枚举。 |
| [ColorType](./colortype/) | 指定页面上元素的颜色类型。 |
| [ColumnAdjustment](./columnadjustment/) | 枚举列调整类型。 |
| [ContentDisposition](./contentdisposition/) | MIME 协议 Content-Disposition 标头。 |
| [ConvertErrorAction](./converterroraction/) | 此类表示转换错误的操作。 |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | 此操作表示带软遮罩的图像转换操作。 |
| [ConvertTransparencyAction](./converttransparencyaction/) | 此类表示透明度转换的操作。 |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | 表示在加密/解密例程中使用的加密算法类型。 |
| [CryptographicStandard](./cryptographicstandard/) | / * / * 该 {@code Aspose.Pdf.Security } 命名空间包含用于加密和数字签名的类。 / * / |
| [DefaultState](./defaultstate/) | 表示 PDF 图层的默认状态。 |
| [DigestHashAlgorithm](./digesthashalgorithm/) | 表示将数据映射到\"哈希\"的算法类型。 |
| [Direction](./direction/) | 文本方向。 |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | 此文档授予的访问权限。有效值为：1 - 不允许对文档进行任何更改；对文档的任何更改都会使签名失效。2 - 允许的更改包括填写表单、实例化页面模板和签名；其他更改会使签名失效。3 - 允许的更改与 2 相同，并且包括注释的创建、删除和修改；其他更改会使签名失效。 |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | 允许指定 .doc 或 .docx 文件格式。 |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | 允许控制 PDF 文档转换为文字处理文档的方式。当生成的文档不需要大量后续编辑时，使用 RecognitionMode.Textbox 模式。文本框在内容较少时易于修改。当输出文档需要进一步编辑时，使用 RecognitionMode.Flow 模式。流模式下的段落和文本行便于文本的修改，但不受支持的格式对象的显示效果会比 RecognitionMode.Textbox 模式更差。 |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | 当 PDF 文件（通常具有固定布局）被转换时，转换引擎会尝试进行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性用于调节该转换，以实现期望的内容识别方式。 |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | 枚举显式目标的类型。 |
| [ExtendedBoolean](./extendedboolean/) | 表示支持 Undefined 值的布尔类型。 |
| [ExtractImageMode](./extractimagemode/) | 定义在从文档中提取图像时可使用的不同模式。 |
| [FileEncoding](./fileencoding/) | 附件文件的编码。可能的取值：Zip - 文件使用 ZIP 压缩，None - 文件未压缩。 |
| [FileIcon](./fileicon/) | 用于显示注释的图标。 |
| [Fixup](./fixup/) | 此枚举表示一种 Fixup 类型。 |
| [FormType](./formtype/) | Acro Form 可能类型的枚举。 |
| [FreeTextIntent](./freetextintent/) | 枚举自由文本注释的意图。 |
| [HighlightingMode](./highlightingmode/) | 枚举注释的高亮模式，即在鼠标按钮在其活动区域内按下或保持时使用的视觉效果。 |
| [HorizontalAlignment](./horizontalalignment/) | 描述水平对齐方式。 |
| [HtmlDocumentType](./htmldocumenttype/) | 表示 Html 文档类型的枚举。 |
| [HtmlMediaType](./htmlmediatype/) | 指定渲染期间使用的可能媒体类型。 |
| [IconCaptionPosition](./iconcaptionposition/) | 描述图标的位置。 |
| [ImageFileType](./imagefiletype/) | 枚举图像文件类型。 |
| [ImageFilterType](./imagefiltertype/) | 表示图像过滤器类型的枚举。 |
| [ImageFormat](./imageformat/) | 此枚举表示图像格式。 |
| [ImportFormat](./importformat/) | 指定导入格式。 |
| [Justification](./justification/) | 枚举在显示注释文本时使用的对齐（两端对齐）形式。 |
| [LaunchActionOperation](./launchactionoperation/) | 枚举在执行启动操作时对文档执行的操作。 |
| [LettersPositioningMethods](./letterspositioningmethods/) | 它枚举结果 HTML 中单词中字母定位的可能模式。 |
| [LightingSchemeType](./lightingschemetype/) | 枚举 LightingSchemeType：一组照明方案类型。 |
| [LineEnding](./lineending/) | 枚举绘制线条时使用的线端样式。 |
| [LineIntent](./lineintent/) | 枚举线注释的意图。 |
| [LoadFormat](./loadformat/) | 指定加载格式。 |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | 指示分数值显示方式的值。 |
| [NumberingStyle](./numberingstyle/) | PageLabel 类支持的页码样式枚举。 |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | 指定在流中用于定位的位置信息。 |
| [PageCoordinateType](./pagecoordinatetype/) | 描述页面坐标类型。MediaBox = 0，CropBox = 1。 |
| [PageLayout](./pagelayout/) | 描述页面布局。 |
| [PageMode](./pagemode/) | 类描述文档页面使用的组件。 |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | 指定用于确定元素在页面上位置的变体。 |
| [PasswordType](./passwordtype/) | 此枚举表示用于受密码保护的 PDF 文档的已知密码类型。 |
| [PDF3DActivation](./pdf3dactivation/) | 枚举 PDF3DActivation：一组 3D 注释激活模式。 |
| [PdfFormat](./pdfformat/) | 此类表示 PDF 格式。 |
| [PdfVersion](./pdfversion/) | 此枚举表示 PDF 文件的版本。 |
| [PolyIntent](./polyintent/) | 枚举多边形或折线注释的意图。 |
| [PredefinedAction](./predefinedaction/) | 定义可以从 PDF 文件触发的不同操作。 |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | 表示页面角落中标记的位置。 |
| [PrinterMarkSidePosition](./printermarksideposition/) | 表示页面上注册标记的位置。 |
| [ReplyType](./replytype/) | 枚举注释与 InReplyTo 指定的对象之间的关系类型（即"回复类型"）。 |
| [ReturnAction](./returnaction/) | 枚举表示在调用 {@code IWarningCallback.Warning(WarningInfo)} 方法时的程序工作流操作。 |
| [Rotation](./rotation/) | 可能的旋转值枚举。 |
| [SaveFormat](./saveformat/) | 指定格式 |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | 表示可用于结果文档中绘制边框或其他线条的线型。 |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | 枚举已保存外部资源的可能类型 |
| [StampIcon](./stampicon/) | 枚举用于显示注释的图标。 |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | 枚举在 PDF 转 SVG 转换期间可以保存为外部资源的图像文件的可能类型。 |
| [TextAlignment](./textalignment/) | 注释中文本的对齐方式。 |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | 剪裁路径处理模式 |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | 字体替换行为。 |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | 语言转换模式 |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | 当字体不包含所需字符时要执行的操作 |
| [TextRenderingMode](./textrenderingmode/) | 文本渲染模式 Tmode 决定显示文本时是否会对字形轮廓进行描边、填充、用作剪裁边界，或三者的某种组合。 |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | 指定文本字体大小应如何调整以适应包含区域的策略。 |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | 替换文本操作的作用范围，默认使用 REPLACE_FIRST。此已废弃选项为兼容性保留。它影响 PdfContentEditor，但对 TextFragmentAbsorber 没有影响。 |
| [VerticalAlignment](./verticalalignment/) | 可能的垂直对齐值枚举。 |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
