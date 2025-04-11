---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.TruncationStrategy 클래스. 실행 전에 스레드가 어떻게 잘릴지를 제어하는 잘림 전략을 나타냅니다.
type: docs
weight: 1240
url: /ko/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy 클래스

실행 전에 스레드가 어떻게 잘릴지를 제어하는 잘림 전략을 나타냅니다.

```csharp
public class TruncationStrategy
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | 실행을 위한 컨텍스트를 구성할 때 스레드에서 가장 최근의 메시지 수를 가져오거나 설정합니다. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | 스레드에 사용할 잘림 전략을 가져오거나 설정합니다. 기본값은 auto입니다. last_messages로 설정하면 스레드는 스레드에서 n개의 가장 최근 메시지로 잘립니다. auto로 설정하면 스레드 중간의 메시지가 모델의 컨텍스트 길이인 max_prompt_tokens에 맞추기 위해 삭제됩니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)