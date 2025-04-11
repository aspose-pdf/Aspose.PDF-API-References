---
title: Class ComHelper
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ComHelper 클래스. COM 클라이언트가 Aspose.Pdf에 문서를 로드할 수 있는 메서드를 제공합니다.
type: docs
weight: 3130
url: /ko/net/aspose.pdf/comhelper/
---
## ComHelper 클래스

COM 클라이언트가 Aspose.Pdf에 문서를 로드할 수 있는 메서드를 제공합니다.

```csharp
public class ComHelper
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ComHelper](comhelper/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | *filename*을 사용하여 문서를 생성하고 반환합니다. [`Document`](../document/document/)와 동일합니다. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | 필요한 변환 옵션을 제공하여 파일에서 기존 문서를 엽니다. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | 암호화된 문서 작업을 위한 [`Document`](../document/) 클래스의 새 인스턴스를 초기화하고 반환합니다. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | 암호화된 문서 작업을 위한 [`Document`](../document/) 클래스의 새 인스턴스를 초기화합니다. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | *input* 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | *input* 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | 필요한 변환을 제공하여 스트림에서 기존 문서를 열고 반환합니다. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | *input* 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | *input* 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다. |

## 비고

ComHelper 클래스를 사용하여 파일 또는 스트림에서 Document 객체로 문서를 로드합니다. Document 클래스는 새 문서를 생성하기 위한 기본 생성자를 제공하며, 파일 또는 스트림에서 문서를 로드하기 위한 오버로드된 생성자도 제공합니다. .NET 애플리케이션에서 Aspose.Words를 사용하는 경우 모든 Document 생성자를 직접 사용할 수 있지만, COM 애플리케이션에서 Aspose.Pdf를 사용하는 경우 기본 Document 생성자만 사용할 수 있습니다.

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)