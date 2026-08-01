---
title: "クラス OpenAIClient"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "クラス Aspose.Pdf.AI.OpenAIClient。ベクトルストアファイルバッチを管理するための OpenAI API とやり取りするメソッドを提供します。"
type: docs
weight: 900
url: /ja/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

ベクトルストアのファイルバッチを管理するために OpenAI API とやり取りするメソッドを提供します。

ベクトルストアファイルを管理するための OpenAI API とやり取りするメソッドを提供します。

ベクトルストアを管理するための OpenAI API とやり取りするメソッドを提供します。

基本的な AI クライアント機能を拡張し、OpenAI API とやり取りするクライアントを表します。

スレッド内の実行ステップを管理するための OpenAI API とやり取りするメソッドを提供します。

ファイルを管理するための OpenAI API とやり取りするメソッドを提供します。

スレッドメッセージを管理するための OpenAI API とやり取りするメソッドを提供します。

スレッドを管理するための OpenAI API とやり取りするメソッドを提供します。

アシスタントを管理するための OpenAI API とやり取りするメソッドを提供します。

バックオフ遅延（秒）を取得または設定します。

HTTP リクエストの再試行回数の最大値を取得または設定します。

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, 
    IOcrClient<OpenAIOcrCopilotOptions>, IOpenAIClient, ISummaryClient<OpenAISummaryCopilotOptions>
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
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | 新しいアシスタントを非同期に作成します。 |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | 新しい完了を非同期に作成します。 |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | 指定されたスレッド内で実行を非同期に作成します。 |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | スレッドとその中の実行を非同期に作成します。 |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | 新しいスレッドを非同期に作成します。 |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | スレッド内に新しいメッセージを非同期に作成します。 |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | 新しいベクトルストアを作成し、完了するまで非同期で待機します。 |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | 新しいベクトルストアを非同期に作成します。 |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | 新しいベクトルストアファイルを非同期に作成します。 |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | 新しいベクトルストアファイルバッチを非同期に作成します。 |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | 既存のアシスタントを非同期に削除します。 |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | 特定のファイルを非同期に削除します。 |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | 既存のスレッドを非同期に削除します。 |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | スレッド内のメッセージを非同期に削除します。 |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | ベクトルストアを非同期に削除します。 |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | ベクトルストア内のファイルを非同期に削除します。 |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | [`AIClientBase`](../aiclientbase/) が使用するリソースを破棄します。 |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | ベクトルストア内のファイルを非同期に削除します。 |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | [`AIClientBase`](../aiclientbase/) が使用するリソースを解放します。 |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | 特定のアシスタントの詳細を非同期で取得します。 |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | アシスタントの一覧を非同期で取得します。 |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | 指定されたオプションで[`IChatCopilot`](../ichatcopilot/)のインスタンスを取得します。 |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | 特定のファイルの詳細を非同期で取得します。 |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | 指定された目的に基づいてファイルの一覧を非同期で取得します。 |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | 指定されたオプションで[`IImageDescriptionCopilot`](../iimagedescriptioncopilot/)のインスタンスを取得します。 |
| [GetOcrCopilot](../../aspose.pdf.ai/openaiclient/getocrcopilot/)(IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | 指定されたオプションで[`IOcrCopilot`](../iocrcopilot/)のインスタンスを取得します。 |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | スレッド内の特定の実行の詳細を非同期で取得します。 |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | 指定されたスレッドの実行一覧を非同期で取得します。 |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | 実行内の特定のステップの詳細を非同期で取得します。 |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | スレッド内の特定の実行のステップ一覧を非同期で取得します。 |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | 指定されたオプションで[`ISummaryCopilot`](../isummarycopilot/)のインスタンスを取得します。 |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | 特定のスレッドの詳細を非同期で取得します。 |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | スレッド内の特定のメッセージの詳細を非同期で取得します。 |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 特定のスレッドのメッセージ一覧を非同期で取得します。 |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | 特定のベクトルストアの詳細を非同期で取得します。 |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | ベクトルストア内の特定のファイルの詳細を非同期で取得します。 |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | 特定のベクトルストアファイルバッチの詳細を非同期で取得します。 |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | 特定のベクトルストアファイルバッチ内のファイル一覧を非同期で取得します。 |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | 特定のベクトルストア内のファイル一覧を非同期で取得します。 |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | ベクトルストアの一覧を非同期で取得します。 |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | 既存のアシスタントを非同期で変更します。 |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | スレッド内の既存の実行を非同期で変更します。 |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | 既存のスレッドを非同期で変更します。 |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | スレッド内の既存のメッセージを非同期で変更します。 |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | 既存のベクトルストアを非同期で変更します。 |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | 指定された threadId と runCreateRequest を使用してアシスタントを実行し、非同期でアシスタントの応答を取得します。 |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | ファイルを非同期で OpenAI サーバーにアップロードします。 |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | スレッド内でアシスタントからの最初のメッセージを非同期で待機します。 |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | スレッド内で run が完了するのを非同期で待機します。 |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | 特定のスレッドメッセージが完了するのを非同期で待機します。 |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | 特定のベクトルストアファイルが完了するのを非同期で待機します。 |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | 特定のベクトルストアが完了するのを非同期で待機します。 |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | 提供された API キーを使用して、[`Builder`](../openaiclient.builder/) の新しいインスタンスを作成します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | `OpenAIClient` のインスタンスを作成するための Builder クラスです。 |

### 関連項目

* class [AIClientBase](../aiclientbase/)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* interface [IOcrClient&lt;TOptions&gt;](../iocrclient-1/)
* class [OpenAIOcrCopilotOptions](../openaiocrcopilotoptions/)
* interface [IOpenAIClient](../iopenaiclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


