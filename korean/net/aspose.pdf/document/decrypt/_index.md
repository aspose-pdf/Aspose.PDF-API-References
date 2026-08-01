---
title: "Document.Decrypt"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document 메서드. 문서를 복호화합니다. 그런 다음 Save를 호출하여 복호화된 문서 버전을 얻습니다."
type: docs
weight: 620
url: /ko/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt method

문서를 복호화합니다. 그런 다음 Save를 호출하여 복호화된 문서 버전을 얻습니다.

```csharp
public void Decrypt()
```

### 예제

다음 샘플 코드는 PDF 파일을 복호화하는 방법을 보여줍니다.

```csharp
[C#]
	// PDF File의 경로입니다.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// 문서 열기
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// PDF 복호화
		document.Decrypt();

		// 업데이트된 PDF 저장
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

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


