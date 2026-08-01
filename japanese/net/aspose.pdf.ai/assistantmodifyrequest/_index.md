---
title: "クラス AssistantModifyRequest"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.AssistantModifyRequest クラス。アシスタントを変更するためのリクエストオブジェクトです"
type: docs
weight: 130
url: /ja/net/aspose.pdf.ai/assistantmodifyrequest/
---
## AssistantModifyRequest class

アシスタントを変更するためのリクエストオブジェクト。

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AssistantModifyRequest](assistantmodifyrequest/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | アシスタントの説明を取得または設定します。最大長は 512 文字です。 |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | アシスタントが使用するシステム指示を取得または設定します。最大長は 256,000 文字です。 |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | 使用するモデルの ID を取得または設定します。List models API を使用して利用可能なすべてのモデルを確認するか、Model overview でそれらの説明をご覧ください。 |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | アシスタントの名前を取得または設定します。最大長は 256 文字です。 |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | モデルが出力しなければならない形式を取得または設定します。GPT-4o、GPT-4 Turbo、そして gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ \"type\": \"json_object\" } に設定すると JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合、システムメッセージまたはユーザーメッセージでモデルに JSON を生成するよう指示する必要があります。これを行わないと、モデルはトークン上限に達するまで空白のストリームを無限に生成し続け、長時間実行され「スタックした」ように見えるリクエストになる可能性があります。また、finish_reason=\"length\" の場合、生成が max_tokens を超えた、または会話が最大コンテキスト長を超えたことを示し、メッセージ内容が部分的に切り取られることがあります。 |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | 使用するサンプリング温度を取得または設定します（0 から 2 の範囲）。0.8 のような高い値は出力をよりランダムにし、0.2 のような低い値はより集中した決定的な出力にします。 |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | アシスタントのツールで使用されるリソースを取得または設定します。リソースはツールのタイプに固有です。例えば、code_interpreter ツールはファイル ID のリストを必要とし、file_search ツールはベクトルストア ID のリストを必要とします。 |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | アシスタントで有効化されたツールのリストを取得または設定します。アシスタントあたり最大 128 個のツールが可能です。ツールは code_interpreter、file_search、または function のタイプです。 |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | 温度によるサンプリングの代替として、トップ確率質量 top_p を考慮する nucleus sampling と呼ばれる手法を取得または設定します。たとえば 0.1 は上位 10% の確率質量を占めるトークンのみが考慮されることを意味します。通常、temperature とこの設定は同時に変更せず、どちらか一方を調整することを推奨します。 |

### 関連項目

* class [AssistantCreateRequest](../assistantcreaterequest/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


