---
title: "クラス LlamaClient"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.LlamaClient クラス。Llama API と対話するためのクライアントを表します。"
type: docs
weight: 750
url: /ja/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

Llama API とやり取りするクライアントを表します。

Llama API とやり取りするクライアントを表します。

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | ポーリング間隔（秒）を取得または設定します。 |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | ポーリングタイムアウト（秒）を取得または設定します。 |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | スレッド内の既存の実行を非同期にキャンセルします。 |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | 特定のベクトルストアファイルバッチを非同期にキャンセルします。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Llama サービスでチャット完了リクエストを作成します。 |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | [`AIClientBase`](../aiclientbase/) が使用するリソースを解放します。 |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | 指定されたオプションで[`ISummaryCopilot`](../isummarycopilot/)のインスタンスを取得します。 |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | 提供された API キーを使用して [`Builder`](../llamaclient.builder/) の新しいインスタンスを作成します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | `LlamaClient` のインスタンスを作成するための Builder クラスです。 |

### 関連項目

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


