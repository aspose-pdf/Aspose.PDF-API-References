---
title: DocSaveOptions.RelativeHorizontalProximity
second_title: Aspose.PDF for .NET API Reference
description: DocSaveOptions 속성. Pdf에서 단어는 독립적으로 글자나 음절을 인쇄하여 단어를 인쇄하는 연산자로 내부적으로 표현될 수 있습니다. 따라서 단어를 감지하기 위해 때때로 실제로 단어인 독립 문자 그룹을 감지해야 합니다. 이 설정은 소스 PDF에서 단어 인식 중 단어 사이의 거리로 처리해야 하는 텍스트 요소（글자, 음절） 사이의 공간 너비를 정의합니다. （글자 사이에 이 너비 이상의 빈 공간이 존재하면 텍스트 요소가 서로 다른 단어에 속함을 의미합니다）. 이는 글꼴 크기에 대해 정규화되어 있으며, 1.0은 가정된 단어의 글꼴 크기의 100%를 의미합니다. 주의! 이는 소스 PDF에 최적 값을 글꼴에서 계산할 수 없는 특정 드물게 사용되는 글꼴이 포함된 경우에만 사용됩니다. 따라서 대다수의 경우 이 매개변수는 결과 문서에 아무런 변화를 주지 않습니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity 속성

Pdf에서 단어는 독립적으로 글자나 음절을 인쇄하여 단어를 인쇄하는 연산자로 내부적으로 표현될 수 있습니다. 따라서 단어를 감지하기 위해 때때로 실제로 단어인 독립 문자 그룹을 감지해야 합니다. 이 설정은 소스 PDF에서 단어 인식 중 단어 사이의 거리로 처리해야 하는 텍스트 요소(글자, 음절) 사이의 공간 너비를 정의합니다. (글자 사이에 이 너비 이상의 빈 공간이 존재하면 텍스트 요소가 서로 다른 단어에 속함을 의미합니다). 이는 글꼴 크기에 대해 정규화되어 있으며, 1.0은 가정된 단어의 글꼴 크기의 100%를 의미합니다. 주의! 이는 소스 PDF에 최적 값을 글꼴에서 계산할 수 없는 특정 드물게 사용되는 글꼴이 포함된 경우에만 사용됩니다. 따라서 대다수의 경우 이 매개변수는 결과 문서에 아무런 변화를 주지 않습니다.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### 참조

* 클래스 [DocSaveOptions](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)