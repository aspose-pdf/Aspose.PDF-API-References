---
title: Class PdfXmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfXmlLoadOptions 클래스. PdfXml 형식의 로드 옵션
type: docs
weight: 8460
url: /ko/net/aspose.pdf/pdfxmlloadoptions/
---
## PdfXmlLoadOptions 클래스

PdfXml 형식의 로드 옵션입니다.

```csharp
public class PdfXmlLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfXmlLoadOptions](pdfxmlloadoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 비활성화하는 플래그를 가져오거나 설정합니다. `true`일 경우, 이 글꼴의 라이선스에 의해 금지된 글꼴로 작업을 수행할 수 있도록 허용합니다. 예를 들어, 이 글꼴에 대한 임베딩이 금지된 경우에도 PDF 문서에 글꼴을 임베드할 수 있도록 허용합니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/)가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 로드 작업이 계속되지만, 사용자가 Abort를 반환할 경우 로드 작업은 중단되어야 합니다. |

## 예제

다음 예제는 PDFXML 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PDFXML File.
	string pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf");

	// Initialize PdfXmlLoadOptions	
	PdfXmlLoadOptions pdfXmlLoadOptions = new PdfXmlLoadOptions();
		
	using (Document pdfDocument = new Document(pdfXmlFile, pdfXmlLoadOptions))
	{
	 
		// Save PDF file
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

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)