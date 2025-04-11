---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptionsRecognitionMode 열거형. PDF 문서가 워드 프로세싱 문서로 변환되는 방식을 제어할 수 있습니다.
type: docs
weight: 3770
url: /ko/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode 열거형

PDF 문서가 워드 프로세싱 문서로 변환되는 방식을 제어할 수 있습니다.

```csharp
public enum RecognitionMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Textbox | `0` | 이 모드는 빠르고 PDF 파일의 원래 모양을 최대한 보존하는 데 좋지만, 결과 문서의 편집 가능성이 제한될 수 있습니다. |
| Flow | `1` | 전체 인식 모드로, 엔진은 그룹화 및 다단계 분석을 수행하여 원래 문서 작성자의 의도를 복원하고 최대한 편집 가능한 문서를 생성합니다. 단점은 출력 문서가 원래 PDF 파일과 다르게 보일 수 있다는 것입니다. |
| EnhancedFlow | `2` | 테이블 인식을 지원하는 대체 Flow 모드입니다. |

## 비고

결과 문서가 더 이상 많이 편집되지 않을 경우 Textbox 모드를 사용하십시오. 수정할 것이 많지 않을 때 텍스트 박스는 수정하기 쉽습니다.

출력 문서가 추가 편집이 필요할 경우 Flow 모드를 사용하십시오. Flow 모드의 단락 및 텍스트 라인은 텍스트 수정이 용이하지만, 지원되지 않는 형식 객체는 Textbox 모드보다 더 나쁘게 보일 수 있습니다.

### 참조

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)