---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlLoadOptions 클래스. PDF 문서로 HTML 파일을 로드/가져오기 위한 옵션을 나타냅니다.
type: docs
weight: 5530
url: /ko/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions 클래스

PDF 문서로 HTML 파일을 로드/가져오기 위한 옵션을 나타냅니다.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | 빈 기본 경로로 HTML을 PDF 문서로 변환하기 위한 로드 옵션을 생성합니다. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | 정의된 기본 경로로 HTML을 PDF 문서로 변환하기 위한 로드 옵션을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | HTML 파일의 기본 경로/URL입니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 비활성화하는 플래그를 가져오거나 설정합니다. `true`일 때, 이 글꼴의 라이선스에 의해 금지된 글꼴로 작업을 수행할 수 있도록 허용합니다. 예를 들어, 이 글꼴에 대한 라이선스 규칙이 포함을 비활성화하더라도 PDF 문서에 글꼴을 포함할 수 있습니다. 기본값은 `false`입니다. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | 렌더링 중에 사용되는 가능한 미디어 유형을 가져오거나 설정합니다. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | 구문 분석 시 이 문서에 사용되는 인코딩을 지정하는 속성을 가져오거나 설정합니다. 이 속성이 null이면 인코딩은 문서 문자 집합 속성에서 결정됩니다. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | 결과 문서에 글꼴 포함 여부를 가져오거나 설정합니다. |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | CSS에서 정의된 @page 규칙이 PageInfo에서 정의된 값을 덮어쓴다는 플래그를 가져오거나 설정합니다. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | 모든 문서를 단일 페이지로 렌더링할지 여부를 가져오거나 설정합니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/)가 설명하는 파일 형식을 나타냅니다. |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | 문서 페이지 정보를 가져오거나 설정합니다. |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | 레이아웃 옵션을 가져오거나 설정합니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속되지만, 사용자가 Abort를 반환할 경우 Load 작업은 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | 때때로 외부 리소스(예: 이미지 또는 CSS)의 내부 로더 사용을 피하고 요청된 리소스를 어딘가에서 가져오는 사용자 정의 메서드를 제공해야 할 필요가 있습니다. 예를 들어, Aspose.PDF를 클라우드에서 사용할 때 참조된 파일에 직접 접근할 수 없으므로, 이 경우 특별한 메서드에 넣은 사용자 정의 코드를 사용해야 하며, 해당 메서드를 참조하는 위임이 이 속성에 할당되어야 합니다. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | HTML에서 참조된 외부 데이터 로드에 자격 증명이 필요한 경우, 이 매개변수에 자격 증명을 넣을 수 있습니다. 이 자격 증명은 외부 리소스를 로드하는 동안 사용됩니다. |

## 예제

다음 예제는 HTML 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)