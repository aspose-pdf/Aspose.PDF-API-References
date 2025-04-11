---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: IFontOptions 속성. 때때로 원하는 글꼴을 문서에 포함하는 것이 불가능합니다. 그 이유는 라이센스 제한이나 원하는 글꼴이 대상 컴퓨터에서 발견되지 않는 경우 등 여러 가지가 있습니다. 이러한 상황이 발생하면 원하는 글꼴이 속성 플래그 Font.IsEmbedded = true를 통해 포함되기 때문에 이를 감지하는 것이 간단하지 않습니다. 물론 이 속성을 설정한 직후에 읽는 것은 가능하지만 편리한 방법은 아닙니다. 플래그 NotifyAboutFontEmbeddingError는 글꼴 포함 시도가 실패했을 때 예외 메커니즘을 강제합니다. 이 플래그가 설정되면 [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 유형의 예외가 발생합니다. 기본값은 false입니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError 속성

때때로 원하는 글꼴을 문서에 포함하는 것이 불가능합니다. 그 이유는 라이센스 제한이나 원하는 글꼴이 대상 컴퓨터에서 발견되지 않는 경우 등 여러 가지가 있습니다. 이러한 상황이 발생하면 원하는 글꼴이 속성 플래그 Font.IsEmbedded = true를 통해 포함되기 때문에 이를 감지하는 것이 간단하지 않습니다. 물론 이 속성을 설정한 직후에 읽는 것은 가능하지만 편리한 방법은 아닙니다. 플래그 NotifyAboutFontEmbeddingError는 글꼴 포함 시도가 실패했을 때 예외 메커니즘을 강제합니다. 이 플래그가 설정되면 [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 유형의 예외가 발생합니다. 기본값은 false입니다.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### 참조

* 인터페이스 [IFontOptions](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)