---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Structure.Element 클래스. 논리 구조의 기본 요소를 나타내는 클래스
type: docs
weight: 10140
url: /ko/net/aspose.pdf.structure/element/
---
## 요소 클래스

논리 구조의 기본 요소를 나타내는 클래스.

```csharp
public abstract class Element
```

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (선택 사항; PDF 1.4) 구조 요소 및 그 자식에 대한 정확한 대체 텍스트. 이 대체 텍스트(가능한 한 작은 콘텐츠 조각에 적용되어야 함)는 장애인을 위한 접근성을 지원하거나 기타 목적을 위해 문서의 내용을 추출할 때 유용합니다. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (선택 사항) 구조 요소 및 그 자식에 대한 인간이 읽을 수 있는 형태의 대체 설명으로, 장애인을 위한 접근성을 지원하거나 기타 목적을 위해 문서의 내용을 추출할 때 유용합니다. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | 자식 요소 컬렉션을 가져옵니다. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (선택 사항; PDF 1.5) 약어의 확장된 형태. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (선택 사항; PDF 1.4) 중첩된 구조 요소 또는 표시된 콘텐츠에 대한 언어 사양에 의해 재정의되지 않는 구조 요소의 모든 텍스트에 대한 자연 언어를 지정하는 언어. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | 요소를 제거합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* 어셈블리 [Aspose.PDF](../../)