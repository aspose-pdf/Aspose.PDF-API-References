---
title: "열거형 EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.EpubSaveOptionsRecognitionMode 열거형. 일반적으로 고정 레이아웃을 가진 PDF 파일을 변환할 때 변환 엔진은 그룹화와 다중 레벨 분석을 수행하여 원본 문서 작성자의 의도를 복원하고 흐름 레이아웃으로 결과를 생성하려고 시도합니다. 이 속성은 콘텐츠 인식의 원하는 방법에 따라 해당 변환을 조정합니다."
type: docs
weight: 4190
url: /ko/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

PDF 파일(보통 고정 레이아웃을 가짐)이 변환될 때, 변환 엔진은 그룹화 및 다중 레벨 분석을 수행하여 원본 문서 작성자의 의도를 복원하고 흐름 레이아웃으로 결과를 생성하려고 시도합니다. 이 속성은 콘텐츠 인식의 원하는 방법에 따라 해당 변환을 조정합니다.

```csharp
public enum RecognitionMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Flow | `0` | 전체 인식 모드에서는 엔진이 그룹화와 다중 레벨 분석을 수행하여 원본 문서 작성자의 의도를 복원하고 흐름 레이아웃으로 XHTML을 생성합니다. |
| PdfFlow | `1` | 이 변환의 주요 아이디어는 PDF 문서 처리 중에 형성되는 콘텐츠 렌더링의 "자연스러운" 순서를 유지하는 데 기반합니다. 일반적으로 PDF 문서는 위에서 아래로, 왼쪽에서 오른쪽으로 렌더링 순서를 유지합니다 (첨부 파일 directions.png 참조). 이 가정은 위치(고정 레이아웃)를 가진 Aps 요소를 HTML, EPUB, DOC와 같은 흐름 형식으로 변환하는 단일 경로 알고리즘을 만들 수 있게 합니다. 이 모드는 PDF(APS)에서 EPUB로 변환할 때 특히 유용합니다, 왜냐하면 EPUB 형식은 Kindle이나 스마트폰과 같은 전자책 리더를 위해 개발되었기 때문입니다. 이러한 장치의 화면 크기는 일반 PC 화면보다 작습니다. 따라서 EPUB 문서의 콘텐츠를 흐름 형식으로 저장하는 것이 다양한 크기의 화면에서 올바르게 렌더링하는 데 더 좋습니다. 이 모드에서는 각 열이 이전 열의 끝에 추가되어 EPUB 리더에서 "페이지 매김" 중에 변환된 문서의 논리 구조를 유지할 수 있습니다. 이 기능을 통해 과학 논문이나 잡지 기사 등을 올바르게 렌더링할 수 있습니다. |
| Fixed | `2` | 이 모드는 빠르고 원본 페이지의 모습을 최대한 보존하는 데 좋지만, 안타깝게도 많은 EPUB 리더가 고정 레이아웃을 가진 XHTML을 지원하지 않습니다. |

### 또 보기

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


