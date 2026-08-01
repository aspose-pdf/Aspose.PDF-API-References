---
title: "클래스 MarkdownSaveOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.MarkdownSaveOptions 클래스. 마크다운 형식의 문서 저장 옵션 클래스를 나타냅니다."
type: docs
weight: 7050
url: /ko/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

마크다운 형식의 문서 저장 옵션 클래스를 나타냅니다.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | 마크다운으로 콘텐츠를 추출할 사각형 영역을 가져오거나 설정합니다. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps 페이지를 준비하는 동안 글꼴 글리프가 캐시될지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 사용량이 증가합니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | 생성된 문서의 강조 스타일을 가져오거나 설정합니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 하위 레이어를 사용하여 PDF Document에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | 벡터 그래픽을 추출할지 여부를 나타내는 속성을 가져오고 설정합니다. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | FontSize 인식 헤더 전략에 사용할 예상 헤딩 레벨을 정의합니다. 이 속성 값이 설정되면, 문서에 북마크가 포함되어 있더라도 !:PdfToMarkdown.HeadingRecognitionStrategy.Auto 전략이 설정될 때 헤더 인식 휴리스틱 전략이 선택됩니다. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | 헤딩 인식 전략을 가져오거나 설정합니다. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | 생성된 문서의 헤딩 스타일을 가져오거나 설정합니다. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | 생성된 문서의 줄 바꿈 스타일을 가져오거나 설정합니다. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | 이미지와 같은 문서 리소스를 저장할 디렉터리 이름을 가져오고 설정합니다. 값이 지정되지 않으면 이미지가 마크다운 파일 자체와 동일한 디렉터리에 기록됩니다. 이는 경로가 아니라 이름만입니다! 이 디렉터리는 저장된 마크다운 파일이 있는 디렉터리 안에 자동으로 생성됩니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | 아래첨자와 위첨자를 변환하도록 허용 여부를 가져오고 설정합니다. 이 값은 기본적으로 true입니다. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | 텍스트의 왼쪽 및 오른쪽에 이미지를 삽입하기 위해 img 태그 사용을 허용하는지를 가져오고 설정합니다. 이 경우 마크다운 뷰어에서 텍스트가 이미지 주위로 흐르게 됩니다. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 몇 개의 스레드에서 페이지를 처리합니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF는 페이지 또는 표 셀의 배경 이미지가 여러 개의 동일한 타일 배경 이미지를 서로 가깝게 배치하여 구성됩니다. 이러한 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 배경 이미지 부분 사이에 눈에 보이는 경계선을 생성할 수 있으며, 이는 이미지 가장자리 부드럽게 처리(안티앨리어싱) 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 Document에 동일한 배경 이미지 부분 사이에 이러한 눈에 보이는 경계가 나타나는 경우, 원하지 않는 효과를 없애기 위해 이 설정을 사용해 보십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 늦추므로, 정말 필요할 때만 이 옵션을 사용하십시오. |

### 또 보기

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


