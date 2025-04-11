---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: 문서 메서드. 문서를 선형화하여 첫 페이지를 가능한 한 빨리 열고, 다음 페이지를 가능한 한 빨리 표시하거나 다음 페이지로의 링크를 따르며, 느린 채널을 통해 페이지 데이터가 전달될 때 도착하는 대로 페이지를 점진적으로 표시하고, 가장 유용한 데이터를 먼저 표시하며, 전체 페이지가 수신되고 표시되기 전에 링크를 따르는 것과 같은 사용자 상호작용을 허용합니다. 이 메서드를 호출한다고 해서 실제로 문서가 저장되는 것은 아닙니다. 반대로 문서는 최적화된 구조를 갖도록 준비되며, 최적화된 문서를 얻으려면 Save를 호출해야 합니다.
type: docs
weight: 750
url: /ko/net/aspose.pdf/document/optimize/
---
## Document.Optimize 메서드

문서를 선형화하여 - 첫 페이지를 가능한 한 빨리 열고; - 다음 페이지를 가능한 한 빨리 표시하거나 다음 페이지로의 링크를 따르고; - 느린 채널을 통해 페이지 데이터가 전달될 때 도착하는 대로 페이지를 점진적으로 표시하고 (가장 유용한 데이터를 먼저 표시); - 전체 페이지가 수신되고 표시되기 전에 링크를 따르는 것과 같은 사용자 상호작용을 수행할 수 있도록 합니다. 이 메서드를 호출한다고 해서 실제로 문서가 저장되는 것은 아닙니다. 반대로 문서는 최적화된 구조를 갖도록 준비되며, 최적화된 문서를 얻으려면 Save를 호출해야 합니다.

```csharp
public void Optimize()
```

### 예제

다음 예제는 웹을 위해 PDF 문서를 최적화하는 방법을 보여줍니다.

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

### 참조

* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)