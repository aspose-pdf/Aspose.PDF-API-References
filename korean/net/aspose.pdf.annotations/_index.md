---
title: "Aspose.Pdf.Annotations"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations 네임스페이스는 다양한 유형의 작업 대상 및 문서의 기타 기능을 다루는 클래스를 제공하며, 전통적으로 인터랙티브라고 불리는 기능을 통해 사용자가 문서와 상호 작용할 수 있도록 합니다."
type: docs
weight: 50
url: /ko/net/aspose.pdf.annotations/
---
**Aspose.Pdf.Annotations** 네임스페이스는 전통적으로 인터랙티브라고 불리는 문서의 다양한 작업 유형, 목적지 및 기타 기능을 다루는 클래스를 제공하여 사용자가 문서와 상호 작용할 수 있도록 합니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [ActionCollection](./actioncollection/) | 작업 컬렉션 |
| [Annotation](./annotation/) | 주석 객체를 나타내는 클래스. |
| [AnnotationActionCollection](./annotationactioncollection/) | 주석 작업의 컬렉션을 나타냅니다. |
| [AnnotationCollection](./annotationcollection/) | 주석 컬렉션을 나타내는 클래스. |
| [AnnotationSelector](./annotationselector/) | 이 클래스는 Visitor 템플릿 아이디어를 사용하여 주석을 선택하는 데 사용됩니다. |
| [AppearanceDictionary](./appearancedictionary/) | 주석이 페이지에 시각적으로 표시되는 방식을 지정하는 주석 외관 사전입니다. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Bleed Mark 주석을 나타냅니다. |
| [Border](./border/) | 주석 테두리 특성을 나타내는 클래스. |
| [CaretAnnotation](./caretannotation/) | Caret 주석을 나타내는 클래스. |
| [Characteristics](./characteristics/) | 주석 특성을 나타냅니다. |
| [CircleAnnotation](./circleannotation/) | Circle 주석을 나타내는 클래스. |
| [ColorBarAnnotation](./colorbarannotation/) | ColorBarAnnotation 주석을 나타내는 클래스입니다. Property Color는 무시되고 대신 ColorsOfCMYK 색상이 사용됩니다. 생성 시, 너비와 높이의 비율에 따라 주석의 방향이 가로 또는 세로로 결정됩니다. 다음으로 주석 사각형이 TrimBox 외부에 있는지 확인하고, 외부에 있지 않으면 주석의 방향을 고려하여 가장 가까운 TrimBox 외부 위치로 이동합니다. 주석이 TrimBox 외부에 맞도록 너비(높이)를 줄일 수 있습니다. 레이아웃을 위한 공간이 없을 경우, 너비/높이를 0으로 설정할 수 있습니다(이 경우 주석은 페이지에 존재하지만 표시되지 않습니다). |
| [CommonFigureAnnotation](./commonfigureannotation/) | 공통 도형 주석을 나타내는 추상 클래스. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | 인쇄된 페이지의 모서리에 배치되는 주석 유형을 나타냅니다. |
| [CustomExplicitDestination](./customexplicitdestination/) | 사용자 정의 명시적 목적지를 나타냅니다. |
| [Dash](./dash/) | 선 대시 패턴을 나타내는 클래스. |
| [DefaultAppearance](./defaultappearance/) | 필드의 기본 외관(글꼴, 텍스트 크기 및 색상)을 설명합니다. |
| [DocumentActionCollection](./documentactioncollection/) | 클래스는 문서와 관련된 일부 작업에 수행되는 동작을 설명합니다. |
| [ExplicitDestination](./explicitdestination/) | PDF 문서에서 명시적 목적지를 위한 기본 클래스를 나타냅니다. |
| [FdfReader](./fdfreader/) | FDF 형식 읽기를 수행하는 클래스. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | 파일 첨부 주석을 설명하는 클래스. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | 수평 및 수직으로 창 안에 경계 상자를 완전히 맞추도록 페이지 내용을 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. 필요한 수평 및 수직 확대 비율이 다르면 두 비율 중 작은 값을 사용하고, 다른 차원에서는 경계 상자를 창 중앙에 배치합니다. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | 수직 좌표 top이 창의 상단 가장자리에 위치하고 페이지 내용이 경계 상자의 전체 너비가 창 안에 들어가도록 충분히 확대하여 페이지를 표시하는 명시적 목적지를 나타냅니다. top에 null 값을 지정하면 해당 매개변수의 현재 값이 그대로 유지됩니다. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | 수평 좌표 left가 창의 왼쪽 가장자리에 위치하고 페이지 내용이 경계 상자의 전체 높이가 창 안에 들어가도록 충분히 확대하여 페이지를 표시하는 명시적 목적지를 나타냅니다. left에 null 값을 지정하면 해당 매개변수의 현재 값이 그대로 유지됩니다. |
| [FitExplicitDestination](./fitexplicitdestination/) | 수평 및 수직으로 창 안에 전체 페이지가 들어가도록 페이지 내용을 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. 필요한 수평 및 수직 확대 비율이 다르면 두 비율 중 작은 값을 사용하고, 다른 차원에서는 페이지를 창 중앙에 배치합니다. |
| [FitHExplicitDestination](./fithexplicitdestination/) | 수직 좌표 top이 창의 상단 가장자리에 위치하고 페이지 내용이 페이지 전체 너비가 창 안에 들어가도록 충분히 확대하여 페이지를 표시하는 명시적 목적지를 나타냅니다. top에 null 값을 지정하면 해당 매개변수의 현재 값이 그대로 유지됩니다. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | 좌표 left, bottom, right, top으로 지정된 사각형이 창 안에 완전히 들어가도록 페이지 내용을 충분히 확대하여 표시하는 명시적 목적지를 나타냅니다. 수평 및 수직 확대 비율이 다르면 두 비율 중 작은 값을 사용하고, 다른 차원에서는 사각형을 창 중앙에 배치합니다. 매개변수 중 하나에 null 값을 지정하면 예측할 수 없는 동작이 발생할 수 있습니다. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | 수평 좌표 left가 창의 왼쪽 가장자리에 위치하고 페이지 내용이 페이지 전체 높이가 창 안에 들어가도록 충분히 확대하여 페이지를 표시하는 명시적 목적지를 나타냅니다. left에 null 값을 지정하면 해당 매개변수의 현재 값이 그대로 유지됩니다. |
| [FixedPrint](./fixedprint/) | 워터마크 주석의 고정 인쇄 데이터를 나타냅니다. |
| [FreeTextAnnotation](./freetextannotation/) | 페이지에 직접 텍스트를 표시하는 자유 텍스트 주석을 나타냅니다. 일반 텍스트 주석과 달리 자유 텍스트 주석은 열림 또는 닫힘 상태가 없으며, 팝업 창에 표시되는 대신 텍스트가 항상 보입니다. |
| [GoToAction](./gotoaction/) | 지정된 목적지(페이지, 위치 및 확대 비율)로 뷰를 변경하는 이동 동작을 나타냅니다. |
| [GoToRemoteAction](./gotoremoteaction/) | 일반 이동 동작과 유사하지만 현재 파일이 아닌 다른 PDF 파일의 목적지로 이동하는 원격 이동 동작을 나타냅니다. |
| [GoToURIAction](./gotouriaction/) | URI를 해결하도록 하는 URI 동작을 나타냅니다. |
| [HideAction](./hideaction/) | Hidden 플래그를 설정하거나 해제하여 화면상의 하나 이상의 주석을 숨기거나 표시하는 숨기기 동작을 나타냅니다. |
| [HighlightAnnotation](./highlightannotation/) | 문서에서 텍스트 범위를 강조 표시하는 하이라이트 주석을 나타냅니다. |
| [ImportDataAction](./importdataaction/) | import-data 동작이 호출될 때, Forms Data Format(FDF) 데이터가 지정된 파일에서 문서의 대화형 양식으로 가져와집니다. |
| [InkAnnotation](./inkannotation/) | 하나 이상의 분리된 경로로 구성된 자유형 "낙서"를 나타냅니다. |
| [JavascriptAction](./javascriptaction/) | JavaScript 동작을 나타내는 클래스. |
| [LaunchAction](./launchaction/) | 응용 프로그램을 실행하거나 문서를 열거나 인쇄하는 실행 동작을 나타냅니다. |
| [LineAnnotation](./lineannotation/) | 선 주석을 나타내는 클래스. |
| [LinkAnnotation](./linkannotation/) | 문서의 다른 위치에 있는 목적지로의 하이퍼텍스트 링크이거나 수행될 작업을 나타냅니다. |
| [MarkupAnnotation](./markupannotation/) | 마크업 주석을 나타내는 추상 클래스입니다. |
| [Measure](./measure/) | 측정 좌표계를 설명하는 클래스입니다. |
| [MediaClip](./mediaclip/) | 렌더링의 미디어 클립 객체를 설명하는 클래스입니다. |
| [MediaClipData](./mediaclipdata/) | 미디어 클립 데이터를 설명하는 클래스입니다. |
| [MediaClipSection](./mediaclipsection/) | 이 클래스는 미디어 클립 섹션을 설명합니다. |
| [MediaRendition](./mediarendition/) | 미디어 렌더링을 설명하는 클래스입니다. |
| [MovieAnnotation](./movieannotation/) | 컴퓨터 화면과 스피커를 통해 표시되는 애니메이션 그래픽 및 사운드를 포함하는 영화 주석을 나타냅니다. 주석이 활성화되면 영화가 재생됩니다. |
| [NamedAction](./namedaction/) | PDF 뷰어 애플리케이션이 지원하도록 예상되는 명명된 작업을 나타냅니다. |
| [NamedDestination](./nameddestination/) | 명시적 구문으로 직접 정의하는 대신, 목적지는 이름 객체나 바이트 문자열을 통해 간접적으로 참조될 수 있습니다. |
| [PageInformationAnnotation](./pageinformationannotation/) | PDF 문서의 페이지 정보 주석을 나타냅니다. 이 주석에는 파일 이름, 페이지 번호 및 주석 생성 날짜와 시간이 포함됩니다. |
| [PDF3DAnnotation](./pdf3dannotation/) | PDF3DAnnotation 클래스입니다. 이 클래스는 상속될 수 없습니다. |
| [PDF3DArtwork](./pdf3dartwork/) | PDF3DArtwork 클래스. |
| [PDF3DContent](./pdf3dcontent/) | PDF3DContent 클래스. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | PDF3DCrossSection 클래스. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | PDF3DCrossSectionArray 클래스. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | PDF3DCuttingPlaneOrientation 클래스. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | PDF3DLightingScheme 클래스. |
| [PDF3DRenderMode](./pdf3drendermode/) | PDF3DRenderMode 클래스. |
| [PDF3DStream](./pdf3dstream/) | PDF3DStream 클래스. |
| [PDF3DView](./pdf3dview/) | PDF3DView 클래스. |
| [PDF3DViewArray](./pdf3dviewarray/) | PDF3DViewArray 클래스. |
| [PdfAction](./pdfaction/) | PDF 문서의 작업을 나타냅니다 |
| [PdfActionCollection](./pdfactioncollection/) | 작업 목록을 설명하는 클래스입니다. |
| [PolyAnnotation](./polyannotation/) | 다중 주석을 위한 추상 기본 클래스입니다. |
| [PolygonAnnotation](./polygonannotation/) | 다각형 주석을 나타내는 클래스. |
| [PolylineAnnotation](./polylineannotation/) | 다각형과 유사하지만 첫 번째와 마지막 정점이 암시적으로 연결되지 않는 폴리라인 주석을 나타냅니다. |
| [PopupAnnotation](./popupannotation/) | 입력 및 편집을 위해 팝업 창에 텍스트를 표시하는 팝업 주석을 나타냅니다. |
| [PrinterMarkAnnotation](./printermarkannotation/) | 프린터 마크 주석을 나타내는 추상 클래스. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/) 열거형에 대한 확장 메서드를 제공합니다. |
| [RedactionAnnotation](./redactionannotation/) | Redact 주석을 나타냅니다. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Registration Mark 주석을 나타냅니다. |
| [Rendition](./rendition/) | RendtionAnnotation의 렌디션 객체를 설명하는 클래스. |
| [RenditionAction](./renditionaction/) | 멀티미디어 콘텐츠 재생을 제어하는 렌디션 작업. |
| [RichMediaAnnotation](./richmediaannotation/) | PDF 문서에 비디오/오디오 데이터를 삽입할 수 있는 RichMediaAnnotation을 설명하는 클래스. |
| [ScreenAnnotation](./screenannotation/) | 미디어 클립을 재생할 수 있는 페이지 영역을 지정하는 화면 주석. |
| [SelectorRendition](./selectorrendition/) | 셀렉터 렌디션을 설명하는 클래스. |
| [SoundAnnotation](./soundannotation/) | 컴퓨터 마이크에서 녹음하거나 파일에서 가져온 사운드를 포함하는 사운드 주석을 나타냅니다. |
| [SoundData](./sounddata/) | 주석이 활성화될 때 재생될 사운드를 정의하는 사운드 데이터를 나타냅니다. |
| [SoundSampleData](./soundsampledata/) | 사운드 객체에 특정된 추가 항목을 나타냅니다 (Section 9.2 PDF1-7). |
| [SquareAnnotation](./squareannotation/) | 사각형 주석을 나타내는 클래스. |
| [SquigglyAnnotation](./squigglyannotation/) | 문서 텍스트에 들쭉날쭉한 밑줄로 표시되는 스퀴글리 주석을 나타냅니다. |
| [StampAnnotation](./stampannotation/) | 고무 스탬프 주석을 나타냅니다. 이 유형의 주석은 페이지에 고무 스탬프로 찍은 것처럼 보이는 텍스트 또는 그래픽을 표시합니다. |
| [StrikeOutAnnotation](./strikeoutannotation/) | 문서 텍스트에 취소선으로 표시되는 스트라이크아웃 주석을 나타냅니다. |
| [SubmitFormAction](./submitformaction/) | 제출 양식 작업을 설명하는 클래스. |
| [TextAnnotation](./textannotation/) | PDF 문서의 한 지점에 부착된 '스티키 노트'인 텍스트 주석을 나타냅니다. |
| [TextMarkupAnnotation](./textmarkupannotation/) | 텍스트 마크업 주석을 위한 추상 기본 클래스. |
| [TextStyle](./textstyle/) | 주석 내 텍스트 스타일을 나타내는 클래스. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Trim Mark 주석을 나타냅니다. |
| [UnderlineAnnotation](./underlineannotation/) | 문서 텍스트에 밑줄로 표시되는 언더라인 주석을 나타냅니다. |
| [WatermarkAnnotation](./watermarkannotation/) | 클래스는 워터마크 주석 객체를 설명합니다. |
| [WidgetAnnotation](./widgetannotation/) | 클래스는 위젯 주석을 나타냅니다. |
| [XfdfReader](./xfdfreader/) | XFDF 형식 읽기를 수행하는 클래스. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | 명시적 목적지를 나타내며, 페이지를 좌표 (left, top) 로 창의 왼쪽 상단에 배치하고 페이지 내용을 zoom 비율로 확대하여 표시합니다. left, top 또는 zoom 매개변수 중 어느 하나가 null 값이면 해당 매개변수의 현재 값이 변경되지 않고 유지됩니다. zoom 값이 0인 경우는 null 값과 동일한 의미입니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | 다양한 문서 주석을 방문하기 위한 Visitor를 정의합니다. |
| [IAppointment](./iappointment/) | 동작 및 목적지를 위한 일반 인터페이스를 나타냅니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | 주석의 다양한 특성을 지정하는 플래그 집합입니다. |
| [AnnotationState](./annotationstate/) | 원본 주석이 설정될 수 있는 상태들의 열거형입니다. |
| [AnnotationStateModel](./annotationstatemodel/) | 주석 상태에 해당하는 상태 모델입니다. |
| [AnnotationType](./annotationtype/) | 주석 유형의 열거형입니다. |
| [BorderEffect](./bordereffect/) | 주석 테두리에 적용되어야 할 효과를 설명합니다. |
| [BorderStyle](./borderstyle/) | 주석 테두리의 스타일을 설명합니다. |
| [CapStyle](./capstyle/) | 잉크 주석 선의 라인 엔딩 스타일입니다. |
| [CaptionPosition](./captionposition/) | 주석 캡션 위치 지정의 열거형입니다. |
| [CaretSymbol](./caretsymbol/) | 캐럿과 연결될 기호입니다. |
| [ColorsOfCMYK](./colorsofcmyk/) | CMYK 색상 모델에 포함된 색상들입니다. |
| [ExplicitDestinationType](./explicitdestinationtype/) | 명시적 목적지 유형을 열거합니다. |
| [FileIcon](./fileicon/) | 주석 표시 시 사용되는 아이콘입니다. |
| [FreeTextIntent](./freetextintent/) | 자유 텍스트 주석의 의도를 열거합니다. |
| [HighlightingMode](./highlightingmode/) | 주석의 하이라이트 모드를 열거하며, 활성 영역 내에서 마우스 버튼을 누르거나 눌러 있을 때 사용되는 시각 효과를 나타냅니다. |
| [Justification](./justification/) | 주석 텍스트 표시 시 사용할 정렬(좌/우 정렬) 형태를 열거합니다. |
| [LaunchActionOperation](./launchactionoperation/) | 실행 작업을 시작할 때 문서와 함께 수행할 작업을 열거합니다. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: 조명 스키마 유형 집합입니다. |
| [LineEnding](./lineending/) | 선을 그릴 때 사용할 라인 엔딩 스타일을 열거합니다. |
| [LineIntent](./lineintent/) | 라인 주석의 의도를 열거합니다. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: 3D 주석 활성화 모드 집합. |
| [PolyIntent](./polyintent/) | 다각형 또는 폴리라인 주석의 의도를 열거합니다. |
| [PredefinedAction](./predefinedaction/) | PDF 파일에서 트리거될 수 있는 다양한 동작을 정의합니다. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | 페이지 모서리에 있는 마크의 위치를 나타냅니다. |
| [PrinterMarkSidePosition](./printermarksideposition/) | 페이지에 있는 레지스트레이션 마크의 위치를 나타냅니다. |
| [PrinterMarksKind](./printermarkskind/) | 문서에 추가될 프린터 마크의 유형을 지정합니다. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: 렌더 모드 유형 집합 |
| [RenditionOperation](./renditionoperation/) | 동작이 트리거될 때 수행할 작업입니다. |
| [RenditionType](./renditiontype/) | 열거형은 가능한 렌더링 유형을 설명합니다. |
| [ReplyType](./replytype/) | 주석과 InReplyTo에 의해 지정된 항목 사이의 관계 종류("reply type")를 열거합니다. |
| [RichTextFontStyles](./richtextfontstyles/) | RichText에서 텍스트 조각을 스타일링하기 위한 옵션입니다. |
| [SoundEncoding](./soundencoding/) | 샘플 데이터의 인코딩 형식입니다. |
| [SoundIcon](./soundicon/) | 주석 표시 시 사용할 아이콘을 열거합니다. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | 사운드 샘플 데이터의 인코딩 형식입니다. |
| [StampIcon](./stampicon/) | 주석 표시 시 사용할 아이콘을 열거합니다. |
| [TextIcon](./texticon/) | 주석 표시 시 사용할 아이콘을 열거합니다. |


