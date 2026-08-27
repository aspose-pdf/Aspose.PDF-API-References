---
title: "Document.Optimize"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document 메서드. 문서를 선형화하여 첫 페이지를 가능한 한 빨리 열고, 다음 페이지를 표시하거나 다음 페이지로 연결되는 링크를 가능한 한 빨리 따라갈 수 있도록 합니다. 페이지 데이터가 느린 채널을 통해 전달될 때 페이지가 도착하는 대로 점진적으로 표시하고, 가장 유용한 데이터를 먼저 표시합니다. 전체 페이지가 수신 및 표시되기 전에 링크를 따라가는 등 사용자 상호 작용을 허용합니다. 이 메서드를 호출해도 실제로 문서가 저장되지는 않습니다. 오히려 문서는 최적화된 구조를 갖도록 준비될 뿐이며, 최적화된 문서를 얻으려면 이후에 Save를 호출해야 합니다."
type: docs
weight: 770
url: /ko/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

문서를 선형화하여 - 첫 페이지를 가능한 빨리 열 수 있도록; - 다음 페이지를 표시하거나 다음 페이지로 연결되는 링크를 가능한 빨리 따라갈 수 있도록; - 페이지 데이터가 느린 채널을 통해 전달될 때 도착하는 대로 페이지를 점진적으로 표시하도록(가장 유용한 데이터를 먼저 표시); - 전체 페이지가 수신 및 표시되기 전에 링크 따라가기와 같은 사용자 상호 작용을 수행할 수 있도록 합니다. 이 메서드를 호출해도 실제로 문서는 저장되지 않습니다. 오히려 문서는 최적화된 구조를 준비할 뿐이며, 최적화된 문서를 얻으려면 Save를 호출하십시오.

```csharp
public void Optimize()
```

### 예제

다음 예제는 웹용 PDF 문서를 최적화하는 방법을 보여줍니다.

```csharp
[C#]
	// PDF File의 경로입니다.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// 문서 열기
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// 웹용 최적화
	pdfDocument.Optimize();

	// 출력 문서 저장
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

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


