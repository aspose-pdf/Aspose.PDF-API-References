---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfSaveOptions 클래스. Pdf 형식으로 내보내기 위한 저장 옵션
type: docs
weight: 8430
url: /ko/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions 클래스

Pdf 형식으로 내보내기 위한 저장 옵션

```csharp
public class PdfSaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps 페이지를 준비하는 동안 글꼴 글리프가 캐시될지 여부를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 소비를 증가시킵니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | 컴퓨터에 없는 글꼴에 대해 기본적으로 사용되는 글꼴 이름입니다. PDF 문서에 포함된 글꼴이 문서 자체 및 장치에서 사용할 수 없는 경우, API는 이 글꼴을 기본 글꼴로 교체합니다(장치에서 [`DefaultFontName`](./defaultfontname/) 글꼴이 발견된 경우). |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식입니다. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | 임시 파일의 경로입니다. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환할 수도 있으며, 이 경우 저장 작업은 중단되어야 합니다. |

## 예제

다음 예제는 PDF를 저장할 때 기본 글꼴 이름을 설정하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Load an existing PDF document with missing font
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Specify Default Font Name
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### 참조

* 클래스 [SaveOptions](../saveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)