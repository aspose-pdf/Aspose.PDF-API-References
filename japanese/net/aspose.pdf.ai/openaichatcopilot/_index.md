---
title: "クラス OpenAIChatCopilot"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.OpenAIChatCopilot クラス。AI モデルを介してドキュメントと対話するためのチャットコパイロットを表します。OpenAI クライアントを作成し、オプションを設定し、ChatCopilot を使用してユーザーの問い合わせに応答し、会話コンテキストを管理する使用例です。"
type: docs
weight: 880
url: /ja/net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

AI モデルを介してドキュメントとやり取りするためのチャットコパイロットを表します。OpenAI クライアントの作成、オプションの構成、および ChatCopilot を使用してユーザーの問い合わせに応答し、会話コンテキストを管理する例です。

```csharp
// AI クライアントを作成します。
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// コパイロットオプションを作成します。
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...デリゲートを使用して作成します。
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// サマリーコパイロットを作成します。
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// ユーザーのクエリに対する応答を取得します。
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// クエリのリストに対する応答を取得します。
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// 要約を PDF ドキュメントとして保存します。
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// 指定された形式で要約を保存します。
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// 要約を PDF ドキュメントとして保存します。
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// 指定された形式で要約を保存します。
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// コンテキストを保存します。
await chatCopilot.SaveContextAsync("outputPath");

// コンテキストを削除します。
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | 指定されたクライアントとオプションで `OpenAIChatCopilot` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### 関連項目

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


