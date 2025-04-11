---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations 命名空间提供用于处理各种类型的动作目标和文档其他特性的类，这些特性传统上被称为交互式，提供用户可以与之相互通信的手段。
type: docs
weight: 50
url: /zh/net/aspose.pdf.annotations/
---
**Aspose.Pdf.Annotations** 命名空间提供用于处理各种类型的动作、目标和文档其他特性的类，这些特性传统上被称为交互式，提供用户可以与之相互通信的手段。

## 类

| 类 | 描述 |
| --- | --- |
| [ActionCollection](./actioncollection/) | 动作集合 |
| [Annotation](./annotation/) | 表示注释对象的类。 |
| [AnnotationActionCollection](./annotationactioncollection/) | 表示注释动作的集合。 |
| [AnnotationCollection](./annotationcollection/) | 表示注释集合的类。 |
| [AnnotationSelector](./annotationselector/) | 此类用于使用访问者模板思想选择注释。 |
| [AppearanceDictionary](./appearancedictionary/) | 注释外观字典，指定注释在页面上如何视觉呈现。 |
| [BleedMarkAnnotation](./bleedmarkannotation/) | 表示一个出血标记注释。 |
| [Border](./border/) | 表示注释边框特性的类。 |
| [CaretAnnotation](./caretannotation/) | 表示插入符注释的类。 |
| [Characteristics](./characteristics/) | 表示注释特性 |
| [CircleAnnotation](./circleannotation/) | 表示圆形注释的类。 |
| [ColorBarAnnotation](./colorbarannotation/) | 表示 ColorBarAnnotation 注释的类。属性 Color 被忽略，而是使用 ColorsOfCMYK 颜色。在创建时，宽度和高度的比例决定注释的方向 - 水平或垂直。接下来，它检查注释矩形是否在 TrimBox 之外，如果没有，则将其移动到 TrimBox 之外的最近位置，考虑注释的方向。可以减少宽度（高度），以便注释适合 TrimBox 之外。如果没有布局空间，宽度/高度可以设置为零（在这种情况下，注释存在于页面上，但不显示）。 |
| [CommonFigureAnnotation](./commonfigureannotation/) | 表示通用图形注释的抽象类。 |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | 表示放置在打印页面角落的注释类型。 |
| [CustomExplicitDestination](./customexplicitdestination/) | 表示自定义显式目标。 |
| [Dash](./dash/) | 表示线条虚线模式的类。 |
| [DefaultAppearance](./defaultappearance/) | 描述字段的默认外观（字体、文本大小和颜色）。 |
| [DocumentActionCollection](./documentactioncollection/) | 类描述对文档某些动作执行的动作 |
| [ExplicitDestination](./explicitdestination/) | 表示 PDF 文档中显式目标的基类。 |
| [FdfReader](./fdfreader/) | 执行 FDF 格式读取的类。 |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | 类描述文件附件注释。 |
| [FitBExplicitDestination](./fitbexplicitdestination/) | 表示显式目标，该目标显示页面，其内容放大到刚好足以使其边界框完全适合窗口的水平和垂直。如果所需的水平和垂直放大因子不同，则使用两个中的较小者，在另一个维度中将边界框居中。 |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | 表示显式目标，该目标显示页面，垂直坐标顶部位于窗口的顶部边缘，页面内容放大到刚好足以使其边界框的整个宽度适合窗口。顶部的空值指定该参数的当前值应保持不变。 |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | 表示显式目标，该目标显示页面，水平坐标左侧位于窗口的左边缘，页面内容放大到刚好足以使其边界框的整个高度适合窗口。左侧的空值指定该参数的当前值应保持不变。 |
| [FitExplicitDestination](./fitexplicitdestination/) | 表示显式目标，该目标显示页面，其内容放大到刚好足以使整个页面在窗口中水平和垂直适合。如果所需的水平和垂直放大因子不同，则使用两个中的较小者，在另一个维度中将页面居中。 |
| [FitHExplicitDestination](./fithexplicitdestination/) | 表示显式目标，该目标显示页面，垂直坐标顶部位于窗口的顶部边缘，页面内容放大到刚好足以使页面的整个宽度适合窗口。顶部的空值指定该参数的当前值应保持不变。 |
| [FitRExplicitDestination](./fitrexplicitdestination/) | 表示显式目标，该目标显示页面，其内容放大到刚好足以使由坐标左、下、右和顶部指定的矩形完全适合窗口的水平和垂直。如果所需的水平和垂直放大因子不同，则使用两个中的较小者，在另一个维度中将矩形居中。任何参数的空值可能导致不可预测的行为。 |
| [FitVExplicitDestination](./fitvexplicitdestination/) | 表示显式目标，该目标显示页面，水平坐标左侧位于窗口的左边缘，页面内容放大到刚好足以使页面的整个高度适合窗口。左侧的空值指定该参数的当前值应保持不变。 |
| [FixedPrint](./fixedprint/) | 表示水印注释的固定打印数据。 |
| [FreeTextAnnotation](./freetextannotation/) | 表示直接在页面上显示文本的自由文本注释。与普通文本注释不同，自由文本注释没有打开或关闭状态；文本始终可见，而不是在弹出窗口中显示。 |
| [GoToAction](./gotoaction/) | 表示一个跳转动作，该动作将视图更改为指定的目标（页面、位置和放大因子）。 |
| [GoToRemoteAction](./gotoremoteaction/) | 表示一个远程跳转动作，该动作类似于普通跳转动作，但跳转到另一个 PDF 文件中的目标，而不是当前文件。 |
| [GoToURIAction](./gotouriaction/) | 表示一个 URI 动作，导致 URI 被解析。 |
| [HideAction](./hideaction/) | 表示一个隐藏动作，通过设置或清除其隐藏标志来隐藏或显示一个或多个注释。 |
| [HighlightAnnotation](./highlightannotation/) | 表示一个高亮注释，该注释在文档中高亮显示一段文本。 |
| [ImportDataAction](./importdataaction/) | 在调用导入数据动作时，表单数据格式（FDF）数据应从指定文件导入到文档的交互式表单中。 |
| [InkAnnotation](./inkannotation/) | 表示由一个或多个不相连的路径组成的自由手“涂鸦”。 |
| [JavascriptAction](./javascriptaction/) | 表示 JavaScript 动作的类。 |
| [LaunchAction](./launchaction/) | 表示一个启动动作，该动作启动一个应用程序或打开或打印一个文档。 |
| [LineAnnotation](./lineannotation/) | 表示线注释的类。 |
| [LinkAnnotation](./linkannotation/) | 表示指向文档中其他位置的超文本链接或要执行的动作。 |
| [MarkupAnnotation](./markupannotation/) | 表示标记注释的抽象类。 |
| [Measure](./measure/) | 描述测量坐标系统的类。 |
| [MediaClip](./mediaclip/) | 描述媒体剪辑对象的类。 |
| [MediaClipData](./mediaclipdata/) | 描述媒体剪辑数据的类。 |
| [MediaClipSection](./mediaclipsection/) | 此类描述媒体剪辑部分。 |
| [MediaRendition](./mediarendition/) | 描述媒体呈现的类。 |
| [MovieAnnotation](./movieannotation/) | 表示一个电影注释，该注释包含动画图形和声音，在计算机屏幕和扬声器上呈现。当注释被激活时，电影播放。 |
| [NamedAction](./namedaction/) | 表示 PDF 查看器应用程序预期支持的命名动作。 |
| [NamedDestination](./nameddestination/) | 目标可以通过名称对象或字节字符串间接引用，而不是直接用显式语法定义。 |
| [PageInformationAnnotation](./pageinformationannotation/) | 表示 PDF 文档中的页面信息注释。此注释包含文件名、页码以及注释创建的日期和时间。 |
| [PDF3DAnnotation](./pdf3dannotation/) | 类 PDF3DAnnotation。此类不能被继承。 |
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
| [PdfAction](./pdfaction/) | 表示 PDF 文档中的动作 |
| [PdfActionCollection](./pdfactioncollection/) | 类描述动作列表。 |
| [PolyAnnotation](./polyannotation/) | 多边形注释的抽象基类。 |
| [PolygonAnnotation](./polygonannotation/) | 表示多边形注释的类。 |
| [PolylineAnnotation](./polylineannotation/) | 表示多线注释，类似于多边形，除了第一个和最后一个顶点没有隐式连接。 |
| [PopupAnnotation](./popupannotation/) | 表示在弹出窗口中显示文本以供输入和编辑的弹出注释。 |
| [PrinterMarkAnnotation](./printermarkannotation/) | 表示打印机标记注释的抽象类。 |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | 为 [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/) 枚举提供扩展方法。 |
| [RedactionAnnotation](./redactionannotation/) | 表示编辑注释。 |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | 表示注册标记注释。 |
| [Rendition](./rendition/) | 描述 RenditionAnnotation 的呈现对象的类。 |
| [RenditionAction](./renditionaction/) | 控制多媒体内容播放的呈现动作。 |
| [RichMediaAnnotation](./richmediaannotation/) | 类描述 RichMediaAnnotation，允许将视频/音频数据嵌入到 PDF 文档中。 |
| [ScreenAnnotation](./screenannotation/) | 指定页面区域的屏幕注释，在该区域可以播放媒体剪辑。 |
| [SelectorRendition](./selectorrendition/) | 描述选择器呈现的类。 |
| [SoundAnnotation](./soundannotation/) | 表示包含从计算机麦克风录制或从文件导入的声音的声音注释。 |
| [SoundData](./sounddata/) | 表示声音数据，定义在激活注释时播放的声音。 |
| [SoundSampleData](./soundsampledata/) | 表示特定于声音对象的附加条目（第 9.2 节 PDF1-7） |
| [SquareAnnotation](./squareannotation/) | 表示方形注释的类。 |
| [SquigglyAnnotation](./squigglyannotation/) | 表示在文档文本中出现的波浪注释，呈现为锯齿状下划线。 |
| [StampAnnotation](./stampannotation/) | 表示橡皮章注释。这种类型的注释显示文本或图形，意图看起来像是用橡皮章盖在页面上的。 |
| [StrikeOutAnnotation](./strikeoutannotation/) | 表示在文档文本中出现的删除线注释。 |
| [SubmitFormAction](./submitformaction/) | 描述提交表单动作的类。 |
| [TextAnnotation](./textannotation/) | 表示附加到 PDF 文档某一点的“便签”的文本注释。 |
| [TextMarkupAnnotation](./textmarkupannotation/) | 文本标记注释的抽象基类。 |
| [TextStyle](./textstyle/) | 类表示注释中文本的样式 |
| [TrimMarkAnnotation](./trimmarkannotation/) | 表示修整标记注释。 |
| [UnderlineAnnotation](./underlineannotation/) | 表示在文档文本中出现的下划线注释。 |
| [WatermarkAnnotation](./watermarkannotation/) | 类描述水印注释对象。 |
| [WidgetAnnotation](./widgetannotation/) | 表示小部件注释的类。 |
| [XfdfReader](./xfdfreader/) | 执行 XFDF 格式读取的类。 |
| [XYZExplicitDestination](./xyzexplicitdestination/) | 表示显式目标，该目标显示页面，其坐标（左，上）位于窗口的左上角，页面内容按放大因子放大。左、上或放大因子的任何参数的空值指定该参数的当前值应保持不变。放大值为 0 的含义与空值相同。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | 定义访问不同文档注释的访问者。 |
| [IAppointment](./iappointment/) | 表示动作和目标的一般接口。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | 一组标志，指定注释的各种特性。 |
| [AnnotationState](./annotationstate/) | 原始注释可以设置的状态枚举。 |
| [AnnotationStateModel](./annotationstatemodel/) | 与注释状态对应的状态模型。 |
| [AnnotationType](./annotationtype/) | 注释类型的枚举。 |
| [BorderEffect](./bordereffect/) | 描述应应用于注释边框的效果。 |
| [BorderStyle](./borderstyle/) | 描述注释边框的样式。 |
| [CapStyle](./capstyle/) | Ink 注释线的线条结束样式。 |
| [CaptionPosition](./captionposition/) | 注释标题定位的枚举。 |
| [CaretSymbol](./caretsymbol/) | 与插入符关联的符号。 |
| [ColorsOfCMYK](./colorsofcmyk/) | 包含在 CMYK 颜色模型中的颜色。 |
| [ExplicitDestinationType](./explicitdestinationtype/) | 枚举显式目标的类型。 |
| [FileIcon](./fileicon/) | 用于显示注释的图标。 |
| [FreeTextIntent](./freetextintent/) | 枚举自由文本注释的意图。 |
| [HighlightingMode](./highlightingmode/) | 枚举注释的高亮模式，在其活动区域内按下或按住鼠标按钮时使用的视觉效果。 |
| [Justification](./justification/) | 枚举用于显示注释文本的对齐形式。 |
| [LaunchActionOperation](./launchactionoperation/) | 枚举在执行启动动作时对文档执行的操作。 |
| [LightingSchemeType](./lightingschemetype/) | 枚举 LightingSchemeType：一组照明方案类型。 |
| [LineEnding](./lineending/) | 枚举用于绘制线条的线条结束样式。 |
| [LineIntent](./lineintent/) | 枚举线注释的意图。 |
| [PDF3DActivation](./pdf3dactivation/) | 枚举 PDF3DActivation：一组 3D 注释激活模式。 |
| [PolyIntent](./polyintent/) | 枚举多边形或多线注释的意图。 |
| [PredefinedAction](./predefinedaction/) | 定义可以从 PDF 文件触发的不同动作。 |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | 表示页面角落中标记的位置。 |
| [PrinterMarkSidePosition](./printermarksideposition/) | 表示页面上注册标记的位置。 |
| [PrinterMarksKind](./printermarkskind/) | 指定要添加到文档的打印机标记类型。 |
| [RenderModeType](./rendermodetype/) | 枚举 RenderModeType：一组渲染模式类型 |
| [RenditionOperation](./renditionoperation/) | 触发动作时要执行的操作。 |
| [RenditionType](./renditiontype/) | 枚举描述可能的呈现类型。 |
| [ReplyType](./replytype/) | 枚举注释与由 InReplyTo 指定的注释之间的关系（“回复类型”）的种类。 |
| [SoundEncoding](./soundencoding/) | 样本数据的编码格式。 |
| [SoundIcon](./soundicon/) | 枚举用于显示注释的图标。 |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | 声音样本数据的编码格式。 |
| [StampIcon](./stampicon/) | 枚举用于显示注释的图标。 |
| [TextIcon](./texticon/) | 枚举用于显示注释的图标。 |