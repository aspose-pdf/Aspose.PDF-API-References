---
title: "CompletionCreateRequest.ToolChoice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "CompletionCreateRequest プロパティ。モデルが呼び出すツール（存在する場合）を制御するオブジェクトを取得または設定します。none はモデルがツールを呼び出さずにメッセージを生成することを意味します。auto はモデルがメッセージ生成とツール呼び出し（1 つ以上）を選択できることを意味します。required はモデルが必ず 1 つ以上のツールを呼び出す必要があることを意味します。type function function name my_function のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます。ツールが存在しない場合のデフォルトは none です。ツールが存在する場合のデフォルトは auto です。"
type: docs
weight: 150
url: /ja/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice property

モデルが呼び出すツール（存在する場合）を制御するオブジェクトを取得または設定します。none はモデルがツールを呼び出さずメッセージを生成することを意味します。auto はモデルがメッセージ生成または1つ以上のツール呼び出しを選択できることを意味します。required はモデルが1つ以上のツールを必ず呼び出す必要があることを意味します。{"type": "function", "function": {"name": "my_function"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます。ツールが存在しない場合のデフォルトは none です。ツールが存在する場合のデフォルトは auto です。

```csharp
public ToolChoice ToolChoice { get; set; }
```

### 関連項目

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


