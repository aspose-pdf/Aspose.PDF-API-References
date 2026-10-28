---
title: "클래스 PdfXmlLoadOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.PdfXmlLoadOptions 클래스. PdfXml 형식에 대한 로드 옵션"
type: docs
weight: 8590
url: /ko/net/aspose.pdf/pdfxmlloadoptions/
---
## PdfXmlLoadOptions class

PdfXml 형식에 대한 로드 옵션입니다.

```csharp
public class PdfXmlLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfXmlLoadOptions](pdfxmlloadoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 해제하는 플래그를 가져오거나 설정합니다. `true`인 경우 해당 글꼴의 라이선스에서 금지된 작업을 수행할 수 있게 하며, 예를 들어 라이선스 규정이 임베딩을 금지하더라도 글꼴을 PDF 문서에 삽입할 수 있습니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `[`LoadOptions`](../loadoptions/)`가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환하면 Load 작업이 중단됩니다. |

## 예제

다음 예제는 PDFXML 파일을 PDF 파일로 변환하는 방법을 보여줍니다

```csharp
[C#]
	// 문서 디렉터리 경로.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// PDFXML 파일의 경로.
	string pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml");

	// 출력 PDF 파일 경로.
	string pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf");

	// PdfXmlLoadOptions 초기화	
	PdfXmlLoadOptions pdfXmlLoadOptions = new PdfXmlLoadOptions();
		
	using (Document pdfDocument = new Document(pdfXmlFile, pdfXmlLoadOptions))
	{
	 
		// PDF 파일 저장
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDFXML File.
    Dim pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf")
 
    ' Initialize PdfXmlLoadOptions  
    Dim pdfXmlLoadOptions As PdfXmlLoadOptions = New PdfXmlLoadOptions()
 
    Using pdfDocument As Document = New Document(pdfXmlFile, pdfXmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


