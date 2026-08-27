---
title: "클래스 DocSaveOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.DocSaveOptions 클래스. Doc 형식으로 내보내기 위한 저장 옵션"
type: docs
weight: 3870
url: /ko/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

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
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | 소스 및 대상 형식 쌍에 배치 변환이 적용되는 경우 배치 크기를 정의합니다. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps 페이지를 준비하는 동안 글꼴 글리프가 캐시될지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 사용량이 증가합니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Type3 글꼴에 대한 변환을 가져오거나 설정합니다. Type 3 글꼴에서는 글리프가 그래픽 연산자 스트림으로 정의됩니다. 이는 DOC/DOCX 출력에서 텍스트 대신 이미지가 표시된다는 의미입니다. 이 플래그를 true로 설정하면 Type3 글꼴을 TTF로 변환하여 결과 파일에 텍스트를 얻을 수 있습니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 하위 레이어를 사용하여 PDF Document에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | 출력 형식 |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | 변환된 이미지 X 해상도. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | 변환된 이미지 Y 해상도. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | 이 매개변수는 텍스트 줄을 단락으로 그룹화하는 데 사용됩니다. 두 개의 상대 텍스트 줄 사이의 거리 허용 범위를 결정합니다. 텍스트 줄 높이의 백분율(백분율 단위)으로 지정됩니다. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | 메모리 저장 모드로 변환할 때 임시 데이터를 보관할 경로(파일 이름 또는 디렉터리 이름)를 정의합니다. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | 인식 모드. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | 글머리 기호 인식을 켭니다 |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | PDF에서는 단어가 각 글자나 음절을 독립적으로 출력하는 연산자를 사용해 내부적으로 표현될 수 있습니다. 따라서 단어를 감지하려면 실제로는 단어인 독립 문자 그룹을 찾아야 할 때가 있습니다. 이 설정은 원본 PDF에서 단어를 인식할 때 텍스트 요소(글자, 음절) 사이의 간격을 단어 간 거리로 간주해야 하는 공백 너비를 정의합니다. (글자 사이에 최소 이 너비만큼의 빈 공간이 있으면 해당 텍스트 요소가 다른 단어에 속한다는 의미입니다). 이 값은 글꼴 크기에 정규화되며, 1.0은 해당 단어 글꼴 크기의 100%를 의미합니다. 주의! 이 옵션은 최적값을 글꼴에서 계산할 수 없는 특정 희귀 글꼴이 포함된 경우에만 사용됩니다. 따라서 대부분의 경우 이 매개변수는 결과 문서에 영향을 주지 않습니다. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | 글꼴을 다시 저장하는 절차를 가져오거나 설정합니다. true로 설정하면 이전 글꼴 속성의 영향을 피하기 위해 각 페이지에서 글꼴을 다시 로드하고 새로 만든 글꼴을 처음부터 로드합니다. 성능을 향상시키려면 이 옵션을 false로 설정하십시오. 기본값은 true입니다; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | 이 핸들러는 변환 진행 이벤트를 처리하는 데 사용할 수 있습니다. 예를 들어 진행 표시줄을 표시하거나 현재 처리된 페이지 수에 대한 메시지를 보여줄 수 있습니다. 콘솔에 진행 상황을 표시하는 핸들러 코드 예시는 다음과 같습니다: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 몇 개의 스레드에서 페이지를 처리합니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF는 페이지 또는 표 셀의 배경 이미지가 여러 개의 동일한 타일 배경 이미지를 서로 가깝게 배치하여 구성됩니다. 이러한 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 배경 이미지 부분 사이에 눈에 보이는 경계선을 생성할 수 있으며, 이는 이미지 가장자리 부드럽게 처리(안티앨리어싱) 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 Document에 동일한 배경 이미지 부분 사이에 이러한 눈에 보이는 경계가 나타나는 경우, 원하지 않는 효과를 없애기 위해 이 설정을 사용해 보십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 늦추므로, 정말 필요할 때만 이 옵션을 사용하십시오. |

### 예제

다음 예제는 PDF 파일을 DOC 또는 DOCX 파일로 변환하는 방법을 보여줍니다

```csharp
[C#]
	// 문서 디렉터리 경로.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF File의 경로입니다.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// DOC 또는 DOCX 파일을 출력할 경로.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// 인식 모드를 Flow로 설정
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// 수평 근접성을 2.5로 설정
			RelativeHorizontalProximity = 2.5f,
			// 변환 과정에서 글머리 기호를 인식하도록 값을 활성화
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

### 또 보기

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


