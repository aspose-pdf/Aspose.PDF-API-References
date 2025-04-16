---
title: RunThreadCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunThreadCreateRequest プロパティ。モデルが出力しなければならないフォーマットを取得または設定します。GPT-4o、GPT-4 Turbo、および gpt-3.5turbo1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。"type": "json_object" に設定すると、JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルに自分で JSON を生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白の無限ストリームを生成し、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length" の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。
type: docs
weight: 80
url: /ja/net/aspose.pdf.ai/runthreadcreaterequest/responseformat/
---
## RunThreadCreateRequest.ResponseFormat プロパティ

モデルが出力しなければならないフォーマットを取得または設定します。GPT-4o、GPT-4 Turbo、および gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルに自分で JSON を生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白の無限ストリームを生成し、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length" の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 関連項目

* class [ResponseFormat](../../responseformat/)
* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)