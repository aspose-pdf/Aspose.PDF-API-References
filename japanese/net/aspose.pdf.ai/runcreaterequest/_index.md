---
title: Class RunCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunCreateRequest クラス。ランを作成するためのリクエストを表します
type: docs
weight: 980
url: /ja/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest クラス

ランを作成するためのリクエストを表します。

```csharp
public class RunCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | 追加の指示を取得または設定します。ランの指示の最後に追加の指示を追加します。これは、他の指示を上書きせずに、ランごとに動作を変更するのに便利です。 |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | ランを作成する前にスレッドに追加のメッセージを取得または設定します。 |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | このランを実行するために使用するアシスタントのIDを取得または設定します。 |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | アシスタントの指示を上書きする指示を取得または設定します。これは、ランごとに動作を変更するのに便利です。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | ランの過程で使用される最大の完了トークン数を取得または設定します。ランは、複数のターンにわたって指定された完了トークンの数のみを使用するよう最善を尽くします。指定された完了トークンの数を超えた場合、ランは不完全な状態で終了します。詳細については incomplete_details を参照してください。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | ランの過程で使用される最大のプロンプトトークン数を取得または設定します。ランは、複数のターンにわたって指定されたプロンプトトークンの数のみを使用するよう最善を尽くします。指定されたプロンプトトークンの数を超えた場合、ランは不完全な状態で終了します。詳細については incomplete_details を参照してください。 |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | オブジェクトに添付できる16のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大64文字、値は最大512文字までです。 |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | このランを実行するために使用されるモデルのIDを取得または設定します。ここに値が提供されると、アシスタントに関連付けられたモデルが上書きされます。提供されない場合は、アシスタントに関連付けられたモデルが使用されます。 |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | レスポンス形式を取得または設定します。モデルが出力する必要がある形式を指定します。GPT-4o、GPT-4 Turbo、および gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、モデルが生成するメッセージが有効な JSON であることを保証する JSON モードが有効になります。重要: JSON モードを使用する場合は、システムまたはユーザーメッセージを介してモデルに自分で JSON を生成するよう指示する必要があります。これがないと、モデルは生成がトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length" の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。 |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | ストリーミングを使用するかどうかを取得または設定します。true の場合、ラン中に発生するイベントのストリームをサーバー送信イベントとして返し、ランがデータ: [DONE] メッセージで端末状態に入ると終了します。 |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | 使用するサンプリング温度を取得または設定します。0から2の範囲です。0.8のような高い値は出力をよりランダムにし、0.2のような低い値はより焦点を絞った決定論的なものにします。 |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | モデルによって呼び出されるツールを取得または設定します。none はモデルがツールを呼び出さず、代わりにメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージを生成するか、1つ以上のツールを呼び出すかを選択できることを意味します。required は、モデルがユーザーに応答する前に1つ以上のツールを呼び出す必要があることを意味します。{"type": "file_search"} や {"type": "function", "function": {"name": "my_function"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すことになります。 |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | このランのためにアシスタントが使用できるツールを上書きするツールを取得または設定します。これは、ランごとに動作を変更するのに便利です。 |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | 温度を使用したサンプリングの代替手段を取得または設定します。これは、モデルが top_p 確率質量を持つトークンの結果を考慮する核サンプリングです。したがって、0.1 は上位10%の確率質量を構成するトークンのみが考慮されることを意味します。一般的に、これまたは温度を変更することをお勧めしますが、両方を変更することはお勧めしません。 |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | 切り捨て戦略を取得または設定します。ランの前にスレッドがどのように切り捨てられるかを制御します。これを使用して、ランの初期コンテキストウィンドウを制御します。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)