---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunThreadCreateRequest クラス。スレッドを作成し、1つのリクエストで実行するためのリクエストを表します。
type: docs
weight: 1070
url: /ja/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest クラス

スレッドを作成し、1つのリクエストで実行するためのリクエストを表します。

```csharp
public class RunThreadCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | この実行を実行するために使用するアシスタントのIDを取得または設定します。 |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | アシスタントの指示を上書きする指示を取得または設定します。これは、実行ごとに動作を変更するのに便利です。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | 実行中に使用できる最大の完了トークン数を取得または設定します。実行は、複数のターンにわたって指定された完了トークン数のみを使用するよう最善を尽くします。指定された完了トークン数を超えた場合、実行は不完全な状態で終了します。詳細については、incomplete_detailsを参照してください。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | 実行中に使用できる最大のプロンプトトークン数を取得または設定します。実行は、複数のターンにわたって指定されたプロンプトトークン数のみを使用するよう最善を尽くします。指定されたプロンプトトークン数を超えた場合、実行は不完全な状態で終了します。詳細については、incomplete_detailsを参照してください。 |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | オブジェクトに添付できる16のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大64文字、値は最大512文字までです。 |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | この実行を実行するために使用するモデルのIDを取得または設定します。ここに値が提供されると、アシスタントに関連付けられたモデルが上書きされます。提供されない場合は、アシスタントに関連付けられたモデルが使用されます。 |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | モデルが出力する必要がある形式を取得または設定します。GPT-4o、GPT-4 Turbo、およびgpt-3.5-turbo-1106以降のすべてのGPT-3.5 Turboモデルと互換性があります。{ "type": "json_object" }に設定すると、モデルが生成するメッセージが有効なJSONであることを保証するJSONモードが有効になります。重要: JSONモードを使用する場合は、システムまたはユーザーメッセージを介してモデルにJSONを生成するよう指示する必要があります。これがないと、モデルは生成がトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length"の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成がmax_tokensを超えたか、会話が最大コンテキスト長を超えたことを示します。 |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | ストリーミングを使用するかどうかを取得または設定します。trueの場合、実行中に発生するイベントのストリームをサーバー送信イベントとして返し、実行がデータ: [DONE]メッセージで終了する端末状態に入ると終了します。 |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | 使用するサンプリング温度を取得または設定します。0から2の範囲で、高い値（例: 0.8）は出力をよりランダムにし、低い値（例: 0.2）はより焦点を絞った決定論的なものにします。 |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | スレッドを作成するためのリクエストを取得または設定します。 |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | モデルによって呼び出されるツール（ある場合）を取得または設定します。noneは、モデルがツールを呼び出さずにメッセージを生成することを意味します。autoはデフォルト値で、モデルがメッセージを生成するか、1つ以上のツールを呼び出すかを選択できることを意味します。requiredは、モデルがユーザーに応答する前に1つ以上のツールを呼び出す必要があることを意味します。{"type": "file_search"}や{"type": "function", "function": {"name": "my_function"}}のように特定のツールを指定すると、モデルはそのツールを呼び出すことになります。 |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | アシスタントのツールによって使用されるリソースのセットを取得または設定します。 |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | この実行のためにアシスタントが使用できるツールを上書きするツールを取得または設定します。これは、実行ごとに動作を変更するのに便利です。 |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | サンプリング温度の代わりに使用される値を取得または設定します。これは、モデルがtop_p確率質量を持つトークンの結果を考慮する核サンプリングです。したがって、0.1は、上位10%の確率質量を構成するトークンのみが考慮されることを意味します。一般的に、これまたは温度を変更することをお勧めしますが、両方は変更しないでください。 |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | 実行前にスレッドがどのように切り捨てられるかを制御する切り捨て戦略を取得または設定します。これを使用して、実行の初期コンテキストウィンドウを制御します。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)