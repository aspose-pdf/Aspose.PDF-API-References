---
title: "클래스 PdfXmlSaveOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.PdfXmlSaveOptions 클래스. PdfXml 형식에 대한 저장 옵션"
type: docs
weight: 8600
url: /ko/net/aspose.pdf/pdfxmlsaveoptions/
---
## PdfXmlSaveOptions class

PdfXml 형식에 대한 저장 옵션입니다.

```csharp
public class PdfXmlSaveOptions : UnifiedSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfXmlSaveOptions](pdfxmlsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps 페이지를 준비하는 동안 글꼴 글리프가 캐시될지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 사용량이 증가합니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 하위 레이어를 사용하여 PDF Document에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식. |
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


