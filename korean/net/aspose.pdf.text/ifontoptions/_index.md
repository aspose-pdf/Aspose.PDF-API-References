---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.IFontOptions 인터페이스. 글꼴 동작을 조정하는 데 유용한 속성
type: docs
weight: 10610
url: /ko/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions 인터페이스

글꼴 동작을 조정하는 데 유용한 속성

```csharp
public interface IFontOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | 때때로 원하는 글꼴을 문서에 포함시키는 것이 불가능할 수 있습니다. 그 이유는 라이센스 제한이나 원하는 글꼴이 대상 컴퓨터에서 발견되지 않는 경우 등 여러 가지가 있습니다. 이러한 상황이 발생하면 감지하기가 쉽지 않습니다. 원하는 글꼴은 속성 플래그 Font.IsEmbedded = true;를 통해 포함됩니다. 물론 설정된 직후에 이 속성을 읽는 것은 가능하지만 편리한 방법은 아닙니다. 플래그 NotifyAboutFontEmbeddingError는 글꼴 포함 시도가 실패했을 때 예외 메커니즘을 강제합니다. 이 플래그가 설정되면 [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) 유형의 예외가 발생합니다. 기본값은 false입니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)