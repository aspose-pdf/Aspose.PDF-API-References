---
title: Class AssistantCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantCreateRequest クラス。アシスタントを作成するためのリクエストオブジェクト
type: docs
weight: 100
url: /ja/net/aspose.pdf.ai/assistantcreaterequest/
---
## AssistantCreateRequest クラス

アシスタントを作成するためのリクエストオブジェクト。

```csharp
public class AssistantCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | アシスタントの説明を取得または設定します。最大長は512文字です。 |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | アシスタントが使用するシステム指示を取得または設定します。最大長は256,000文字です。 |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | オブジェクトに添付できる16のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに役立ちます。キーは最大64文字、値は最大512文字です。 |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | 使用するモデルのIDを取得または設定します。利用可能なすべてのモデルを確認するには、List models APIを使用するか、モデルの概要を参照してください。 |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | アシスタントの名前を取得または設定します。最大長は256文字です。 |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | モデルが出力する必要がある形式を取得または設定します。GPT-4o、GPT-4 Turbo、およびgpt-3.5-turbo-1106以降のすべてのGPT-3.5 Turboモデルと互換性があります。{ "type": "json_object" }に設定すると、モデルが生成するメッセージが有効なJSONであることを保証するJSONモードが有効になります。重要: JSONモードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルにJSONを生成するよう指示する必要があります。これがないと、モデルは生成がトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length"の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成がmax_tokensを超えたか、会話が最大コンテキスト長を超えたことを示します。 |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | 使用するサンプリング温度を取得または設定します。範囲は0から2です。0.8のような高い値は出力をよりランダムにし、0.2のような低い値はより集中し決定論的にします。 |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | アシスタントのツールによって使用されるリソースを取得または設定します。リソースはツールの種類に特有です。たとえば、code_interpreterツールはファイルIDのリストを必要とし、file_searchツールはベクターストアIDのリストを必要とします。 |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | アシスタントで有効なツールのリストを取得または設定します。アシスタントごとに最大128のツールを持つことができます。ツールはcode_interpreter、file_search、またはfunctionのタイプであることができます。 |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | 温度によるサンプリングの代替手段である、核サンプリングを取得または設定します。モデルはtop_p確率質量を持つトークンの結果を考慮します。したがって、0.1は上位10%の確率質量を構成するトークンのみが考慮されることを意味します。一般的に、これまたは温度を変更することをお勧めしますが、両方を変更することはお勧めしません。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)