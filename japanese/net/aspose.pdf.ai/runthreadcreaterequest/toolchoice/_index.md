---
title: "RunThreadCreateRequest.ToolChoice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "RunThreadCreateRequest プロパティ。モデルが呼び出すツールを取得または設定します。none はモデルがツールを呼び出さずにメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージ生成またはツール呼び出しのいずれかを選択できることを意味します。required はモデルがユーザーへの応答前に少なくとも一つのツールを呼び出す必要があることを意味します。type file_search や type function function name my_function のように特定のツールを指定すると、モデルはそのツールを必ず呼び出します。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## RunThreadCreateRequest.ToolChoice property

モデルが呼び出すツール（存在する場合）を取得または設定します。none はモデルがツールを呼び出さずメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージ生成または1つ以上のツール呼び出しのいずれかを選択できることを意味します。required はモデルがユーザーに応答する前に1つ以上のツールを必ず呼び出さなければならないことを意味します。{\"type\": \"file_search\"} や {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます。

```csharp
public string ToolChoice { get; set; }
```

### 関連項目

* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


