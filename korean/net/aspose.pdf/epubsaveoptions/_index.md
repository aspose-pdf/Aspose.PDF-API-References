---
title: Class EpubSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptions 클래스. EPUB 형식으로 내보내기 위한 저장 옵션
type: docs
weight: 4060
url: /ko/net/aspose.pdf/epubsaveoptions/
---
## EpubSaveOptions 클래스

EPUB 형식으로 내보내기 위한 저장 옵션

```csharp
public class EpubSaveOptions : UnifiedSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [EpubSaveOptions](epubsaveoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | APS 페이지를 준비하는 동안 글꼴 글리프를 캐시할지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 소비를 증가시킵니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 이 속성은 OCR 하위 레이어가 있는 PDF 문서에서 이미지 또는 텍스트를 추출하는 기능을 활성화합니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식입니다. |
| [Title](../../aspose.pdf/epubsaveoptions/title/) { get; set; } | EPUB 문서 제목을 가져오거나 설정합니다. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환할 경우 저장 작업은 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [ContentRecognitionMode](../../aspose.pdf/epubsaveoptions/contentrecognitionmode/) | 일반적으로 고정 레이아웃을 가진 PDF 파일이 변환될 때, 변환 엔진은 원래 문서 작성자의 의도를 복원하고 흐름 레이아웃으로 결과를 생성하기 위해 그룹화 및 다단계 분석을 수행하려고 합니다. 이 속성은 콘텐츠 인식의 바람직한 방법을 위해 변환을 조정합니다. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 여러 스레드에서 페이지를 처리합니다. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 때때로 PDF에는 여러 개의 동일한 타일 배경 이미지로 구성된 배경 이미지(페이지 또는 테이블 셀)가 포함됩니다. 이 경우 대상 형식의 렌더러(예: DOCS 형식의 MsWord)는 때때로 배경 이미지의 부분 사이에 눈에 보이는 경계를 생성합니다. 이는 이미지 가장자리 부드럽게 처리하는 기술이 Acrobat Reader와 다르기 때문입니다. 내보낸 문서에 동일한 배경 이미지의 부분 사이에 눈에 보이는 경계가 포함된 것처럼 보인다면, 이 설정을 사용하여 원하지 않는 효과를 제거해 보십시오. 주의! 이 품질 최적화는 일반적으로 변환 속도를 크게 저하시킵니다. 따라서 정말 필요한 경우에만 이 옵션을 사용하십시오. |

## 예제

다음 예제는 PDF 파일을 EPUB 파일로 변환하는 방법을 보여줍니다.

```csharp
	[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf");

	// The path to output EPUB File.
	var epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub");
		
	using (Document pdfDocument = new Document(pdfFile))
	{

		// Initialize EpubSaveOptions 	
		EpubSaveOptions saveOptions = new EpubSaveOptions();
		
		// Save EPUB file
		pdfDocument.Save(epubFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf")

    ' The path to output EPUB File.
    Dim epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize EpubSaveOptions    
        Dim saveOptions As EpubSaveOptions = New EpubSaveOptions()
 
        ' Save EPUB file
        pdfDocument.Save(epubFile, saveOptions)
    End Using
```

### 참조

* 클래스 [UnifiedSaveOptions](../unifiedsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)