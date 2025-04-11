---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaClient クラス。Llama API と対話するためのクライアントを表します
type: docs
weight: 700
url: /ja/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient クラス

Llama API と対話するためのクライアントを表します。

Llama API と対話するためのクライアントを表します。

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | バックオフ遅延を秒単位で取得または設定します。 |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | HTTP リクエストの最大再試行回数を取得または設定します。 |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | ポーリング間隔を秒単位で取得または設定します。 |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | ポーリングタイムアウトを秒単位で取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Llama サービスでチャット完了リクエストを作成します。 |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | [`AIClientBase`](../aiclientbase/) によって使用されるリソースを解放します。 |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | 指定されたオプションを持つ [`ISummaryCopilot`](../isummarycopilot/) のインスタンスを取得します。 |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | 提供された API キーで [`Builder`](../llamaclient.builder/) の新しいインスタンスを作成します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | `LlamaClient` のインスタンスを作成するためのビルダー クラス。 |

### 参照

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)