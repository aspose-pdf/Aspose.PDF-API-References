---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MarkdownSaveOptions 클래스. 마크다운 형식으로 문서를 저장하는 옵션 클래스를 나타냅니다.
type: docs
weight: 6910
url: /ko/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions 클래스

마크다운 형식으로 문서를 저장하는 옵션 클래스를 나타냅니다.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | 마크다운으로 콘텐츠를 추출할 사각형 영역을 가져오거나 설정합니다. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps 페이지를 준비하는 동안 글꼴 글리프를 캐시할지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 소비를 증가시킵니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | 생성된 문서의 강조 스타일을 가져오거나 설정합니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 서브레이어가 있는 PDF 문서에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | 벡터 그래픽을 추출해야 하는지 여부를 나타내는 속성을 가져오거나 설정합니다. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | 글꼴 크기 인식 헤더 전략에서 사용할 예상 헤딩 수준을 정의합니다. 이 속성 값이 설정되면 문서에 북마크가 포함되어 있더라도 헤더 인식 !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic 전략이 선택됩니다. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | 헤딩 인식 전략을 가져오거나 설정합니다. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | 생성된 문서의 헤딩 스타일을 가져오거나 설정합니다. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | 생성된 문서의 줄 바꿈 스타일을 가져오거나 설정합니다. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | 이미지와 같은 문서 리소스를 저장할 디렉터리 이름을 가져오거나 설정합니다. 값이 지정되지 않으면 이미지는 마크다운 파일과 동일한 디렉터리에 기록됩니다. 이것은 경로가 아니라 이름일 뿐입니다! 이 디렉터리는 저장된 마크다운 파일이 있는 디렉터리에 자동으로 생성됩니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식입니다. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | 아래 첨자 및 위 첨자로 변환할 수 있는 허용 여부를 가져오거나 설정합니다. 이 값은 기본적으로 true입니다. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | 텍스트의 왼쪽과 오른쪽에 이미지를 삽입하기 위해 img 태그 사용을 허용하는지 여부를 가져오거나 설정합니다. 이 경우 마크다운 뷰어에서 텍스트가 이미지 주위로 감쌉니다. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만 사용자가 Abort를 반환할 수도 있으며, 이 경우 저장 작업이 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 여러 스레드에서 페이지를 처리합니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF에는 여러 개의 동일한 타일 배경 이미지로 구성된 배경 이미지(페이지 또는 테이블 셀)가 포함됩니다. 이 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지의 부분 사이에 가시적인 경계를 생성합니다. 이는 이미지 가장자리 부드럽게 처리하는 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 문서에 동일한 배경 이미지의 부분 사이에 가시적인 경계가 포함된 것처럼 보이면 이 설정을 사용하여 원하지 않는 효과를 제거해 보십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 저하시킵니다. 따라서 정말 필요한 경우에만 이 옵션을 사용하십시오. |

### 참조

* 클래스 [UnifiedSaveOptions](../unifiedsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)