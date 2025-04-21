---
title: AssistantCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: AssistantCreateRequestプロパティ。モデルが出力しなければならないフォーマットを取得または設定します。gpt3.5turbo1106以降のGPT-4o、GPT-4 Turbo、およびすべてのGPT-3.5 Turboモデルと互換性があります。"type" "json_object" に設定すると、JSONモードが有効になり、モデルが生成するメッセージが有効なJSONであることが保証されます。重要 JSONモードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルに自分でJSONを生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length"の場合、メッセージの内容が部分的にカットオフされる可能性があることに注意してください。これは、生成がmax_tokensを超えたか、会話が最大コンテキスト長を超えたことを示します。
type: docs
weight: 70
url: /ja/net/aspose.pdf.ai/assistantcreaterequest/responseformat/
---
## AssistantCreateRequest.ResponseFormatプロパティ

モデルが出力しなければならないフォーマットを取得または設定します。gpt-3.5-turbo-1106以降のGPT-4o、GPT-4 Turbo、およびすべてのGPT-3.5 Turboモデルと互換性があります。{ "type": "json_object" }に設定すると、JSONモードが有効になり、モデルが生成するメッセージが有効なJSONであることが保証されます。重要: JSONモードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルに自分でJSONを生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length"の場合、メッセージの内容が部分的にカットオフされる可能性があることに注意してください。これは、生成がmax_tokensを超えたか、会話が最大コンテキスト長を超えたことを示します。

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 参照

* class [ResponseFormat](../../responseformat/)
* class [AssistantCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)