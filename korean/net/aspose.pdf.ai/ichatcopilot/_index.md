---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IChatCopilot 인터페이스. AI 모델을 통해 문서와 상호작용하기 위한 채팅 코파일럿을 나타냅니다.
type: docs
weight: 470
url: /ko/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot 인터페이스

AI 모델을 통해 문서와 상호작용하기 위한 채팅 코파일럿을 나타냅니다.

```csharp
public interface IChatCopilot : IAICopilot
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | 비동기적으로 컨텍스트를 삭제합니다. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | 주어진 메시지 목록에 대한 응답을 비동기적으로 가져옵니다. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | 주어진 메시지에 대한 응답을 비동기적으로 가져옵니다. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | 비동기적으로 컨텍스트를 JSON 파일에 저장합니다. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | 주어진 메시지 목록에 대한 응답을 PDF 파일에 비동기적으로 저장합니다. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | 주어진 메시지에 대한 응답을 PDF 파일에 비동기적으로 저장합니다. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | 주어진 메시지 목록에 대한 응답을 지정된 형식의 파일에 비동기적으로 저장합니다. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | 주어진 메시지에 대한 응답을 지정된 형식의 파일에 비동기적으로 저장합니다. |

### 참조

* 인터페이스 [IAICopilot](../iaicopilot/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)