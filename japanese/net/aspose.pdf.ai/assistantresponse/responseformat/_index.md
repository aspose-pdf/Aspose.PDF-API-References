---
title: AssistantResponse.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: AssistantResponse プロパティ。モデルが出力しなければならないフォーマットを取得または設定します。gpt-3.5-turbo-1106 以降の GPT-4o、GPT-4 Turbo、およびすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルに自分で JSON を生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストが発生する可能性があります。また、finish_reason="length" の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。
type: docs
weight: 100
url: /ja/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## AssistantResponse.ResponseFormat プロパティ

モデルが出力しなければならないフォーマットを取得または設定します。gpt-3.5-turbo-1106 以降の GPT-4o、GPT-4 Turbo、およびすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルに自分で JSON を生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストが発生する可能性があります。また、finish_reason="length" の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 関連項目

* クラス [ResponseFormat](../../responseformat/)
* クラス [AssistantResponse](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)