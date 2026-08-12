---
title: "пространство имён Aspose::Pdf::Annotations"
linktitle: "Aspose::Pdf::Annotations"
second_title: "Справочник API Aspose.PDF для C++"
description: "Пространство имён Aspose::Pdf::Annotations. Пространство имён Aspose.Pdf.Annotations предоставляет классы для работы с различными типами действий, назначений и другими возможностями документа, традиционно называемыми интерактивными, предоставляя средства, позволяющие пользователю взаимодействовать с ним в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.annotations/
---

Пространство имён **[Aspose.Pdf.Annotations](./)** предоставляет классы для работы с различными типами действий, назначений и другими возможностями документа, традиционно называемыми интерактивными, предоставляя средства, позволяющие пользователю взаимодействовать с ним.

## Классы

| Класс | Описание |
| --- | --- |
| [ActionCollection](./actioncollection/) | [Коллекция](../aspose.pdf/collection/) действий. |
| [Annotation](./annotation/) | Класс, представляющий объект аннотации. |
| [AnnotationActionCollection](./annotationactioncollection/) | Представляет коллекцию действий аннотации. |
| [AnnotationCollection](./annotationcollection/) | Класс, представляющий коллекцию аннотаций. |
| [AnnotationFlagsConverter](./annotationflagsconverter/) |  |
| [AnnotationSelector](./annotationselector/) | Этот класс используется для выбора аннотаций с помощью идеи шаблона Visitor. |
| [AnnotationStateConverter](./annotationstateconverter/) |  |
| [AnnotationStateModelConverter](./annotationstatemodelconverter/) |  |
| [AppearanceDictionary](./appearancedictionary/) | [Аннотация](./annotation/) словарь внешнего вида, определяющий, как аннотация должна визуально отображаться на странице. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Представляет аннотацию Bleed Mark. |
| [Border](./border/) | Класс, представляющий характеристики границы аннотации. |
| [BorderEffectConverter](./bordereffectconverter/) |  |
| [BorderStyleConverter](./borderstyleconverter/) |  |
| [CaptionPositionConverter](./captionpositionconverter/) |  |
| [CaretAnnotation](./caretannotation/) | Класс, представляющий аннотацию Caret. |
| [CaretSymbolConverter](./caretsymbolconverter/) |  |
| [Characteristics](./characteristics/) | Представляет характеристики аннотации. |
| [CircleAnnotation](./circleannotation/) | Класс, представляющий аннотацию Circle. |
| [ColorBarAnnotation](./colorbarannotation/) | Класс, представляющий аннотацию [ColorBarAnnotation](./colorbarannotation/). Свойство [Color](../aspose.pdf/color/) игнорируется, вместо него используется цвет [ColorsOfCMYK](./colorsofcmyk/). При создании соотношение ширины и высоты определяет ориентацию аннотации — горизонтальную или вертикальную. Затем проверяется, находится ли прямоугольник аннотации за пределами TrimBox, и если нет, он смещается к ближайшему расположению за пределами TrimBox с учётом ориентации аннотации. Возможно уменьшить ширину (высоту), чтобы аннотация помещалась за пределами TrimBox. Если места для размещения нет, ширина/высота могут быть установлены в ноль (в этом случае аннотация присутствует на странице, но не отображается). |
| [ColorsOfCMYKConverter](./colorsofcmykconverter/) |  |
| [CommonFigureAnnotation](./commonfigureannotation/) | Абстрактный класс, представляющий общую фигурную аннотацию. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Представляет типы аннотаций, размещаемые в углах печатной страницы. |
| [CustomExplicitDestination](./customexplicitdestination/) | Представляет пользовательскую явную точку назначения. |
| [Dash](./dash/) | Класс, представляющий шаблон пунктирной линии. |
| [DefaultAppearance](./defaultappearance/) | Описывает внешний вид поля по умолчанию (шрифт, размер текста и цвет). |
| [DocumentActionCollection](./documentactioncollection/) | Класс описывает действия, выполняемые над некоторыми действиями с документом. |
| [ExplicitDestination](./explicitdestination/) | Представляет базовый класс для явных точек назначения в PDF‑документе. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) |  |
| [FdfReader](./fdfreader/) | Класс, выполняющий чтение формата FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Класс описывает аннотацию вложения файла. |
| [FileIconConverter](./fileiconconverter/) |  |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Представляет явную точку назначения, отображающую страницу с её содержимым, увеличенным настолько, чтобы её ограничивающий прямоугольник полностью помещался в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из них, центрируя ограничивающий прямоугольник в окне по другой оси. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Представляет явную точку назначения, отображающую страницу, при этом вертикальная координата top размещается у верхнего края окна, а содержимое страницы увеличивается настолько, чтобы вся ширина её ограничивающего прямоугольника помещалась в окне. Значение null для top указывает, что текущие значения этого параметра сохраняются без изменений. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Представляет явную точку назначения, отображающую страницу, при этом горизонтальная координата left размещается у левого края окна, а содержимое страницы увеличивается настолько, чтобы вся высота её ограничивающего прямоугольника помещалась в окне. Значение null для left указывает, что текущие значения этого параметра сохраняются без изменений. |
| [FitExplicitDestination](./fitexplicitdestination/) | Представляет явную точку назначения, отображающую страницу с её содержимым, увеличенным настолько, чтобы вся страница полностью помещалась в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из них, центрируя страницу в окне по другой оси. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Представляет явную точку назначения, отображающую страницу, при этом вертикальная координата top размещается у верхнего края окна, а содержимое страницы увеличивается настолько, чтобы вся её ширина полностью помещалась в окне. Значение null для top указывает, что текущие значения этого параметра сохраняются без изменений. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Представляет явную точку назначения, отображающую страницу с её содержимым, увеличенным настолько, чтобы прямоугольник, заданный координатами left, bottom, right и top, полностью помещался в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из них, центрируя прямоугольник в окне по другой оси. Значение null для любого из параметров может привести к непредсказуемому поведению. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Представляет явную точку назначения, отображающую страницу, при этом горизонтальная координата left размещается у левого края окна, а содержимое страницы увеличивается настолько, чтобы вся её высота полностью помещалась в окне. Значение null для left указывает, что текущие значения этого параметра сохраняются без изменений. |
| [FixedPrint](./fixedprint/) | Представляет фиксированные данные печати [Watermark](../aspose.pdf/watermark/)[Annotation](./annotation/). |
| [FreeTextAnnotation](./freetextannotation/) | Представляет аннотацию свободного текста, отображающую текст непосредственно на странице. В отличие от обычной текстовой аннотации, аннотация свободного текста не имеет состояний открыто/закрыто; вместо отображения во всплывающем окне текст всегда виден. |
| [FreeTextIntentConverter](./freetextintentconverter/) |  |
| [GenericAnnotation](./genericannotation/) | Класс описывает общую аннотацию. |
| [GoToAction](./gotoaction/) | Представляет действие перехода (go-to), которое изменяет вид на указанную точку назначения (страницу, местоположение и коэффициент масштабирования). |
| [GoToRemoteAction](./gotoremoteaction/) | Представляет удалённое действие перехода (go-to), аналогичное обычному действию перехода, но переходящее к точке назначения в другом PDF‑файле вместо текущего. |
| [GoToURIAction](./gotouriaction/) | Представляет действие URI, вызывающее разрешение URI. |
| [HideAction](./hideaction/) | Представляет действие скрытия, которое скрывает или отображает одну или несколько аннотаций на экране, устанавливая или сбрасывая их флаги Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Представляет аннотацию выделения, которая подсвечивает диапазон текста в документе. |
| [HighlightingModeConverter](./highlightingmodeconverter/) |  |
| [IAnnotationVisitor](./iannotationvisitor/) | Определяет Visitor для обхода различных аннотаций документа. |
| [IAppointment](./iappointment/) | Представляет общий интерфейс для действий и назначений. |
| [ImportDataAction](./importdataaction/) | При вызове действия import-data, данные [Forms](../aspose.pdf.forms/) Data Format (FDF) должны быть импортированы в интерактивную форму документа из указанного файла. |
| [InkAnnotation](./inkannotation/) | Представляет свободный "scribble", состоящий из одной или нескольких разрозненных путей. |
| [JavascriptAction](./javascriptaction/) | Класс, представляющий действие javascript. |
| [JustificationConverter](./justificationconverter/) |  |
| [LaunchAction](./launchaction/) | Представляет действие запуска, которое запускает приложение или открывает, либо печатает документ. |
| [LaunchActionOperationConverter](./launchactionoperationconverter/) |  |
| [LineAnnotation](./lineannotation/) | Класс, представляющий аннотацию линии. |
| [LineEndingConverter](./lineendingconverter/) |  |
| [LineIntentConverter](./lineintentconverter/) |  |
| [LinkAnnotation](./linkannotation/) | Представляет либо гипертекстовую ссылку на назначение в другом месте документа, либо действие, которое следует выполнить. |
| [MarkupAnnotation](./markupannotation/) | Абстрактный класс, представляющий разметочную аннотацию. |
| [Measure](./measure/) | Класс, описывающий координатную систему [Measure](./measure/). |
| [MediaClip](./mediaclip/) | Класс, описывающий объект медиа‑клипа рендеринга. |
| [MediaClipData](./mediaclipdata/) | Класс, описывающий данные медиа‑клипа. |
| [MediaClipSection](./mediaclipsection/) | Этот класс описывает раздел Media clip. |
| [MediaRendition](./mediarendition/) | Класс, описывающий медиа‑рендеринг. |
| [MovieAnnotation](./movieannotation/) | Представляет аннотацию фильма, содержащую анимированную графику и звук, которые отображаются на экране компьютера и воспроизводятся через динамики. При активации аннотации фильм воспроизводится. |
| [NamedAction](./namedaction/) | Представляет именованные действия, которые ожидается поддерживать PDF‑просмотрщиками. |
| [NamedDestination](./nameddestination/) | Вместо прямого определения с помощью явного синтаксиса, назначение может ссылаться косвенно через объект имени или байтовую строку. |
| [PageInformationAnnotation](./pageinformationannotation/) | Представляет аннотацию [Page](../aspose.pdf/page/) Information в PDF‑документе. Эта аннотация содержит имя файла, номер страницы и дату и время создания аннотации. |
| [PDF3DAnnotation](./pdf3dannotation/) | Класс [PDF3DAnnotation](./pdf3dannotation/). Этот класс не может быть унаследован. |
| [PDF3DArtwork](./pdf3dartwork/) | Класс [PDF3DArtwork](./pdf3dartwork/). |
| [PDF3DContent](./pdf3dcontent/) | Класс [PDF3DContent](./pdf3dcontent/). |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Класс [PDF3DCrossSection](./pdf3dcrosssection/). |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Класс [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/). |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Класс [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/). |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Класс [PDF3DLightingScheme](./pdf3dlightingscheme/). |
| [PDF3DRenderMode](./pdf3drendermode/) | Класс [PDF3DRenderMode](./pdf3drendermode/). |
| [PDF3DStream](./pdf3dstream/) | Класс [PDF3DStream](./pdf3dstream/). |
| [PDF3DView](./pdf3dview/) | Класс [PDF3DView](./pdf3dview/). |
| [PDF3DViewArray](./pdf3dviewarray/) | Класс [PDF3DViewArray](./pdf3dviewarray/). |
| [PdfAction](./pdfaction/) | Представляет действие в PDF‑документе. |
| [PdfActionCollection](./pdfactioncollection/) | Класс описывает список действий. |
| [PolyAnnotation](./polyannotation/) | Абстрактный базовый класс для полигональных аннотаций. |
| [PolygonAnnotation](./polygonannotation/) | Класс, представляющий полигональную аннотацию. |
| [PolyIntentConverter](./polyintentconverter/) |  |
| [PolylineAnnotation](./polylineannotation/) | Представляет аннотацию полилиния, которая похожа на полигон, за исключением того, что первая и последняя вершины не соединяются автоматически. |
| [PopupAnnotation](./popupannotation/) | Представляет всплывающую аннотацию, которая отображает текст во всплывающем окне для ввода и редактирования. |
| [PredefinedActionConverter](./predefinedactionconverter/) |  |
| [PrinterMarkAnnotation](./printermarkannotation/) | Абстрактный класс, представляющий аннотацию отметки принтера. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Предоставляет методы расширения для перечисления [PrinterMarksKind](./printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Представляет аннотацию Redact. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Представляет аннотацию регистрационной метки. |
| [Rendition](./rendition/) | Класс, который описывает объект воспроизведения RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Действие воспроизведения, которое управляет воспроизведением мультимедийного контента. |
| [ReplyTypeConverter](./replytypeconverter/) |  |
| [RichMediaAnnotation](./richmediaannotation/) | Класс описывает [RichMediaAnnotation](./richmediaannotation/), который позволяет встраивать видео/аудио данные в PDF‑документ. |
| [ScreenAnnotation](./screenannotation/) | Экранная аннотация, указывающая область страницы, на которой могут воспроизводиться медиа‑клипы. |
| [SelectorRendition](./selectorrendition/) | Класс описывает селектор воспроизведения. |
| [SoundAnnotation](./soundannotation/) | Представляет звуковую аннотацию, содержащую звук, записанный с микрофона компьютера или импортированный из файла. |
| [SoundData](./sounddata/) | Представляет звуковые данные, определяющие звук, который будет воспроизводиться при активации аннотации. |
| [SoundEncodingConverter](./soundencodingconverter/) |  |
| [SoundIconConverter](./soundiconconverter/) |  |
| [SoundSampleData](./soundsampledata/) | Представляет дополнительные записи, специфичные для звукового объекта (Раздел 9.2 PDF1‑7). |
| [SquareAnnotation](./squareannotation/) | Класс, представляющий квадратную аннотацию. |
| [SquigglyAnnotation](./squigglyannotation/) | Представляет волнообразную аннотацию, которая отображается как неровное подчеркивание в тексте документа. |
| [StampAnnotation](./stampannotation/) | Представляет аннотацию в виде резиновой печати. Этот тип аннотации отображает текст или графику, имитирующие печать на странице резиновой печатью. |
| [StampIconConverter](./stampiconconverter/) |  |
| [StrikeOutAnnotation](./strikeoutannotation/) | Представляет аннотацию зачеркивания, которая отображается как зачеркивание в тексте документа. |
| [SubmitFormAction](./submitformaction/) | Класс, описывающий действие отправки формы. |
| [TextAnnotation](./textannotation/) | Представляет текстовую аннотацию, являющуюся «липкой заметкой», прикреплённой к точке в PDF‑документе. |
| [TextIconConverter](./texticonconverter/) |  |
| [TextMarkupAnnotation](./textmarkupannotation/) | Абстрактный базовый класс для текстовых разметочных аннотаций. |
| [TextStyle](./textstyle/) | Класс, представляющий стиль текста в аннотации. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Представляет аннотацию метки обрезки. |
| [UnderlineAnnotation](./underlineannotation/) | Представляет аннотацию подчеркивания, которая отображается как подчеркивание в тексте документа. |
| [WatermarkAnnotation](./watermarkannotation/) | Класс, описывающий объект аннотации [Watermark](../aspose.pdf/watermark/). |
| [WidgetAnnotation](./widgetannotation/) | Класс, представляющий виджет‑аннотацию. |
| [XfdfReader](./xfdfreader/) | Класс, выполняющий чтение формата XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Представляет явный пункт назначения, который отображает страницу с координатами (left, top), расположенными в левом верхнем углу окна, и содержимое страницы увеличивается с коэффициентом zoom. Значение null для любого из параметров left, top или zoom указывает, что текущие значения этих параметров должны оставаться без изменений. Значение zoom, равное 0, имеет то же значение, что и null. |
## Enums

| Перечисление | Описание |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Набор флагов, определяющих различные характеристики аннотации. |
| [AnnotationState](./annotationstate/) | Перечисление состояний, в которые может быть установлена оригинальная аннотация. |
| [AnnotationStateModel](./annotationstatemodel/) | Модель состояния, соответствующая состоянию аннотации. |
| [AnnotationType](./annotationtype/) | Перечисление типов аннотаций. |
| [BorderEffect](./bordereffect/) | Описывает эффект, который должен быть применён к границе аннотаций. |
| [BorderStyle](./borderstyle/) | Описывает стиль границы аннотации. |
| [CapStyle](./capstyle/) | Стиль окончания линии в аннотации Ink. |
| [CaptionPosition](./captionposition/) | Перечисление расположения подписи аннотации. |
| [CaretSymbol](./caretsymbol/) | Символ, который будет связан с кареткой. |
| [ColorsOfCMYK](./colorsofcmyk/) | Цвета, включённые в цветовую модель CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Перечисляет типы явных пунктов назначения. |
| [FileIcon](./fileicon/) | Значок, используемый при отображении аннотации. |
| [FreeTextIntent](./freetextintent/) | Перечисляет намерения свободной текстовой аннотации. |
| [HighlightingMode](./highlightingmode/) | Перечисляет режим подсветки аннотации, визуальный эффект, который будет использоваться при нажатии или удержании кнопки мыши внутри её активной области. |
| [Justification](./justification/) | Перечисляет формы выравнивания (justification) текста аннотации. |
| [LaunchActionOperation](./launchactionoperation/) | Перечисляет операции, которые следует выполнить с документом во время выполнения действия запуска. |
| [LightingSchemeType](./lightingschemetype/) | Перечисление [LightingSchemeType](./lightingschemetype/): набор типов схем освещения. |
| [LineEnding](./lineending/) | Перечисляет стили окончаний линии, используемые при её рисовании. |
| [LineIntent](./lineintent/) | Перечисляет намерения линейной аннотации. |
| [PDF3DActivation](./pdf3dactivation/) | Перечисление [PDF3DActivation](./pdf3dactivation/): набор режимов активации 3D‑аннотации. |
| [PolyIntent](./polyintent/) | Перечисляет намерения полигональной или полилинейной аннотации. |
| [PredefinedAction](./predefinedaction/) | Определяет различные действия, которые могут быть вызваны из PDF‑файла. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Представляет позицию метки в углу страницы. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Представляет позицию регистрационной метки на странице. |
| [PrinterMarksKind](./printermarkskind/) | Указывает типы печатных меток, которые следует добавить в документ. |
| [RenderModeType](./rendermodetype/) | Перечисление [RenderModeType](./rendermodetype/): набор типов режимов рендеринга. |
| [RenditionOperation](./renditionoperation/) | Операция, которую следует выполнить при срабатывании действия. |
| [RenditionType](./renditiontype/) | Перечисление описывает возможные типы [Rendition](./rendition/). |
| [ReplyType](./replytype/) | Перечисляет виды отношений (\"reply type\") между аннотацией и той, которая указана в InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Параметры стилизации фрагментов текста в RichText. |
| [SoundEncoding](./soundencoding/) | Формат кодирования образцовых данных. |
| [SoundIcon](./soundicon/) | Перечисляет значки, используемые при отображении аннотации. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Формат кодирования звуковых образцовых данных. |
| [StampIcon](./stampicon/) | Перечисляет значки, используемые при отображении аннотации. |
| [TextAlignment](./textalignment/) | Выравнивание текста в аннотации. |
| [TextIcon](./texticon/) | Перечисляет значки, используемые при отображении аннотации. |
