---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: 문서 메서드. 문서를 복호화합니다. 복호화된 문서 버전을 얻으려면 저장을 호출하십시오.
type: docs
weight: 600
url: /ko/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt 메서드

문서를 복호화합니다. 복호화된 문서 버전을 얻으려면 저장을 호출하십시오.

```csharp
public void Decrypt()
```

### 예제

다음 샘플 코드는 PDF 파일을 복호화하는 방법을 보여줍니다.

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

### 참조

* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)