---
title: "열거형 DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.DocSaveOptionsRecognitionMode 열거형. PDF 문서가 워드 프로세싱 문서로 변환되는 방식을 제어할 수 있습니다."
type: docs
weight: 3890
url: /ko/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

PDF 문서가 워드 프로세싱 문서로 변환되는 방식을 제어할 수 있습니다.

```csharp
public enum RecognitionMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Textbox | `0` | 이 모드는 빠르고 PDF 파일의 원본 모양을 최대한 보존하는 데 적합하지만, 결과 문서의 편집 가능성이 제한될 수 있습니다. |
| Flow | `1` | 전체 인식 모드에서는 엔진이 그룹화와 다중 레벨 분석을 수행하여 원본 문서 작성자의 의도를 복원하고 최대한 편집 가능한 문서를 생성합니다. 단점은 출력 문서가 원본 PDF 파일과 다르게 보일 수 있다는 점입니다. |
| EnhancedFlow | `2` | 표 인식을 지원하는 대체 Flow 모드입니다. |

## 비고

결과 문서가 크게 편집되지 않을 경우 Textbox 모드를 사용하십시오. Textbox는 할 일이 많지 않을 때 쉽게 수정할 수 있습니다.

출력 문서가 추가 편집이 필요할 경우 Flow 모드를 사용하십시오. Flow 모드의 단락과 텍스트 라인은 텍스트를 쉽게 수정할 수 있게 하지만, 지원되지 않는 서식 개체는 Textbox 모드보다 더 나빠 보일 수 있습니다.

### 또 보기

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


