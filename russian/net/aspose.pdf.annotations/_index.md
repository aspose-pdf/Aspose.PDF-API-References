---
title: "Aspose.Pdf.Annotations"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Пространство имен Aspose.Pdf.Annotations предоставляет классы для работы с различными типами действий, назначений и другими функциями документа, которые традиционно называют интерактивными, предоставляя средства для взаимодействия пользователя с ним."
type: docs
weight: 50
url: /ru/net/aspose.pdf.annotations/
---
Пространство имён **Aspose.Pdf.Annotations** предоставляет классы для работы с различными типами действий, назначений и другими функциями документа, которые традиционно называют интерактивными, предоставляя пользователю возможность взаимодействовать с ним.

## Классы

| Класс | Описание |
| --- | --- |
| [ActionCollection](./actioncollection/) | Коллекция действий |
| [Annotation](./annotation/) | Класс, представляющий объект аннотации. |
| [AnnotationActionCollection](./annotationactioncollection/) | Представляет коллекцию действий аннотации. |
| [AnnotationCollection](./annotationcollection/) | Класс, представляющий коллекцию аннотаций. |
| [AnnotationSelector](./annotationselector/) | Этот класс используется для выбора аннотаций с помощью идеи шаблона Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Словарь внешнего вида аннотации, указывающий, как аннотация должна визуально отображаться на странице. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Представляет аннотацию Bleed Mark. |
| [Border](./border/) | Класс, представляющий характеристики границы аннотации. |
| [CaretAnnotation](./caretannotation/) | Класс, представляющий аннотацию Caret. |
| [Characteristics](./characteristics/) | Представляет характеристики аннотации |
| [CircleAnnotation](./circleannotation/) | Класс, представляющий аннотацию Circle. |
| [ColorBarAnnotation](./colorbarannotation/) | Класс, представляющий аннотацию ColorBarAnnotation. Свойство Color игнорируется, вместо него используется цвет ColorsOfCMYK. При создании соотношение ширины и высоты определяет ориентацию аннотации — горизонтальную или вертикальную. Затем проверяется, находится ли прямоугольник аннотации за пределами TrimBox, и если нет, он смещается в ближайшее положение за пределами TrimBox с учётом ориентации аннотации. Возможно уменьшить ширину (высоту), чтобы аннотация помещалась за пределами TrimBox. Если места для размещения нет, ширина/высота могут быть установлены в ноль (в этом случае аннотация присутствует на странице, но не отображается). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Абстрактный класс, представляющий общую фигурную аннотацию. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Представляет типы аннотаций, размещаемые в углах печатной страницы. |
| [CustomExplicitDestination](./customexplicitdestination/) | Представляет пользовательскую явную цель. |
| [Dash](./dash/) | Класс, представляющий шаблон пунктирной линии. |
| [DefaultAppearance](./defaultappearance/) | Описывает внешний вид поля по умолчанию (шрифт, размер текста и цвет). |
| [DocumentActionCollection](./documentactioncollection/) | Класс описывает действия, выполняемые над некоторыми действиями с document. |
| [ExplicitDestination](./explicitdestination/) | Представляет базовый класс для явных назначений в PDF‑Document. |
| [FdfReader](./fdfreader/) | Класс, который выполняет чтение формата FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Класс описывает file attachment annotation. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Представляет явное назначение, которое отображает страницу с её содержимым, увеличенным настолько, чтобы её ограничивающий прямоугольник полностью помещался в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из них, центрируя ограничивающий прямоугольник в окне по другой оси. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Представляет явное назначение, которое отображает страницу, при этом вертикальная координата top располагается у верхнего края окна, а содержимое страницы увеличивается настолько, чтобы вся ширина её ограничивающего прямоугольника помещалась в окно. Значение null для top указывает, что текущий параметр должен оставаться без изменений. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Представляет явное назначение, которое отображает страницу, при этом горизонтальная координата left располагается у левого края окна, а содержимое страницы увеличивается настолько, чтобы вся высота её ограничивающего прямоугольника помещалась в окно. Значение null для left указывает, что текущий параметр должен оставаться без изменений. |
| [FitExplicitDestination](./fitexplicitdestination/) | Представляет явное назначение, которое отображает страницу с её содержимым, увеличенным настолько, чтобы вся страница полностью помещалась в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из них, центрируя страницу в окне по другой оси. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Представляет явное назначение, которое отображает страницу, при этом вертикальная координата top располагается у верхнего края окна, а содержимое страницы увеличивается настолько, чтобы вся ширина страницы помещалась в окно. Значение null для top указывает, что текущий параметр должен оставаться без изменений. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Представляет явное назначение, которое отображает страницу с её содержимым, увеличенным настолько, чтобы прямоугольник, указанный координатами left, bottom, right и top, полностью помещался в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из них, центрируя прямоугольник в окне по другой оси. Значение null для любого из параметров может привести к непредсказуемому поведению. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Представляет явное назначение, которое отображает страницу, при этом горизонтальная координата left располагается у левого края окна, а содержимое страницы увеличивается настолько, чтобы вся высота страницы помещалась в окно. Значение null для left указывает, что текущий параметр должен оставаться без изменений. |
| [FixedPrint](./fixedprint/) | Представляет фиксированные данные печати Watermark Annotation. |
| [FreeTextAnnotation](./freetextannotation/) | Представляет free text annotation, которая отображает текст непосредственно на странице. В отличие от обычной текстовой annotation, free text annotation не имеет состояний открыто/закрыто; вместо отображения во всплывающем окне текст всегда виден. |
| [GoToAction](./gotoaction/) | Представляет действие перехода, которое изменяет вид на указанное назначение (страница, место и коэффициент масштабирования). |
| [GoToRemoteAction](./gotoremoteaction/) | Представляет удалённое действие перехода, похожее на обычное действие перехода, но переходит к назначению в другом PDF‑файле вместо текущего. |
| [GoToURIAction](./gotouriaction/) | Представляет действие URI, которое приводит к разрешению URI. |
| [HideAction](./hideaction/) | Представляет действие скрытия, которое скрывает или показывает одну или несколько annotations на экране, устанавливая или снимая их флаг Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Представляет highlight annotation, которая подсвечивает диапазон текста в document. |
| [ImportDataAction](./importdataaction/) | При вызове действия import-data данные формата Forms Data Format (FDF) должны быть импортированы в интерактивную форму document из указанного файла. |
| [InkAnnotation](./inkannotation/) | Представляет свободный \"scribble\", состоящий из одного или нескольких несвязанных путей. |
| [JavascriptAction](./javascriptaction/) | Класс, представляющий действие javascript. |
| [LaunchAction](./launchaction/) | Представляет действие запуска, которое запускает приложение или открывает или печатает документ. |
| [LineAnnotation](./lineannotation/) | Класс, представляющий аннотацию линии. |
| [LinkAnnotation](./linkannotation/) | Представляет либо гипертекстовую ссылку на место назначения в другом месте document, либо действие, которое следует выполнить. |
| [MarkupAnnotation](./markupannotation/) | Абстрактный класс, представляющий разметочную аннотацию. |
| [Measure](./measure/) | Класс, описывающий систему координат измерения. |
| [MediaClip](./mediaclip/) | Класс, описывающий объект медиа‑клипа рендеринга. |
| [MediaClipData](./mediaclipdata/) | Класс, описывающий данные медиа‑клипа. |
| [MediaClipSection](./mediaclipsection/) | Этот класс описывает раздел медиа‑клипа. |
| [MediaRendition](./mediarendition/) | Класс, описывающий медиа‑рендеринг. |
| [MovieAnnotation](./movieannotation/) | Представляет аннотацию фильма, содержащую анимированную графику и звук, которые отображаются на экране компьютера и воспроизводятся через динамики. При активации аннотации фильм воспроизводится. |
| [NamedAction](./namedaction/) | Представляет именованные действия, которые, как ожидается, поддерживают приложения‑просмотрщики PDF. |
| [NamedDestination](./nameddestination/) | Вместо того чтобы определяться напрямую с помощью явного синтаксиса, место назначения может ссылаться косвенно через объект имени или байтовую строку. |
| [PageInformationAnnotation](./pageinformationannotation/) | Представляет аннотацию Page Information в document PDF. Эта аннотация содержит имя файла, номер page и дату и время создания аннотации. |
| [PDF3DAnnotation](./pdf3dannotation/) | Класс PDF3DAnnotation. Этот класс не может быть наследован. |
| [PDF3DArtwork](./pdf3dartwork/) | Класс PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Класс PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Класс PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Класс PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Класс PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Класс PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Класс PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Класс PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Класс PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Класс PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Представляет действие в document PDF |
| [PdfActionCollection](./pdfactioncollection/) | Класс описывает список действий. |
| [PolyAnnotation](./polyannotation/) | Абстрактный базовый класс для полигональных аннотаций. |
| [PolygonAnnotation](./polygonannotation/) | Класс, представляющий полигональную аннотацию. |
| [PolylineAnnotation](./polylineannotation/) | Представляет аннотацию полилиния, которая похожа на полигон, за исключением того, что первая и последняя вершины не соединяются автоматически. |
| [PopupAnnotation](./popupannotation/) | Представляет всплывающую аннотацию, которая отображает текст во всплывающем окне для ввода и редактирования. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Абстрактный класс, представляющий аннотацию отметки принтера. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Предоставляет методы расширения для перечисления [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Представляет аннотацию Redact. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Представляет аннотацию Registration Mark. |
| [Rendition](./rendition/) | Класс, описывающий объект воспроизведения RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Действие воспроизведения, которое управляет воспроизведением мультимедийного контента. |
| [RichMediaAnnotation](./richmediaannotation/) | Класс описывает RichMediaAnnotation, который позволяет встраивать видео/аудио данные в PDF‑документ. |
| [ScreenAnnotation](./screenannotation/) | Экранная аннотация, указывающая область страницы, на которой могут воспроизводиться медиа‑клипы. |
| [SelectorRendition](./selectorrendition/) | Класс описывает селектор воспроизведения. |
| [SoundAnnotation](./soundannotation/) | Представляет звуковую аннотацию, содержащую звук, записанный с микрофона компьютера или импортированный из файла. |
| [SoundData](./sounddata/) | Представляет звуковые данные, определяющие звук, который будет воспроизводиться при активации аннотации. |
| [SoundSampleData](./soundsampledata/) | Представляет дополнительные записи, специфичные для звукового объекта (Раздел 9.2 PDF1‑7). |
| [SquareAnnotation](./squareannotation/) | Класс, представляющий квадратную аннотацию. |
| [SquigglyAnnotation](./squigglyannotation/) | Представляет волнистую аннотацию, которая отображается как неровное подчеркивание в тексте документа. |
| [StampAnnotation](./stampannotation/) | Представляет аннотацию резиновой печати. Этот тип аннотации отображает текст или графику, имитирующие печать на странице резиновой печатью. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Представляет аннотацию зачеркивания, которая отображается как зачеркивание в тексте документа. |
| [SubmitFormAction](./submitformaction/) | Класс, описывающий действие submit-form. |
| [TextAnnotation](./textannotation/) | Представляет текстовую аннотацию, являющуюся «липкой заметкой», прикреплённой к точке в PDF‑документе. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Абстрактный базовый класс для текстовых разметочных аннотаций. |
| [TextStyle](./textstyle/) | Класс представляет стиль текста в аннотации. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Представляет аннотацию Trim Mark. |
| [UnderlineAnnotation](./underlineannotation/) | Представляет аннотацию подчёркивания, которая отображается как подчёркнутый текст в документе. |
| [WatermarkAnnotation](./watermarkannotation/) | Класс описывает объект аннотации Watermark. |
| [WidgetAnnotation](./widgetannotation/) | Класс, представляющий аннотацию widget. |
| [XfdfReader](./xfdfreader/) | Класс, который выполняет чтение формата XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Представляет явный пункт назначения, который отображает страницу с координатами (left, top), расположенными в левом верхнем углу окна, и содержимое страницы увеличивается в факторе zoom. Значение null для любого из параметров left, top или zoom указывает, что текущее значение этого параметра должно оставаться без изменений. Значение zoom, равное 0, имеет то же значение, что и значение null. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Определяет Visitor для обхода различных аннотаций документа. |
| [IAppointment](./iappointment/) | Представляет общий интерфейс для действий и пунктов назначения. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Набор флагов, определяющих различные характеристики аннотации. |
| [AnnotationState](./annotationstate/) | Перечисление состояний, в которые может быть установлена исходная аннотация. |
| [AnnotationStateModel](./annotationstatemodel/) | Модель состояния, соответствующая состоянию аннотации. |
| [AnnotationType](./annotationtype/) | Перечисление типов аннотаций. |
| [BorderEffect](./bordereffect/) | Описывает эффект, который должен быть применён к границе аннотаций. |
| [BorderStyle](./borderstyle/) | Описывает стиль границы аннотации. |
| [CapStyle](./capstyle/) | Стиль окончания линии аннотации Ink. |
| [CaptionPosition](./captionposition/) | Перечисление позиционирования подписи аннотации. |
| [CaretSymbol](./caretsymbol/) | Символ, который будет ассоциирован с кареткой. |
| [ColorsOfCMYK](./colorsofcmyk/) | Цвета, включённые в цветовую модель CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Перечисляет типы явных пунктов назначения. |
| [FileIcon](./fileicon/) | Иконка, используемая при отображении аннотации. |
| [FreeTextIntent](./freetextintent/) | Перечисляет назначения аннотации свободного текста. |
| [HighlightingMode](./highlightingmode/) | Перечисляет режим подсветки аннотации, визуальный эффект, используемый при нажатии или удержании кнопки мыши внутри её активной области. |
| [Justification](./justification/) | Перечисляет формы выравнивания (justification) текста аннотации. |
| [LaunchActionOperation](./launchactionoperation/) | Перечисляет операции, выполняемые с документом во время выполнения действия запуска. |
| [LightingSchemeType](./lightingschemetype/) | Перечисление LightingSchemeType: набор типов схем освещения. |
| [LineEnding](./lineending/) | Перечисляет стили завершения линии, используемые при рисовании линии. |
| [LineIntent](./lineintent/) | Перечисляет назначения аннотации линии. |
| [PDF3DActivation](./pdf3dactivation/) | Перечисление PDF3DActivation: набор режимов активации 3D‑аннотации. |
| [PolyIntent](./polyintent/) | Перечисляет назначения аннотации полигон или полилиния. |
| [PredefinedAction](./predefinedaction/) | Определяет различные действия, которые могут быть вызваны из PDF‑файла. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Представляет позицию метки в углу страницы. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Представляет позицию регистрационной метки на странице. |
| [PrinterMarksKind](./printermarkskind/) | Указывает типы принтерных меток, которые следует добавить в документ. |
| [RenderModeType](./rendermodetype/) | Перечисление RenderModeType: набор типов режимов рендеринга |
| [RenditionOperation](./renditionoperation/) | Операция, которую следует выполнить при срабатывании действия. |
| [RenditionType](./renditiontype/) | Перечисление описывает возможные типы воспроизведения. |
| [ReplyType](./replytype/) | Перечисляет виды отношений ("тип ответа") между аннотацией и той, которая указана в InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Параметры стилизации текстовых фрагментов в RichText. |
| [SoundEncoding](./soundencoding/) | Формат кодирования для образцовых данных. |
| [SoundIcon](./soundicon/) | Перечисляет значки, используемые при отображении аннотации. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Формат кодирования для звуковых образцовых данных. |
| [StampIcon](./stampicon/) | Перечисляет значки, используемые при отображении аннотации. |
| [TextIcon](./texticon/) | Перечисляет значки, используемые при отображении аннотации. |


