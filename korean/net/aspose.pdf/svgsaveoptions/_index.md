---
title: "클래스 SvgSaveOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.SvgSaveOptions 클래스. SVG 형식으로 내보내기 위한 저장 옵션"
type: docs
weight: 10410
url: /ko/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

SVG 형식으로 내보내기 위한 저장 옵션입니다.

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps 페이지를 준비하는 동안 글꼴 글리프가 캐시될지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 사용량이 증가합니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 하위 레이어를 사용하여 PDF Document에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | 출력이 하나의 zip 아카이브로 생성될지 여부를 지정합니다. 다중 페이지 소스 문서의 페이지별 SVG 파일 이름 규칙은 'TreatTargetFileNameAsDirectory' 옵션에 대한 주석을 참조하십시오. 이 규칙은 압축된 출력 파일 세트에도 적용됩니다. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | 이 필드는 변환 중에 생성된 외부 이미지 파일(예: 임베드된 BMP 또는 JPEG)의 맞춤형 처리를 위해 사용해야 하는 저장 전략을 포함할 수 있습니다(존재하는 경우). 해당 전략은 리소스를 처리하고 생성된 SVG에서 저장된 리소스의 원하는 URI를 나타내는 문자열을 반환해야 합니다. 어떤 이유로 이 파일 또는 저 파일에 대한 처리를 변환기 코드 자체에서 수행해야 하고 사용자 정의 코드에서 수행하지 않아야 하는 경우, 사용자 정의 코드에서 'imageSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에 해당 리소스 처리를 외부 사용자 정의 코드 없이 변환기 자체에서 수행해야 함을 알립니다. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 몇 개의 스레드에서 페이지를 처리합니다. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | 출력 문서를 타이포그래픽 포인트에서 픽셀로 스케일링할지 여부를 지정합니다. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | 이 옵션은 요청된 출력 파일 자체 대신 요청된 출력 파일과 동일한 이름의 대상 디렉터리가 (존재하지 않을 경우) 생성될지 여부를 정의합니다. 이렇게 하면 해당 디렉터리에 모든 페이지의 출력 SVG 이미지가 포함됩니다(아래에 설명된 대로). '아니오'인 경우, 첫 번째 페이지를 제외한 페이지들의 출력 파일은 메인 출력 파일과 동일한 디렉터리에 생성되지만 파일 이름에 _[2...n] 접미사가 붙으며, 이는 페이지 번호에 따라 정의됩니다. 예를 들어 출력 파일을 "C:\AsposeTests\output.svg" 로 지정하고 여러 페이지의 SVG 파일이 생성되는 경우, 페이지 파일들은 "C:\AsposeTests\" 디렉터리에도 생성되어 'output.svg', 'output_2.svg', 'output_3.svg' 등과 같은 이름을 갖게 됩니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF는 페이지 또는 표 셀의 배경 이미지가 여러 개의 동일한 타일 배경 이미지를 서로 가깝게 배치하여 구성됩니다. 이러한 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 배경 이미지 부분 사이에 눈에 보이는 경계선을 생성할 수 있으며, 이는 이미지 가장자리 부드럽게 처리(안티앨리어싱) 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 Document에 동일한 배경 이미지 부분 사이에 이러한 눈에 보이는 경계가 나타나는 경우, 원하지 않는 효과를 없애기 위해 이 설정을 사용해 보십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 늦추므로, 정말 필요할 때만 이 옵션을 사용하십시오. |

## 예제

다음 예제는 PDF 파일을 SVG 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// 문서 디렉터리 경로.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF File의 경로입니다.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// 출력 SVG 파일의 경로.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// SvgSaveOptions 초기화	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// SVG 파일 저장
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

### 또 보기

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


