---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations 네임스페이스는 전통적으로 상호작용이라고 불리는 문서의 다양한 유형의 작업 목적지 및 기타 기능을 다루기 위한 클래스를 제공합니다. 사용자가 문서와 상호작용할 수 있는 수단을 제공합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.annotations/
---
**Aspose.Pdf.Annotations** 네임스페이스는 전통적으로 상호작용이라고 불리는 문서의 다양한 유형의 작업, 목적지 및 기타 기능을 다루기 위한 클래스를 제공합니다. 사용자가 문서와 상호작용할 수 있는 수단을 제공합니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [ActionCollection](./actioncollection/) | 작업의 모음 |
| [Annotation](./annotation/) | 주석 객체를 나타내는 클래스입니다. |
| [AnnotationActionCollection](./annotationactioncollection/) | 주석 작업의 모음을 나타냅니다. |
| [AnnotationCollection](./annotationcollection/) | 주석 모음을 나타내는 클래스입니다. |
| [AnnotationSelector](./annotationselector/) | 이 클래스는 방문자 템플릿 아이디어를 사용하여 주석을 선택하는 데 사용됩니다. |
| [AppearanceDictionary](./appearancedictionary/) | 주석이 페이지에 시각적으로 어떻게 표시될지를 지정하는 주석 외관 사전입니다. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Bleed Mark 주석을 나타냅니다. |
| [Border](./border/) | 주석 테두리의 특성을 나타내는 클래스입니다. |
| [CaretAnnotation](./caretannotation/) | Caret 주석을 나타내는 클래스입니다. |
| [Characteristics](./characteristics/) | 주석 특성을 나타냅니다. |
| [CircleAnnotation](./circleannotation/) | Circle 주석을 나타내는 클래스입니다. |
| [ColorBarAnnotation](./colorbarannotation/) | ColorBarAnnotation 주석을 나타내는 클래스입니다. Color 속성은 무시되며, 대신 ColorsOfCMYK 색상이 사용됩니다. 생성 시 너비와 높이의 비율이 주석의 방향(수평 또는 수직)을 결정합니다. 다음으로 주석 사각형이 TrimBox 외부에 있는지 확인하고, 그렇지 않은 경우 주석의 방향을 고려하여 TrimBox 외부의 가장 가까운 위치로 이동합니다. 주석이 TrimBox 외부에 맞도록 너비(높이)를 줄이는 것이 가능합니다. 레이아웃을 위한 공간이 없으면 너비/높이를 0으로 설정할 수 있습니다(이 경우 주석은 페이지에 존재하지만 표시되지 않습니다). |
| [CommonFigureAnnotation](./commonfigureannotation/) | 일반 도형 주석을 나타내는 추상 클래스입니다. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | 인쇄된 페이지의 모서리에 배치되는 주석 유형을 나타냅니다. |
| [CustomExplicitDestination](./customexplicitdestination/) | 사용자 정의 명시적 목적지를 나타냅니다. |
| [Dash](./dash/) | 선 대시 패턴을 나타내는 클래스입니다. |
| [DefaultAppearance](./defaultappearance/) | 필드의 기본 외관(글꼴, 텍스트 크기 및 색상)을 설명합니다. |
| [DocumentActionCollection](./documentactioncollection/) | 문서와 관련된 일부 작업을 설명하는 클래스입니다. |
| [ExplicitDestination](./explicitdestination/) | PDF 문서에서 명시적 목적지의 기본 클래스를 나타냅니다. |
| [FdfReader](./fdfreader/) | FDF 형식을 읽는 클래스를 나타냅니다. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | 파일 첨부 주석을 설명하는 클래스입니다. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | 페이지의 내용을 창 내에서 수평 및 수직으로 완전히 맞추기 위해 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. 필요한 수평 및 수직 확대 비율이 다르면 두 값 중 작은 값을 사용하여 다른 차원에서 창 내에 경계 상자를 중앙에 배치합니다. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | 페이지의 수직 좌표가 창의 상단 모서리에 위치하고 페이지의 내용이 창 내에서 경계 상자의 전체 너비에 맞도록 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. top에 대한 null 값은 해당 매개변수의 현재 값을 변경하지 않고 유지해야 함을 지정합니다. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | 페이지의 수평 좌표가 창의 왼쪽 모서리에 위치하고 페이지의 내용이 창 내에서 경계 상자의 전체 높이에 맞도록 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. left에 대한 null 값은 해당 매개변수의 현재 값을 변경하지 않고 유지해야 함을 지정합니다. |
| [FitExplicitDestination](./fitexplicitdestination/) | 페이지의 내용을 창 내에서 수평 및 수직으로 완전히 맞추기 위해 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. 필요한 수평 및 수직 확대 비율이 다르면 두 값 중 작은 값을 사용하여 다른 차원에서 페이지를 중앙에 배치합니다. |
| [FitHExplicitDestination](./fithexplicitdestination/) | 페이지의 수직 좌표가 창의 상단 모서리에 위치하고 페이지의 내용이 창 내에서 페이지의 전체 너비에 맞도록 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. top에 대한 null 값은 해당 매개변수의 현재 값을 변경하지 않고 유지해야 함을 지정합니다. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | 페이지의 내용을 수평 및 수직으로 완전히 맞추기 위해 충분히 확대하여 지정된 좌표(left, bottom, right, top)로 정의된 사각형 내에 표시하는 명시적 목적지를 나타냅니다. 필요한 수평 및 수직 확대 비율이 다르면 두 값 중 작은 값을 사용하여 다른 차원에서 사각형을 중앙에 배치합니다. 매개변수 중 하나에 대한 null 값은 예측할 수 없는 동작을 초래할 수 있습니다. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | 페이지의 수평 좌표가 창의 왼쪽 모서리에 위치하고 페이지의 내용이 창 내에서 페이지의 전체 높이에 맞도록 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. left에 대한 null 값은 해당 매개변수의 현재 값을 변경하지 않고 유지해야 함을 지정합니다. |
| [FixedPrint](./fixedprint/) | 워터마크 주석의 고정 인쇄 데이터를 나타냅니다. |
| [FreeTextAnnotation](./freetextannotation/) | 페이지에 직접 텍스트를 표시하는 자유 텍스트 주석을 나타냅니다. 일반 텍스트 주석과 달리 자유 텍스트 주석은 열려 있거나 닫힌 상태가 없으며, 팝업 창에 표시되는 대신 텍스트가 항상 표시됩니다. |
| [GoToAction](./gotoaction/) | 지정된 목적지(페이지, 위치 및 확대 비율)로 뷰를 변경하는 이동 작업을 나타냅니다. |
| [GoToRemoteAction](./gotoremoteaction/) | 일반 이동 작업과 유사하지만 현재 파일 대신 다른 PDF 파일의 목적지로 점프하는 원격 이동 작업을 나타냅니다. |
| [GoToURIAction](./gotouriaction/) | URI를 해결하는 URI 작업을 나타냅니다. |
| [HideAction](./hideaction/) | 주석의 숨김 플래그를 설정하거나 지워 화면에서 하나 이상의 주석을 숨기거나 표시하는 숨김 작업을 나타냅니다. |
| [HighlightAnnotation](./highlightannotation/) | 문서에서 텍스트 범위를 강조 표시하는 강조 표시 주석을 나타냅니다. |
| [ImportDataAction](./importdataaction/) | 가져오기 데이터 작업이 호출되면 Forms Data Format (FDF) 데이터가 지정된 파일에서 문서의 대화형 양식으로 가져와집니다. |
| [InkAnnotation](./inkannotation/) | 하나 이상의 분리된 경로로 구성된 자유형 "낙서"를 나타냅니다. |
| [JavascriptAction](./javascriptaction/) | 자바스크립트 작업을 나타내는 클래스입니다. |
| [LaunchAction](./launchaction/) | 애플리케이션을 시작하거나 문서를 열거나 인쇄하는 시작 작업을 나타냅니다. |
| [LineAnnotation](./lineannotation/) | 선 주석을 나타내는 클래스입니다. |
| [LinkAnnotation](./linkannotation/) | 문서의 다른 위치로의 하이퍼텍스트 링크 또는 수행할 작업을 나타냅니다. |
| [MarkupAnnotation](./markupannotation/) | 마크업 주석을 나타내는 추상 클래스입니다. |
| [Measure](./measure/) | 측정 좌표계를 설명하는 클래스입니다. |
| [MediaClip](./mediaclip/) | 렌디션의 미디어 클립 객체를 설명하는 클래스입니다. |
| [MediaClipData](./mediaclipdata/) | 미디어 클립 데이터를 설명하는 클래스입니다. |
| [MediaClipSection](./mediaclipsection/) | 이 클래스는 미디어 클립 섹션을 설명합니다. |
| [MediaRendition](./mediarendition/) | 미디어 렌디션을 설명하는 클래스입니다. |
| [MovieAnnotation](./movieannotation/) | 컴퓨터 화면과 스피커에서 표시될 애니메이션 그래픽과 사운드를 포함하는 영화 주석을 나타냅니다. 주석이 활성화되면 영화가 재생됩니다. |
| [NamedAction](./namedaction/) | PDF 뷰어 응용 프로그램이 지원할 것으로 예상되는 명명된 작업을 나타냅니다. |
| [NamedDestination](./nameddestination/) | 명시적 구문으로 직접 정의되는 대신 이름 객체나 바이트 문자열을 통해 간접적으로 참조될 수 있는 목적지를 나타냅니다. |
| [PageInformationAnnotation](./pageinformationannotation/) | PDF 문서에서 페이지 정보 주석을 나타냅니다. 이 주석은 파일 이름, 페이지 번호 및 주석 생성 날짜와 시간을 포함합니다. |
| [PDF3DAnnotation](./pdf3dannotation/) | PDF3DAnnotation 클래스입니다. 이 클래스는 상속할 수 없습니다. |
| [PDF3DArtwork](./pdf3dartwork/) | PDF3DArtwork 클래스입니다. |
| [PDF3DContent](./pdf3dcontent/) | PDF3DContent 클래스입니다. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | PDF3DCrossSection 클래스입니다. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | PDF3DCrossSectionArray 클래스입니다. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | PDF3DCuttingPlaneOrientation 클래스입니다. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | PDF3DLightingScheme 클래스입니다. |
| [PDF3DRenderMode](./pdf3drendermode/) | PDF3DRenderMode 클래스입니다. |
| [PDF3DStream](./pdf3dstream/) | PDF3DStream 클래스입니다. |
| [PDF3DView](./pdf3dview/) | PDF3DView 클래스입니다. |
| [PDF3DViewArray](./pdf3dviewarray/) | PDF3DViewArray 클래스입니다. |
| [PdfAction](./pdfaction/) | PDF 문서의 작업을 나타냅니다. |
| [PdfActionCollection](./pdfactioncollection/) | 작업 목록을 설명하는 클래스입니다. |
| [PolyAnnotation](./polyannotation/) | 다각형 주석의 추상 기본 클래스입니다. |
| [PolygonAnnotation](./polygonannotation/) | 다각형 주석을 나타내는 클래스입니다. |
| [PolylineAnnotation](./polylineannotation/) | 첫 번째와 마지막 정점이 암묵적으로 연결되지 않는 다각형과 유사한 폴리라인 주석을 나타냅니다. |
| [PopupAnnotation](./popupannotation/) | 입력 및 편집을 위해 팝업 창에 텍스트를 표시하는 팝업 주석을 나타냅니다. |
| [PrinterMarkAnnotation](./printermarkannotation/) | 프린터 마크 주석을 나타내는 추상 클래스입니다. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/) 열거형에 대한 확장 메서드를 제공합니다. |
| [RedactionAnnotation](./redactionannotation/) | Redact 주석을 나타냅니다. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | 등록 마크 주석을 나타냅니다. |
| [Rendition](./rendition/) | RenditionAnnotation의 렌디션 객체를 설명하는 클래스입니다. |
| [RenditionAction](./renditionaction/) | 멀티미디어 콘텐츠 재생을 제어하는 렌디션 작업입니다. |
| [RichMediaAnnotation](./richmediaannotation/) | PDF 문서에 비디오/오디오 데이터를 삽입할 수 있는 RichMediaAnnotation을 설명하는 클래스입니다. |
| [ScreenAnnotation](./screenannotation/) | 미디어 클립이 재생될 수 있는 페이지의 영역을 지정하는 화면 주석입니다. |
| [SelectorRendition](./selectorrendition/) | 선택기 렌디션을 설명하는 클래스입니다. |
| [SoundAnnotation](./soundannotation/) | 컴퓨터의 마이크로폰에서 녹음되거나 파일에서 가져온 소리를 포함하는 소리 주석을 나타냅니다. |
| [SoundData](./sounddata/) | 주석이 활성화될 때 재생될 소리를 정의하는 소리 데이터를 나타냅니다. |
| [SoundSampleData](./soundsampledata/) | 소리 객체에 특정한 추가 항목을 나타냅니다(섹션 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | 사각형 주석을 나타내는 클래스입니다. |
| [SquigglyAnnotation](./squigglyannotation/) | 문서의 텍스트에 톱니 모양의 밑줄로 나타나는 스퀴글리 주석을 나타냅니다. |
| [StampAnnotation](./stampannotation/) | 고무 도장 주석을 나타냅니다. 이 유형의 주석은 페이지에 고무 도장으로 찍힌 것처럼 보이도록 텍스트나 그래픽을 표시합니다. |
| [StrikeOutAnnotation](./strikeoutannotation/) | 문서의 텍스트에 취소선으로 나타나는 취소선 주석을 나타냅니다. |
| [SubmitFormAction](./submitformaction/) | 제출 양식 작업을 설명하는 클래스입니다. |
| [TextAnnotation](./textannotation/) | PDF 문서의 특정 지점에 부착된 '메모'인 텍스트 주석을 나타냅니다. |
| [TextMarkupAnnotation](./textmarkupannotation/) | 텍스트 마크업 주석의 추상 기본 클래스입니다. |
| [TextStyle](./textstyle/) | 주석의 텍스트 스타일을 나타내는 클래스입니다. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Trim Mark 주석을 나타냅니다. |
| [UnderlineAnnotation](./underlineannotation/) | 문서의 텍스트에 밑줄로 나타나는 밑줄 주석을 나타냅니다. |
| [WatermarkAnnotation](./watermarkannotation/) | 워터마크 주석 객체를 설명하는 클래스입니다. |
| [WidgetAnnotation](./widgetannotation/) | 위젯 주석을 나타내는 클래스입니다. |
| [XfdfReader](./xfdfreader/) | XFDF 형식을 읽는 클래스를 나타냅니다. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | (left, top) 좌표가 창의 왼쪽 상단 모서리에 위치하고 페이지의 내용이 확대 비율에 의해 확대되어 표시되는 명시적 목적지를 나타냅니다. left, top 또는 zoom 매개변수 중 하나에 대한 null 값은 해당 매개변수의 현재 값을 변경하지 않고 유지해야 함을 지정합니다. zoom 값이 0인 경우 null 값과 동일한 의미를 가집니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | 다양한 문서 주석을 방문하기 위한 방문자를 정의합니다. |
| [IAppointment](./iappointment/) | 작업 및 목적지에 대한 일반 인터페이스를 나타냅니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | 주석의 다양한 특성을 지정하는 플래그 집합입니다. |
| [AnnotationState](./annotationstate/) | 원래 주석이 설정될 수 있는 상태의 열거형입니다. |
| [AnnotationStateModel](./annotationstatemodel/) | 주석 상태에 해당하는 상태 모델입니다. |
| [AnnotationType](./annotationtype/) | 주석 유형의 열거형입니다. |
| [BorderEffect](./bordereffect/) | 주석의 테두리에 적용해야 할 효과를 설명합니다. |
| [BorderStyle](./borderstyle/) | 주석 테두리의 스타일을 설명합니다. |
| [CapStyle](./capstyle/) | 잉크 주석 선의 선 끝 스타일입니다. |
| [CaptionPosition](./captionposition/) | 주석의 캡션 위치 열거형입니다. |
| [CaretSymbol](./caretsymbol/) | 커서와 연관될 기호입니다. |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK 색상 모델에 포함된 색상입니다. |
| [ExplicitDestinationType](./explicitdestinationtype/) | 명시적 목적지의 유형을 열거합니다. |
| [FileIcon](./fileicon/) | 주석을 표시하는 데 사용될 아이콘입니다. |
| [FreeTextIntent](./freetextintent/) | 자유 텍스트 주석의 의도를 열거합니다. |
| [HighlightingMode](./highlightingmode/) | 주석의 강조 모드, 즉 마우스 버튼이 활성 영역 내에서 눌리거나 눌려 있을 때 사용할 시각적 효과를 열거합니다. |
| [Justification](./justification/) | 주석의 텍스트를 표시하는 데 사용할 쿼드(정렬)의 형태를 열거합니다. |
| [LaunchActionOperation](./launchactionoperation/) | 시작 작업 실행 중 문서와 수행할 작업을 열거합니다. |
| [LightingSchemeType](./lightingschemetype/) | 조명 스킴 유형의 집합을 나타내는 열거형입니다. |
| [LineEnding](./lineending/) | 선을 그릴 때 사용할 선 끝 스타일을 열거합니다. |
| [LineIntent](./lineintent/) | 선 주석의 의도를 열거합니다. |
| [PDF3DActivation](./pdf3dactivation/) | 3D 주석 활성화 모드의 집합을 나타내는 열거형입니다. |
| [PolyIntent](./polyintent/) | 다각형 또는 폴리라인 주석의 의도를 열거합니다. |
| [PredefinedAction](./predefinedaction/) | PDF 파일에서 트리거할 수 있는 다양한 작업을 정의합니다. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | 페이지 모서리에 있는 마크의 위치를 나타냅니다. |
| [PrinterMarkSidePosition](./printermarksideposition/) | 페이지에 있는 등록 마크의 위치를 나타냅니다. |
| [PrinterMarksKind](./printermarkskind/) | 문서에 추가할 프린터 마크의 유형을 지정합니다. |
| [RenderModeType](./rendermodetype/) | 렌더 모드 유형의 집합을 나타내는 열거형입니다. |
| [RenditionOperation](./renditionoperation/) | 작업이 트리거될 때 수행할 작업입니다. |
| [RenditionType](./renditiontype/) | 렌디션의 가능한 유형을 설명하는 열거형입니다. |
| [ReplyType](./replytype/) | 주석과 InReplyTo로 지정된 주석 간의 관계(“답변 유형”)의 종류를 열거합니다. |
| [SoundEncoding](./soundencoding/) | 샘플 데이터의 인코딩 형식입니다. |
| [SoundIcon](./soundicon/) | 주석을 표시하는 데 사용될 아이콘을 열거합니다. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | 소리 샘플 데이터의 인코딩 형식입니다. |
| [StampIcon](./stampicon/) | 주석을 표시하는 데 사용될 아이콘을 열거합니다. |
| [TextIcon](./texticon/) | 주석을 표시하는 데 사용될 아이콘을 열거합니다. |