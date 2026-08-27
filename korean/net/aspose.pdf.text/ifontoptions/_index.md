---
title: "인터페이스 IFontOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.IFontOptions 인터페이스. 글꼴 동작을 조정하기 위한 유용한 속성들"
type: docs
weight: 10790
url: /ko/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

폰트 동작을 조정하기 위한 유용한 속성들

```csharp
public interface IFontOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | 때때로 원하는 글꼴을 문서에 포함시키는 것이 불가능할 수 있습니다. 라이선스 제한이나 대상 컴퓨터에 원하는 글꼴이 없을 경우 등 여러 이유가 있습니다. 이러한 상황이 발생하면 감지하기가 쉽지 않은데, 원하는 글꼴은 `Font.IsEmbedded = true` 속성 플래그를 통해 포함되기 때문입니다. 물론 이 속성이 설정된 직후에 읽을 수는 있지만 편리한 방법은 아닙니다. `NotifyAboutFontEmbeddingError` 플래그는 글꼴 포함 시도가 실패했을 때 예외 메커니즘을 강제합니다. 이 플래그가 설정되면 [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) 유형의 예외가 발생합니다. 기본값은 false입니다. |

### 또 보기

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


