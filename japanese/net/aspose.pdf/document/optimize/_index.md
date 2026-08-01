---
title: "Document.Optimize"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document メソッド。 ドキュメントを線形化して、最初のページをできるだけ早く開く、次のページをできるだけ早く表示またはリンクで次のページへ移動する、ページのデータが遅いチャネルで届く際に段階的にページを表示する、最も有用なデータを先に表示する、ページ全体が受信・表示される前でもリンクをたどるといったユーザー操作を可能にする、という目的で実行します。このメソッドを呼び出しても実際にドキュメントは保存されません。むしろ、ドキュメントは最適化された構造になるように準備されるだけです。最適化されたドキュメントを取得するには、後で Save を呼び出してください。"
type: docs
weight: 770
url: /ja/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

document をリニアライズして、- 最初のページをできるだけ速く開くため、- 次のページを表示するか、次のページへのリンクをできるだけ速くたどるため、- ページデータが遅いチャネルで送信される際に、ページが到着したら段階的に表示する（最も有用なデータを先に表示する）ため、- ユーザー操作（リンクのクリックなど）を、ページ全体が受信・表示される前に実行できるようにするためです。このメソッドを呼び出しても実際には document は保存されません。むしろ、document は最適化された構造になるように準備されるだけで、最適化された document を取得するには Save を呼び出してください。

```csharp
public void Optimize()
```

### 例

次の例は、PDF ドキュメントをウェブ向けに最適化する方法を示しています。

```csharp
[C#]
	// PDF ファイルへのパスです。
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// 開く document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// ウェブ向け最適化
	pdfDocument.Optimize();

	// 出力ドキュメントを保存
	pdfDocument.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
	
    ' Open document
    Using pdfDocument As Document = New Document(pdfFilePath)

        ' Optimize for web
        pdfDocument.Optimize()

        ' Save output document
        pdfDocument.Save(pdfFilePath)
    End Using
```

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


