---
title: "IFontOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "글꼴 동작을 조정하기 위한 유용한 속성들"
type: docs
weight: 180
url: /ko/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

글꼴 동작을 조정하기 위한 유용한 속성들

IFontOptions 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| notify_about_font_embedding_error | 때때로 원하는 글꼴을 문서에 포함시키는 것이 불가능할 수 있습니다. 여러 이유가 있는데, 예를 들어<br/>            라이선스 제한이나 대상 컴퓨터에서 원하는 글꼴을 찾을 수 없는 경우가 있습니다.<br/>            이러한 상황이 발생하면 감지하기가 쉽지 않은데, 원하는 글꼴이 Font.IsEmbedded = true 속성 플래그를 설정하여 포함되기 때문입니다. 물론 이 속성을 설정 직후에 읽을 수는 있지만<br/>            편리한 방법은 아닙니다. Flag NotifyAboutFontEmbeddingError 플래그는 글꼴 포함 시도가 실패했을 때 예외 메커니즘을 강제합니다.<br/>            이 플래그가 설정되면 유형이 <br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/)인 예외가 발생합니다. 기본값은 false. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

