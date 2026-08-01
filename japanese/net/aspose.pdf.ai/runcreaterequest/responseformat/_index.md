---
title: "RunCreateRequest.ResponseFormat"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "RunCreateRequest プロパティ。レスポンス形式を取得または設定します。モデルが出力すべき形式を指定します。GPT4o、GPT4 Turbo、そして gpt3.5turbo1106 以降のすべての GPT3.5 Turbo モデルと互換性があります。`type json_object` に設定すると JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。JSON モードを使用する場合、システムメッセージまたはユーザーメッセージでモデルに JSON を生成するよう指示する必要があります。これを行わないと、モデルはトークン上限に達するまで空白のストリームを無限に生成し、長時間実行されているように見えるリクエストになることがあります。また、生成が max_tokens を超えた、または会話が最大コンテキスト長を超えたことを示す finish_reasonlength がある場合、メッセージ内容が部分的に切り取られることがあります。"
type: docs
weight: 100
url: /ja/net/aspose.pdf.ai/runcreaterequest/responseformat/
---
## RunCreateRequest.ResponseFormat property

レスポンス形式を取得または設定します。モデルが出力しなければならない形式を指定します。GPT-4o、GPT-4 Turbo、そして gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ \"type\": \"json_object\" } に設定すると JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合、システムメッセージまたはユーザーメッセージでモデルに JSON を生成するよう指示する必要があります。これを行わないと、モデルはトークン上限に達するまで空白のストリームを無限に生成し続け、長時間実行され「スタック」したように見えるリクエストになる可能性があります。また、finish_reason=\"length\" の場合、生成が max_tokens を超えた、または会話が最大コンテキスト長を超えたことを示し、メッセージ内容が部分的に切り取られることがあります。

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 関連項目

* class [ResponseFormat](../../responseformat/)
* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


