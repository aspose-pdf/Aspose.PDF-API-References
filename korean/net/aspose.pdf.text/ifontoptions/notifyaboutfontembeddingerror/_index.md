---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IFontOptions 속성. 원하는 글꼴을 문서에 포함시킬 수 없는 경우가 있습니다. 라이선스 제한이나 대상 컴퓨터에 원하는 글꼴이 없을 때와 같이 여러 이유가 있습니다. 이러한 상황이 발생하면 원하는 글꼴이 Font.IsEmbedded 플래그가 true 로 설정된 상태로 포함되기 때문에 단순히 감지하기 어렵습니다. 물론 이 플래그가 설정된 직후에 해당 속성을 읽을 수는 하지만 편리한 방법은 아닙니다. NotifyAboutFontEmbeddingError 플래그는 글꼴 포함 시도가 실패했을 때 예외 메커니즘을 강제합니다. 이 플래그가 설정되면 FontEmbeddingException 유형의 예외가 발생합니다. 기본값은 false입니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

원하는 글꼴을 문서에 포함시킬 수 없는 경우가 있습니다. 라이선스 제한이나 대상 컴퓨터에 원하는 글꼴이 없을 때와 같이 여러 이유가 있습니다. 이러한 상황이 발생하면 Font.IsEmbedded = true 플래그가 설정된 상태로 글꼴이 포함되기 때문에 단순히 감지하기 어렵습니다. 물론 이 플래그가 설정된 직후에 해당 속성을 읽을 수는 하지만 편리한 방법은 아닙니다. NotifyAboutFontEmbeddingError 플래그는 글꼴 포함 시도가 실패했을 때 예외 메커니즘을 강제합니다. 이 플래그가 설정되면 [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 유형의 예외가 발생합니다. 기본값은 false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### 또 보기

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


