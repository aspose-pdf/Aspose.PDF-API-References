---
title: "XImage.TrySetAlternativeText"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "XImage method. 페이지의 XImage에 대한 대체 텍스트를 설정합니다."
type: docs
weight: 180
url: /ko/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

페이지의 XImage에 대한 대체 텍스트를 설정합니다.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| alternativeText | String | 지정할 대체 텍스트. |
| 페이지 | 페이지 | XImage가 위치한 페이지. |

### 반환 값

XImage에 대한 alternativeText가 설정된 경우 true, 설정되지 않은 경우 false.

## 비고

다음 경우에 메서드는 false를 반환합니다: - 지정된 페이지에서 XImage를 찾을 수 없습니다. - 페이지에 XImage가 여러 번 나타나고 서로 다른 구조 요소와 함께 있어, 어느 인스턴스에 대체 텍스트를 적용해야 할지 모호합니다.

### 또 보기

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


