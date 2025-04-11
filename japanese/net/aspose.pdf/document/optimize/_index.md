---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントメソッド。ドキュメントを線形化して、できるだけ早く最初のページを開き、できるだけ早く次のページを表示するか、次のページへのリンクをたどることができるようにし、データが遅いチャネルで配信されるときにページが到着するにつれてページを段階的に表示し、最も有用なデータを最初に表示し、ユーザーがリンクをたどるなどの操作を、ページ全体が受信され表示される前に実行できるようにします。このメソッドを呼び出しても、実際にはドキュメントは保存されません。逆に、ドキュメントは最適化された構造を持つように準備されるだけであり、その後に保存を呼び出して最適化されたドキュメントを取得します。
type: docs
weight: 750
url: /ja/net/aspose.pdf/document/optimize/
---
## Document.Optimize メソッド

ドキュメントを線形化して、- できるだけ早く最初のページを開く; - できるだけ早く次のページを表示するか、次のページへのリンクをたどる; - データが遅いチャネルで配信されるときにページが到着するにつれてページを段階的に表示する（最も有用なデータを最初に表示する）; - ページ全体が受信され表示される前に、リンクをたどるなどのユーザーインタラクションを実行できるようにします。このメソッドを呼び出しても、実際にはドキュメントは保存されません。逆に、ドキュメントは最適化された構造を持つように準備されるだけであり、その後に保存を呼び出して最適化されたドキュメントを取得します。

```csharp
public void Optimize()
```

### 例

次の例は、PDFドキュメントをウェブ用に最適化する方法を示しています。

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimize for web
	pdfDocument.Optimize();

	// Save output document
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

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)