---
title: RunCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunCreateRequest プロパティ。レスポンスフォーマットを取得または設定します。モデルが出力する必要があるフォーマットを指定します。GPT-4o、GPT-4 Turbo、および gpt-3.5turbo1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルに自分で JSON を生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白の無限ストリームを生成する可能性があり、その結果、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length" の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。
type: docs
weight: 100
url: /ja/net/aspose.pdf.ai/runcreaterequest/responseformat/
---
## RunCreateRequest.ResponseFormat プロパティ

レスポンスフォーマットを取得または設定します。モデルが出力する必要があるフォーマットを指定します。GPT-4o、GPT-4 Turbo、および gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合は、システムメッセージまたはユーザーメッセージを介してモデルに自分で JSON を生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白の無限ストリームを生成する可能性があり、その結果、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length" の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 関連情報

* クラス [ResponseFormat](../../responseformat/)
* クラス [RunCreateRequest](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)