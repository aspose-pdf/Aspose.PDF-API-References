---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIClient クラス。ベクターストアファイルバッチを管理するために OpenAI API と対話するメソッドを提供します
type: docs
weight: 840
url: /ja/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient クラス

OpenAI API と対話するためのメソッドを提供し、ベクターストアファイルバッチを管理します。

OpenAI API と対話するためのメソッドを提供し、ベクターストアファイルを管理します。

OpenAI API と対話するためのメソッドを提供し、ベクターストアを管理します。

OpenAI API と対話するためのクライアントを表し、基本的な AI クライアント機能を拡張します。

スレッド内の実行ステップを管理するために OpenAI API と対話するためのメソッドを提供します。

ファイルを管理するために OpenAI API と対話するためのメソッドを提供します。

スレッドメッセージを管理するために OpenAI API と対話するためのメソッドを提供します。

スレッドを管理するために OpenAI API と対話するためのメソッドを提供します。

アシスタントを管理するために OpenAI API と対話するためのメソッドを提供します。

完了を作成するために OpenAI API と対話するためのメソッドを提供します。

スレッド内の実行を管理するために OpenAI API と対話するためのメソッドを提供します。

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
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
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | スレッド内の既存の実行を非同期にキャンセルします。 |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | 特定のベクターストアファイルバッチを非同期にキャンセルします。 |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | 新しいアシスタントを非同期に作成します。 |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | 新しい完了を非同期に作成します。 |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | 指定されたスレッド内に実行を非同期に作成します。 |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | スレッドとその中に実行を非同期に作成します。 |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | 新しいスレッドを非同期に作成します。 |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | スレッド内に新しいメッセージを非同期に作成します。 |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | 新しいベクターストアを作成し、非同期に完了を待ちます。 |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | 新しいベクターストアを非同期に作成します。 |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | 新しいベクターストアファイルを非同期に作成します。 |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | 新しいベクターストアファイルバッチを非同期に作成します。 |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | 既存のアシスタントを非同期に削除します。 |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | 特定のファイルを非同期に削除します。 |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | 既存のスレッドを非同期に削除します。 |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | スレッド内のメッセージを非同期に削除します。 |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | ベクターストアを非同期に削除します。 |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | ベクターストア内のファイルを非同期に削除します。 |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | [`AIClientBase`](../aiclientbase/) によって使用されるリソースを解放します。 |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | 特定のアシスタントの詳細を非同期に取得します。 |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | アシスタントのリストを非同期に取得します。 |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | 指定されたオプションで [`IChatCopilot`](../ichatcopilot/) のインスタンスを取得します。 |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | 特定のファイルの詳細を非同期に取得します。 |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | 指定された目的に基づいてファイルのリストを非同期に取得します。 |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | 指定されたオプションで [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) のインスタンスを取得します。 |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | スレッド内の特定の実行の詳細を非同期に取得します。 |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | 指定されたスレッドの実行のリストを非同期に取得します。 |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | 実行内の特定のステップの詳細を非同期に取得します。 |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | スレッド内の特定の実行のステップのリストを非同期に取得します。 |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | 指定されたオプションで [`ISummaryCopilot`](../isummarycopilot/) のインスタンスを取得します。 |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | 特定のスレッドの詳細を非同期に取得します。 |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | スレッド内の特定のメッセージの詳細を非同期に取得します。 |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 特定のスレッドのメッセージのリストを非同期に取得します。 |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | 特定のベクターストアの詳細を非同期に取得します。 |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | ベクターストア内の特定のファイルの詳細を非同期に取得します。 |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string) | 特定のベクターストアファイルバッチの詳細を非同期に取得します。 |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | 特定のベクターストアファイルバッチ内のファイルのリストを非同期に取得します。 |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | 特定のベクターストア内のファイルのリストを非同期に取得します。 |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | ベクターストアのリストを非同期に取得します。 |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | 既存のアシスタントを非同期に修正します。 |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | スレッド内の既存の実行を非同期に修正します。 |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | 既存のスレッドを非同期に修正します。 |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | スレッド内の既存のメッセージを非同期に修正します。 |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | 既存のベクターストアを非同期に修正します。 |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | 指定された threadId と runCreateRequest でアシスタントを実行し、非同期にアシスタントの応答を取得します。 |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | OpenAI サーバーにファイルを非同期にアップロードします。 |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | スレッド内のアシスタントからの最初のメッセージを非同期に待ちます。 |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | スレッド内の実行が完了するのを非同期に待ちます。 |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | 特定のスレッドメッセージが完了するのを非同期に待ちます。 |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | 特定のベクターストアファイルが完了するのを非同期に待ちます。 |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | 特定のベクターストアが完了するのを非同期に待ちます。 |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | 提供された API キーで [`Builder`](../openaiclient.builder/) の新しいインスタンスを作成します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | `OpenAIClient` のインスタンスを作成するためのビルダー クラス。 |

### 参照

* class [AIClientBase](../aiclientbase/)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* interface [IOpenAIClient](../iopenaiclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)