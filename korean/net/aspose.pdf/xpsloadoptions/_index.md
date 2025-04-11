---
title: Class XpsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XpsLoadOptions 클래스. PDF 문서로 XPS 파일을 로드/가져오기 위한 옵션을 나타냅니다.
type: docs
weight: 11510
url: /ko/net/aspose.pdf/xpsloadoptions/
---
## XpsLoadOptions 클래스

PDF 문서로 XPS 파일을 로드/가져오기 위한 옵션을 나타냅니다.

```csharp
public sealed class XpsLoadOptions : LoadOptions, IPipelineOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XpsLoadOptions](xpsloadoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | 소스 및 대상 형식 쌍에 배치 변환이 적용 가능한 경우 배치 크기를 정의합니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 비활성화하는 플래그를 가져오거나 설정합니다. `true`일 경우, 이 글꼴의 라이선스에 의해 금지된 글꼴로 작업을 수행할 수 있도록 허용합니다. 예를 들어, 이 글꼴에 대한 임베딩을 비활성화하는 라이선스 규칙이 있더라도 PDF 문서에 글꼴을 임베드할 수 있습니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/)가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 로드 작업이 계속되지만, 사용자가 Abort를 반환할 경우 로드 작업은 중단되어야 합니다. |

## 예제

다음 예제는 XPS 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XPS File.
	string xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf");

	// Initialize XpsLoadOptions	
	XpsLoadOptions xpsLoadOptions = new XpsLoadOptions();
		
	using (Document pdfDocument = new Document(xpsFile, xpsLoadOptions)){
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XPS File.
    Dim xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf")
 
    ' Initialize XpsLoadOptions
    Dim xpsLoadOptions As XpsLoadOptions = New XpsLoadOptions()
 
    Using pdfDocument As Document = New Document(xpsFile, xpsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 인터페이스 [IPipelineOptions](../ipipelineoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)