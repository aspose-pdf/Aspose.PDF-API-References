---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptions 클래스. Doc 형식으로 내보내기 위한 저장 옵션
type: docs
weight: 3750
url: /ko/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions 클래스

Doc 형식으로 내보내기 위한 저장 옵션

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | 단락 또는 줄 바꿈 사용 |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | 배치 변환이 소스 및 대상 형식 쌍에 적용 가능한 경우 배치 크기를 정의합니다. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps 페이지를 준비하는 동안 글꼴 글리프가 캐시될지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 소비가 증가합니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Type3 글꼴에 대한 변환을 가져오거나 설정합니다. Type 3 글꼴에서는 글리프가 그래픽 연산자의 스트림으로 정의됩니다. 이는 DOC/DOCX 출력에서 텍스트 대신 이미지를 보게 됨을 의미합니다. 이 플래그를 true로 설정하면 Type3 글꼴을 TTF로 변환하여 결과 파일에서 텍스트를 얻을 수 있습니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 하위 레이어가 있는 PDF 문서에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | 출력 형식 |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | 변환된 이미지의 X 해상도. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | 변환된 이미지의 Y 해상도. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | 이 매개변수는 텍스트 줄을 단락으로 그룹화하는 데 사용됩니다. 두 개의 상대 텍스트 줄 사이의 최대 거리를 결정합니다. 텍스트 줄 높이의 백분율로 지정됩니다. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | 메모리 저장 모드에서 변환할 때 임시 데이터를 저장할 경로(파일 이름 또는 디렉터리 이름)를 정의합니다. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | 인식 모드. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | 글머리 기호 인식을 활성화합니다. |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | PDF에서 단어는 독립적으로 글자나 음절을 인쇄하여 표현될 수 있습니다. 따라서 단어를 감지하기 위해서는 실제로 단어인 독립 문자 그룹을 감지해야 할 때가 있습니다. 이 설정은 소스 PDF에서 단어 인식 중 단어 사이의 거리로 처리해야 하는 텍스트 요소(문자, 음절) 사이의 간격을 정의합니다. (문자 사이에 최소한 이 너비의 빈 공간이 존재하면 텍스트 요소가 서로 다른 단어에 속함을 의미합니다). 글꼴 크기에 정규화되어 있으며 - 1.0은 예상 단어의 글꼴 크기의 100%를 의미합니다. 주의! 이 값은 소스 PDF에 최적 값을 계산할 수 없는 특정 드물게 사용되는 글꼴이 포함된 경우에만 사용됩니다. 따라서 대다수의 경우 이 매개변수는 결과 문서에 아무런 영향을 미치지 않습니다. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | 글꼴 재저장 절차를 가져오거나 설정합니다. true로 설정하면 이전 글꼴 속성의 영향을 피하기 위해 모든 페이지에서 글꼴을 다시 로드하고 새로 생성된 글꼴을 처음부터 로드합니다. 성능을 개선하려면 이 옵션을 false로 설정하십시오. 기본값은 true입니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만 사용자가 Abort를 반환할 수도 있으며 이 경우 저장 작업이 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | 이 핸들러는 변환 진행 이벤트를 처리하는 데 사용할 수 있습니다. 예를 들어 진행률 표시줄이나 처리된 페이지의 현재 양에 대한 메시지를 표시하는 데 사용할 수 있습니다. 진행률을 콘솔에 표시하는 핸들러 코드의 예는 다음과 같습니다. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 여러 스레드에서 페이지를 처리합니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF에는 서로 인접한 여러 동일한 타일 배경 이미지로 구성된 배경 이미지(페이지 또는 테이블 셀)가 포함됩니다. 이 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지의 부분 사이에 가시적인 경계를 생성합니다. 이는 이미지 가장자리 부드럽게 처리하는 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 문서에 동일한 배경 이미지의 부분 사이에 가시적인 경계가 포함된 것처럼 보이면 이 설정을 사용하여 원하지 않는 효과를 제거하십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 저하시킵니다. 따라서 정말 필요한 경우에만 이 옵션을 사용하십시오. |

### 예제

다음 예제는 PDF 파일을 DOC 또는 DOCX 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### 참조

* 클래스 [UnifiedSaveOptions](../unifiedsaveoptions/)
* 인터페이스 [IPipelineOptions](../ipipelineoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)