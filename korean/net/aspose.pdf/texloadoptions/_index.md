---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXLoadOptions 클래스. PDF 문서로 TeX 파일을 로드/가져오기 위한 옵션을 나타냅니다.
type: docs
weight: 10370
url: /ko/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions 클래스

PDF 문서로 TeX 파일을 로드/가져오기 위한 옵션을 나타냅니다.

```csharp
public class TeXLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | 연도, 월, 일 및 시간과 같은 날짜/시간 원시 값에 대한 특정 값을 가져오거나 설정합니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 비활성화하는 플래그를 가져오거나 설정합니다. `true`일 때, 이 글꼴의 라이선스에 의해 금지된 글꼴로 작업을 수행할 수 있도록 허용합니다. 예를 들어, 이 글꼴에 대한 임베딩이 금지된 경우에도 PDF 문서에 글꼴을 임베딩할 수 있습니다. 기본값은 `false`입니다. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | TeX 입력 디렉토리를 가져오거나 설정합니다. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | 작업의 이름을 가져오거나 설정합니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/)가 설명하는 파일 형식을 나타냅니다. |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | 모든 글꼴에서 리가처를 취소하는 플래그를 가져오거나 설정합니다. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | TeX 출력 디렉토리를 가져오거나 설정합니다. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | 수학 공식을 래스터화할 수 있도록 허용하는 플래그를 가져오거나 설정합니다. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | 입력 TeX 파일에 참조가 있는 경우와 같이 TeX 작업을 두 번 실행해야 하는지를 나타내는 플래그를 가져오거나 설정합니다. 일반적으로 이 동작은 엔진이 조판 과정에서 일부 데이터를 수집하고 이를 보조 파일에 저장할 때 유용합니다. 첫 번째 실행에서 모든 작업이 이루어지고 두 번째 실행에서 엔진이 그 데이터를 사용하는 방식입니다. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | TeX에서 요구하는 입력 디렉토리를 가져오거나 설정합니다. 필수 입력은 주 .tex 파일에 포함된 파일로, 내장 지원이 없는 패키지 등을 포함합니다. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | 콘솔에 터미널 출력을 표시할지를 나타내는 플래그를 가져오거나 설정합니다. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | 출력 파일에서 글꼴을 서브셋할지를 나타내는 플래그를 가져오거나 설정합니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환할 경우 Load 작업은 중단되어야 합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | TeX 로드 및 컴파일 결과를 가져옵니다 - 모든 것이 원활하게 진행되었는지 또는 주석/오류가 있었는지 확인합니다. |

## 예제

다음 예제는 TeX 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)