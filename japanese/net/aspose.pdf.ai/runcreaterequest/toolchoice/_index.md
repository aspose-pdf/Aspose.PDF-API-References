---
title: "RunCreateRequest.ToolChoice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "RunCreateRequest プロパティ。モデルが呼び出すツールを取得または設定します。none はモデルがツールを呼び出さずメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージ生成または1つ以上のツール呼び出しのいずれかを選択できることを意味します。required はモデルがユーザーに応答する前に1つ以上のツールを必ず呼び出す必要があることを意味します。type file_search や type function function name my_function のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます"
type: docs
weight: 130
url: /ja/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## RunCreateRequest.ToolChoice property

モデルが呼び出すツール（存在する場合）を取得または設定します。none はモデルがツールを呼び出さずメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージ生成または1つ以上のツール呼び出しのいずれかを選択できることを意味します。required はモデルがユーザーに応答する前に1つ以上のツールを必ず呼び出さなければならないことを意味します。{\"type\": \"file_search\"} や {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます。

```csharp
public string ToolChoice { get; set; }
```

### 関連項目

* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


