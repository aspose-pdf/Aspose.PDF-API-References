---
title: "클래스 EpubLoadOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.EpubLoadOptions 클래스. EPUB 파일을 PDF 문서로 로드/임포트하기 위한 옵션을 포함합니다."
type: docs
weight: 4170
url: /ko/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

pdf 문서에 EPUB 파일을 로드/임포트하기 위한 옵션을 포함합니다.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | EPUB 파일을 PDF 문서로 변환하기 위한 기본 로드 옵션을 생성합니다. 기본 PDF 페이지 크기 - A4 300dpi 2480 × 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | 지정된 페이지 크기로 로드 옵션을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Epub 문서를 열 때 적용할 사용자 정의 Css를 가져오거나 설정합니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 해제하는 플래그를 가져오거나 설정합니다. `true`인 경우 해당 글꼴의 라이선스에서 금지된 작업을 수행할 수 있게 하며, 예를 들어 라이선스 규정이 임베딩을 금지하더라도 글꼴을 PDF 문서에 삽입할 수 있습니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `[`LoadOptions`](../loadoptions/)`가 설명하는 파일 형식을 나타냅니다. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | 여백 정보를 나타내는 객체에 대한 참조를 가져옵니다. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | 가져오기에 대한 출력 페이지 크기를 가져오거나 설정합니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환하면 Load 작업이 중단됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | 여백 영역 사용 모드를 나타냅니다. 가져온 문서의 CSS에 있는 여백 사용과 관련된 지시문(있는 경우)의 처리 방식을 정의합니다. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | 주의! 이 기능은 구현되었지만 샘플 문서에서 OSHARED 레이어의 차단 이슈가 발견되어 아직 공개 API에 반영되지 않았습니다. 변환 중 페이지 크기 사용 모드를 나타냅니다. HTML, EPUB 등과 같은 포맷은 일반적으로 유동적인 디자인을 가지고 있어 필요한 페이지 크기에 맞출 수 있습니다. 그러나 경우에 따라 콘텐츠에 지정된 가로 위치나 크기가 있어 필요한 페이지 크기에 맞추기 어려울 수 있습니다. 이러한 경우(예: 콘텐츠 크기가 결과 PDF 문서의 초기 페이지 크기에 맞지 않을 때) 어떻게 처리할지 정의할 수 있습니다. |

## 예제

다음 예제는 EPUB 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// 문서 디렉터리 경로.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// EPUB 파일 경로.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// 출력 PDF 파일 경로.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// EpubLoadOptions 초기화 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// PDF 파일 저장
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

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


