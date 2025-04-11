---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントメソッド。ドキュメントを復号化します。その後、保存を呼び出して復号化されたバージョンのドキュメントを取得します。
type: docs
weight: 600
url: /ja/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt メソッド

ドキュメントを復号化します。その後、保存を呼び出して復号化されたバージョンのドキュメントを取得します。

```csharp
public void Decrypt()
```

### 例

以下のサンプルコードは、PDFファイルを復号化する方法を示しています。

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// Decrypt PDF
		document.Decrypt();

		// Save updated PDF
		document.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"

    ' Open document
    Using document As Document = New Document(pdfFilePath, "YOUR_PASSWORD")

        ' Decrypt PDF
        document.Decrypt()

        ' Save updated PDF
        document.Save(pdfFilePath)
    End Using
```

### 関連項目

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)