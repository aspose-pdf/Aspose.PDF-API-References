---
title: "대리자 HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "이 속성에는 생성된 HTML 문서에 참조된 CSS의 URL 생성을 구현하는 사용자 정의 메서드에서 만든 대리자를 할당할 수 있습니다. 예를 들어 HTML에 참조되는 CSS를 otherPage.ASPXCssIDzjjkklj 로 만들고 싶다면, 해당 사용자 정의 전략은 otherPage.ASPXCssIDzjjkklj 를 반환해야 합니다."
type: docs
weight: 5730
url: /ko/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

이 속성에는 생성된 HTML 문서에 참조된 CSS의 URL 생성을 구현하는 사용자 정의 메서드에서 만든 대리자를 할당할 수 있습니다. 예를 들어 HTML에 참조되는 CSS를 \"otherPage.ASPX?CssID=zjjkklj\" 로 만들고 싶다면, 해당 사용자 정의 전략은 \"otherPage.ASPX?CssID=zjjkklj\" 를 반환해야 합니다.

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | CSS URL 생성을 위해 사용할 수 있는 데이터 집합을 나타냅니다. |

### 반환 값

CSS URL 또는 URL 템플릿을 나타내는 문자열을 반환해야 합니다.

### 또 보기

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


