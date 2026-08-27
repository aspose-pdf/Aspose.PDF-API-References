---
title: "Document.Decrypt"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document メソッド。ドキュメントを復号化します。その後 Save を呼び出して復号化されたバージョンのドキュメントを取得します。"
type: docs
weight: 620
url: /ja/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

Document を復号化します。その後 Save を呼び出して復号化されたバージョンを取得します。

```csharp
public void Decrypt()
```

### 例

以下のサンプルコードは PDF ファイルを復号化する方法を示しています。

```csharp
[C#]
	// PDF ファイルへのパスです。
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// 開く document
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// PDF を復号化
		document.Decrypt();

		// 更新された PDF を保存
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

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


