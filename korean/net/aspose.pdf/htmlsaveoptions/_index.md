---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptions 클래스. Html 형식으로 내보내기 위한 저장 옵션
type: docs
weight: 5560
url: /ko/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions 클래스

Html 형식으로 내보내기 위한 저장 옵션

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | `HtmlSaveOptions` 클래스의 새 인스턴스를 초기화합니다. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | `HtmlSaveOptions` 클래스의 새 인스턴스를 초기화합니다. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | `HtmlSaveOptions` 클래스의 새 인스턴스를 초기화합니다. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | `HtmlSaveOptions` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | 배치 변환이 소스 및 대상 형식 쌍에 적용 가능한 경우 배치 크기를 정의합니다. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps 페이지를 준비하는 동안 글꼴 글리프가 캐시될지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 소비를 증가시킵니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | 저장하는 동안 발견된 SVG 그래픽(있는 경우)이 SVGZ 형식으로 압축될지 여부를 나타내는 플래그를 가져오거나 설정합니다. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | ConvertMarkedContentToLayers 속성이 true로 설정되면 PDF 마크된 콘텐츠(레이어) 내부의 모든 요소가 레이어 이름을 지정하는 "data-pdflayer" 속성이 있는 HTML div에 배치됩니다. 이 레이어 이름은 PDF 마크된 콘텐츠의 선택적 속성에서 추출됩니다. 이 속성이 false(기본값)인 경우 PDF 마크된 콘텐츠에서 레이어가 생성되지 않습니다. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | 시스템에 설치되지 않았거나 포함되지 않은 문서 글꼴을 대체하는 데 사용되는 설치된 글꼴의 이름을 지정합니다. null인 경우 기본 대체 글꼴이 사용됩니다. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | [`HtmlDocumentType`](../htmldocumenttype/)을 가져오거나 설정합니다. |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | 이 속성을 사용하면 변환할 문서의 페이지를 명시적으로 정의할 수 있습니다. 이 목록의 페이지는 1 기반 번호를 가져야 합니다. 즉, 유효한 페이지 번호는 (1...[NumberOfPagesInConvertedDocument]) 범위에서 가져와야 합니다. 이 목록의 페이지가 나타나는 순서는 결과 HTML 페이지의 순서에 영향을 미치지 않습니다. 이 목록이 null인 경우(기본값) 모든 페이지가 변환됩니다. 이 목록의 페이지 번호가 현재 페이지 범위(1-[amountOfPagesInDocument])를 벗어나면 예외가 발생합니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 하위 레이어가 있는 PDF 문서에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | HTML이 고정 레이아웃으로 생성될지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | 이 속성은 흐름 모드에서 전체 너비 단락 텍스트를 지정합니다. FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | 미리 저장된 글꼴의 글꼴 소스입니다. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | 지정된 크기 이하의 텍스트는 변환 중에 무시됩니다. 이 텍스트는 제거되지 않고 무시되며 출력 파일로 전송되지 않습니다. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | 글꼴 부재와 관련된 오류를 무시할지 여부를 가져오거나 설정합니다. true - 글꼴 부재의 오류가 무시됨을 의미합니다. 잘못된 리소스를 참조하는 텍스트 세그먼트는 처리 중에 건너뜁니다. 기본값은 false입니다. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | 이미지 렌더링을 위한 해상도를 가져오거나 설정합니다. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | 이 속성은 그래픽 경로 선의 최소 너비를 설정합니다. 선의 두께가 1px보다 작으면 Adobe Acrobat이 이 값으로 반올림합니다. 따라서 이 속성은 HTML 브라우저에서 이 동작을 에뮬레이트하는 데 사용할 수 있습니다. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | 이 속성은 텍스트 글리프가 단어와 문자열로 그룹화되지 않도록 하는 모드를 전환합니다. 이 모드는 페이지에서 글리프의 최대 정밀도를 유지할 수 있도록 하며, 음악 기호나 서로 별도로 배치해야 하는 글리프가 있는 문서 변환에 사용할 수 있습니다. 이 매개변수는 FixedLayout 속성의 값이 true일 때만 문서에 적용됩니다. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | RenderTextAsImage 속성이 true로 설정되면 소스의 텍스트가 HTML에서 이미지로 변환됩니다. 텍스트를 선택할 수 없게 하거나 HTML 텍스트가 제대로 렌더링되지 않을 때 유용할 수 있습니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식입니다. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | 전체 글꼴이 저장될 것임을 나타내며, True Type Fonts만 지원합니다. 기본적으로 SaveFullFont = false이며 변환기는 문서의 텍스트를 표시하는 데 필요한 초기 글꼴의 하위 집합을 저장합니다. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | 이 속성은 글리프와 단어를 문자열로 순차적으로 그룹화하는 것을 지정합니다. 예를 들어 태그와 단어가 변환된 HTML에서 다른 순서를 가지며 일치하도록 하려는 경우 이 매개변수는 FixedLayout 속성의 값이 true일 때만 문서에 적용됩니다. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | 다중 페이지 모드가 선택된 경우(즉, 'SplitIntoPages'가 'true'인 경우) 이 속성은 각 결과 HTML 페이지에 대해 별도의 CSS 파일을 생성해야 하는지 여부를 정의합니다. 기본적으로 이 속성은 false이므로 모든 생성된 페이지에 대해 하나의 큰 공통 CSS가 생성됩니다. 이 모드에서 생성된 모든 CSS의 요약 크기(페이지당 하나의 CSS)는 일반적으로 하나의 큰 CSS 파일의 크기보다 훨씬 큽니다. 왜냐하면 이전 경우 CSS 클래스가 여러 CSS 파일에 중복되기 때문입니다. 따라서 이 설정은 각 HTML 페이지를 독립적으로 처리하는 데 관심이 있는 경우에만 사용하는 것이 좋습니다. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | 소스 문서의 각 페이지가 자체 대상 HTML 문서로 변환될 것인지 여부를 나타내는 플래그를 가져오거나 설정합니다. 즉, 결과 HTML이 여러 HTML 페이지로 분할될지 여부입니다. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | HTML 페이지 제목을 가져오거나 설정합니다. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | 이미지 조각을 하나의 그림으로 결합하기 위한 플래그입니다. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | UseZOrder 속성이 true로 설정되면 그래픽과 텍스트가 원본 PDF 문서의 Z 순서에 따라 결과 HTML 문서에 추가됩니다. 이 속성이 false인 경우 모든 그래픽이 단일 레이어로 배치되어 겹치는 객체에 대해 불필요한 효과를 초래할 수 있습니다. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만 사용자가 Abort를 반환할 수도 있으며, 이 경우 저장 작업이 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | 이 매개변수는 PDF에서 HTML로 변환하는 동안 복합 배경 이미지에 필요한 안티앨리어싱 조치를 정의합니다. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | PDFtoHTML 변환기가 결과 CSS를 생성할 때 CSS 클래스 이름(예: ".stl_01 {}" ... ".stl_NN {}")이 생성되어 결과 CSS에서 사용됩니다. 이 속성은 클래스 이름 접두사를 강제로 설정할 수 있습니다. 예를 들어 모든 클래스 이름이 'my_prefix_'로 시작하도록 하려면(즉, 'my_prefix_1' ... 'my_prefix_NNN'과 같은) 변환 전에 이 속성에 'my_prefix_'를 할당하면 됩니다. 이 속성이 변경되지 않으면(즉, null이 값으로 남아 있으면) 변환기가 클래스 이름을 자체적으로 생성합니다(예: ".stl_01 {}" ... ".stl_NN {}"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | 이 필드는 PDF를 HTML로 변환하는 동안 생성된 HTML 문서 전체 또는 페이지에 대한 CSS 저장을 처리하는 데 사용해야 하는 저장 전략을 포함할 수 있습니다(있는 경우). CSS 파일을 특정 방식으로 처리하려면 관련 메서드를 생성하고 이 속성에 생성된 델리게이트를 할당하면 됩니다. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | 변환 결과는 하나 이상의 HTML 페이지를 포함할 수 있습니다. 이 속성에 변환 중에 생성된 HTML 페이지(정확히는 외부 링크된 파일이 없는 마크업 HTML)를 처리하는 사용자 정의 메서드에서 생성된 델리게이트를 할당할 수 있습니다. 이 경우 페이지의 HTML을 스트림이나 디스크에 저장하는 등의 처리는 사용자 정의 코드에서 수행할 수 있습니다. 이 경우 HTML 페이지 저장을 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기 코드에서 결과를 저장하는 것은 사용되지 않습니다. 특정 경우에 대해 변환기 코드 자체에서 처리해야 하는 경우 사용자 정의 코드에서 'htmlSavingInfo' 매개변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스 처리를 위한 모든 필요한 단계를 변환기 자체에서 수행해야 함을 신호합니다. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | 이 핸들러는 변환 진행 이벤트를 처리하는 데 사용할 수 있습니다. 예를 들어 진행률 표시줄이나 처리된 페이지 수에 대한 메시지를 표시하는 데 사용할 수 있습니다. 핸들러 코드의 예는 다음과 같습니다: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | 이 필드는 생성된 참조 리소스 파일(예: 이미지 및 글꼴)을 사용자 정의 처리하는 데 사용해야 하는 저장 전략을 포함할 수 있습니다(있는 경우). 이 전략은 리소스를 처리하고 생성된 HTML에서 저장된 리소스의 바람직한 URL을 나타내는 문자열을 반환해야 합니다. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | 이 필드는 생성된 결과 HTML에 삽입될 주제 CSS의 URL(또는 다중 페이지 생성이 활성화된 경우 URL 템플릿)을 반환하는 사용자 정의 메서드를 포함할 수 있습니다. 예를 들어 변환기가 생성된 CSS에 대해 표준 CSS 파일 이름 대신 특정 URL을 삽입하도록 하려면 바람직한 URL을 생성하는 메서드를 생성하고 이 속성에 넣으면 됩니다. 'SplitCssIntoPages' 플래그가 설정된 경우 이 사용자 정의 전략은 CSS의 정확한 URL이 아니라 페이지 번호로 자리 표시자를 대체한 후 변환기 내부에서 URL로 해결될 수 있는 템플릿 문자열을 반환해야 합니다. 이 경우 예상되는 반환 문자열의 예는 다음과 같습니다: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | HTML에 포함되지 않을 PDF 포함 글꼴 이름 목록입니다. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | 현재 문서에 대한 PDF 디코딩을 조정하기 위한 인코딩 특별 규칙을 정의합니다. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | PDF를 원하는 형식으로 저장하는 동안 사용할 글꼴 저장 모드를 정의합니다. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | 때때로 HTML 마크업 생성에 대한 특정 요구 사항이 있습니다. 이 매개변수는 PDF를 HTML로 변환하는 동안 이러한 특정 요구 사항을 충족하기 위해 사용할 수 있는 HTML 준비 모드를 정의합니다. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 여러 스레드에서 페이지를 처리합니다. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | 결과 HTML에서 단어의 글자 위치 지정 모드를 설정합니다. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | 이 속성은 소스 PDF 페이지를 나타내는 영역 주위에 결과 HTML 문서에서 경계(있는 경우)를 그리는 데 사용되는 설정 집합을 나타냅니다. 본질적으로 이는 페이지의 종이 가장자리를 표시하는 것과 관련이 있으며, PDF 페이지 자체에서 참조된 페이지 경계와는 다릅니다. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | 이 속성은 소스 PDF 페이지를 나타내는 영역 주위에 결과 HTML 문서에서 추가 페이지 여백(있는 경우)을 나타냅니다. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | 'SplitOnPages=false'인 경우 모든 입력 PDF 페이지를 나타내는 전체 HTML이 하나의 큰 결과 HTML 파일로 배치됩니다. 이 플래그는 결과 HTML이 생성되는 방식이 뷰어의 화면 해상도에 따라 PDF 페이지를 나타내는 영역의 흐름에 의존할지 여부를 정의합니다. 뷰어 측의 화면 너비가 충분히 넓어 2페이지 이상이 수평 방향으로 나란히 배치될 수 있다고 가정합니다. 이 플래그가 true로 설정되면 이 기회를 사용합니다(가능한 한 많은 페이지가 수평 방향으로 나란히 표시되고 다음 수평 페이지 그룹이 첫 번째 아래에 표시됨). 그렇지 않으면 페이지는 다음 페이지가 항상 이전 페이지 아래에 가도록 흐릅니다. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | 참조된 파일(HTML, 글꼴, 이미지, CSS)이 기본 HTML 파일에 포함될지 아니면 별도의 이진 엔티티로 생성될지를 정의합니다. |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | 변환된 PDF는 래스터 이미지를 포함할 수 있습니다. 이 매개변수는 PDF를 HTML로 변환하는 동안 이러한 이미지를 처리하는 방법을 정의합니다. |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | 생성된 HTML에서 콘텐츠가 없는 상단 및 하단의 빈 영역을 제거할지 여부를 정의합니다. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF는 다른 요소(예: 이미지)에 의해 그림자가 있는 텍스트를 포함할 수 있지만 Acrobat Reader에서 클립보드로 선택할 수 있습니다(일반적으로 문서에 이미지와 OCR된 텍스트가 포함된 경우 발생). 이 설정은 변환기에게 결과 HTML에서 이러한 텍스트를 투명 선택 가능한 텍스트로 저장해야 하는지 여부를 알려줍니다. 그렇지 않으면 이러한 텍스트는 일반적으로 숨겨진 상태로 저장되어 클립보드에 복사할 수 없습니다. |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF는 클립보드에 선택할 수 있는 투명 텍스트를 포함할 수 있습니다(일반적으로 문서에 이미지와 OCR된 텍스트가 포함된 경우 발생). 이 설정은 변환기에게 이러한 텍스트를 결과 HTML에서 투명 선택 가능한 텍스트로 저장해야 하는지 여부를 알려줍니다. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | 문서를 HTML로 저장하는 동안 발견된 모든 이미지를 저장해야 하는 디렉토리의 경로를 가져오거나 설정합니다. 매개변수가 비어 있거나 null인 경우 이미지 파일(있는 경우)은 HTML에 연결된 다른 파일과 함께 저장됩니다. CustomImageSavingStrategy 속성이 성공적으로 사용된 경우 관련 이미지 파일을 처리하는 데 영향을 미치지 않습니다. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | 문서를 HTML로 저장하는 동안 발견된 SVG 이미지만 저장해야 하는 디렉토리의 경로를 가져오거나 설정합니다. 매개변수가 비어 있거나 null인 경우 SVG 파일(있는 경우)은 다른 이미지 파일(출력 파일 근처) 또는 이미지에 대한 특별 폴더(특별 이미지 폴더가 지정된 경우)에 저장됩니다. CustomImageSavingStrategy 속성이 성공적으로 사용된 경우 관련 이미지 파일을 처리하는 데 영향을 미치지 않습니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF에는 여러 개의 동일한 타일 배경 이미지로 구성된 배경 이미지(페이지 또는 테이블 셀)가 포함됩니다. 이 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지 부분 사이에 가시적인 경계를 생성합니다. 이는 이미지 가장자리 부드럽게 처리하는 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 문서에 동일한 배경 이미지 부분 사이에 가시적인 경계가 포함된 것처럼 보이면 이 설정을 사용하여 원하지 않는 효과를 제거하십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 저하시킵니다. 따라서 이 옵션은 정말 필요한 경우에만 사용하십시오. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF 자체에는 텍스트에 대한 밑줄 표시기가 포함되어 있지 않습니다. 이는 텍스트 아래에 위치한 선으로 에뮬레이트됩니다. 이 옵션은 변환기가 이 선이 텍스트의 밑줄임을 추측하고 이를 그래픽적으로 밑줄을 그리는 대신 CSS에 정보를 넣도록 허용합니다. |

## 예제

다음 예제는 PDF 파일을 HTML 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### 참조

* 클래스 [UnifiedSaveOptions](../unifiedsaveoptions/)
* 인터페이스 [IPageSetOptions](../ipagesetoptions/)
* 인터페이스 [IPipelineOptions](../ipipelineoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)