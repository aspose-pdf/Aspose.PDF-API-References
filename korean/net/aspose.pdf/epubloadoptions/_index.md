---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubLoadOptions 클래스. PDF 문서로 EPUB 파일을 로드/가져오기 위한 옵션을 포함합니다.
type: docs
weight: 4050
url: /ko/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions 클래스

PDF 문서로 EPUB 파일을 로드/가져오기 위한 옵션을 포함합니다.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | EPUB 파일을 PDF 문서로 변환하기 위한 기본 로드 옵션을 생성합니다. 기본 PDF 페이지 크기 - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | 지정된 페이지 크기로 로드 옵션을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Epub 문서를 열 때 적용할 사용자 정의 Css를 가져오거나 설정합니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 비활성화하는 플래그를 가져오거나 설정합니다. `true`일 때, 이 글꼴의 라이선스에 의해 금지된 글꼴로 작업을 수행할 수 있도록 허용합니다. 예를 들어, 이 글꼴에 대한 임베딩을 비활성화하는 라이선스 규칙이 있더라도 PDF 문서에 글꼴을 임베드할 수 있도록 허용합니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/)가 설명하는 파일 형식을 나타냅니다. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | 여백 정보를 나타내는 객체에 대한 참조를 가져옵니다. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | 가져오기 위한 출력 페이지 크기를 가져오거나 설정합니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 로드 작업이 계속되지만, 사용자가 Abort를 반환할 경우 로드 작업은 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | 여백 영역의 사용 모드를 나타냅니다 - 가져온 문서의 CSS와 관련된 여백 사용 지침(있는 경우)의 처리를 정의합니다. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | 주의! 기능이 구현되었지만 샘플 문서에서 OSHARED 계층의 차단 문제로 인해 아직 공개 API에 추가되지 않았습니다. 변환 중 페이지 크기 사용 모드를 나타냅니다. 형식(HTML, EPUB 등)은 일반적으로 플로트 디자인을 가지므로 필요한 페이지 크기에 맞출 수 있습니다. 그러나 때때로 콘텐츠가 지정된 수평 위치나 크기를 가지고 있어 필요한 페이지 크기에 콘텐츠를 배치할 수 없습니다. 이러한 경우, 결과 PDF 문서의 초기 페이지 크기에 맞지 않는 콘텐츠 크기일 때 어떻게 해야 하는지를 정의할 수 있습니다. |

## 예제

다음 예제는 EPUB 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)