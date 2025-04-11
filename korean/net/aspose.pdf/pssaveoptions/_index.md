---
title: Class PsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsSaveOptions 클래스. PS PostScript 또는 EPS 형식으로 내보내기 위한 저장 옵션
type: docs
weight: 9740
url: /ko/net/aspose.pdf/pssaveoptions/
---
## PsSaveOptions 클래스

PS (PostScript) 또는 EPS 형식으로 내보내기 위한 저장 옵션.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | 생성자. |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps 페이지를 준비하는 동안 글꼴 글리프를 캐시할지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 소비를 증가시킵니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | 결과 PS 문서에 글꼴을 포함해야 하는지 여부를 나타내는 플래그를 가져오거나 설정합니다. |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | 결과 PS 문서에 글꼴이 포함되어야 하는 유형을 가져오거나 설정합니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 하위 레이어가 있는 PDF 문서에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하는 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만 사용자가 Abort를 반환할 수도 있으며, 이 경우 저장 작업이 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 여러 스레드에서 페이지를 처리합니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF에는 여러 개의 동일한 타일 배경 이미지로 구성된 배경 이미지(페이지 또는 테이블 셀)가 포함됩니다. 이 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지의 부분 사이에 눈에 띄는 경계를 생성하는데, 이는 이미지 가장자리 부드럽게 처리하는 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 문서에 동일한 배경 이미지의 부분 사이에 눈에 띄는 경계가 포함된 것처럼 보이면 이 설정을 사용하여 원하지 않는 효과를 제거해 보십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 저하시킵니다. 따라서 정말 필요한 경우에만 이 옵션을 사용하십시오. |

### 참조

* 클래스 [UnifiedSaveOptions](../unifiedsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)