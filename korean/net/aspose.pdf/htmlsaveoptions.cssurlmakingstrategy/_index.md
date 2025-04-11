---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 생성된 HTML 문서에서 참조된 CSS의 URL 생성을 구현하는 custom method로 생성된 delegate를 이 속성에 할당할 수 있습니다. 예를 들어, HTML에서 참조된 CSS를 otherPage.ASPXCssIDzjjkklj와 같이 만들고자 하는 경우, 해당 custom strategy는 otherPage.ASPXCssIDzjjkklj를 반환해야 합니다.
type: docs
weight: 5600
url: /ko/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy 대리자

생성된 HTML 문서에서 참조된 CSS의 URL 생성을 구현하는 custom method로 생성된 delegate를 이 속성에 할당할 수 있습니다. 예를 들어, HTML에서 참조된 CSS를 "otherPage.ASPX?CssID=zjjkklj"와 같이 만들고자 하는 경우, 해당 custom strategy는 "otherPage.ASPX?CssID=zjjkklj"를 반환해야 합니다.

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| 매개변수            | 유형                | 설명                                                              |
| ------------------- | ------------------- | ----------------------------------------------------------------- |
| cssUrlRequestInfo   | CssUrlRequestInfo   | CSS의 URL 생성을 위해 사용될 수 있는 데이터 집합을 나타냅니다.         |

### 반환 값

CSS의 URL 또는 URL 템플릿을 나타내는 문자열을 반환해야 합니다.

### 참조

* 클래스 [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)