---
title: "클래스 TruncationStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.TruncationStrategy 클래스. 실행 전에 스레드가 어떻게 잘릴지를 제어하는 트렁케이션 전략을 나타냅니다"
type: docs
weight: 1330
url: /ko/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

실행 전에 스레드가 어떻게 잘릴지를 제어하는 트렁케이션 전략을 나타냅니다.

```csharp
public class TruncationStrategy
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | 실행을 위한 컨텍스트를 구성할 때 스레드에서 가장 최근 메시지 수를 가져오거나 설정합니다. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | 스레드에 사용할 트렁케이션 전략을 가져오거나 설정합니다. 기본값은 auto입니다. last_messages 로 설정하면 스레드가 가장 최근 n개의 메시지로 잘립니다. auto 로 설정하면 모델의 컨텍스트 길이(max_prompt_tokens)에 맞추기 위해 스레드 중간의 메시지가 삭제됩니다. |

### 또 보기

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


