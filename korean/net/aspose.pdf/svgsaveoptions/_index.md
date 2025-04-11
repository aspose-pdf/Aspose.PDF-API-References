---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptions 클래스. SVG 형식으로 내보내기 위한 저장 옵션
type: docs
weight: 10230
url: /ko/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions 클래스

SVG 형식으로 내보내기 위한 저장 옵션

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | APS 페이지를 준비하는 동안 글꼴 글리프를 캐시할지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 소비를 증가시킵니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 서브 레이어가 있는 PDF 문서에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만 사용자는 Abort를 반환할 수도 있으며, 이 경우 저장 작업은 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | 출력이 하나의 zip 아카이브로 생성될지 여부를 지정합니다. 다중 페이지 소스 문서의 SVG 파일 이름 규칙을 보려면 'TreatTargetFileNameAsDirectory' 옵션에 대한 주석을 참조하십시오. 이 규칙은 압축된 출력 파일 세트에도 적용됩니다. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | 이 필드는 저장된 SVG에 삽입된 참조 외부 이미지 파일(예: 삽입된 BMP 또는 JPEG)의 사용자 정의 처리를 위한 변환 중에 사용해야 하는 저장 전략을 포함할 수 있습니다. 이 전략은 리소스를 처리하고 생성된 SVG에서 저장된 리소스의 바람직한 URI를 나타내는 문자열을 반환해야 합니다. 어떤 이유로 이 파일에 대한 처리가 변환기 코드 자체에서 수행되어야 하는 경우, 사용자 정의 코드에서 'imageSavingInfo' 매개변수의 변수에 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스의 처리를 위한 모든 필요한 단계가 외부 사용자 정의 코드 없이 변환기 자체에서 수행되어야 함을 신호합니다. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 여러 스레드에서 페이지를 처리합니다. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | 출력 문서를 타이포그래픽 포인트에서 픽셀로 스케일링할지 여부를 지정합니다. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | 이 옵션은 요청된 출력 파일 대신 요청된 출력 파일과 동일한 이름의 대상 디렉터리가 생성될지 여부를 정의합니다(아직 없는 경우). 그렇다면 해당 디렉터리는 모든 출력 SVG 페이지 이미지를 포함합니다(아래 설명된 대로). 그렇지 않으면 첫 번째 페이지를 제외한 페이지의 출력 파일이 요청된 디렉터리에 정확히 생성되며, 파일 이름에는 페이지 번호에 의해 정의된 접미사 _[2...n]이 포함됩니다. 예를 들어 출력 파일 "C:\AsposeTests\output.svg"를 정의하고 출력에 여러 SVG 페이지 파일이 포함되면 페이지 파일은 "C:\AsposeTests\" 디렉터리에도 생성되며 이름은 'output.svg', 'output_2.svg', 'output_3.svg' 등입니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF에는 서로 인접한 여러 동일한 타일 배경 이미지로 구성된 배경 이미지(페이지 또는 테이블 셀)가 포함됩니다. 이러한 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지의 부분 사이에 가시적인 경계를 생성합니다. 이는 이미지 가장자리 부드럽게 처리하는 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 문서에 동일한 배경 이미지의 부분 사이에 가시적인 경계가 포함된 것처럼 보이면 이 설정을 사용하여 원하지 않는 효과를 제거하십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 저하시킵니다. 따라서 정말 필요한 경우에만 이 옵션을 사용하십시오. |

## 예제

다음 예제는 PDF 파일을 SVG 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### 참조

* 클래스 [UnifiedSaveOptions](../unifiedsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)