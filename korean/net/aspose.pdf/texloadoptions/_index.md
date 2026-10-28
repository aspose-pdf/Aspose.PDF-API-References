---
title: "TeXLoadOptions 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.TeXLoadOptions 클래스. TeX 파일을 PDF 문서로 로드/임포트하기 위한 옵션을 나타냅니다."
type: docs
weight: 10550
url: /ko/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

TeX 파일을 PDF 문서에 로드/임포트하기 위한 옵션을 나타냅니다.

```csharp
public class TeXLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | 연도, 월, 일 및 시간과 같은 날짜/시간 기본형에 대한 특정 값을 가져오거나 설정합니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 해제하는 플래그를 가져오거나 설정합니다. `true`인 경우 해당 글꼴의 라이선스에서 금지된 작업을 수행할 수 있게 하며, 예를 들어 라이선스 규정이 임베딩을 금지하더라도 글꼴을 PDF 문서에 삽입할 수 있습니다. 기본값은 `false`입니다. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | TeX 입력 디렉터리를 가져오거나 설정합니다. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | 작업 이름을 가져오거나 설정합니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `[`LoadOptions`](../loadoptions/)`가 설명하는 파일 형식을 나타냅니다. |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | 모든 글꼴에서 합자를 취소하는 플래그를 가져오거나 설정합니다. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | TeX 출력 디렉터리를 가져오거나 설정합니다. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | 수학 수식을 래스터화하도록 허용하는 플래그를 가져오거나 설정합니다. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | 입력 TeX 파일에 참조가 있는 경우와 같이 TeX 작업을 두 번 실행해야 하는지 여부를 나타내는 플래그를 가져오거나 설정합니다. 일반적으로 이 동작은 엔진이 조판 과정에서 데이터를 수집하여 첫 번째 실행 시 보조 파일에 저장하고, 두 번째 실행 시 해당 데이터를 사용해야 할 때 유용합니다. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | TeX 필수 입력 디렉터리를 가져오거나 설정합니다. 필수 입력은 메인 .tex 파일에 포함되는 파일들(예: 내장 지원이 없는 패키지)입니다. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | 콘솔에 터미널 출력을 표시할지 여부를 나타내는 플래그를 가져오거나 설정합니다. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | 출력 파일에서 글꼴을 서브셋팅할지 여부를 나타내는 플래그를 가져오거나 설정합니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환하면 Load 작업이 중단됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | TeX 로드 및 컴파일 결과를 가져옵니다 – 모든 작업이 원활히 진행되었는지, 혹은 의견/오류가 있었는지 확인합니다. |

## 예제

다음 예제는 TeX 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// 문서 디렉터리 경로.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// TeX 파일의 경로입니다.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// 출력 PDF 파일 경로.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// TeXLoadOptions 초기화
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// PDF 파일 저장
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

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


