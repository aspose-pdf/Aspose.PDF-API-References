---
title: "DocSaveOptions.RelativeHorizontalProximity"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "DocSaveOptions 속성. Pdf에서는 단어가 문자나 음절을 개별적으로 출력하는 연산자를 사용해 내부적으로 표현될 수 있습니다. 따라서 단어를 감지하려면 실제 단어인 독립 문자 그룹을 찾아야 합니다. 이 설정은 원본 PDF에서 단어를 인식할 때 단어 사이 거리로 간주되어야 하는 텍스트 요소(문자·음절) 사이의 공백 너비를 정의합니다. 문자 사이에 최소 이 너비만큼의 빈 공간이 있으면 해당 텍스트 요소는 서로 다른 단어에 속한다고 판단합니다. 이는 글꼴 크기 1.0에 정규화되어 있으며, 이는 단어 글꼴 크기의 100%를 의미합니다. ATTENTION 이 값은 특정 드물게 사용되는 글꼴이 포함된 PDF에서만 사용되며, 해당 글꼴에 대해 최적값을 글꼴에서 계산할 수 없을 때 적용됩니다. 따라서 대부분의 경우 이 매개변수는 결과 문서에 아무 영향을 주지 않습니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity property

PDF에서는 단어가 각 글자나 음절을 독립적으로 출력하는 연산자를 사용해 내부적으로 표현될 수 있습니다. 따라서 단어를 감지하려면 실제로는 단어인 독립 문자 그룹을 찾아야 할 때가 있습니다. 이 설정은 원본 PDF에서 단어를 인식할 때 텍스트 요소(글자, 음절) 사이의 간격을 단어 간 거리로 간주해야 하는 공백 너비를 정의합니다. (글자 사이에 최소 이 너비만큼의 빈 공간이 있으면 해당 텍스트 요소가 다른 단어에 속한다는 의미입니다). 이 값은 글꼴 크기에 정규화되며, 1.0은 해당 단어 글꼴 크기의 100%를 의미합니다. 주의! 이 옵션은 최적값을 글꼴에서 계산할 수 없는 특정 희귀 글꼴이 포함된 경우에만 사용됩니다. 따라서 대부분의 경우 이 매개변수는 결과 문서에 영향을 주지 않습니다.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### 또 보기

* class [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


