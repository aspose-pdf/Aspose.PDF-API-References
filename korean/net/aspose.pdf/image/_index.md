---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Image 클래스. 이미지를 나타냅니다.
type: docs
weight: 5860
url: /ko/net/aspose.pdf/image/
---
## 이미지 클래스

이미지를 나타냅니다.

```csharp
public sealed class Image : BaseParagraph
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Image](image/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | 압축되지 않은 이미지 바이트를 가져오거나 설정합니다. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | 이미지 비트맵 크기를 가져옵니다. |
| [File](../../aspose.pdf/image/file/) { get; set; } | 이미지 파일을 가져오거나 설정합니다. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | 이미지 파일 유형을 가져오거나 설정합니다. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | 이미지 높이를 가져오거나 설정합니다. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | 이미지 너비를 가져오거나 설정합니다. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 단락의 수평 정렬을 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( PDF 생성기용). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | 이미지 비율을 가져오거나 설정합니다. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | 이미지 스트림을 가져오거나 설정합니다. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | 생성 중에 이미지가 해상도를 사용하는지 여부를 나타내는 bool 값을 가져오거나 설정합니다. |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | 이미지가 흑백으로 강제 설정되는지 여부를 나타내는 bool 값을 가져오거나 설정합니다. CCITT 하위 형식의 TIFF 이미지가 사용되는 경우 이 속성은 true로 설정해야 합니다. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지 여부를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지 여부를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다(PDF 생성용) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | 이미지의 제목을 나타내는 문자열 값을 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | 이미지를 복제합니다. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | 이미지의 MIME 유형을 반환합니다. |

## 예제

다음 예제는 이미지를 PDF 파일로 변환하는 방법을 보여줍니다(PNG, JPEG, GIF, BMP 또는 기타 이미지 형식).

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your image (bmp, png, gif, jpeg, etc.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initialize empty PDF document
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Load sample image file
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Save output PDF document
	  pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir = "YOUR_DATA_DIRECTORY"

    ' The path to your image (bmp, png, gif, jpeg, etc.) File.
    Dim imageFile = Path.Combine(dataDir, "Image-to-PDF.png")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf")
 
    'Initialize empty PDF document
    Using pdfDocument As Document = New Document()
        pdfDocument.Pages.Add()
        Dim image As Image = New Image()
 
        ' Load sample image file
        image.File = imageFile
        pdfDocument.Pages(1).Paragraphs.Add(image)
 
        ' Save output PDF document
        pdfDocument.Save(pdfFile)
    End Using
```

### 참조

* 클래스 [BaseParagraph](../baseparagraph/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)