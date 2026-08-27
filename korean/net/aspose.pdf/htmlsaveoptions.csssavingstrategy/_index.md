---
title: "델리게이트 HtmlSaveOptions.CssSavingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "이 속성에 PDF를 HTML로 변환하는 동안 생성된 하나의 CSS 파트의 처리 및/또는 저장을 구현하는 사용자 지정 전략을 할당할 수 있습니다. 이러한 경우 스트림이나 디스크에 저장과 같은 처리는 해당 사용자 지정 코드에서 수행되어야 합니다."
type: docs
weight: 5720
url: /ko/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

이 속성에 PDF를 HTML로 변환하는 동안 생성된 하나의 CSS 파트의 처리 및/또는 저장을 구현하는 사용자 지정 전략을 할당할 수 있습니다. 이러한 경우 스트림이나 디스크에 저장과 같은 처리(예: 저장)는 해당 사용자 지정 코드에서 수행되어야 합니다.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | 제공된 CSS 파트를 저장하는 데 사용할 수 있는 데이터 집합을 나타냅니다. |

### 또 보기

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


