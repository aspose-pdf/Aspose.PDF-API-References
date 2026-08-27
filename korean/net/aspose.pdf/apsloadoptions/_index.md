---
title: "ApsLoadOptions 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.ApsLoadOptions 클래스. 이 클래스는 APS 로드 옵션을 설명합니다."
type: docs
weight: 2850
url: /ko/net/aspose.pdf/apsloadoptions/
---
## ApsLoadOptions class

클래스는 aps 로드 옵션을 설명합니다.

```csharp
public class ApsLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ApsLoadOptions](apsloadoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 해제하는 플래그를 가져오거나 설정합니다. `true`인 경우 해당 글꼴의 라이선스에서 금지된 작업을 수행할 수 있게 하며, 예를 들어 라이선스 규정이 임베딩을 금지하더라도 글꼴을 PDF 문서에 삽입할 수 있습니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `[`LoadOptions`](../loadoptions/)`가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환하면 Load 작업이 중단됩니다. |

## 예제

다음 예제는 APS 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// 문서 디렉터리 경로.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// APS 파일의 경로입니다.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// 출력 PDF 파일 경로.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// ApsLoadOptions 초기화 	
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// ApsLoadOptions로 Document 초기화     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// PDF 파일 저장
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your APS File.
    Dim apsFile = Path.Combine(dataDir, "APS-to-PDF.aps")
	
    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf")
 
    ' Initialize ApsLoadOptions    
    Dim apsLoadOptions As ApsLoadOptions = New ApsLoadOptions()
 
	' Initialize Document wiht ApsLoadOptions
    Using pdfDocument As Document = New Document(apsFile, apsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


