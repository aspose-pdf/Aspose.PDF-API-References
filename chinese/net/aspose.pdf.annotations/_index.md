---
title: "Aspose.Pdf.Annotations"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations 命名空间提供用于处理各种操作目标类型以及文档其他传统称为交互式的功能的类，提供用户可以与之交互的手段。"
type: docs
weight: 50
url: /zh/net/aspose.pdf.annotations/
---
**Aspose.Pdf.Annotations** 命名空间提供用于处理文档中各种操作、目标及其他传统称为交互式功能的类，使用户能够与文档进行交互。

## 类

| 类 | 描述 |
| --- | --- |
| [ActionCollection](./actioncollection/) | 操作集合 |
| [Annotation](./annotation/) | 表示注释对象的类。 |
| [AnnotationActionCollection](./annotationactioncollection/) | 表示注释操作的集合。 |
| [AnnotationCollection](./annotationcollection/) | 表示注释集合的类。 |
| [AnnotationSelector](./annotationselector/) | 此类用于使用 Visitor 模板思想选择注释。 |
| [AppearanceDictionary](./appearancedictionary/) | 注释外观字典，指定注释在页面上如何以视觉方式呈现。 |
| [BleedMarkAnnotation](./bleedmarkannotation/) | 表示出血标记注释。 |
| [Border](./border/) | 表示注释边框特性的类。 |
| [CaretAnnotation](./caretannotation/) | 表示插入符号注释的类。 |
| [Characteristics](./characteristics/) | 表示注释特性 |
| [CircleAnnotation](./circleannotation/) | 表示圆形注释的类。 |
| [ColorBarAnnotation](./colorbarannotation/) | 表示 ColorBarAnnotation 注释的类。属性 Color 被忽略，改用 ColorsOfCMYK 颜色。创建时，宽高比决定注释的方向——水平或垂直。随后检查注释矩形是否位于 TrimBox 之外，如果不在，则根据注释的方向将其移动到最近的 TrimBox 外部位置。可以缩小宽度（高度），使注释位于 TrimBox 之外。如果布局没有空间，宽度/高度可以设为零（此时注释仍在页面上，但不显示）。 |
| [CommonFigureAnnotation](./commonfigureannotation/) | 表示通用图形注释的抽象类。 |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | 表示放置在打印页面角落的注释类型。 |
| [CustomExplicitDestination](./customexplicitdestination/) | 表示自定义显式目标。 |
| [Dash](./dash/) | 表示线段虚线模式的类。 |
| [DefaultAppearance](./defaultappearance/) | 描述字段的默认外观（字体、文字大小和颜色）。 |
| [DocumentActionCollection](./documentactioncollection/) | 描述对文档执行的某些操作的类。 |
| [ExplicitDestination](./explicitdestination/) | 表示 PDF 文档中显式目标的基类。 |
| [FdfReader](./fdfreader/) | 执行读取 FDF 格式的类。 |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | 描述文件附件注释的类。 |
| [FitBExplicitDestination](./fitbexplicitdestination/) | 表示显式目标，该目标显示页面，并将其内容放大到恰好使其边界框在水平和垂直方向上完全适合窗口。如果所需的水平和垂直放大系数不同，则使用两者中较小的一个，并在另一维度上将边界框居中于窗口。 |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | 表示显式目标，该目标显示页面，并将垂直坐标 top 定位在窗口的上边缘，同时将页面内容放大到恰好使其边界框的整个宽度适合窗口。top 为 null 值表示保留该参数的当前值不变。 |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | 表示显式目标，该目标显示页面，并将水平坐标 left 定位在窗口的左边缘，同时将页面内容放大到恰好使其边界框的整个高度适合窗口。left 为 null 值表示保留该参数的当前值不变。 |
| [FitExplicitDestination](./fitexplicitdestination/) | 表示显式目标，该目标显示页面，并将其内容放大到恰好使整个页面在水平和垂直方向上都适合窗口。如果所需的水平和垂直放大系数不同，则使用两者中较小的一个，并在另一维度上将页面居中于窗口。 |
| [FitHExplicitDestination](./fithexplicitdestination/) | 表示显式目标，该目标显示页面，并将垂直坐标 top 定位在窗口的上边缘，同时将页面内容放大到恰好使页面的整个宽度适合窗口。top 为 null 值表示保留该参数的当前值不变。 |
| [FitRExplicitDestination](./fitrexplicitdestination/) | 表示显式目标，该目标显示页面，并将其内容放大到恰好使由 left、bottom、right 和 top 坐标指定的矩形在水平和垂直方向上完全适合窗口。如果所需的水平和垂直放大系数不同，则使用两者中较小的一个，并在另一维度上将矩形居中于窗口。任何参数为 null 值可能导致不可预测的行为。 |
| [FitVExplicitDestination](./fitvexplicitdestination/) | 表示显式目标，该目标显示页面，并将水平坐标 left 定位在窗口的左边缘，同时将页面内容放大到恰好使页面的整个高度适合窗口。left 为 null 值表示保留该参数的当前值不变。 |
| [FixedPrint](./fixedprint/) | 表示水印注释的固定打印数据。 |
| [FreeTextAnnotation](./freetextannotation/) | 表示自由文本注释，可直接在页面上显示文本。与普通文本注释不同，自由文本注释没有打开或关闭状态；文本不会以弹出窗口显示，而是始终可见。 |
| [GoToAction](./gotoaction/) | 表示跳转操作，可将视图更改为指定的目标（页面、位置和放大系数）。 |
| [GoToRemoteAction](./gotoremoteaction/) | 表示远程跳转操作，其类似于普通跳转操作，但跳转到另一个 PDF 文件中的目标，而不是当前文件。 |
| [GoToURIAction](./gotouriaction/) | 表示 URI 操作，会解析 URI。 |
| [HideAction](./hideaction/) | 表示隐藏操作，可通过设置或清除隐藏标志来隐藏或显示屏幕上的一个或多个注释。 |
| [HighlightAnnotation](./highlightannotation/) | 表示高亮注释，用于突出显示文档中的一段文本。 |
| [ImportDataAction](./importdataaction/) | 在调用 import-data 操作时，表单数据格式（FDF）数据应从指定文件导入到文档的交互式表单中。 |
| [InkAnnotation](./inkannotation/) | 表示由一个或多个不相连路径组成的手绘“涂鸦”。 |
| [JavascriptAction](./javascriptaction/) | 表示 JavaScript 操作的类。 |
| [LaunchAction](./launchaction/) | 表示启动操作，可启动应用程序或打开或打印文档。 |
| [LineAnnotation](./lineannotation/) | 表示线注释的类。 |
| [LinkAnnotation](./linkannotation/) | 表示文档中指向其他位置的超文本链接或要执行的操作。 |
| [MarkupAnnotation](./markupannotation/) | 表示标记注释的抽象类。 |
| [Measure](./measure/) | 描述测量坐标系的类。 |
| [MediaClip](./mediaclip/) | 描述呈现的媒体剪辑对象的类。 |
| [MediaClipData](./mediaclipdata/) | 描述媒体剪辑数据的类。 |
| [MediaClipSection](./mediaclipsection/) | 此类描述媒体剪辑部分。 |
| [MediaRendition](./mediarendition/) | 描述媒体呈现的类。 |
| [MovieAnnotation](./movieannotation/) | 表示包含动画图形和声音的电影注释，这些内容将在电脑屏幕和扬声器上呈现。激活注释时，将播放电影。 |
| [NamedAction](./namedaction/) | 表示 PDF 查看器应用程序应支持的已命名操作。 |
| [NamedDestination](./nameddestination/) | 目标可以不使用显式语法直接定义，而是通过名称对象或字节串间接引用。 |
| [PageInformationAnnotation](./pageinformationannotation/) | 表示 PDF 文档中的页面信息注释。此注释包含文件名、页码以及注释创建的日期和时间。 |
| [PDF3DAnnotation](./pdf3dannotation/) | 类 PDF3DAnnotation。此类不可被继承。 |
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
| [PdfActionCollection](./pdfactioncollection/) | 描述操作列表的类。 |
| [PolyAnnotation](./polyannotation/) | 多注释的抽象基类。 |
| [PolygonAnnotation](./polygonannotation/) | 表示多边形注释的类。 |
| [PolylineAnnotation](./polylineannotation/) | 表示多线注释，它类似于多边形，但首尾顶点未隐式连接。 |
| [PopupAnnotation](./popupannotation/) | 表示弹出注释，可在弹出窗口中显示文本以进行输入和编辑。 |
| [PrinterMarkAnnotation](./printermarkannotation/) | 表示打印标记注释的抽象类。 |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | 提供针对[`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/)枚举的扩展方法。 |
| [RedactionAnnotation](./redactionannotation/) | 表示编辑注释。 |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | 表示登记标记注释。 |
| [Rendition](./rendition/) | 描述 RendtionAnnotation 的呈现对象的类。 |
| [RenditionAction](./renditionaction/) | 控制多媒体内容播放的呈现操作。 |
| [RichMediaAnnotation](./richmediaannotation/) | 描述 RichMediaAnnotation 的类，允许将视频/音频数据嵌入 PDF 文档。 |
| [ScreenAnnotation](./screenannotation/) | 指定页面上可播放媒体剪辑区域的屏幕注释。 |
| [SelectorRendition](./selectorrendition/) | 描述选择器呈现的类。 |
| [SoundAnnotation](./soundannotation/) | 表示包含从计算机麦克风录制或从文件导入的声音的声音注释。 |
| [SoundData](./sounddata/) | 表示定义在激活注释时播放的声音的数据。 |
| [SoundSampleData](./soundsampledata/) | 表示特定于声音对象的附加条目（第 9.2 节 PDF1-7） |
| [SquareAnnotation](./squareannotation/) | 表示方形注释的类。 |
| [SquigglyAnnotation](./squigglyannotation/) | 表示在文档文本中出现锯齿形下划线的波浪注释。 |
| [StampAnnotation](./stampannotation/) | 表示橡胶印章注释。此类注释显示的文本或图形看起来像是用橡胶印章盖在页面上。 |
| [StrikeOutAnnotation](./strikeoutannotation/) | 表示在文档文本中出现删除线的删除注释。 |
| [SubmitFormAction](./submitformaction/) | 描述提交表单操作的类。 |
| [TextAnnotation](./textannotation/) | 表示附着在 PDF 文档中某点的“便签”文本注释。 |
| [TextMarkupAnnotation](./textmarkupannotation/) | 文本标记注释的抽象基类。 |
| [TextStyle](./textstyle/) | 表示注释中文本样式的类。 |
| [TrimMarkAnnotation](./trimmarkannotation/) | 表示裁剪标记注释。 |
| [UnderlineAnnotation](./underlineannotation/) | 表示在文档文本中出现下划线的下划线注释。 |
| [WatermarkAnnotation](./watermarkannotation/) | 类描述水印注释对象。 |
| [WidgetAnnotation](./widgetannotation/) | 类表示小部件注释。 |
| [XfdfReader](./xfdfreader/) | 执行读取 XFDF 格式的类。 |
| [XYZExplicitDestination](./xyzexplicitdestination/) | 表示显式目标，该目标在窗口左上角显示页面，坐标 (left, top) 位于窗口左上角，并按 zoom 因子放大页面内容。对于参数 left、top 或 zoom 的任意 null 值，表示该参数的当前值保持不变。zoom 为 0 的值具有与 null 值相同的含义。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | 定义用于访问不同文档注释的 Visitor。 |
| [IAppointment](./iappointment/) | 表示用于操作和目标的通用接口。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | 一组标志，用于指定注释的各种特性。 |
| [AnnotationState](./annotationstate/) | 原始注释可以设置的状态枚举。 |
| [AnnotationStateModel](./annotationstatemodel/) | 对应于注释状态的状态模型。 |
| [AnnotationType](./annotationtype/) | 注释类型的枚举。 |
| [BorderEffect](./bordereffect/) | 描述应应用于注释边框的效果。 |
| [BorderStyle](./borderstyle/) | 描述注释边框的样式。 |
| [CapStyle](./capstyle/) | 墨迹注释线的线端样式。 |
| [CaptionPosition](./captionposition/) | 注释标题定位的枚举。 |
| [CaretSymbol](./caretsymbol/) | 与插入符号关联的符号。 |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK 颜色模型中包含的颜色。 |
| [ExplicitDestinationType](./explicitdestinationtype/) | 枚举显式目标的类型。 |
| [FileIcon](./fileicon/) | 用于显示注释的图标。 |
| [FreeTextIntent](./freetextintent/) | 枚举自由文本注释的意图。 |
| [HighlightingMode](./highlightingmode/) | 枚举注释的高亮模式，即在其活动区域内按下或保持鼠标按钮时使用的视觉效果。 |
| [Justification](./justification/) | 枚举在显示注释文本时使用的对齐（齐行）形式。 |
| [LaunchActionOperation](./launchactionoperation/) | 枚举在执行启动操作时对文档执行的操作。 |
| [LightingSchemeType](./lightingschemetype/) | 枚举 LightingSchemeType：一组照明方案类型。 |
| [LineEnding](./lineending/) | 枚举绘制线条时使用的线端样式。 |
| [LineIntent](./lineintent/) | 枚举线注释的意图。 |
| [PDF3DActivation](./pdf3dactivation/) | 枚举 PDF3DActivation：3D 注释激活模式的集合。 |
| [PolyIntent](./polyintent/) | 枚举多边形或折线注释的意图。 |
| [PredefinedAction](./predefinedaction/) | 定义可以从 PDF 文件触发的不同操作。 |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | 表示页面角落中标记的位置。 |
| [PrinterMarkSidePosition](./printermarksideposition/) | 表示页面上注册标记的位置。 |
| [PrinterMarksKind](./printermarkskind/) | 指定要添加到文档中的打印机标记类型。 |
| [RenderModeType](./rendermodetype/) | 枚举 RenderModeType：渲染模式类型的集合 |
| [RenditionOperation](./renditionoperation/) | 当操作被触发时要执行的操作。 |
| [RenditionType](./renditiontype/) | 枚举描述了可能的呈现类型。 |
| [ReplyType](./replytype/) | 枚举注释与 InReplyTo 指定的对象之间关系（“回复类型”）的种类。 |
| [RichTextFontStyles](./richtextfontstyles/) | RichText 中文本片段样式的选项。 |
| [SoundEncoding](./soundencoding/) | 示例数据的编码格式。 |
| [SoundIcon](./soundicon/) | 枚举用于显示注释的图标。 |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | 声音示例数据的编码格式。 |
| [StampIcon](./stampicon/) | 枚举用于显示注释的图标。 |
| [TextIcon](./texticon/) | 枚举用于显示注释的图标。 |


