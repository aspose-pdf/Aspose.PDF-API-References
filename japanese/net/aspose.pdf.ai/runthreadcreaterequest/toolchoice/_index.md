---
title: RunThreadCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunThreadCreateRequest プロパティ。モデルによって呼び出されるツールがある場合、それを取得または設定します。none はモデルがツールを呼び出さず、代わりにメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージを生成するか、1つ以上のツールを呼び出すかを選択できることを意味します。required は、モデルがユーザーに応答する前に1つ以上のツールを呼び出さなければならないことを意味します。"type": "file_search" や "type": "function", "function": "name": "my_function" のように特定のツールを指定すると、モデルはそのツールを呼び出すことを強制されます。
type: docs
weight: 120
url: /ja/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## RunThreadCreateRequest.ToolChoice プロパティ

モデルによって呼び出されるツールがある場合、それを取得または設定します。none はモデルがツールを呼び出さず、代わりにメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージを生成するか、1つ以上のツールを呼び出すかを選択できることを意味します。required は、モデルがユーザーに応答する前に1つ以上のツールを呼び出さなければならないことを意味します。{"type": "file_search"}や{"type": "function", "function": {"name": "my_function"}}のように特定のツールを指定すると、モデルはそのツールを呼び出すことを強制されます。

```csharp
public string ToolChoice { get; set; }
```

### 参照

* クラス [RunThreadCreateRequest](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)